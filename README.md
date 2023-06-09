# Gamepedia_Bot
The Gamepedia Bot is a bot that suggests indoor and outdoor games to play and provides information and rules about the suggested game using the OpenAI GPT API.


Features
•	Generates game suggestions for indoor and outdoor activities.
•	Retrieves information and rules about the suggested game using the OpenAI GPT API.
•	Displays an image related to the suggested game using the pexel image generation API.
•	Built with the Discord.py library.


Installation
•	Clone this repository:
•	Install the required dependencies:
•	Obtain API keys:
o	Discord bot token: Obtain a bot token by creating a new bot on the Discord Developer Portal.
o	OpenAI GPT API key: Sign up for an API key at the OpenAI website.
o	Pexels API key: Get an API key from the Pexels API.
•	Update the configuration:
o	Replace the TOKEN variable in the code with your Discord bot token.
o	Replace the openai_api_key variable in the code with your OpenAI GPT API key.
o	Replace the pexels_api_key variable in the code with your Pexels API key.



Usage
•	Invite the bot to your Discord server using the OAuth2 URL generated on the Discord Developer Portal.
•	Run the bot:
o	Execute the following command: python bot.py
•	Use the bot by mentioning it with the command prefix (e.g., !game_suggestion indoor).

How to Run:

•	Set up the environment:
	Make sure you have Python installed on your system. You can download it from the official Python website (https://www.python.org).
	Install the required dependencies.
•	Obtain the necessary API keys:
	Discord bot token: Create a new bot on the Discord Developer Portal (https://discord.com/developers/applications) and copy the bot token.
	OpenAI GPT API key: Sign up for an API key at the OpenAI website (https://openai.com).
	Pexels API key: Obtain an API key from the Pexels API (https://www.pexels.com/api).
•	Update the code with API keys:
	Open the code file in your preferred code editor.
	Replace the value of the TOKEN variable with your Discord bot token.
	Replace the value of the openai_api_key variable with your OpenAI GPT API key.
	Replace the value of the pexels_api_key variable with your Pexels API key.
•	Run the code:
	Open a terminal or command prompt or any other platform to run this code.
	Navigate to the directory where your code file is located.
	Execute the command python <filename>.py to run the code (replace <filename> with the actual name of your code file).
•	Interact with the bot:
	Once the code is running, the bot will connect to Discord and be ready to receive commands.
	In your Discord server, mention the bot using the command prefix followed by the desired command. For example, !game_suggestion indoor.
	The bot will generate a game suggestion based on the provided command and respond with game information and an image.

