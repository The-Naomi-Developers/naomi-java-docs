# Category: **Moderation**

> ⚠️ All punishments issued to users are stored in the our database.
> To see all punishments for a specific user on the current server, use the `/punishments` command.

- [`/ban <user> [reason] [delete_days]`](/en_us/moderation.html#ban-user-reason-delete_days)
- [`/kick <user> [reason]`](/en_us/moderation.html#ban-user-reason)
- [`/mute <user> [reason]`](/en_us/moderation.html#mute-user-reason)
- [`/unmute <user> [reason]`](/en_us/moderation.html#unmute-user-reason)

### `/ban <user> [reason] [delete_days]`
Ban the user `user` for `reason`. Or without a reason, if you did not specify one. Bans the user by deleting all of their posts for the last `delete_days`. If the number of days is not specified, the value **7** will be used.

> **Cooldown**: 5 seconds     
> **Required permissions**: `Ban members`   
> **Required conditions**: *the bot's highest role, as well as your highest role, must be higher than that of the punished member.*

### `/kick <user> [reason]`
Kick the user `user` because of `reason`. If no reason is given, no reason will be given, obviously.

> **Cooldown**: 5 seconds   
> **Required permissions**: `Kick Members`   
> **Required conditions**: *the bot's highest role, as well as your highest role, must be higher than that of the punished member.*

### `/mute <user> [reason]`
Prevent the user `user` from sending messages to chat by giving a special mute-role. You can set up this mute-role using the `/mute-role` command.

> **Cooldown**: 5 seconds   
> **Required permissions**: `Manage roles`   
> **Required conditions**: *the bot's highest role, as well as your highest role, must be higher than that of the punished member.*

### `/unmute <user> [reason]`
Return the user `user` ability to send messages to the chat, mute-role will be removed. You can set up this mute-role using the `/mute-role` command.

> **Cooldown**: 5 seconds   
> **Required permissions**: `Manage roles`   
> **Required conditions**: *the bot's highest role, as well as your highest role, must be higher than that of the punished member.*
