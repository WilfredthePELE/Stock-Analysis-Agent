# Stock Analysis Agent

This project implements a Financial Market Analysis Assistant that integrates Google Gemini (via LangChain) with the yfinance library to provide real-time stock market data and portfolio analysis. The assistant supports queries for stock prices, company information, dividend and earnings dates, institutional and mutual fund holders, stock upgrades/downgrades, stock splits, and recent news. It also includes portfolio analysis for a user-defined set of stocks, calculating total portfolio value and providing brief stock analyses.
Features

Stock Price Queries: Retrieves current stock prices for any ticker using yfinance.
Company Information: Provides detailed company data, including address, industry, sector, market cap, EBITDA, total debt, total revenue, and debt-to-equity ratio.
Dividend and Earnings: Fetches the latest dividend and earnings release dates.
Institutional and Mutual Fund Holders: Summarizes top institutional and mutual fund holders, including share percentages and holding values.
Stock Upgrades/Downgrades: Retrieves recent rating changes with details on firms, grades, and dates.
Stock Splits History: Provides historical stock split data.
News Retrieval: Fetches recent news articles for specified tickers.
Portfolio Analysis: Analyzes a user-defined portfolio, calculating total value and providing brief analyses of each stock (e.g., price, P/E ratio, recent performance).
Agent-Based Interaction: Uses LangChain's tool-calling agent to handle complex financial queries with Google Gemini (gemini-2.0-flash).
Error Handling: Gracefully handles invalid tickers, API errors, and parsing issues.

Prerequisites

Python 3.8 or higher
Required libraries: yfinance, langchain, langchain-google-genai, google-colab (for Colab environments)
Google Gemini API key for LLM integration
Internet access for API calls and yfinance data retrieval
(Optional) Google
