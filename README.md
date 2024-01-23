# obmnl-flask_assignment

A simple Flask web application for managing transactions.

## Features

- Add new transactions with date and amount.
- Edit existing transactions.
- Delete transactions.
- Search transactions based on amount range.
- View total balance.

## Installation

1. Clone the repository:

    ```bash
    git clone https://PromiseUgochukwuNnanemere/obmnl-flask_assignment.git
    ```

2. Navigate to the project directory:

    ```bash
    cd obmnl-flask_assignment
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the Flask application:

    ```bash
    python app.py
    ```

2. Open your browser and go to [http://localhost:5000](http://localhost:5000).

## Routes

- `/`: List all transactions and display total balance.
- `/add`: Add a new transaction.
- `/edit/<int:transaction_id>`: Edit an existing transaction.
- `/delete/<int:transaction_id>`: Delete a transaction.
- `/search`: Search transactions based on amount range.
- `/balance`: View total balance.

## Contributing

Contributions are welcome! Please follow the [Contributing Guidelines](CONTRIBUTING.md).
