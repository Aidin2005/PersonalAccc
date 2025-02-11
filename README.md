# PersonalAccc
![Uploading chatuml-diagram.png…]()

My code mimics a bank account system:
1. Transaction Tracking
• Every deposit and withdrawal must be an object of class Amount, including both the timestamp of the transaction, along with type.
2. Account Management
• The class Account shall hold information such as account number, holder name, balance, history of transactions as a list, etc.
• Deposit money can be done - increases the amount and adds to the transaction
• Withdraw - provided there is enough balance else throws error.
• The account keeps a history of all transactions.
3. How It Runs
• Creates an account for “John Doe” with an initial balance of 0.
• Deposits $500 and updates the balance.
• Withdraws $200 if there are enough funds.
• Prints the transaction history.
