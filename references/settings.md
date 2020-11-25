# Settings

There are many config options that can be set. You don't have to set all of them. If you just added the bot, just run `!setup`, which will guide you through the most important ones.

## Overview

### General

| Setting | Description |
| :--- | :--- |
| [Prefix]() | The prefix used to trigger bot commands. |
| [Language]() | The language of the bot |
| [Log Channel]() | The channel where bot actions are logged. |
| [Get Updates]() | Enable to receive development updates about InviteLogger. |
| [Command channels]() | The channels in which the bot will react to commands. |
| [Ignored channels]() | The channels in which the bot will ignore commands. |

### Invites

#### General

| Setting | Description |
| :--- | :--- |
| [Join Roles]() | Roles that are assigned to all members when joining. |

#### Joins

| Setting | Description |
| :--- | :--- |
| [Message]() | The message sent when someone joins the server. |
| [Message Channel]() | The channel that the message on join is sent to. |

#### Leaves

| Setting | Description |
| :--- | :--- |
| [Message]() | The message sent when someone leaves the server. |
| [Message Channel]() | The channel that the leave message is sent to. |
| [Auto Subtract]() | Automatically remove invites from the inviter when the invited user leaves. |
| [Auto Subtract Threshold]() | The time in seconds for which a user has to stay in the server for the invite to count. |

#### Leaderboard

| Setting | Description |
| :--- | :--- |
| [Style]() | The display style of the leaderboard. |
| [Hide left members]() | Hide members that left the server from the leaderboard. |

#### Fakes

| Setting | Description |
| :--- | :--- |
| [Auto Subtract]() | Automatically subtract fake invites. |

#### Ranks

| Setting | Description |
| :--- | :--- |
| [Assignment Style]() | How ranks are rewarded to users. |
| [Announcement Channel]() | The channel where users receiving a new rank are announced. |
| [Announcement Message]() | The message that is sent when a user receives a new rank. |

### Moderation

#### Captcha

| Setting | Description |
| :--- | :--- |
| [Enabled]() | Whether or not captcha verification is enabled. |
| [Welcome Message]() | The message a user will get after joining a server and instructing them to enter the captcha. |
| [Success Message]() | The welcome message that will be sent to the user after he successfully verifies. |
| [Failed Message]() | The message sent to the user if he enters an invalid captcha. |
| [Verification Timeout]() | The time within which the captcha has to be entered successfully. |
| [Log Enabled]() | Whether or not verification attempts will be logged. |

#### General

| Setting | Description |
| :--- | :--- |
| [Enabled]() | Automatically moderate messages \(specific rules can also be turned on or off, this has to be ON for ANY rule to work\). |
| [Moderated Channels]() | The list of moderated channels \(this acts as a whitelist, leave empty to moderate all channels, or use `autoModIgnoredChannels` to ignore certain channels\). |
| [Moderated Roles]() | The list of roles that are moderated \(this acts as a whitelist, leave empty to moderate all roles, or use `autoModIgnoredRoles` to ignore certain roles\). |
| [Ignored Channels]() | Channels that are ignored while automatically moderating. |
| [Ignored Roles]() | Any members with these roles will not automatically be moderated. |
| [Muted Role]() | The role that is given to people who are muted. Make sure this role is denied the "Send Message" permission. |
| [Disabled for Old Members]() | Disabled auto moderation for members that have been in your server for a long time. |
| [Old Members Threshold]() | The amount of time a member has to be in your server to be considered 'old'. |

#### Logging

| Setting | Description |
| :--- | :--- |
| [Log Enabled]() | Log any moderation actions that the bot makes. |
| [Mod Log Channel]() | The channel where moderation logs will be posted in. |
| [Delete Bot Messages]() | Automatically delete the bots own messages \(keeps your chat clean\). |
| [Delete Bot Message Timeout]() | The timeout after which bot messages are deleted. |
| [Delete Ban Messages]() | Whether or not "Ban" pushment messages will be deleted automatically. |
| [Delete Kick Messages]() | Whether or not "Kick" pushment messages will be deleted automatically. |
| [Delete Softban Messages]() | Whether or not "Softban" pushment messages will be deleted automatically. |
| [Delete Warn Messages]() | Whether or not "Warn" pushment messages will be deleted automatically. |
| [Delete Mute Messages]() | Whether or not "Mute" pushment messages will be deleted automatically. |

#### Invites

| Setting | Description |
| :--- | :--- |
| [Enabled]() | Automatically scan messages for discord invite links and remove them. |

#### Links

| Setting | Description |
| :--- | :--- |
| [Enabled]() | Automatically remove messages containing links \(you can set a whitelist and blacklist\). |
| [Whitelist]() | A list of links that users are allowed to post. |
| [Blacklist]() | Blacklist certain links which users won't be able to post. |
| [Follow Redirects]() | Enable this to resolve redirects for links. |

#### Banned Words

| Setting | Description |
| :--- | :--- |
| [Enabled]() | Whether or not blacklisted words will be automoderated. |
| [Blacklist]() | A list of words that are banned. |

#### Caps

| Setting | Description |
| :--- | :--- |
| [Enabled]() | Automatically moderate messages with A LOT OF CAPS. |
| [Min. Characters]() | The minimum amount of characters in a message to be considered for moderating \(setting to '3' would ignore 'OK'\). |
| [Percentage CAPs]() | The percentage of characters of the message that have to be CAPs for the rule to trigger. |

#### Duplicate Messages

| Setting | Description |
| :--- | :--- |
| [Enabled]() | Automatically moderate duplicate messages \(copy-paste spam\). |
| [Timeframe in Seconds]() | The timeframe whithin which messages will be considered duplicates. |

#### Spam

| Setting | Description |
| :--- | :--- |
| [Enabled]() | Automatically moderate users sending a lot of messages in a short time. |
| [\# of Messages]() | The number of messages that have to be sent within the timeframe to trigger the rule. |
| [Timeframe in Seconds]() | The timeframe within which a user is allowed to send a maximum amount of messages. |

#### Mentions

| Setting | Description |
| :--- | :--- |
| [Enabled]() | Automatically moderate messages that mention an excessive amount of users. |
| [Max \# of Mentions]() | The maximum amount of users a member can mention in a message. |
| [Enabled]() | Automatically moderate messages that mention an excessive amount of roles. |
| [Max \# of Mentions]() | The maximum amount of roles a member can mention in a message. |

#### Emojis

| Setting | Description |
| :--- | :--- |
| [Enabled]() | Automatically moderate messages with an excessive amount of emojis. |
| [Max \# of Emojis]() | The maximum amount of emojis a message is allowed to have before trigger the rule. |
| [Enabled]() | Automatically give members nicknames if they try to hoist \(use special characters to appear at the top of the user list\). |

## Prefix

The prefix used to trigger bot commands.

Type: `String`

Default: `!`

Reset to default: `!config prefix default`

Examples:

`!config prefix +`

`!config prefix >`

## Language

The language of the bot

Type: `Enum<Lang>`

Default: `en`

Reset to default: `!config lang default`

Possible values: `ar`, `bg`, `cs`, `de`, `el`, `en`, `es`, `fr`, `hu`, `id_ID`, `it`, `ja`, `lt`, `nl`, `pl`, `pt`, `pt_BR`, `ro`, `ru`, `sr`, `tr`, `zh_CN`, `zh_TW`

Example:

`!config lang ar`

## Log Channel

The channel where bot actions are logged.

Type: `Channel`

Default: `null`

Reset to default: `!config logChannel default`

Examples:

`!config logChannel #channel`

## Get Updates

Enable to receive development updates about InviteLogger.

Type: `Boolean`

Default: `true`

Reset to default: `!config getUpdates default`

Enable:

`!config getUpdates true`

Disable:

`!config getUpdates false`

## Command channels

The channels in which the bot will react to commands.

Type: `Channel[]`

Default: \`\`

Reset to default: `!config channels default`

## Ignored channels

The channels in which the bot will ignore commands.

Type: `Channel[]`

Default: \`\`

Reset to default: `!config ignoredChannels default`

## Join Roles

Roles that are assigned to all members when joining.

Type: `Role[]`

Default: \`\`

Reset to default: `!config joinRoles default`

## Message

The message sent when someone joins the server.

Type: `String`

Default: `{memberMention} **joined**; Invited by **{inviterName}** (**{numInvites}** invites)`

Reset to default: `!config joinMessage default`

## Message Channel

The channel that the message on join is sent to.

Type: `Channel`

Default: `null`

Reset to default: `!config joinMessageChannel default`

Examples:

`!config joinMessageChannel #general`

`!config joinMessageChannel #joins`

## Message

The message sent when someone leaves the server.

Type: `String`

Default: `{memberName} **left**; Invited by **{inviterName}**`

Reset to default: `!config leaveMessage default`

Examples:

`!config leaveMessage`

`!config leaveMessage`

## Message Channel

The channel that the leave message is sent to.

Type: `Channel`

Default: `null`

Reset to default: `!config leaveMessageChannel default`

Examples:

`!config leaveMessageChannel #general`

`!config leaveMessageChannel #leaves`

## Style

The display style of the leaderboard.

Type: `Enum<LeaderboardStyle>`

Default: `normal`

Reset to default: `!config leaderboardStyle default`

Possible values: `normal`, `table`, `mentions`

Example:

`!config leaderboardStyle normal`

## Hide left members

Hide members that left the server from the leaderboard.

Type: `Boolean`

Default: `true`

Reset to default: `!config hideLeftMembersFromLeaderboard default`

Enable:

`!config hideLeftMembersFromLeaderboard true`

Disable:

`!config hideLeftMembersFromLeaderboard false`

## Auto Subtract

Automatically subtract fake invites.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoSubtractFakes default`

Enable:

`!config autoSubtractFakes true`

Disable:

`!config autoSubtractFakes false`

## Auto Subtract

Automatically remove invites from the inviter when the invited user leaves.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoSubtractLeaves default`

Enable:

`!config autoSubtractLeaves true`

Disable:

`!config autoSubtractLeaves false`

## Auto Subtract Threshold

The time in seconds for which a user has to stay in the server for the invite to count.

Type: `Number`

Default: `600`

Reset to default: `!config autoSubtractLeaveThreshold default`

Examples:

`!config autoSubtractLeaveThreshold 60`

`!config autoSubtractLeaveThreshold 3600`

## Assignment Style

How ranks are rewarded to users.

Type: `Enum<RankAssignmentStyle>`

Default: `all`

Reset to default: `!config rankAssignmentStyle default`

Possible values: `all`, `highest`, `onlyAdd`

Example:

`!config rankAssignmentStyle all`

## Announcement Channel

The channel where users receiving a new rank are announced.

Type: `Channel`

Default: `null`

Reset to default: `!config rankAnnouncementChannel default`

Examples:

`!config rankAnnouncementChannel`

`!config rankAnnouncementChannel`

## Announcement Message

The message that is sent when a user receives a new rank.

Type: `String`

Default: `Congratulations, **{memberMention}** has reached the **{rankName}** rank!`

Reset to default: `!config rankAnnouncementMessage default`

Examples:

`!config rankAnnouncementMessage`

`!config rankAnnouncementMessage`

## Enabled

Whether or not captcha verification is enabled.

Type: `Boolean`

Default: `false`

Reset to default: `!config captchaVerificationOnJoin default`

Enable:

`!config captchaVerificationOnJoin true`

Disable:

`!config captchaVerificationOnJoin false`

## Welcome Message

The message a user will get after joining a server and instructing them to enter the captcha.

Type: `String`

Default: `Welcome to the server **{serverName}**! For extra protection, new members are required to enter a captcha.`

Reset to default: `!config captchaVerificationWelcomeMessage default`

Examples:

`!config captchaVerificationWelcomeMessage Welcome, please enter the captcha below!`

## Success Message

The welcome message that will be sent to the user after he successfully verifies.

Type: `String`

Default: `You have successfully entered the captcha. Welcome to the server!`

Reset to default: `!config captchaVerificationSuccessMessage default`

Examples:

`!config captchaVerificationSuccessMessage Thanks for entering the captcha, enjoy our server!`

## Failed Message

The message sent to the user if he enters an invalid captcha.

Type: `String`

Default: `You did not enter the captha right within the specified time.We're sorry, but we have to kick you from the server. Feel free to join again.`

Reset to default: `!config captchaVerificationFailedMessage default`

Examples:

`!config captchaVerificationFailedMessage Looks like you are not human :(. You can join again and try again later if this was a mistake!`

## Verification Timeout

The time within which the captcha has to be entered successfully.

Type: `Number`

Default: `180`

Reset to default: `!config captchaVerificationTimeout default`

Examples:

`!config captchaVerificationTimeout 60`

`!config captchaVerificationTimeout 600`

## Log Enabled

Whether or not verification attempts will be logged.

Type: `Boolean`

Default: `true`

Reset to default: `!config captchaVerificationLogEnabled default`

Enable:

`!config captchaVerificationLogEnabled true`

Disable:

`!config captchaVerificationLogEnabled false`

## Enabled

Automatically moderate messages \(specific rules can also be turned on or off, this has to be ON for ANY rule to work\).

Type: `Boolean`

Default: `false`

Reset to default: `!config autoModEnabled default`

Enable:

`!config autoModEnabled true`

Disable:

`!config autoModEnabled false`

## Moderated Channels

The list of moderated channels \(this acts as a whitelist, leave empty to moderate all channels, or use `autoModIgnoredChannels` to ignore certain channels\).

Type: `Channel[]`

Default: \`\`

Reset to default: `!config autoModModeratedChannels default`

Examples:

`!config autoModModeratedChannels #general`

`!config autoModModeratedChannels #support,#help`

## Moderated Roles

The list of roles that are moderated \(this acts as a whitelist, leave empty to moderate all roles, or use `autoModIgnoredRoles` to ignore certain roles\).

Type: `Role[]`

Default: \`\`

Reset to default: `!config autoModModeratedRoles default`

Examples:

`!config autoModModeratedRoles @NewMembers`

`!config autoModModeratedRoles @Newbies,@Starters`

## Ignored Channels

Channels that are ignored while automatically moderating.

Type: `Channel[]`

Default: \`\`

Reset to default: `!config autoModIgnoredChannels default`

Examples:

`!config autoModIgnoredChannels #general`

`!config autoModIgnoredChannels #off-topic,#nsfw`

## Ignored Roles

Any members with these roles will not automatically be moderated.

Type: `Role[]`

Default: \`\`

Reset to default: `!config autoModIgnoredRoles default`

Examples:

`!config autoModIgnoredRoles @TrustedMembers`

`!config autoModIgnoredRoles @Moderators,@Staff`

## Muted Role

The role that is given to people who are muted. Make sure this role is denied the "Send Message" permission.

Type: `Role`

Default: `null`

Reset to default: `!config mutedRole default`

Examples:

`!config mutedRole @muted`

## Disabled for Old Members

Disabled auto moderation for members that have been in your server for a long time.

Type: `Boolean`

Default: `false`

Reset to default: `!config autoModDisabledForOldMembers default`

Enable:

`!config autoModDisabledForOldMembers true`

Disable:

`!config autoModDisabledForOldMembers false`

## Old Members Threshold

The amount of time a member has to be in your server to be considered 'old'.

Type: `Number`

Default: `604800`

Reset to default: `!config autoModDisabledForOldMembersThreshold default`

Examples:

`!config autoModDisabledForOldMembersThreshold 604800` \(1 week\)\`\`

`!config autoModDisabledForOldMembersThreshold 2419200` \(1 month\)\`\`

## Log Enabled

Log any moderation actions that the bot makes.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModLogEnabled default`

Enable:

`!config autoModLogEnabled true`

Disable:

`!config autoModLogEnabled false`

## Mod Log Channel

The channel where moderation logs will be posted in.

Type: `Channel`

Default: `null`

Reset to default: `!config modLogChannel default`

Examples:

`!config modLogChannel #channel`

`!config modLogChannel #logs`

## Delete Bot Messages

Automatically delete the bots own messages \(keeps your chat clean\).

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModDeleteBotMessage default`

Enable:

`!config autoModDeleteBotMessage true`

Disable:

`!config autoModDeleteBotMessage false`

## Delete Bot Message Timeout

The timeout after which bot messages are deleted.

Type: `Number`

Default: `5`

Reset to default: `!config autoModDeleteBotMessageTimeoutInSeconds default`

Examples:

`!config autoModDeleteBotMessageTimeoutInSeconds 5`

`!config autoModDeleteBotMessageTimeoutInSeconds 10`

## Delete Ban Messages

Whether or not "Ban" pushment messages will be deleted automatically.

Type: `Boolean`

Default: `true`

Reset to default: `!config modPunishmentBanDeleteMessage default`

Enable:

`!config modPunishmentBanDeleteMessage true`

Disable:

`!config modPunishmentBanDeleteMessage false`

## Delete Kick Messages

Whether or not "Kick" pushment messages will be deleted automatically.

Type: `Boolean`

Default: `true`

Reset to default: `!config modPunishmentKickDeleteMessage default`

Enable:

`!config modPunishmentKickDeleteMessage true`

Disable:

`!config modPunishmentKickDeleteMessage false`

## Delete Softban Messages

Whether or not "Softban" pushment messages will be deleted automatically.

Type: `Boolean`

Default: `true`

Reset to default: `!config modPunishmentSoftbanDeleteMessage default`

Enable:

`!config modPunishmentSoftbanDeleteMessage true`

Disable:

`!config modPunishmentSoftbanDeleteMessage false`

## Delete Warn Messages

Whether or not "Warn" pushment messages will be deleted automatically.

Type: `Boolean`

Default: `true`

Reset to default: `!config modPunishmentWarnDeleteMessage default`

Enable:

`!config modPunishmentWarnDeleteMessage true`

Disable:

`!config modPunishmentWarnDeleteMessage false`

## Delete Mute Messages

Whether or not "Mute" pushment messages will be deleted automatically.

Type: `Boolean`

Default: `true`

Reset to default: `!config modPunishmentMuteDeleteMessage default`

Enable:

`!config modPunishmentMuteDeleteMessage true`

Disable:

`!config modPunishmentMuteDeleteMessage false`

## Enabled

Automatically scan messages for discord invite links and remove them.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModInvitesEnabled default`

Enable:

`!config autoModInvitesEnabled true`

Disable:

`!config autoModInvitesEnabled false`

## Enabled

Automatically remove messages containing links \(you can set a whitelist and blacklist\).

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModLinksEnabled default`

Enable:

`!config autoModLinksEnabled true`

Disable:

`!config autoModLinksEnabled false`

## Whitelist

A list of links that users are allowed to post.

Type: `String[]`

Default: \`\`

Reset to default: `!config autoModLinksWhitelist default`

Examples:

`!config autoModLinksWhitelist discordbots.org`

`!config autoModLinksWhitelist youtube.com,twitch.com`

## Blacklist

Blacklist certain links which users won't be able to post.

Type: `String[]`

Default: \`\`

Reset to default: `!config autoModLinksBlacklist default`

Examples:

`!config autoModLinksBlacklist google.com`

`!config autoModLinksBlacklist twitch.com,youtube.com`

## Follow Redirects

Enable this to resolve redirects for links.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModLinksFollowRedirects default`

Enable:

`!config autoModLinksFollowRedirects true`

Disable:

`!config autoModLinksFollowRedirects false`

## Enabled

Whether or not blacklisted words will be automoderated.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModWordsEnabled default`

Enable:

`!config autoModWordsEnabled true`

Disable:

`!config autoModWordsEnabled false`

## Blacklist

A list of words that are banned.

Type: `String[]`

Default: \`\`

Reset to default: `!config autoModWordsBlacklist default`

Examples:

`!config autoModWordsBlacklist gay`

`!config autoModWordsBlacklist stupid,fuck`

## Enabled

Automatically moderate messages with A LOT OF CAPS.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModAllCapsEnabled default`

Enable:

`!config autoModAllCapsEnabled true`

Disable:

`!config autoModAllCapsEnabled false`

## Min. Characters

The minimum amount of characters in a message to be considered for moderating \(setting to '3' would ignore 'OK'\).

Type: `Number`

Default: `10`

Reset to default: `!config autoModAllCapsMinCharacters default`

Examples:

`!config autoModAllCapsMinCharacters 5`

`!config autoModAllCapsMinCharacters 15`

## Percentage CAPs

The percentage of characters of the message that have to be CAPs for the rule to trigger.

Type: `Number`

Default: `70`

Reset to default: `!config autoModAllCapsPercentageCaps default`

Examples:

`!config autoModAllCapsPercentageCaps 50`

`!config autoModAllCapsPercentageCaps 90`

## Enabled

Automatically moderate duplicate messages \(copy-paste spam\).

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModDuplicateTextEnabled default`

Enable:

`!config autoModDuplicateTextEnabled true`

Disable:

`!config autoModDuplicateTextEnabled false`

## Timeframe in Seconds

The timeframe whithin which messages will be considered duplicates.

Type: `Number`

Default: `60`

Reset to default: `!config autoModDuplicateTextTimeframeInSeconds default`

Examples:

`!config autoModDuplicateTextTimeframeInSeconds 5`

`!config autoModDuplicateTextTimeframeInSeconds 20`

## Enabled

Automatically moderate users sending a lot of messages in a short time.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModQuickMessagesEnabled default`

Enable:

`!config autoModQuickMessagesEnabled true`

Disable:

`!config autoModQuickMessagesEnabled false`

## \# of Messages

The number of messages that have to be sent within the timeframe to trigger the rule.

Type: `Number`

Default: `5`

Reset to default: `!config autoModQuickMessagesNumberOfMessages default`

Examples:

`!config autoModQuickMessagesNumberOfMessages 5`

`!config autoModQuickMessagesNumberOfMessages 10`

## Timeframe in Seconds

The timeframe within which a user is allowed to send a maximum amount of messages.

Type: `Number`

Default: `3`

Reset to default: `!config autoModQuickMessagesTimeframeInSeconds default`

Examples:

`!config autoModQuickMessagesTimeframeInSeconds 2`

`!config autoModQuickMessagesTimeframeInSeconds 10`

## Enabled

Automatically moderate messages that mention an excessive amount of users.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModMentionUsersEnabled default`

Enable:

`!config autoModMentionUsersEnabled true`

Disable:

`!config autoModMentionUsersEnabled false`

## Max \# of Mentions

The maximum amount of users a member can mention in a message.

Type: `Number`

Default: `5`

Reset to default: `!config autoModMentionUsersMaxNumberOfMentions default`

Examples:

`!config autoModMentionUsersMaxNumberOfMentions 2`

`!config autoModMentionUsersMaxNumberOfMentions 5`

## Enabled

Automatically moderate messages that mention an excessive amount of roles.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModMentionRolesEnabled default`

Enable:

`!config autoModMentionRolesEnabled true`

Disable:

`!config autoModMentionRolesEnabled false`

## Max \# of Mentions

The maximum amount of roles a member can mention in a message.

Type: `Number`

Default: `3`

Reset to default: `!config autoModMentionRolesMaxNumberOfMentions default`

Examples:

`!config autoModMentionRolesMaxNumberOfMentions 2`

`!config autoModMentionRolesMaxNumberOfMentions 5`

## Enabled

Automatically moderate messages with an excessive amount of emojis.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModEmojisEnabled default`

Enable:

`!config autoModEmojisEnabled true`

Disable:

`!config autoModEmojisEnabled false`

## Max \# of Emojis

The maximum amount of emojis a message is allowed to have before trigger the rule.

Type: `Number`

Default: `5`

Reset to default: `!config autoModEmojisMaxNumberOfEmojis default`

Examples:

`!config autoModEmojisMaxNumberOfEmojis 5`

`!config autoModEmojisMaxNumberOfEmojis 10`

## Enabled

Automatically give members nicknames if they try to hoist \(use special characters to appear at the top of the user list\).

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModHoistEnabled default`

Enable:

`!config autoModHoistEnabled true`

Disable:

`!config autoModHoistEnabled false`

