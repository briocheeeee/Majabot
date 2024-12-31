
# MajaBot

MajaBot is a powerful and versatile Discord bot built with `discord.js`. It is designed to help server admins with various moderation tasks, enhance server interactions, and provide fun utilities. This bot is constantly being developed and improved to provide a better experience for users and admins alike.

## Features

- **Moderation**: Kick, ban, warn, mute, and manage server members.
- **Fun Commands**: Fun features like trivia, jokes, and more!
- **Utility Commands**: Get server info, user stats, and perform other useful tasks.
- **Role Management**: Assign and remove roles with ease.
- **Premium Commands**: Access exclusive features with a premium subscription.

## Setup

To get MajaBot up and running, follow the steps below:

### Prerequisites

- **Node.js**: Ensure you have Node.js installed on your machine. You can download it [here](https://nodejs.org/).
- **Discord Developer Account**: You'll need to create a bot on Discord's developer portal [here](https://discord.com/developers/applications).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/briocheeeee/Majabot.git
   ```

2. Install dependencies:
   ```bash
   cd MajaBot
   npm install
   ```

3. In your `main.js` file, make sure you add your bot token directly in the `client.login()` method:
   ```js
   client.login('your_discord_bot_token');
   ```

4. Run the bot:
   ```bash
   node main.js
   ```

### Commands

Here are some of the available commands for **MajaBot**:

#### Moderation Commands

- `;kick @user`: Kicks a member from the server.
- `;ban @user`: Bans a member from the server.
- `;warn @user`: Warns a user for misconduct.
- `;clear <number>`: Clears a specified number of messages in the chat.
- `;mute @user`: Mutes a user in the server.

#### Fun Commands

- `;joke`: Tells a random joke.
- `;quote`: Gives a random quote.
- `;trivia`: Starts a trivia game.

#### Utility Commands

- `;userinfo @user`: Displays user information.
- `;serverinfo`: Displays information about the server.
- `;stats`: Shows bot stats and uptime.

#### Role Management

- `;addrole @user @role`: Adds a role to a user.
- `;removerole @user @role`: Removes a role from a user.

#### Premium Commands

- `;premiumcommand1`: Exclusive command for premium users.
- `;premiumcommand2`: Another premium-only command, granting special privileges to premium members.
- **Note**: Premium commands are available to users with a premium subscription and can unlock additional features like special roles, enhanced permissions, and more.

### Contributing

If you want to contribute to MajaBot, feel free to fork the repository, make changes, and submit a pull request. We welcome any help in improving the bot, adding new features, or fixing bugs.

### License

MajaBot is open-source and available under the [MIT License](LICENSE).

### Support

If you encounter any issues or have questions about MajaBot, feel free to open an issue on GitHub or contact the developer directly on Discord.

---

## Upcoming Features

- More commands and features!
- Customizable command prefixes.
- Enhanced error handling and logging.
- Premium feature expansion!
