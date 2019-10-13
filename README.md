## CREDIT-CARD-SEGMENTATION

### BUSINESS CONTEXT:
In this project it requires to develop a customer segmentation to define marketing strategy through machine learning techniqe. The sample dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioral variables.

#### Problems need to address:

Advanced data preparation: Build an ‘enriched’ customer profile by deriving “intelligent” KPIs such as:
- Monthly average purchase and cash advance amount
- Purchases by type (one-off, installments)
- Average amount per purchase and cash advance transaction,
- Limit usage (balance to credit limit ratio),
- Payments to minimum payments ratio etc.

#### Advanced reporting: 
- Use the derived KPIs to gain insight on the customer profiles.
- Identification of the relationships/ affinities between services.
- Clustering: Apply a data reduction technique factor analysis for variable reduction technique and a clustering algorithm to reveal the behavioural segments of credit card holders
- Identify cluster characterisitics of the cluster using detailed profiling.
- Provide the strategic insights and implementation of strategies for given set of cluster characteristics

#### DATA DICTIONARY:

- CUST_ID: Credit card holder ID
- BALANCE: Monthly average balance (based on daily balance averages) 
- BALANCE_FREQUENCY: Ratio of last 12 months with balance 
- PURCHASES: Total purchase amount spent during last 12 months 
- ONEOFF_PURCHASES: Total amount of one-off purchases 
- INSTALLMENTS_PURCHASES: Total amount of installment purchases 
- CASH_ADVANCE: Total cash-advance amount
- PURCHASES_ FREQUENCY: Frequency of purchases (Percent of months with at least one purchase)
- ONEOFF_PURCHASES_FREQUENCY: Frequency of one-off-purchases 
- PURCHASES_INSTALLMENTS_FREQUENCY: Frequency of installment purchases 
- CASH_ADVANCE_ FREQUENCY: Cash-Advance frequency 
- AVERAGE_PURCHASE_TRX: Average amount per purchase transaction 
- CASH_ADVANCE_TRX: Average amount per cash-advance transaction 
- PURCHASES_TRX: Average amount per purchase transaction
- CREDIT_LIMIT: Credit limit
- PAYMENTS: Total payments (due amount paid by the customer to decrease their statement balance) in the period
- MINIMUM_PAYMENTS: Total minimum payments due in the period. 
- PRC_FULL_PAYMEN: Percentage of months with full payment of the due statement balance 
- TENURE: Number of months as a customer

#### DATA AVAILABLE:
- CC GENERAL.csv
