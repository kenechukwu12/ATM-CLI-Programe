# ATM-CLI-Programe
Program of the Operating system for ATM Mechaine
The code file follows a modular approach to implementing the ATM CLI program. Let's break down the main concepts used in developing the code:

1. **Functions**: The program is divided into several functions, each responsible for a specific task. Functions like `create_account()`, `login()`, `withdraw()`, `deposit()`, and `check_balance()` encapsulate specific actions that can be reused throughout the program. This modular approach improves code organization and makes it easier to understand and maintain.

2. **Customer Data Storage**: The program uses a list called `customers` to store customer account details. Each customer account is represented as a dictionary containing attributes like `name`, `pin`, `account_number`, and `balance`. The `customers` list allows for storing and retrieving customer information across different functions.

3. **User Input**: The program uses the `input()` function to obtain user input. It prompts the user with appropriate messages and stores the input in variables for further processing. For example, the user is asked to enter their name, PIN, account number, PIN during account creation and login.

4. **Account Validation**: The program validates user input at various stages to ensure correctness. For example, during login, it checks if the account number and PIN combination provided by the user match the details stored in the `customers` list. It also checks for sufficient funds before processing a withdrawal.

5. **Error Handling**: The program includes error handling to handle situations like incorrect PIN, insufficient funds, and invalid user choices. It displays appropriate error messages and prompts the user to try again or continue.

6. **Looping and Navigation**: The program is structured using a while loop to provide a menu-based interface. It allows the user to navigate through different options like account creation, login, banking operations, and exiting the program. The loop ensures that the program continues until the user chooses to exit.

7. **Clear Screen (optional)**: The program includes a `clear_screen()` function that clears the console screen. It helps in enhancing the user experience by removing previous information from the console, providing a cleaner interface.

The program implements the required features of an ATM CLI program, creating a user-friendly interface for account creation, login, and banking operations. It demonstrates the use of functions, data storage, input validation, error handling, and navigation to create a functional ATM system in the command-line interface.
