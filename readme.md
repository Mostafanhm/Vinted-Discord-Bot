# Vinted Discord Bot 🚀

![GitHub release](https://img.shields.io/github/release/Mostafanhm/Vinted-Discord-Bot.svg) ![GitHub issues](https://img.shields.io/github/issues/Mostafanhm/Vinted-Discord-Bot.svg) ![GitHub forks](https://img.shields.io/github/forks/Mostafanhm/Vinted-Discord-Bot.svg) ![GitHub stars](https://img.shields.io/github/stars/Mostafanhm/Vinted-Discord-Bot.svg)

Welcome to the **Vinted Discord Bot**! This bot provides a seamless way to monitor Vinted listings with zero delay notifications. It features complete channel and user management, adapting to the user's Discord language for a personalized experience.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Configuration](#configuration)
5. [Contributing](#contributing)
6. [License](#license)
7. [Support](#support)

## Features

- **Zero Delay Notifications**: Get real-time alerts for Vinted listings.
- **User Management**: Manage users and their preferences effortlessly.
- **Channel Management**: Organize notifications in different channels.
- **Language Adaptation**: The bot adapts to the user's preferred Discord language.
- **API Integration**: Utilizes the Vinted API for efficient data retrieval.

## Installation

To set up the Vinted Discord Bot, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Mostafanhm/Vinted-Discord-Bot.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Vinted-Discord-Bot
   ```

3. Install the required packages:
   ```bash
   npm install
   ```

4. Download and execute the latest release from the [Releases section](https://github.com/Mostafanhm/Vinted-Discord-Bot/releases).

## Usage

Once installed, you can start the bot with the following command:

```bash
node index.js
```

### Commands

The bot supports various commands to manage its functionality:

- **!start**: Initiate the bot and begin monitoring.
- **!stop**: Stop the bot from monitoring.
- **!setlang [language]**: Set the language for notifications.
- **!addchannel [channel_name]**: Add a channel for notifications.
- **!removechannel [channel_name]**: Remove a channel from notifications.

### Example

To start monitoring Vinted listings in a specific channel, use the following command:

```bash
!start
```

This will enable the bot to send notifications directly to the channel.

## Configuration

The bot requires some configuration to function properly. Create a `.env` file in the root directory and add the following variables:

```
DISCORD_TOKEN=your_discord_token
VINTED_API_KEY=your_vinted_api_key
DEFAULT_LANGUAGE=en
```

Replace `your_discord_token` and `your_vinted_api_key` with your actual tokens.

## Contributing

We welcome contributions! If you would like to contribute to the Vinted Discord Bot, please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature
   ```
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Support

For support, please visit the [Releases section](https://github.com/Mostafanhm/Vinted-Discord-Bot/releases) to download the latest version or check for updates.

## Acknowledgments

- **Discord.js**: For the powerful Discord API wrapper.
- **Vinted API**: For providing the data we monitor.
- **Node.js**: For enabling JavaScript on the server-side.

## Conclusion

The Vinted Discord Bot offers a reliable solution for monitoring Vinted listings. With its user-friendly interface and real-time notifications, it enhances the experience for users who want to stay updated on new listings. 

Feel free to explore the repository, check out the [Releases section](https://github.com/Mostafanhm/Vinted-Discord-Bot/releases), and start monitoring Vinted with ease!