#Command Reference
This is the command reference for Lorian Version 1.6. You can find more elaborative information here on each of the commands currently implemented.
!!! tip
    On the bot you cannot change the prefix, with the bot, you must edit the config, if you are using the lorian bot please use `??` as that is the default prefix.
!!! tip
    If you have a need for any further info, you can send the message {prefix}help <command> to the bot to get info about the command.

Another thing to note is that some commands will have an empty `Usage` field on this page. This means that the command takes no arguments and is accepted as such.

Usage with <> are required, [] are optional.

##Command reference
!!! tip
    Some of these commands are not in currently with this version of lorian, Some have been removed, some commands will stay as I plan to add them to either the basic bot or sqlite bot version.
###General Commands

| Name | Description | Usage | Required permission | In Bot / Planed |
| ---- | ----------- | ----- | ------------------- | --------------- |
| invite | Invite me to your server | None | None | Planed |
| submit | Submit ideas or bugs to a server | <idea/bug\>\|\[text\]| None | Planed |
| ping | Check the bot's connection speed | None | None | In Bot |
| prefix | Find out my prefix | None | None | Default ??, not in |

###Fun Commands

All Fun and Tag commands, are not currently added, and will be added soon.

| Name | Description | Usage | Required permission |
| ---- | ----------- | ----- | ------------------- |
| say | make me say something.| <text\> | None |
| sayembed (coming soon) | make me say something in a embed | <text\> | None |
| tf | Translate something in Tringlish | <text\> | None |
| cookie | Give yourself, or a friend a cookie | \[user\] | None |
| slap (coming soon) | Slap a given user| <user\> | None |
| kill (coming soon) | Kill a given user | <user\> | None|
| noscope (coming soon) | Noscope a given user | <user\> | None |
| lenny (coming soon) | I'll give you a lenny face | None | None |
| nuke (coming soon) | Nuke a given user | <user\> | None |
| sleep (coming soon) | I'll tell a user to go to sleep | <user\> | None |

###Tag Commands

| Name | Description | Usage | Required permission |
| ---- | ----------- | ----- | ------------------- |
| tag | Help and get tag | \[tag name\] | None |
| tag new | create a new tag | <tag name\> | None |
| tag del | Delete one of you're tags | <tag\> | None |
| tag edit | Edit one of you're tags | <tag\> | None |
| tag find | Find a tag of someones | <tag\> | None |
| tag list | List all of you're or someones tags | <tag\> | None |
| tag raw | Get raw tag info | <tag\> | None |

###Moderation Commands

| Name | Description | Usage | Required permission | In Bot / Planed |
| ---- | ----------- | ----- | ------------------- | --------------- |
| kick | I'll kick the given users | <users\> | kick_members | in |
| ban | I'll ban the given users | <users\> | ban_members | in |
| clear | I'll remove messages matching the specified criteria | \[user\] <amount\> | manage_messages | Planed |
| clearch | I'll clear an entire channel | None | manage_channels | Planed |
| mute | Mute a user for a set amount of time | <user\(s\)\>[time] | manage_messages | in |
| unmute | Unmute a muted user | <user\(s\)\> | manage_messages | in |

###Setting commands
!!! tip
    Settings commands will not be in the basic version.

| Name | Description | Usage | Required permission |
| ---- | ----------- | ----- | ------------------- |
| set | Gives setting help| None | manage_guild |
| set log | Turn logs on or off | \[on/off\] | manage_guild |
| set log-ch | Set the log channel where logs are sent to | #channel | manage_guild |
| set submit-ch | Sets the channel where ideas / bugs go | #channel | manage_guild |
| set ticket-ch | Set where ticket notifications, such as create, close, and join go | #channel | manage_guild |
| set ticketmsg-ch | Set where ticket messages go from reply | #channel | manage_guild |
| set logs | Set which logging events are turned on or off | <option\|on/off\> | manage_guild |
| set prefix | Set my prefix in a server | <text\> | manage_guild |

To get all options for `set logs` leave it blank.
