# SQL-PBI_Bank_Loan_Data_Analysis
## I. Introduction
### 1. Business question
<p>The Bank Loan Portfolio Analysis project aims to provide insights into the bank's loan portfolio using SQL queries and Power BI visualization tools. This project will help improve decision-making, reduce risks, and optimize loan management strategies.</p>
<p>Project Objectives:</p>
<ul>
  <li>Analyze the bank's loan portfolio to see the distribution of loans across different types (like mortgage, personal loans, business loans).</li>
  <li>Evaluate the performance of loans based on metrics such as default rates, repayment patterns, and profitability.</li>
  <li>Identify trends and patterns within the loan portfolio to help with planning and forecasting.</li>
  <li>Develop interactive dashboards in Power BI for visualizing key metrics and trends.</li>
  <li>Generate insights to optimize lending practices, manage risks, and improve overall portfolio performance.</li>
</ul>

### 2. Dataset
Internal bank databases containing loan information including borrower details, loan amounts, interest rates, repayment terms, and loan status.

## II. Apply design-thinking mindset
### 1. Empathize
<img width="1200" alt="emphathy" src="https://github.com/user-attachments/assets/2617a935-efa7-4ff0-8cc5-8ec24c0f590f">

### 2. Define point of view
<img width="1200" alt="stage2" src="https://github.com/user-attachments/assets/118c34f8-6af5-40b3-ba82-59f7deefde6e">

### 3.Ideate
<img width="1200" alt="stage3" src="https://github.com/user-attachments/assets/f6e296e7-6df4-41f7-9b9d-626f8daeb4c9">

## III. Main Process

### 1. SQL Query
See more detail: https://docs.google.com/document/d/1AzPGot5EupUrt6IITzn1J1wv2OxgiYS7E-6th5zpH0E/edit



### 2. Build Dashboard
<p><b>Summary</b></p>
<img width="1200" alt="Screenshot_9" src="https://github.com/user-attachments/assets/c4ca0631-8109-4df2-be8f-5a0eb4f15be6">
<p><b>Overview</b></p>
<img width="1200" alt="Screenshot_10" src="https://github.com/user-attachments/assets/6dc9ea66-f388-45ca-bbd6-56e443fb29df">
<p><b>Details</b></p>
<img width="1200" alt="Screenshot_12" src="https://github.com/user-attachments/assets/ad9d94bd-591a-4e3d-ae93-93d10fee9d31">


## III. Insight
<h4>1. Loan Application Analysis</h4>
    <p><strong>Total Loan Applications:</strong> 38,600 applications</p>
    <ul>
        <li>The number of applications increased steadily from January (2.3K) to December (4.3K), indicating a significant rise in loan demand.</li>
        <li>States with the highest number of applications are CA (6.9K), NY (3.7K), FL (2.8K), and TX (2.7K), showing high demand for loans in these regions.</li>
        <li>The majority of loan applications come from individuals with over 10 years of employment (8.9K) and less than 1 year (4.6K), possibly reflecting a stable income or the start of a career.</li>
        <li>The most common loan purposes are debt consolidation (18K), credit card (5K), and home improvement (4K), indicating that borrowers aim to manage debt effectively or upgrade personal assets.</li>
        <li>Loan applications from renters (18K) and mortgage holders (17K) are nearly equal, suggesting high loan demand from both groups.</li>
    </ul>

    <h4>2. Funded Amount Analysis</h4>
    <p><strong>Total Funded Amount:</strong> $435.8 million</p>
    <ul>
        <li>The funded amount also increased from January ($25M) to December ($54M), corresponding with the rise in loan applications.</li>
        <li>The highest funded amounts are in CA ($78M), followed by NY ($42M), and TX ($31M), reflecting strong economies in these states.</li>
        <li>The highest funded amounts go to individuals with over 10 years of employment ($116M) and 2 years ($45M), indicating better repayment capabilities.</li>
        <li>Debt consolidation (0.23 billion), credit card (0.06 billion), and home improvement (0.03 billion) are the top funded purposes.</li>
        <li>Mortgage holders receive the highest funded amount ($219.33M), followed by renters ($185.77M), possibly due to the collateral provided by mortgage holders.</li>
    </ul>

    <h4>3. Received Amount Analysis</h4>
    <p><strong>Total Amount Received:</strong> $473.1 million</p>
    <ul>
        <li>The received amount increased from January ($28M) to December ($58M), showing effective debt recovery.</li>
        <li>CA has the highest received amount ($84M), followed by NY ($46M) and TX ($34M), reflecting strong economies and repayment abilities.</li>
        <li>Individuals with over 10 years of employment ($126M) and 3 years ($48M) have the highest repayment amounts.</li>
        <li>The most repaid loan purposes are debt consolidation (0.25 billion), credit card (0.07 billion), and home improvement (0.04 billion).</li>
        <li>Mortgage holders repay the highest amount ($238.47M), followed by renters ($201.82M).</li>
    </ul>

    <h4>Recommendations</h4>
    <ul>
        <li><strong>Enhance Risk Assessment:</strong> Implement stricter credit evaluation criteria to reduce the percentage of bad loans. Use predictive analytics to identify high-risk segments and adjust lending policies accordingly.</li>
        <li><strong>Optimize Interest Rates:</strong> Continuously monitor market conditions to maintain competitive interest rates. Consider variable interest rates based on borrower profiles to attract a diverse customer base.</li>
        <li><strong>Improve Debt-to-Income (DTI) Ratio Management:</strong> Educate borrowers on maintaining a healthy DTI ratio through workshops or online resources.</li>
        <li><strong>Expand Lending Portfolio:</strong> Explore new or underserved markets to expand the customer base. Diversify loan products, such as small business loans, educational loans, or green loans, to attract a wide range of customers.</li>
        <li><strong>Leverage Technology:</strong> Use artificial intelligence and machine learning to enhance predictive modeling for loan approvals and risk assessment. Invest in digital platforms to streamline the loan application and approval process, providing a seamless experience for customers.</li>
    </ul>
