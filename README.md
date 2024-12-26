# Memex-bot

Memex Automation Check-in Tool

This is an automation script written in Node.js, designed to perform the following tasks on the Memex platform:

- Auto check-in.
- Auto claim SBT (if the account meets the requirements).
- Scheduled loop to repeat tasks at fixed intervals (every 12 hours).

## Features
- **Auto Check-in**: Checks the daily check-in status and completes the check-in automatically.
- **SBT Claiming**: Determines if the account meets the requirements and claims SBT automatically.
- **Scheduled Loop**: Repeats tasks every 12 hours, supports multiple accounts.
- **Colorful Log Output**: Displays task status for easier monitoring.

## Requirements
- Node.js (>= 14.0.0)

### Dependencies
- `axios`
- `chalk`
- `random-useragent`

## Installation and Setup

1. Clone the project:
   ```bash
   git clone https://github.com/ziqing888/Memex-bot.git
   cd Memex-bot

2. Install Depencies:
   ```bash
   npm install


   Prepare the data.txt file:

Save the user's query_id to the data.txt file in the project root directory, one per line. This file is required to simulate user actions.
Create a queries.txt file in the project directory to configure QueryIDs (user identifiers).

🔑 Get QueryID
If you're using the Telegram WebApp, you can obtain your QueryID by following these steps:

Open your Telegram WebApp.

Press F12 to open Developer Tools and switch to the Console panel.

Enter the following command to get initData:
```bash
copy(Telegram.WebApp.initData)

You’ll get something like:
query_id=...&user=%7B%22username%22%3A%22Alexyamin%22%7D&...

Running the Script :
   ```bash
   node memex-proxy.js


















