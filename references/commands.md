# Commands

## Commands

To get a list of available commands, do !help on your server.

### Arguments & Flags

Most commands accept arguments and/or flags.  
According to the **Type** of the argument or flag you can provide different values.

#### ブール値

この引数は、`true` または `false`を要求しています。 `yes`と `no`使用できます。

#### 番号

この引数には数値が必要です

#### 列挙型

この引数は、有効な値の特定のセットからの値を要求します。

> 有効な値はコマンドによって異なります。コマンドと列挙型の有効な値に関する詳細情報を取得するには、`!help<command>` \(eg. `!help addRank`\) と使用してください。

#### 招待コード

この引数は、Discord Invite Code を想定しています。

> `https://discord.gg/` の後ろの部分置くことができ、Discord がプレビューを作成しないようにします。

#### ユーザー

この引数は Discord ユーザーを想定しています。 次のいずれかの方法を使用して、ユーザーに指定できます:

-ユーザーをメンション: `@Valandur`

* 彼らの ID を使用: `102785693046026240`
* 彼らの名前を使用: `Valandur`
* 名前と識別名を使用: `Valandur#3581`
* 名前にスペースが含まれる場合は引用符を使用します: `"Valandur with a space"`

#### 役職

この引数は、Discord の Role を想定しています。 次のいずれかの方法を使用して、Role を指定できます。

* role をメンション: `@Admin`
* ID を使用: `102785693046026240`
* 名前を使用: `Admin`
* 名前にスペースがある場合は引用符を使用します: `"Admin with a space"`

#### チャンネル

この引数は Discord チャンネルを想定しています。 次のいずれかの方法を使用して、チャンネルを要求できます:

* チャンネルのメンション:`#general`
* ID を使用: `409846838129197057`
* 名前を使用: `general`
* 名前にスペースがある場合は引用符を使用します: `"general with a space"`

#### コマンド

This argument expects a command of this bot. You can use any of the following methods to provide a command:

* Use the command name: `invites`
* Use an alias of the command: `p`

#### テキスト

この引数には、任意のテキストが必要です。 スペースを含むテキストには、引用符\(`"Text with quotes"`\) を使用できます。

> テキストが最後の引数である場合、引用符を使用する必要はありません。

#### 日付

This argument expects a date. You can use various formats, but we recommend: `YYYY-MM-DD`

#### 期間

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
| addInvites | メンバーに招待を追加\(又は削除\)します。 | !addInvites \ \ \[reason\] |
| clearInvites | サーバー\(ユーザー\)の招待を削除します。 | !clearInvites \[-d value\|--date=value\]\[-cb\|--clearbonus\] \[user\] |
| createInvite | 永久の招待コードを作成します。 | !createInvite \ \[channel\]\[maxuses\] \[expires\]\[temporarymembership\] |
| info | 特定のメンバーに関する情報を表示します。 | !info \ \[details\]\[page\] |
| inviteCodes | すべての招待コードの一覧を取得する | !inviteCodes |
| inviteDetails | 招待状の送信元に関する詳細が表示されます。 | !inviteDetails \[user\] |
| invites | Show personal invites. | !invites \[user\] |
| leaderboard | 招待が最も多いメンバーを表示します。 | !leaderboard \[page\] |
| removeInvites | Removes a specified amount of invites from a user. | !removeInvites \ \ \[reason\] |
| restoreInvites | 以前にクリアした招待状をすべて復元します。 | !restoreInvites \[user\] |
| subtractFakes | すべてのユーザーから偽の招待を削除します。 | !subtractFakes |
| subtractLeaves | すべてのユーザーの退出履歴を削除します。 | !subtractLeaves |

#### Ranks

| Command | Description | Usage |
| :--- | :--- | :--- |
| addRank | 新しいランクを追加する。 | !addRank \ \ \[info\] |
| fixRanks | Deletes any ranks where the role was deleted. | !fixRanks |
| ranks | すべてのランクを見る | !ranks \[page\] |
| removeRank | ランクを外します。 | !removeRank \ |

#### Config

| Command | Description | Usage |
| :--- | :--- | :--- |
| botConfig | BOT の設定を表示および変更します。 | !botConfig \[key\]\[value\] |
| config | サーバーの設定を表示および変更します。 | !config \[key\]\[value\] |
| interactiveConfig | 対話型の設定 | !interactiveConfig |
| inviteCodeConfig | サーバーの招待リンクの設定を表示、変更します。 | !inviteCodeConfig \[key\]\[invitecode\] \[value\] |
| memberConfig | サーバーのメンバーの設定を表示および変更します。 | !memberConfig \[key\]\[user\] \[value\] |
| permissions | コマンドを使用するための権限を設定します。 | !permissions \[cmd\]\[role\] |

#### Info

| Command | Description | Usage |
| :--- | :--- | :--- |
| botInfo | BOT に関する基本的な情報を入手してください。 | !botInfo |
| credits | BOT の開発者と貢献者を表示します。 | !credits |
| getBot | ボットへの招待リンクを入手できます。 | !getBot |
| help | ヘルプを表示する。 | !help \[command\] |
| members | 現在のサーバーのメンバー数を表示します。 | !members |
| ping | ボットをピング | !ping |
| prefix | ボットの現在のプレフィックスを表示します。 | !prefix |
| setup | ボットの設定や問題の確認（権限の不足など）を手助けする | !setup |
| support | サポートサーバーへの招待リンクを入手してください。 | !support |

#### Premium

| Command | Description | Usage |
| :--- | :--- | :--- |
| export | InviteManager のデータを csv シートにエクスポートします。 | !export \ |
| premium | InviteManager のプレミアムバージョンに関する情報。 | !premium \[action\] |
| tryPremium | プレミアム版の InviteManager を期間限定で無料でお試しください。 | !tryPremium |

#### Moderation

| Command | Description | Usage |
| :--- | :--- | :--- |
| ban | サーバーからメンバーを BAN します。 | !ban \[-d value\|--deleteMessageDays=value\] \ \[reason\] |
| caseDelete | 指定したケースを削除します。 | !caseDelete \ \[reason\] |
| caseView | 特定のケースに関する情報を表示します。 | !caseView \ |
| check | ユーザーの違反と罰の回数を確認してください。 | !check \ |
| clean | 特定のチャットタイプを削除します。 | !clean \ \[numberOfMessages\] |
| cleanShort | 短いメッセージを消去する | !cleanShort \ \[numberOfMessages\] |
| cleanText | 指定のキーワードを含むメッセージを削除します。 | !cleanText \ \[numberOfMessages\] |
| kick | サーバーからメンバーを蹴ります。 | !kick \ \[reason\] |
| lockdown | Lockdown a specific channel \(Prevents anyone without special roles from sending messages\) | !lockdown \[-t value\|--timeout=value\]\[channel\] |
| mute | ユーザーをミュートする | !mute \[-d value\|--duration=value\] \ \[reason\] |
| punishmentConfig | 一定量の警告に達したときに罰を設定します。 | !punishmentConfig \[punishment\]\[strikes\] \[args\] |
| purge | チャネル内のメッセージを削除します。 | !purge \ \[user\] |
| purgeUntil | 指定されたメッセージまでチャネル内のメッセージを削除します。 | !purgeUntil \ |
| softBan | サーバーからメンバーを BAN してから自動的に BAN 解除します。 | !softBan \[-d value\|--deleteMessageDays=value\] \ \[reason\] |
| strike | ユーザーにストライクを追加する | !strike \ \ \ |
| strikeConfig | さまざまな違反に対して受け取った警告を設定します。 | !strikeConfig \[violation\]\[strikes\] |
| unban | ユーザーの BAN を解除する | !unban \ \[reason\] |
| unhoist | すべてのメンバーの前にその名前の前に特殊文字を付けて文字を追加すると、メンバーリストの最後にそれらが表示されます。 | !unhoist |
| unmute | ユーザーのミュートを解除する | !unmute \ |
| warn | メンバーに警告する | !warn \ \[reason\] |

#### Other

| Command | Description | Usage |
| :--- | :--- | :--- |
| graph | このサーバー上のさまざまな統計グラフを表示します。 | !graph \ \[from\]\[to\] |

### !addInvites

メンバーに招待を追加\(又は削除\)します。

#### Usage

```text
!addInvites <user> <amount> [reason]
```

#### Aliases

* `!add-invites`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | ユーザー | Yes | そのユーザーはボーナスの招待数を受け取る、または失うでしょう。 |  |
| amount | 番号 | Yes | ユーザーが取得、又は失う可能性のある招待の数。招待を削除する場合は`-`を用います。 |  |
| reason | テキスト | No | 招待数を追加\(又は削除\)した理由。 |  |

#### Examples

```text
!addInvites @User 5
```

```text
!addInvites "Name with space" -30 Removed for cheating
```

### !addRank

新しいランクを追加する。

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
| role | 役職 | Yes | このランクに到達したときにユーザーが受け取る役職。 |  |
| invites | 番号 | Yes | ランクに到達するために必要な招待の数。 |  |
| info | テキスト | No | ユーザーがこのランクについて知るために表示される説明。 |  |

#### Examples

```text
!addRank @Role 5
```

```text
!addRank "Role with space" 10 Wow, already 10 people!
```

### !ban

サーバーからメンバーを BAN します。

#### Usage

```text
!ban [-d value|--deleteMessageDays=value] <user> [reason]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | ユーザー | Yes | ユーザーを BAN する。 |  |
| reason | テキスト | No | ユーザーが BAN された理由。 |  |

#### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑deleteMessageDays | ‑d | 番号 | BAN するユーザーのメッセージを指定した日数分削除します |

#### Examples

### !botConfig

BOT の設定を表示および変更します。

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
| key | 列挙型 | No | 表示/変更したい設定。 | 以下のいずれかの値を使用:`activityEnabled`, `activityMessage`, `activityStatus`, `activityType`, `activityUrl`, `embedDefaultColor` |
| value | 値 | No | 設定の新しい値 |  |

#### Examples

```text
!botConfig
```

### !botInfo

BOT に関する基本的な情報を入手してください。

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

指定したケースを削除します。

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
| caseNumber | 番号 | Yes | ケース番号 |  |
| reason | テキスト | No | そのケースを削除した理由 |  |

#### Examples

```text
!caseDelete 5434 User apologized
```

### !caseView

特定のケースに関する情報を表示します。

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
| caseNumber | 番号 | Yes | ケース番号 |  |

#### Examples

```text
!caseView 5434
```

### !check

ユーザーの違反と罰の回数を確認してください。

#### Usage

```text
!check <user>
```

#### Aliases

* `!history`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | ユーザー | Yes | ユーザーを確認する。 |  |

#### Examples

```text
!check @User
```

```text
!check "User with space"
```

### !clean

特定のチャットタイプを削除します。

#### Usage

```text
!clean <type> [numberOfMessages]
```

#### Aliases

* `!clear`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| type | 列挙型 | Yes | 削除するメッセージの種類 | 以下のいずれかの値を使用:`bots`, `embeds`, `emojis`, `images`, `links`, `mentions`, `reacted`, `reactions` |
| numberOfMessages | 番号 | No | 削除されるメッセージの数 |  |

#### Examples

### !cleanShort

短いメッセージを消去する

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
| maxTextLength | 番号 | Yes | これより短いメッセージはすべて削除されます。 |  |
| numberOfMessages | 番号 | No | 削除されるメッセージの数 |  |

#### Examples

### !cleanText

指定のキーワードを含むメッセージを削除します。

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
| text | テキスト | Yes | この単語を含むすべてのメッセージが削除されます。 |  |
| numberOfMessages | 番号 | No | 検索されるメッセージの数 |  |

#### Examples

### !clearInvites

サーバー\(ユーザー\)の招待を削除します。

#### Usage

```text
!clearInvites [-d value|--date=value] [-cb|--clearBonus] [user]
```

#### Aliases

* `!clear-invites`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | ユーザー | No | 招待数をすべて削除する。省略された場合、すべてのメンバーが対象になります。 |  |

#### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑date | ‑d | 日付 | 招待の開始日を指定する必要があります。 デフォルトは今日です。 |
| ‑‑clearBonus | ‑cb | ブール値 | これを追加すると、ボーナスの招待数もクリアされます。省略した場合、ボーナスの招待状はそのまま残ります。 |

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

サーバーの設定を表示および変更します。

#### Usage

```text
!config [key] [value]
```

#### Aliases

* `!c`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| key | 列挙型 | No | 表示/変更したい設定。 | 以下のいずれかの値を使用:`autoModAllCapsEnabled`, `autoModAllCapsMinCharacters`, `autoModAllCapsPercentageCaps`, `autoModDeleteBotMessage`, `autoModDeleteBotMessageTimeoutInSeconds`, `autoModDisabledForOldMembers`, `autoModDisabledForOldMembersThreshold`, `autoModDuplicateTextEnabled`, `autoModDuplicateTextTimeframeInSeconds`, `autoModEmojisEnabled`, `autoModEmojisMaxNumberOfEmojis`, `autoModEnabled`, `autoModHoistEnabled`, `autoModIgnoredChannels`, `autoModIgnoredRoles`, `autoModInvitesEnabled`, `autoModLinksBlacklist`, `autoModLinksEnabled`, `autoModLinksFollowRedirects`, `autoModLinksWhitelist`, `autoModLogEnabled`, `autoModMentionRolesEnabled`, `autoModMentionRolesMaxNumberOfMentions`, `autoModMentionUsersEnabled`, `autoModMentionUsersMaxNumberOfMentions`, `autoModModeratedChannels`, `autoModModeratedRoles`, `autoModQuickMessagesEnabled`, `autoModQuickMessagesNumberOfMessages`, `autoModQuickMessagesTimeframeInSeconds`, `autoModWordsBlacklist`, `autoModWordsEnabled`, `autoSubtractFakes`, `autoSubtractLeaves`, `autoSubtractLeaveThreshold`, `captchaVerificationFailedMessage`, `captchaVerificationLogEnabled`, `captchaVerificationOnJoin`, `captchaVerificationSuccessMessage`, `captchaVerificationTimeout`, `captchaVerificationWelcomeMessage`, `channels`, `getUpdates`, `hideLeftMembersFromLeaderboard`, `ignoredChannels`, `joinMessage`, `joinMessageChannel`, `joinRoles`, `lang`, `leaderboardStyle`, `leaveMessage`, `leaveMessageChannel`, `logChannel`, `modLogChannel`, `modPunishmentBanDeleteMessage`, `modPunishmentKickDeleteMessage`, `modPunishmentMuteDeleteMessage`, `modPunishmentSoftbanDeleteMessage`, `modPunishmentWarnDeleteMessage`, `mutedRole`, `prefix`, `rankAnnouncementChannel`, `rankAnnouncementMessage`, `rankAssignmentStyle` |
| value | 値 | No | 設定の新しい値 |  |

#### Examples

```text
!config
```

### !createInvite

永久の招待コードを作成します。

#### Usage

```text
!createInvite <name> [channel] [maxUses] [expires] [temporaryMembership]
```

#### Aliases

* `!create-invite`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| name | テキスト | Yes | 招待リンクの名前。 |  |
| channel | チャンネル | No | 招待コードが作成されたチャンネル。 デフォルトで現在のチャンネルを使用します。 |  |
| maxUses | 番号 | No | `number` --&gt; The max amount of uses of the invite code |  |
| expires | ブール値 | No | `true` or `false` --&gt; Set if the invite will expires after 24 hours |  |
| temporaryMembership | ブール値 | No | `true` or `false` --&gt; Set if the invited users are granted as temporary members |  |

#### Examples

```text
!createInvite reddit
```

```text
!createInvite website #welcome
```

### !credits

BOT の開発者と貢献者を表示します。

#### Usage

```text
!credits
```

#### Examples

```text
!credits
```

### !export

InviteManager のデータを csv シートにエクスポートします。

#### Usage

```text
!export <type>
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| type | 列挙型 | Yes | 必要なエクスポートの種類。 | 以下のいずれかの値を使用:`leaderboard` |

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

ボットへの招待リンクを入手できます。

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

このサーバー上のさまざまな統計グラフを表示します。

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
| type | 列挙型 | Yes | 表示するチャートの種類。 | 以下のいずれかの値を使用:`joins`, `joinsAndLeaves`, `leaves` |
| from | 日付 | No | Start date of the chart |  |
| to | 日付 | No | End date of the chart |  |

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

ヘルプを表示する。

#### Usage

```text
!help [command]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| command | コマンド | No | 詳細情報を取得するためのコマンド。 | 以下のいずれかの値を使用:`addInvites`, `addRank`, `ban`, `botConfig`, `botInfo`, `caseDelete`, `caseView`, `check`, `clean`, `cleanShort`, `cleanText`, `clearInvites`, `config`, `createInvite`, `credits`, `export`, `fixRanks`, `getBot`, `graph`, `help`, `info`, `interactiveConfig`, `inviteCodeConfig`, `inviteCodes`, `inviteDetails`, `invites`, `kick`, `leaderboard`, `lockdown`, `memberConfig`, `members`, `mute`, `permissions`, `ping`, `prefix`, `premium`, `punishmentConfig`, `purge`, `purgeUntil`, `ranks`, `removeInvites`, `removeRank`, `restoreInvites`, `setup`, `softBan`, `strike`, `strikeConfig`, `subtractFakes`, `subtractLeaves`, `support`, `tryPremium`, `unban`, `unhoist`, `unmute`, `warn` |

#### Examples

```text
!help
```

```text
!help addRank
```

### !info

特定のメンバーに関する情報を表示します。

#### Usage

```text
!info <user> [details] [page]
```

#### Aliases

* `!showinfo`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | ユーザー | Yes | 追加情報を見たいユーザー。 |  |
| details | 列挙型 | No | メンバーに関する特定の詳細のみを要求します。 | 以下のいずれかの値を使用:`bonus`, `members` |
| page | 番号 | No | 表示する詳細のどのページ。 リアクションを使って移動することもできます。 |  |

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

対話型の設定

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

サーバーの招待リンクの設定を表示、変更します。

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
| key | 列挙型 | No | 表示/変更したい設定。 | 以下のいずれかの値を使用:`name`, `roles` |
| inviteCode | 招待コード | No | 招待リンクの設定を変更する。 |  |
| value | 値 | No | 新しい設定値 |  |

#### Examples

```text
!inviteCodeConfig
```

### !inviteCodes

すべての招待コードの一覧を取得する

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

招待状の送信元に関する詳細が表示されます。

#### Usage

```text
!inviteDetails [user]
```

#### Aliases

* `!invite-details`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | ユーザー | No | 詳細な招待状を見たいユーザー。 |  |

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

Show personal invites.

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
| user | ユーザー | No | 表示したいユーザーを招待します。 |  |

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

サーバーからメンバーを蹴ります。

#### Usage

```text
!kick <member> [reason]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| member | メンバー | Yes | メンバーをキックする |  |
| reason | テキスト | No | メンバーが蹴られた理由 |  |

#### Examples

### !leaderboard

招待が最も多いメンバーを表示します。

#### Usage

```text
!leaderboard [page]
```

#### Aliases

* `!top`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| page | 番号 | No | リーダーボードのどのページを取得するか。 |  |

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
| channel | チャンネル | No | The channel that you want to lock down. |  |

#### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑timeout | ‑t | 期間 | The timeout after which the lockdown automatically ends. Run the command again to end the lockdown manually. |

#### Examples

```text
!lockdown
```

### !memberConfig

サーバーのメンバーの設定を表示および変更します。

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
| key | 列挙型 | No | 表示/変更したいメンバー構成設定。 | 以下のいずれかの値を使用:`hideFromLeaderboard` |
| user | ユーザー | No | 設定が表示/変更されたメンバー。 |  |
| value | 値 | No | 設定の新しい値 |  |

#### Examples

```text
!memberConfig
```

### !members

現在のサーバーのメンバー数を表示します。

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

ユーザーをミュートする

#### Usage

```text
!mute [-d value|--duration=value] <user> [reason]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | メンバー | Yes | ミュートする必要があるユーザー。 |  |
| reason | テキスト | No | このユーザーがミュートされている理由 |  |

#### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑duration | ‑d | 期間 | The duration to mute the user for |

#### Examples

### !permissions

コマンドを使用するための権限を設定します。

#### Usage

```text
!permissions [cmd] [role]
```

#### Aliases

* `!perms`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| cmd | コマンド | No | 権限を設定するためのコマンド。 | 以下のいずれかの値を使用:`addInvites`, `addRank`, `ban`, `botConfig`, `botInfo`, `caseDelete`, `caseView`, `check`, `clean`, `cleanShort`, `cleanText`, `clearInvites`, `config`, `createInvite`, `credits`, `export`, `fixRanks`, `getBot`, `graph`, `help`, `info`, `interactiveConfig`, `inviteCodeConfig`, `inviteCodes`, `inviteDetails`, `invites`, `kick`, `leaderboard`, `lockdown`, `memberConfig`, `members`, `mute`, `permissions`, `ping`, `prefix`, `premium`, `punishmentConfig`, `purge`, `purgeUntil`, `ranks`, `removeInvites`, `removeRank`, `restoreInvites`, `setup`, `softBan`, `strike`, `strikeConfig`, `subtractFakes`, `subtractLeaves`, `support`, `tryPremium`, `unban`, `unhoist`, `unmute`, `warn` |
| role | 役職 | No | コマンドへのアクセスを許可または拒否する役職。 |  |

#### Examples

```text
!permissions
```

### !ping

ボットをピング

#### Usage

```text
!ping
```

#### Examples

```text
!ping
```

### !prefix

ボットの現在のプレフィックスを表示します。

#### Usage

```text
!prefix
```

#### Examples

```text
!prefix
```

### !premium

InviteManager のプレミアムバージョンに関する情報。

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
| action | 列挙型 | No | プレミアム情報はありません。 あなたのプレミアムステータスをチェックするために `check`。 このサーバーにプレミアムを使用するには `activate`してください。 | 以下のいずれかの値を使用:`Activate`, `Check`, `Deactivate` |

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

一定量の警告に達したときに罰を設定します。

#### Usage

```text
!punishmentConfig [punishment] [strikes] [args]
```

#### Aliases

* `!punishment-config`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| punishment | 列挙型 | No | 使用する罰の種類 | 以下のいずれかの値を使用:`ban`, `kick`, `mute`, `softban`, `warn` |
| strikes | 番号 | No | この罰が適用されるための警告の数。 |  |
| args | テキスト | No | 議論は罰に渡された。 |  |

#### Examples

```text
!punishmentConfig
```

### !purge

チャネル内のメッセージを削除します。

#### Usage

```text
!purge <quantity> [user]
```

#### Aliases

* `!prune`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| quantity | 番号 | Yes | 削除するメッセージ数。 |  |
| user | ユーザー | No | ユーザーのメッセージは削除されました。 |  |

#### Examples

### !purgeUntil

指定されたメッセージまでチャネル内のメッセージを削除します。

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
| messageID | テキスト | Yes | 最後のメッセージ ID は削除されました。 |  |

#### Examples

### !ranks

すべてのランクを見る

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
| page | 番号 | No | The page of the ranks list to show. |  |

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
| user | ユーザー | Yes | The user to remove the invites from. |  |
| amount | 番号 | Yes | The amount of invites to remove. |  |
| reason | テキスト | No | The reason for removing the invites. |  |

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

ランクを外します。

#### Usage

```text
!removeRank <rank>
```

#### Aliases

* `!remove-rank`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| rank | 役職 | Yes | ランクを削除したい対象です。 |  |

#### Examples

```text
!removeRank @Role
```

```text
!removeRank "Role with space"
```

### !restoreInvites

以前にクリアした招待状をすべて復元します。

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
| user | ユーザー | No | ユーザーのすべての招待を復元する。 省略すると、すべてのユーザーの招待が復元されます。 |  |

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

ボットの設定や問題の確認（権限の不足など）を手助けする

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

サーバーからメンバーを BAN してから自動的に BAN 解除します。

#### Usage

```text
!softBan [-d value|--deleteMessageDays=value] <user> [reason]
```

#### Aliases

* `!soft-ban`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | メンバー | Yes | メンバーを BAN する |  |
| reason | テキスト | No | ユーザーが BAN された理由 |  |

#### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑deleteMessageDays | ‑d | 番号 | Delete messages from the user this many days back. |

#### Examples

### !strike

ユーザーにストライクを追加する

#### Usage

```text
!strike <member> <type> <amount>
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| member | メンバー | Yes | メンバーがストライキを受けました。 |  |
| type | 列挙型 | Yes | 違反の種類 | 以下のいずれかの値を使用:`allCaps`, `duplicateText`, `emojis`, `hoist`, `invites`, `links`, `mentionRoles`, `mentionUsers`, `quickMessages`, `words` |
| amount | 番号 | Yes | 追加するストライクの量 |  |

#### Examples

### !strikeConfig

さまざまな違反に対して受け取った警告を設定します。

#### Usage

```text
!strikeConfig [violation] [strikes]
```

#### Aliases

* `!strike-config`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| violation | 列挙型 | No | 違反のタイプ | 以下のいずれかの値を使用:`allCaps`, `duplicateText`, `emojis`, `hoist`, `invites`, `links`, `mentionRoles`, `mentionUsers`, `quickMessages`, `words` |
| strikes | 番号 | No | 警告の数 |  |

#### Examples

```text
!strikeConfig
```

### !subtractFakes

すべてのユーザーから偽の招待を削除します。

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

すべてのユーザーの退出履歴を削除します。

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

サポートサーバーへの招待リンクを入手してください。

#### Usage

```text
!support
```

#### Examples

```text
!support
```

### !tryPremium

プレミアム版の InviteManager を期間限定で無料でお試しください。

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

ユーザーの BAN を解除する

#### Usage

```text
!unban <user> [reason]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | ユーザー | Yes | BAN を解除すべきユーザー。 |  |
| reason | テキスト | No | このユーザーの BAN が解除された理由。 |  |

#### Examples

### !unhoist

すべてのメンバーの前にその名前の前に特殊文字を付けて文字を追加すると、メンバーリストの最後にそれらが表示されます。

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

ユーザーのミュートを解除する

#### Usage

```text
!unmute <user>
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | メンバー | Yes | ミュートを解除する必要があるユーザー。 |  |

#### Examples

### !warn

メンバーに警告する

#### Usage

```text
!warn <member> [reason]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| member | メンバー | Yes | メンバーに警告する |  |
| reason | テキスト | No | メンバーが警告された理由。 |  |

#### Examples

