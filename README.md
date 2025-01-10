# MoneyCounter - Your Personal Finance Tracker

**MoneyCounter** is a web application designed to help users efficiently manage and track their financial transactions, including both income and expenses. This frontend repository is built using **React** and **TypeScript**, providing a seamless and interactive user experience to track finances in real time.

## Setup & Installation

### Prerequisites

- **Node.js**: Ensure you have [Node.js](https://nodejs.org/) installed.
- **npm**: npm comes bundled with Node.js.

### Steps to Get Started

1. **Clone the repository**:
    ```bash
    git clone https://github.com/DavidAslanyan/Finance-Management-App-Frontend.git
    ```
2. **Navigate into the project directory if needed**:
    ```bash
    cd MoneyCounter
    ```
3. **Install the required dependencies**:
    ```bash
    npm install
    ```

4. **Start the development server**:
    ```bash
    npm start
    ```

5. Visit [http://localhost:3000](http://localhost:3000) in your browser to see the application in action.


## Features

- **User Registration & Login**: Secure sign-up and login to manage personal finance data.
- **Add/Edit/Delete Transactions**: Users can add, edit, and delete income or expense transactions.
- **Transaction History**: View a detailed history of all financial transactions.
- **Current Balance Display**: Instantly see the current balance, reflecting income and expenses.
- **Transaction Search & Filter**: Search for specific transactions or filter by category, date, or type.
- **Export to CSV**: Easily export transaction history into a CSV file for offline use.

## Tech Stack

- **React**: A JavaScript library for building interactive user interfaces.
- **TypeScript**: Enhances JavaScript with static types for better tooling and code quality.
- **Redux**: Used for managing application state, ensuring smooth state flow.
- **React Router**: For managing navigation and routing within the app.
- **Axios**: For making HTTP requests to the backend.

## Usage

- **Register** a new account or **login** to an existing one.
- **Add** new transactions by specifying the amount, type (income or expense), category, and date.
- **Edit** or **delete** transactions as needed.
- View the **transaction history** and your **current balance** on the dashboard.
- **Search and filter** your transactions based on different parameters like date or type.
- **Export** transaction history to a CSV file for offline use or reporting.

## Code Structure

- `src/`: Contains all source code for the frontend application.
  - `components/`: Reusable components like forms, buttons, transaction list, and balance display.
  - `redux/`: Manages state for transactions, user authentication, and filters.
  - `utils/`: Utility functions for handling transactions, form validation, and CSV export.
  - `App.tsx`: The main component responsible for rendering the app's layout and routing.

## Contribution

Contributions to **MoneyCounter** are welcome! If you'd like to contribute, follow these steps:

1. Fork the repository.
2. Create a new feature branch: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -am 'Add new feature'`.
4. Push to your branch: `git push origin feature/your-feature`.
5. Create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the **React** and **TypeScript** communities for making development faster and easier.
- A special thanks to the **Flask** and **PostgreSQL** developers for their powerful backend support, even though this repository is the frontend part of the project.
