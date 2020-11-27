# S.S.S (Sıkça Sorulan Sorular)

### Botun ön ekini nasıl değiştirebilirim?

Öneki değiştirmek için `!config prefix -` yapabilirsiniz.

Geçerli önekinizi bilmiyorsanız, öneki görmek için`@inviteLogger classic config prefix` komtunu kullanabilirsiniz.

### Katılma ve ayrılma mesajlarını nasıl ayarlarım?

Aşağıdaki komut ile Giriş Mesajının kanalını,

`!config joinMessageChannel #kanal`

Aşağıdaki komut ile de Ayrılma Mesajının kanalını ayarlıyabilirsiniz

`!config leaveMessageChannel #kanal`.

Bunu yaptıktan sonra yeni girişler ve ayrılmalar o kanala gönderilecek.

### Giriş ve ayrılma mesajlarını özelleştirebilir miyim?

Kesinlikle!

#Giriş Mesajı

`!config joinMessage {memberMention} **katıldı**; **{inviterName}** tarafından davet edildi (**{numInvites}** davet yaptı)`

#Ayrılma Mesajı

`!config leaveMessage {memberName} **ayrıldı**; **{inviterName}** tarafından davet edilmişti.`

Kullanılabilecek çok sayıda yer tutucu var. Listenin tamamını '[Custom Messages](/tr/modules/invites/custom-messages.md)' sayfasında görebilirsiniz.

### 'Rütbe' nedir, nasıl kullanabilirim?

Rütbe, belirli bir sayıda davete ulaştıklarında insanlara rol atamak için kullanılır. Örneğin. `@Başlangıçcı` adında bir rolünüz varsa ve 5 veya daha fazla daveti olan kişilerin bu role eklenmesini istiyorsanız şu şekilde bir sıralama oluşturmanız gerekir:`!add-rank @Başlangıçcı 5 (ve burada bir açıklama istersiniz)`. Birisi 5 davet alır almaz, otomatik olarak bu role eklenir!

### Bir / bazı kanallar dışındaki tüm botları nasıl devre dışı bırakabilirim?

Botun yanıt vermesini istemediğiniz kanallarda okunan mesaj izinlerini kaldırın.

### Sınırlama: Bot katılmadan önce gelişmiş izleme yok.

Gelişmiş izleme \(kim kimi davet ettiğinde\) yalnızca botu davet ettikten sonra çalışır. Bot, herkesin davet ettikten sonra sayımı davet ettiğini bilecek, endişelenmeyin. Yalnızca ek bilgiler eksiktir ve yalnızca botu davet ettikten sonra katılan üyeler için toplanabilir.

