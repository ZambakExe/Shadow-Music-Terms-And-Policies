# Shadow Music — Gizlilik Politikası

**Son güncelleme:** 4 Temmuz 2026

## 1. Giriş

Bu Gizlilik Politikası, Shadow Music Discord botunun ("**Bot**") hangi verileri topladığını, bunları nasıl kullandığını, kimlerle paylaştığını ve nasıl koruduğunu açıklar. Bot'u sunucusuna ekleyen yöneticiler ile Bot'un komutlarını kullanan tüm Discord kullanıcıları için geçerlidir.

**Veri sorumlusu:** Utku — **İletişim:** utkuborhan111@gmail.com

## 2. Topladığımız Veriler

### 2.1 Sunucuya Özel Ayarlar (kalıcı olarak saklanır)

Her Discord sunucusu için aşağıdaki ayarlar veritabanımızda tutulur:

| Veri | Açıklama |
|---|---|
| Sunucu (Guild) kimliği | Ayarın hangi sunucuya ait olduğunu belirlemek için |
| Varsayılan ses seviyesi | `/ses` komutuyla belirlenen başlangıç ses düzeyi |
| SponsorBlock kategorileri | Otomatik atlanacak reklam/sponsor bölümü tercihleri |
| Arama motoru tercihi | YouTube Music / YouTube / Spotify / SoundCloud tercihi |

Bu veriler yalnızca sunucu düzeyindedir, herhangi bir kişiyle ilişkilendirilmez ve yalnızca sunucu **Yöneticileri** tarafından değiştirilebilir.

### 2.2 Geçici (Oturum İçi) Veriler

Aşağıdakiler yalnızca Bot'un anlık işlevini yerine getirmesi için bellekte tutulur; kalıcı olarak kaydedilmez ve Bot yeniden başlatıldığında veya ilgili çalma oturumu sona erdiğinde silinir:

- Bir şarkıyı isteyen kullanıcının adı/kimliği ("Öneren" bilgisini şu an çalınan şarkı ekranında göstermek için),
- Bulunduğunuz ses kanalındaki üye sayısı (kanal boş kaldığında Bot'un otomatik ayrılabilmesi için),
- Arama sorgunuz ve o anki şarkı kuyruğu.

### 2.3 Yüklenen Ses Dosyaları

`/oynat` komutuyla eklediğiniz ses dosyaları Discord'un kendi sunucularında (CDN) barındırılır. Bot bu dosyaların bir kopyasını indirmez veya saklamaz; yalnızca Discord tarafından üretilen bağlantıyı çalma amacıyla ses altyapımıza iletir.

### 2.4 Toplamadığımız Veriler

Bot şunları **toplamaz veya saklamaz**:

- Sunucunuzdaki olağan sohbet mesajlarının içeriğini (Bot, Discord'un ayrıcalıklı "Mesaj İçeriği" iznini kullanmaz),
- Ses kanalındaki konuşmaları veya herhangi bir ses kaydını (Bot yalnızca ses **çalar**; dinlemez veya kaydetmez),
- E-posta, telefon numarası, IP adresi, ödeme/kart bilgisi gibi kişisel iletişim veya finansal veriler,
- Spotify, Apple Music gibi harici hesaplarınızla herhangi bir bağlantı veya kimlik bilgisi.

## 3. Verileri Nasıl Kullanıyoruz

Topladığımız sınırlı veriyi yalnızca şu amaçlarla kullanırız: müzik çalma ve kuyruk yönetimi gibi temel işlevleri sağlamak, sunucunuza özel tercihlerinizi hatırlamak ve hataları teşhis ederek Bot'u iyileştirmek. Verileriniz reklam amacıyla kullanılmaz, satılmaz veya kiralanmaz.

## 4. Üçüncü Taraflarla Paylaşım

Bot'un çalışabilmesi için, yalnızca ilgili işlem için gerekli olan bilgiler aşağıdaki üçüncü taraflara iletilir:

| Üçüncü taraf | Paylaşılan bilgi | Amaç |
|---|---|---|
| YouTube | Arama sorgusu / video linki | Video/ses bulma ve çalma |
| Spotify, Apple Music, Deezer, Yandex Music | Arama sorgusu / link (LavaSrc eklentisi ile) | Şarkı bulma ve meta veri çözümleme |
| SoundCloud, Bandcamp, Twitch, Vimeo | Arama sorgusu / link | Alternatif ses kaynaklarından çalma |
| LRCLIB (lrclib.net) | Şarkı ve sanatçı adı | Şarkı sözü / karaoke gösterimi |
| SponsorBlock (sponsor.ajay.app) | Video kimliği | Sponsor/reklam bölümü zaman bilgisi |
| Discord Inc. | Bot'un çalışması için gereken temel veriler | Hizmetin altyapısı |

Bu taraflar kendi bağımsız gizlilik politikalarına tabidir; verilerin onlarda ne kadar süreyle tutulduğu bizim kontrolümüzde değildir.

## 5. Teknik Kayıtlar

Hataları tespit edip gidermek için sunucu kimliği, komut adı ve hata mesajı gibi sınırlı teknik kayıtlar geçici olarak tutulabilir. Bu kayıtlar mesaj içeriği veya kişisel veri içermez.

## 6. Saklama Süresi

Sunucuya özel ayarlar (Bölüm 2.1), siz değiştirene, silinmesini talep edene ya da Bot sunucunuzdan kaldırılıp verinin temizlenmesine kadar veritabanımızda kalır. Geçici oturum verileri (Bölüm 2.2) kalıcı olarak saklanmaz.

## 7. Veri Güvenliği

Verilerinizi korumak için makul teknik önlemler alınır; ancak hiçbir aktarım veya depolama yönteminin %100 güvenli olduğu garanti edilemez. Veritabanına erişim yalnızca Bot'u işleten geliştirici(ler) ile sınırlıdır.

## 8. Haklarınız

Bulunduğunuz ülkeye bağlı olarak (örneğin Türkiye'de 6698 sayılı Kişisel Verilerin Korunması Kanunu ("KVKK") veya AB'de Genel Veri Koruma Tüzüğü ("GDPR") kapsamında), sunucunuza ait verilerle ilgili olarak hangi verilerin saklandığını öğrenme ve bunların düzeltilmesini veya silinmesini talep etme hakkına sahip olabilirsiniz. Bu tür talepleri utkuborhan111@gmail.com üzerinden iletebilir veya Bot'u sunucunuzdan çıkararak kullanımı sonlandırabilirsiniz.

## 9. Çocukların Gizliliği

Bot, Discord'un izin verdiği asgari yaşın altındaki kişilerden bilerek veri toplamaz. Böyle bir durumun farkına varırsak ilgili veriyi makul süre içinde sileriz.

## 10. Discord ile İlişki

Shadow Music, Discord Inc.'in resmî bir ürünü değildir ve Discord tarafından onaylanmamıştır. Discord platformunun genel kullanımı için Discord'un kendi [Gizlilik Politikası](https://discord.com/privacy) her zaman ayrıca geçerlidir.

## 11. Politikadaki Değişiklikler

Bu Gizlilik Politikası zaman zaman güncellenebilir; değişiklikler yayımlandığı anda yürürlüğe girer ve "Son güncelleme" tarihi buna göre değiştirilir.

## 12. İletişim

- **Discord destek sunucusu:** [discord.gg/shdwali / discord.gg/yPhaamZhmM]
- **E-posta:** utkuborhan111@gmail.com
