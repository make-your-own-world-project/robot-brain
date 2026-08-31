> Türkçe: Yetkili İngilizce kaynağın makine destekli çevirisi. Ana dildeki düzeltmeler memnuniyetle karşılanır. [İngilizce](../../16-What-Commercial-Language-Model-Services-Got-Wrong.md) | [Tüm diller](../README.md)

# Ücretli dil modeli hizmetlerinde gözlemlenen başarısızlıklar ve bunların yol açtığı önlemler

![Kaydedilen arızalar daha sonraki çalışmalar için testler ve korumalar haline geldi.](../../illustrations/failures-became-blueprint.png)

## Bunlar mevcut en güçlü ücretli seçeneklerdi

Bu projede araştırma, kodlama, yazma ve inceleme için ücretli çevrimiçi dil modeli hizmetleri kullanıldı. Hesaplar, o dönemde sunulan hizmetlerin en güçlü genel modellerini içeriyordu. Daha yetenekli bir ücretli seçeneği seçmek, aşağıdaki arızaları engellemedi.

Her örnek tarihli bir proje kaydından gelmektedir. Tablolarda ücretli bir modelin ne yaptığı, daha sonra ne olduğu ve model dışında hangi korumanın oluşturulduğu açıklanmaktadır. Bunlar ticari hizmetlerde görülen arızalardır, ticari hizmetlerden kaynaklanan arızalar değildir.Robot Brain. Sağ sütunda bu projenin nasıl yanıt verdiği açıklanmaktadır.

Kayıtlar, sağlayıcının amacına ilişkin tahminde bulunmaz veya açıklanmayan bir teknik nedeni bildiğini iddia etmez. Korumalar tek bir şirket yerine tekrarlanan davranışlara yanıt verdiği için sağlayıcı adları dışarıda bırakıldı.

## Başarısızlıkların maliyeti nedir?

Maliyet yanlış cevapla sınırlı değildi.

- **Zaman kaybedildi.** Bitti olarak tanımlanan işin kişi tarafından incelenmesi, yeniden açıklanması, onarılması ve test edilmesi gerekiyordu. Bazı arızalar saatlerce sürdü.
- **Bazen kota olarak da adlandırılan ücretli kullanım ödeneği kaybedildi.** Yeniden denemeler, tekrarlanan bağlam, değiştirme taslakları ve düzeltmeler, yararlı çalışma olarak aynı sınırlı ödeneği kullandı. Kaydedilen bu oturumlarda, kullanılamayan çıktılar veya düzeltici değişimler için otomatik kota iadesi yapılmadı.
- **Hizmet her iki durumda da ödenmiştir.** Abonelik veya kullanım ücreti kalırken kişi aynı zamanda arızayı bulup onarmak için gereken zaman ve çabayı da harcamıştır.
- **Çalışan şeyler bozuldu.** Eksik düzenlemeler, canlı bir hizmetin çalışamamasına neden oldu. Bir ayarın yanlış kopyasında değişiklikler yapıldı. Çıkış, erişimi onarmak yerine gerekli konumdan uzaklaştırıldı.
- **Tarihsel kayıt riske atıldı.** Oluşturulan metin, insan materyaliyle karıştırıldı ve kişi bu değişikliği onaylamadan kayıtlar değiştirildi veya kaldırıldı.
- **Dikkat izinsiz tüketildi.** Önemli yanıtlar tekrarlanan açıklamaların içine gömüldü ve kişi, önemli olan küçük kısmı kurtarmak için her şeyi okumaya zorlandı.

Bu nedenle önemli kurallar burada sadece bir istemde yaşamıyor.Robot Brain gerçekte ne olduğunu kontrol eder ve model başarılı olduğunu söylese bile katkıyı reddedebilir.

## Süreklilik ve bilgi başarısızlıkları

| Gözlemlenen başarısızlık | Ne oldu | Dil modelinin dışına koruma eklendi |
|---|---|---|
| Geçmişi kaybettikten sonra sürekli ses geliyor | Bir hizmet, önceki görüşmeyi çalışma sınırına uyacak şekilde kısalttı. Akıcı görünmeye devam ederken bazı sonuçları korudu ancak kaynakları, düzeltmeleri, reddedilen alternatifleri, olay sırasını ve kullanıcı amacını kaybetti. | Konuşmanın tamamını sırayla tutun. Kısaltılmış versiyonu ayrı olarak kaydedin ve neleri içerdiğini, neleri çıkardığını ve neleri kaybetmiş olabileceğini kaydedin. |
| Kayıtlı geçmişin yerini alan yeni bir yanıt | Dünyayla ilgili farklı bilgilerden, kurallardan ve seçimlerden gelse bile, daha yeni bir dil modeli yanıtı, kendisinden önceki her şeyin yerini alacak gibi görünebilir. | Her bulguyu zamanı ile birlikte kaydedin. En yeni yanıtın daha önce kabul edilmiş, reddedilmiş veya belirsiz bulguların üzerine yazılmasına asla izin vermeyin. |
| Dil modeli öğrenimi kaynağa giden yolu yok etti | Dil modeli, yararlı kalıpları kaynağın yaratıcısından, amacından, hedef kitlesinden, kanıtlarından, anlaşmazlıklarından ve daha sonraki geçmişinden ayırırken korudu. | Değişmeyen kaynakları ve bunların bilinen bağlantılarını her dil modelinin dışında tutun. Desteklenmeyen dil modeli bilgisini, ayrı bir kanıt onu bir kaynağa yeniden bağlamadığı sürece öneri olarak ele alın. |
| Dil modelinin öğrendiklerinin ardındaki koşulların kaybı | Dil modeli yararlı olmaya devam etti ancak yanıtı onu şekillendiren tüm insanları, kaynakları, amaçları, anlaşmazlıkları, izinleri ve kültürleri ortaya çıkaramadı. | Bilinen durumları saklayın ve dil modelinin dışında kaydedilen kaynaklara itibar edin. Desteklenmeyen öğrenilen bilgiyi bir kaynağa bağlı bir gerçek olarak değil, bir dil modeli önerisi olarak ele alın. |
| Seçilen şeyden gizli önyargı | Dil modelinin tanıyabildiği şeyler, onu oluşturmak için kullanılan dilleri, kaynakları, arşivleri, etiketleri, insan incelemecileri ve hedefleri yansıtıyordu. Cevabı tüm bu etkileri ortaya çıkarmadı. | Dil modelinin bilinen sınırlarını ve öğrenildiği materyal hakkında bilinenleri kaydedin. Birkaç sınırlı aracı karşılaştırın ve tek bir düzgün yanıtı eksiksiz bir görünüm olarak ele almayın. |
| Paylaşılan tarih sessizce yeniden yazılıyor | Ana görünümlü bir geçmişi düzenleyen birden fazla çalışan, uyumsuz kararları kaybedebilir veya birleştirebilir. | Önceki girişlerin üzerine yazmadan yeni kaynak geçmişi ekleyin. Olay kaydını yeniden yazmaya gerek kalmadan bu geçmişten güncel görünümler oluşturun. |
| Farklı zamanlar ve durumlar eşit kabul edilir | Güncel, tarihsel, deneysel, ayrı ayrı test edilmiş ve değiştirilmiş ifadeler sanki aynı konumdaymış gibi sunuldu. | Her önemli talep ve sistem parçasıyla birlikte zamanı ve mevcut durumu saklayın. |
| Bir parçayı kimin kullandığını kontrol etmeden çıkarmak | Mevcut süreçte kullanılmayan bir parça, ona bağlı daha sonraki çalışmalar kontrol edilmeksizin eskimiş olarak değerlendirildi. | Her parçanın işini, kullanıcılarını, mevcut durumunu ve değiştirmeleri kaydedin. Kaldırmadan önce bu kullanıcıları kontrol edin. |
| Oluşturulan metni bir kişinin kaydına karıştırma | Dil-model-yazılı açıklama, daha sonra kişinin kendi sözleri veya inançlarıyla karıştırılabilecek bir biçimde, insan malzemesinin yanında saklandı. | Kelimesi kelimesine insan materyalini, transkriptleri ve dil modeliyle oluşturulan yorumlamayı net bir şekilde ayrı tutun. Üretilen metnin sessizce insan kaydının bir parçası olmasına asla izin vermeyin. |
| Temizleme sırasında geçmişi kaldırma | Daha önceki kayıtlar, bir dil modelinin bunların yanlış veya düzensiz olduğuna karar vermesi nedeniyle değiştirildi veya kaldırıldı. Bu, ne olduğunu ve neden değiştiğini anlamak için gereken kanıtları yok etti. | Tarihsel kayıtları koruyun. Geçmişi sessizce yeniden yazmak yerine bir düzeltme veya daha sonra bir bulgu ekleyin. |

## Talimat ve kapsam hataları

| Gözlemlenen başarısızlık | Ne oldu | Dil modelinin dışına koruma eklendi |
|---|---|---|
| Görev sırasında kaybolan kurallar | Bir dil modeli aynı görevdeki bir kuralı okuyabilir, yeniden ifade edebilir ve ardından ihlal edebilir. | Başarısızlığı maliyeti yüksek olan kuralları, işi reddedebilecek gerekli şartlara ve kontrollere dönüştürün. |
| İddia kurallarına delil olmadan uyulmuştur | Model, sonuç aksini gösterdiğinde talimatların veya belgelerin takip edildiğini iddia etti. | İlgili kontrolün çalıştırıldığına ve geçtiğine dair kanıt isteyin. Başarılı olduğunu söyleyen bir dil modeli kanıt değildir. |
| İstenen görevin değiştirilmesi | Belirli bir isteğin yerini dil modelinin tercih ettiği çerçeve aldı ve bu da kullanıcıyı orijinal çalışma için yeniden tartışmaya zorladı. | İstenilen limitleri koruyun. Gerçek bir güvenlik veya izin çatışması gerektirmediği sürece çerçevelemede talep edilmeyen bir değişikliği reddedin. |
| İzinsiz ekstra iş yapmak | Talep edilmemesine rağmen faydalı göründüğü için ilgili çalışma yapıldı. | Her eylemi beyan edilen göreve bağlayın. Herhangi bir genişlemeyi yeni bir karar olarak değerlendirin. |
| İstenilen hedefi değiştirme | İstenilen konuma ulaşılamadığında, erişimi onarmak yerine sonuç daha kolay bir yere taşındı. | Seçilen hedefi koruyun. Bunu değiştirmek kullanıcının kararını gerektirir. |
| İstenilen düzeltmenin ötesine geçiliyor | Geri bildirim, ulaşılması gereken kesin bir düzeltme yerine, işi değiştirmeye devam etme yönünde bir yön olarak değerlendirildi. | İstenen son durumu kaydedin ve değişiklikten sonra sonucu buna göre kontrol edin. |
| Yeni malzemeyi yanlış yere zorlamak | Mevcut bir belgeye yapıya sığdırılmadan yeni malzeme eklenmesi her ikisine de zarar verdi. | Sonucun tamamını planlayın, eklemenin neleri değiştirdiğini izleyin ve ait olmadığında ayrı bir belge oluşturun. |
| Erişimi düzeltmek yerine çıktıyı taşıma | İstenilen klasöre ulaşılamadığında bir asistan sonucu daha kolay bir yere taşıdı. Bu, kişinin kayıtlarını böldü ve orijinal konum etrafında oluşturulmuş olan dosyalama, izinler ve alışkanlıkları ortadan kaldırdı. | Seçilen konuma erişimi onarın. Hedefi değiştirmek kişinin kararı olarak kalır. |

## Kanıt ve tamamlama hataları

| Gözlemlenen başarısızlık | Ne oldu | Dil modelinin dışına koruma eklendi |
|---|---|---|
| Tamamlanmanın çok erken bildirilmesi | Bir bölümün düzenlenmesi veya başlatılması, etkisi test edilmeden önce tamamlanmış olarak rapor edildi. | Tamamlama, oluşturulan bir durum bildirimini değil, talep edilen sonuca ilişkin kanıt gerektirir. |
| Teşhisi kontrol etmeden kabul etmek | Bir hata mesajının nereden, ne zaman geldiği veya mevcut görevi açıklayıp açıklamadığı kontrol edilmeden kabul edildi. | Kanıtları nerede, ne zaman ve hangi koşullar altında üretildiğine bağlı tutun. |
| Makul tahmin | Nedenler ve sonraki adımlar, kanıtlar onları gösterdiği için değil, makul göründükleri için önerildi. | Bilinmeyenleri koruyun. Gözlemlenenleri, olası açıklamayı, testi ve doğrulanan nedeni ayırın. |
| En yeni değişikliğin doğru olduğunu varsayarsak | Son zamanlarda dil-model-yazılı değişikliklerin doğru olduğu varsayılırken, ilk önce diğer kısımlardan şüphelenildi. | Nedeni belirlemeden önce en yeni değişikliği ve rakip açıklamaları kontrol edin. |
| Zamanlamayı nedenin kanıtı olarak ele almak | Bir arızanın yakınında aktif olan kısım, normal davranış veya diğer değişen koşullar karşılaştırılmadan suçlandı. | Sorunun tekrar yaşanmasını sağlayın. Normal ve değişen koşulları karşılaştırın, aksi kanıtları arayın ve sebebin izini sürün. |
| Küçük bir testi canlı davranışın kanıtı olarak ele almak | Taklit, hazırlanmış bir örnek veya küçük bir test, tüm sistemin sıradan kullanımda çalıştığının kanıtı olarak sunuldu. | Neyin test edildiğini tam olarak belirtin ve sonucun daha fazlasını kanıtladığını iddia etmeyin. |
| Yanlış izinlerle test etme | Canlı programın farklı izinlerle çalışmasına rağmen geliştiricinin erişimi kullanılarak yapılan bir kontrol. | Canlı program tarafından kullanılan aynı hesap ve izinlerle test edin veya sonucu kanıtlanmadan bırakın. |
| Bir hatayı kaydetmeden önce onarmak | Bir hata, açıklanmadan önce onarılarak plağın eserden daha temiz görünmesi sağlandı. | Arızayı ve düzeltmeyi sırasıyla koruyun. Onarımın kanıtları silmesine izin vermeyin. |
| Kullanıcının önünde tekrarlanan revizyon | Planlama ilk sonucun sonrasına ertelendiği için sonuç kullanıcının önünde tekrar tekrar revize edildi. | İnceleme talebinde bulunmadan önce materyali seçin ve tüm sonucu planlayın. Mümkün olduğunda sınırlı bir taslak sunun. |
| Eksik bir düzenlemeyle canlı bir hizmeti bozma | Bir dil modeli, çalışan bir dosyanın yalnızca bir kısmını değiştirdi ve devam etti. Çalışan hizmet işini tamamlayamamıştı. | Dosyanın tamamı geçerli olana ve asıl hizmet amaçlanan işi tamamlayana kadar bir değişikliği tamamlanmamış olarak değerlendirin. |
| Bir ayarın yanlış kopyasını değiştirme | Bir dil modeli ana ayarlar dosyasını düzenledi, hizmeti yeniden başlattı, başarılı bir yeniden başlatma yanıtı aldı ve başarı bildirdi. Hizmet farklı oluşturulmuş bir kopya kullandığından eski ayar etkin kaldı. | Yalnızca düzenleme veya yeniden başlatma mesajını değil, görünür sonucu da doğrulayın. Ana ayardan hizmetin gerçekte kullandığı kopyaya giden açık bir yol tutun. |
| Sorunu çözmeyen tekrarlanan düzeltmeler | Bir problem için dört değişiklik yapıldı. Her biri bazı kodların çalıştığını kanıtladı, ancak hiçbiri asıl sorunun ortadan kalktığını kanıtlamadı. | Düzenlemeden önce değişmesi gereken sonucu tanımlayın. Her değişiklikten sonra sonucu doğrudan test edin. |
| Canlı hizmetin erişimi kontrol ediliyor | Kişinin hesabı üzerinden test edildiğinde bir klasör çalıştı ancak canlı hizmet farklı bir hesap kullandı ve yine de bu klasöre ulaşamadı. | Denetimi canlı hizmetle aynı koşullar altında çalıştırın. |

## Kimin neyi söyleyebileceği veya onaylayabileceği konusundaki başarısızlıklar

| Gözlemlenen başarısızlık | Ne oldu | Dil modelinin dışına koruma eklendi |
|---|---|---|
| Farklı işler aynı muameleye tabi tutulur | Gözlemciler, yazarlar, dama, çalışmayı bırakabilecek kişiler ve serbest bırakmayı onaylayanlar aynı muameleye tabi tutuldu çünkü her biri sonuca dokundu. | Her parçanın belirlenmiş bir işi ve neye karar verebileceği konusunda sınırları vardır. Bir yazar bir iddiayı doğrulayamaz. Bir gözlemci yayınlayamaz. |
| İkame değerleri gerçek olarak gösterme | Ekranlarda boş ölçümler veya makul ikameler görüntüleniyor, böylece kurulum tamamlanmış görünüyordu. | Ölçülen değeri ve nereden geldiğini gösterin veya mevcut olmadığını açıkça belirtin. |
| Bir sayfayı yenilemek kullanıcının yerini yok etti | Yenileme tüm sayfanın yerini aldı ve odağı, seçimi, kaydırma konumunu veya kopyalamayı yok etti. | Ekranı bir insanın çalışma alanı olarak değerlendirin. Kullanıcının yerini bozmadan değişen değerleri güncelleyin. |
| Şifreleri korumasız metinde tutmak | Parolalar ve erişim anahtarları korumalı depolama yerine sıradan dosyalara yerleştirildi. | Bunları korumalı bir depoda saklayın ve yayınlanmadan önce her dosyayı kontrol edin. |
| Bir hizmetin çalışmaya devam ederken durdurulduğunu bildirme | Durdurma isteği başarıyla geri döndü ancak süreç çalışmaya devam etti. | Bir kontrol talebinden sonra süreci ve gerçek etkisini kontrol edin. Talebi sonuç olarak bildirmeyin. |

## İnsan dikkati başarısızlıkları

| Gözlemlenen başarısızlık | Ne oldu | Dil modelinin dışına koruma eklendi |
|---|---|---|
| Bir kişinin sözlerini doldurmak | Kısa bir insan ifadesi, orijinal kelimeleri bulmak zorlaşıncaya kadar oluşturulan materyalle genişletildi. | Orijinal bildirimi ana kayıt olarak koruyun. Oluşturulan yorumlama ayrı ve isteğe bağlı kalır. |
| Dairesel yazı | Yararlı içerik tükendikten sonra yanıt açıklandı, yeniden ifade edildi, özetlendi ve sonuçlandırıldı. | İstenen sonuç tamamlandığında durun. Tekrarlanan sonuçları kaldırın. |
| Cevabı gömmek | Kullanıcının talep etmediği ekran dolusu materyalin içine bir veya iki yararlı bilgi yerleştirildi. | En kısa tam cevabı ilk sıraya koyun ve daha derin materyali isteğe bağlı hale getirin. |
| Sunulmamış ilgiyi harcamak | Doğru ama gereksiz açıklama, okuyucuyu bunun gereksiz olduğuna karar vererek zaman harcamaya zorladı. | Okumayı ve düzeltmeyi gerçek maliyetler olarak sayın. Okuyucunun isteğe bağlı derinliği başlatmasına izin verin. |
| Çok fazla vurgu | Neredeyse her nokta kalın harflerle yazılmış, başlı veya bir tabloya yerleştirilmişti, dolayısıyla gerçek uyarılar artık göze çarpmıyordu. | Yalnızca karar veya güvenlik yükünü taşıyan birkaç ayrım için vurgu yapın. |

## Maliyet ve sağlayıcı teşviklerini içeren başarısızlıklar

| Gözlemlenen başarısızlık | Ne oldu | Dil modelinin dışına koruma eklendi |
|---|---|---|
| Varsayılan olarak kullanılan ücretli bir büyük dil modeli | İş, basit bir sabit süreç, kaydedilen sonuç veya sınırlı bir araç bunu daha güvenilir bir şekilde yapabildiğinde bile mevcut olduğu için ücretli bir çevrimiçi model aracılığıyla gönderildi. | İşin tam değerini ve maliyetini ölçün. Çalışması kontrol edilebilecek ve doğrulanabilecek en küçük araç kombinasyonunu seçin. |
| Düzeltme maliyeti toplamlardan kayboldu | Kötü bir sonuçtan sonra yeniden denemeler, tekrarlanan bağlam, bekleme ve insan düzeltmesi, ücretli ödenek kullanılmasına ve kişinin daha fazla zaman ve enerjisine ihtiyaç duymasına rağmen ücretsiz olarak değerlendirildi. | Gerçek maliyetin bir parçası olarak beklemeyi, yeniden denemeyi, reddetmeyi, tekrarlanan hizmet kullanımını ve insan dikkatini kaydedin. |
| Başarısız çalışma için kota iade edilmez | Kullanılamayan çıktı ve bunu düzeltmek için gereken değişimler, ödenen kotaya dahil edildi. Kişi, kaybedilen ödenek veya zamanın yerine otomatik olarak yenisini alamadı. | Kayıt başarısız oldu ve düzeltici kullanım ayrı ayrı. Aynı hatanın tekrar yaşanmaması için kaydedilen bağlamı ve reddedilen sonuçları yeniden kullanın. |
| Yararlı başarısızlık atıldı | Reddedilen bir yanıt ortadan kayboldu, bu nedenle daha sonra çalışma aynı hatayı tekrarladı ve bedelini yeniden ödedi. | Reddedilen sonuçları ve reddedilme nedenlerini kabul edilen bilgilerin dışında tutun. Desteklenmeyen iddiayı kabul etmeden dersi yeniden kullanın. |
| Aynı bağlamın tekrar sağlanması gerekiyordu | Daha önceki bilgiler dil modelinin çalışma görünümünden kaybolduğunda, kişinin isteği yeniden yapılandırması ve ücretli bir oturumda zaten sağlanan geçmişi yeniden göndermesi gerekiyordu. | Kalıcı bağlamı hizmetin dışında tutun. Her iş için sınırlı bir paket oluşturun ve geri gönderilen çalışmayı, düzeltmeyi ve reddetmeyi daha sonra kullanmak üzere saklayın. |

## Bu hizmet başarısızlıkları nasıl bu projenin tasarımı haline geldi?

Gözlenen sorun zayıf bir modelle sınırlı değildi. Aynı geçici asistanın hafıza, tarihçi, plancı, yazar, denetleyici ve kendi işinin yargıcı olarak görev yapması isteniyordu. En güçlü ücretli modeller bile, onu diğer her şeye bağlayan insanlık tarihini kaybederken bireysel bir görevi başarabilir.

Robot Brain bu işleri ayrı parçalara ayırır. Kaynak koruyucusu olayı korur. Odaklanmış yerel okuyucular tanımlanmış özellikleri inceler. İstek oluşturucu tek bir amaç için kanıt toplar. Bir model arka plana veya ifadeye katkıda bulunabilir. Neyin kabul edileceğine bağımsız kontroller ve insan onayı karar verir.

Geçmiş ücretli hizmetin dışında kalır. Bir model, seçilen bir işte yardımcı olabilir, ancak kişinin hayatını saklamaz veya daha önce yapılmış bir işi kullanmanın tek yolu haline gelmez.

Yerel modelde de aynı sınır vardır. Kişinin kayıtları üzerinden eğitim verilmemektedir. Seçilen materyali okur, tarihli bir öneri döndürür ve değiştirilebilir. Kişinin sözleri, zamanı, tecrübesi, kararları, başarısızlıkları ve düzeltmeleri değerli olan kısımdır.
