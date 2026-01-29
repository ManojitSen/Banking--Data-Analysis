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

## Dashboards
 - ![Home_Screenshot](https://github.com/user-attachments/assets/90b612e6-cb77-4630-982d-5cbf12fe1e4b)
 - ![Loan Analysis_Screenshot](https://github.com/user-attachments/assets/12e6514d-f5b3-4666-ad3f-323f9a3422c3)
 - ![Deposit Analysis_Screenshot](https://github.com/user-attachments/assets/0ed92c18-35ab-461a-92f7-9d6168654fcc)
 - ![Summary Dashboard _Screenshot](https://github.com/user-attachments/assets/8e143f9f-8d2c-49a1-bb38-66636a840a91)



