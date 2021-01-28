# Python-Algorithmic-Trading
Algorithmic Trading

# Overview
1. Algorithmic Trading Basics
2. API Basics and Configurations
3. Project 1: Equal-Weight S&P 500 Screener
4. Project 2: Quantitative Momentum Screener
5. Project 3: Quantitative Value Screener

# Algorithmic Trading Overview
Algorithmic trading means using computers to make investment decisions.There are many different types of algorithmic trading. The main difference is their speed of execution.

# The Algorithmic Trading Process
The process of running a quantitative investing strategy can be broken down into the following steps:
1. Collect data
2. Develop a hypothesis for a strategy
3. Backtest that strategy
4. Implement the strategy in production

# API  Basics and Course Configuration
An API is an Application Programming Interface. APIs allow you to interact with someone's else's software using your own code.
We'll be using the IEX Cloud API to gather stock market data to make investment decisions.We'll be using GET requests to gather data 
from the IEX Cloud API.

There are many other ways to interact with an API.
>POST: Adds data to the database exposed by the API. (Create only)
>PUT: Adds and overwrites data in the database exposed by the API. (Create od replace)
>DELETE: Deletes data from the API's database

practice interacting with APIs
https://github.com/public-apis/public-apis

# PROJECT 1: Equal-Weight S&P 500 Screener
The S&P 500 is the world's most popular stock market index. Many investment funds are benchmarked to the S&P 500. This means that they seek to replicate the performance of this index by owning all the stocks that are held in the index.One of the most important characteristics of the S&P 500 is that it is market capitalization-weighted. This means that larger companies get a correspondingly larger weight in the index.

In the first project we're going to build an alternative version of the S&P 500 Index where each company has the same weighting. 

# PROJECT 2: Quantitative Momentum Screener
Momentum investing means investing in assets that have increased in price the most. Let's consider an example: Imagine that you have the chioce of investing in two stocks that have had the following returns over the last year: 
  <li> Apple (AAPL): 35%<li/>
  <li> Microsoft (MSFT): 20%<li/>
  
> A momentum investing strategy would suggest investing in Apple because of its higher recent price return.There are many other nuances to  momentum investing strategies that we will explore.

# PROJECT 3: Quantitative Value Screener
Value investing means investing in stocks that are trading below their percieved intrinsic value. Value investing was popularized by investors like Warren Buffet, Seth Klarman, and Benjamin Graham.

Creating algorithmic value investing strategies relies on a concept called multiples.Multiples are calculated by dividing a company's stock price by some measure of the company's worth - like earnings or assets.

Here are a few examples of common multiples used in  value investing:
  <li> Price-to-earnings ratio<li/>
  <li> Price-to-book-value<li/>
  <li> Price-to-free-cash-flow<li/>  
Each of the individual multiples used by value investors has its pros and cons. One way to minimize the impact of any specific multiple is by using a composite. A composite is an average of of many different valuation strategies. We'll use a composite of 5 different value metrics in our strategy.
