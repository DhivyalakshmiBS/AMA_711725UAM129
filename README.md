Banking management system program in C language.

This program allows users to create and manage their bank accounts. 

Functions in this program.
 1. Create account: Users can create a new bank account by prooviding the last name, first name, account number, balance and pin number.
 2. Deposit money: Users can deposit money into their account by providing the account number and the amount to be deposited and the pin number for authentication. The remaining balance will be updated accordingly and displayed to the user.
 3. Withdraw money: Users can withdraw money from their account by providing the account number, the amount to be withdrawn and the pin number for authentication. The remaining balance will be updated accordingly and displayed to the user.
 4. Transfer money: Users can transfer money from one account to another by providing the sender account number, receiver account number, the amount to be transferred and the pin number for authentication. 
 5. Delete account: Users can delete their bank account by providing the account number and the pin number for authentication. The account will be removed from the system.

Technologies used in this program:
- C programming language
- File handling for storing account information 
- Structures
- VS code
- Github

To run this program, execute the following command in the terminal:
```gcc 711725UAM129.c _o message
./message```

In this output,
      1. The user need to enter the choice for the operation they want to perform.
      2. If the user want to create an account,the user want to enter choice 1 and they need to provide the last name, first name, account number, balance and pin number.
      3. If the user want to deposit money, the user need to enter choice 2 and they need to provide the account number, the amount to be deposited and the pin number for authentication. The remaining balance will be updated accordingly and displayed to the user.
      4. If the user want to withdraw money, the user need to enter choice 3 and they need to provide the account number, the amount to be withdrawn and the pin number for authentication. The remaining balance will be updated accordingly and displayed to the user.
      5. If the user want to transfer money, the user need to enter choice 4 and they need to provide the sender account number, receiver account number, the amount to be transferred and the pin number for authentication. 
      6. If the user want to delete account, the user need to enter choice 5 and they need to provide the account number and the pin number for authentication. The account will be removed from the system.
      7. If the user want to exit the program, the user need to enter choice 6 and the program will be terminated.

File Used
credit.dat

This binary file stores all account information permanently.

Each record contains:

    Account Number
    Last Name
    First Name
    Balance
    PIN

 Function            Purpose                    

createAccount()    Creates a new bank account 
deposit()          Deposits money             
withdraw()         Withdraws money            
transfer()         Transfers money            
deleteAccount()    Deletes an account         
verifyPIN()        Verifies account PIN       
enterChoice()      Displays menu options      

