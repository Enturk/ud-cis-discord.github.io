---
waltz:
  title: Staff Commands
  resource: page
  published: false
layout: page
title: Staff Commands
permalink: staff_pages/staff%20commands
---
## Running Commands

As staff, you have access to some commands not listed in the general [commands page][29]. You run them the same as the
other commands, using `s;[command] [arguments]`in any channel that Sage is in, although we recommend running staff
commands in staff-only channels.

### Staff Commands

**addassignment**

- Description: Adds an assignment to a given course ID's assignment list

- Usage: `s;addassignment <course ID>|<assignmentID(s)>`

- Aliases: `adda`


**google**

- Description: Have Sage google something for someone

- Usage: `s;google <query>`

- Aliases: `lmgt`
, `lmg`


**lookup**

- Description: Looks up information about a given user

- Usage: `s;lookup <user>`


**mute**

- Description: Gives the muted role to the given user.

- Usage: `s;mute <user>`


**resetlevel**

- Description: Resets a given user's message count.

- Usage: `s;resetlevel <user>|[to_subtract|to_set_to]`

- Aliases: `reset`

- More info: Using with no value will reset to 0. A positive integer will
	set their message count and a negative will subtract that from their total


**roleinfo**

- Description: Gives information about a role, including a list of the members who have it.

- Usage: `s;roleinfo <role>`


**sudoreply**

- Description: Reply to a question asked through Sage.

- Usage: `s;sudoreply <questionID> <response>`

- Aliases: `sreply`

- More info: Responses get sent to the askers DMs. This command will tell you it failed if it cannot send the DM.


**warn**

- Description: Warns a user for breaking the rules and deletes the offending message.

- Usage: `s;warn [reason]`

- More info: This command must be used when replying to a message.


**whois**

- Description: Gives an overview of a member's info.

- Usage: `s;whois <user>`

- Aliases: `member`

[29]: https://ud-cis-discord.github.io/pages/commands (Commands)