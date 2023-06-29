# Create base for DDA models

**Steps followed:**
1. Extract the lending responses (from 29 Nov,22 till 5th June,23)
2. Tag the plaid accounts to responses basis the plaid mapping logic
3. Filter the base for approvals and map the target
4. Extract transactions from mapped accounts for last 6 months
5. Filter the data for accounts which have atleast 20 transactions in last 6 months
6. Finally filter out the business and personal accounts (with business-like transactions) and remove all the personal transactions from the remaining set of accounts to get the final base
