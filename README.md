# Discord Animated Gif Banner Welcome Bot

![Pi Day LED display preview](https://raw.githubusercontent.com/owntheweb/discord-animated-welcome-bot/master/img/welcome.gif)

![welcome bot preview](https://raw.githubusercontent.com/owntheweb/discord-animated-welcome-bot/master/img/example-discord.jpg)

This was a "thin slice" experiment to welcome new members to a Discord guild via an animated gif banner while exploring Nodejs TypeScript and dependency injection with Inversify.

## Setup

Copy the `.env.example` file to `.env`.

Create a Discord token while configuring a bot app, placing the bot in a channel, then include token in `.env`.

Install TypeScript:

```
npm install -g typescript
```

Install node modules:

```
npm i
```

Install fonts. See src/assets/fonts/README.md for details.

Run:

```
npm run prod
```

In the Discord channel, type the following:

```
ping
```

The bot should respond with `pong!`

Type the following to generate a welcome graphic (new channel members will also get a welcome graphic):

```
!join
```

## Image Credits

