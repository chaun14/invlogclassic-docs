# Settings

## Configs

There are many config options that can be set. You don't have to set all of them. If you just added the bot, just run `!setup`, which will guide you through the most important ones.

### Overview

#### عام

| Setting | Description |
| :--- | :--- |
| بريفكس | البريفكس المستخدم لتشغيل أوامر البوت. |
| لغه | لغة البوت |
| قناه السجل | القناه التي يتم تسجيل حركات البوت فيها. |
| الحصول على التحديثات | فعل لتلقي تحديثات التطوير الخاصه بInviteManager. |
| قنوات الأوامر | القنوات التي سيتفاعل فيها البوت مع الأوامر. |
| القنوات المتجاهلة | القنوات التي سيتجاهل فيها البوت الأوامر. |

#### دعوات

**General**

| Setting | Description |
| :--- | :--- |
| Join Roles | Roles that are assigned to all members when joining. |

**الانضمامات**

| Setting | Description |
| :--- | :--- |
| رساله | الرسالة المرسلة عندما يدخل شخص ما الخادم/السيرفر. |
| قناه الرسائل | القناة التي يتم إرسال رسالة الدخول فيها. |

**المغادرات**

| Setting | Description |
| :--- | :--- |
| رساله | الرسالة المرسلة عندما يترك شخص ما الخادم/السيرفر. |
| قناه الرسائل | القناة التي يتم إرسال رسالة الخروج فيها. |
| طرح تلقائي | ازالة الدعوات تلقائيًا من المدعو عندما يغادر |
| بداية الطرح التلقائي | الوقت بالثواني الذي يتعين على المستخدم البقاء فيه في السيرفر للدعوه للعد |

**المتصدرين**

| Setting | Description |
| :--- | :--- |
| اسلوب  | مظهر اسلوب المتصدرين |
| اخفي الاعضاء الذين خرجوا | إخفاء الأعضاء الذين تركوا الخادم من المتصدرين |

**المزيفون**

| Setting | Description |
| :--- | :--- |
| طرح تلقائي | ازاله الدعوات المزورة تلقائياً |

**رتب**

| Setting | Description |
| :--- | :--- |
| أسلوب الواجب | كيف تتم مكافأة الرتب للمستخدمين. |
| قناه التصاريح | القناة التي يعلن فيها المستخدمون الذين يتلقون رتبة جديدة. |
| رساله التصريح | الرسالة التي يتم إرسالها عندما يتلقى المستخدم رتبة جديدة. |

#### اداره

**كلمة التحقق**

| Setting | Description |
| :--- | :--- |
| مفعل | سواء تم تفعيل التحقق من كلمة التحقق أم لا. |
| رسالة الترحيب | الرسالة التي سيحصل عليها المستخدم بعد الانضمام إلى الخادم وتوجيهه لدخول اختبار كلمة التحقق. |
| رسالة النجاح | رسالة الترحيب التي سيتم إرسالها إلى المستخدم بعد أن يتحقق بنجاح. |
| رسالة فاشلة | الرسالة التي يتم إرسالها عندما يخفق المستخدم بكلمه التحقق. |
| التحقق من المهلة | الوقت الذي يتم فيه إدخال كلمة التحقق بنجاح. |
| السجل مفعل | سواء سيتم تسجيل محاولات التحقق ام لا. |

**عام**

| Setting | Description |
| :--- | :--- |
| تمكين | Automatically moderate messages \(specific rules can also be turned on or off, this has to be ON for ANY rule to work\). |
| القنوات الادارية | The list of moderated channels \(this acts as a whitelist, leave empty to moderate all channels, or use `autoModIgnoredChannels` to ignore certain channels\). |
| الرتب الادارية | The list of roles that are moderated \(this acts as a whitelist, leave empty to moderate all roles, or use `autoModIgnoredRoles` to ignore certain roles\). |
| القنوات المتجاهلة | Channels that are ignored while automatically moderating. |
| تجاهل الأدوار | Any members with these roles will not automatically be moderated. |
| رتبه صامته | The role that is given to people who are muted. Make sure this role is denied the "Send Message" permission. |
| معطل للأعضاء القدامى | Disabled auto moderation for members that have been in your server for a long time. |
| الأعضاء القديمة عتبة | The amount of time a member has to be in your server to be considered 'old'. |

**تسجيل**

| Setting | Description |
| :--- | :--- |
| Log Enabled | Log any moderation actions that the bot makes. |
| سجل القناه الخاص بالمود | القناة التي سيتم نشر سجلات المود فيها. |
| حذف رسائل بوت | Automatically delete the bots own messages \(keeps your chat clean\). |
| حذف Bot Message Timeout | The timeout after which bot messages are deleted. |
| حذف رسائل الحظر | سواء سيتم حذف رسائل "الحظر" من عدمه تلقائيًا او لا. |
| حذف رسائل الطرد | سواء سيتم حذف رسائل "الطرد" من عدمه تلقائيًا او لا. |
| حذف رسائل الحظر | سواء سيتم حذف رسائل "الحظر" من عدمه تلقائيًا او لا. |
| حذف رسائل التحذير. | سواء سيتم حذف رسائل "تحذير" من عدمه تلقائيًا او لا. |
| حذف رسائل الصمت | سواء سيتم حذف رسائل "الصمت" من عدمه تلقائيًا او لا. |

**دعوات**

| Setting | Description |
| :--- | :--- |
| تمكين | Automatically scan messages for discord invite links and remove them. |

**روابط**

| Setting | Description |
| :--- | :--- |
| تمكين | Automatically remove messages containing links \(you can set a whitelist and blacklist\). |
| القائمة البيضاء | A list of links that users are allowed to post. |
| القائمة السوداء | Blacklist certain links which users won't be able to post. |
| Follow Redirects | Enable this to resolve redirects for links. |

**كلمات محظوره**

| Setting | Description |
| :--- | :--- |
| مفعل | سواء سيتم التحقق تلقائياً من رسائل المحظوره او لا. |
| حظر | قائمه من الكلمات المحظوره |

**احرف كبيره**

| Setting | Description |
| :--- | :--- |
| تمكين | Automatically moderate messages with A LOT OF CAPS. |
| الحد الأدنى من الشخصيات | The minimum amount of characters in a message to be considered for moderating \(setting to '3' would ignore 'OK'\). |
| النسبة المئوية CAPs | The percentage of characters of the message that have to be CAPs for the rule to trigger. |

**رسائل مكررة**

| Setting | Description |
| :--- | :--- |
| تمكين | Automatically moderate duplicate messages \(copy-paste spam\). |
| الإطار الزمني بالثواني | The timeframe whithin which messages will be considered duplicates. |

**سبام/اصرار**

| Setting | Description |
| :--- | :--- |
| مفعل | Automatically moderate users sending a lot of messages in a short time. |
| \# من الرسائل | The number of messages that have to be sent within the timeframe to trigger the rule. |
| الإطار الزمني بالثواني | The timeframe within which a user is allowed to send a maximum amount of messages. |

**إشارات**

| Setting | Description |
| :--- | :--- |
| تمكين | Automatically moderate messages that mention an excessive amount of users. |
| Max \# of Mentions | The maximum amount of users a member can mention in a message. |
| تمكين | Automatically moderate messages that mention an excessive amount of roles. |
| Max \# of Mentions | The maximum amount of roles a member can mention in a message. |

**ايموجيز - تعبير وجه**

| Setting | Description |
| :--- | :--- |
| تمكين | Automatically moderate messages with an excessive amount of emojis. |
| ماكس \# من Emojis | The maximum amount of emojis a message is allowed to have before trigger the rule. |
| Enabled | Automatically give members nicknames if they try to hoist \(use special characters to appear at the top of the user list\). |

### بريفكس

البريفكس المستخدم لتشغيل أوامر البوت.

Type: `String`

Default: `!`

Reset to default: `!config prefix default`

Examples:

`!config prefix +`

`!config prefix >`

### لغه

لغة البوت

Type: `Enum<Lang>`

Default: `en`

Reset to default: `!config lang default`

Possible values: `ar`, `bg`, `cs`, `de`, `el`, `en`, `es`, `fr`, `hu`, `id_ID`, `it`, `ja`, `lt`, `nl`, `pl`, `pt`, `pt_BR`, `ro`, `ru`, `sr`, `tr`, `zh_CN`, `zh_TW`

Example:

`!config lang ar`

### قناه السجل

القناه التي يتم تسجيل حركات البوت فيها.

Type: `Channel`

Default: `null`

Reset to default: `!config logChannel default`

Examples:

`!config logChannel #channel`

### الحصول على التحديثات

فعل لتلقي تحديثات التطوير الخاصه بInviteManager.

Type: `Boolean`

Default: `true`

Reset to default: `!config getUpdates default`

Enable:

`!config getUpdates true`

Disable:

`!config getUpdates false`

### قنوات الأوامر

القنوات التي سيتفاعل فيها البوت مع الأوامر.

Type: `Channel[]`

Default: \`\`

Reset to default: `!config channels default`

### القنوات المتجاهلة

القنوات التي سيتجاهل فيها البوت الأوامر.

Type: `Channel[]`

Default: \`\`

Reset to default: `!config ignoredChannels default`

### Join Roles

Roles that are assigned to all members when joining.

Type: `Role[]`

Default: \`\`

Reset to default: `!config joinRoles default`

### رساله

الرسالة المرسلة عندما يدخل شخص ما الخادم/السيرفر.

Type: `String`

Default: `{memberMention} **joined**; Invited by **{inviterName}** (**{numInvites}** invites)`

Reset to default: `!config joinMessage default`

### قناه الرسائل

القناة التي يتم إرسال رسالة الدخول فيها.

Type: `Channel`

Default: `null`

Reset to default: `!config joinMessageChannel default`

Examples:

`!config joinMessageChannel #general`

`!config joinMessageChannel #joins`

### رساله

الرسالة المرسلة عندما يترك شخص ما الخادم/السيرفر.

Type: `String`

Default: `{memberName} **left**; Invited by **{inviterName}**`

Reset to default: `!config leaveMessage default`

Examples:

`!config leaveMessage`

`!config leaveMessage`

### قناه الرسائل

القناة التي يتم إرسال رسالة الخروج فيها.

Type: `Channel`

Default: `null`

Reset to default: `!config leaveMessageChannel default`

Examples:

`!config leaveMessageChannel #general`

`!config leaveMessageChannel #leaves`

### اسلوب

مظهر اسلوب المتصدرين

Type: `Enum<LeaderboardStyle>`

Default: `normal`

Reset to default: `!config leaderboardStyle default`

Possible values: `normal`, `table`, `mentions`

Example:

`!config leaderboardStyle normal`

### اخفي الاعضاء الذين خرجوا

إخفاء الأعضاء الذين تركوا الخادم من المتصدرين

Type: `Boolean`

Default: `true`

Reset to default: `!config hideLeftMembersFromLeaderboard default`

Enable:

`!config hideLeftMembersFromLeaderboard true`

Disable:

`!config hideLeftMembersFromLeaderboard false`

### طرح تلقائي

ازاله الدعوات المزورة تلقائياً

Type: `Boolean`

Default: `true`

Reset to default: `!config autoSubtractFakes default`

Enable:

`!config autoSubtractFakes true`

Disable:

`!config autoSubtractFakes false`

### طرح تلقائي

ازالة الدعوات تلقائيًا من المدعو عندما يغادر

Type: `Boolean`

Default: `true`

Reset to default: `!config autoSubtractLeaves default`

Enable:

`!config autoSubtractLeaves true`

Disable:

`!config autoSubtractLeaves false`

### بداية الطرح التلقائي

الوقت بالثواني الذي يتعين على المستخدم البقاء فيه في السيرفر للدعوه للعد

Type: `Number`

Default: `600`

Reset to default: `!config autoSubtractLeaveThreshold default`

Examples:

`!config autoSubtractLeaveThreshold 60`

`!config autoSubtractLeaveThreshold 3600`

### أسلوب الواجب

كيف تتم مكافأة الرتب للمستخدمين.

Type: `Enum<RankAssignmentStyle>`

Default: `all`

Reset to default: `!config rankAssignmentStyle default`

Possible values: `all`, `highest`, `onlyAdd`

Example:

`!config rankAssignmentStyle all`

### قناه التصاريح

القناة التي يعلن فيها المستخدمون الذين يتلقون رتبة جديدة.

Type: `Channel`

Default: `null`

Reset to default: `!config rankAnnouncementChannel default`

Examples:

`!config rankAnnouncementChannel`

`!config rankAnnouncementChannel`

### رساله التصريح

الرسالة التي يتم إرسالها عندما يتلقى المستخدم رتبة جديدة.

Type: `String`

Default: `Congratulations, **{memberMention}** has reached the **{rankName}** rank!`

Reset to default: `!config rankAnnouncementMessage default`

Examples:

`!config rankAnnouncementMessage`

`!config rankAnnouncementMessage`

### مفعل

سواء تم تفعيل التحقق من كلمة التحقق أم لا.

Type: `Boolean`

Default: `false`

Reset to default: `!config captchaVerificationOnJoin default`

Enable:

`!config captchaVerificationOnJoin true`

Disable:

`!config captchaVerificationOnJoin false`

### رسالة الترحيب

الرسالة التي سيحصل عليها المستخدم بعد الانضمام إلى الخادم وتوجيهه لدخول اختبار كلمة التحقق.

Type: `String`

Default: `Welcome to the server **{serverName}**! For extra protection, new members are required to enter a captcha.`

Reset to default: `!config captchaVerificationWelcomeMessage default`

Examples:

`!config captchaVerificationWelcomeMessage Welcome, please enter the captcha below!`

### رسالة النجاح

رسالة الترحيب التي سيتم إرسالها إلى المستخدم بعد أن يتحقق بنجاح.

Type: `String`

Default: `You have successfully entered the captcha. Welcome to the server!`

Reset to default: `!config captchaVerificationSuccessMessage default`

Examples:

`!config captchaVerificationSuccessMessage Thanks for entering the captcha, enjoy our server!`

### رسالة فاشلة

الرسالة التي يتم إرسالها عندما يخفق المستخدم بكلمه التحقق.

Type: `String`

Default: `You did not enter the captha right within the specified time.We're sorry, but we have to kick you from the server. Feel free to join again.`

Reset to default: `!config captchaVerificationFailedMessage default`

Examples:

`!config captchaVerificationFailedMessage Looks like you are not human :(. You can join again and try again later if this was a mistake!`

### التحقق من المهلة

الوقت الذي يتم فيه إدخال كلمة التحقق بنجاح.

Type: `Number`

Default: `180`

Reset to default: `!config captchaVerificationTimeout default`

Examples:

`!config captchaVerificationTimeout 60`

`!config captchaVerificationTimeout 600`

### السجل مفعل

سواء سيتم تسجيل محاولات التحقق ام لا.

Type: `Boolean`

Default: `true`

Reset to default: `!config captchaVerificationLogEnabled default`

Enable:

`!config captchaVerificationLogEnabled true`

Disable:

`!config captchaVerificationLogEnabled false`

### تمكين

Automatically moderate messages \(specific rules can also be turned on or off, this has to be ON for ANY rule to work\).

Type: `Boolean`

Default: `false`

Reset to default: `!config autoModEnabled default`

Enable:

`!config autoModEnabled true`

Disable:

`!config autoModEnabled false`

### القنوات الادارية

The list of moderated channels \(this acts as a whitelist, leave empty to moderate all channels, or use `autoModIgnoredChannels` to ignore certain channels\).

Type: `Channel[]`

Default: \`\`

Reset to default: `!config autoModModeratedChannels default`

Examples:

`!config autoModModeratedChannels #general`

`!config autoModModeratedChannels #support,#help`

### الرتب الادارية

The list of roles that are moderated \(this acts as a whitelist, leave empty to moderate all roles, or use `autoModIgnoredRoles` to ignore certain roles\).

Type: `Role[]`

Default: \`\`

Reset to default: `!config autoModModeratedRoles default`

Examples:

`!config autoModModeratedRoles @NewMembers`

`!config autoModModeratedRoles @Newbies,@Starters`

### القنوات المتجاهلة

Channels that are ignored while automatically moderating.

Type: `Channel[]`

Default: \`\`

Reset to default: `!config autoModIgnoredChannels default`

Examples:

`!config autoModIgnoredChannels #general`

`!config autoModIgnoredChannels #off-topic,#nsfw`

### تجاهل الأدوار

Any members with these roles will not automatically be moderated.

Type: `Role[]`

Default: \`\`

Reset to default: `!config autoModIgnoredRoles default`

Examples:

`!config autoModIgnoredRoles @TrustedMembers`

`!config autoModIgnoredRoles @Moderators,@Staff`

### رتبه صامته

The role that is given to people who are muted. Make sure this role is denied the "Send Message" permission.

Type: `Role`

Default: `null`

Reset to default: `!config mutedRole default`

Examples:

`!config mutedRole @muted`

### معطل للأعضاء القدامى

Disabled auto moderation for members that have been in your server for a long time.

Type: `Boolean`

Default: `false`

Reset to default: `!config autoModDisabledForOldMembers default`

Enable:

`!config autoModDisabledForOldMembers true`

Disable:

`!config autoModDisabledForOldMembers false`

### الأعضاء القديمة عتبة

The amount of time a member has to be in your server to be considered 'old'.

Type: `Number`

Default: `604800`

Reset to default: `!config autoModDisabledForOldMembersThreshold default`

Examples:

`!config autoModDisabledForOldMembersThreshold 604800` \(1 week\)\`\`

`!config autoModDisabledForOldMembersThreshold 2419200` \(1 month\)\`\`

### Log Enabled

Log any moderation actions that the bot makes.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModLogEnabled default`

Enable:

`!config autoModLogEnabled true`

Disable:

`!config autoModLogEnabled false`

### سجل القناه الخاص بالمود

القناة التي سيتم نشر سجلات المود فيها.

Type: `Channel`

Default: `null`

Reset to default: `!config modLogChannel default`

Examples:

`!config modLogChannel #channel`

`!config modLogChannel #logs`

### حذف رسائل بوت

Automatically delete the bots own messages \(keeps your chat clean\).

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModDeleteBotMessage default`

Enable:

`!config autoModDeleteBotMessage true`

Disable:

`!config autoModDeleteBotMessage false`

### حذف Bot Message Timeout

The timeout after which bot messages are deleted.

Type: `Number`

Default: `5`

Reset to default: `!config autoModDeleteBotMessageTimeoutInSeconds default`

Examples:

`!config autoModDeleteBotMessageTimeoutInSeconds 5`

`!config autoModDeleteBotMessageTimeoutInSeconds 10`

### حذف رسائل الحظر

سواء سيتم حذف رسائل "الحظر" من عدمه تلقائيًا او لا.

Type: `Boolean`

Default: `true`

Reset to default: `!config modPunishmentBanDeleteMessage default`

Enable:

`!config modPunishmentBanDeleteMessage true`

Disable:

`!config modPunishmentBanDeleteMessage false`

### حذف رسائل الطرد

سواء سيتم حذف رسائل "الطرد" من عدمه تلقائيًا او لا.

Type: `Boolean`

Default: `true`

Reset to default: `!config modPunishmentKickDeleteMessage default`

Enable:

`!config modPunishmentKickDeleteMessage true`

Disable:

`!config modPunishmentKickDeleteMessage false`

### حذف رسائل الحظر

سواء سيتم حذف رسائل "الحظر" من عدمه تلقائيًا او لا.

Type: `Boolean`

Default: `true`

Reset to default: `!config modPunishmentSoftbanDeleteMessage default`

Enable:

`!config modPunishmentSoftbanDeleteMessage true`

Disable:

`!config modPunishmentSoftbanDeleteMessage false`

### حذف رسائل التحذير.

سواء سيتم حذف رسائل "تحذير" من عدمه تلقائيًا او لا.

Type: `Boolean`

Default: `true`

Reset to default: `!config modPunishmentWarnDeleteMessage default`

Enable:

`!config modPunishmentWarnDeleteMessage true`

Disable:

`!config modPunishmentWarnDeleteMessage false`

### حذف رسائل الصمت

سواء سيتم حذف رسائل "الصمت" من عدمه تلقائيًا او لا.

Type: `Boolean`

Default: `true`

Reset to default: `!config modPunishmentMuteDeleteMessage default`

Enable:

`!config modPunishmentMuteDeleteMessage true`

Disable:

`!config modPunishmentMuteDeleteMessage false`

### تمكين

Automatically scan messages for discord invite links and remove them.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModInvitesEnabled default`

Enable:

`!config autoModInvitesEnabled true`

Disable:

`!config autoModInvitesEnabled false`

### تمكين

Automatically remove messages containing links \(you can set a whitelist and blacklist\).

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModLinksEnabled default`

Enable:

`!config autoModLinksEnabled true`

Disable:

`!config autoModLinksEnabled false`

### القائمة البيضاء

A list of links that users are allowed to post.

Type: `String[]`

Default: \`\`

Reset to default: `!config autoModLinksWhitelist default`

Examples:

`!config autoModLinksWhitelist discordbots.org`

`!config autoModLinksWhitelist youtube.com,twitch.com`

### القائمة السوداء

Blacklist certain links which users won't be able to post.

Type: `String[]`

Default: \`\`

Reset to default: `!config autoModLinksBlacklist default`

Examples:

`!config autoModLinksBlacklist google.com`

`!config autoModLinksBlacklist twitch.com,youtube.com`

### Follow Redirects

Enable this to resolve redirects for links.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModLinksFollowRedirects default`

Enable:

`!config autoModLinksFollowRedirects true`

Disable:

`!config autoModLinksFollowRedirects false`

### مفعل

سواء سيتم التحقق تلقائياً من رسائل المحظوره او لا.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModWordsEnabled default`

Enable:

`!config autoModWordsEnabled true`

Disable:

`!config autoModWordsEnabled false`

### حظر

قائمه من الكلمات المحظوره

Type: `String[]`

Default: \`\`

Reset to default: `!config autoModWordsBlacklist default`

Examples:

`!config autoModWordsBlacklist gay`

`!config autoModWordsBlacklist stupid,fuck`

### تمكين

Automatically moderate messages with A LOT OF CAPS.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModAllCapsEnabled default`

Enable:

`!config autoModAllCapsEnabled true`

Disable:

`!config autoModAllCapsEnabled false`

### الحد الأدنى من الشخصيات

The minimum amount of characters in a message to be considered for moderating \(setting to '3' would ignore 'OK'\).

Type: `Number`

Default: `10`

Reset to default: `!config autoModAllCapsMinCharacters default`

Examples:

`!config autoModAllCapsMinCharacters 5`

`!config autoModAllCapsMinCharacters 15`

### النسبة المئوية CAPs

The percentage of characters of the message that have to be CAPs for the rule to trigger.

Type: `Number`

Default: `70`

Reset to default: `!config autoModAllCapsPercentageCaps default`

Examples:

`!config autoModAllCapsPercentageCaps 50`

`!config autoModAllCapsPercentageCaps 90`

### تمكين

Automatically moderate duplicate messages \(copy-paste spam\).

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModDuplicateTextEnabled default`

Enable:

`!config autoModDuplicateTextEnabled true`

Disable:

`!config autoModDuplicateTextEnabled false`

### الإطار الزمني بالثواني

The timeframe whithin which messages will be considered duplicates.

Type: `Number`

Default: `60`

Reset to default: `!config autoModDuplicateTextTimeframeInSeconds default`

Examples:

`!config autoModDuplicateTextTimeframeInSeconds 5`

`!config autoModDuplicateTextTimeframeInSeconds 20`

### مفعل

Automatically moderate users sending a lot of messages in a short time.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModQuickMessagesEnabled default`

Enable:

`!config autoModQuickMessagesEnabled true`

Disable:

`!config autoModQuickMessagesEnabled false`

### \# من الرسائل

The number of messages that have to be sent within the timeframe to trigger the rule.

Type: `Number`

Default: `5`

Reset to default: `!config autoModQuickMessagesNumberOfMessages default`

Examples:

`!config autoModQuickMessagesNumberOfMessages 5`

`!config autoModQuickMessagesNumberOfMessages 10`

### الإطار الزمني بالثواني

The timeframe within which a user is allowed to send a maximum amount of messages.

Type: `Number`

Default: `3`

Reset to default: `!config autoModQuickMessagesTimeframeInSeconds default`

Examples:

`!config autoModQuickMessagesTimeframeInSeconds 2`

`!config autoModQuickMessagesTimeframeInSeconds 10`

### تمكين

Automatically moderate messages that mention an excessive amount of users.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModMentionUsersEnabled default`

Enable:

`!config autoModMentionUsersEnabled true`

Disable:

`!config autoModMentionUsersEnabled false`

### Max \# of Mentions

The maximum amount of users a member can mention in a message.

Type: `Number`

Default: `5`

Reset to default: `!config autoModMentionUsersMaxNumberOfMentions default`

Examples:

`!config autoModMentionUsersMaxNumberOfMentions 2`

`!config autoModMentionUsersMaxNumberOfMentions 5`

### تمكين

Automatically moderate messages that mention an excessive amount of roles.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModMentionRolesEnabled default`

Enable:

`!config autoModMentionRolesEnabled true`

Disable:

`!config autoModMentionRolesEnabled false`

### Max \# of Mentions

The maximum amount of roles a member can mention in a message.

Type: `Number`

Default: `3`

Reset to default: `!config autoModMentionRolesMaxNumberOfMentions default`

Examples:

`!config autoModMentionRolesMaxNumberOfMentions 2`

`!config autoModMentionRolesMaxNumberOfMentions 5`

### تمكين

Automatically moderate messages with an excessive amount of emojis.

Type: `Boolean`

Default: `true`

Reset to default: `!config autoModEmojisEnabled default`

Enable:

`!config autoModEmojisEnabled true`

Disable:

`!config autoModEmojisEnabled false`

### ماكس \# من Emojis

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

