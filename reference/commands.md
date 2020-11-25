# Commands

To get a list of available commands, do !help on your server.

## Arguments & Flags

Most commands accept arguments and/or flags.  
According to the **Type** of the argument or flag you can provide different values.

### Boolean

This arguments expects `true` or `false`. You can also use `yes` and `no`.

### Number

This arguments expects a number

### Enum

This arguments expects a value from a specific set of valid values.

> Depending on the command the valid values can vary. Use `!help <command>` (eg. `!help addRank`) to get more information about the command and the valid values for the enum.

### Invite Code

This arguments expects a Discord Invite Code.

> You can put only the part after `https://discord.gg/` to prevent Discord from creating a preview.

### User

This arguments expects a Discord User. You can use any of the following methods to provide a user:

- Mention the user: `@Valandur`
- Use their ID: `102785693046026240`
- Use their name: `Valandur`
- Use their name and discriminator: `Valandur#3581`
- Use quotes if their name has a space: `"Valandur with a space"`

### Role

This arguments expects a Discord Role. You can use any of the following methods to provide a role:

- Mention the role: `@Admin`
- Use the ID: `102785693046026240`
- Use the name: `Admin`
- Use quotes if the name has a space: `"Admin with a space"`

### Channel

This arguments expects a Discord Channel. You can use any of the following methods to provide a channel:

- Mention the channel: `#general`
- Use the ID: `409846838129197057`
- Use the name: `general`
- Use quotes if the name has a space: `"general with a space"`

### Command

This argument expects a command of this bot. You can use any of the following methods to provide a command:

- Use the command name: `invites`
- Use an alias of the command: `p`

### Text

This arguments expects any text. You can use quotes (`"Text with quotes"`) for text that has spaces.

> If the text is the last argument you don't have to use quotes.

### Date

This argument expects a date. You can use various formats, but we recommend: `YYYY-MM-DD`

### Duration

This argument expects a duration. The following duration types are supported:

- Seconds: `s` (`5s` = 5 seconds)
- Minutes: `min` (`3min` = 3 minutes)
- Hours: `h` (`4h` = 4 hours)
- Days: `d` (`2d` = 2 days)
- Weeks: `w` (`1w` = 1 week)
- Months: `mo` (`6mo` = 6 months)
- Years: `y` (`10y` = 10 years)

## Overview

### Invites

| Command                           | Description                                        | Usage                                                                    |
| --------------------------------- | -------------------------------------------------- | ------------------------------------------------------------------------ |
| [addInvites](#addInvites)         | Adds/Removes invites to/from a member.             | !addInvites \<user\> \<amount\> [reason]                                 |
| [clearInvites](#clearInvites)     | Clear invites of the server/a user.                | !clearInvites [-d value\|--date=value][-cb\|--clearbonus] [user]         |
| [createInvite](#createInvite)     | Creates unique invite codes.                       | !createInvite \<name\> [channel][maxuses] [expires][temporarymembership] |
| [info](#info)                     | Show info about a specific member.                 | !info \<user\> [details][page]                                           |
| [inviteCodes](#inviteCodes)       | Get a list of all your invite codes                | !inviteCodes                                                             |
| [inviteDetails](#inviteDetails)   | Shows details about where your invites are from.   | !inviteDetails [user]                                                    |
| [invites](#invites)               | Show personal invites.                             | !invites [user]                                                          |
| [leaderboard](#leaderboard)       | Show members with most invites.                    | !leaderboard [page]                                                      |
| [removeInvites](#removeInvites)   | Removes a specified amount of invites from a user. | !removeInvites \<user\> \<amount\> [reason]                              |
| [restoreInvites](#restoreInvites) | Restore all previously cleared invites.            | !restoreInvites [user]                                                   |
| [subtractFakes](#subtractFakes)   | Remove fake invites from all users.                | !subtractFakes                                                           |
| [subtractLeaves](#subtractLeaves) | Remove leaves from all users                       | !subtractLeaves                                                          |

### Ranks

| Command                   | Description                                   | Usage                                |
| ------------------------- | --------------------------------------------- | ------------------------------------ |
| [addRank](#addRank)       | Add a new rank.                               | !addRank \<role\> \<invites\> [info] |
| [fixRanks](#fixRanks)     | Deletes any ranks where the role was deleted. | !fixRanks                            |
| [ranks](#ranks)           | Show all ranks.                               | !ranks [page]                        |
| [removeRank](#removeRank) | Remove a rank.                                | !removeRank \<rank\>                 |

### Config

| Command                                 | Description                                               | Usage                                       |
| --------------------------------------- | --------------------------------------------------------- | ------------------------------------------- |
| [botConfig](#botConfig)                 | Show and change the config of the bot.                    | !botConfig [key][value]                     |
| [config](#config)                       | Show and change the config of the server.                 | !config [key][value]                        |
| [interactiveConfig](#interactiveConfig) | Interactive Config                                        | !interactiveConfig                          |
| [inviteCodeConfig](#inviteCodeConfig)   | Show and change the config of invite codes of the server. | !inviteCodeConfig [key][invitecode] [value] |
| [memberConfig](#memberConfig)           | Show and change the config of members of the server.      | !memberConfig [key][user] [value]           |
| [permissions](#permissions)             | Configure permissions to use commands.                    | !permissions [cmd][role]                    |

### Info

| Command             | Description                                                                       | Usage           |
| ------------------- | --------------------------------------------------------------------------------- | --------------- |
| [botInfo](#botInfo) | Get general information about the bot.                                            | !botInfo        |
| [credits](#credits) | Show developers and contributors of the bot.                                      | !credits        |
| [getBot](#getBot)   | Get an invite link for the bot.                                                   | !getBot         |
| [help](#help)       | Display help.                                                                     | !help [command] |
| [members](#members) | Show member count of current server.                                              | !members        |
| [ping](#ping)       | Ping the bot                                                                      | !ping           |
| [prefix](#prefix)   | Shows the current prefix of the bot.                                              | !prefix         |
| [setup](#setup)     | Help with setting up the bot and checking for problems (e.g. missing permissions) | !setup          |
| [support](#support) | Get an invite link to our support server.                                         | !support        |

### Premium

| Command                   | Description                                                              | Usage             |
| ------------------------- | ------------------------------------------------------------------------ | ----------------- |
| [export](#export)         | Export data of InviteLogger to a csv sheet.                              | !export \<type\>  |
| [premium](#premium)       | Info about premium version of InviteLogger.                              | !premium [action] |
| [tryPremium](#tryPremium) | Try the premium version of InviteLogger for free for a limited duration. | !tryPremium       |

### Moderation

| Command                               | Description                                                                                                                                   | Usage                                                            |
| ------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| [ban](#ban)                           | Ban a member from the server.                                                                                                                 | !ban [-d value\|--deleteMessageDays=value] \<user\> [reason]     |
| [caseDelete](#caseDelete)             | Delete a specific case.                                                                                                                       | !caseDelete \<caseNumber\> [reason]                              |
| [caseView](#caseView)                 | View info about a specific case.                                                                                                              | !caseView \<caseNumber\>                                         |
| [check](#check)                       | Check violation and punishment history of a user.                                                                                             | !check \<user\>                                                  |
| [clean](#clean)                       | Clean a channel of certain message types.                                                                                                     | !clean \<type\> [numberOfMessages]                               |
| [cleanShort](#cleanShort)             | Clear short messages                                                                                                                          | !cleanShort \<maxTextLength\> [numberOfMessages]                 |
| [cleanText](#cleanText)               | Delete messages containing certain keywords.                                                                                                  | !cleanText \<text\> [numberOfMessages]                           |
| [kick](#kick)                         | Kick a member from the server.                                                                                                                | !kick \<member\> [reason]                                        |
| [lockdown](#lockdown)                 | Lockdown a specific channel (Prevents anyone without special roles from sending messages)                                                     | !lockdown [-t value\|--timeout=value][channel]                   |
| [mute](#mute)                         | Mute a user                                                                                                                                   | !mute [-d value\|--duration=value] \<user\> [reason]             |
| [punishmentConfig](#punishmentConfig) | Configure punishments when reaching a certain amount of strikes.                                                                              | !punishmentConfig [punishment][strikes] [args]                   |
| [purge](#purge)                       | Purge messages in a channel.                                                                                                                  | !purge \<quantity\> [user]                                       |
| [purgeUntil](#purgeUntil)             | Purge messages in a channel up until a specified message.                                                                                     | !purgeUntil \<messageID\>                                        |
| [softBan](#softBan)                   | Ban and then automatically unban a member from the server.                                                                                    | !softBan [-d value\|--deleteMessageDays=value] \<user\> [reason] |
| [strike](#strike)                     | Add strikes to a user                                                                                                                         | !strike \<member\> \<type\> \<amount\>                           |
| [strikeConfig](#strikeConfig)         | Configure strikes received for various violations.                                                                                            | !strikeConfig [violation][strikes]                               |
| [unban](#unban)                       | Unban a user                                                                                                                                  | !unban \<user\> [reason]                                         |
| [unhoist](#unhoist)                   | Add a character in front of all members with a special character in front of their name, so they will be shown at the end of the member list. | !unhoist                                                         |
| [unmute](#unmute)                     | Unmute a user                                                                                                                                 | !unmute \<user\>                                                 |
| [warn](#warn)                         | Warn a member.                                                                                                                                | !warn \<member\> [reason]                                        |

### Other

| Command         | Description                                      | Usage                      |
| --------------- | ------------------------------------------------ | -------------------------- |
| [graph](#graph) | Shows graphs about various stats on this server. | !graph \<type\> [from][to] |

<a name='addInvites'></a>

---

## !addInvites

Adds/Removes invites to/from a member.

### Usage

```text
!addInvites <user> <amount> [reason]
```

### Aliases

- `!add-invites`

### Arguments

| Argument | Type              | Required | Description                                                                                | Details |
| -------- | ----------------- | -------- | ------------------------------------------------------------------------------------------ | ------- |
| user     | [User](#User)     | Yes      | The user that will receive/lose the bonus invites.                                         |         |
| amount   | [Number](#Number) | Yes      | The amount of invites the user will get/lose. Use a negative (-) number to remove invites. |         |
| reason   | [Text](#Text)     | No       | The reason for adding/removing the invites.                                                |         |

### Examples

```text
!addInvites @User 5
```

```text
!addInvites "Name with space" -30 Removed for cheating
```

<a name='addRank'></a>

---

## !addRank

Add a new rank.

### Usage

```text
!addRank <role> <invites> [info]
```

### Aliases

- `!add-rank`
- `!set-rank`
- `!setrank`

### Arguments

| Argument | Type              | Required | Description                                                          | Details |
| -------- | ----------------- | -------- | -------------------------------------------------------------------- | ------- |
| role     | [Role](#Role)     | Yes      | The role which the user will receive when reaching this rank.        |         |
| invites  | [Number](#Number) | Yes      | The amount of invites needed to reach the rank.                      |         |
| info     | [Text](#Text)     | No       | A description that users will see so they know more about this rank. |         |

### Examples

```text
!addRank @Role 5
```

```text
!addRank "Role with space" 10 Wow, already 10 people!
```

<a name='ban'></a>

---

## !ban

Ban a member from the server.

### Usage

```text
!ban [-d value|--deleteMessageDays=value] <user> [reason]
```

### Arguments

| Argument | Type          | Required | Description              | Details |
| -------- | ------------- | -------- | ------------------------ | ------- |
| user     | [User](#User) | Yes      | User to ban.             |         |
| reason   | [Text](#Text) | No       | Why was the user banned. |         |

### Flags

| Flag                              | Short     | Type              | Description                                                                  |
| --------------------------------- | --------- | ----------------- | ---------------------------------------------------------------------------- |
| &#x2011;&#x2011;deleteMessageDays | &#x2011;d | [Number](#Number) | If specified will delete messages by the banned members this many days back. |

### Examples

<a name='botConfig'></a>

---

## !botConfig

Show and change the config of the bot.

### Usage

```text
!botConfig [key] [value]
```

### Aliases

- `!bot-config`
- `!botsetting`
- `!bot-setting`

### Arguments

| Argument | Type            | Required | Description                                           | Details                                                                                                                                     |
| -------- | --------------- | -------- | ----------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| key      | [Enum](#Enum)   | No       | The bot config setting which you want to show/change. | Use one of the following values: `activityEnabled`, `activityMessage`, `activityStatus`, `activityType`, `activityUrl`, `embedDefaultColor` |
| value    | [Value](#Value) | No       | The new value of the setting.                         |                                                                                                                                             |

### Examples

```text
!botConfig
```

<a name='botInfo'></a>

---

## !botInfo

Get general information about the bot.

### Usage

```text
!botInfo
```

### Aliases

- `!bot-info`

### Examples

```text
!botInfo
```

<a name='caseDelete'></a>

---

## !caseDelete

Delete a specific case.

### Usage

```text
!caseDelete <caseNumber> [reason]
```

### Aliases

- `!case-delete`
- `!deletecase`
- `!delete-case`

### Arguments

| Argument   | Type              | Required | Description                       | Details |
| ---------- | ----------------- | -------- | --------------------------------- | ------- |
| caseNumber | [Number](#Number) | Yes      | Case number                       |         |
| reason     | [Text](#Text)     | No       | The reason for removing the case. |         |

### Examples

```text
!caseDelete 5434 User apologized
```

<a name='caseView'></a>

---

## !caseView

View info about a specific case.

### Usage

```text
!caseView <caseNumber>
```

### Aliases

- `!case-view`
- `!viewcase`
- `!view-case`

### Arguments

| Argument   | Type              | Required | Description | Details |
| ---------- | ----------------- | -------- | ----------- | ------- |
| caseNumber | [Number](#Number) | Yes      | Case number |         |

### Examples

```text
!caseView 5434
```

<a name='check'></a>

---

## !check

Check violation and punishment history of a user.

### Usage

```text
!check <user>
```

### Aliases

- `!history`

### Arguments

| Argument | Type          | Required | Description    | Details |
| -------- | ------------- | -------- | -------------- | ------- |
| user     | [User](#User) | Yes      | User to check. |         |

### Examples

```text
!check @User
```

```text
!check "User with space"
```

<a name='clean'></a>

---

## !clean

Clean a channel of certain message types.

### Usage

```text
!clean <type> [numberOfMessages]
```

### Aliases

- `!clear`

### Arguments

| Argument         | Type              | Required | Description                                | Details                                                                                                            |
| ---------------- | ----------------- | -------- | ------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ |
| type             | [Enum](#Enum)     | Yes      | The type of messages that will be deleted. | Use one of the following values: `bots`, `embeds`, `emojis`, `images`, `links`, `mentions`, `reacted`, `reactions` |
| numberOfMessages | [Number](#Number) | No       | Number of messages that will be searched.  |                                                                                                                    |

### Examples

<a name='cleanShort'></a>

---

## !cleanShort

Clear short messages

### Usage

```text
!cleanShort <maxTextLength> [numberOfMessages]
```

### Aliases

- `!clean-short`
- `!clearshort`
- `!clear-short`

### Arguments

| Argument         | Type              | Required | Description                                     | Details |
| ---------------- | ----------------- | -------- | ----------------------------------------------- | ------- |
| maxTextLength    | [Number](#Number) | Yes      | All messages shorter than this will be deleted. |         |
| numberOfMessages | [Number](#Number) | No       | Number of messages that will be searched.       |         |

### Examples

<a name='cleanText'></a>

---

## !cleanText

Delete messages containing certain keywords.

### Usage

```text
!cleanText <text> [numberOfMessages]
```

### Aliases

- `!clean-text`
- `!cleartext`
- `!clear-text`

### Arguments

| Argument         | Type              | Required | Description                                        | Details |
| ---------------- | ----------------- | -------- | -------------------------------------------------- | ------- |
| text             | [Text](#Text)     | Yes      | All messages containing this word will be deleted. |         |
| numberOfMessages | [Number](#Number) | No       | Number of messages that will be searched.          |         |

### Examples

<a name='clearInvites'></a>

---

## !clearInvites

Clear invites of the server/a user.

### Usage

```text
!clearInvites [-d value|--date=value] [-cb|--clearBonus] [user]
```

### Aliases

- `!clear-invites`

### Arguments

| Argument | Type          | Required | Description                                                      | Details |
| -------- | ------------- | -------- | ---------------------------------------------------------------- | ------- |
| user     | [User](#User) | No       | The user to clear all invites from. If omitted clears all users. |         |

### Flags

| Flag                       | Short      | Type                | Description                                                                              |
| -------------------------- | ---------- | ------------------- | ---------------------------------------------------------------------------------------- |
| &#x2011;&#x2011;date       | &#x2011;d  | [Date](#Date)       | The date start at which invites should be counted. Default is today.                     |
| &#x2011;&#x2011;clearBonus | &#x2011;cb | [Boolean](#Boolean) | Add this flag to clear bonus invites aswell. Otherwise bonus invites are left untouched. |

### Examples

```text
!clearInvites
```

```text
!clearInvites @User
```

```text
!clearInvites -cb "User with space"
```

<a name='config'></a>

---

## !config

Show and change the config of the server.

### Usage

```text
!config [key] [value]
```

### Aliases

- `!c`

### Arguments

| Argument | Type            | Required | Description                                       | Details                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| -------- | --------------- | -------- | ------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| key      | [Enum](#Enum)   | No       | The config setting which you want to show/change. | Use one of the following values: `autoModAllCapsEnabled`, `autoModAllCapsMinCharacters`, `autoModAllCapsPercentageCaps`, `autoModDeleteBotMessage`, `autoModDeleteBotMessageTimeoutInSeconds`, `autoModDisabledForOldMembers`, `autoModDisabledForOldMembersThreshold`, `autoModDuplicateTextEnabled`, `autoModDuplicateTextTimeframeInSeconds`, `autoModEmojisEnabled`, `autoModEmojisMaxNumberOfEmojis`, `autoModEnabled`, `autoModHoistEnabled`, `autoModIgnoredChannels`, `autoModIgnoredRoles`, `autoModInvitesEnabled`, `autoModLinksBlacklist`, `autoModLinksEnabled`, `autoModLinksFollowRedirects`, `autoModLinksWhitelist`, `autoModLogEnabled`, `autoModMentionRolesEnabled`, `autoModMentionRolesMaxNumberOfMentions`, `autoModMentionUsersEnabled`, `autoModMentionUsersMaxNumberOfMentions`, `autoModModeratedChannels`, `autoModModeratedRoles`, `autoModQuickMessagesEnabled`, `autoModQuickMessagesNumberOfMessages`, `autoModQuickMessagesTimeframeInSeconds`, `autoModWordsBlacklist`, `autoModWordsEnabled`, `autoSubtractFakes`, `autoSubtractLeaves`, `autoSubtractLeaveThreshold`, `captchaVerificationFailedMessage`, `captchaVerificationLogEnabled`, `captchaVerificationOnJoin`, `captchaVerificationSuccessMessage`, `captchaVerificationTimeout`, `captchaVerificationWelcomeMessage`, `channels`, `getUpdates`, `hideLeftMembersFromLeaderboard`, `ignoredChannels`, `joinMessage`, `joinMessageChannel`, `joinRoles`, `lang`, `leaderboardStyle`, `leaveMessage`, `leaveMessageChannel`, `logChannel`, `modLogChannel`, `modPunishmentBanDeleteMessage`, `modPunishmentKickDeleteMessage`, `modPunishmentMuteDeleteMessage`, `modPunishmentSoftbanDeleteMessage`, `modPunishmentWarnDeleteMessage`, `mutedRole`, `prefix`, `rankAnnouncementChannel`, `rankAnnouncementMessage`, `rankAssignmentStyle` |
| value    | [Value](#Value) | No       | The new value of the setting.                     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |

### Examples

```text
!config
```

<a name='createInvite'></a>

---

## !createInvite

Creates unique invite codes.

### Usage

```text
!createInvite <name> [channel] [maxUses] [expires] [temporaryMembership]
```

### Aliases

- `!create-invite`

### Arguments

| Argument            | Type                | Required | Description                                                                            | Details |
| ------------------- | ------------------- | -------- | -------------------------------------------------------------------------------------- | ------- |
| name                | [Text](#Text)       | Yes      | The name of the invite code.                                                           |         |
| channel             | [Channel](#Channel) | No       | The channel for which the invite code is created. Uses the current channel by default. |         |
| maxUses             | [Number](#Number)   | No       | `number` --> The max amount of uses of the invite code                                 |         |
| expires             | [Boolean](#Boolean) | No       | `true` or `false` --> Set if the invite will expires after 24 hours                    |         |
| temporaryMembership | [Boolean](#Boolean) | No       | `true` or `false` --> Set if the invited users are granted as temporary members        |         |

### Examples

```text
!createInvite reddit
```

```text
!createInvite website #welcome
```

<a name='credits'></a>

---

## !credits

Show developers and contributors of the bot.

### Usage

```text
!credits
```

### Examples

```text
!credits
```

<a name='export'></a>

---

## !export

Export data of InviteLogger to a csv sheet.

### Usage

```text
!export <type>
```

### Arguments

| Argument | Type          | Required | Description                  | Details                                        |
| -------- | ------------- | -------- | ---------------------------- | ---------------------------------------------- |
| type     | [Enum](#Enum) | Yes      | The type of export you want. | Use one of the following values: `leaderboard` |

### Examples

```text
!export leaderboard
```

<a name='fixRanks'></a>

---

## !fixRanks

Deletes any ranks where the role was deleted.

### Usage

```text
!fixRanks
```

### Aliases

- `!fix-ranks`

### Examples

```text
!fixRanks
```

<a name='getBot'></a>

---

## !getBot

Get an invite link for the bot.

### Usage

```text
!getBot
```

### Aliases

- `!get-bot`
- `!invite-bot`
- `!invitebot`

### Examples

```text
!getBot
```

<a name='graph'></a>

---

## !graph

Shows graphs about various stats on this server.

### Usage

```text
!graph <type> [from] [to]
```

### Aliases

- `!g`
- `!chart`

### Arguments

| Argument | Type          | Required | Description                   | Details                                                              |
| -------- | ------------- | -------- | ----------------------------- | -------------------------------------------------------------------- |
| type     | [Enum](#Enum) | Yes      | The type of chart to display. | Use one of the following values: `joins`, `joinsAndLeaves`, `leaves` |
| from     | [Date](#Date) | No       | Start date of the chart       |                                                                      |
| to       | [Date](#Date) | No       | End date of the chart         |                                                                      |

### Examples

```text
!graph joins
```

```text
!graph leaves
```

```text
!graph usage
```

<a name='help'></a>

---

## !help

Display help.

### Usage

```text
!help [command]
```

### Arguments

| Argument | Type                | Required | Description                                  | Details                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| -------- | ------------------- | -------- | -------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| command  | [Command](#Command) | No       | The command to get detailed information for. | Use one of the following values: `addInvites`, `addRank`, `ban`, `botConfig`, `botInfo`, `caseDelete`, `caseView`, `check`, `clean`, `cleanShort`, `cleanText`, `clearInvites`, `config`, `createInvite`, `credits`, `export`, `fixRanks`, `getBot`, `graph`, `help`, `info`, `interactiveConfig`, `inviteCodeConfig`, `inviteCodes`, `inviteDetails`, `invites`, `kick`, `leaderboard`, `lockdown`, `memberConfig`, `members`, `mute`, `permissions`, `ping`, `prefix`, `premium`, `punishmentConfig`, `purge`, `purgeUntil`, `ranks`, `removeInvites`, `removeRank`, `restoreInvites`, `setup`, `softBan`, `strike`, `strikeConfig`, `subtractFakes`, `subtractLeaves`, `support`, `tryPremium`, `unban`, `unhoist`, `unmute`, `warn` |

### Examples

```text
!help
```

```text
!help addRank
```

<a name='info'></a>

---

## !info

Show info about a specific member.

### Usage

```text
!info <user> [details] [page]
```

### Aliases

- `!showinfo`

### Arguments

| Argument | Type              | Required | Description                                                                   | Details                                             |
| -------- | ----------------- | -------- | ----------------------------------------------------------------------------- | --------------------------------------------------- |
| user     | [User](#User)     | Yes      | The user for whom you want to see additional info.                            |                                                     |
| details  | [Enum](#Enum)     | No       | Request only specific details about a member.                                 | Use one of the following values: `bonus`, `members` |
| page     | [Number](#Number) | No       | What page of the details to show. You can also use the reactions to navigate. |                                                     |

### Examples

```text
!info @User
```

```text
!info "User with space"
```

```text
!info @User members
```

```text
!info @User bonus
```

```text
!info @User members 4
```

<a name='interactiveConfig'></a>

---

## !interactiveConfig

Interactive Config

### Usage

```text
!interactiveConfig
```

### Aliases

- `!ic`

### Examples

```text
!interactiveConfig
```

<a name='inviteCodeConfig'></a>

---

## !inviteCodeConfig

Show and change the config of invite codes of the server.

### Usage

```text
!inviteCodeConfig [key] [inviteCode] [value]
```

### Aliases

- `!invite-code-config`
- `!icc`

### Arguments

| Argument   | Type                       | Required | Description                                                | Details                                          |
| ---------- | -------------------------- | -------- | ---------------------------------------------------------- | ------------------------------------------------ |
| key        | [Enum](#Enum)              | No       | The config setting which you want to show/change.          | Use one of the following values: `name`, `roles` |
| inviteCode | [Invite Code](#InviteCode) | No       | The invite code for which you want to change the settings. |                                                  |
| value      | [Value](#Value)            | No       | The new value of the setting.                              |                                                  |

### Examples

```text
!inviteCodeConfig
```

<a name='inviteCodes'></a>

---

## !inviteCodes

Get a list of all your invite codes

### Usage

```text
!inviteCodes
```

### Aliases

- `!invitecode`
- `!invite-code`
- `!invite-codes`
- `!getinvitecode`
- `!get-invite-code`
- `!get-invite-codes`
- `!showinvitecode`
- `!show-invite-code`

### Examples

```text
!inviteCodes
```

<a name='inviteDetails'></a>

---

## !inviteDetails

Shows details about where your invites are from.

### Usage

```text
!inviteDetails [user]
```

### Aliases

- `!invite-details`

### Arguments

| Argument | Type          | Required | Description                                          | Details |
| -------- | ------------- | -------- | ---------------------------------------------------- | ------- |
| user     | [User](#User) | No       | The user for whom you want to show detailed invites. |         |

### Examples

```text
!inviteDetails
```

```text
!inviteDetails @User
```

```text
!inviteDetails "User with space"
```

<a name='invites'></a>

---

## !invites

Show personal invites.

### Usage

```text
!invites [user]
```

### Aliases

- `!invite`
- `!rank`

### Arguments

| Argument | Type          | Required | Description                                 | Details |
| -------- | ------------- | -------- | ------------------------------------------- | ------- |
| user     | [User](#User) | No       | The user for whom you want to show invites. |         |

### Examples

```text
!invites
```

```text
!invites @User
```

```text
!invites "User with space"
```

<a name='kick'></a>

---

## !kick

Kick a member from the server.

### Usage

```text
!kick <member> [reason]
```

### Arguments

| Argument | Type              | Required | Description                | Details |
| -------- | ----------------- | -------- | -------------------------- | ------- |
| member   | [Member](#Member) | Yes      | Member to kick.            |         |
| reason   | [Text](#Text)     | No       | Why the member was kicked. |         |

### Examples

<a name='leaderboard'></a>

---

## !leaderboard

Show members with most invites.

### Usage

```text
!leaderboard [page]
```

### Aliases

- `!top`

### Arguments

| Argument | Type              | Required | Description                           | Details |
| -------- | ----------------- | -------- | ------------------------------------- | ------- |
| page     | [Number](#Number) | No       | Which page of the leaderboard to get. |         |

### Examples

```text
!leaderboard
```

```text
!leaderboard 1mo
```

```text
!leaderboard 30d 6
```

<a name='lockdown'></a>

---

## !lockdown

Lockdown a specific channel (Prevents anyone without special roles from sending messages)

### Usage

```text
!lockdown [-t value|--timeout=value] [channel]
```

### Arguments

| Argument | Type                | Required | Description                             | Details |
| -------- | ------------------- | -------- | --------------------------------------- | ------- |
| channel  | [Channel](#Channel) | No       | The channel that you want to lock down. |         |

### Flags

| Flag                    | Short     | Type                  | Description                                                                                                  |
| ----------------------- | --------- | --------------------- | ------------------------------------------------------------------------------------------------------------ |
| &#x2011;&#x2011;timeout | &#x2011;t | [Duration](#Duration) | The timeout after which the lockdown automatically ends. Run the command again to end the lockdown manually. |

### Examples

```text
!lockdown
```

<a name='memberConfig'></a>

---

## !memberConfig

Show and change the config of members of the server.

### Usage

```text
!memberConfig [key] [user] [value]
```

### Aliases

- `!member-config`
- `!memconf`
- `!mc`

### Arguments

| Argument | Type            | Required | Description                                              | Details                                                |
| -------- | --------------- | -------- | -------------------------------------------------------- | ------------------------------------------------------ |
| key      | [Enum](#Enum)   | No       | The member config setting which you want to show/change. | Use one of the following values: `hideFromLeaderboard` |
| user     | [User](#User)   | No       | The member that the setting is shown/changed for.        |                                                        |
| value    | [Value](#Value) | No       | The new value of the setting.                            |                                                        |

### Examples

```text
!memberConfig
```

<a name='members'></a>

---

## !members

Show member count of current server.

### Usage

```text
!members
```

### Aliases

- `!member`
- `!memberscount`

### Examples

```text
!members
```

<a name='mute'></a>

---

## !mute

Mute a user

### Usage

```text
!mute [-d value|--duration=value] <user> [reason]
```

### Arguments

| Argument | Type              | Required | Description                        | Details |
| -------- | ----------------- | -------- | ---------------------------------- | ------- |
| user     | [Member](#Member) | Yes      | The user that should be muted.     |         |
| reason   | [Text](#Text)     | No       | The reason why this user is muted. |         |

### Flags

| Flag                     | Short     | Type                  | Description                       |
| ------------------------ | --------- | --------------------- | --------------------------------- |
| &#x2011;&#x2011;duration | &#x2011;d | [Duration](#Duration) | The duration to mute the user for |

### Examples

<a name='permissions'></a>

---

## !permissions

Configure permissions to use commands.

### Usage

```text
!permissions [cmd] [role]
```

### Aliases

- `!perms`

### Arguments

| Argument | Type                | Required | Description                                                       | Details                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| -------- | ------------------- | -------- | ----------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| cmd      | [Command](#Command) | No       | The command to configure permissions for.                         | Use one of the following values: `addInvites`, `addRank`, `ban`, `botConfig`, `botInfo`, `caseDelete`, `caseView`, `check`, `clean`, `cleanShort`, `cleanText`, `clearInvites`, `config`, `createInvite`, `credits`, `export`, `fixRanks`, `getBot`, `graph`, `help`, `info`, `interactiveConfig`, `inviteCodeConfig`, `inviteCodes`, `inviteDetails`, `invites`, `kick`, `leaderboard`, `lockdown`, `memberConfig`, `members`, `mute`, `permissions`, `ping`, `prefix`, `premium`, `punishmentConfig`, `purge`, `purgeUntil`, `ranks`, `removeInvites`, `removeRank`, `restoreInvites`, `setup`, `softBan`, `strike`, `strikeConfig`, `subtractFakes`, `subtractLeaves`, `support`, `tryPremium`, `unban`, `unhoist`, `unmute`, `warn` |
| role     | [Role](#Role)       | No       | The role which should be granted or denied access to the command. |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |

### Examples

```text
!permissions
```

<a name='ping'></a>

---

## !ping

Ping the bot

### Usage

```text
!ping
```

### Examples

```text
!ping
```

<a name='prefix'></a>

---

## !prefix

Shows the current prefix of the bot.

### Usage

```text
!prefix
```

### Examples

```text
!prefix
```

<a name='premium'></a>

---

## !premium

Info about premium version of InviteLogger.

### Usage

```text
!premium [action]
```

### Aliases

- `!patreon`
- `!donate`

### Arguments

| Argument | Type          | Required | Description                                                                                                                         | Details                                                            |
| -------- | ------------- | -------- | ----------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| action   | [Enum](#Enum) | No       | The action to perform. None for premium info. `check` to check your premium status. `activate` to use your premium for this server. | Use one of the following values: `Activate`, `Check`, `Deactivate` |

### Examples

```text
!premium
```

```text
!premium check
```

```text
!premium activate
```

```text
!premium deactivate
```

<a name='punishmentConfig'></a>

---

## !punishmentConfig

Configure punishments when reaching a certain amount of strikes.

### Usage

```text
!punishmentConfig [punishment] [strikes] [args]
```

### Aliases

- `!punishment-config`

### Arguments

| Argument   | Type              | Required | Description                                       | Details                                                                   |
| ---------- | ----------------- | -------- | ------------------------------------------------- | ------------------------------------------------------------------------- |
| punishment | [Enum](#Enum)     | No       | Type of punishment to use.                        | Use one of the following values: `ban`, `kick`, `mute`, `softban`, `warn` |
| strikes    | [Number](#Number) | No       | Number of strikes for this punishment to be used. |                                                                           |
| args       | [Text](#Text)     | No       | Arguments passed to the punishment.               |                                                                           |

### Examples

```text
!punishmentConfig
```

<a name='purge'></a>

---

## !purge

Purge messages in a channel.

### Usage

```text
!purge <quantity> [user]
```

### Aliases

- `!prune`

### Arguments

| Argument | Type              | Required | Description                          | Details |
| -------- | ----------------- | -------- | ------------------------------------ | ------- |
| quantity | [Number](#Number) | Yes      | How many messages should be deleted. |         |
| user     | [User](#User)     | No       | User whose messages are deleted.     |         |

### Examples

<a name='purgeUntil'></a>

---

## !purgeUntil

Purge messages in a channel up until a specified message.

### Usage

```text
!purgeUntil <messageID>
```

### Aliases

- `!purge-until`
- `!prune-until`
- `!pruneu`
- `!purgeu`

### Arguments

| Argument  | Type          | Required | Description                    | Details |
| --------- | ------------- | -------- | ------------------------------ | ------- |
| messageID | [Text](#Text) | Yes      | Last message ID to be deleted. |         |

### Examples

<a name='ranks'></a>

---

## !ranks

Show all ranks.

### Usage

```text
!ranks [page]
```

### Aliases

- `!show-ranks`
- `!showranks`

### Arguments

| Argument | Type              | Required | Description                         | Details |
| -------- | ----------------- | -------- | ----------------------------------- | ------- |
| page     | [Number](#Number) | No       | The page of the ranks list to show. |         |

### Examples

```text
!ranks
```

<a name='removeInvites'></a>

---

## !removeInvites

Removes a specified amount of invites from a user.

### Usage

```text
!removeInvites <user> <amount> [reason]
```

### Aliases

- `!remove-invites`

### Arguments

| Argument | Type              | Required | Description                          | Details |
| -------- | ----------------- | -------- | ------------------------------------ | ------- |
| user     | [User](#User)     | Yes      | The user to remove the invites from. |         |
| amount   | [Number](#Number) | Yes      | The amount of invites to remove.     |         |
| reason   | [Text](#Text)     | No       | The reason for removing the invites. |         |

### Examples

```text
!removeInvites @User 5
```

```text
!removeInvites "User with space" 23 Removed for cheating
```

```text
!removeInvites @User -6 Added for apologizing
```

<a name='removeRank'></a>

---

## !removeRank

Remove a rank.

### Usage

```text
!removeRank <rank>
```

### Aliases

- `!remove-rank`

### Arguments

| Argument | Type          | Required | Description                                | Details |
| -------- | ------------- | -------- | ------------------------------------------ | ------- |
| rank     | [Role](#Role) | Yes      | The for which you want to remove the rank. |         |

### Examples

```text
!removeRank @Role
```

```text
!removeRank "Role with space"
```

<a name='restoreInvites'></a>

---

## !restoreInvites

Restore all previously cleared invites.

### Usage

```text
!restoreInvites [user]
```

### Aliases

- `!restore-invites`
- `!unclear-invites`
- `!unclearinvites`

### Arguments

| Argument | Type          | Required | Description                                                                    | Details |
| -------- | ------------- | -------- | ------------------------------------------------------------------------------ | ------- |
| user     | [User](#User) | No       | The user to restore all invites to. If omitted restores invites for all users. |         |

### Examples

```text
!restoreInvites
```

```text
!restoreInvites @User
```

```text
!restoreInvites "User with space"
```

<a name='setup'></a>

---

## !setup

Help with setting up the bot and checking for problems (e.g. missing permissions)

### Usage

```text
!setup
```

### Aliases

- `!guide`
- `!test`
- `!testbot`
- `!test-bot`

### Examples

```text
!setup
```

<a name='softBan'></a>

---

## !softBan

Ban and then automatically unban a member from the server.

### Usage

```text
!softBan [-d value|--deleteMessageDays=value] <user> [reason]
```

### Aliases

- `!soft-ban`

### Arguments

| Argument | Type              | Required | Description              | Details |
| -------- | ----------------- | -------- | ------------------------ | ------- |
| user     | [Member](#Member) | Yes      | User to ban.             |         |
| reason   | [Text](#Text)     | No       | Why was the user banned. |         |

### Flags

| Flag                              | Short     | Type              | Description                                        |
| --------------------------------- | --------- | ----------------- | -------------------------------------------------- |
| &#x2011;&#x2011;deleteMessageDays | &#x2011;d | [Number](#Number) | Delete messages from the user this many days back. |

### Examples

<a name='strike'></a>

---

## !strike

Add strikes to a user

### Usage

```text
!strike <member> <type> <amount>
```

### Arguments

| Argument | Type              | Required | Description                       | Details                                                                                                                                                      |
| -------- | ----------------- | -------- | --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| member   | [Member](#Member) | Yes      | The member receiving the strikes  |                                                                                                                                                              |
| type     | [Enum](#Enum)     | Yes      | The type of the violation         | Use one of the following values: `allCaps`, `duplicateText`, `emojis`, `hoist`, `invites`, `links`, `mentionRoles`, `mentionUsers`, `quickMessages`, `words` |
| amount   | [Number](#Number) | Yes      | The amount of strikes to be added |                                                                                                                                                              |

### Examples

<a name='strikeConfig'></a>

---

## !strikeConfig

Configure strikes received for various violations.

### Usage

```text
!strikeConfig [violation] [strikes]
```

### Aliases

- `!strike-config`

### Arguments

| Argument  | Type              | Required | Description        | Details                                                                                                                                                      |
| --------- | ----------------- | -------- | ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| violation | [Enum](#Enum)     | No       | Violation type.    | Use one of the following values: `allCaps`, `duplicateText`, `emojis`, `hoist`, `invites`, `links`, `mentionRoles`, `mentionUsers`, `quickMessages`, `words` |
| strikes   | [Number](#Number) | No       | Number of strikes. |                                                                                                                                                              |

### Examples

```text
!strikeConfig
```

<a name='subtractFakes'></a>

---

## !subtractFakes

Remove fake invites from all users.

### Usage

```text
!subtractFakes
```

### Aliases

- `!subtract-fakes`
- `!subfakes`
- `!sf`

### Examples

```text
!subtractFakes
```

<a name='subtractLeaves'></a>

---

## !subtractLeaves

Remove leaves from all users

### Usage

```text
!subtractLeaves
```

### Aliases

- `!subtract-leaves`
- `!subleaves`
- `!sl`

### Examples

```text
!subtractLeaves
```

<a name='support'></a>

---

## !support

Get an invite link to our support server.

### Usage

```text
!support
```

### Examples

```text
!support
```

<a name='tryPremium'></a>

---

## !tryPremium

Try the premium version of InviteLogger for free for a limited duration.

### Usage

```text
!tryPremium
```

### Aliases

- `!try`
- `!try-premium`

### Examples

```text
!tryPremium
```

<a name='unban'></a>

---

## !unban

Unban a user

### Usage

```text
!unban <user> [reason]
```

### Arguments

| Argument | Type          | Required | Description                           | Details |
| -------- | ------------- | -------- | ------------------------------------- | ------- |
| user     | [User](#User) | Yes      | The user that should be unbanned.     |         |
| reason   | [Text](#Text) | No       | The reason why this user is unbanned. |         |

### Examples

<a name='unhoist'></a>

---

## !unhoist

Add a character in front of all members with a special character in front of their name, so they will be shown at the end of the member list.

### Usage

```text
!unhoist
```

### Aliases

- `!dehoist`

### Examples

```text
!unhoist
```

<a name='unmute'></a>

---

## !unmute

Unmute a user

### Usage

```text
!unmute <user>
```

### Arguments

| Argument | Type              | Required | Description                      | Details |
| -------- | ----------------- | -------- | -------------------------------- | ------- |
| user     | [Member](#Member) | Yes      | The user that should be unmuted. |         |

### Examples

<a name='warn'></a>

---

## !warn

Warn a member.

### Usage

```text
!warn <member> [reason]
```

### Arguments

| Argument | Type              | Required | Description                    | Details |
| -------- | ----------------- | -------- | ------------------------------ | ------- |
| member   | [Member](#Member) | Yes      | Member to warn.                |         |
| reason   | [Text](#Text)     | No       | Why was the member was warned. |         |

### Examples
