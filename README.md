# Discord-Chatbot

A self-learning chatbot for discord made with [Chatterbot](https://github.com/gunthercox/ChatterBot) and [Discord.py](https://github.com/Rapptz/discord.py)

## Running in container

Go to the project's directory then run

```bash
docker build -t discord_chatbot .
docker run --env TOKEN=<YOUR BOT TOKEN> --net=host discord_chatbot
```
