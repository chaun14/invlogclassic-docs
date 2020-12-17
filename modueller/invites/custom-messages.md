---
description: Giriş ve ayrılma mesajları kendinize göre özelleştirebilirsiniz.
---

# Özelleştirme

Özelleştirilmiş Mesajlar

\(Değişkenlere zıpla\)

## Özelleştirilmiş Mesajlar

Kendinize özel mesaj ayarlayarak katılma ve ayrılma mesajı oluşturabilirsiniz:

```text
!config joinMessage Bu senin katılma mesajın olucak! Ayrıca her kullanıcı sunucuya girceği zaman atılcaktır.
```

veya

```text
!config leaveMessage Bu senin çıkış mesajın olucak! Ayrıca her kullanıcı sunucuya çıktığı zaman atılcaktır.
```

gibi örnekler verilebilir.

Bunun gibi bir mesaj açıkça mantıklı değil. Yeni üye, davet eden veya sunucu hakkındaki bilgilerle kişiselleştirmelisiniz. Lütfen mevcut tüm değişkenler için aşağıdaki listeye göz atın.

Eğer mesajımızı

`Hoşgeldin @Andy! Valandur tarafından sunucuya giriş yaptın, toplamda 3 davetin oldu! İyi eğlenmeler!`

olmasını istiyorsak.

Tüm isimleri ve numaraları değişkenlerlere bağlayarak bunu kolayca yapabiliriz: `Hoşgeldin {memberMention}! {inviterName} tarafından sunucuya giriş yaptın, toplamda {numInvites} davetin oldu! İyi eğlenmeler!`

Böylece, mesajı ayarlamak için artık `!config joinMessage <mesaj>` komutunu kullanabilirsiniz. Botumuz, birisi her katıldığında değişkenleri otomatik olarak değiştirecektir.

> \[!Not\|style:flat\] Premium kullanıcılar bu mesajları embed halinde ayarlayabilir. [Daha fazla bilgi](https://github.com/chaun14/invlogclassic-docs/tree/d05e5669fc48cfcc5f429ee855b06f4511193435/modules/invites/modules/invites/examples.md)

Lütfen [Örnek sayfa](https://github.com/chaun14/invlogclassic-docs/tree/d05e5669fc48cfcc5f429ee855b06f4511193435/modules/invites/modules/invites/examples.md)'ya bakarak nasıl embed mesajı yapabilceğinizi görün.

### Değişkenler

|  | Katılma | Ayrılma | Örnek | Açıklama |
| :--- | :--- | :--- | :--- | :--- |
| {memberName} | Evet | Evet | Andy | Sunucuya giren kişinin ismi. |
| {memberId} | Evet | Evet | 436844634 | Sunucuya giren kişinin kullanıcı ID'si |
| {memberMention} | Evet | Hayır | @Andy | Sunucuya giren kişinin etiketi. \(Gelen kişi etiketlenir\). |
| {memberFullName} | Evet | Evet | Andy\#1801 | Sunucuya giren kişinin tüm ismi. |
| {memberImage} | Evet | Evet | \[URL\] | Sunucuya giren kişinin avatar linki. |
| {inviterName} | Evet | Evet | Andy | Davet eden kişinin ismi. |
| {inviterId} | Evet | Evet | 241929953 | Davet eden kişinin kullanıcı ID'si |
| {inviterMention} | Evet | Evet | @Andy | Davet eden kişinin etiketi \(Davet eden kişi etiketlenir\) |
| {inviterFullName} | Evet | Evet | Andy\#1801 | Davet eden kişinin tüm ismi. |
| {inviterImage} | Evet | Evet | \[URL\] | Davet eden kişinin avatar linki. |
| {numInvites} | Evet | Evet | 12 | Davet eden kişinin toplam davet sayısı. |
| {numRegularInvites} | Evet | Evet | 7 | Davet eden kişinin normal davet sayısı. |
| {numBonusInvites} | Evet | Evet | 5 | Davet eden kişinin bonus davet sayısı. \(!addInvites komutu ile eklenenler.\) |
| {numFakeInvites} | Evet | Evet | 3 | Davet eden kişinin fake davet sayısı. |
| {numLeaveInvites} | Evet | Evet | 6 | Davet eden kişinin daha önceden davet edip sunucudan çıkan kişilerim sayısı. |
| {memberCount} | Evet | Evet | 42 | Sunucudaki üye sayısı. |
| {numJoins} | Evet | Evet | 3 | Sunucuya gelen kişinin bu sunucuya kaçıncı girişi olduğunun sayısı.. |
| {channelName} | Evet | Evet | general | Davet kodunun oluşturulduğu kanalın ismi. |
| {channelMention} | Evet | Evet | \#general | Davet kodunun oluşturulduğu kanalın etiketi. |
| {inviteCode} | Evet | Evet | fgSr30s | Sunucuya gelen kişinin kullandığı davet kodu. |
| {memberCreated:date} | Evet | Evet | 25.09.2016 | Sunucuya gelen kişinin hesap oluşturulma tarihi. |
| {memberCreated:duration} | Evet | Evet | 5 weeks | Sunucuya gelen kişinin hesabının ne kadar süredir açık olduğu. |
| {memberCreated:timeAgo} | Evet | Evet | 2 day ago | Sunucuya gelen kişinin ne kadar süre önce hesabının açıldığı. |
| {firstJoin:date} | Evet | Evet | 11.12.2017 | Sunucuya gelen kişinin sunucuya ilk giriş yaptığı tarih. |
| {firstJoin:duration} | Evet | Evet | 4 days | Sunucuya gelen kişinin sunucuya ilk giriş yaptığı tarihin aralığı. |
| {firstJoin:timeAgo} | Evet | Evet | 1 week ago | Sunucuya gelen kişinin sunucuya ilk ne kadar süre önce giriş yaptığı. |
| {previousJoin:date} | Evet | Hayır | 02.04.2018 | Sunucuya gelen kişinin sunucuya son giriş yaptığı tarih. |
| {previousJoin:duration} | Evet | Hayır | 2 months | Sunucuya gelen kişinin sunucuya son giriş yaptığı tarihin aralığı. |
| {previousJoin:timeAgo} | Evet | Hayır | 1 second ago | Sunucuya gelen kişinin sunucuya en son ne kadar süre önce giriş yaptığı. |
| {joinedAt:date} | Hayır | Evet | 17.05.2018 | Sunucuya giriş tarihi. |
| {joinedAt:duration} | Hayır | Evet | 3 minutes | Sunucuya giriş tarihin şu anki zamana aralığı. |
| {joinedAt:timeAgo} | Hayır | Evet | 2 minutes ago | Sunucuya ne kadar süre önce giriş yaptığın. |

