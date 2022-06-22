# OpenAI Discord Bot

Intended as a learning experiment to become familiar with how OpenAI's completion models work, this bot was developed as a joke.

It was _very_ funny.

However it did prove to be incredibly interesting. Seeing how OpenAI's models responded to a crowd of people throwing all sort of prompts at it sometimes resulted in some incredible responses. For instance, we learned:

1. It's actually pretty good at writing songs
2. It can write legitimate, valid code
3. It really likes World of Warcraft for some reason

## Disclaimer

This was done with groups that I am close friends with and the server owners approved that this bot was added. Don't go around asking people to add random bots to their Discord server. It's super rude.

## Setup

Copy the `config.json.ph` file to `config.json` and provide your [OpenAI API Key](https://beta.openai.com/account/api-keys) and [Discord App Token](https://discord.com/developers). You can either then compile and run the bot:

```bash
go build
./openai-discord-bot
```

Or run it directly with `go run`

```bash
go run bot.go
```

You can then [add your bot to your Discord server](https://discord.com/developers/docs/getting-started#configuring-a-bot) and interact with it by at-mentioning it directly (ie. `@botname how are you?`).
