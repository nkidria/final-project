# final-project
!pip install yfinance==0.1.67
!mamba install bs4==4.10.0 -y
!pip install nbformat==4.2.0
Requirement already satisfied: yfinance==0.1.67 in /opt/conda/envs/Python-3.10/lib/python3.10/site-packages (0.1.67)
Requirement already satisfied: pandas>=0.24 in /opt/conda/envs/Python-3.10/lib/python3.10/site-packages (from yfinance==0.1.67) (1.4.3)
Requirement already satisfied: requests>=2.20 in /opt/conda/envs/Python-3.10/lib/python3.10/site-packages (from yfinance==0.1.67) (2.28.1)
Requirement already satisfied: numpy>=1.15 in /opt/conda/envs/Python-3.10/lib/python3.10/site-packages (from yfinance==0.1.67) (1.23.1)
Requirement already satisfied: lxml>=4.5.1 in /opt/conda/envs/Python-3.10/lib/python3.10/site-packages (from yfinance==0.1.67) (4.9.1)
Requirement already satisfied: multitasking>=0.0.7 in /opt/conda/envs/Python-3.10/lib/python3.10/site-packages (from yfinance==0.1.67) (0.0.11)
Requirement already satisfied: python-dateutil>=2.8.1 in /opt/conda/envs/Python-3.10/lib/python3.10/site-packages (from pandas>=0.24->yfinance==0.1.67) (2.8.2)
Requirement already satisfied: pytz>=2020.1 in /opt/conda/envs/Python-3.10/lib/python3.10/site-packages (from pandas>=0.24->yfinance==0.1.67) (2022.1)
Requirement already satisfied: charset-normalizer<3,>=2 in /opt/conda/envs/Python-3.10/lib/python3.10/site-packages (from requests>=2.20->yfinance==0.1.67) (2.0.4)
Requirement already satisfied: urllib3<1.27,>=1.21.1 in /opt/conda/envs/Python-3.10/lib/python3.10/site-packages (from requests>=2.20->yfinance==0.1.67) (1.26.11)
Requirement already satisfied: idna<4,>=2.5 in /opt/conda/envs/Python-3.10/lib/python3.10/site-packages (from requests>=2.20->yfinance==0.1.67) (3.3)
Requirement already satisfied: certifi>=2017.4.17 in /opt/conda/envs/Python-3.10/lib/python3.10/site-packages (from requests>=2.20->yfinance==0.1.67) (2022.12.7)
Requirement already satisfied: six>=1.5 in /opt/conda/envs/Python-3.10/lib/python3.10/site-packages (from python-dateutil>=2.8.1->pandas>=0.24->yfinance==0.1.67) (1.16.0)

                  __    __    __    __
                 /  \  /  \  /  \  /  \
                /    \/    \/    \/    \
███████████████/  /██/  /██/  /██/  /████████████████████████
              /  / \   / \   / \   / \  \____
             /  /   \_/   \_/   \_/   \    o \__,
            / _/                       \_____/  `
            |/
        ███╗   ███╗ █████╗ ███╗   ███╗██████╗  █████╗
        ████╗ ████║██╔══██╗████╗ ████║██╔══██╗██╔══██╗
        ██╔████╔██║███████║██╔████╔██║██████╔╝███████║
        ██║╚██╔╝██║██╔══██║██║╚██╔╝██║██╔══██╗██╔══██║
        ██║ ╚═╝ ██║██║  ██║██║ ╚═╝ ██║██████╔╝██║  ██║
        ╚═╝     ╚═╝╚═╝  ╚═╝╚═╝     ╚═╝╚═════╝ ╚═╝  ╚═╝

        mamba (0.27.0) supported by @QuantStack

        GitHub:  https://github.com/mamba-org/mamba
        Twitter: https://twitter.com/QuantStack

█████████████████████████████████████████████████████████████


Looking for: ['bs4==4.10.0']

[+] 0.0s
opt/ibm/custom-channels/meta-wscloud/linux-64 ━━━━━━━━━━━╸━━━━━━━━   0.0 B  0.0sopt/ibm/custom-channels/meta-wscloud/linux-64       0.0s
opt/ibm/custom-channels/meta-wscloud/noarch         13.0kB @ 125.8MB/s  0.0s
opt/ibm/custom-channels/placebo-20220915-noarch/..  ??.?MB @  ??.?MB/s 0 failed  0.0s
opt/ibm/custom-channels/placebo-20220915-noarch/..   3.6kB @  64.0MB/s  0.0s
[+] 0.1s
pkgs/main/linux-64 ━━━━━━━━━━━━╸━━━━━━━━━━━━   0.0 B /  ??.?MB @  ??.?MB/s  0.1s
pkgs/main/noarch   ━━━━━━━━━╸━━━━━━━━━━━━━━━   0.0 B /  ??.?MB @  ??.?MB/s  0.1spkgs/main/noarch                                              No change
pkgs/main/linux-64                                            No change

Pinned packages:
  - python 3.10.*
  - python 3.10.*
  - widgetsnbextension 3.5.2.*


Transaction

  Prefix: /opt/conda/envs/Python-3.10

  All requested packages already installed

Requirement already satisfied: nbformat==4.2.0 in /opt/conda/envs/Python-3.10/lib/python3.10/site-packages (4.2.0)
Requirement already satisfied: ipython-genutils in /opt/conda/envs/Python-3.10/lib/python3.10/site-packages (from nbformat==4.2.0) (0.2.0)
Requirement already satisfied: jsonschema!=2.5.0,>=2.4 in /opt/conda/envs/Python-3.10/lib/python3.10/site-packages (from nbformat==4.2.0) (4.4.0)
Requirement already satisfied: jupyter-core in /opt/conda/envs/Python-3.10/lib/python3.10/site-packages (from nbformat==4.2.0) (4.11.2)
Requirement already satisfied: traitlets>=4.1 in /opt/conda/envs/Python-3.10/lib/python3.10/site-packages (from nbformat==4.2.0) (5.1.1)
Requirement already satisfied: pyrsistent!=0.17.0,!=0.17.1,!=0.17.2,>=0.14.0 in /opt/conda/envs/Python-3.10/lib/python3.10/site-packages (from jsonschema!=2.5.0,>=2.4->nbformat==4.2.0) (0.18.0)
Requirement already satisfied: attrs>=17.4.0 in /opt/conda/envs/Python-3.10/lib/python3.10/site-packages (from jsonschema!=2.5.0,>=2.4->nbformat==4.2.0) (21.4.0)
import yfinance as yf
import pandas as pd
import requests
from bs4 import BeautifulSoup
import plotly.graph_objects as go
from plotly.subplots import make_subplots
Define Graphing Function
In this section, we define the function make_graph. You don't have to know how the function works, you should only care about the inputs. It takes a dataframe with stock data (dataframe must contain Date and Close columns), a dataframe with revenue data (dataframe must contain Date and Revenue columns), and the name of the stock.

def make_graph(stock_data, revenue_data, stock):
    fig = make_subplots(rows=2, cols=1, shared_xaxes=True, subplot_titles=("Historical Share Price", "Historical Revenue"), vertical_spacing = .3)
    stock_data_specific = stock_data[stock_data.Date <= '2021--06-14']
    revenue_data_specific = revenue_data[revenue_data.Date <= '2021-04-30']
    fig.add_trace(go.Scatter(x=pd.to_datetime(stock_data_specific.Date, infer_datetime_format=True), y=stock_data_specific.Close.astype("float"), name="Share Price"), row=1, col=1)
    fig.add_trace(go.Scatter(x=pd.to_datetime(revenue_data_specific.Date, infer_datetime_format=True), y=revenue_data_specific.Revenue.astype("float"), name="Revenue"), row=2, col=1)
    fig.update_xaxes(title_text="Date", row=1, col=1)
    fig.update_xaxes(title_text="Date", row=2, col=1)
    fig.update_yaxes(title_text="Price ($US)", row=1, col=1)
    fig.update_yaxes(title_text="Revenue ($US Millions)", row=2, col=1)
    fig.update_layout(showlegend=False,
    height=900,
    title=stock,
    xaxis_rangeslider_visible=True)
    fig.show()
Question 1: Use yfinance to Extract Stock Data
Using the Ticker function enter the ticker symbol of the stock we want to extract data on to create a ticker object. The stock is Tesla and its ticker symbol is TSLA.

Tesla = yf.Ticker("TSLA")
Using the ticker object and the function history extract stock information and save it in a dataframe named tesla_data. Set the period parameter to max so we get information for the maximum amount of time.

tesla_data = Tesla.history(period="max")
Reset the index using the reset_index(inplace=True) function on the tesla_data DataFrame and display the first five rows of the tesla_data dataframe using the head function. Take a screenshot of the results and code from the beginning of Question 1 to the results below.

tesla_data.head(5)
Date	Open	High	Low	Close	Volume	Dividends	Stock Splits
0	2010-06-29	1.266667	1.666667	1.169333	1.592667	281494500	0	0.0
1	2010-06-30	1.719333	2.028000	1.553333	1.588667	257806500	0	0.0
2	2010-07-01	1.666667	1.728000	1.351333	1.464000	123282000	0	0.0
3	2010-07-02	1.533333	1.540000	1.247333	1.280000	77097000	0	0.0
4	2010-07-06	1.333333	1.333333	1.055333	1.074000	103003500	0	0.0
Question 2: Use Webscraping to Extract Tesla Revenue Data
Use the requests library to download the webpage https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/revenue.htm Save the text of the response as a variable named html_data.

url = "https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/revenue.htm"
data  = requests.get(url).text
html_data = data
Parse the html data using beautiful_soup.

soup = BeautifulSoup(data, 'html.parser')
Using BeautifulSoup or the read_html function extract the table with Tesla Quarterly Revenue and store it into a dataframe named tesla_revenue. The dataframe should have columns Date and Revenue.

Click here if you need help locating the table
soup.find_all("tbody")[1]
tesla_revenue = pd.DataFrame(columns=["Date", "Revenue"])
for row in soup.find("tbody").find_all('tr'):
    col = row.find_all("td")
    date = col[0].text
    Revenue = col[1].text
    tesla_revenue = tesla_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/2383278492.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  tesla_revenue = tesla_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/2383278492.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  tesla_revenue = tesla_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/2383278492.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  tesla_revenue = tesla_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/2383278492.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  tesla_revenue = tesla_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/2383278492.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  tesla_revenue = tesla_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/2383278492.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  tesla_revenue = tesla_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/2383278492.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  tesla_revenue = tesla_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/2383278492.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  tesla_revenue = tesla_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/2383278492.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  tesla_revenue = tesla_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/2383278492.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  tesla_revenue = tesla_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/2383278492.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  tesla_revenue = tesla_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/2383278492.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  tesla_revenue = tesla_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/2383278492.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  tesla_revenue = tesla_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
Execute the following line to remove the comma and dollar sign from the Revenue column.

tesla_revenue["Revenue"] = tesla_revenue['Revenue'].str.replace(',|\$',"")
/tmp/wsuser/ipykernel_164/349343550.py:1: FutureWarning: The default value of regex will change from True to False in a future version.
  tesla_revenue["Revenue"] = tesla_revenue['Revenue'].str.replace(',|\$',"")
Execute the following lines to remove an null or empty strings in the Revenue column.

tesla_revenue.dropna(inplace=True)

tesla_revenue = tesla_revenue[tesla_revenue['Revenue'] != ""]
Display the last 5 row of the tesla_revenue dataframe using the tail function. Take a screenshot of the results.

tesla_revenue.tail(5)
Date	Revenue
8	2013	2013
9	2012	413
10	2011	204
11	2010	117
12	2009	112
Question 3: Use yfinance to Extract Stock Data
Using the Ticker function enter the ticker symbol of the stock we want to extract data on to create a ticker object. The stock is GameStop and its ticker symbol is GME.

Gamestop = yf.Ticker("GME")
Using the ticker object and the function history extract stock information and save it in a dataframe named gme_data. Set the period parameter to max so we get information for the maximum amount of time.

gme_data = Gamestop.history(period="max")
Reset the index using the reset_index(inplace=True) function on the gme_data DataFrame and display the first five rows of the gme_data dataframe using the head function. Take a screenshot of the results and code from the beginning of Question 3 to the results below.

gme_data.head(5)
Date	Open	High	Low	Close	Volume	Dividends	Stock Splits
0	2002-02-13	1.620129	1.693350	1.603296	1.691667	76216000	0.0	0.0
1	2002-02-14	1.712707	1.716074	1.670626	1.683250	11021600	0.0	0.0
2	2002-02-15	1.683250	1.687458	1.658001	1.674834	8389600	0.0	0.0
3	2002-02-19	1.666418	1.666418	1.578047	1.607504	7410400	0.0	0.0
4	2002-02-20	1.615920	1.662210	1.603296	1.662210	6892800	0.0	0.0
Question 4: Use Webscraping to Extract GME Revenue Data
Use the requests library to download the webpage https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/stock.html. Save the text of the response as a variable named html_data.

url = " https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/stock.html"
data = requests.get(url).text
html_data = data
Parse the html data using beautiful_soup.

soup = BeautifulSoup(html_data, 'html.parser')
Using BeautifulSoup or the read_html function extract the table with GameStop Quarterly Revenue and store it into a dataframe named gme_revenue. The dataframe should have columns Date and Revenue. Make sure the comma and dollar sign is removed from the Revenue column using a method similar to what you did in Question 2.

Click here if you need help locating the table
soup.find_all("tbody")[1]
gme_revenue = pd.DataFrame(columns=["Date", "Revenue"])
for row in soup.find("tbody").find_all('tr'):
    col = row.find_all("td")
    date = col[0].text
    Revenue = col[1].text
    gme_revenue = gme_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/1190327258.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  gme_revenue = gme_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/1190327258.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  gme_revenue = gme_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/1190327258.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  gme_revenue = gme_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/1190327258.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  gme_revenue = gme_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/1190327258.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  gme_revenue = gme_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/1190327258.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  gme_revenue = gme_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/1190327258.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  gme_revenue = gme_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/1190327258.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  gme_revenue = gme_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/1190327258.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  gme_revenue = gme_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/1190327258.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  gme_revenue = gme_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/1190327258.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  gme_revenue = gme_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/1190327258.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  gme_revenue = gme_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/1190327258.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  gme_revenue = gme_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/1190327258.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  gme_revenue = gme_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/1190327258.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  gme_revenue = gme_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
/tmp/wsuser/ipykernel_164/1190327258.py:7: FutureWarning: The frame.append method is deprecated and will be removed from pandas in a future version. Use pandas.concat instead.
  gme_revenue = gme_revenue.append({"Date":date, "Revenue":Revenue}, ignore_index=True)
Display the last five rows of the gme_revenue dataframe using the tail function. Take a screenshot of the results.

gme_revenue.tail(5)
Date	Revenue
11	2009	8806
12	2008	7094
13	2007	5319
14	2006	3092
15	2005	1843
Question 5: Plot Tesla Stock Graph
Use the make_graph function to graph the Tesla Stock Data, also provide a title for the graph. The structure to call the make_graph function is make_graph(tesla_data, tesla_revenue, 'Tesla'). Note the graph will only show data upto June 2021.

make_graph(tesla_data, tesla_revenue, 'Tesla')
---------------------------------------------------------------------------
NameError                                 Traceback (most recent call last)
Input In [86], in <cell line: 1>()
----> 1 make_graph(tesla_data, tesla_revenue, 'Tesla')

Input In [84], in make_graph(tesla_data, tesla_revenue, Tesla)
      1 def make_graph(tesla_data, tesla_revenue,Tesla):
      2     fig = make_subplots(rows=2, cols=1, shared_xaxes=True, subplot_titles=("Historical Share Price", "Historical Revenue"), vertical_spacing = .3)
----> 3     stock_data_specific = stock_data[stock_data.Date <= '2021--06-14']
      4     revenue_data_specific = revenue_data[revenue_data.Date <= '2021-04-30']
      5     fig.add_trace(go.Scatter(x=pd.to_datetime(stock_data_specific.Date, infer_datetime_format=True), y=stock_data_specific.Close.astype("float"), name="Share Price"), row=1, col=1)

NameError: name 'stock_data' is not defined
Question 6: Plot GameStop Stock Graph
Use the make_graph function to graph the GameStop Stock Data, also provide a title for the graph. The structure to call the make_graph function is make_graph(gme_data, gme_revenue, 'GameStop'). Note the graph will only show data upto June 2021.

def make_graph(gme_data, gme_revenue, Gamestop):
    fig = make_subplots(rows=2, cols=1, shared_xaxes=True, subplot_titles=("Historical Share Price", "Historical Revenue"), vertical_spacing = .3)
    stock_data_specific = stock_data[stock_data.Date <= '2021--06-14']
    revenue_data_specific = revenue_data[revenue_data.Date <= '2021-04-30']
    fig.add_trace(go.Scatter(x=pd.to_datetime(stock_data_specific.Date, infer_datetime_format=True), y=stock_data_specific.Close.astype("float"), name="Share Price"), row=1, col=1)
    fig.add_trace(go.Scatter(x=pd.to_datetime(revenue_data_specific.Date, infer_datetime_format=True), y=revenue_data_specific.Revenue.astype("float"), name="Revenue"), row=2, col=1)
    fig.update_xaxes(title_text="Date", row=1, col=1)
    fig.update_xaxes(title_text="Date", row=2, col=1)
    fig.update_yaxes(title_text="Price ($US)", row=1, col=1)
    fig.update_yaxes(title_text="Revenue ($US Millions)", row=2, col=1)
    fig.update_layout(showlegend=False,
    height=900,
    title=stock,
    xaxis_rangeslider_visible=True)
    fig.show()
About the Authors:
Joseph Santarcangelo has a PhD in Electrical Engineering, his research focused on using machine learning, signal processing, and computer vision to determine how videos impact human cognition. Joseph has been working for IBM since he completed his PhD.

Azim Hirjani

Change Log
Date (YYYY-MM-DD)	Version	Changed By	Change Description
2022-02-28	1.2	Lakshmi Holla	Changed the URL of GameStop
2020-11-10	1.1	Malika Singla	Deleted the Optional part
2020-08-27	1.0	Malika Singla	Added lab to GitLab
