#Command Reference
This is the command reference for Lorian Version 1.6. You can find more elaborative information here on each of the commands currently implemented.

!!! tip
    If you have a need for any further info, you can send the message {prefix}help <command> to the bot to get info about the command.

The prefix is not specified in this reference. You have to apply your own prefix to the commands. If you don't know the prefix, type `@lorian prefix` in the server you're using.

Another thing to note is that some commands will have an empty `Usage` field on this page. This means that the command takes no arguments and is accepted as such.

Usage with <> are required, [] are optional.

##Command reference
###General Commands

| Name | Description | Usage | Required permission |
| ---- | ----------- | ----- | ------------------- |
| invite | Invite me to your server | None | None |
| ram | Check my ram usage | None | None |
| submit | Submit ideas or bugs to a server | <idea/bug\>\|\[text\]| None |
| idea | Submit ideas or bugs for me | None | None |
| ping | Check the bot's connection speed | None | None |
| prefix | Find out my prefix | None | None |

###Fun Commands

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

###Ticket Commands

| Name | Description | Usage | Required permission |
| ---- | ----------- | ----- | ------------------- |
| tickets | I'll give you the ticket help menu | None | None |
| ticket create | Create a ticket for the server you are in | <text\|priority\> | None |
| ticket close | Close your ticket | <ticket id\> | None |
| ticket reply | Reply to a ticket | <ticket id\> <text\> | None |
| ticket join | Join a ticket as an agent | <ticket id\> | manage_messages |

Tickets must be setup be for using. Tickets also will only work in dms, except reply.
Reply and close has a special perm setup, If a user is either the author, agent or someone with manage_guild they may close or reply.

###Moderation Commands

| Name | Description | Usage | Required permission |
| ---- | ----------- | ----- | ------------------- |
| kick | I'll kick the given users | <users\> | kick_members |
| ban | I'll ban the given users | <users\> | ban_members |
| clear | I'll remove messages matching the specified criteria | \[user\] <amount\> | manage_messages |
| clearch | I'll clear an entire channel | None | manage_channels |
| mute | Mute a user for a set amount of time | <user\(s\)\>[time] | manage_messages |
| unmute | Unmute a muted user | <user\(s\)\> | manage_messages |

###Setting commands

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
