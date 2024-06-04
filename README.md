# Finance API with Node.js and Express

## Overview

This project implements a financial API using Node.js and Express.

### Requirements

- **Account Creation**: Users should be able to create an account.
- **View Bank Statement**: Users should be able to view their bank statement.
- **Deposit**: Users should be able to deposit money into their account.
- **Withdrawal**: Users should be able to withdraw money from their account.
- **Search Bank Statement by Date**: Users should be able to search their bank statement by date.
- **Update Account Data**: Users should be able to update their account information.
- **Get Account Data**: Users should be able to retrieve their account information.
- **Delete Account**: Users should be able to delete their account.

### Business Rules

- **Unique CPF**: It should not be possible to register an account with an existing CPF.
- **Non-existent Account**: It should not be possible to deposit into a non-existent account.
- **Non-existent Account**: It should not be possible to view the bank statement of a non-existent account.
- **Non-existent Account**: It should not be possible to withdraw from a non-existent account.
- **Non-existent Account**: It should not be possible to delete a non-existent account.
- **Insufficient Balance**: It should not be possible to withdraw when the balance is insufficient.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine.
2. Install the necessary dependencies by running `npm install`.
3. Run the project using `npm start`.
4. Access the API endpoints to perform various operations related to account management and transactions.

## Usage

Once the project is running, you can interact with the API using various endpoints:
(exemples)
- `/create-account`: Create a new account.
- `/bank-statement`: View bank statement.
- `/deposit`: Deposit money into the account.
- `/withdraw`: Withdraw money from the account.
- `/search-by-date`: Search bank statement by date.
- `/update-account`: Update account data.
- `/get-account-data`: Retrieve account information.
- `/delete-account`: Delete the account.

## Contributing

Contributions to this project are welcome. You can fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE]([LICENSE](https://www.mit.edu/~amini/LICENSE.md)) file for details.
