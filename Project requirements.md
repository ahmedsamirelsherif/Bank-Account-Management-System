Part 1: Bank Account Management System 

Objective 

Implement a simple bank account management system using Python object-oriented programming. 

The project should include class creation, object manipulation, and basic file handling. 

Class Definition 
Create a class named Account that includes the following: 
Attributes: 
• name: Account holder's name (string) 
• id: Unique account ID generated automatically 
• balance: Starting balance (default is 0.0) 
Methods: 
1. deposit(amount) 
o Add the amount to the balance. 
o Before depositing, check that the amount is not negative. 
o If invalid, print an error message. 
2. withdraw(amount) 
o Subtract the amount from the balance. 
o Before withdrawing, check that: 
▪ The amount is not negative. 
▪ The amount is less than or equal to the current balance. 
o If invalid, print an error message. 
3. display() 
o Print the account holder’s name, id, and current balance. 
Program Structure 
Implement the following functions outside the class: 
1. read_data() 
o Prompt the user to enter name and initial balance. 
o Create an Account object and return it. 
2. display_account(account) 
o Call the account’s display() method. 
3. menu() 
o Show a menu to the user: 
o 1. Deposit Money 
o 2. Withdraw Money 
o 3. Display Account Details 
o 4. Exit 
o Allow the user to perform operations repeatedly until they choose Exit.
