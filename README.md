# Writing the README content to a file so the user can download it.

readme_content = """
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
