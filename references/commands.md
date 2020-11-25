# Commands

## Commands

### Arguments & Flags

Most commands accept arguments and/or flags.  
According to the **Type** of the argument or flag you can provide different values.

#### Boolean

This arguments expects `true` or `false`. You can also use `yes` and `no`.

#### Number

This arguments expects a number

#### Enum

This arguments expects a value from a specific set of valid values.

> Depending on the command the valid values can vary. Use `!help <command>` \(eg. `!help addRank`\) to get more information about the command and the valid values for the enum.

#### Invite Code

This arguments expects a Discord Invite Code.

> You can put only the part after `https://discord.gg/` to prevent Discord from creating a preview.

#### User

This arguments expects a Discord User. You can use any of the following methods to provide a user:

* Mention the user: `@Valandur`
* Use their ID: `102785693046026240`
* Use their name: `Valandur`
* Use their name and discriminator: `Valandur#3581`
* Use quotes if their name has a space: `"Valandur with a space"`

#### Role

This arguments expects a Discord Role. You can use any of the following methods to provide a role:

* Mention the role: `@Admin`
* Use the ID: `102785693046026240`
* Use the name: `Admin`
* Use quotes if the name has a space: `"Admin with a space"`

#### Channel

This arguments expects a Discord Channel. You can use any of the following methods to provide a channel:

* Mention the channel: `#general`
* Use the ID: `409846838129197057`
* Use the name: `general`
* Use quotes if the name has a space: `"general with a space"`

#### Command

This argument expects a command of this bot. You can use any of the following methods to provide a command:

* Use the command name: `invites`
* Use an alias of the command: `p`

#### Text

This arguments expects any text. You can use quotes \(`"Text with quotes"`\) for text that has spaces.

> If the text is the last argument you don't have to use quotes.

#### Date

This argument expects a date. You can use various formats, but we recommend: `YYYY-MM-DD`

#### Duration

This argument expects a duration. The following duration types are supported:

* Seconds: `s` \(`5s` = 5 seconds\)
* Minutes: `min` \(`3min` = 3 minutes\)
* Hours: `h` \(`4h` = 4 hours\)
* Days: `d` \(`2d` = 2 days\)
* Weeks: `w` \(`1w` = 1 week\)
* Months: `mo` \(`6mo` = 6 months\)
* Years: `y` \(`10y` = 10 years\)

### Overview

#### Invites

| Command | Description | Usage |
| :--- | :--- | :--- |
| addInvites | Entfernt/Fügt Einladungen von/zu einem Mitglied hinzu. | !addInvites \ \ \[reason\] |
| clearInvites | Entferne Einladungen des servers/eines Benutzers. | !clearInvites \[-d value\|--date=value\]\[-cb\|--clearbonus\] \[user\] |
| createInvite | Erstellt einen einzigartigen Einladungs Code. | !createInvite \ \[channel\]\[maxuses\] \[expires\]\[temporarymembership\] |
| info | Zeigt Informationen über einen bestimmten Benutzer. | !info \ \[details\]\[page\] |
| inviteCodes | Erhalte eine Lliste aller Invite codes. | !inviteCodes |
| inviteDetails | Shows details about where your invites are from. | !inviteDetails \[user\] |
| invites | Zeigt persönliche Einladungen. | !invites \[user\] |
| leaderboard | Zeigt Benutzer mit meissten Einladungen. | !leaderboard \[page\] |
| removeInvites | Removes a specified amount of invites from a user. | !removeInvites \ \ \[reason\] |
| restoreInvites | Erhalte alle vorher entfernten Einladungen zurück. | !restoreInvites \[user\] |
| subtractFakes | Entferne Fake Einladungen von allen Benutzern. | !subtractFakes |
| subtractLeaves | Entferne Leaves von allen Benutzern. | !subtractLeaves |

#### Ranks

| Command | Description | Usage |
| :--- | :--- | :--- |
| addRank | Füge einen neuen Rang hinzu. | !addRank \ \ \[info\] |
| fixRanks | Deletes any ranks where the role was deleted. | !fixRanks |
| ranks | Zeigt alle Ränge. | !ranks \[page\] |
| removeRank | Entferne einen Rang. | !removeRank \ |

#### Config

| Command | Description | Usage |
| :--- | :--- | :--- |
| botConfig | Show and change the config of the bot. | !botConfig \[key\]\[value\] |
| config | Zeigt und ändert die einstellungen des Servers. | !config \[key\]\[value\] |
| interactiveConfig | Interactive Config | !interactiveConfig |
| inviteCodeConfig | Show and change the config of invite codes of the server. | !inviteCodeConfig \[key\]\[invitecode\] \[value\] |
| memberConfig | Zeigt und ändert die einstellungen von Benutzern des servers. | !memberConfig \[key\]\[user\] \[value\] |
| permissions | Configure permissions to use commands. | !permissions \[cmd\]\[role\] |

#### Info

| Command | Description | Usage |
| :--- | :--- | :--- |
| botInfo | Erhalte die wichtigsten Informationen des Bots | !botInfo |
| credits | Show developers and contributors of the bot. | !credits |
| getBot | Get an invite link for the bot. | !getBot |
| help | Zeigt hilfe. | !help \[command\] |
| members | Zeigt Mitgliederanzahl des servers. | !members |
| ping | Ping the bot | !ping |
| prefix | Shows the current prefix of the bot. | !prefix |
| setup | Hilft den Bot einzustellen und sucht nach Problemen \(z.B. fehlende Rechte\) | !setup |
| support | Get an invite link to our support server. | !support |

#### Premium

| Command | Description | Usage |
| :--- | :--- | :--- |
| export | Export data of InviteManager to a csv sheet. | !export \ |
| premium | Info about premium version of InviteManager. | !premium \[action\] |
| tryPremium | Try the premium version of InviteManager for free for a limited duration. | !tryPremium |

#### Moderation

| Command | Description | Usage |
| :--- | :--- | :--- |
| ban | Bannt ein Mitglied vom Server. | !ban \[-d value\|--deleteMessageDays=value\] \ \[reason\] |
| caseDelete | Delete a specific case. | !caseDelete \ \[reason\] |
| caseView | View info about a specific case. | !caseView \ |
| check | Zeige Verletzungen der Regeln und Bestrafungen des Benutzers. | !check \ |
| clean | Entferne bestimmte nachrichten in einem Kanal. | !clean \ \[numberOfMessages\] |
| cleanShort | Clear short messages | !cleanShort \ \[numberOfMessages\] |
| cleanText | Delete messages containing certain keywords. | !cleanText \ \[numberOfMessages\] |
| kick | Kickt ein Benutzer vom Server. | !kick \ \[reason\] |
| lockdown | Lockdown a specific channel \(Prevents anyone without special roles from sending messages\) | !lockdown \[-t value\|--timeout=value\]\[channel\] |
| mute | Mute a user | !mute \[-d value\|--duration=value\] \ \[reason\] |
| punishmentConfig | Stelle eine Bestrafung ein wenn eine bestimmte anzahl am Regelverletzungen erreicht wird. | !punishmentConfig \[punishment\]\[strikes\] \[args\] |
| purge | Entferne Nachrichten in einem Kanal. | !purge \ \[user\] |
| purgeUntil | Entferne nachrichten bis zu einer bestimmten nachricht. | !purgeUntil \ |
| softBan | Banne ein Mitlgied und es wird dann automatisch entbannt. | !softBan \[-d value\|--deleteMessageDays=value\] \ \[reason\] |
| strike | Add strikes to a user | !strike \ \ \ |
| strikeConfig | Bearbeite strikes die für unterschiedliche Regelbrüche verteilt werden. | !strikeConfig \[violation\]\[strikes\] |
| unban | Unban a user | !unban \ \[reason\] |
| unhoist | Add a character in front of all members with a special character in front of their name, so they will be shown at the end of the member list. | !unhoist |
| unmute | Unmute a user | !unmute \ |
| warn | Warn a member. | !warn \ \[reason\] |

#### Other

| Command | Description | Usage |
| :--- | :--- | :--- |
| graph | Shows graphs about various stats on this server. | !graph \ \[from\]\[to\] |

### !addInvites

Entfernt/Fügt Einladungen von/zu einem Mitglied hinzu.

#### Usage

```text
!addInvites <user> <amount> [reason]
```

#### Aliases

* `!add-invites`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | User | Yes | Der Benutzer welcher die zusätzlichen Invites erhalten/verlieren wird. |  |
| amount | Number | Yes | Die Anzahl der Einladungen welche der Benutzer erhalten/verlieren wird. Benutze eine negative \(-\) Zahl um Einladungen zu entfernen. |  |
| reason | Text | No | Grund für das hinzufügen/entfernen der Einladungen. |  |

#### Examples

```text
!addInvites @User 5
```

```text
!addInvites "Name with space" -30 Removed for cheating
```

### !addRank

Füge einen neuen Rang hinzu.

#### Usage

```text
!addRank <role> <invites> [info]
```

#### Aliases

* `!add-rank`
* `!set-rank`
* `!setrank`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| role | Role | Yes | Die Rolle welche Benutzer erhalten wenn sie diesen Rang erreichen. |  |
| invites | Number | Yes | Die Anzahl der Einladungen um den Rang zu erreichen. |  |
| info | Text | No | Eine Beschreibung die Nutzer sehen damit sie mehr über den Rang wissen. |  |

#### Examples

```text
!addRank @Role 5
```

```text
!addRank "Role with space" 10 Wow, already 10 people!
```

### !ban

Bannt ein Mitglied vom Server.

#### Usage

```text
!ban [-d value|--deleteMessageDays=value] <user> [reason]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | User | Yes | Nutzer zum verbannen. |  |
| reason | Text | No | Warum der Nutzer gebannt wurde. |  |

#### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑deleteMessageDays | ‑d | Number | If specified will delete messages by the banned members this many days back. |

#### Examples

### !botConfig

Show and change the config of the bot.

#### Usage

```text
!botConfig [key] [value]
```

#### Aliases

* `!bot-config`
* `!botsetting`
* `!bot-setting`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| key | Enum | No | The bot config setting which you want to show/change. | Use one of the following values: `activityEnabled`, `activityMessage`, `activityStatus`, `activityType`, `activityUrl`, `embedDefaultColor` |
| value | Value | No | The new value of the setting. |  |

#### Examples

```text
!botConfig
```

### !botInfo

Erhalte die wichtigsten Informationen des Bots

#### Usage

```text
!botInfo
```

#### Aliases

* `!bot-info`

#### Examples

```text
!botInfo
```

### !caseDelete

Delete a specific case.

#### Usage

```text
!caseDelete <caseNumber> [reason]
```

#### Aliases

* `!case-delete`
* `!deletecase`
* `!delete-case`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| caseNumber | Number | Yes | Case number |  |
| reason | Text | No | The reason for removing the case. |  |

#### Examples

```text
!caseDelete 5434 User apologized
```

### !caseView

View info about a specific case.

#### Usage

```text
!caseView <caseNumber>
```

#### Aliases

* `!case-view`
* `!viewcase`
* `!view-case`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| caseNumber | Number | Yes | Case number |  |

#### Examples

```text
!caseView 5434
```

### !check

Zeige Verletzungen der Regeln und Bestrafungen des Benutzers.

#### Usage

```text
!check <user>
```

#### Aliases

* `!history`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | User | Yes | Benutzer zum Überpfrüfen. |  |

#### Examples

```text
!check @User
```

```text
!check "User with space"
```

### !clean

Entferne bestimmte nachrichten in einem Kanal.

#### Usage

```text
!clean <type> [numberOfMessages]
```

#### Aliases

* `!clear`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| type | Enum | Yes | The type of messages that will be deleted. | Use one of the following values: `bots`, `embeds`, `emojis`, `images`, `links`, `mentions`, `reacted`, `reactions` |
| numberOfMessages | Number | No | Number of messages that will be searched. |  |

#### Examples

### !cleanShort

Clear short messages

#### Usage

```text
!cleanShort <maxTextLength> [numberOfMessages]
```

#### Aliases

* `!clean-short`
* `!clearshort`
* `!clear-short`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| maxTextLength | Number | Yes | All messages shorter than this will be deleted. |  |
| numberOfMessages | Number | No | Number of messages that will be searched. |  |

#### Examples

### !cleanText

Delete messages containing certain keywords.

#### Usage

```text
!cleanText <text> [numberOfMessages]
```

#### Aliases

* `!clean-text`
* `!cleartext`
* `!clear-text`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| text | Text | Yes | All messages containing this word will be deleted. |  |
| numberOfMessages | Number | No | Number of messages that will be searched. |  |

#### Examples

### !clearInvites

Entferne Einladungen des servers/eines Benutzers.

#### Usage

```text
!clearInvites [-d value|--date=value] [-cb|--clearBonus] [user]
```

#### Aliases

* `!clear-invites`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | User | No | Der Benutzer wessen Einladungen entfernt werden.Wenn nicht angeben werden einladungen aller Benutzer entfernt. |  |

#### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑date | ‑d | Date | The date start at which invites should be counted. Default is today. |
| ‑‑clearBonus | ‑cb | Boolean | Add this flag to clear bonus invites aswell. Otherwise bonus invites are left untouched. |

#### Examples

```text
!clearInvites
```

```text
!clearInvites @User
```

```text
!clearInvites -cb "User with space"
```

### !config

Zeigt und ändert die einstellungen des Servers.

#### Usage

```text
!config [key] [value]
```

#### Aliases

* `!c`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| key | Enum | No | Die Configurations Einstellung welche du anzeichen/ändern willst. | Use one of the following values: `autoModAllCapsEnabled`, `autoModAllCapsMinCharacters`, `autoModAllCapsPercentageCaps`, `autoModDeleteBotMessage`, `autoModDeleteBotMessageTimeoutInSeconds`, `autoModDisabledForOldMembers`, `autoModDisabledForOldMembersThreshold`, `autoModDuplicateTextEnabled`, `autoModDuplicateTextTimeframeInSeconds`, `autoModEmojisEnabled`, `autoModEmojisMaxNumberOfEmojis`, `autoModEnabled`, `autoModHoistEnabled`, `autoModIgnoredChannels`, `autoModIgnoredRoles`, `autoModInvitesEnabled`, `autoModLinksBlacklist`, `autoModLinksEnabled`, `autoModLinksFollowRedirects`, `autoModLinksWhitelist`, `autoModLogEnabled`, `autoModMentionRolesEnabled`, `autoModMentionRolesMaxNumberOfMentions`, `autoModMentionUsersEnabled`, `autoModMentionUsersMaxNumberOfMentions`, `autoModModeratedChannels`, `autoModModeratedRoles`, `autoModQuickMessagesEnabled`, `autoModQuickMessagesNumberOfMessages`, `autoModQuickMessagesTimeframeInSeconds`, `autoModWordsBlacklist`, `autoModWordsEnabled`, `autoSubtractFakes`, `autoSubtractLeaves`, `autoSubtractLeaveThreshold`, `captchaVerificationFailedMessage`, `captchaVerificationLogEnabled`, `captchaVerificationOnJoin`, `captchaVerificationSuccessMessage`, `captchaVerificationTimeout`, `captchaVerificationWelcomeMessage`, `channels`, `getUpdates`, `hideLeftMembersFromLeaderboard`, `ignoredChannels`, `joinMessage`, `joinMessageChannel`, `joinRoles`, `lang`, `leaderboardStyle`, `leaveMessage`, `leaveMessageChannel`, `logChannel`, `modLogChannel`, `modPunishmentBanDeleteMessage`, `modPunishmentKickDeleteMessage`, `modPunishmentMuteDeleteMessage`, `modPunishmentSoftbanDeleteMessage`, `modPunishmentWarnDeleteMessage`, `mutedRole`, `prefix`, `rankAnnouncementChannel`, `rankAnnouncementMessage`, `rankAssignmentStyle` |
| value | Value | No | Der neue wert der Einstellung. |  |

#### Examples

```text
!config
```

### !createInvite

Erstellt einen einzigartigen Einladungs Code.

#### Usage

```text
!createInvite <name> [channel] [maxUses] [expires] [temporaryMembership]
```

#### Aliases

* `!create-invite`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| name | Text | Yes | Der Name des Invite codes. |  |
| channel | Channel | No | The channel for which the invite code is created. Uses the current channel by default. |  |
| maxUses | Number | No | `number` --&gt; The max amount of uses of the invite code |  |
| expires | Boolean | No | `true` or `false` --&gt; Set if the invite will expires after 24 hours |  |
| temporaryMembership | Boolean | No | `true` or `false` --&gt; Set if the invited users are granted as temporary members |  |

#### Examples

```text
!createInvite reddit
```

```text
!createInvite website #welcome
```

### !credits

Show developers and contributors of the bot.

#### Usage

```text
!credits
```

#### Examples

```text
!credits
```

### !export

Export data of InviteManager to a csv sheet.

#### Usage

```text
!export <type>
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| type | Enum | Yes | The type of export you want. | Use one of the following values: `leaderboard` |

#### Examples

```text
!export leaderboard
```

### !fixRanks

Deletes any ranks where the role was deleted.

#### Usage

```text
!fixRanks
```

#### Aliases

* `!fix-ranks`

#### Examples

```text
!fixRanks
```

### !getBot

Get an invite link for the bot.

#### Usage

```text
!getBot
```

#### Aliases

* `!get-bot`
* `!invite-bot`
* `!invitebot`

#### Examples

```text
!getBot
```

### !graph

Shows graphs about various stats on this server.

#### Usage

```text
!graph <type> [from] [to]
```

#### Aliases

* `!g`
* `!chart`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| type | Enum | Yes | The type of chart to display. | Use one of the following values: `joins`, `joinsAndLeaves`, `leaves` |
| from | Date | No | Start date of the chart |  |
| to | Date | No | End date of the chart |  |

#### Examples

```text
!graph joins
```

```text
!graph leaves
```

```text
!graph usage
```

### !help

Zeigt hilfe.

#### Usage

```text
!help [command]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| command | Command | No | Der command um deatilierte Informationen zu erhalten. | Use one of the following values: `addInvites`, `addRank`, `ban`, `botConfig`, `botInfo`, `caseDelete`, `caseView`, `check`, `clean`, `cleanShort`, `cleanText`, `clearInvites`, `config`, `createInvite`, `credits`, `export`, `fixRanks`, `getBot`, `graph`, `help`, `info`, `interactiveConfig`, `inviteCodeConfig`, `inviteCodes`, `inviteDetails`, `invites`, `kick`, `leaderboard`, `lockdown`, `memberConfig`, `members`, `mute`, `permissions`, `ping`, `prefix`, `premium`, `punishmentConfig`, `purge`, `purgeUntil`, `ranks`, `removeInvites`, `removeRank`, `restoreInvites`, `setup`, `softBan`, `strike`, `strikeConfig`, `subtractFakes`, `subtractLeaves`, `support`, `tryPremium`, `unban`, `unhoist`, `unmute`, `warn` |

#### Examples

```text
!help
```

```text
!help addRank
```

### !info

Zeigt Informationen über einen bestimmten Benutzer.

#### Usage

```text
!info <user> [details] [page]
```

#### Aliases

* `!showinfo`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | User | Yes | Der Benutzer wessen information du sehen willst. |  |
| details | Enum | No | Request only specific details about a member. | Use one of the following values: `bonus`, `members` |
| page | Number | No | What page of the details to show. You can also use the reactions to navigate. |  |

#### Examples

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

### !interactiveConfig

Interactive Config

#### Usage

```text
!interactiveConfig
```

#### Aliases

* `!ic`

#### Examples

```text
!interactiveConfig
```

### !inviteCodeConfig

Show and change the config of invite codes of the server.

#### Usage

```text
!inviteCodeConfig [key] [inviteCode] [value]
```

#### Aliases

* `!invite-code-config`
* `!icc`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| key | Enum | No | The config setting which you want to show/change. | Use one of the following values: `name`, `roles` |
| inviteCode | Invite Code | No | The invite code for which you want to change the settings. |  |
| value | Value | No | The new value of the setting. |  |

#### Examples

```text
!inviteCodeConfig
```

### !inviteCodes

Erhalte eine Lliste aller Invite codes.

#### Usage

```text
!inviteCodes
```

#### Aliases

* `!invitecode`
* `!invite-code`
* `!invite-codes`
* `!getinvitecode`
* `!get-invite-code`
* `!get-invite-codes`
* `!showinvitecode`
* `!show-invite-code`

#### Examples

```text
!inviteCodes
```

### !inviteDetails

Shows details about where your invites are from.

#### Usage

```text
!inviteDetails [user]
```

#### Aliases

* `!invite-details`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | User | No | Der Benutzer ,von dem sie Deatailierte Einladungen sehen wollen. |  |

#### Examples

```text
!inviteDetails
```

```text
!inviteDetails @User
```

```text
!inviteDetails "User with space"
```

### !invites

Zeigt persönliche Einladungen.

#### Usage

```text
!invites [user]
```

#### Aliases

* `!invite`
* `!rank`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | User | No | Der Benutzer,wessen Einladungen sie anzeigen möchten. |  |

#### Examples

```text
!invites
```

```text
!invites @User
```

```text
!invites "User with space"
```

### !kick

Kickt ein Benutzer vom Server.

#### Usage

```text
!kick <member> [reason]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| member | Member | Yes | Benutzer zum kicken. |  |
| reason | Text | No | Warum der Benutzer gekickt wurde. |  |

#### Examples

### !leaderboard

Zeigt Benutzer mit meissten Einladungen.

#### Usage

```text
!leaderboard [page]
```

#### Aliases

* `!top`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| page | Number | No | Welche seite des Leaderboards aufgerufen werden soll. |  |

#### Examples

```text
!leaderboard
```

```text
!leaderboard 1mo
```

```text
!leaderboard 30d 6
```

### !lockdown

Lockdown a specific channel \(Prevents anyone without special roles from sending messages\)

#### Usage

```text
!lockdown [-t value|--timeout=value] [channel]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| channel | Channel | No | The channel that you want to lock down. |  |

#### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑timeout | ‑t | Duration | The timeout after which the lockdown automatically ends. Run the command again to end the lockdown manually. |

#### Examples

```text
!lockdown
```

### !memberConfig

Zeigt und ändert die einstellungen von Benutzern des servers.

#### Usage

```text
!memberConfig [key] [user] [value]
```

#### Aliases

* `!member-config`
* `!memconf`
* `!mc`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| key | Enum | No | The member config setting which you want to show/change. | Use one of the following values: `hideFromLeaderboard` |
| user | User | No | Der bentzer für den die Einstellung angezeigt/geändert wird. |  |
| value | Value | No | Der neue Wert der Einstellung. |  |

#### Examples

```text
!memberConfig
```

### !members

Zeigt Mitgliederanzahl des servers.

#### Usage

```text
!members
```

#### Aliases

* `!member`
* `!memberscount`

#### Examples

```text
!members
```

### !mute

Mute a user

#### Usage

```text
!mute [-d value|--duration=value] <user> [reason]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | Member | Yes | The user that should be muted. |  |
| reason | Text | No | The reason why this user is muted. |  |

#### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑duration | ‑d | Duration | The duration to mute the user for |

#### Examples

### !permissions

Configure permissions to use commands.

#### Usage

```text
!permissions [cmd] [role]
```

#### Aliases

* `!perms`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| cmd | Command | No | The command to configure permissions for. | Use one of the following values: `addInvites`, `addRank`, `ban`, `botConfig`, `botInfo`, `caseDelete`, `caseView`, `check`, `clean`, `cleanShort`, `cleanText`, `clearInvites`, `config`, `createInvite`, `credits`, `export`, `fixRanks`, `getBot`, `graph`, `help`, `info`, `interactiveConfig`, `inviteCodeConfig`, `inviteCodes`, `inviteDetails`, `invites`, `kick`, `leaderboard`, `lockdown`, `memberConfig`, `members`, `mute`, `permissions`, `ping`, `prefix`, `premium`, `punishmentConfig`, `purge`, `purgeUntil`, `ranks`, `removeInvites`, `removeRank`, `restoreInvites`, `setup`, `softBan`, `strike`, `strikeConfig`, `subtractFakes`, `subtractLeaves`, `support`, `tryPremium`, `unban`, `unhoist`, `unmute`, `warn` |
| role | Role | No | The role which should be granted or denied access to the command. |  |

#### Examples

```text
!permissions
```

### !ping

Ping the bot

#### Usage

```text
!ping
```

#### Examples

```text
!ping
```

### !prefix

Shows the current prefix of the bot.

#### Usage

```text
!prefix
```

#### Examples

```text
!prefix
```

### !premium

Info about premium version of InviteManager.

#### Usage

```text
!premium [action]
```

#### Aliases

* `!patreon`
* `!donate`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| action | Enum | No | The action to perform. None for premium info. `check` to check your premium status. `activate` to use your premium for this server. | Use one of the following values: `Activate`, `Check`, `Deactivate` |

#### Examples

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

### !punishmentConfig

Stelle eine Bestrafung ein wenn eine bestimmte anzahl am Regelverletzungen erreicht wird.

#### Usage

```text
!punishmentConfig [punishment] [strikes] [args]
```

#### Aliases

* `!punishment-config`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| punishment | Enum | No | Typ der Bestrafung welche benutzt wird. | Use one of the following values: `ban`, `kick`, `mute`, `softban`, `warn` |
| strikes | Number | No | Anzahl der Regel verletzungen um diese Strafe auszulösen. |  |
| args | Text | No | Argument der Bestrafung. |  |

#### Examples

```text
!punishmentConfig
```

### !purge

Entferne Nachrichten in einem Kanal.

#### Usage

```text
!purge <quantity> [user]
```

#### Aliases

* `!prune`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| quantity | Number | Yes | Wieviele Nachrichten sollen entfernt werden. |  |
| user | User | No | User whose messages are deleted. |  |

#### Examples

### !purgeUntil

Entferne nachrichten bis zu einer bestimmten nachricht.

#### Usage

```text
!purgeUntil <messageID>
```

#### Aliases

* `!purge-until`
* `!prune-until`
* `!pruneu`
* `!purgeu`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| messageID | Text | Yes | Letzte Nachrichten ID die entfernt werden soll. |  |

#### Examples

### !ranks

Zeigt alle Ränge.

#### Usage

```text
!ranks [page]
```

#### Aliases

* `!show-ranks`
* `!showranks`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| page | Number | No | The page of the ranks list to show. |  |

#### Examples

```text
!ranks
```

### !removeInvites

Removes a specified amount of invites from a user.

#### Usage

```text
!removeInvites <user> <amount> [reason]
```

#### Aliases

* `!remove-invites`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | User | Yes | The user to remove the invites from. |  |
| amount | Number | Yes | The amount of invites to remove. |  |
| reason | Text | No | The reason for removing the invites. |  |

#### Examples

```text
!removeInvites @User 5
```

```text
!removeInvites "User with space" 23 Removed for cheating
```

```text
!removeInvites @User -6 Added for apologizing
```

### !removeRank

Entferne einen Rang.

#### Usage

```text
!removeRank <rank>
```

#### Aliases

* `!remove-rank`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| rank | Role | Yes | Der Benutzer für den der Rang entfernt werden soll. |  |

#### Examples

```text
!removeRank @Role
```

```text
!removeRank "Role with space"
```

### !restoreInvites

Erhalte alle vorher entfernten Einladungen zurück.

#### Usage

```text
!restoreInvites [user]
```

#### Aliases

* `!restore-invites`
* `!unclear-invites`
* `!unclearinvites`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | User | No | Der Benutzer wessen Einladungen zurückgegeben werden.Wenn kein Benutzer angegeben wird werden alle Einladungen zurückgegeben. |  |

#### Examples

```text
!restoreInvites
```

```text
!restoreInvites @User
```

```text
!restoreInvites "User with space"
```

### !setup

Hilft den Bot einzustellen und sucht nach Problemen \(z.B. fehlende Rechte\)

#### Usage

```text
!setup
```

#### Aliases

* `!guide`
* `!test`
* `!testbot`
* `!test-bot`

#### Examples

```text
!setup
```

### !softBan

Banne ein Mitlgied und es wird dann automatisch entbannt.

#### Usage

```text
!softBan [-d value|--deleteMessageDays=value] <user> [reason]
```

#### Aliases

* `!soft-ban`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | Member | Yes | Nutzer zum bannen. |  |
| reason | Text | No | Warum der nutzer gebannt wurde, |  |

#### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑deleteMessageDays | ‑d | Number | Delete messages from the user this many days back. |

#### Examples

### !strike

Add strikes to a user

#### Usage

```text
!strike <member> <type> <amount>
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| member | Member | Yes | The member receiving the strikes |  |
| type | Enum | Yes | The type of the violation | Use one of the following values: `allCaps`, `duplicateText`, `emojis`, `hoist`, `invites`, `links`, `mentionRoles`, `mentionUsers`, `quickMessages`, `words` |
| amount | Number | Yes | The amount of strikes to be added |  |

#### Examples

### !strikeConfig

Bearbeite strikes die für unterschiedliche Regelbrüche verteilt werden.

#### Usage

```text
!strikeConfig [violation] [strikes]
```

#### Aliases

* `!strike-config`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| violation | Enum | No | Typ des Regelbruchs. | Use one of the following values: `allCaps`, `duplicateText`, `emojis`, `hoist`, `invites`, `links`, `mentionRoles`, `mentionUsers`, `quickMessages`, `words` |
| strikes | Number | No | Anzahl an strikes. |  |

#### Examples

```text
!strikeConfig
```

### !subtractFakes

Entferne Fake Einladungen von allen Benutzern.

#### Usage

```text
!subtractFakes
```

#### Aliases

* `!subtract-fakes`
* `!subfakes`
* `!sf`

#### Examples

```text
!subtractFakes
```

### !subtractLeaves

Entferne Leaves von allen Benutzern.

#### Usage

```text
!subtractLeaves
```

#### Aliases

* `!subtract-leaves`
* `!subleaves`
* `!sl`

#### Examples

```text
!subtractLeaves
```

### !support

Get an invite link to our support server.

#### Usage

```text
!support
```

#### Examples

```text
!support
```

### !tryPremium

Try the premium version of InviteManager for free for a limited duration.

#### Usage

```text
!tryPremium
```

#### Aliases

* `!try`
* `!try-premium`

#### Examples

```text
!tryPremium
```

### !unban

Unban a user

#### Usage

```text
!unban <user> [reason]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | User | Yes | The user that should be unbanned. |  |
| reason | Text | No | The reason why this user is unbanned. |  |

#### Examples

### !unhoist

Add a character in front of all members with a special character in front of their name, so they will be shown at the end of the member list.

#### Usage

```text
!unhoist
```

#### Aliases

* `!dehoist`

#### Examples

```text
!unhoist
```

### !unmute

Unmute a user

#### Usage

```text
!unmute <user>
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | Member | Yes | The user that should be unmuted. |  |

#### Examples

### !warn

Warn a member.

#### Usage

```text
!warn <member> [reason]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| member | Member | Yes | Member to warn. |  |
| reason | Text | No | Why was the member was warned. |  |

#### Examples

