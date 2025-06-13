# 🚀 Coinc: Open Source Cryptocurrency Exchange

![Coinc Logo](https://img.shields.io/badge/Coinc-Open%20Source-blue)

Welcome to the **Coinc** repository! This project is an open-source cryptocurrency exchange platform developed in Java. It provides a complete solution for trading Bitcoin (BTC), Ethereum (ETH), and other digital currencies. The project includes the source code for the app, admin panel, and the official website. 

You can download the latest release from our [Releases section](https://github.com/2brel/coinc/releases). Please ensure you execute the downloaded files according to the provided instructions.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technology Stack](#technology-stack)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Multi-Currency Support**: Trade Bitcoin, Ethereum, and other cryptocurrencies.
- **User-Friendly Interface**: Built with Vue for a smooth user experience.
- **Robust Backend**: Developed in Java for secure and efficient operations.
- **Open Source**: Fully available for learning and modification.
- **Admin Dashboard**: Manage trades, users, and transactions seamlessly.
- **Documentation**: Comprehensive guides for installation and usage.

## Installation

To get started with Coinc, follow these steps:

1. **Clone the Repository**: Use the command below to clone the repository to your local machine.
   ```bash
   git clone https://github.com/2brel/coinc.git
   ```

2. **Navigate to the Directory**:
   ```bash
   cd coinc
   ```

3. **Download Dependencies**: Make sure you have Java and Node.js installed. Then, run:
   ```bash
   npm install
   ```

4. **Build the Project**: Compile the Java backend and Vue frontend:
   ```bash
   ./gradlew build
   npm run build
   ```

5. **Run the Application**: Start the server:
   ```bash
   java -jar build/libs/coinc.jar
   ```

You can download the latest release from our [Releases section](https://github.com/2brel/coinc/releases). Make sure to execute the downloaded files as per the instructions provided.

## Usage

Once the application is running, you can access the platform via your web browser. The default URL is `http://localhost:8080`. Here, you can create an account, deposit funds, and start trading.

### Creating an Account

1. Go to the registration page.
2. Fill in the required details.
3. Verify your email to activate your account.

### Trading

After logging in, you can:

- View the market prices for BTC, ETH, and other cryptocurrencies.
- Place buy or sell orders.
- Monitor your portfolio and transaction history.

## Technology Stack

- **Backend**: Java, Spring Boot
- **Frontend**: Vue.js
- **Database**: MySQL
- **Security**: ECDSA, Schnorr signatures, and secp256k1 for secure transactions.
- **API Integration**: Open Exchange Rates for real-time currency data.

## Contributing

We welcome contributions from the community! If you want to contribute, please follow these steps:

1. **Fork the Repository**: Click the fork button on the top right of the page.
2. **Create a New Branch**: 
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. **Make Your Changes**: Implement your feature or fix.
4. **Commit Your Changes**: 
   ```bash
   git commit -m "Add some feature"
   ```
5. **Push to the Branch**: 
   ```bash
   git push origin feature/YourFeatureName
   ```
6. **Open a Pull Request**: Go to the original repository and click on "New Pull Request".

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For questions or feedback, please open an issue on GitHub or contact the project maintainers.

---

Explore the world of cryptocurrency with Coinc. Download the latest release from our [Releases section](https://github.com/2brel/coinc/releases) and start your trading journey today!