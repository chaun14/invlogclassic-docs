# Commands

## Commands

To get a list of available commands, do !help on your server.

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
| addInvites | Dodaje/Usuwa zaproszenia dla/od członka. | !addInvites \ \ \[reason\] |
| clearInvites | Wyczyść zaproszenia serwera/użytkownika. | !clearInvites \[-d value\|--date=value\]\[-cb\|--clearbonus\] \[user\] |
| createInvite | Tworzy unikalne kody zaproszeń. | !createInvite \ \[channel\]\[maxuses\] \[expires\]\[temporarymembership\] |
| info | Pokaż informacje o określonym członku. | !info \ \[details\]\[page\] |
| inviteCodes | Zdobądź listę wszystkich twoich kodów zaproszeń | !inviteCodes |
| inviteDetails | Pokazuje szczegóły skąd są twoje zaproszenia. | !inviteDetails \[user\] |
| invites | Pokaż osobiste zaproszenia. | !invites \[user\] |
| leaderboard | Pokaż członków z największą liczbą zaproszeń. | !leaderboard \[page\] |
| removeInvites | Removes a specified amount of invites from a user. | !removeInvites \ \ \[reason\] |
| restoreInvites | Restore all previously cleared invites. | !restoreInvites \[user\] |
| subtractFakes | Remove fake invites from all users. | !subtractFakes |
| subtractLeaves | Remove leaves from all users | !subtractLeaves |

#### Ranks

| Command | Description | Usage |
| :--- | :--- | :--- |
| addRank | Dodaj nową rangę. | !addRank \ \ \[info\] |
| fixRanks | Deletes any ranks where the role was deleted. | !fixRanks |
| ranks | Show all ranks. | !ranks \[page\] |
| removeRank | Remove a rank. | !removeRank \ |

#### Config

| Command | Description | Usage |
| :--- | :--- | :--- |
| botConfig | Pokaż i zmień konfigurację bota. | !botConfig \[key\]\[value\] |
| config | Pokaż i zmień konfigurację serwera. | !config \[key\]\[value\] |
| interactiveConfig | Interaktywna konfiguracja | !interactiveConfig |
| inviteCodeConfig | Pokaż i zmień konfiguracje kodu zaproszenia serwera. | !inviteCodeConfig \[key\]\[invitecode\] \[value\] |
| memberConfig | Pokaż i zmień konfigurację członków serwera. | !memberConfig \[key\]\[user\] \[value\] |
| permissions | Configure permissions to use commands. | !permissions \[cmd\]\[role\] |

#### Info

| Command | Description | Usage |
| :--- | :--- | :--- |
| botInfo | Uzyskaj ogólne informacje o bocie. | !botInfo |
| credits | Pokaż deweloperów i kontrybutorów bota. | !credits |
| getBot | Uzyskaj link zaproszenia dla bota. | !getBot |
| help | Pokaż pomoc | !help \[command\] |
| members | Pokaż liczbę członków bieżącego serwera. | !members |
| ping | Ping the bot | !ping |
| prefix | Shows the current prefix of the bot. | !prefix |
| setup | Help with setting up the bot and checking for problems \(e.g. missing permissions\) | !setup |
| support | Get an invite link to our support server. | !support |

#### Premium

| Command | Description | Usage |
| :--- | :--- | :--- |
| export | Eksportuj dane InviteManager do arkusza CSV. | !export \ |
| premium | Info about premium version of InviteManager. | !premium \[action\] |
| tryPremium | Try the premium version of InviteManager for free for a limited duration. | !tryPremium |

#### Moderation

| Command | Description | Usage |
| :--- | :--- | :--- |
| ban | Banuje członka z serwera. | !ban \[-d value\|--deleteMessageDays=value\] \ \[reason\] |
| caseDelete | Usuń określoną sprawę. | !caseDelete \ \[reason\] |
| caseView | Wyświetl informacje o określonej sprawie. | !caseView \ |
| check | Sprawdź historię naruszeń i kar użytkownika. | !check \ |
| clean | Wyczyść kanał niektórych typów wiadomości. | !clean \ \[numberOfMessages\] |
| cleanShort | Wyczyść krótkie wiadomości | !cleanShort \ \[numberOfMessages\] |
| cleanText | Usuń wiadomości zawierające określone słowa kluczowe. | !cleanText \ \[numberOfMessages\] |
| kick | Wyrzuć członka z serwera. | !kick \ \[reason\] |
| lockdown | Lockdown a specific channel \(Prevents anyone without special roles from sending messages\) | !lockdown \[-t value\|--timeout=value\]\[channel\] |
| mute | Mute a user | !mute \[-d value\|--duration=value\] \ \[reason\] |
| punishmentConfig | Configure punishments when reaching a certain amount of strikes. | !punishmentConfig \[punishment\]\[strikes\] \[args\] |
| purge | Purge messages in a channel. | !purge \ \[user\] |
| purgeUntil | Purge messages in a channel up until a specified message. | !purgeUntil \ |
| softBan | Ban and then automatically unban a member from the server. | !softBan \[-d value\|--deleteMessageDays=value\] \ \[reason\] |
| strike | Add strikes to a user | !strike \ \ \ |
| strikeConfig | Configure strikes received for various violations. | !strikeConfig \[violation\]\[strikes\] |
| unban | Unban a user | !unban \ \[reason\] |
| unhoist | Add a character in front of all members with a special character in front of their name, so they will be shown at the end of the member list. | !unhoist |
| unmute | Unmute a user | !unmute \ |
| warn | Warn a member. | !warn \ \[reason\] |

#### Other

| Command | Description | Usage |
| :--- | :--- | :--- |
| graph | Pokazuje wykresy dotyczące różnych statystyk na tym serwerze. | !graph \ \[from\]\[to\] |

### !addInvites

Dodaje/Usuwa zaproszenia dla/od członka.

#### Usage

```text
!addInvites <user> <amount> [reason]
```

#### Aliases

* `!add-invites`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | User | Yes | Użytkownik, który otrzyma/straci bonusowe zaproszenia. |  |
| amount | Number | Yes | Ilość zaproszeń, które użytkownik otrzyma/straci. Użyj liczby ujemnej \(-\), aby usunąć zaproszenia. |  |
| reason | Text | No | Powód dodania/usunięcia zaproszeń. |  |

#### Examples

```text
!addInvites @User 5
```

```text
!addInvites "Name with space" -30 Removed for cheating
```

### !addRank

Dodaj nową rangę.

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
| role | Role | Yes | Rola, którą użytkownik otrzyma po osiągnięciu tej rangi. |  |
| invites | Number | Yes | Ilość zaproszeń potrzebnych do osiągnięcia rangi. |  |
| info | Text | No | Opis, który zobaczą użytkownicy, aby dowiedzieć się więcej o tej randze. |  |

#### Examples

```text
!addRank @Role 5
```

```text
!addRank "Role with space" 10 Wow, already 10 people!
```

### !ban

Banuje członka z serwera.

#### Usage

```text
!ban [-d value|--deleteMessageDays=value] <user> [reason]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | User | Yes | Użytkownik do zbanowania. |  |
| reason | Text | No | Dlaczego użytkownik został zbanowany. |  |

#### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑deleteMessageDays | ‑d | Number | Jeśli zostanie określony, usunie wiadomości od zbanowanych członków sprzed kilku dni. |

#### Examples

### !botConfig

Pokaż i zmień konfigurację bota.

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
| key | Enum | No | Ustawienie konfiguracji bota, które chcesz pokazać/zmienić. | Use one of the following values: `activityEnabled`, `activityMessage`, `activityStatus`, `activityType`, `activityUrl`, `embedDefaultColor` |
| value | Value | No | Nowa wartość ustawienia. |  |

#### Examples

```text
!botConfig
```

### !botInfo

Uzyskaj ogólne informacje o bocie.

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

Usuń określoną sprawę.

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
| caseNumber | Number | Yes | Numer sprawy |  |
| reason | Text | No | Powód usunięcia sprawy. |  |

#### Examples

```text
!caseDelete 5434 User apologized
```

### !caseView

Wyświetl informacje o określonej sprawie.

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
| caseNumber | Number | Yes | Numer sprawy |  |

#### Examples

```text
!caseView 5434
```

### !check

Sprawdź historię naruszeń i kar użytkownika.

#### Usage

```text
!check <user>
```

#### Aliases

* `!history`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | User | Yes | Użytkownik do sprawdzenia. |  |

#### Examples

```text
!check @User
```

```text
!check "User with space"
```

### !clean

Wyczyść kanał niektórych typów wiadomości.

#### Usage

```text
!clean <type> [numberOfMessages]
```

#### Aliases

* `!clear`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| type | Enum | Yes | Typ wiadomości, które zostaną usunięte. | Use one of the following values: `bots`, `embeds`, `emojis`, `images`, `links`, `mentions`, `reacted`, `reactions` |
| numberOfMessages | Number | No | Liczba wiadomości, które będą wyszukiwane. |  |

#### Examples

### !cleanShort

Wyczyść krótkie wiadomości

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
| maxTextLength | Number | Yes | Wszystkie wiadomości krótsze niż ta zostaną usunięte. |  |
| numberOfMessages | Number | No | Liczba wiadomości, które będą wyszukiwane. |  |

#### Examples

### !cleanText

Usuń wiadomości zawierające określone słowa kluczowe.

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
| text | Text | Yes | Wszystkie wiadomości zawierające to słowo zostaną usunięte. |  |
| numberOfMessages | Number | No | Liczba wiadomości, które będą wyszukiwane. |  |

#### Examples

### !clearInvites

Wyczyść zaproszenia serwera/użytkownika.

#### Usage

```text
!clearInvites [-d value|--date=value] [-cb|--clearBonus] [user]
```

#### Aliases

* `!clear-invites`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | User | No | Użytkownik, któremu usunąć wszystkie zaproszenia. Jeśli pominięto, usuwa wszystkich użytkowników. |  |

#### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑date | ‑d | Date | Data rozpoczęcia, w której należy liczyć zaproszenia. Domyślnie jest to dzisiaj. |
| ‑‑clearBonus | ‑cb | Boolean | Dodaj tę flagę, aby wyczyścić również bonusowe zaproszenia. W przeciwnym razie bonusowe zaproszenia pozostaną nietknięte. |

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

Pokaż i zmień konfigurację serwera.

#### Usage

```text
!config [key] [value]
```

#### Aliases

* `!c`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| key | Enum | No | Ustawienie konfiguracyjne, które chcesz pokazać/zmienić. | Use one of the following values: `autoModAllCapsEnabled`, `autoModAllCapsMinCharacters`, `autoModAllCapsPercentageCaps`, `autoModDeleteBotMessage`, `autoModDeleteBotMessageTimeoutInSeconds`, `autoModDisabledForOldMembers`, `autoModDisabledForOldMembersThreshold`, `autoModDuplicateTextEnabled`, `autoModDuplicateTextTimeframeInSeconds`, `autoModEmojisEnabled`, `autoModEmojisMaxNumberOfEmojis`, `autoModEnabled`, `autoModHoistEnabled`, `autoModIgnoredChannels`, `autoModIgnoredRoles`, `autoModInvitesEnabled`, `autoModLinksBlacklist`, `autoModLinksEnabled`, `autoModLinksFollowRedirects`, `autoModLinksWhitelist`, `autoModLogEnabled`, `autoModMentionRolesEnabled`, `autoModMentionRolesMaxNumberOfMentions`, `autoModMentionUsersEnabled`, `autoModMentionUsersMaxNumberOfMentions`, `autoModModeratedChannels`, `autoModModeratedRoles`, `autoModQuickMessagesEnabled`, `autoModQuickMessagesNumberOfMessages`, `autoModQuickMessagesTimeframeInSeconds`, `autoModWordsBlacklist`, `autoModWordsEnabled`, `autoSubtractFakes`, `autoSubtractLeaves`, `autoSubtractLeaveThreshold`, `captchaVerificationFailedMessage`, `captchaVerificationLogEnabled`, `captchaVerificationOnJoin`, `captchaVerificationSuccessMessage`, `captchaVerificationTimeout`, `captchaVerificationWelcomeMessage`, `channels`, `getUpdates`, `hideLeftMembersFromLeaderboard`, `ignoredChannels`, `joinMessage`, `joinMessageChannel`, `joinRoles`, `lang`, `leaderboardStyle`, `leaveMessage`, `leaveMessageChannel`, `logChannel`, `modLogChannel`, `modPunishmentBanDeleteMessage`, `modPunishmentKickDeleteMessage`, `modPunishmentMuteDeleteMessage`, `modPunishmentSoftbanDeleteMessage`, `modPunishmentWarnDeleteMessage`, `mutedRole`, `prefix`, `rankAnnouncementChannel`, `rankAnnouncementMessage`, `rankAssignmentStyle` |
| value | Value | No | Nowa wartość ustawienia. |  |

#### Examples

```text
!config
```

### !createInvite

Tworzy unikalne kody zaproszeń.

#### Usage

```text
!createInvite <name> [channel] [maxUses] [expires] [temporaryMembership]
```

#### Aliases

* `!create-invite`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| name | Text | Yes | Nazwa kodu zaproszenia. |  |
| channel | Channel | No | Kanał, dla którego tworzony jest kod zaproszenia. Domyślnie używa bieżącego kanału. |  |
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

Pokaż deweloperów i kontrybutorów bota.

#### Usage

```text
!credits
```

#### Examples

```text
!credits
```

### !export

Eksportuj dane InviteManager do arkusza CSV.

#### Usage

```text
!export <type>
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| type | Enum | Yes | Rodzaj pliku, który eksportujesz. | Use one of the following values: `leaderboard` |

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

Uzyskaj link zaproszenia dla bota.

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

Pokazuje wykresy dotyczące różnych statystyk na tym serwerze.

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
| type | Enum | Yes | Typ wykresu do wyświetlenia. | Use one of the following values: `joins`, `joinsAndLeaves`, `leaves` |
| from | Date | No | Data rozpoczęcia wykresu |  |
| to | Date | No | Data zakończenia wykresu |  |

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

Pokaż pomoc

#### Usage

```text
!help [command]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| command | Command | No | Polecenie, dla którego uzyskać szczegółowe informacje. | Use one of the following values: `addInvites`, `addRank`, `ban`, `botConfig`, `botInfo`, `caseDelete`, `caseView`, `check`, `clean`, `cleanShort`, `cleanText`, `clearInvites`, `config`, `createInvite`, `credits`, `export`, `fixRanks`, `getBot`, `graph`, `help`, `info`, `interactiveConfig`, `inviteCodeConfig`, `inviteCodes`, `inviteDetails`, `invites`, `kick`, `leaderboard`, `lockdown`, `memberConfig`, `members`, `mute`, `permissions`, `ping`, `prefix`, `premium`, `punishmentConfig`, `purge`, `purgeUntil`, `ranks`, `removeInvites`, `removeRank`, `restoreInvites`, `setup`, `softBan`, `strike`, `strikeConfig`, `subtractFakes`, `subtractLeaves`, `support`, `tryPremium`, `unban`, `unhoist`, `unmute`, `warn` |

#### Examples

```text
!help
```

```text
!help addRank
```

### !info

Pokaż informacje o określonym członku.

#### Usage

```text
!info <user> [details] [page]
```

#### Aliases

* `!showinfo`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | User | Yes | Użytkownik, dla którego chcesz zobaczyć dodatkowe informacje. |  |
| details | Enum | No | Poproś tylko o szczegółowe informacje na temat członka. | Use one of the following values: `bonus`, `members` |
| page | Number | No | Jaka strona szczegółów do pokazania. Możesz także użyć reakcji do nawigacji. |  |

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

Interaktywna konfiguracja

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

Pokaż i zmień konfiguracje kodu zaproszenia serwera.

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
| key | Enum | No | Konfiguracja ustawienia jaką chcesz pokazać/zmienić. | Use one of the following values: `name`, `roles` |
| inviteCode | Invite Code | No | Kod zaproszenia dla którego chcesz zmienić ustawienia. |  |
| value | Value | No | Nowa wartość ustawienia |  |

#### Examples

```text
!inviteCodeConfig
```

### !inviteCodes

Zdobądź listę wszystkich twoich kodów zaproszeń

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

Pokazuje szczegóły skąd są twoje zaproszenia.

#### Usage

```text
!inviteDetails [user]
```

#### Aliases

* `!invite-details`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | User | No | Użytkownik kogo chcesz zobaczyć szczegółowo zaproszenia. |  |

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

Pokaż osobiste zaproszenia.

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
| user | User | No | Użytkownik, dla którego chcesz pokazać zaproszenia. |  |

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

Wyrzuć członka z serwera.

#### Usage

```text
!kick <member> [reason]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| member | Member | Yes | Członkowie do wyrzucenia. |  |
| reason | Text | No | Dlaczego członek został wyrzucony. |  |

#### Examples

### !leaderboard

Pokaż członków z największą liczbą zaproszeń.

#### Usage

```text
!leaderboard [page]
```

#### Aliases

* `!top`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| page | Number | No | Którą stronę z tabeli liderów?. |  |

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

Pokaż i zmień konfigurację członków serwera.

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
| key | Enum | No | Ustawienie konfiguracji członka, które chcesz pokazać/zmienić. | Use one of the following values: `hideFromLeaderboard` |
| user | User | No | Członek, dla którego ustawienie jest pokazane/zmienione. |  |
| value | Value | No | Nowa wartość ustawienia. |  |

#### Examples

```text
!memberConfig
```

### !members

Pokaż liczbę członków bieżącego serwera.

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

Configure punishments when reaching a certain amount of strikes.

#### Usage

```text
!punishmentConfig [punishment] [strikes] [args]
```

#### Aliases

* `!punishment-config`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| punishment | Enum | No | Type of punishment to use. | Use one of the following values: `ban`, `kick`, `mute`, `softban`, `warn` |
| strikes | Number | No | Number of strikes for this punishment to be used. |  |
| args | Text | No | Arguments passed to the punishment. |  |

#### Examples

```text
!punishmentConfig
```

### !purge

Purge messages in a channel.

#### Usage

```text
!purge <quantity> [user]
```

#### Aliases

* `!prune`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| quantity | Number | Yes | How many messages should be deleted. |  |
| user | User | No | User whose messages are deleted. |  |

#### Examples

### !purgeUntil

Purge messages in a channel up until a specified message.

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
| messageID | Text | Yes | Last message ID to be deleted. |  |

#### Examples

### !ranks

Show all ranks.

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

Remove a rank.

#### Usage

```text
!removeRank <rank>
```

#### Aliases

* `!remove-rank`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| rank | Role | Yes | The for which you want to remove the rank. |  |

#### Examples

```text
!removeRank @Role
```

```text
!removeRank "Role with space"
```

### !restoreInvites

Restore all previously cleared invites.

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
| user | User | No | The user to restore all invites to. If omitted restores invites for all users. |  |

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

Help with setting up the bot and checking for problems \(e.g. missing permissions\)

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

Ban and then automatically unban a member from the server.

#### Usage

```text
!softBan [-d value|--deleteMessageDays=value] <user> [reason]
```

#### Aliases

* `!soft-ban`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | Member | Yes | User to ban. |  |
| reason | Text | No | Why was the user banned. |  |

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

Configure strikes received for various violations.

#### Usage

```text
!strikeConfig [violation] [strikes]
```

#### Aliases

* `!strike-config`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| violation | Enum | No | Violation type. | Use one of the following values: `allCaps`, `duplicateText`, `emojis`, `hoist`, `invites`, `links`, `mentionRoles`, `mentionUsers`, `quickMessages`, `words` |
| strikes | Number | No | Number of strikes. |  |

#### Examples

```text
!strikeConfig
```

### !subtractFakes

Remove fake invites from all users.

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

Remove leaves from all users

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

