<h1>Bank Account Management System</h1>

<p>This is a simple bank account management system that can read a .CSV file of names, social security numbers, account types, and initial deposit amounts. The system uses a proper data structure to hold all of these accounts, and both checking and savings accounts share common properties, including methods for depositing, withdrawing, transferring funds, and displaying account information.</p>



<h2>Account Numbers</h2>
The application generates 11-digit account numbers for each account, using a process that includes a 1 or 2 depending on the account type, the last two digits of the account holder's social security number, a unique 5-digit number, and a random 3-digit number.



<h2>Safety Deposit Boxes and Debit Cards</h2>
Savings account holders are given a safety deposit box identified by a 3-digit number and accessed with a 4-digit code, while checking account holders are assigned a debit card with a 12-digit number and a 4-digit PIN.
  

  
<h2>Interest Rates</h2>
Both account types use an interface to determine the base interest rate, with savings accounts using a rate that is .25 points less than the base rate and checking accounts using a rate that is 15% of the base rate.
  


<h2>Usage</h2>
To use this application, simply run the BankAccountApp.java file. The program will prompt you to enter the name of the .CSV file containing the account information. Once the file is loaded, you can perform various operations on the accounts, such as depositing or withdrawing funds, transferring funds between accounts, and displaying account information.
  

  
<h2>Requirements</h2>
This program requires Java 8 and above

  
  
<h2>License</h2>
This project is licensed under the MIT License - see the LICENSE file for details.

