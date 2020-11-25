# Commands

## Commands

To get a list of available commands, do !help on your server.

### Arguments & Flags

Most commands accept arguments and/or flags.  
According to the **Type** of the argument or flag you can provide different values.

#### Boolean

This arguments expects `true` or `false`. You can also use `yes` and `no`.

#### رقم

This arguments expects a number

#### Enum

This arguments expects a value from a specific set of valid values.

> Depending on the command the valid values can vary. Use `!help <command>` \(eg. `!help addRank`\) to get more information about the command and the valid values for the enum.

#### رقم الدعوة

This arguments expects a Discord Invite Code.

> You can put only the part after `https://discord.gg/` to prevent Discord from creating a preview.

#### المستعمل

This arguments expects a Discord User. You can use any of the following methods to provide a user:

* Mention the user: `@Valandur`
* Use their ID: `102785693046026240`
* Use their name: `Valandur`
* Use their name and discriminator: `Valandur#3581`
* Use quotes if their name has a space: `"Valandur with a space"`

#### وظيفة

This arguments expects a Discord Role. You can use any of the following methods to provide a role:

* Mention the role: `@Admin`
* Use the ID: `102785693046026240`
* Use the name: `Admin`
* Use quotes if the name has a space: `"Admin with a space"`

#### القناة

This arguments expects a Discord Channel. You can use any of the following methods to provide a channel:

* Mention the channel: `#general`
* Use the ID: `409846838129197057`
* Use the name: `general`
* Use quotes if the name has a space: `"general with a space"`

#### أمر

This argument expects a command of this bot. You can use any of the following methods to provide a command:

* Use the command name: `invites`
* Use an alias of the command: `p`

#### نص

This arguments expects any text. You can use quotes \(`"Text with quotes"`\) for text that has spaces.

> If the text is the last argument you don't have to use quotes.

#### تاريخ

This argument expects a date. You can use various formats, but we recommend: `YYYY-MM-DD`

#### المدة الزمنية

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
| addInvites | أضافة/ازالة دعوات للعضو او منه. | !addInvites \ \ \[reason\] |
| clearInvites | تنظيف الاضافات للسيرفر او لمستعمل. | !clearInvites \[-d value\|--date=value\]\[-cb\|--clearbonus\] \[user\] |
| createInvite | انشاء كود الدعوات فريد من نوعه. | !createInvite \ \[channel\]\[maxuses\] \[expires\]\[temporarymembership\] |
| info | عرض معلومات حول عضو معين. | !info \ \[details\]\[page\] |
| inviteCodes | الحصول على قائمة كل ما لديك من روابط | !inviteCodes |
| inviteDetails | يعرض تفاصيل من اين لك دعواتك. | !inviteDetails \[user\] |
| invites | اظهار عدد الدعوات الخاصة. | !invites \[user\] |
| leaderboard | إظهار الأعضاء مع اعلى الدعوات. | !leaderboard \[page\] |
| removeInvites | Removes a specified amount of invites from a user. | !removeInvites \ \ \[reason\] |
| restoreInvites | استعادة جميع الدعوات التي تم مسحها مسبقًا. | !restoreInvites \[user\] |
| subtractFakes | Remove fake invites from all users. | !subtractFakes |
| subtractLeaves | Remove leaves from all users | !subtractLeaves |

#### Ranks

| Command | Description | Usage |
| :--- | :--- | :--- |
| addRank | أضف رتبة جديدة. | !addRank \ \ \[info\] |
| fixRanks | Deletes any ranks where the role was deleted. | !fixRanks |
| ranks | اظهار كل الرتب. | !ranks \[page\] |
| removeRank | إزالة رتبة. | !removeRank \ |

#### Config

| Command | Description | Usage |
| :--- | :--- | :--- |
| botConfig | قم باظهار وتغيير اعدادات البوت. | !botConfig \[key\]\[value\] |
| config | اظهر وغير الاعدادات في السيرفر. | !config \[key\]\[value\] |
| interactiveConfig | التكوين التفاعلي | !interactiveConfig |
| inviteCodeConfig | اظهار وتغيير اعدادات كود الدعوات في السيرفر | !inviteCodeConfig \[key\]\[invitecode\] \[value\] |
| memberConfig | اظهر وغير الاعدادات التابعة للاعضاء في السيرفر. | !memberConfig \[key\]\[user\] \[value\] |
| permissions | تهيئة الإذن ليستخدم الأوامر | !permissions \[cmd\]\[role\] |

#### Info

| Command | Description | Usage |
| :--- | :--- | :--- |
| botInfo | الحصول على معلومات عامة حول الروبوت. | !botInfo |
| credits | إظهار المطورين والمساهمين في البوت. | !credits |
| getBot | الحصول على رابط دعوة للبوت. | !getBot |
| help | عرض المساعدة. | !help \[command\] |
| members | إظهار عدد الأعضاء لسيرفر الحالي. | !members |
| ping | بينغ الروبوت | !ping |
| prefix | يظهر البادئة الحالية للروبوت. | !prefix |
| setup | Help with setting up the bot and checking for problems \(e.g. missing permissions\) | !setup |
| support | Get an invite link to our support server. | !support |

#### Premium

| Command | Description | Usage |
| :--- | :--- | :--- |
| export | اصدار ملفات الانفايت منجر لـ csv | !export \ |
| premium | معلومات حول الإصدار المتميز من InviteManager. | !premium \[action\] |
| tryPremium | Try the premium version of InviteManager for free for a limited duration. | !tryPremium |

#### Moderation

| Command | Description | Usage |
| :--- | :--- | :--- |
| ban | قم بحظر العضو من السيرفر الخاص بك. | !ban \[-d value\|--deleteMessageDays=value\] \ \[reason\] |
| caseDelete | حذف حالة معينة. | !caseDelete \ \[reason\] |
| caseView | عرض معلومات حول حالة معينة. | !caseView \ |
| check | تحقق من انتهاك وتاريخ العقوبة للمستخدم. | !check \ |
| clean | مسح روم/غرفة لنوع معين من الرسائل | !clean \ \[numberOfMessages\] |
| cleanShort | قم بمسح الرسائل القصيرة | !cleanShort \ \[numberOfMessages\] |
| cleanText | حذف الرسائل التي تحتوي على كلمات رئيسية معينة. | !cleanText \ \[numberOfMessages\] |
| kick | طرد عضو من سيرفر | !kick \ \[reason\] |
| lockdown | Lockdown a specific channel \(Prevents anyone without special roles from sending messages\) | !lockdown \[-t value\|--timeout=value\]\[channel\] |
| mute | اسكت المستخدم | !mute \[-d value\|--duration=value\] \ \[reason\] |
| punishmentConfig | Configure punishments when reaching a certain amount of strikes. | !punishmentConfig \[punishment\]\[strikes\] \[args\] |
| purge | Purge messages in a channel. | !purge \ \[user\] |
| purgeUntil | Purge messages in a channel up until a specified message. | !purgeUntil \ |
| softBan | Ban and then automatically unban a member from the server. | !softBan \[-d value\|--deleteMessageDays=value\] \ \[reason\] |
| strike | Add strikes to a user | !strike \ \ \ |
| strikeConfig | Configure strikes received for various violations. | !strikeConfig \[violation\]\[strikes\] |
| unban | فك الحظر من شخص. | !unban \ \[reason\] |
| unhoist | Add a character in front of all members with a special character in front of their name, so they will be shown at the end of the member list. | !unhoist |
| unmute | فك الاسكات من شخص. | !unmute \ |
| warn | تحذير شخص. | !warn \ \[reason\] |

#### Other

| Command | Description | Usage |
| :--- | :--- | :--- |
| graph | يعرض الرسوم البيانية حول الإحصائيات المختلفة على هذا السيرفر. | !graph \ \[from\]\[to\] |

### !addInvites

أضافة/ازالة دعوات للعضو او منه.

#### Usage

```text
!addInvites <user> <amount> [reason]
```

#### Aliases

* `!add-invites`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | المستعمل | Yes | المستعمل المشار اليه ستضاف او تنقص منه الدعوات الاضافية. |  |
| amount | رقم | Yes | مقدار الدعوات التي سيحصل عليها المستعمل او يخسرها, استعمل \(-\) وبجانبها العدد لازالة الدعوات. |  |
| reason | نص | No | السبب لاضافة او ازالة الدعوات.. |  |

#### Examples

```text
!addInvites @User 5
```

```text
!addInvites "Name with space" -30 Removed for cheating
```

### !addRank

أضف رتبة جديدة.

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
| role | وظيفة | Yes | الرتبة التي سيحصل عليها المستخدم عند الوصول إلى هذا العدد. |  |
| invites | رقم | Yes | كمية الدعوات اللازمة للوصول إلى الرتبة. |  |
| info | نص | No | وصف سيشاهده المستخدمون حتى يعرفوا المزيد عن هذه الرتبة. |  |

#### Examples

```text
!addRank @Role 5
```

```text
!addRank "Role with space" 10 Wow, already 10 people!
```

### !ban

قم بحظر العضو من السيرفر الخاص بك.

#### Usage

```text
!ban [-d value|--deleteMessageDays=value] <user> [reason]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | المستعمل | Yes | قم بذكر المستعمل للحظر. |  |
| reason | نص | No | لماذا تم حظر المستعمل؟ |  |

#### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑deleteMessageDays | ‑d | رقم | If specified will delete messages by the banned members this many days back. |

#### Examples

### !botConfig

قم باظهار وتغيير اعدادات البوت.

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
| key | Enum | No | اعدادات البوت التي تريد اظهارها/تغييرها. | Use one of the following values: `activityEnabled`, `activityMessage`, `activityStatus`, `activityType`, `activityUrl`, `embedDefaultColor` |
| value | القيمة | No | الاعدادت الجديدة. |  |

#### Examples

```text
!botConfig
```

### !botInfo

الحصول على معلومات عامة حول الروبوت.

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

حذف حالة معينة.

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
| caseNumber | رقم | Yes | رقم القضية |  |
| reason | نص | No | السبب الذي بسببه ستحذف القضية. |  |

#### Examples

```text
!caseDelete 5434 User apologized
```

### !caseView

عرض معلومات حول حالة معينة.

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
| caseNumber | رقم | Yes | رقم القضية |  |

#### Examples

```text
!caseView 5434
```

### !check

تحقق من انتهاك وتاريخ العقوبة للمستخدم.

#### Usage

```text
!check <user>
```

#### Aliases

* `!history`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | المستعمل | Yes | الرجاء اذكر المستخدم للفحص. |  |

#### Examples

```text
!check @User
```

```text
!check "User with space"
```

### !clean

مسح روم/غرفة لنوع معين من الرسائل

#### Usage

```text
!clean <type> [numberOfMessages]
```

#### Aliases

* `!clear`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| type | Enum | Yes | الرجاء تحديد نوع الرسائل التي ستقوم بحذفها | Use one of the following values: `bots`, `embeds`, `emojis`, `images`, `links`, `mentions`, `reacted`, `reactions` |
| numberOfMessages | رقم | No | الرجاء تحديد عدد الرسائل التي ستقوم بالبحث عنها |  |

#### Examples

### !cleanShort

قم بمسح الرسائل القصيرة

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
| maxTextLength | رقم | Yes | اي رسالة اقصر من هذه سيتم حذفها. |  |
| numberOfMessages | رقم | No | عدد الرسائل التي سيتم البحث عنها. |  |

#### Examples

### !cleanText

حذف الرسائل التي تحتوي على كلمات رئيسية معينة.

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
| text | نص | Yes | جميع الرسائل التي تحتوي هذه الكلمة سيتم حذفها. |  |
| numberOfMessages | رقم | No | عدد الرسائل التي سيتم البحث عنها. |  |

#### Examples

### !clearInvites

تنظيف الاضافات للسيرفر او لمستعمل.

#### Usage

```text
!clearInvites [-d value|--date=value] [-cb|--clearBonus] [user]
```

#### Aliases

* `!clear-invites`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | المستعمل | No | قم بذكر المستعمل لمسح جميع الانفايت التابع له, او قم بتنظيف جميع المستعملين. |  |

#### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑date | ‑d | تاريخ | تاريخ البدء الذي يجب فيه حساب الدعوات. الافتراضي هو اليوم. |
| ‑‑clearBonus | ‑cb | Boolean | إضافة هذه العلامة لمسح المكافآت تدعو أيضا. خلاف ذلك ، يتم ترك دعوات المكافأة دون تغيير. |

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

اظهر وغير الاعدادات في السيرفر.

#### Usage

```text
!config [key] [value]
```

#### Aliases

* `!c`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| key | Enum | No | الاعدادات التي تحتاجها تظهر/تغير. | Use one of the following values: `autoModAllCapsEnabled`, `autoModAllCapsMinCharacters`, `autoModAllCapsPercentageCaps`, `autoModDeleteBotMessage`, `autoModDeleteBotMessageTimeoutInSeconds`, `autoModDisabledForOldMembers`, `autoModDisabledForOldMembersThreshold`, `autoModDuplicateTextEnabled`, `autoModDuplicateTextTimeframeInSeconds`, `autoModEmojisEnabled`, `autoModEmojisMaxNumberOfEmojis`, `autoModEnabled`, `autoModHoistEnabled`, `autoModIgnoredChannels`, `autoModIgnoredRoles`, `autoModInvitesEnabled`, `autoModLinksBlacklist`, `autoModLinksEnabled`, `autoModLinksFollowRedirects`, `autoModLinksWhitelist`, `autoModLogEnabled`, `autoModMentionRolesEnabled`, `autoModMentionRolesMaxNumberOfMentions`, `autoModMentionUsersEnabled`, `autoModMentionUsersMaxNumberOfMentions`, `autoModModeratedChannels`, `autoModModeratedRoles`, `autoModQuickMessagesEnabled`, `autoModQuickMessagesNumberOfMessages`, `autoModQuickMessagesTimeframeInSeconds`, `autoModWordsBlacklist`, `autoModWordsEnabled`, `autoSubtractFakes`, `autoSubtractLeaves`, `autoSubtractLeaveThreshold`, `captchaVerificationFailedMessage`, `captchaVerificationLogEnabled`, `captchaVerificationOnJoin`, `captchaVerificationSuccessMessage`, `captchaVerificationTimeout`, `captchaVerificationWelcomeMessage`, `channels`, `getUpdates`, `hideLeftMembersFromLeaderboard`, `ignoredChannels`, `joinMessage`, `joinMessageChannel`, `joinRoles`, `lang`, `leaderboardStyle`, `leaveMessage`, `leaveMessageChannel`, `logChannel`, `modLogChannel`, `modPunishmentBanDeleteMessage`, `modPunishmentKickDeleteMessage`, `modPunishmentMuteDeleteMessage`, `modPunishmentSoftbanDeleteMessage`, `modPunishmentWarnDeleteMessage`, `mutedRole`, `prefix`, `rankAnnouncementChannel`, `rankAnnouncementMessage`, `rankAssignmentStyle` |
| value | القيمة | No | الاعدادات الجديدة. |  |

#### Examples

```text
!config
```

### !createInvite

انشاء كود الدعوات فريد من نوعه.

#### Usage

```text
!createInvite <name> [channel] [maxUses] [expires] [temporaryMembership]
```

#### Aliases

* `!create-invite`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| name | نص | Yes | الاسم لكود الدعوات. |  |
| channel | القناة | No | الروم التي تم انشاء فيها الكود, تستعمل الروم الاعتيادية. |  |
| maxUses | رقم | No | `number` --&gt; The max amount of uses of the invite code |  |
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

إظهار المطورين والمساهمين في البوت.

#### Usage

```text
!credits
```

#### Examples

```text
!credits
```

### !export

اصدار ملفات الانفايت منجر لـ csv

#### Usage

```text
!export <type>
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| type | Enum | Yes | نوع الاصدار الذي تريده | Use one of the following values: `leaderboard` |

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

الحصول على رابط دعوة للبوت.

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

يعرض الرسوم البيانية حول الإحصائيات المختلفة على هذا السيرفر.

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
| type | Enum | Yes | نوع المخطط لعرضه. | Use one of the following values: `joins`, `joinsAndLeaves`, `leaves` |
| from | تاريخ | No | Start date of the chart |  |
| to | تاريخ | No | End date of the chart |  |

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

عرض المساعدة.

#### Usage

```text
!help [command]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| command | أمر | No | الرجاء اذكر الأمر الذي تريد ان تحصل معلومات عنه. | Use one of the following values: `addInvites`, `addRank`, `ban`, `botConfig`, `botInfo`, `caseDelete`, `caseView`, `check`, `clean`, `cleanShort`, `cleanText`, `clearInvites`, `config`, `createInvite`, `credits`, `export`, `fixRanks`, `getBot`, `graph`, `help`, `info`, `interactiveConfig`, `inviteCodeConfig`, `inviteCodes`, `inviteDetails`, `invites`, `kick`, `leaderboard`, `lockdown`, `memberConfig`, `members`, `mute`, `permissions`, `ping`, `prefix`, `premium`, `punishmentConfig`, `purge`, `purgeUntil`, `ranks`, `removeInvites`, `removeRank`, `restoreInvites`, `setup`, `softBan`, `strike`, `strikeConfig`, `subtractFakes`, `subtractLeaves`, `support`, `tryPremium`, `unban`, `unhoist`, `unmute`, `warn` |

#### Examples

```text
!help
```

```text
!help addRank
```

### !info

عرض معلومات حول عضو معين.

#### Usage

```text
!info <user> [details] [page]
```

#### Aliases

* `!showinfo`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | المستعمل | Yes | المستخدم الذي تريد أن ترى معلوماته إلاضافية. |  |
| details | Enum | No | اطلب معلومات معينة عن المستعمل | Use one of the following values: `bonus`, `members` |
| page | رقم | No | ما صفحة من التفاصيل لإظهار. يمكنك أيضًا استخدام ردود الفعل للتنقل. |  |

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

التكوين التفاعلي

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

اظهار وتغيير اعدادات كود الدعوات في السيرفر

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
| key | Enum | No | الاعدادات التي تريد اظهارها/تغييرها. | Use one of the following values: `name`, `roles` |
| inviteCode | رقم الدعوة | No | اعدادات كود الدعوات التي تحتاج الى تغييرها |  |
| value | القيمة | No | الاعدادات الجديدة. |  |

#### Examples

```text
!inviteCodeConfig
```

### !inviteCodes

الحصول على قائمة كل ما لديك من روابط

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

يعرض تفاصيل من اين لك دعواتك.

#### Usage

```text
!inviteDetails [user]
```

#### Aliases

* `!invite-details`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | المستعمل | No | قم بذكر المستخدم الذي تريد عرض دعوات مفصلة له. |  |

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

اظهار عدد الدعوات الخاصة.

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
| user | المستعمل | No | المستخدم الذي تريد عرض الدعوات له. |  |

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

طرد عضو من سيرفر

#### Usage

```text
!kick <member> [reason]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| member | عضو | Yes | اذكر عضو للقيام بالطرد |  |
| reason | نص | No | الرجاء قم بذكر سبب الطرد |  |

#### Examples

### !leaderboard

إظهار الأعضاء مع اعلى الدعوات.

#### Usage

```text
!leaderboard [page]
```

#### Aliases

* `!top`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| page | رقم | No | أي صفحة من المتصدرين تريد الحصول عليها. |  |

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
| channel | القناة | No | The channel that you want to lock down. |  |

#### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑timeout | ‑t | المدة الزمنية | The timeout after which the lockdown automatically ends. Run the command again to end the lockdown manually. |

#### Examples

```text
!lockdown
```

### !memberConfig

اظهر وغير الاعدادات التابعة للاعضاء في السيرفر.

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
| key | Enum | No | الاعدادات التي تحتاجها تظهر/تغير. | Use one of the following values: `hideFromLeaderboard` |
| user | المستعمل | No | اعدادات كود الدعوات تغيرت الى. |  |
| value | القيمة | No | الاعدادت الجديدة. |  |

#### Examples

```text
!memberConfig
```

### !members

إظهار عدد الأعضاء لسيرفر الحالي.

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

اسكت المستخدم

#### Usage

```text
!mute [-d value|--duration=value] <user> [reason]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | عضو | Yes | المستخدم الذي يجب اسكاته. |  |
| reason | نص | No | السبب الذي سيتم اسكات المستخدم بسببه. |  |

#### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑duration | ‑d | المدة الزمنية | The duration to mute the user for |

#### Examples

### !permissions

تهيئة الإذن ليستخدم الأوامر

#### Usage

```text
!permissions [cmd] [role]
```

#### Aliases

* `!perms`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| cmd | أمر | No | الأمر لتكوين أذونات ل. | Use one of the following values: `addInvites`, `addRank`, `ban`, `botConfig`, `botInfo`, `caseDelete`, `caseView`, `check`, `clean`, `cleanShort`, `cleanText`, `clearInvites`, `config`, `createInvite`, `credits`, `export`, `fixRanks`, `getBot`, `graph`, `help`, `info`, `interactiveConfig`, `inviteCodeConfig`, `inviteCodes`, `inviteDetails`, `invites`, `kick`, `leaderboard`, `lockdown`, `memberConfig`, `members`, `mute`, `permissions`, `ping`, `prefix`, `premium`, `punishmentConfig`, `purge`, `purgeUntil`, `ranks`, `removeInvites`, `removeRank`, `restoreInvites`, `setup`, `softBan`, `strike`, `strikeConfig`, `subtractFakes`, `subtractLeaves`, `support`, `tryPremium`, `unban`, `unhoist`, `unmute`, `warn` |
| role | وظيفة | No | الدور الذي ينبغي منحه أو رفض الوصول إلى الأمر. |  |

#### Examples

```text
!permissions
```

### !ping

بينغ الروبوت

#### Usage

```text
!ping
```

#### Examples

```text
!ping
```

### !prefix

يظهر البادئة الحالية للروبوت.

#### Usage

```text
!prefix
```

#### Examples

```text
!prefix
```

### !premium

معلومات حول الإصدار المتميز من InviteManager.

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
| action | Enum | No | العمل على التنفيذ. لا شيء للحصول على معلومات متميزة. "تحقق" للتحقق |  |
| متميزة. "تحقق" للتحقق ص بك. "تنشيط" لاستخدام قسطك لهذا الخادم. | Use one of the following values: `Activate`, `Check`, `Deactivate` |  |  |  |

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
| strikes | رقم | No | Number of strikes for this punishment to be used. |  |
| args | نص | No | Arguments passed to the punishment. |  |

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
| quantity | رقم | Yes | How many messages should be deleted. |  |
| user | المستعمل | No | User whose messages are deleted. |  |

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
| messageID | نص | Yes | Last message ID to be deleted. |  |

#### Examples

### !ranks

اظهار كل الرتب.

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
| page | رقم | No | The page of the ranks list to show. |  |

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
| user | المستعمل | Yes | The user to remove the invites from. |  |
| amount | رقم | Yes | The amount of invites to remove. |  |
| reason | نص | No | The reason for removing the invites. |  |

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

إزالة رتبة.

#### Usage

```text
!removeRank <rank>
```

#### Aliases

* `!remove-rank`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| rank | وظيفة | Yes | والتي تريد إزالة الترتيب. |  |

#### Examples

```text
!removeRank @Role
```

```text
!removeRank "Role with space"
```

### !restoreInvites

استعادة جميع الدعوات التي تم مسحها مسبقًا.

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
| user | المستعمل | No | المستخدم لاستعادة جميع يدعو ل. إذا تم حذف يستعيد يدعو لجميع المستخدمين. |  |

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
| user | عضو | Yes | User to ban. |  |
| reason | نص | No | Why was the user banned. |  |

#### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑deleteMessageDays | ‑d | رقم | Delete messages from the user this many days back. |

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
| member | عضو | Yes | The member receiving the strikes |  |
| type | Enum | Yes | The type of the violation | Use one of the following values: `allCaps`, `duplicateText`, `emojis`, `hoist`, `invites`, `links`, `mentionRoles`, `mentionUsers`, `quickMessages`, `words` |
| amount | رقم | Yes | The amount of strikes to be added |  |

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
| strikes | رقم | No | Number of strikes. |  |

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

فك الحظر من شخص.

#### Usage

```text
!unban <user> [reason]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | المستعمل | Yes | المستخدم الذي يجب فك الحظر منه. |  |
| reason | نص | No | السبب لفك حظر المستخدم. |  |

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

فك الاسكات من شخص.

#### Usage

```text
!unmute <user>
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | عضو | Yes | المستخدم الذي يجب فك اسكاته. |  |

#### Examples

### !warn

تحذير شخص.

#### Usage

```text
!warn <member> [reason]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| member | عضو | Yes | شخص ليتم تحذيره. |  |
| reason | نص | No | لماذا تم تحذير الشخص. |  |

#### Examples

