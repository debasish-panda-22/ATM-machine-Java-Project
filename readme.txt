# ATM Machine Program in Java

## Overview
This is a simple ATM Machine simulation written in Java. The program allows users to log in using a customer number and PIN, access their checking and savings accounts, and perform basic banking operations such as checking balances, withdrawing money, and depositing funds.

## Features
- **User Authentication**: Secure login using a customer number and PIN.
- **Account Types**: Support for checking and savings accounts.
- **View Balance**: Check the current balance of the selected account.
- **Withdraw Funds**: Withdraw money from the checking or savings account.
- **Deposit Funds**: Deposit money into the checking or savings account.
- **Exit Option**: Allows users to exit the ATM interface.

## How to Run
1. **Compile the program**  
   Open a terminal or command prompt in the project directory and compile all `.java` files using:
   ```
   javac *.java
   ```

2. **Run the program**  
   Start the ATM system by running:
   ```
   java ATM
   ```

3. **Login Credentials**  
   The program currently has predefined test credentials:
   - Customer Number: `952141`, PIN: `191904`
   - Customer Number: `989947`, PIN: `717976`

4. **Follow On-Screen Instructions**  
   - Enter your customer number and PIN to log in.
   - Choose an account type (Checking/Savings).
   - Select an operation (View Balance, Withdraw, Deposit, Exit).

## File Structure
- **ATM.java**: The main class that starts the program.
- **OptionMenu.java**: Handles user interactions and menu options.
- **Account.java**: Manages account details such as balances and transactions.

## Notes
- This is a console-based program with hardcoded customer data.
- To add more users, modify the `HashMap` in `OptionMenu.java`.
- No actual database is used; data resets upon restart.

## License
This project is open-source and can be modified as needed.


