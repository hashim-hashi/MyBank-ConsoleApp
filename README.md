# MyBank-ConsoleApp

Here you're going to create new types that represent a bank account. 
This file will contain the definition of a bank account. 
Here Object Oriented programming organizes code by creating types in the form of classes. 
These classes contain the code that represents a specific entity. 
The BankAccount class represents a bank account. 
The code implements specific operations through methods and properties. 

The bank account supports this behaviors:

1. It has a 10-digit number that uniquely identifies the bank account.
2. It has a string that stores the name or names of the owners.
3. The balance can be retrieved.
4. It accepts deposits.
5. It accepts withdrawals.
6. The initial balance must be positive.
7. Withdrawals can't result in a negative balance.

Adding Further Modification:
1. An interest earning account:
   Will get a credit of 2% of the month-ending-balance.
2. A line of credit:
   Can have a negative balance, but not be greater in absolute value than the credit limit.
   Will incur an interest charge each month where the end of month balance isn't 0.
   Will incur a fee on each withdrawal that goes over the credit limit.
3. A gift card account:
   Can be refilled with a specified amount once each month, on the last day of the month.



This Project demonstrated many of the techniques used in Object-Oriented programming:

1. I used Abstraction when i defined classes for each of the different
   account types. Those classes described the behavior for that type of account.
2. I used Encapsulation when i kept many details private in each class.
3. Used Inheritance when i leveraged the implementation already created 
   in the BankAccount class to save code.
4. Used Polymorphism when i created virtual methods that derived classes 
   could override to create specific behavior for that account type.
