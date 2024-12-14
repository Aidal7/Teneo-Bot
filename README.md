# Teneo Bot

## Description
Teneo bot is a simple tool designed to automate the node interaction.

## Features
- **Automated node interaction**

## Prerequisites
- [Node.js](https://nodejs.org/) (version 12 or higher)

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/recitativonika/teneo-bot.git
   ```
2. Navigate to the project directory:
   ```bash
   cd teneo-bot
   ```
4. Install the necessary dependencies:
   ```bash
   npm install
   ```

## Usage

1. Set the `account.js`, `config.js` and `proxy.txt` before running the script. Below how to setup this fie.
2. Configuration:
   Modify the `account.js` file to set your account parameters
```
module.exports = [
  {
    email: "account1@example.com",
    password: "password1"
  },
  {
    email: "account2@example.com",
    password: "password2"
  },
  // Add more accounts as needed
];
```
 Modify the `config.js` file if you want to use proxy or not, default is false (not use proxy)
```
const useProxy = false; // (set true if want to use proxy, false if not)

module.exports = {
  useProxy
};
```
 Modify and set the `proxy.txt` file if you want to use proxy
```
ip:port
username:password@ip:port
http://ip:port
http://username:password@ip:port
```
3. Run the script:
```bash
node index.js
```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Note
This script only for testing purpose, using this script might violates ToS and may get your account permanently banned.

Extension link : https://chromewebstore.google.com/detail/teneo-community-node/emcclcoaglgcpoognfiggmhnhgabppkm

My reff code if you want to use :) : 
```Bash
 HIuMT
```
