# Khidmat

Welcome to Khidmat! This is a mini project developed to facilitate charitable donations. Users can sign up, log in, donate everyday items, and also donate money via credit and debit cards.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About

Khidmat is a web application designed to help users donate both everyday items and money to those in need. Whether you want to contribute physical goods or monetary support, Khidmat makes the process simple and efficient.

## Features

- **User Authentication:** Sign up and log in securely.
- **Donate Items:** Users can donate everyday items through the platform.
- **Monetary Donations:** Secure transactions via credit and debit cards.
- **User Dashboard:** Manage your donations and profile.

## Tech Stack

- **Backend:** Flask, SQLAlchemy
- **Frontend:** HTML, CSS, JavaScript (Bootstrap for styling)
- **Database:** SQLite (for development)
- **Payment Processing:** Integrate with a payment gateway like Stripe or PayPal (to be implemented)

## Getting Started

To get a local copy up and running, follow these steps:

### Prerequisites

- [Python](https://www.python.org/downloads/)
- [pip](https://pip.pypa.io/en/stable/installation/)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/syed735/Charity-webapp.git
    ```

2. Navigate to the project directory:
    ```sh
    cd Charity-webapp
    ```

3. Create a virtual environment:
    ```sh
    python -m venv venv
    ```

4. Activate the virtual environment:
    - On Windows:
      ```sh
      venv\Scripts\activate
      ```
    - On macOS/Linux:
      ```sh
      source venv/bin/activate
      ```

5. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

6. Set up the database:
    ```sh
    flask db init
    flask db migrate -m "Initial migration."
    flask db upgrade
    ```

7. Run the application:
    ```sh
    flask run
    ```

    The application will be available at `http://127.0.0.1:5000`.

## Usage

1. **Sign Up:** Create a new account by providing your details.
2. **Log In:** Access your account using your credentials.
3. **Donate Items:** List items you wish to donate.
4. **Donate Money:** Use the secure payment gateway to make monetary donations.
5. **Manage Donations:** View and manage your donations from the user dashboard.

## Contributing

We welcome contributions! Please follow these steps to contribute:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

Please make sure to update tests as appropriate.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Syed Sufiyan - sufiyanahmedsyed388@gmail.com

Project Link: https://github.com/syed735/Charity-webapp

---


