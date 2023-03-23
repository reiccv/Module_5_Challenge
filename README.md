# Module 5 Challenge

In this Challenge, ill create two financial analysis tools by using a single Jupyter notebook:

Part 1: A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

Part 2: A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.


# Imports

The imports, libraries and dependecies I used for this financial analysis tool are  os, requests, json, pandas, dotenv, alpaca_trade_api and 
MCForecastTools


![alt text](https://github.com/reiccv/Module_5_Challenge/blob/main/Images/imports_mod5.PNG)


# Financial Planner for Emergencies

In this section, ill determine the current value of a member’s cryptocurrency wallet. ill collect the current prices for the Bitcoin and Ethereum cryptocurrencies by using the Python Requests library. For the prototype, ill assume that the member holds the 1.2 Bitcoins (BTC) and 5.3 Ethereum coins (ETH). To do all this, complete the following steps:

![alt text](https://github.com/reiccv/Module_5_Challenge/blob/main/Images/part1_1.PNG)

![alt text](https://github.com/reiccv/Module_5_Challenge/blob/main/Images/part1_2.PNG)

![alt text](https://github.com/reiccv/Module_5_Challenge/blob/main/Images/part1_3.PNG)

![alt text](https://github.com/reiccv/Module_5_Challenge/blob/main/Images/part1_4.PNG)

![alt text](https://github.com/reiccv/Module_5_Challenge/blob/main/Images/part1_5.PNG)

![alt text](https://github.com/reiccv/Module_5_Challenge/blob/main/Images/part1_6.PNG)

![alt text](https://github.com/reiccv/Module_5_Challenge/blob/main/Images/part1_7.PNG)

# Financial Planner for Retiremenet

Create the Monte Carlo Simulation
In this section, ill use the MCForecastTools library to create a Monte Carlo simulation for the member’s savings portfolio. To do this, the following steps:

Make an API call via the Alpaca SDK to get 3 years of historical closing prices for a traditional 60/40 portfolio split: 60% stocks (SPY) and 40% bonds (AGG).

Run a Monte Carlo simulation of 500 samples and 30 years for the 60/40 portfolio, and then plot the results.


![alt text](https://github.com/reiccv/Module_5_Challenge/blob/main/Images/part2_1.PNG)

![alt text](https://github.com/reiccv/Module_5_Challenge/blob/main/Images/part2_2.PNG)

![alt text](https://github.com/reiccv/Module_5_Challenge/blob/main/Images/part2_3.PNG)

![alt text](https://github.com/reiccv/Module_5_Challenge/blob/main/Images/part2_4.PNG)

# Jupyter notebook 