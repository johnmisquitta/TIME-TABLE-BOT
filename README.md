# TIME-TABLE-BOT

[![Watch the video](https://img.youtube.com/vi/YOUR_VIDEO_ID/maxresdefault.jpg)](https://drive.google.com/file/d/1X7pxp5Pk3tB7bcODzl5ufkhn3J2FIpKm/view)

## 🤖 About the Project

This Discord bot is designed to bring the power of AI to your server! By integrating OpenAI's GPT model, the bot can respond to user queries with insightful and creative answers. Additionally, it can generate images based on user prompts, manage schedules, and handle subject resources, providing a rich and interactive experience directly within Discord.

## ✨ Features

- **AI-Powered Responses:** The bot uses OpenAI's GPT model to understand and respond to user questions, providing informative and context-aware answers.
- **Schedule Management:** Teachers can add, view, and manage lecture schedules directly from Discord. Students can easily check their schedule for any day of the week.
- **Resource Management:** Teachers can upload subject notes or resource files. Students can easily retrieve these files by requesting them with a simple command.
- **Interactive Commands:** A variety of commands are available to interact with the bot, making it a versatile tool for any Discord server.

## 🛠️ Installation

To get the bot up and running on your Discord server, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/discord-ai-bot.git
    cd discord-ai-bot
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up your environment variables:**
   - Create a `.env` file in the root directory of your project.
   - Add your Discord bot token and OpenAI API key:
     ```env
     DISCORD_TOKEN=your-discord-bot-token
     OPENAI_API_KEY=your-openai-api-key
     ```

4. **Run the bot:**
    ```bash
    python bot.py
    ```

5. **Invite the bot to your server:**
   - Use the OAuth2 URL generator on the [Discord Developer Portal](https://discord.com/developers/applications) to generate an invite link for your bot.
   - Invite the bot to your desired server.

## 🚀 Usage

Once the bot is running on your server, users can interact with it using specific commands. Below are some examples:

### AI-Powered Responses

- **Ask a Question:**
  ```bash
  !ask How do black holes work?
