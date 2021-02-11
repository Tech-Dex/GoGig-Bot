# Reddit Job Finder Discord Bot

A Discord bot that is using AsyncPRAW, a Reddit API to find jobs on subreddits and post them to your Discord channel.
I created this bot for programmers so feel free to edit keywords list and subreddit list for your requirements.

## Setup
You'll need to create:
 - Reddit Applications: https://www.reddit.com/prefs/apps
 - Discord Bot: https://discord.com/developers/applications
 
Create a local.env file with following envs:
```bash
export DISCORD_TOKEN="YOUR_DISCORD_TOKEN"
export DISCORD_GUILD="YOUR_DISCORD_GUILD"
export REDDIT_USER="YOUR_REDDIT_USER"
export REDDIT_PASSWORD="YOUR_REDDIT_PASSWORD"
export CLIENT_ID="YOUR_CLIENT_ID"
export CLIENT_SECRET="YOUR_CLIENT_SECRET"
```

## Usage

```bash
pipenv install or pip install -r requirements.txt
source envs/local.env
python main.py
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to test before pull request.

## License
[MIT](https://choosealicense.com/licenses/mit/)
