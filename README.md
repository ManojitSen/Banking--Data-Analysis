## Banking Dashboard (Using Microsoft PowerBi)

## About Dataset 
This dataset basically contains information about bank details , various client details which consists of multiple tables which are interlinked with each other through keys like primary key and foreign key.
The various tables are Banking Relationship, Client-Banking, Gender, Investment Advisor and Period.
- <a href="https://github.com/ManojitSen/Banking--Data-Analysis/blob/main/Datasets.zip">Dataset</a>

## Business Questions / KPIs
The dashboard is designed to answer the following key business and risk-related questions:
- How many total clients does the bank currently serve?
   - Helps assess customer base size and portfolio exposure.
- What is the total loan exposure across all clients?
    - Measures overall lending risk for the bank.
- How is the total loan distributed across bank loans, business lending, and credit cards?
   - Identifies high-risk lending categories.
- Which client segments (by gender, investor type, or advisor) have the highest loan amounts?
    -  Supports risk profiling and targeted decision-making.
- What is the total deposit amount held by the bank?
    - Helps compare deposits vs loans to evaluate liquidity and risk balance.
- How do deposits vary across different account types (Savings, Checking, Bank Deposit, Foreign Currency)?
 -  Identifies stable vs volatile sources of funds.
- What is the total processing fee earned by the bank from lending activities?
  - Measures profitability from loan processing.
- How long have clients been engaged with the bank (Engagement Days / Timeframe)?
  - Long-term clients generally indicate lower default risk.
- How does estimated income (Low, Mid income bands) relate to loan and repayment capacity?
  - Helps assess creditworthiness and default probability.
- Which clients or segments have high loan amounts but low deposits?
  - Flags high-risk customers.
- What is the total credit card balance outstanding across clients?
  - Indicates short-term credit risk exposure.
- Which banking relationship types or periods show higher lending and better engagement?
   - Supports strategic planning and risk optimization.
- Dashboard Interaction
  - <a href="https://github.com/ManojitSen/Banking--Data-Analysis/blob/main/Home_Screenshot.jpg">Home(View Dashboard)</a>
  - <a href="https://github.com/ManojitSen/Banking--Data-Analysis/blob/main/Loan%20Analysis_Screenshot.jpg">Loan Analysis(View Dashboard)</a>
  - <a href="https://github.com/ManojitSen/Banking--Data-Analysis/blob/main/Deposit%20Analysis_Screenshot.jpg">Deposit Analysis(View Dashboard)</a>
  - <a href="https://github.com/ManojitSen/Banking--Data-Analysis/blob/main/Summary%20Dashboard%20_Screenshot.jpg">Summary(View Dashboard)</a>

## Process
-  Collected and understood banking and client-related datasets linked through primary and foreign keys.
-  Performed data cleaning by validating data types, handling inconsistencies, and ensuring correct relationships between tables.
- Cleaned and prepared data by creating new columns such as Engagement Timeframe, Engagement Days, Income Band, and Processing Fees.
- Built calculated measures using DAX functions like SUM, DISTINCTCOUNT, SUMX, SWITCH, and DATEDIFF.
- Analysed loans, deposits, fees, and client engagement to assess risk and profitability.
- Designed interactive Power BI dashboards for loan analysis, deposit analysis, and overall summary to support data-driven lending decisions.

## Home_Dashboard
![Home_Screenshot](https://github.com/user-attachments/assets/90b612e6-cb77-4630-982d-5cbf12fe1e4b)

## Loan_Analysis_Dashboard
![Loan Analysis_Screenshot](https://github.com/user-attachments/assets/12e6514d-f5b3-4666-ad3f-323f9a3422c3)

## Deposit_Analysis_Dashboard
![Deposit Analysis_Screenshot](https://github.com/user-attachments/assets/0ed92c18-35ab-461a-92f7-9d6168654fcc)

## Summary_Dashboard
![Summary Dashboard_Screenshot](https://github.com/user-attachments/assets/8e143f9f-8d2c-49a1-bb38-66636a840a91)

## Project Insights
-  The dashboard provides a comprehensive view of client-level risk by analyzing loans, deposits, fees, and engagement metrics.
- Clients with longer engagement periods tend to maintain higher deposits and demonstrate more stable banking relationships.
- Bank loans constitute the largest share of total lending compared to business lending and credit card balances.
- Low and mid-income bands account for a major portion of loan distribution, making income-based risk segmentation essential.
- Clients with higher deposit balances generally show better repayment capacity and lower financial risk.
- Credit card balances highlight short-term credit exposure, particularly among clients with lower deposits.
- Processing fees generate significant revenue from high-loan-value clients, contributing to overall bank profitability.
- Private banks have a higher number of clients compared to other bank types, indicating stronger customer acquisition.
- Deposit amounts vary across different account types such as savings, checking, bank deposits, and foreign currency accounts.
- Engagement metrics help identify long-term clients who contribute more consistently to deposits and lending stability.
- Nationality-wise analysis shows variations in loan amounts, helping identify regions with higher credit exposure.
- Advisor and banking relationship analysis supports better understanding of client behavior and risk distribution over time.

## Conclusion 
Empowered by the latest data visualization techniques, Power BI dashboards are among the most effective resources for using in banking sector. As outlined in this write-up, a banking  operations dashboard in Power BI can be developed with key banking related metrics and KPIs.

##  Future Work 
-  With these dashboards banks can easily know what is the total loan amount and all other things of a particular investor.
- It also helps which type of banks have more number of clients as we can see private banks have more number of clients so it can helps other banks can build their strategies to increase clients.
- It also provides insights about which nationality has highest bank loans.
- It gives information about various types of amount involved in different types of accounts by investors.





