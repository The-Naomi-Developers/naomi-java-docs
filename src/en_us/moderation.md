# Category: **Moderation**
### `/say <content> [textchannel]`
Send message on behalf of the bot. If any **text channel** is specified
as the `textchannel` argument, the message will be sent there.

> **Cooldown**: 5 seconds  
> **Required permissions**: `Manage channels`   
> **Required conditions**: *if you specify the `textchannel` argument, be kind enough to specify a **text** channel.*

### `/ban <user> [reason] [delete_days]`
Ban the user `user` for `reason`. Or without a reason, if you did not specify one. Bans the user by deleting all of their posts for the last `delete_days`. If the number of days is not specified, the value **7** will be used.

> **Cooldown**: 5 seconds     
> **Required permissions**: `Ban members`   
> **Required conditions**: *the bot's highest role, as well as your highest role, must be higher than that of the punished member.*

### `/kick <user> [reason]`
Kick the user `user` because of `reason`. If no reason is given, no reason will be given, obviously.

> **Cooldown**: 5 секунд   
> **Required permissions**: `Kick Members`   
> **Required conditions**: *the bot's highest role, as well as your highest role, must be higher than that of the punished member.*
