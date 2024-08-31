# Bank-system-python-gui

## Overview
This is a Python-based GUI project that simulates a bank management system with functionalities for both customers and admins. The project is built using the Tkinter library for the GUI and stores data in text files. It supports multiple actions, including customer and admin login, account creation, transaction management, and account summary display.

## Features
### Admin
- **Create/Delete Admin Accounts**: Admin can create new admin accounts and delete existing ones.
- **Manage Customer Accounts**: Admin can create and delete customer accounts, as well as view account summaries.
- **Transaction Management**: Admin can monitor and manage customer transactions.

### Customer
- **Login/Sign Up**: Customers can log in to their accounts or sign up for new ones.
- **Transaction Management**: Customers can deposit or withdraw money.
- **PIN Management**: Customers can change their account PIN.
- **Account Summary**: Customers can view their account balance and transaction history.
- **Account Closure**: Customers have the option to close their bank accounts.

## Technologies Used
- **Python**: Core programming language.
- **Tkinter**: For building the graphical user interface.
- **File Handling**: Data is stored in text files, mimicking a database.

## Project Structure
```
- **/database**: Contains the customer and admin data stored in text files.
- **/images**: Stores images used in the GUI.
- **mainProject.py**: The main Python file that contains all the functionalities of the application.
```


## Data Storage
- Customer and admin data are stored in text files within the `/database` directory.
- The text files store information such as account numbers, PINs, balances, and transaction histories.

## Contribution
Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request with your changes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
