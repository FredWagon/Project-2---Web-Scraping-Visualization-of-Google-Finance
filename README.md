# Project 2 - Web Scraping & Visualization of Google Finance  

### Purpose  
The purpose of this analysis is to introduce the concepts web scraping using BeutifulSoup and advanced visualization using Seaborn. The data selected for this analysis was stock price data from Google Finance, including indexes, market leaders (most active, top gainers & top losers) as individual stocks in a portfolio imported from CSV. The analysis will answer the following questions:
1. What are the top performering stocks in My Portfolio this trading session? What are the worst performers?  
2. What is the Total Value, Total Change and Percent Change in My Portfolio in this trading session?  
3. How did My Portfolio perform against Market Indexes this trading session?  
4. How did My Portfolio atocks perform against Most Active, Top Gainers and Top Losers?  
5. Do any stocks in My Portfolio appear in Most Active, Top Gainers or Top Losers?  

### Code ('Scraping Google Finance.ipynb' file)  
The code is contained in the 'Scraping Google Finance.ipynb' file and is intended to be run in JupyterLab environment. The code includes all activities from  import of a personal porfolio from CSV, through web scraping using BeautifulSoup and Selenium, through import of a personal porfolio from CSV, data transformation, and analysis. The code also includes observations and conclusions as markdown blocks in the notebook file.  

### Prerequisites  
1. This notebook is intended for Jupyter Notebooks or Jupyter Labs. These environments must be installed in your environment and are available through Anaconda.  
2. This code uses Selenium and BeautifulSoup. Both library sets must be installed in your environment.
3. This code uses Google Chrome for active scraping of certain elements using Selenium. Google Chrome must be installed in your environment and you must provide the path to the Chrome executable in this code.

### Input Files (Raw Data)  
The raw data files used in this analysis are included and must be located in the same directory as the code above.  
* my_portfolio.csv - This CSV file can be upated to reflect the user's portfolio for this analysis. An example portolio is pre-loaded. The CSV file includes the stock name, stock symbol, market, Google Finance URL for the stock, and number of shares. This file needs to be in the same directory as the 'Scraping Google Finance.ipynb' file to run correctly.

### Analysis Results  
Results of the analysis (answers to the questions detailed in purpose) are contained in the 'conclusion' markdown cells at the end of each part in the 'Scraping Google Finance.ipynb' file:
* QUESTION 1: What are the top performering stocks in My Portfolio this trading session? What are the worst performers?  
* QUESTION 2: What is the Total Value, Total Change and Percent Change in My Portfolio in this trading session?  
* QUESTION 3: How did My Portfolio perform against Market Indexes this trading session?  
* QUESTION 4: How did My Portfolio atocks perform against Most Active, Top Gainers and Top Losers?  
* QUESTION 5: Do any stocks in My Portfolio appear in Most Active, Top Gainers or Top Losers?  

Please note that the code is scraping dynamic data and will change trading session to trading session. The written conclusions detailed in markdown cells is not! Re-running the code will likely yeild different results than those summarized in markdown.  
