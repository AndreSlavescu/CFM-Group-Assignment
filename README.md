# CFM-Group-Assignment

CFM group assignment

# Due date: November 26, 2021

- Target either the riskiest or safest portfolio
  - Decided on targeting the safest portfolio

- Read a .csv file containing a finite number of stock tickers

- Only target US listed stocks

- Stocks in the portfolio must have an average daily volume of at least 10 000 shares

- Minimum of 10 - Maximum of 20 stocks
  - No individual stock can make up more than 35% of the portfolio
  - Must spend all $100 000 USD

- Purchase stocks at the closing prices on November 26

- Create a DataFrame called "FinalPortfolio"
    - Index starts at 1 and ends at the number of stocks the code chose
    - Have the following headings: Ticker, Price, Shares, Value, Weight
    - Show the total adds to $100 000 and weight is 100%
    - Second last output

- Create final DataFrame "Stocks"
    - Same index as "FinalPortfolio" but only has Ticker and Shares
    - Must output DataFrame to a CSV file titled “Stocks_Group_18.csv” 

- At the end of the assignment, provide a declaration of contribution from each team member

# Notes on Code
    - Code should be well commented
    - Write and call functions when appropriate
    - Avoid hardcoding
    - Use loops where appropriate
    - Why are the stocks picked those specific stocks?