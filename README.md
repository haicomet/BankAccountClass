BankAccount
--------------

-accountId: int

-customerName: string

-balance: decimal

-transactions: List<string>

+BankAccount(customerName: string, balance: decimal)

+Deposit(amount: decimal): void

+Withdraw(amount: decimal): void

+AccountId: int { get; }

+CustomerName: string { get; }

+Balance: decimal { get; }

+Transactions: List<string> { get; }

Test Cases:
Keeps track of account id, balance, transactions, note: use properties to access these instance variables

An account can be created given the customer name, initial balance, 

Create deposit and withdrawal methods.


<img width="552" height="239" alt="Screenshot 2025-09-24 at 7 46 10 PM" src="https://github.com/user-attachments/assets/e06e27f5-5521-4937-9d3f-b765f34d622e" />
