# ATM-Management-System
Here is a README file for your **ATM Banking System** project. I will also provide instructions for sharing it.

---

# ATM Banking System

## Project Overview
The **ATM Banking System** is a C-based application designed to replicate the essential functionalities of an ATM. The system provides a secure, user-friendly interface for account management, enabling users to perform transactions such as checking balances, depositing money, withdrawing funds, and changing or recovering PINs. This project emphasizes simplicity and security, catering to real-world ATM scenarios.

---

## Features
- **User Authentication**: Secure login with a PIN and limited incorrect attempts.
- **Account Management**:
  - Check account balance.
  - Deposit money and update account balance.
  - Withdraw money with sufficient fund verification.
  - Change PIN with old PIN verification.
  - Recover forgotten PIN using account number, IFSC code, and registered mobile verification.
- **Error Handling**: Displays appropriate error messages for invalid inputs.
- **Modular Design**: Well-structured functions for different ATM operations.

---

## Technology Stack
- **Programming Language**: C
- **Development Environment**: Windows
- **Additional Libraries**:
  - `stdio.h`
  - `stdlib.h`
  - `stdbool.h`
  - `string.h`
  - `ctype.h`
  - `windows.h`

---

## Installation
1. **Clone or Download the Project**:
   - Clone the repository or download the source code.
2. **Compile the Code**:
   - Use a C compiler like GCC or an IDE like Code::Blocks or Dev-C++.
   - Ensure all required header files are included.
3. **Run the Executable**:
   - Compile and run the program to access the ATM Banking System.

---

## Usage
1. Launch the application.
2. Choose your account type (Savings or Current).
3. Enter your PIN to access the main menu.
4. Perform transactions:
   - Check balance.
   - Deposit or withdraw funds.
   - Change or recover PIN.
5. Exit the system after completing transactions.

---

## Source Code Highlights
Key functions:
- `login()`: Authenticates user PIN.
- `checkBalance(float balance)`: Displays account balance.
- `moneyDeposit(float balance)`: Deposits money and updates balance.
- `moneyWithdraw(float balance)`: Withdraws money with sufficient fund verification.
- `changePin()`: Changes the PIN securely.
- `forgetPin()`: Recovers forgotten PIN using secure verification steps.

---

## Results
The system outputs transaction details, updated balances, and error or success messages. It provides clear and concise user guidance for every step, ensuring a smooth experience.

---

## Future Enhancements
- **Database Integration**: Replace hardcoded values with a database for scalable user management.
- **GUI Support**: Add a graphical user interface for better usability.
- **Multi-User Support**: Expand the application to handle multiple accounts.

---

## License
This project is licensed under the MIT License.
