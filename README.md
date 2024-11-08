
# MemesWar Bot

The **MemesWar Bot** automates daily interactions with the Memes War platform, a game where players earn points, tokens, and rewards through quests, attendance, and guild contributions. This bot simplifies tasks such as claiming treasury rewards, checking in, completing quests, and managing guild operations.

## Features

- **Log Messages**: Outputs actions with custom symbols for success, errors, warnings, and informational messages.
- **User Data Retrieval**: Fetches user stats, including honor points and token balances.
- **Quest Management**: Automates daily and single quests, including claim and reward progress.
- **Attendance**: Checks daily attendance and handles rewards.
- **Guild Operations**: Manages guild status, favorites, and transfers Warbond tokens to a designated guild.
- **Countdowns**: Pauses between certain actions, displaying a countdown.

## Requirements

- **Node.js**: Ensure that Node.js is installed.
- **Modules**: Install required modules via npm:
  ```bash
  npm install fs path axios colors readline
  ```

## Setup

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```
2. **Prepare Data File**:
   - Create a `data.txt` file in the root directory.
   - Insert your `telegramInitData` credentials for each account on separate lines.
3. **Run the Bot**:
   ```bash
   node main.js
   ```

## Usage

The bot continuously iterates over the accounts provided in `data.txt`, performing the following:
- Fetches and logs user data.
- Claims attendance and treasury rewards if available.
- Completes pending quests.
- Checks guild status and transfers tokens if conditions are met.

The bot pauses between account iterations and waits 65 minutes before restarting the entire sequence.

## License

This project is licensed under the MIT License.
