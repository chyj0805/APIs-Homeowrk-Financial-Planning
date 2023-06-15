# APIs Homeowrk Financial Planning
Module 5 Challenge

# Backgorund 
You decided to start a FinTech consultancy firm, and you want to make a difference by working on projects with high social impact in local communities. You just won your first contract to help one of the biggest credit unions in your area. They want to create a tool that helps their members enhance their financial health. The Chief Technology Officer (CTO) of the credit union asked you to develop a prototype application to demo in the next credit union assembly.

The credit union board wants to allow the union's members to assess their monthly personal finances, and also be able to forecast a reasonably good retirement plan based on cryptocurrencies, stocks, and bonds.
In this homework activity, you will use all the skills you have learned until now - focusing on using APIs as part of the technical solution - to create two financial analysis tools.

The first will be a personal finance planner that will allow users to visualize their savings composed by investments in shares and cryptocurrencies to assess if they have enough money as an emergency fund.
The second tool will be a retirement planning tool that will use the Alpaca API to fetch historical closing prices for a retirement portfolio composed of stocks and bonds, then run Monte Carlo simulations to project the portfolio performance at 30 years. You will then use the Monte Carlo data to calculate the expected portfolio returns given a specific initial investment amount.

# Part 1 - Personal Finance Planner
We collect data of BTC, ETH, SPY(STOCK) and AGG thorugh API and determined our clients current investment assets networth
## Savings Health Analysis
Base on the client income of $12000 , and our client is be able to have enough saings to cover the emergency fund, which determined client has good cash flow.

# Part 2 - Retirement Planning
with client investment profolio (AGG,SPY), we run a Monte Carlo Simulation to simulate 1000 times of his proflio grow which in 3 different time line, 5 years, 10 years and 30 years. and they most efficient way to get early retired is 10years invest interval with $20000 intial investment on AGG and SPY evenly.