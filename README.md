# Taker-Auto-Bot
An automated bot for managing multiple Taker with proxy support.
Taker-BOT is a blockchain automation tool designed to interact with various cryptocurrency services for swapping and staking tokens. It provides a dashboard interface to monitor operations and logs, and it cycles through tasks like wrapping/unwrapping and staking/unstaking tokens.

## Features

- **Dashboard Interface**: Real-time updates on balance, network status, and transaction history.
- **Automated Cycles**: Configurable cycles for executing Transaction every 24 Hours 
- **Blockchain Interactions**: Utilizes the `ethers` library for seamless blockchain operations.
- **API Integrations**: Interacts with external APIs to check transaction statuses and claimable Points rewards.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ytbiilly/Taker-Auto-Bot.git
   cd Taker-Auto-Bot
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Edit wallets.txt file and input your private keys and wallet address (one per line)

   ```bash
   nano wallets.json
   ```

## Usage

- **Start the bot**:

  ```bash
  node index.js
  ```

- **Dashboard**: The dashboard will display real-time information about the bot's operations, Every 24 hours, network status
- **Proxy** : use free proxy from webshare


## License

This project is licensed under the ISC License.

Last updated: Sat Mar 22 03:02:38 UTC 2025
