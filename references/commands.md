# Commandes

To get a list of available commands, do !help on your server.

## Arguments & Flags

Most commands accept arguments and/or flags.  
According to the **Type** of the argument or flag you can provide different values.

### Booléen

Cet argument prend la valeur `vrai` ou `faux`. Vous pouvez aussi utiliser `oui` ou `non`.

### Nombre

Veuillez spécifier un nombre

### Énumération

Cet argument attend une valeur d'une liste spécifique de valeurs.

> Selon la commande les valeurs valides peuvent changer. Utilisez `!help <command>` \(ex : `!help addRank`\) pour avoir plus d'informations sur la commande et les valeurs valides pour cette commande.

### Code d'invitation

Cet argument attend un code d'invitation Discord.

> Vous pouvez donner uniquement le code après `https://discord.gg/` pour annuler l'aperçu créé par Discord.

### Utilisateur

Cet argument attend un utilisateur Discord. Vous pouvez utiliser une de ces méthodes pour donner un utilisateur :

* Mentionner l'utilisateur `@Valandur`
* Utiliser l'ID : `102785693046026240`
* Utiliser le nom : `Valandur`
* Utiliser des guillemets si le nom contient un espace : `"Valandur avec des espaces"`

### Role

Cet argument attend un role Discord. Vous pouvez utiliser une de ces méthodes pour donner un role :

* Mentionner le role `@Admin`
* Utiliser l'ID : `102785693046026240`
* Utiliser le nom : `Admin`
* Utiliser des guillemets si le nom contient un espace : `"Admin avec des espaces"`

### Salon

Cet argument attend un salon Discord. Vous pouvez utiliser une de ces méthodes pour donner un salon :

* Mentionner le salon `#general`
* Utiliser l'ID : `409846838129197057`
* Utiliser le nom : `general`
* Utiliser des guillemets si le nom contient un espace : `"general avec des espaces"`

### Commande

Cet argument attend une commande de ce bot. Vous pouvez utiliser une de ces méthodes pour donner une commande :

* Utiliser le nom de la commande : `invites`
* Utiliser un alias de la commande : `p`

### Texte

Cet argument attend du texte. Vous pouvez utiliser des guillemets \(\`"Texte avec des guillemets"\) pour du texte avec des espaces.

> Si le texte est le dernier argument vous n'avez pas besoin d'utiliser des guillemets.

### Date

Cet argument attend une date. Vous pouvez utiliser différents formats, mais nous recommandons : `YYYY-MM-DD`

### Durée

Cet argument attend une durée. Les durées suivantes sont supportées :

* Secondes : `s` \(`5s` = 5 secondes\)
* Minutes : `min` \(`3min` = 3 minutes\)
* Heures : `h` \(`4h` = 4 heures\)
* Jours : `d` \(`2d` = 2 jours\)
* Semaines : `w` \(`1w` = 1 semaine\)
* Mois : `mo` \(`6mo` = 6 mois\)
* Années : `y` \(`10y` = 10 ans\)

## Overview

### Invites

| Command | Description | Usage |
| :--- | :--- | :--- |
| [addInvites](commands.md#addInvites) | Ajoute/supprime des invitations d'un membre. | !addInvites \ \ \[reason\] |
| [clearInvites](commands.md#clearInvites) | Effacer les invitations du serveur/d'un utilisateur. | !clearInvites \[-d value\|--date=value\]\[-cb\|--clearbonus\] \[user\] |
| [createInvite](commands.md#createInvite) | Crée des codes d'invitation uniques. | !createInvite \ \[channel\]\[maxuses\] \[expires\]\[temporarymembership\] |
| [info](commands.md#info) | Afficher des informations sur un membre spécifique. | !info \ \[details\]\[page\] |
| [inviteCodes](commands.md#inviteCodes) | Obtenez une liste de tous vos codes d'invitation. | !inviteCodes |
| [inviteDetails](commands.md#inviteDetails) | Affiche des détails sur l'origine de vos invitations. | !inviteDetails \[user\] |
| [invites](commands.md#invites) | Afficher les invitations personnelles. | !invites \[user\] |
| [leaderboard](commands.md#leaderboard) | Afficher les membres avec le plus d'invitations. | !leaderboard \[page\] |
| [removeInvites](commands.md#removeInvites) | Enlève un certain nombre d'invitations à un utilisateur. | !removeInvites \ \ \[reason\] |
| [restoreInvites](commands.md#restoreInvites) | Restaurez toutes les invitations précédemment effacées. | !restoreInvites \[user\] |
| [subtractFakes](commands.md#subtractFakes) | Supprimez les fausses invitations de tous les utilisateurs. | !subtractFakes |
| [subtractLeaves](commands.md#subtractLeaves) | Supprimer le nombre des invitations des personne qui ont quitter de tous les utilisateurs. | !subtractLeaves |

### Ranks

| Command | Description | Usage |
| :--- | :--- | :--- |
| [addRank](commands.md#addRank) | Ajouter un nouveau Ranks. | !addRank \ \ \[info\] |
| [fixRanks](commands.md#fixRanks) | Supprime les rangs configurés si le rôle a été supprimé. | !fixRanks |
| [ranks](commands.md#ranks) | Montrer tous les rangs. | !ranks \[page\] |
| [removeRank](commands.md#removeRank) | Supprimer un rang. | !removeRank \ |

### Config

| Command | Description | Usage |
| :--- | :--- | :--- |
| [botConfig](commands.md#botConfig) | Afficher et changer la configuration du bot. | !botConfig \[key\]\[value\] |
| [config](commands.md#config) | Affiche et modifie la configuration du serveur. | !config \[key\]\[value\] |
| [interactiveConfig](commands.md#interactiveConfig) | Configuration interactive | !interactiveConfig |
| [inviteCodeConfig](commands.md#inviteCodeConfig) | Affiche et modifie la configuration des codes d'invitation du serveur. | !inviteCodeConfig \[key\]\[invitecode\] \[value\] |
| [memberConfig](commands.md#memberConfig) | Affiche et modifie la configuration des membres du serveur. | !memberConfig \[key\]\[user\] \[value\] |
| [permissions](commands.md#permissions) | Configurez les permissions pour utiliser des commandes. | !permissions \[cmd\]\[role\] |

### Info

| Command | Description | Usage |
| :--- | :--- | :--- |
| [botInfo](commands.md#botInfo) | Obtenez des informations à propos du bot. | !botInfo |
| [credits](commands.md#credits) | Afficher les développeurs et les contributeurs du bot. | !credits |
| [getBot](commands.md#getBot) | Obtenez un lien d'invitation pour le bot. | !getBot |
| [help](commands.md#help) | Afficher l'aide. | !help \[command\] |
| [members](commands.md#members) | Afficher le nombre de membres du serveur actuel. | !members |
| [ping](commands.md#ping) | Mentionner le bot | !ping |
| [prefix](commands.md#prefix) | Affiche le préfixe actuel du bot. | !prefix |
| [setup](commands.md#setup) | Aide à la configuration du bot et à la recherche de problèmes \(par exemple: autorisations manquantes\) | !setup |
| [support](commands.md#support) | Obtenez un lien d'invitation vers notre serveur d'assistance. | !support |

### Premium

| Command | Description | Usage |
| :--- | :--- | :--- |
| [export](commands.md#export) | Exportez les données d'InviteManager vers une feuille de calculs CSV. | !export \ |
| [premium](commands.md#premium) | Informations sur la version premium d'InviteManager. | !premium \[action\] |
| [tryPremium](commands.md#tryPremium) | Essayez gratuitement la version premium d’InviteManager pour une durée limitée. | !tryPremium |

### Moderation

| Command | Description | Usage |
| :--- | :--- | :--- |
| [ban](commands.md#ban) | Bannir un membre du serveur. | !ban \[-d value\|--deleteMessageDays=value\] \ \[reason\] |
| [caseDelete](commands.md#caseDelete) | Supprimer un cas spécifique. | !caseDelete \ \[reason\] |
| [caseView](commands.md#caseView) | Voir les informations sur un cas spécifique. | !caseView \ |
| [check](commands.md#check) | Vérifier la violation et l'historique des punitions d'un utilisateur. | !check \ |
| [clean](commands.md#clean) | Nettoyer un salon de certains messages. | !clean \ \[numberOfMessages\] |
| [cleanShort](commands.md#cleanShort) | Effacer les messages courts. | !cleanShort \ \[numberOfMessages\] |
| [cleanText](commands.md#cleanText) | Supprimer les messages contenant certains mots clefs. | !cleanText \ \[numberOfMessages\] |
| [kick](commands.md#kick) | Expulser un membre du serveur. | !kick \ \[reason\] |
| [lockdown](commands.md#lockdown) | Bloque un salon spécifique \(empêche tout le monde sans rôle spécial d'envoyer des messages\) | !lockdown \[-t value\|--timeout=value\]\[channel\] |
| [mute](commands.md#mute) | Rendre muet un utilisateur | !mute \[-d value\|--duration=value\] \ \[reason\] |
| [punishmentConfig](commands.md#punishmentConfig) | Configurez les punitions lorsque vous atteignez un certain nombre d'avertissements. | !punishmentConfig \[punishment\]\[strikes\] \[args\] |
| [purge](commands.md#purge) | Purger les messages dans un canal. | !purge \ \[user\] |
| [purgeUntil](commands.md#purgeUntil) | Purger les messages dans un salon jusqu'à un message spécifié. | !purgeUntil \ |
| [softBan](commands.md#softBan) | Bannir puis automatiquement dé-bannir un membre du serveur. | !softBan \[-d value\|--deleteMessageDays=value\] \ \[reason\] |
| [strike](commands.md#strike) | Ajouter des avertissements à un utilisateur | !strike \ \ \ |
| [strikeConfig](commands.md#strikeConfig) | Configurez les Strike reçues pour diverses violations. | !strikeConfig \[violation\]\[strikes\] |
| [unban](commands.md#unban) | Dé-bannir un utilisateur | !unban \ \[reason\] |
| [unhoist](commands.md#unhoist) | Ajoute un caractère spécial devant le nom de chaque membre, donc ils seront affichés en dernier de la liste des membres. | !unhoist |
| [unmute](commands.md#unmute) | Démuter un utilisateur | !unmute \ |
| [warn](commands.md#warn) | Avertir un membre. | !warn \ \[reason\] |

### Other

| Command | Description | Usage |
| :--- | :--- | :--- |
| [graph](commands.md#graph) | Affiche des graphiques sur différentes statistiques sur ce serveur. | !graph \ \[from\]\[to\] |

## !addInvites

Ajoute/supprime des invitations d'un membre.

### Usage

```text
!addInvites <user> <amount> [reason]
```

### Aliases

* `!add-invites`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | [Utilisateur](commands.md#Utilisateur) | Yes | L'utilisateur recevra / perdra le bonus invite |  |
| amount | [Nombre](commands.md#Nombre) | Yes | La quantité d'invitations que l'utilisateur va recevoir / perdre. Utilisez un nombre négatif \(-\) pour supprimer les invitations. |  |
| reason | [Texte](commands.md#Texte) | No | La raison de l'ajout / suppression des invitations. |  |

### Examples

```text
!addInvites @User 5
```

```text
!addInvites "Name with space" -30 Removed for cheating
```

## !addRank

Ajouter un nouveau Ranks.

### Usage

```text
!addRank <role> <invites> [info]
```

### Aliases

* `!add-rank`
* `!set-rank`
* `!setrank`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| role | [Role](commands.md#Role) | Yes | Le rôle que l'utilisateur recevra lorsqu'il atteindra ce rang. |  |
| invites | [Nombre](commands.md#Nombre) | Yes | La quantité d'invitations nécessaires pour atteindre le rang. |  |
| info | [Texte](commands.md#Texte) | No | Une description que les utilisateurs verront pour en savoir plus sur ce rang. |  |

### Examples

```text
!addRank @Role 5
```

```text
!addRank "Role with space" 10 Wow, already 10 people!
```

## !ban

Bannir un membre du serveur.

### Usage

```text
!ban [-d value|--deleteMessageDays=value] <user> [reason]
```

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | [Utilisateur](commands.md#Utilisateur) | Yes | Utilisateur à bannir. |  |
| reason | [Texte](commands.md#Texte) | No | Pourquoi l'utilisateur a-t-il été banni? |  |

### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑deleteMessageDays | ‑d | [Nombre](commands.md#Nombre) | Si spécifié, cela va supprimer les messages du membre banni ce nombre de jours en arrière. |

### Examples

## !botConfig

Afficher et changer la configuration du bot.

### Usage

```text
!botConfig [key] [value]
```

### Aliases

* `!bot-config`
* `!botsetting`
* `!bot-setting`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| key | [Énumération](commands.md#Énumération) | No | Les paramètres de configurations que vous souhaitez afficher / modifier. | Utilisez une des valeurs suivantes : `activityEnabled`, `activityMessage`, `activityStatus`, `activityType`, `activityUrl`, `embedDefaultColor` |
| value | [Valeur](commands.md#Valeur) | No | La nouvelle valeur du paramètre. |  |

### Examples

```text
!botConfig
```

## !botInfo

Obtenez des informations à propos du bot.

### Usage

```text
!botInfo
```

### Aliases

* `!bot-info`

### Examples

```text
!botInfo
```

## !caseDelete

Supprimer un cas spécifique.

### Usage

```text
!caseDelete <caseNumber> [reason]
```

### Aliases

* `!case-delete`
* `!deletecase`
* `!delete-case`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| caseNumber | [Nombre](commands.md#Nombre) | Yes | Numéro du cas |  |
| reason | [Texte](commands.md#Texte) | No | La raison de la suppression du cas. |  |

### Examples

```text
!caseDelete 5434 User apologized
```

## !caseView

Voir les informations sur un cas spécifique.

### Usage

```text
!caseView <caseNumber>
```

### Aliases

* `!case-view`
* `!viewcase`
* `!view-case`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| caseNumber | [Nombre](commands.md#Nombre) | Yes | Numéro du cas |  |

### Examples

```text
!caseView 5434
```

## !check

Vérifier la violation et l'historique des punitions d'un utilisateur.

### Usage

```text
!check <user>
```

### Aliases

* `!history`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | [Utilisateur](commands.md#Utilisateur) | Yes | Utilisateur à vérifier. |  |

### Examples

```text
!check @User
```

```text
!check "User with space"
```

## !clean

Nettoyer un salon de certains messages.

### Usage

```text
!clean <type> [numberOfMessages]
```

### Aliases

* `!clear`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| type | [Énumération](commands.md#Énumération) | Yes | Le type de messages qui seront supprimés. | Utilisez une des valeurs suivantes : `bots`, `embeds`, `emojis`, `images`, `links`, `mentions`, `reacted`, `reactions` |
| numberOfMessages | [Nombre](commands.md#Nombre) | No | Nombre de messages qui seront recherchés. |  |

### Examples

## !cleanShort

Effacer les messages courts.

### Usage

```text
!cleanShort <maxTextLength> [numberOfMessages]
```

### Aliases

* `!clean-short`
* `!clearshort`
* `!clear-short`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| maxTextLength | [Nombre](commands.md#Nombre) | Yes | Tous les messages plus courts que ça seront supprimés. |  |
| numberOfMessages | [Nombre](commands.md#Nombre) | No | Nombre de messages qui seront recherchés. |  |

### Examples

## !cleanText

Supprimer les messages contenant certains mots clefs.

### Usage

```text
!cleanText <text> [numberOfMessages]
```

### Aliases

* `!clean-text`
* `!cleartext`
* `!clear-text`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| text | [Texte](commands.md#Texte) | Yes | Tous les messages contenants ce mot seront supprimés. |  |
| numberOfMessages | [Nombre](commands.md#Nombre) | No | Nombre de messages qui seront recherchés. |  |

### Examples

## !clearInvites

Effacer les invitations du serveur/d'un utilisateur.

### Usage

```text
!clearInvites [-d value|--date=value] [-cb|--clearBonus] [user]
```

### Aliases

* `!clear-invites`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | [Utilisateur](commands.md#Utilisateur) | No | L'utilisateur que vous voulez effacer toutes ses invitations. Si pas renseigner, efface les invitations de tous les utilisateurs. |  |

### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑date | ‑d | [Date](commands.md#Date) | La date à laquelle les invitations doivent être comptées. La valeur par défaut est aujourd'hui. |
| ‑‑clearBonus | ‑cb | [Booléen](commands.md#Booléen) | Ajouter ce drapeau pour effacer aussi les invitations bonus. Sinon, les invitations bonus ne seront pas altérées. |

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

## !config

Affiche et modifie la configuration du serveur.

### Usage

```text
!config [key] [value]
```

### Aliases

* `!c`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| key | [Énumération](commands.md#Énumération) | No | Le paramètre de configuration que vous souhaitez afficher / modifier. | Utilisez une des valeurs suivantes : `autoModAllCapsEnabled`, `autoModAllCapsMinCharacters`, `autoModAllCapsPercentageCaps`, `autoModDeleteBotMessage`, `autoModDeleteBotMessageTimeoutInSeconds`, `autoModDisabledForOldMembers`, `autoModDisabledForOldMembersThreshold`, `autoModDuplicateTextEnabled`, `autoModDuplicateTextTimeframeInSeconds`, `autoModEmojisEnabled`, `autoModEmojisMaxNumberOfEmojis`, `autoModEnabled`, `autoModHoistEnabled`, `autoModIgnoredChannels`, `autoModIgnoredRoles`, `autoModInvitesEnabled`, `autoModLinksBlacklist`, `autoModLinksEnabled`, `autoModLinksFollowRedirects`, `autoModLinksWhitelist`, `autoModLogEnabled`, `autoModMentionRolesEnabled`, `autoModMentionRolesMaxNumberOfMentions`, `autoModMentionUsersEnabled`, `autoModMentionUsersMaxNumberOfMentions`, `autoModModeratedChannels`, `autoModModeratedRoles`, `autoModQuickMessagesEnabled`, `autoModQuickMessagesNumberOfMessages`, `autoModQuickMessagesTimeframeInSeconds`, `autoModWordsBlacklist`, `autoModWordsEnabled`, `autoSubtractFakes`, `autoSubtractLeaves`, `autoSubtractLeaveThreshold`, `captchaVerificationFailedMessage`, `captchaVerificationLogEnabled`, `captchaVerificationOnJoin`, `captchaVerificationSuccessMessage`, `captchaVerificationTimeout`, `captchaVerificationWelcomeMessage`, `channels`, `getUpdates`, `hideLeftMembersFromLeaderboard`, `ignoredChannels`, `joinMessage`, `joinMessageChannel`, `joinRoles`, `lang`, `leaderboardStyle`, `leaveMessage`, `leaveMessageChannel`, `logChannel`, `modLogChannel`, `modPunishmentBanDeleteMessage`, `modPunishmentKickDeleteMessage`, `modPunishmentMuteDeleteMessage`, `modPunishmentSoftbanDeleteMessage`, `modPunishmentWarnDeleteMessage`, `mutedRole`, `prefix`, `rankAnnouncementChannel`, `rankAnnouncementMessage`, `rankAssignmentStyle` |
| value | [Valeur](commands.md#Valeur) | No | La nouvelle valeur du paramétrage. |  |

### Examples

```text
!config
```

## !createInvite

Crée des codes d'invitation uniques.

### Usage

```text
!createInvite <name> [channel] [maxUses] [expires] [temporaryMembership]
```

### Aliases

* `!create-invite`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| name | [Texte](commands.md#Texte) | Yes | Le nom du code d'invitation. |  |
| channel | [Salon](commands.md#Salon) | No | Le Salon ou le code d'invitation est créé. Utilise le canal actuel par défaut. |  |
| maxUses | [Nombre](commands.md#Nombre) | No | `number` --&gt; The max amount of uses of the invite code |  |
| expires | [Booléen](commands.md#Booléen) | No | `true` or `false` --&gt; Set if the invite will expires after 24 hours |  |
| temporaryMembership | [Booléen](commands.md#Booléen) | No | `true` or `false` --&gt; Set if the invited users are granted as temporary members |  |

### Examples

```text
!createInvite reddit
```

```text
!createInvite website #welcome
```

## !credits

Afficher les développeurs et les contributeurs du bot.

### Usage

```text
!credits
```

### Examples

```text
!credits
```

## !export

Exportez les données d'InviteManager vers une feuille de calculs CSV.

### Usage

```text
!export <type>
```

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| type | [Énumération](commands.md#Énumération) | Yes | Le type d'exportation que vous voulez. | Utilisez une des valeurs suivantes : `leaderboard` |

### Examples

```text
!export leaderboard
```

## !fixRanks

Supprime les rangs configurés si le rôle a été supprimé.

### Usage

```text
!fixRanks
```

### Aliases

* `!fix-ranks`

### Examples

```text
!fixRanks
```

## !getBot

Obtenez un lien d'invitation pour le bot.

### Usage

```text
!getBot
```

### Aliases

* `!get-bot`
* `!invite-bot`
* `!invitebot`

### Examples

```text
!getBot
```

## !graph

Affiche des graphiques sur différentes statistiques sur ce serveur.

### Usage

```text
!graph <type> [from] [to]
```

### Aliases

* `!g`
* `!chart`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| type | [Énumération](commands.md#Énumération) | Yes | Le type de graphique à afficher. | Utilisez une des valeurs suivantes : `joins`, `joinsAndLeaves`, `leaves` |
| from | [Date](commands.md#Date) | No | Date de début du graphique |  |
| to | [Date](commands.md#Date) | No | Date de fin du graphique |  |

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

## !help

Afficher l'aide.

### Usage

```text
!help [command]
```

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| command | [Commande](commands.md#Commande) | No | La commande pour obtenir des informations détaillées pour. | Utilisez une des valeurs suivantes : `addInvites`, `addRank`, `ban`, `botConfig`, `botInfo`, `caseDelete`, `caseView`, `check`, `clean`, `cleanShort`, `cleanText`, `clearInvites`, `config`, `createInvite`, `credits`, `export`, `fixRanks`, `getBot`, `graph`, `help`, `info`, `interactiveConfig`, `inviteCodeConfig`, `inviteCodes`, `inviteDetails`, `invites`, `kick`, `leaderboard`, `lockdown`, `memberConfig`, `members`, `mute`, `permissions`, `ping`, `prefix`, `premium`, `punishmentConfig`, `purge`, `purgeUntil`, `ranks`, `removeInvites`, `removeRank`, `restoreInvites`, `setup`, `softBan`, `strike`, `strikeConfig`, `subtractFakes`, `subtractLeaves`, `support`, `tryPremium`, `unban`, `unhoist`, `unmute`, `warn` |

### Examples

```text
!help
```

```text
!help addRank
```

## !info

Afficher des informations sur un membre spécifique.

### Usage

```text
!info <user> [details] [page]
```

### Aliases

* `!showinfo`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | [Utilisateur](commands.md#Utilisateur) | Yes | L'utilisateur pour lequel vous souhaitez voir des informations supplémentaires. |  |
| details | [Énumération](commands.md#Énumération) | No | Voir uniquement des détails spécifiques d'un membre. | Utilisez une des valeurs suivantes : `bonus`, `members` |
| page | [Nombre](commands.md#Nombre) | No | Quelle page des détails afficher. Vous pouvez aussi utiliser les réactions pour naviguer. |  |

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

## !interactiveConfig

Configuration interactive

### Usage

```text
!interactiveConfig
```

### Aliases

* `!ic`

### Examples

```text
!interactiveConfig
```

## !inviteCodeConfig

Affiche et modifie la configuration des codes d'invitation du serveur.

### Usage

```text
!inviteCodeConfig [key] [inviteCode] [value]
```

### Aliases

* `!invite-code-config`
* `!icc`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| key | [Énumération](commands.md#Énumération) | No | Les paramètres de configurations que vous souhaitez afficher / modifier. | Utilisez une des valeurs suivantes : `name`, `roles` |
| inviteCode | \[Code d'invitation\]\(\#Coded'invitation\) | No | The invite code for which you want to change the settings. |  |
| value | [Valeur](commands.md#Valeur) | No | La nouvelle valeur du paramètre. |  |

### Examples

```text
!inviteCodeConfig
```

## !inviteCodes

Obtenez une liste de tous vos codes d'invitation.

### Usage

```text
!inviteCodes
```

### Aliases

* `!invitecode`
* `!invite-code`
* `!invite-codes`
* `!getinvitecode`
* `!get-invite-code`
* `!get-invite-codes`
* `!showinvitecode`
* `!show-invite-code`

### Examples

```text
!inviteCodes
```

## !inviteDetails

Affiche des détails sur l'origine de vos invitations.

### Usage

```text
!inviteDetails [user]
```

### Aliases

* `!invite-details`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | [Utilisateur](commands.md#Utilisateur) | No | L'utilisateur ou vous souhaitez afficher des invitations détaillées. |  |

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

## !invites

Afficher les invitations personnelles.

### Usage

```text
!invites [user]
```

### Aliases

* `!invite`
* `!rank`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | [Utilisateur](commands.md#Utilisateur) | No | L'utilisateur ou vous souhaitez afficher les invitations. |  |

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

## !kick

Expulser un membre du serveur.

### Usage

```text
!kick <member> [reason]
```

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| member | [Membre](commands.md#Membre) | Yes | Membre à expulser. |  |
| reason | [Texte](commands.md#Texte) | No | Pourquoi le membre a été expulsé. |  |

### Examples

## !leaderboard

Afficher les membres avec le plus d'invitations.

### Usage

```text
!leaderboard [page]
```

### Aliases

* `!top`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| page | [Nombre](commands.md#Nombre) | No | Quelle page du classement voulez vous voir. |  |

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

## !lockdown

Bloque un salon spécifique \(empêche tout le monde sans rôle spécial d'envoyer des messages\)

### Usage

```text
!lockdown [-t value|--timeout=value] [channel]
```

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| channel | [Salon](commands.md#Salon) | No | Le salon que vous voulez bloquer. |  |

### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑timeout | ‑t | [Durée](commands.md#Durée) | La durée après laquelle le blocage se finit automatiquement. Utilisez la commande une nouvelle fois pour terminer le blocage manuellement. |

### Examples

```text
!lockdown
```

## !memberConfig

Affiche et modifie la configuration des membres du serveur.

### Usage

```text
!memberConfig [key] [user] [value]
```

### Aliases

* `!member-config`
* `!memconf`
* `!mc`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| key | [Énumération](commands.md#Énumération) | No | La configuration de membre que vous souhaitez voir/changer. | Utilisez une des valeurs suivantes : `hideFromLeaderboard` |
| user | [Utilisateur](commands.md#Utilisateur) | No | Le membre ou le paramètre est affiché / modifié. |  |
| value | [Valeur](commands.md#Valeur) | No | La nouvelle valeur du paramètre. |  |

### Examples

```text
!memberConfig
```

## !members

Afficher le nombre de membres du serveur actuel.

### Usage

```text
!members
```

### Aliases

* `!member`
* `!memberscount`

### Examples

```text
!members
```

## !mute

Rendre muet un utilisateur

### Usage

```text
!mute [-d value|--duration=value] <user> [reason]
```

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | [Membre](commands.md#Membre) | Yes | L'utilisateur qui doit être rendu muet. |  |
| reason | [Texte](commands.md#Texte) | No | La raison de pourquoi l'utilisateur est muet. |  |

### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑duration | ‑d | [Durée](commands.md#Durée) | Le temps pendant lequel l'utilisateur est muet |

### Examples

## !permissions

Configurez les permissions pour utiliser des commandes.

### Usage

```text
!permissions [cmd] [role]
```

### Aliases

* `!perms`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| cmd | [Commande](commands.md#Commande) | No | La commande pour configurer les autorisations pour. | Utilisez une des valeurs suivantes : `addInvites`, `addRank`, `ban`, `botConfig`, `botInfo`, `caseDelete`, `caseView`, `check`, `clean`, `cleanShort`, `cleanText`, `clearInvites`, `config`, `createInvite`, `credits`, `export`, `fixRanks`, `getBot`, `graph`, `help`, `info`, `interactiveConfig`, `inviteCodeConfig`, `inviteCodes`, `inviteDetails`, `invites`, `kick`, `leaderboard`, `lockdown`, `memberConfig`, `members`, `mute`, `permissions`, `ping`, `prefix`, `premium`, `punishmentConfig`, `purge`, `purgeUntil`, `ranks`, `removeInvites`, `removeRank`, `restoreInvites`, `setup`, `softBan`, `strike`, `strikeConfig`, `subtractFakes`, `subtractLeaves`, `support`, `tryPremium`, `unban`, `unhoist`, `unmute`, `warn` |
| role | [Role](commands.md#Role) | No | Le rôle qui aura l'accès ou non à la commande. |  |

### Examples

```text
!permissions
```

## !ping

Mentionner le bot

### Usage

```text
!ping
```

### Examples

```text
!ping
```

## !prefix

Affiche le préfixe actuel du bot.

### Usage

```text
!prefix
```

### Examples

```text
!prefix
```

## !premium

Informations sur la version premium d'InviteManager.

### Usage

```text
!premium [action]
```

### Aliases

* `!patreon`
* `!donate`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| action | [Énumération](commands.md#Énumération) | No | L'action à faire. Aucune pour les infos premium. `check` pour vérifier votre statut premium. `activate` pour utiliser votre premium sur ce serveur. | Utilisez une des valeurs suivantes : `Activate`, `Check`, `Deactivate` |

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

## !punishmentConfig

Configurez les punitions lorsque vous atteignez un certain nombre d'avertissements.

### Usage

```text
!punishmentConfig [punishment] [strikes] [args]
```

### Aliases

* `!punishment-config`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| punishment | [Énumération](commands.md#Énumération) | No | Type de punitions à utiliser. | Utilisez une des valeurs suivantes : `ban`, `kick`, `mute`, `softban`, `warn` |
| strikes | [Nombre](commands.md#Nombre) | No | Nombre d'avertissements pour que cette peine soit appliquée. |  |
| args | [Texte](commands.md#Texte) | No | Arguments passés pour la sanction. |  |

### Examples

```text
!punishmentConfig
```

## !purge

Purger les messages dans un canal.

### Usage

```text
!purge <quantity> [user]
```

### Aliases

* `!prune`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| quantity | [Nombre](commands.md#Nombre) | Yes | Combien de messages doivent être supprimés? |  |
| user | [Utilisateur](commands.md#Utilisateur) | No | L'utilisateur dont les messages sont supprimés. |  |

### Examples

## !purgeUntil

Purger les messages dans un salon jusqu'à un message spécifié.

### Usage

```text
!purgeUntil <messageID>
```

### Aliases

* `!purge-until`
* `!prune-until`
* `!pruneu`
* `!purgeu`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| messageID | [Texte](commands.md#Texte) | Yes | Dernier ID de message à supprimer. |  |

### Examples

## !ranks

Montrer tous les rangs.

### Usage

```text
!ranks [page]
```

### Aliases

* `!show-ranks`
* `!showranks`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| page | [Nombre](commands.md#Nombre) | No | La page de la liste des rangs à montrer. |  |

### Examples

```text
!ranks
```

## !removeInvites

Enlève un certain nombre d'invitations à un utilisateur.

### Usage

```text
!removeInvites <user> <amount> [reason]
```

### Aliases

* `!remove-invites`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | [Utilisateur](commands.md#Utilisateur) | Yes | L'utilisateur à qui enlever des invitations. |  |
| amount | [Nombre](commands.md#Nombre) | Yes | Le nombre d'invitations à enlever. |  |
| reason | [Texte](commands.md#Texte) | No | La raison de l'enlèvement d'invitations. |  |

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

## !removeRank

Supprimer un rang.

### Usage

```text
!removeRank <rank>
```

### Aliases

* `!remove-rank`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| rank | [Role](commands.md#Role) | Yes | Celui que vous voulez supprimer le rang. |  |

### Examples

```text
!removeRank @Role
```

```text
!removeRank "Role with space"
```

## !restoreInvites

Restaurez toutes les invitations précédemment effacées.

### Usage

```text
!restoreInvites [user]
```

### Aliases

* `!restore-invites`
* `!unclear-invites`
* `!unclearinvites`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | [Utilisateur](commands.md#Utilisateur) | No | L'utilisateur à qui restaurer les invitations. Si aucun utilisateur n'est indiqué, cela restaure les invitations pour tous les utilisateurs. |  |

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

## !setup

Aide à la configuration du bot et à la recherche de problèmes \(par exemple: autorisations manquantes\)

### Usage

```text
!setup
```

### Aliases

* `!guide`
* `!test`
* `!testbot`
* `!test-bot`

### Examples

```text
!setup
```

## !softBan

Bannir puis automatiquement dé-bannir un membre du serveur.

### Usage

```text
!softBan [-d value|--deleteMessageDays=value] <user> [reason]
```

### Aliases

* `!soft-ban`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | [Membre](commands.md#Membre) | Yes | Utilisateur à bannir. |  |
| reason | [Texte](commands.md#Texte) | No | Pourquoi l'utilisateur a-t-il été banni? |  |

### Flags

| Flag | Short | Type | Description |
| :--- | :--- | :--- | :--- |
| ‑‑deleteMessageDays | ‑d | [Nombre](commands.md#Nombre) | Supprime les messages d'un utilisateur depuis un certain nombre de jours. |

### Examples

## !strike

Ajouter des avertissements à un utilisateur

### Usage

```text
!strike <member> <type> <amount>
```

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| member | [Membre](commands.md#Membre) | Yes | Le membre recevant les avertissements |  |
| type | [Énumération](commands.md#Énumération) | Yes | Le type d'infraction | Utilisez une des valeurs suivantes : `allCaps`, `duplicateText`, `emojis`, `hoist`, `invites`, `links`, `mentionRoles`, `mentionUsers`, `quickMessages`, `words` |
| amount | [Nombre](commands.md#Nombre) | Yes | Le nombre d'avertissements à ajouter |  |

### Examples

## !strikeConfig

Configurez les Strike reçues pour diverses violations.

### Usage

```text
!strikeConfig [violation] [strikes]
```

### Aliases

* `!strike-config`

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| violation | [Énumération](commands.md#Énumération) | No | Type de violation | Utilisez une des valeurs suivantes : `allCaps`, `duplicateText`, `emojis`, `hoist`, `invites`, `links`, `mentionRoles`, `mentionUsers`, `quickMessages`, `words` |
| strikes | [Nombre](commands.md#Nombre) | No | Nombre de Strikes. |  |

### Examples

```text
!strikeConfig
```

## !subtractFakes

Supprimez les fausses invitations de tous les utilisateurs.

### Usage

```text
!subtractFakes
```

### Aliases

* `!subtract-fakes`
* `!subfakes`
* `!sf`

### Examples

```text
!subtractFakes
```

## !subtractLeaves

Supprimer le nombre des invitations des personne qui ont quitter de tous les utilisateurs.

### Usage

```text
!subtractLeaves
```

### Aliases

* `!subtract-leaves`
* `!subleaves`
* `!sl`

### Examples

```text
!subtractLeaves
```

## !support

Obtenez un lien d'invitation vers notre serveur d'assistance.

### Usage

```text
!support
```

### Examples

```text
!support
```

## !tryPremium

Essayez gratuitement la version premium d’InviteManager pour une durée limitée.

### Usage

```text
!tryPremium
```

### Aliases

* `!try`
* `!try-premium`

### Examples

```text
!tryPremium
```

## !unban

Dé-bannir un utilisateur

### Usage

```text
!unban <user> [reason]
```

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | [Utilisateur](commands.md#Utilisateur) | Yes | The user that should be unbanned. |  |
| reason | [Texte](commands.md#Texte) | No | La raison de pourquoi l'utilisateur est dé-banni. |  |

### Examples

## !unhoist

Ajoute un caractère spécial devant le nom de chaque membre, donc ils seront affichés en dernier de la liste des membres.

### Usage

```text
!unhoist
```

### Aliases

* `!dehoist`

### Examples

```text
!unhoist
```

## !unmute

Démuter un utilisateur

### Usage

```text
!unmute <user>
```

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| user | [Membre](commands.md#Membre) | Yes | L'utilisateur qui doit reprendre la parole. |  |

### Examples

## !warn

Avertir un membre.

### Usage

```text
!warn <member> [reason]
```

### Arguments

| Argument | Type | Required | Description | Details |
| :--- | :--- | :--- | :--- | :--- |
| member | [Membre](commands.md#Membre) | Yes | Membre à avertir. |  |
| reason | [Texte](commands.md#Texte) | No | Pourquoi le membre a été averti. |  |

### Examples

