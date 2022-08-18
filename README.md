# equity_valuator
This script connects to yahoo finance API and put in the past 4 years' data of the chosen stocks. The first part of the script visualize key indicators of financial records/health. The second part valuates the equity using 1) Discounted Cash Flow Model on Operating Cash Flow, Net Income and Free Cash Flow, and 2) Perpetual growth of Dividend (Dividend Discount Model) and Free Cash Flow

## Under 2nd cell, simply insert the ticker symbol and let the program do the rest
* example 1 facebook : ticker = yf.Ticker("fb")
* example 2 Tencent (HKEX) : ticker = yf.Ticker("0700.HK")
* example 3 DBS (SGX) : ticker = yf.Ticker("D05.SI")
\n Do check the ticker in yahoo finance site for the ticker and the market code if the stocks is outside of US market
