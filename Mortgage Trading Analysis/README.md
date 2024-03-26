# Mortgage Trading Analysis in Power BI: A Case Study

This case study simulates a real-world scenario for a Junior Trader at Sooper Mortgage, a fictional non-bank mortgage lender.  We'll use Power BI to analyze mortgage data, market prices, and target profit margins to execute a profitable mortgage trade in the U.S. capital markets.

## Scenario:

    - Date: September 21st, 2021 (Trade Settlement: October 13th, 2021)
    - Dataset: Over 5,000 mortgages representing real market data.
    - Objective: Maximize profit by selling a selection of mortgages through a whole loan trade or securitization (UMBS).

## Methodology:

    - Data Cleaning & Preparation: Used Power Query to clean datasets and create trade statuses & scheduled balances using IF statements.
    - Trading Strategy Exploration: Compared whole loan and UMBS prices to determine the most profitable option.
    - Identifying Winning Bids: Created a system (Power Query & M) to find the highest bid and winning bidder for each loan.
    - Data Model Construction: Combined multiple datasets into a cohesive Power BI data model.
    - Trade Profitability Analysis: Calculated trade premiums, prices, and total revenue, highlighting the importance of weighted average price over mean average for accurate calculations.
    - Profit Margin and Key Influencers: Analyzed profit margins and used Power BI's AI-driven insights to identify key factors influencing profitability.

## Key Findings:

    - Loan Population:
        - Low default risk indicated by high Loan-to-Value (LTV) ratio (60.44%) and Debt-to-Income (DTI) ratio (31.7%).
        - Over 60% of loans are ready for trade.
    - Trade Performance:
        - 27.33% of loans surpassed the benchmark test, suggesting UMBS might yield better profit for some loans.
        - Profitable trade with a total premium of $15.14 million.
        - Weighted average price (103.66) provides a more accurate representation than average price (103.75) when considering loan balances.
        - Excluding low-profit loans (Smells Largo) improves overall trade efficiency.
    - Profit Margin & Influencers:
        - Sooper Mortgage achieved a 5.69% profit margin on loans, exceeding their target of 5%.
        - Higher-than-expected trade premium suggests increased market demand for Sooper Mortgage loans.
        - FICO score is a key influencer on price; loans with higher credit scores command higher prices.

## Recommendations:

    - Implement tiered pricing structures based on FICO score ranges - lower fees for higher credit scores.
    - Leverage insights to refine loan origination strategies and attract borrowers with strong credit profiles.

This case study demonstrates the power of Power BI in analyzing mortgage data and making informed decisions for profitable mortgage trading.

#PowerBI #MortgageTrading #FinancialAnalysis #Profitability #LoanAnalysis #DataCleaning #UMBS #FICOscore #WeightedAverage #KeyInfluencers