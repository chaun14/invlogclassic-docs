# Commands

## Commands

To get a list of available commands, do !help on your server.

### Arguments & Flags

Most commands accept arguments and/or flags.  
According to the **Type** of the argument or flag you can provide different values.

#### Boolean

This arguments expects `true` or `false`. You can also use `yes` and `no`.

#### Sayı

This arguments expects a number

#### Enum

This arguments expects a value from a specific set of valid values.

> Depending on the command the valid values can vary. Use `!help <command>` \(eg. `!help addRank`\) to get more information about the command and the valid values for the enum.

#### Davet Kodu

This arguments expects a Discord Invite Code.

> You can put only the part after `https://discord.gg/` to prevent Discord from creating a preview.

#### Kullanıcı

This arguments expects a Discord User. You can use any of the following methods to provide a user:

* Mention the user: `@Valandur`
* Use their ID: `102785693046026240`
* Use their name: `Valandur`
* Use their name and discriminator: `Valandur#3581`
* Use quotes if their name has a space: `"Valandur with a space"`

#### Rol

This arguments expects a Discord Role. You can use any of the following methods to provide a role:

* Mention the role: `@Admin`
* Use the ID: `102785693046026240`
* Use the name: `Admin`
* Use quotes if the name has a space: `"Admin with a space"`

#### Kanal

Bu argümanlar bir Discord Kanalı bekler. Kanal sağlamak için aşağıdaki yöntemlerden herhangi birini kullanabilirsiniz:

* Kanaldan bahsedin: `#general`
* Kanal ID kullanın: `409846838129197057`
* Kanal adını kullanın: `genel`
* Adda bir boşluk varsa tırnak işareti kullanın: `"boşluklu genel"`

#### Komut

Bu argüman bu botun bir komutunu bekliyor. Komut sağlamak için aşağıdaki yöntemlerden birini kullanabilirsiniz:

* Komut adını kullanın: `invites`
* Komutun takma adını kullanın: `p`

#### Metin

This arguments expects any text. You can use quotes \(`"Text with quotes"`\) for text that has spaces.

> If the text is the last argument you don't have to use quotes.

#### Tarih

Bu argüman bir tarih bekliyor. Çeşitli formatlar kullanabilirsiniz, ancak şunları öneririz: `YYYY-AA-GG`

#### Süre

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
| addInvites | Kullanıcıya davet puanı ekler/siler. | !addInvites \ \ \[reason\] |
| clearInvites | Sunucudaki/kullanıcıdaki davetleri temizler. | !clearInvites \[-d value\|--date=value\]\[-cb\|--clearbonus\] \[user\] |
| createInvite | Özel davet kodları oluştur. | !createInvite \ \[channel\]\[maxuses\] \[expires\]\[temporarymembership\] |
| info | Belirli bir üye hakkında bilgi göster. | !info \ \[details\]\[page\] |
| inviteCodes | Tüm davet kodlarınızın bir listesini alın | !inviteCodes |
| inviteDetails | Davetiyelerinizin nereden geldiğiyle ilgili ayrıntıları gösterir. | !inviteDetails \[user\] |
| invites | Kişi Davetlerini Göster | !invites \[user\] |
| leaderboard | En çok davet edilen üyeleri göster. | !leaderboard \[page\] |
| removeInvites | Bir kullanıcıdan belirtilen miktarda daveti kaldırır. | !removeInvites \ \ \[reason\] |
| restoreInvites | Önceden temizlenmiş tüm davetiyeleri geri yükleyin. | !restoreInvites \[user\] |
| subtractFakes | Tüm kullanıcılardan sahte davetliler temizlendi. | !subtractFakes |
| subtractLeaves | Tüm Kullanıcılardan Sunucudan Ayrılanları Sil. | !subtractLeaves |

#### Ranks

| Command | Description | Usage |
| :--- | :--- | :--- |
| addRank | Yeni bir rütbe ekle. | !addRank \ \ \[info\] |
| fixRanks | Rolün silindiği tüm rütbeleri siler. | !fixRanks |
| ranks | Tüm rütbeleri göster. | !ranks \[page\] |
| removeRank | Bir rank'ı kaldırın. | !removeRank \ |

#### Config

| Command | Description | Usage |
| :--- | :--- | :--- |
| botConfig | Botun yapılandırmasını göster ve değiştir. | !botConfig \[key\]\[value\] |
| config | Sunucunun yapılandırmasını göster ve değiştir. | !config \[key\]\[value\] |
| interactiveConfig | Etkileşimli Yapılandırma | !interactiveConfig |
| inviteCodeConfig | Sunucunun davet kodlarının yapılandırmasını gösterin ve değiştirin. | !inviteCodeConfig \[key\]\[invitecode\] \[value\] |
| memberConfig | Sunucunun üyelerinin yapılandırmasını gösterin ve değiştirin. | !memberConfig \[key\]\[user\] \[value\] |
| permissions | Komutları kullanmak için izinleri yapılandırın. | !permissions \[cmd\]\[role\] |

#### Info

| Command | Description | Usage |
| :--- | :--- | :--- |
| botInfo | Bot hakkında genel bilgi al. | !botInfo |
| credits | Bot geliştiricileri ve katkıda bulunanları göster. | !credits |
| getBot | Bot için bir davet linki al. | !getBot |
| help | Yardımı gösterir. | !help \[command\] |
| members | Geçerli sunucunun üye sayısını göster. | !members |
| ping | botun pingi | !ping |
| prefix | Botun geçerli ön-ekini gösterir. | !prefix |
| setup | Botu ayarlama ve sorunları kontrol etme konusunda yardım \(örn. Eksik izinler\) | !setup |
| support | Destek sunucumuza katılmak için davet bağlantısı alın. | !support |

#### Premium

| Command | Description | Usage |
| :--- | :--- | :--- |
| export | InviteManager verilerini bir csv sayfasına aktarın. | !export \ |
| premium | InviteManager'ın premium versiyonu hakkında bilgi edinmek. | !premium \[action\] |
| tryPremium | InviteManager'ın premium sürümünü sınırlı bir süre için ücretsiz deneyin. | !tryPremium |

#### Moderation

| Command | Description | Usage |
| :--- | :--- | :--- |
| ban | Kullanıcıyı sunucudan banlamak için. | !ban \[-d value\|--deleteMessageDays=value\] \ \[reason\] |
| caseDelete | Belirli bir durumu silin. | !caseDelete \ \[reason\] |
| caseView | Belirli bir kasa hakkındaki bilgileri görüntüleyin. | !caseView \ |
| check | Bir kullanıcının ihlal ve ceza geçmişini kontrol edin. | !check \ |
| clean | Belirli mesaj türlerinden bir kanalı temizleyin. | !clean \ \[numberOfMessages\] |
| cleanShort | Kısa mesajları temizle | !cleanShort \ \[numberOfMessages\] |
| cleanText | Belirli anahtar kelimeleri içeren iletileri sil | !cleanText \ \[numberOfMessages\] |
| kick | Sunucudan bir üyeyi atar. | !kick \ \[reason\] |
| lockdown | Lockdown a specific channel \(Prevents anyone without special roles from sending messages\) | !lockdown \[-t value\|--timeout=value\]\[channel\] |
| mute | Bir kullanıcı sustur | !mute \[-d value\|--duration=value\] \ \[reason\] |
| punishmentConfig | Configure punishments when reaching a certain amount of strikes. | !punishmentConfig \[punishment\]\[strikes\] \[args\] |
| purge | Bir kanaldaki mesajları temizleme | !purge \ \[user\] |
| purgeUntil | Bir kanaldaki mesajları belirtilen mesaja kadar temizleyin. | !purgeUntil \ |
| softBan | Ban and then automatically unban a member from the server. | !softBan \[-d value\|--deleteMessageDays=value\] \ \[reason\] |
| strike | Add strikes to a user | !strike \ \ \ |
| strikeConfig | Configure strikes received for various violations. | !strikeConfig \[violation\]\[strikes\] |
| unban | Bir kullanıcının yasağını kaldır. | !unban \ \[reason\] |
| unhoist | Tüm üyelerin önüne, adlarının önünde özel bir karakter olacak şekilde bir karakter ekleyin, böylece üye listesinin sonunda gösterilirler. | !unhoist |
| unmute | Unmute a user | !unmute \ |
| warn | Kullanıcı Uyar | !warn \ \[reason\] |

#### Other

| Command | Description | Usage |
| :--- | :--- | :--- |
| graph | Bu sunucudaki çeşitli istatistikler hakkındaki grafikleri gösterir. | !graph \ \[from\]\[to\] |

### !addInvites

Kullanıcıya davet puanı ekler/siler.

#### Usage

```text
!addInvites <user> <amount> [reason]
```

#### Aliases

* `!add-invites`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | Kullanıcı | Yes | Bonus alacak / kaybedecek kullanıcı davet eder. |  |
| amount | Sayı | Yes | Kullanıcının alacağı / kaybedeceği davet miktarı. Davetiyeleri kaldırmak için negatif \(-\) bir sayı kullanın. |  |
| reason | Metin | No | Kullanıcıya davet puanı ekleme/silme sebebi. |  |

#### Examples

```text
!addInvites @User 5
```

```text
!addInvites "Name with space" -30 Removed for cheating
```

### !addRank

Yeni bir rütbe ekle.

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
| role | Rol | Yes | Bu rütbeye geldiğinde kullanıcının alacağı rol. |  |
| invites | Sayı | Yes | Rütbeye ulaşmak için gereken davet miktarı. |  |
| info | Metin | No | Kullanıcıların göreceği bir açıklama, böylece bu rütbe hakkında daha fazla bilgi sahibi olacaklar. |  |

#### Examples

```text
!addRank @Role 5
```

```text
!addRank "Role with space" 10 Wow, already 10 people!
```

### !ban

Kullanıcıyı sunucudan banlamak için.

#### Usage

```text
!ban [-d value|--deleteMessageDays=value] <user> [reason]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | Kullanıcı | Yes | Kullanıcıyı yasaklamak için. |  |
| reason | Metin | No | Kullanıcı neden yasaklandı? |  |

#### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑deleteMessageDays | ‑d | Sayı | Belirtilirse, yasaklanan üyelerin mesajlarını bu günler önce siler. |

#### Examples

### !botConfig

Botun yapılandırmasını göster ve değiştir.

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
| key | Enum | No | Göstermek / değiştirmek istediğiniz bot yapılandırma ayarı. | Use one of the following values: `activityEnabled`, `activityMessage`, `activityStatus`, `activityType`, `activityUrl`, `embedDefaultColor` |
| value | Değer | No | Ayarın yeni değeri. |  |

#### Examples

```text
!botConfig
```

### !botInfo

Bot hakkında genel bilgi al.

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

Belirli bir durumu silin.

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
| caseNumber | Sayı | Yes | Durum numarası |  |
| reason | Metin | No | Durumu silmenin sebebi |  |

#### Examples

```text
!caseDelete 5434 User apologized
```

### !caseView

Belirli bir kasa hakkındaki bilgileri görüntüleyin.

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
| caseNumber | Sayı | Yes | Kasa numarası |  |

#### Examples

```text
!caseView 5434
```

### !check

Bir kullanıcının ihlal ve ceza geçmişini kontrol edin.

#### Usage

```text
!check <user>
```

#### Aliases

* `!history`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | Kullanıcı | Yes | Kontrol edilecek kullanıcı. |  |

#### Examples

```text
!check @User
```

```text
!check "User with space"
```

### !clean

Belirli mesaj türlerinden bir kanalı temizleyin.

#### Usage

```text
!clean <type> [numberOfMessages]
```

#### Aliases

* `!clear`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| type | Enum | Yes | Silinecek mesajların türü. | Use one of the following values: `bots`, `embeds`, `emojis`, `images`, `links`, `mentions`, `reacted`, `reactions` |
| numberOfMessages | Sayı | No | Aranacak mesaj sayısı. |  |

#### Examples

### !cleanShort

Kısa mesajları temizle

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
| maxTextLength | Sayı | Yes | Bundan kısa olan tüm mesajlar silinecektir. |  |
| numberOfMessages | Sayı | No | Aranacak mesaj sayısı. |  |

#### Examples

### !cleanText

Belirli anahtar kelimeleri içeren iletileri sil

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
| text | Metin | Yes | Bu kelimeyi içeren tüm mesajlar silinecek. |  |
| numberOfMessages | Sayı | No | Aranacak mesaj sayısı. |  |

#### Examples

### !clearInvites

Sunucudaki/kullanıcıdaki davetleri temizler.

#### Usage

```text
!clearInvites [-d value|--date=value] [-cb|--clearBonus] [user]
```

#### Aliases

* `!clear-invites`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | Kullanıcı | No | Kullanıcıdan tüm davetiyeleri temizleyecek. Atlanırsa tüm kullanıcıları temizler. |  |

#### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑date | ‑d | Tarih | Davetiyelerin sayıldığı tarih başlangıcı. Varsayılan bugün. |
| ‑‑clearBonus | ‑cb | Boolean | Bonus davetlerini de temizlemek için bu bayrağı ekleyin. Aksi takdirde bonus davetlerine dokunulmaz. |

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

Sunucunun yapılandırmasını göster ve değiştir.

#### Usage

```text
!config [key] [value]
```

#### Aliases

* `!c`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| key | Enum | No | Göstermek/değiştirmek istediğiniz yapılandırma ayarı. | Use one of the following values: `autoModAllCapsEnabled`, `autoModAllCapsMinCharacters`, `autoModAllCapsPercentageCaps`, `autoModDeleteBotMessage`, `autoModDeleteBotMessageTimeoutInSeconds`, `autoModDisabledForOldMembers`, `autoModDisabledForOldMembersThreshold`, `autoModDuplicateTextEnabled`, `autoModDuplicateTextTimeframeInSeconds`, `autoModEmojisEnabled`, `autoModEmojisMaxNumberOfEmojis`, `autoModEnabled`, `autoModHoistEnabled`, `autoModIgnoredChannels`, `autoModIgnoredRoles`, `autoModInvitesEnabled`, `autoModLinksBlacklist`, `autoModLinksEnabled`, `autoModLinksFollowRedirects`, `autoModLinksWhitelist`, `autoModLogEnabled`, `autoModMentionRolesEnabled`, `autoModMentionRolesMaxNumberOfMentions`, `autoModMentionUsersEnabled`, `autoModMentionUsersMaxNumberOfMentions`, `autoModModeratedChannels`, `autoModModeratedRoles`, `autoModQuickMessagesEnabled`, `autoModQuickMessagesNumberOfMessages`, `autoModQuickMessagesTimeframeInSeconds`, `autoModWordsBlacklist`, `autoModWordsEnabled`, `autoSubtractFakes`, `autoSubtractLeaves`, `autoSubtractLeaveThreshold`, `captchaVerificationFailedMessage`, `captchaVerificationLogEnabled`, `captchaVerificationOnJoin`, `captchaVerificationSuccessMessage`, `captchaVerificationTimeout`, `captchaVerificationWelcomeMessage`, `channels`, `getUpdates`, `hideLeftMembersFromLeaderboard`, `ignoredChannels`, `joinMessage`, `joinMessageChannel`, `joinRoles`, `lang`, `leaderboardStyle`, `leaveMessage`, `leaveMessageChannel`, `logChannel`, `modLogChannel`, `modPunishmentBanDeleteMessage`, `modPunishmentKickDeleteMessage`, `modPunishmentMuteDeleteMessage`, `modPunishmentSoftbanDeleteMessage`, `modPunishmentWarnDeleteMessage`, `mutedRole`, `prefix`, `rankAnnouncementChannel`, `rankAnnouncementMessage`, `rankAssignmentStyle` |
| value | Değer | No | Ayarın yeni değeri. |  |

#### Examples

```text
!config
```

### !createInvite

Özel davet kodları oluştur.

#### Usage

```text
!createInvite <name> [channel] [maxUses] [expires] [temporaryMembership]
```

#### Aliases

* `!create-invite`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| name | Metin | Yes | Davet kodunun adı. |  |
| channel | Kanal | No | Davet kodunun oluşturulduğu kanal. Geçerli kanalı varsayılan olarak kullanır. |  |
| maxUses | Sayı | No | `number` --&gt; The max amount of uses of the invite code |  |
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

Bot geliştiricileri ve katkıda bulunanları göster.

#### Usage

```text
!credits
```

#### Examples

```text
!credits
```

### !export

InviteManager verilerini bir csv sayfasına aktarın.

#### Usage

```text
!export <type>
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| type | Enum | Yes | İstediğiniz dışa aktarma türü. | Use one of the following values: `leaderboard` |

#### Examples

```text
!export leaderboard
```

### !fixRanks

Rolün silindiği tüm rütbeleri siler.

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

Bot için bir davet linki al.

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

Bu sunucudaki çeşitli istatistikler hakkındaki grafikleri gösterir.

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
| type | Enum | Yes | Gösterilecek tablonun türü. | Use one of the following values: `joins`, `joinsAndLeaves`, `leaves` |
| from | Tarih | No | Grafiğin başlangıç tarihi |  |
| to | Tarih | No | Grafiğin bitiş tarihi |  |

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

Yardımı gösterir.

#### Usage

```text
!help [command]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| command | Komut | No | Hakkında ayrıntılı bilgi alma komutu. | Use one of the following values: `addInvites`, `addRank`, `ban`, `botConfig`, `botInfo`, `caseDelete`, `caseView`, `check`, `clean`, `cleanShort`, `cleanText`, `clearInvites`, `config`, `createInvite`, `credits`, `export`, `fixRanks`, `getBot`, `graph`, `help`, `info`, `interactiveConfig`, `inviteCodeConfig`, `inviteCodes`, `inviteDetails`, `invites`, `kick`, `leaderboard`, `lockdown`, `memberConfig`, `members`, `mute`, `permissions`, `ping`, `prefix`, `premium`, `punishmentConfig`, `purge`, `purgeUntil`, `ranks`, `removeInvites`, `removeRank`, `restoreInvites`, `setup`, `softBan`, `strike`, `strikeConfig`, `subtractFakes`, `subtractLeaves`, `support`, `tryPremium`, `unban`, `unhoist`, `unmute`, `warn` |

#### Examples

```text
!help
```

```text
!help addRank
```

### !info

Belirli bir üye hakkında bilgi göster.

#### Usage

```text
!info <user> [details] [page]
```

#### Aliases

* `!showinfo`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | Kullanıcı | Yes | Ek bilgi görmek istediğiniz kullanıcı. |  |
| details | Enum | No | Bir üye hakkında sadece belirli detayları isteyin. | Use one of the following values: `bonus`, `members` |
| page | Sayı | No | Ayrıntıların hangi sayfasında gösterileceği. Reaksiyonlarda gezinmek için de kullanabilirsiniz. |  |

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

Etkileşimli Yapılandırma

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

Sunucunun davet kodlarının yapılandırmasını gösterin ve değiştirin.

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
| key | Enum | No | Göstermek / değiştirmek istediğiniz yapılandırma ayarı. | Use one of the following values: `name`, `roles` |
| inviteCode | Davet Kodu | No | Ayarlarını değiştirmek istediğiniz davet kodu. |  |
| value | Değer | No | Ayarın yeni değeri |  |

#### Examples

```text
!inviteCodeConfig
```

### !inviteCodes

Tüm davet kodlarınızın bir listesini alın

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

Davetiyelerinizin nereden geldiğiyle ilgili ayrıntıları gösterir.

#### Usage

```text
!inviteDetails [user]
```

#### Aliases

* `!invite-details`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | Kullanıcı | No | Ayrıntılı davetler göstermek istediğiniz kullanıcı. |  |

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

Kişi Davetlerini Göster

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
| user | Kullanıcı | No | Kendisini göstermek istediğiniz kullanıcı davet ediyor. |  |

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

Sunucudan bir üyeyi atar.

#### Usage

```text
!kick <member> [reason]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| member | Üye | Yes | Kullanıcı Atıldı. |  |
| reason | Metin | No | Kullanıcının Atılma Sebebi |  |

#### Examples

### !leaderboard

En çok davet edilen üyeleri göster.

#### Usage

```text
!leaderboard [page]
```

#### Aliases

* `!top`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| page | Sayı | No | Afiş almak için hangi sayfa. |  |

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
| channel | Kanal | No | Kilitlemek istediğiniz kanal. |  |

#### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑timeout | ‑t | Süre | Kilitlemenin otomatik olarak sona erdiği zaman aşımı süresi. Kilidi manuel olarak sonlandırmak için komutu tekrar çalıştırın. |

#### Examples

```text
!lockdown
```

### !memberConfig

Sunucunun üyelerinin yapılandırmasını gösterin ve değiştirin.

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
| key | Enum | No | Göstermek / değiştirmek istediğiniz üye yapılandırma ayarı. | Use one of the following values: `hideFromLeaderboard` |
| user | Kullanıcı | No | Ayarın gösterildiği / değiştirildiği üye. |  |
| value | Değer | No | Ayarın yeni değeri. |  |

#### Examples

```text
!memberConfig
```

### !members

Geçerli sunucunun üye sayısını göster.

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

Bir kullanıcı sustur

#### Usage

```text
!mute [-d value|--duration=value] <user> [reason]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | Üye | Yes | Susturulması gereken kullanıcı. |  |
| reason | Metin | No | Bu kullanıcının susturulmuş olmasının nedeni. |  |

#### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑duration | ‑d | Süre | Kullanıcının susturulma süresi |

#### Examples

### !permissions

Komutları kullanmak için izinleri yapılandırın.

#### Usage

```text
!permissions [cmd] [role]
```

#### Aliases

* `!perms`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| cmd | Komut | No | Komut, izinleri yapılandırma için | Use one of the following values: `addInvites`, `addRank`, `ban`, `botConfig`, `botInfo`, `caseDelete`, `caseView`, `check`, `clean`, `cleanShort`, `cleanText`, `clearInvites`, `config`, `createInvite`, `credits`, `export`, `fixRanks`, `getBot`, `graph`, `help`, `info`, `interactiveConfig`, `inviteCodeConfig`, `inviteCodes`, `inviteDetails`, `invites`, `kick`, `leaderboard`, `lockdown`, `memberConfig`, `members`, `mute`, `permissions`, `ping`, `prefix`, `premium`, `punishmentConfig`, `purge`, `purgeUntil`, `ranks`, `removeInvites`, `removeRank`, `restoreInvites`, `setup`, `softBan`, `strike`, `strikeConfig`, `subtractFakes`, `subtractLeaves`, `support`, `tryPremium`, `unban`, `unhoist`, `unmute`, `warn` |
| role | Rol | No | Komuta erişim izni verilmesi veya reddedilmesi gereken rol. |  |

#### Examples

```text
!permissions
```

### !ping

botun pingi

#### Usage

```text
!ping
```

#### Examples

```text
!ping
```

### !prefix

Botun geçerli ön-ekini gösterir.

#### Usage

```text
!prefix
```

#### Examples

```text
!prefix
```

### !premium

InviteManager'ın premium versiyonu hakkında bilgi edinmek.

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
| action | Enum | No | Gerçekleştirilecek eylem. Premium bilgi için yok. Premium durumunuzu kontrol etmek için `check`. bu sunucu için priminizi kullanmak için `activate` . | Use one of the following values: `Activate`, `Check`, `Deactivate` |

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
| punishment | Enum | No | Kullanılacak cezalandırma türü. | Use one of the following values: `ban`, `kick`, `mute`, `softban`, `warn` |
| strikes | Sayı | No | Bu cezalandırma için kullanılacak ihtar sayısı. |  |
| args | Metin | No | İddialar cezaya geçti. |  |

#### Examples

```text
!punishmentConfig
```

### !purge

Bir kanaldaki mesajları temizleme

#### Usage

```text
!purge <quantity> [user]
```

#### Aliases

* `!prune`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| quantity | Sayı | Yes | Kaç mesaj silinmelidir. |  |
| user | Kullanıcı | No | Mesajları silinmiş olan kullanıcı. |  |

#### Examples

### !purgeUntil

Bir kanaldaki mesajları belirtilen mesaja kadar temizleyin.

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
| messageID | Metin | Yes | Silinecek son mesaj ID'si |  |

#### Examples

### !ranks

Tüm rütbeleri göster.

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
| page | Sayı | No | Gösterilecek sıralama listesinin sayfası |  |

#### Examples

```text
!ranks
```

### !removeInvites

Bir kullanıcıdan belirtilen miktarda daveti kaldırır.

#### Usage

```text
!removeInvites <user> <amount> [reason]
```

#### Aliases

* `!remove-invites`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | Kullanıcı | Yes | Davetlerin kaldırılacağı kullanıcı. |  |
| amount | Sayı | Yes | Kaldırılacak davetlerin sayısı. |  |
| reason | Metin | No | Davetlerin kaldırılmasının nedeni. |  |

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

Bir rank'ı kaldırın.

#### Usage

```text
!removeRank <rank>
```

#### Aliases

* `!remove-rank`

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| rank | Rol | Yes | Sırasını kaldırmak istediğiniz. |  |

#### Examples

```text
!removeRank @Role
```

```text
!removeRank "Role with space"
```

### !restoreInvites

Önceden temizlenmiş tüm davetiyeleri geri yükleyin.

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
| user | Kullanıcı | No | Tüm davetleri geri yükleyecek kullanıcı. Atlanırsa tüm kullanıcılar için davetleri geri yükler. |  |

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

Botu ayarlama ve sorunları kontrol etme konusunda yardım \(örn. Eksik izinler\)

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
| user | Üye | Yes | Kullanıcı Yasaklamak. |  |
| reason | Metin | No | Kullanıcı neden yasaklandı ? |  |

#### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑deleteMessageDays | ‑d | Sayı | Kullanıcının bu kadar gün önceki mesajlarını silin. |

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
| member | Üye | Yes | Vuruşları alan üye |  |
| type | Enum | Yes | The type of the violation | Use one of the following values: `allCaps`, `duplicateText`, `emojis`, `hoist`, `invites`, `links`, `mentionRoles`, `mentionUsers`, `quickMessages`, `words` |
| amount | Sayı | Yes | The amount of strikes to be added |  |

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
| violation | Enum | No | İhlal türü. | Use one of the following values: `allCaps`, `duplicateText`, `emojis`, `hoist`, `invites`, `links`, `mentionRoles`, `mentionUsers`, `quickMessages`, `words` |
| strikes | Sayı | No | Number of strikes. |  |

#### Examples

```text
!strikeConfig
```

### !subtractFakes

Tüm kullanıcılardan sahte davetliler temizlendi.

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

Tüm Kullanıcılardan Sunucudan Ayrılanları Sil.

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

Destek sunucumuza katılmak için davet bağlantısı alın.

#### Usage

```text
!support
```

#### Examples

```text
!support
```

### !tryPremium

InviteManager'ın premium sürümünü sınırlı bir süre için ücretsiz deneyin.

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

Bir kullanıcının yasağını kaldır.

#### Usage

```text
!unban <user> [reason]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | Kullanıcı | Yes | Yasağının kaldırılması gereken kullanıcı |  |
| reason | Metin | No | Bu kullanıcının yasaklanmasının nedeni. |  |

#### Examples

### !unhoist

Tüm üyelerin önüne, adlarının önünde özel bir karakter olacak şekilde bir karakter ekleyin, böylece üye listesinin sonunda gösterilirler.

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
| user | Üye | Yes | Susturulması gereken kullanıcı |  |

#### Examples

### !warn

Kullanıcı Uyar

#### Usage

```text
!warn <member> [reason]
```

#### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| member | Üye | Yes | Member to warn. |  |
| reason | Metin | No | Üye neden uyarıldı ? |  |

#### Examples

