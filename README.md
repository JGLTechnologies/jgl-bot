<a href="https://jgltechnologies.com/discord">
<img src="https://discord.com/api/guilds/844418702430175272/embed.png">
</a>

# JGL Bot

Support for the bot can be given in the issues tab of the repository, at <a href="https://jgltechnologies.com/contact">https://jgltechnologies.com/contact</a>, or on our <a href="https://jgltechnologies.com/discord">Discord server</a>.

<a href="https://jgltechnologies.com/bot/invite">Invite Link</a>

## Config

View config using `/config`
Reset config using `/config reset`

<br>

Setting a mute role:

`/set role name: Mute role: @muted`
Leave role empty to unset it.

<br>

Valid role names:
  - Mute (Added when muted)
  - Mute Remove (Removed when muted)
  - Staff (Allows access to most admin commands)

<br>

Setting a logging channel:

`/set channel name: Logging channel: #logging`
Leave channel empty to unset it.

<br>

Valid channel names:
  - Welcome (Welcome messages are sent here)
  - Goodbye (Goodbye messages are sent here)
  - Logging (Logs are sent here)

<br>

Setting a welcome message:

`/set message name: Welcome message: {member} has joined the server!`
 Leave message empty to unset it.
 Message have a max of 1000 charaters.
 
<br>

Valid message names:
  - Welcome (Welcome message)
  - Goodbye (Goodbye message)

Setting a warning punishment:

`/set punishment punishment: Temp Ban warning: 7 duration: Days number: 5`
Leave punishment empty to unset it.
This will ban someone for 5 days when they get 7 warnings. Duration and number are not need when the punishment is not temporary.

<br>

Valid punishments:
  - Kick
  - Ban
  - Mute
  - Timeout
  - Temp Ban
  - Temp Mute

<br>

## Role Dependencies

A role dependecy is when a role is dependent on another role. So if one role gets removed so does the dependent role.
There is a max of 20 per server.

Creating a role dependency:

`/dependencies add role: @staff dependent: @helper`
If @staff is removed, @helper will also be removed

<br>

Removing a role dependency:

`/dependencies remove role: @staff dependent: @helper`

<br>

Clear all dependencies:

`/dependencies clear`

<br>

List all role dependencies:

`/dependencies list`

<br>

## Reaction Roles

To delete the reaction role from the list just delete the message. If that does not work, use the `/rr remove` command

Creating a reaction role:

`/rr create emojis: 🔴, 🔵 roles: @red, @blue title: Colors description: Select your favorite color`

<br>

Clearing all reaction roles:


`/rr clear`


Listing recent reaction roles:

`/rr list`

<br>

## Tickets

To use the tickets feature you must run the `/tickets setup` command.

Creating a ticket:

`/tickets create reason: I need support`

<br>

Closing a ticket (must be in the ticket channel):

`/tickets close`

<br>

View the current ticket config:

`/tickets config`






