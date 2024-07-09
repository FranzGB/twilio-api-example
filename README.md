# Twilio Messaging Handler

This project contains a Node.js function designed to handle incoming messages using Twilio's Programmable Messaging. When a message is received, it logs the incoming message and responds with a predefined message.

## Features

- Logs incoming messages to the console.
- Sends a predefined response message to the sender.
- Captures photos send to the number.
- Displays them in the `index.html` site by calling an endpoint.

## Requirements

- Node.js
- Twilio account and a Twilio phone number with SMS capabilities.

## Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/FranzGB/twilio-api-example
   ```

2. **Navigate to the project directory:**

   ```bash
   cd twilio-api-example
   ```

3. **Install dependencies:**

   ```bash
   npm install
   ```

4. **Set up Twilio credentials:**

   Create a `.env` file in the root of your project and add your Twilio Account SID and Auth Token.

   ```plaintext
   ACCOUNT_SID=your_account_sid
   AUTH_TOKEN=your_auth_token
   ```

5. **Deploy the function to Twilio:**

   This project is designed to run as a Twilio Function. Follow Twilio's documentation to deploy the function.

## Usage

Once deployed, the function will be triggered by incoming messages to your Twilio number. It logs the content of the message and responds with "Thanks for your submission! 📸".
