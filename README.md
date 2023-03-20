# PNG Metadata Discord Bot

This Discord bot extracts metadata from PNG images and sends it to users on request.

Created by: axsddlr (S6yx#3618)

## Setup

1. Clone the repository and navigate to the directory
2. Install dependencies with `pip install -r requirements.txt`
3. Create a new Discord application and bot account
4. Copy the bot token and set it as an environment variable named `DISCORD_TOKEN`
5. Replace `TARGET_GUILD_ID` and `TARGET_CHANNEL_ID` with the ID of the guild and channel where the bot should operate
6. Run the bot with `python bot.py`

## Usage

1. Upload a PNG image to the designated channel
2. React with the 🔍 emoji to receive the image metadata in a DM from the bot
3. React with the 📥 emoji to receive the original image file in a DM from the bot
