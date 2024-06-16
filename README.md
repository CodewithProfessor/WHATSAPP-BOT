# WhatsApp Bot

A versatile WhatsApp Bot built using Node.js and the Baileys library. This bot can handle a variety of tasks including downloading content, managing groups, and more.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Features

- Download content from various sources
- Group management
- Message handling
- Web scraping
- TikTok and YouTube integrations
- Customizable plugins

## Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/yourusername/whatsapp-bot.git
    cd whatsapp-bot
    ```

2. **Install dependencies:**

    ```sh
    npm install
    ```

3. **Start the bot:**

    ```sh
    npm start
    ```

## Usage

- To start the bot, run `npm start`.
- Ensure you have your WhatsApp account linked by scanning the QR code that appears when you start the bot.

## Configuration

### app.json

Configuration settings for the application.

### settings.js

Modify settings according to your needs.

### lib/owner.json

Contains owner-related information and settings.

### lib/vajira_rathnayaka.json

Contains user or developer-specific information.

## Dependencies

- [@whiskeysockets/baileys](https://github.com/VajiraTech/VAJIRA-BAILEYS)
- [axios](https://www.npmjs.com/package/axios)
- [cheerio](https://www.npmjs.com/package/cheerio)
- [express](https://www.npmjs.com/package/express)
- [ffmpeg-installer](https://www.npmjs.com/package/@ffmpeg-installer/ffmpeg)
- [puppeteer](https://www.npmjs.com/package/puppeteer)
- And many more...

For a full list of dependencies, please refer to the `package.json` file.

## Project Structure

- **index.js**: Main entry point of the application.
- **settings.js**: Configuration settings for the application.
- **lib/**: Contains various utility modules and database handlers.
  - **apkdl.js**: Functions related to APK downloads.
  - **command.js**: Handles command parsing and execution.
  - **database.js**: Manages database connections and queries.
  - **scraper.js**: Functions for web scraping.
  - **tiktok.js**: Functions related to TikTok data handling.
  - **msg.js**: Handles message-related operations.
  - And more...
- **plugins/**: Contains various plugins that add functionality to the bot.
  - **bugs.js**: Handles bug-related operations.
  - **convert.js**: Functions for converting data formats.
  - **download.js**: Handles downloading operations.
  - **group.js**: Functions related to group operations.
  - **search.js**: Handles search functionality.
  - And more...

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
