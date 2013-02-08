# HelperBot

A Node.js Minecraft bot that helps you out by performing menial tasks.

## Current Project Status

Supports Minecraft 1.4.7

## Available In-game Commands

 - '**come**' - Make the bot come to your current location.
 - '**echo** message' - Repeat the given 'message' into chat.
 - '**find** block name' - Make the bot find the coordinates of the nearest 'block name' block.
 - '**give** username [count] block name' - Make the bot /give 'username' 'count' of a given block.
 - '**gimme** [count] block name' - Make the bot /give you 'count' of a given block.
 - '**help** command' - Gives help on a given command.
 - '**masters** [add/rm username]' - Display the bot's list of masters, or add/remove a master.
 - '**quiet mode** [on/off]' - Enable/disable quiet mode.
 - '**quit**' - Make the bot leave the server.

## Usage

```sh
Usage: node helperbot.js [SERVER] [USERNAME] [OPTIONS]
Connect a mineflayer bot to SERVER as USERNAME.
By default connects 'helperbot' to localhost.

      --help               display this help and exit
      -l, --login          prompt for credentials and login to minecraft.net
      --password=PASSWORD  connect to minecraft.net with the given PASSWORD
      -p, --port=PORT      connect to the given port (defaults to 25565)
      --masters=usr1,...   set the bot's masters to usr1, ...
      -q, --quiet          causes the bot to whisper all responses
```

 - Example online mode:

```sh
helperbot server username --password=12345678
```

 - Example online mode #2:

```sh
helperbot server --login
```

 - Example offline mode:

```sh
helperbot server
```

## Installation

`npm install -g helperbot`
