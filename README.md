# ATM-C

A basic command-line ATM service program written in C. This program allows users to perform simple banking operations such as checking balance, withdrawing money, and depositing money. The user interface is text-based, making it easy to understand and use.

## Features

- **Secure**: The program requires a 4-digit PIN for access, providing a level of security.
- **Options**: Users can choose from various options in the main menu, including checking balance, withdrawing money, depositing money, and exiting the program.
- **Balance Updates**: The program displays the updated balance after successful transactions.

## Usage

1. Compile the program using a C compiler.
2. Run the compiled executable.
3. Enter your debit card number and 4-digit PIN when prompted.
4. Choose an option from the main menu to perform the desired operation.

## Code Overview

- The program uses a predefined ATM PIN (1234) for simplicity.
- Users can check their balance, withdraw money, deposit money, and exit the program.
- The interface is text-based and user-friendly.
- The program includes basic error handling for invalid inputs and insufficient balances.

## Getting Started

Clone the repository and compile the program using a C compiler:

```bash
gcc ATM.c -o ATM
```

Run the compiled executable:

```bash
./ATM
```

Follow the on-screen instructions to navigate through the ATM service.

Feel free to contribute and improve this ATM service program!
