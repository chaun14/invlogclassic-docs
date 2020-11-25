# Settings

## Configs

There are many config options that can be set. You don't have to set all of them. If you just added the bot, just run `!setup`, which will guide you through the most important ones.

### Overview

#### 総合

| Setting | Description |
| :--- | :--- |
| 接頭辞 | ボットコマンドを呼びだすために使用されるプレフィックス。 |
| 言語 | BOT の言語 |
| ログチャンネル | ボットアクションが記録されるチャンネル。 |
| アップデート情報を手に入れる | InviteManager に関する開発の最新情報を受け取ることができるようにします。 |
| コマンドチャンネル | ボットがコマンドに反応するチャンネル。 |
| 無視されるチャンネル | ボットがコマンドを無視するチャンネル。 |

#### 招待

**General**

| Setting | Description |
| :--- | :--- |
| Join Roles | Roles that are assigned to all members when joining. |

**参加**

| Setting | Description |
| :--- | :--- |
| メッセージ | サーバーに参加したときに送信されるメッセージ。 |
| メッセージチャンネル | 参加時のメッセージが送信されるチャンネル。 |

**退出**

| Setting | Description |
| :--- | :--- |
| メッセージ | サーバーを離れたときに送信されるメッセージ。 |
| メッセージチャンネル | 退出メッセージが送信されるチャンネル。 |
| 自動減算 | 招待ユーザーが退出したときに招待者から招待状を自動的に削除します。 |
| 自動減算しきい値 | 招待を数えるためにユーザーがサーバーに留まる必要がある時間（秒）。 |

**リーダーボード**

| Setting | Description |
| :--- | :--- |
| スタイル | リーダーボードの表示スタイル。 |
| 退出メンバーを隠す | リーダーボードからサーバーを離れたメンバーを非表示にします。 |

**偽**

| Setting | Description |
| :--- | :--- |
| 自動減算 | 自動的に偽の招待を差し引きます。 |

**ランク**

| Setting | Description |
| :--- | :--- |
| 割り当てスタイル | ランクはユーザーにどのように与えられますか。 |
| お知らせチャンネル | ユーザーが新しいランクを獲得したときにアナウンスするチャンネル。 |
| お知らせメッセージ | ユーザーが新しいランクを受け取ったときに送信されるメッセージ。 |

#### 管理

**Captcha**

| Setting | Description |
| :--- | :--- |
| 有効 | キャプチャ検証が有効かどうか。 |
| 参加メッセージ | ユーザーがサーバーに参加してキャプチャに入るように指示した後に表示されるメッセージ。 |
| 成功メッセージ | ユーザーが正常に確認した後にユーザーに送信されるウェルカムメッセージ。 |
| 失敗メッセージ | ユーザーが無効なキャプチャを入力した場合にメッセージがユーザーに送信されます。 |
| 認証タイムアウト | キャプチャが正常に入力されなければならない時間。 |
| ログが有効化されました | 検証の試行がログに記録されるかどうか。 |

**総合**

| Setting | Description |
| :--- | :--- |
| 有効 | Automatically moderate messages \(specific rules can also be turned on or off, this has to be ON for ANY rule to work\). |
| 管理チャンネル | The list of moderated channels \(this acts as a whitelist, leave empty to moderate all channels, or use `autoModIgnoredChannels` to ignore certain channels\). |
| 管理役職 | The list of roles that are moderated \(this acts as a whitelist, leave empty to moderate all roles, or use `autoModIgnoredRoles` to ignore certain roles\). |
| 無視されるチャンネル | Channels that are ignored while automatically moderating. |
| 無視される役職 | Any members with these roles will not automatically be moderated. |
| ミュート役職 | The role that is given to people who are muted. Make sure this role is denied the "Send Message" permission. |
| 古いメンバーには無効 | Disabled auto moderation for members that have been in your server for a long time. |
| 古いメンバーのしきい値 | The amount of time a member has to be in your server to be considered 'old'. |

**ログを記録する**

| Setting | Description |
| :--- | :--- |
| ログが有効化されました | Log any moderation actions that the bot makes. |
| MOD ログチャンネル | モデレーションログが記録されるチャンネル。 |
| BOT のメッセージを削除 | Automatically delete the bots own messages \(keeps your chat clean\). |
| ボットメッセージタイムアウトの削除 | The timeout after which bot messages are deleted. |
| BAN メッセージを削除 | 「禁止」プッシュメッセージを自動的に削除するかどうか。 |
| キックメッセージを削除 | 「キック」プッシュメッセージが自動的に削除されるかどうか。 |
| ソフト BAN メッセージを削除 | 「Softban」プッシュメッセージが自動的に削除されるかどうか。 |
| 警告メッセージを削除 | 「警告」プッシュメッセージを自動的に削除するかどうか。 |
| ミュートメッセージを削除 | 「ミュート」プッシュメッセージが自動的に削除されるかどうか。 |

**招待**

| Setting | Description |
| :--- | :--- |
| 有効 | Automatically scan messages for discord invite links and remove them. |

**リンク**

| Setting | Description |
| :--- | :--- |
| 有効 | Automatically remove messages containing links \(you can set a whitelist and blacklist\). |
| ホワイトリスト | A list of links that users are allowed to post. |
| ブラックリスト | Blacklist certain links which users won't be able to post. |
| リダイレクトをフォローする | Enable this to resolve redirects for links. |

**禁止された単語**

| Setting | Description |
| :--- | :--- |
| 有効 | ブラックリストに載っている単語を自動対応するかどうか |
| ブラックリスト | 禁止されている単語のリスト。 |

**キャップ**

| Setting | Description |
| :--- | :--- |
| 有効 | 自動的に 適度な メッセージ とともに 多くのキャップ |
| 最小文字 | あの ミニマム 量 の キャラクター に メッセージ へ なる 検討する ために 適度な \(セッティング へ '3' しましょう 無視する 'オーケー'\). |
| 煽りのパーセント | あの 割合 の キャラクター の あの メッセージ それ 持ってる へ なる クリック数 ために あの ルール へ 引き金. |

**重複メッセージ**

| Setting | Description |
| :--- | :--- |
| 有効化 | Automatically moderate duplicate messages \(copy-paste spam\). |
| 秒単位のタイムフレーム | The timeframe whithin which messages will be considered duplicates. |

**スパム**

| Setting | Description |
| :--- | :--- |
| 有効 | Automatically moderate users sending a lot of messages in a short time. |
| \#のメッセージ数 | The number of messages that have to be sent within the timeframe to trigger the rule. |
| 秒単位のタイムフレーム | The timeframe within which a user is allowed to send a maximum amount of messages. |

**メンション**

| Setting | Description |
| :--- | :--- |
| 有効 | Automatically moderate messages that mention an excessive amount of users. |
| メンション | The maximum amount of users a member can mention in a message. |
| 有効 | Automatically moderate messages that mention an excessive amount of roles. |
| メンション | The maximum amount of roles a member can mention in a message. |

**絵文字**

| Setting | Description |
| :--- | :--- |
| 有効 | Automatically moderate messages with an excessive amount of emojis. |
| 絵文字の最大数 | The maximum amount of emojis a message is allowed to have before trigger the rule. |
| Enabled | Automatically give members nicknames if they try to hoist \(use special characters to appear at the top of the user list\). |

### 接頭辞

ボットコマンドを呼びだすために使用されるプレフィックス。

Type: `String`

Default: `!`

Reset to default: `!config prefix default`

Examples:

`!config prefix +`

`!config prefix >`

### 言語

BOT の言語

Type: `Enum<Lang>`

Default: `en`

Reset to default: `!config lang default`

Possible values: `ar`, `bg`, `cs`, `de`, `el`, `en`, `es`, `fr`, `hu`, `id_ID`, `it`, `ja`, `lt`, `nl`, `pl`, `pt`, `pt_BR`, `ro`, `ru`, `sr`, `tr`, `zh_CN`, `zh_TW`

Example:

`!config lang ar`

### ログチャンネル

ボットアクションが記録されるチャンネル。

Type: `Channel`

Default: `null`

Reset to default: `!config logChannel default`

Examples:

`!config logChannel #channel`

### アップデート情報を手に入れる

InviteManager に関する開発の最新情報を受け取ることができるようにします。

Type: `Boolean`

Default: `true`

Reset to default: `!config getUpdates default`

Enable:

`!config getUpdates true`

Disable:

`!config getUpdates false`

### コマンドチャンネル

ボットがコマンドに反応するチャンネル。

Type: `Channel[]`

Default: \`\`

Reset to default: `!config channels default`

### 無視されるチャンネル

ボットがコマンドを無視するチャンネル。

Type: `Channel[]`

Default: \`\`

Reset to default: `!config ignoredChannels default`

### Join Roles

Roles that are assigned to all members when joining.

Type: `Role[]`

Default: \`\`

Reset to default: `!config joinRoles default`

### メッセージ

サーバーに参加したときに送信されるメッセージ。

Type: `String`

Default: `{memberMention} **joined**; Invited by **{inviterName}** (**{numInvites}** invites)`

Reset to default: `!config joinMessage default`

### メッセージチャンネル

参加時のメッセージが送信されるチャンネル。

Type: `Channel`

Default: `null`

Reset to default: `!config joinMessageChannel default`

Examples:

`!config joinMessageChannel #general`

`!config joinMessageChannel #joins`

### メッセージ

サーバーを離れたときに送信されるメッセージ。

Type: `String`

Default: `{memberName} **left**; Invited by **{inviterName}**`

Reset to default: `!config leaveMessage default`

Examples:

`!config leaveMessage`

`!config leaveMessage`

### メッセージチャンネル

退出メッセージが送信されるチャンネル。

Type: `Channel`

Default: `null`

Reset to default: `!config leaveMessageChannel default`

Examples:

`!config leaveMessageChannel #general`

`!config leaveMessageChannel #leaves`

### スタイル

リーダーボードの表示スタイル。

Type: `Enum<LeaderboardStyle>`

Default: `normal`

Reset to default: `!config leaderboardStyle default`

Possible values: `normal`, `table`, `mentions`

Example:

`!config leaderboardStyle normal`

### 退出メンバーを隠す

リーダーボードからサーバーを離れたメンバーを非表示にします。

Type: `Boolean`

Default: `true`

Reset to default: `!config hideLeftMembersFromLeaderboard default`

Enable:

`!config hideLeftMembersFromLeaderboard true`

Disable:

`!config hideLeftMembersFromLeaderboard false`

### 自動減算

自動的に偽の招待を差し引きます。

Type: `Boolean`

Default: `true`

Reset to default: `!config autoSubtractFakes default`

Enable:

`!config autoSubtractFakes true`

Disable:

`!config autoSubtractFakes false`

### 自動減算

招待ユーザーが退出したときに招待者から招待状を自動的に削除します。

Type: `Boolean`

Default: `true`

Reset to default: `!config autoSubtractLeaves default`

Enable:

`!config autoSubtractLeaves true`

Disable:

`!config autoSubtractLeaves false`

### 自動減算しきい値

招待を数えるためにユーザーがサーバーに留まる必要がある時間（秒）。

Type: `Number`

Default: `600`

Reset to default: `!config autoSubtractLeaveThreshold default`

Examples:

`!config autoSubtractLeaveThreshold 60`

`!config autoSubtractLeaveThreshold 3600`

### 割り当てスタイル

ランクはユーザーにどのように与えられますか。

Type: `Enum<RankAssignmentStyle>`

Default: `all`

Reset to default: `!config rankAssignmentStyle default`

Possible values: `all`, `highest`, `onlyAdd`

Example:

`!config rankAssignmentStyle all`

### お知らせチャンネル

ユーザーが新しいランクを獲得したときにアナウンスするチャンネル。

Type: `Channel`

Default: `null`

Reset to default: `!config rankAnnouncementChannel default`

Examples:

`!config rankAnnouncementChannel`

`!config rankAnnouncementChannel`

### お知らせメッセージ

ユーザーが新しいランクを受け取ったときに送信されるメッセージ。

Type: `String`

Default: `Congratulations, **{memberMention}** has reached the **{rankName}** rank!`

Reset to default: `!config rankAnnouncementMessage default`

Examples:

`!config rankAnnouncementMessage`

`!config rankAnnouncementMessage`

### 有効

キャプチャ検証が有効かどうか。

Type: `Boolean`

Default: `false`

Reset to default: `!config captchaVerificationOnJoin default`

Enable:

`!config captchaVerificationOnJoin true`

Disable:

`!config captchaVerificationOnJoin false`

### 参加メッセージ

ユーザーがサーバーに参加してキャプチャに入るように指示した後に表示されるメッセージ。

Type: `String`

Default: `Welcome to the server **{serverName}**! For extra protection, new members are required to enter a captcha.`

Reset to default: `!config captchaVerificationWelcomeMessage default`

Examples:

`!config captchaVerificationWelcomeMessage Welcome, please enter the captcha below!`

### 成功メッセージ

ユーザーが正常に確認した後にユーザーに送信されるウェルカムメッセージ。

Type: `String`

Default: `You have successfully entered the captcha. Welcome to the server!`

Reset to default: `!config captchaVerificationSuccessMessage default`

Examples:

`!config captchaVerificationSuccessMessage Thanks for entering the captcha, enjoy our server!`

### 失敗メッセージ

ユーザーが無効なキャプチャを入力した場合にメッセージがユーザーに送信されます。

Type: `String`

Default: `You did not enter the captha right within the specified time.We're sorry, but we have to kick you from the server. Feel free to join again.`

Reset to default: `!config captchaVerificationFailedMessage default`

Examples:

`!config captchaVerificationFailedMessage Looks like you are not human :(. You can join again and try again later if this was a mistake!`

### 認証タイムアウト

キャプチャが正常に入力されなければならない時間。

Type: `Number`

Default: `180`

Reset to default: `!config captchaVerificationTimeout default`

Examples:

`!config captchaVerificationTimeout 60`

`!config captchaVerificationTimeout 600`

### ログが有効化されました

検証の試行がログに記録されるかどうか。

Type: `Boolean`

Default: `true`

Reset to default: `!config captchaVerificationLogEnabled default`

Enable:

`!config captchaVerificationLogEnabled true`

Disable:

`!config captchaVerificationLogEnabled false`

### 有効

Automatically moderate messages \(specific rules can also be turned on or off, this has to be ON for ANY rule to work\).

Type: `Boolean`

Default: `false`

Reset to default: `!config autoModEnabled default`

Enable:

`!config autoModEnabled true`

Disable:

`!config autoModEnabled false`

### 管理チャンネル

The list of moderated channels \(this acts as a whitelist, leave empty to moderate all channels, or use `autoModIgnoredChannels` to ignore certain channels\).

Type: `Channel[]`

Default: \`\`

Reset to default: `!config autoModModeratedChannels default`

Examples:

`!config autoModModeratedChannels #general`

`!config autoModModeratedChannels #support,#help`

### 管理役職

The list of roles that are moderated \(this acts as a whitelist, leave empty to moderate all roles, or use `autoModIgnoredRoles` to ignore certain roles\).

Type: `Role[]`

Default: \`\`

Reset to default: `!config autoModModeratedRoles default`

Examples:

`!config autoModModeratedRoles @NewMembers`

`!config autoModModeratedRoles @Newbies,@Starters`

### 無視されるチャンネル

Channels that are ignored while automatically moderating.

Type: `Channel[]`

Default: \`\`

Reset to default: `!config autoModIgnoredChannels default`

Examples:

`!config autoModIgnoredChannels #general`

`!config autoModIgnoredChannels #off-topic,#nsfw`

### 無視される役職

Any members with these roles will not automatically be moderated.

Type: `Role[]`

Default: \`\`

Reset to default: `!config autoModIgnoredRoles default`

Examples:

`!config autoModIgnoredRoles @TrustedMembers`

`!config autoModIgnoredRoles @Moderators,@Staff`

### ミュート役職

The role that is given to people who are muted. Make sure this role is denied the "Send Message" permission.

Type: `Role`

Default: `null`

Reset to default: `!config mutedRole default`

Examples:

`!config mutedRole @muted`

### 古いメンバーには無効

Disabled auto moderation for members that have been in your server for a long time.

Type: `Boolean`

Default: `false`

Reset to default: `!config autoModDisabledForOldMembers default`

Enable:

`!config autoModDisabledForOldMembers true`

Disable:

`!config autoModDisabledForOldMembers false`

### 古いメンバーのしきい値

The amount of time a member has to be in your server to be considered 'old'.

Type: `Number`

Default: `604800`

Reset to default: `!config autoModDisabledForOldMembersThreshold default`

Examples:

`!config autoModDisabledForOldMembersThreshold 604800` \(1 week\)\`\`

`!config autoModDisabledForOldMembersThreshold 2419200` \(1 month\)\`\`

### ログが有効化されました

Log any moderation actions that the bot makes.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModLogEnabled default`

Enable:

`!config autoModLogEnabled true`

Disable:

`!config autoModLogEnabled false`

### MOD ログチャンネル

モデレーションログが記録されるチャンネル。

Type: `Channel`

Default: `null`

Reset to default: `!config modLogChannel default`

Examples:

`!config modLogChannel #channel`

`!config modLogChannel #logs`

### BOT のメッセージを削除

Automatically delete the bots own messages \(keeps your chat clean\).

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModDeleteBotMessage default`

Enable:

`!config autoModDeleteBotMessage true`

Disable:

`!config autoModDeleteBotMessage false`

### ボットメッセージタイムアウトの削除

The timeout after which bot messages are deleted.

Type: `Number`

Default: `5`

Reset to default: `!config autoModDeleteBotMessageTimeoutInSeconds default`

Examples:

`!config autoModDeleteBotMessageTimeoutInSeconds 5`

`!config autoModDeleteBotMessageTimeoutInSeconds 10`

### BAN メッセージを削除

「禁止」プッシュメッセージを自動的に削除するかどうか。

Type: `Boolean`

Default: `true`

Reset to default: `!config modPunishmentBanDeleteMessage default`

Enable:

`!config modPunishmentBanDeleteMessage true`

Disable:

`!config modPunishmentBanDeleteMessage false`

### キックメッセージを削除

「キック」プッシュメッセージが自動的に削除されるかどうか。

Type: `Boolean`

Default: `true`

Reset to default: `!config modPunishmentKickDeleteMessage default`

Enable:

`!config modPunishmentKickDeleteMessage true`

Disable:

`!config modPunishmentKickDeleteMessage false`

### ソフト BAN メッセージを削除

「Softban」プッシュメッセージが自動的に削除されるかどうか。

Type: `Boolean`

Default: `true`

Reset to default: `!config modPunishmentSoftbanDeleteMessage default`

Enable:

`!config modPunishmentSoftbanDeleteMessage true`

Disable:

`!config modPunishmentSoftbanDeleteMessage false`

### 警告メッセージを削除

「警告」プッシュメッセージを自動的に削除するかどうか。

Type: `Boolean`

Default: `true`

Reset to default: `!config modPunishmentWarnDeleteMessage default`

Enable:

`!config modPunishmentWarnDeleteMessage true`

Disable:

`!config modPunishmentWarnDeleteMessage false`

### ミュートメッセージを削除

「ミュート」プッシュメッセージが自動的に削除されるかどうか。

Type: `Boolean`

Default: `true`

Reset to default: `!config modPunishmentMuteDeleteMessage default`

Enable:

`!config modPunishmentMuteDeleteMessage true`

Disable:

`!config modPunishmentMuteDeleteMessage false`

### 有効

Automatically scan messages for discord invite links and remove them.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModInvitesEnabled default`

Enable:

`!config autoModInvitesEnabled true`

Disable:

`!config autoModInvitesEnabled false`

### 有効

Automatically remove messages containing links \(you can set a whitelist and blacklist\).

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModLinksEnabled default`

Enable:

`!config autoModLinksEnabled true`

Disable:

`!config autoModLinksEnabled false`

### ホワイトリスト

A list of links that users are allowed to post.

Type: `String[]`

Default: \`\`

Reset to default: `!config autoModLinksWhitelist default`

Examples:

`!config autoModLinksWhitelist discordbots.org`

`!config autoModLinksWhitelist youtube.com,twitch.com`

### ブラックリスト

Blacklist certain links which users won't be able to post.

Type: `String[]`

Default: \`\`

Reset to default: `!config autoModLinksBlacklist default`

Examples:

`!config autoModLinksBlacklist google.com`

`!config autoModLinksBlacklist twitch.com,youtube.com`

### リダイレクトをフォローする

Enable this to resolve redirects for links.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModLinksFollowRedirects default`

Enable:

`!config autoModLinksFollowRedirects true`

Disable:

`!config autoModLinksFollowRedirects false`

### 有効

ブラックリストに載っている単語を自動対応するかどうか

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModWordsEnabled default`

Enable:

`!config autoModWordsEnabled true`

Disable:

`!config autoModWordsEnabled false`

### ブラックリスト

禁止されている単語のリスト。

Type: `String[]`

Default: \`\`

Reset to default: `!config autoModWordsBlacklist default`

Examples:

`!config autoModWordsBlacklist gay`

`!config autoModWordsBlacklist stupid,fuck`

### 有効

自動的に 適度な メッセージ とともに 多くのキャップ

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModAllCapsEnabled default`

Enable:

`!config autoModAllCapsEnabled true`

Disable:

`!config autoModAllCapsEnabled false`

### 最小文字

あの ミニマム 量 の キャラクター に メッセージ へ なる 検討する ために 適度な \(セッティング へ '3' しましょう 無視する 'オーケー'\).

Type: `Number`

Default: `10`

Reset to default: `!config autoModAllCapsMinCharacters default`

Examples:

`!config autoModAllCapsMinCharacters 5`

`!config autoModAllCapsMinCharacters 15`

### 煽りのパーセント

あの 割合 の キャラクター の あの メッセージ それ 持ってる へ なる クリック数 ために あの ルール へ 引き金.

Type: `Number`

Default: `70`

Reset to default: `!config autoModAllCapsPercentageCaps default`

Examples:

`!config autoModAllCapsPercentageCaps 50`

`!config autoModAllCapsPercentageCaps 90`

### 有効化

Automatically moderate duplicate messages \(copy-paste spam\).

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModDuplicateTextEnabled default`

Enable:

`!config autoModDuplicateTextEnabled true`

Disable:

`!config autoModDuplicateTextEnabled false`

### 秒単位のタイムフレーム

The timeframe whithin which messages will be considered duplicates.

Type: `Number`

Default: `60`

Reset to default: `!config autoModDuplicateTextTimeframeInSeconds default`

Examples:

`!config autoModDuplicateTextTimeframeInSeconds 5`

`!config autoModDuplicateTextTimeframeInSeconds 20`

### 有効

Automatically moderate users sending a lot of messages in a short time.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModQuickMessagesEnabled default`

Enable:

`!config autoModQuickMessagesEnabled true`

Disable:

`!config autoModQuickMessagesEnabled false`

### \#のメッセージ数

The number of messages that have to be sent within the timeframe to trigger the rule.

Type: `Number`

Default: `5`

Reset to default: `!config autoModQuickMessagesNumberOfMessages default`

Examples:

`!config autoModQuickMessagesNumberOfMessages 5`

`!config autoModQuickMessagesNumberOfMessages 10`

### 秒単位のタイムフレーム

The timeframe within which a user is allowed to send a maximum amount of messages.

Type: `Number`

Default: `3`

Reset to default: `!config autoModQuickMessagesTimeframeInSeconds default`

Examples:

`!config autoModQuickMessagesTimeframeInSeconds 2`

`!config autoModQuickMessagesTimeframeInSeconds 10`

### 有効

Automatically moderate messages that mention an excessive amount of users.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModMentionUsersEnabled default`

Enable:

`!config autoModMentionUsersEnabled true`

Disable:

`!config autoModMentionUsersEnabled false`

### メンション

The maximum amount of users a member can mention in a message.

Type: `Number`

Default: `5`

Reset to default: `!config autoModMentionUsersMaxNumberOfMentions default`

Examples:

`!config autoModMentionUsersMaxNumberOfMentions 2`

`!config autoModMentionUsersMaxNumberOfMentions 5`

### 有効

Automatically moderate messages that mention an excessive amount of roles.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModMentionRolesEnabled default`

Enable:

`!config autoModMentionRolesEnabled true`

Disable:

`!config autoModMentionRolesEnabled false`

### メンション

The maximum amount of roles a member can mention in a message.

Type: `Number`

Default: `3`

Reset to default: `!config autoModMentionRolesMaxNumberOfMentions default`

Examples:

`!config autoModMentionRolesMaxNumberOfMentions 2`

`!config autoModMentionRolesMaxNumberOfMentions 5`

### 有効

Automatically moderate messages with an excessive amount of emojis.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModEmojisEnabled default`

Enable:

`!config autoModEmojisEnabled true`

Disable:

`!config autoModEmojisEnabled false`

### 絵文字の最大数

The maximum amount of emojis a message is allowed to have before trigger the rule.

Type: `Number`

Default: `5`

Reset to default: `!config autoModEmojisMaxNumberOfEmojis default`

Examples:

`!config autoModEmojisMaxNumberOfEmojis 5`

`!config autoModEmojisMaxNumberOfEmojis 10`

### Enabled

Automatically give members nicknames if they try to hoist \(use special characters to appear at the top of the user list\).

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModHoistEnabled default`

Enable:

`!config autoModHoistEnabled true`

Disable:

`!config autoModHoistEnabled false`

