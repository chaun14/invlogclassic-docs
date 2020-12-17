---
description: InviteLogger Classic Hakkında Sıkça Sorulan Sorular.
---

# S.S.S

## S.S.S \(Sıkça Sorulan Sorular\)

### Botun ön ekini nasıl değiştirebilirim?

Öneki değiştirmek için `!config prefix <prefix>` komutunu kullanabilirsiniz. Ör: `!config prefix -`

Geçerli önekinizi bilmiyorsanız, öneki görmek için botu etiketleyebilirsiniz.

### Katılma ve ayrılma mesajlarını nasıl ayarlarım?

Aşağıdaki komut ile Giriş Mesajının kanalını,

`!config joinMessageChannel #kanal`

Aşağıdaki komut ile de Ayrılma Mesajının kanalını ayarlıyabilirsiniz

`!config leaveMessageChannel #kanal`.

Bunu yaptıktan sonra yeni girişler ve ayrılmalar o kanala gönderilecek.

### Giriş ve ayrılma mesajlarını özelleştirebilir miyim?

Kesinlikle!

## Giriş Mesajı

`!config joinMessage {memberMention} **katıldı**; **{inviterName}** tarafından davet edildi (**{numInvites}** davet yaptı)`

## Ayrılma Mesajı

`!config leaveMessage {memberName} **ayrıldı**; **{inviterName}** tarafından davet edilmişti.`

Kullanılabilecek çok sayıda değişken var. Listenin tamamını '[Tüm Değişkenler](../modueller/invites/custom-messages.md#oezellestirilmis-mesajlar)' sayfasında görebilirsiniz.

### 'Rütbe' nedir, nasıl kullanabilirim?

Rütbe, belirli bir sayıda davete yapan insanlara rol vermek için kullanılır. Örneğin; `@Yakışıklı` adında bir rolünüz varsa ve 5 veya daha fazla daveti olan kişilere bu rolün eklenmesini istiyorsanız bu örnekteki gibi bir komut kullanmanız gerekir: `!addRank @Yakışıklı 5 (açıklama)`. Birisi 5 davet alır almaz, otomatik olarak bu rol kullanıcıya eklenir!

### Botun bazı kanallara mesaj atmasını ve o kanallarda komut kullanılmasını istemiyorum, nasıl yapabilirim?

Botun yanıt vermesini istemediğiniz kanallarda botun mesaj atma yetkisini kaldırabilirsiniz veya direk olarak botun o kanalı algılamasını kapatmak istiyorsanız da `!config ignoredChannels #kanal` komutu ile bu özelliği kullanabilirsiniz.

### Sınırlama: Bot katılmadan önce gelişmiş izleme yok.

Gelişmiş izleme \(kim kimi davet ettiği\) yalnızca botu davet ettikten sonra çalışır. Bot, herkesin davet ettikten sonra davet ettiğini bilecek, endişelenmeyin. Yalnızca ek bilgiler eksiktir ve yalnızca botu davet ettikten sonra katılan üyeler için gösterilebilir.

