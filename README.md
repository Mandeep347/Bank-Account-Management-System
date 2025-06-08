Project Title : Bank Account Management System

Project Description : A simple console-based Bank Account Management System built using C.
It allows users to register, login, and perform wallet transactions like credit, debit, and view account information.

Features :-
-New user registration with email validation
-Secure login with password check
-Auto-generated 3-digit client ID
-Wallet system with:
 >Balance display
 >Credit and Debit operations
 >Account details display

Technologies Used :-
Language : C
Libraries : stdio.h, stdlib.h, string.h, time.h

Getting Started :-
1. Use any C compiler like GCC. Example (Linux/macOS/Windows with GCC):
2. gcc bank.c -o bank./bank
3. Or compile and run in any C IDE (like Code::Blocks, Dev-C++, Turbo C).

How it Works:-
1. Main Menu: User chooses between Login or Register.
2. Registration Flow:
   -User enters name and a .com email address.
   -System validates email.
   -A unique client ID is generated using rand().
   -User sets a password.
   -Initial wallet balance is set to 0.
3. Login Flow:
   -User enters client ID and password.
   -If valid, user is welcomed and shown the wallet dashboard.
4. Wallet Dashboard Options:
   a. Credit: Add money to wallet.
   b. Debit: Deduct money from wallet (checks for sufficient balance).
   c. Main menu: Returns to main screen.
   d. Account Info: View name, email, masked password, and wallet balance.

Sample Output:  
-------Choose an option------

1. Login  or   2. Register
-----New Registration----

Enter your first name: John
Enter your last name: Doe
Enter your email address: john.doe@example.com
Create a password: pass123
Welcome John ! Your Client Id is 274
Registration Successful

Limitations : 
-No file/database storage — data is lost on program exit.
-Max 20 users can be registered (array[20] limit).
-Passwords are stored in plain text (not secure for production).

Author : Mandeep Chauhan - B.Tech CSE Student (AKTU university)

License : This project is open-source under the MIT License.
