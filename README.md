# Financial Planner

This repository creates 2 financial analysis tools utilizing API's.

The first will be a personal finance planner that will allow users to visualize their savings composed by investments in shares and cryptocurrencies to assess if they have enough money as an emergency fund.

API's were used to fetch the current BTC and ETH prices.  At the moment they are very low, but we anticipate them to do well in the next couple of years. :)

![](/Images/cryptoPie.png)


The second tool will be a retirement planning tool that will use the Alpaca API to fetch historical closing prices for a retirement portfolio composed of stocks and bonds, then run Monte Carlo simulations to project the portfolio performance at 30 years. Use the Monte Carlo data to calculate the expected portfolio returns given a specific initial investment amount.

I used ALPACA's API's to get historical data for stocks and bonds, and ran some Monte Carlo simulations for 30 years.  It looks promising even for a $20000 investment, but I think I would use the $30000 one.

*There is a 95% chance that an initial investment of $20000 in the portfolio over the next 30 years will end within in the range of $45864.22 and $484618.9*

*There is a 95% chance that an initial investment of $30000.0 in the portfolio over the next 30 years will end within in the range of $68796.33 and $726928.35*


# Optional Challenge completed - Early retirement
I used an investment of $50000, and 10 years to retirement with a 80/20 weight split stocks/bonds.....Still don't think it is enough....Maybe some more crypto investments will pay off.