---
description: You can customise the join and leave messages with a number of parameters.
---

# Custom Messages

\(Jump to placeholders\)

## Custom Messages

You can set a custom join or leave message by setting the config:

```text
!config joinMessage This is your custom join message! It will be posted every time someone joins your server.
```

or

```text
!config leaveMessage This is your custom leave message! It will be posted every time someone leaves your server.
```

A message like that obviously doesn't make sense. You should personalise it with information about the new member, inviter or the server. Please see the list below for all available placeholders.

Si vous voulez que le message soit:

`Welcome @Andy! You were invited by Valandur, who now has 3 invites! Have fun on our server!`

Vous pouvez facilement le faire en remplaçant les noms et les nombres par des variables:

`Welcome {memberMention}! You were invited by {inviterName}, who now has {numInvites} invites! Have fun on our server!`

Maintenant vous pouvez faire `!config joinMessage <message du dessus>`pour définir le message. Le bot remplacera automatiquement les variables par sa valeur associée \(voir tableau ci dessous\).

> \[!NOTE\|style:flat\] Premium users can also use embeds in their join and leave messages. [More info here](https://github.com/chaun14/invlogclassic-docs/tree/d05e5669fc48cfcc5f429ee855b06f4511193435/modules/invites/modules/invites/examples.md) Please see the [examples page](https://github.com/chaun14/invlogclassic-docs/tree/d05e5669fc48cfcc5f429ee855b06f4511193435/modules/invites/modules/invites/examples.md) to see what kind of messages you can make!

### Variables

|  | join | leave | example | description |
| :--- | :--- | :--- | :--- | :--- |
| {memberName} | yes | yes | Andy | Pseudo de la personne qui vient de rejoindre votre serveur |
| {memberId} | yes | yes | 436844634 | Identifiant discord de la personne qui vient de rejoindre votre serveur |
| {memberMention} | yes | no | @Andy | Mention de la personne qui vient de rejoindre votre serveur \(elle sera ping\) |
| {memberFullName} | yes | yes | Andy\#1801 | Le nom d'utilisateur et le tag de la personne qui vient de rejoindre votre serveur |
| {memberImage} | yes | yes | \[URL\] | URL de la photo de profil de la personne qui vient de rejoindre votre serveur |
| {inviterName} | yes | yes | Andy | Pseudo de la personne qui a invité le membre |
| {inviterId} | yes | yes | 241929953 | Identifiant discord de la personne qui a invité le membre |
| {inviterMention} | yes | yes | @Andy | Mention de la personne qui a invité le membre |
| {inviterFullName} | yes | yes | Andy\#1801 | Pseudo et tag de la personne qui a invité le membre |
| {inviterImage} | yes | yes | \[URL\] | URL de la photo de profil de la personne qui a invité le membre |
| {numInvites} | yes | yes | 12 | Nombre total d'invitations de la personne qui a invité le membre |
| {numRegularInvites} | yes | yes | 7 | Nombre d'invitations total réel \(sans compter les leaves et bonus\) de la personne qui a invité le membre |
| {numBonusInvites} | yes | yes | 5 | Nombre total d'invitation bonus de la personne qui a invité le membre |
| {numFakeInvites} | yes | yes | 3 | Nombre total de fausses invitations de la personne qui a invité le membre |
| {numLeaveInvites} | yes | yes | 6 | Nombre total d'invitation retirées à cause du depart de personnes invitées |
| {memberCount} | yes | yes | 42 | Nombre de membre actuel de votre serveur discord |
| {numJoins} | yes | yes | 3 | Nombre de fois ou la personne a rejoint votre serveur discord |
| {channelName} | yes | yes | general | Nom du salon dans lequel l'invitation a été crée |
| {channelMention} | yes | yes | \#general | Mention du salon dans lequel l'invitation a été crée |
| {inviteCode} | yes | yes | fgSr30s | Code d'invitation utilisé par la personne |
| {memberCreated:date} | yes | yes | 25.09.2016 | Date the discord user was created |
| {memberCreated:duration} | yes | yes | 5 weeks | Duration since the discord user was created |
| {memberCreated:timeAgo} | yes | yes | 2 day ago | Time the discord user was created |
| {firstJoin:date} | yes | yes | 11.12.2017 | Date the user joined the server for the first time |
| {firstJoin:duration} | yes | yes | 4 days | Duration since the user joined the server for the first time |
| {firstJoin:timeAgo} | yes | yes | 1 week ago | Time the user joined the server for the first time |
| {previousJoin:date} | yes | no | 02.04.2018 | Date when the user joined the server the last time |
| {previousJoin:duration} | yes | no | 2 months | Duration since when the user joined the server the last time |
| {previousJoin:timeAgo} | yes | no | 1 second ago | Time when the user joined the server the last time |
| {joinedAt:date} | no | yes | 17.05.2018 | Date à laquelle la personne a rejoint |
| {joinedAt:duration} | no | yes | 3 minutes | Durée depuis que la personne a rejoint |
| {joinedAt:timeAgo} | no | yes | 2 minutes ago | Il y a combien de temps la personne a rejoint |

