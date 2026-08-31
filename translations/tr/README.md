> Türkçe: Yetkili İngilizce kaynağın makine destekli çevirisi. Ana dildeki düzeltmeler memnuniyetle karşılanır. [İngilizce](../../README.md) | [Tüm diller](../README.md)

# Kaydı sakla. Modeli değiştirin.

![Bir kişinin kayıtları tek bir yerde kalırken, ayrı çalışma bölümleri sınırlı işleri gerçekleştirir.](../../illustrations/specialist-assembly-line-vs-giant-chatbot.png)

Robot Brain uzun süredir devam eden insan çalışmasının arkasındaki tarihi ve anlamı korumaya yönelik bir yazılımdır. Bir dil modeli, bir chatbot ya da her soruyu bir modele ileten bir hizmet değil.

Büyük dil modelleri zor problemleri araştırabilir, yazabilir, açıklayabilir ve çözmeye yardımcı olabilir. Bunların etrafında oluşturulan ücretli hizmetler hâlâ geçici çalışma alanlarıdır. Uzun bir konuşmayı kısaltabilir, daha önceki talimatları kaybedebilir, sonuçları kanıtlardan ayırabilir ve kayıp tarih hâlâ oradaymış gibi yazmaya devam edebilirler. Daha sonra kişi, halihazırda sağlanan bağlamı yeniden oluşturmak için daha fazla zaman ve ücretli kullanım harcar.

Bu yazılım, kalıcı değerin yaşadığı yeri değiştirir. Kişinin konuşmaları, belgeleri, kararları, başarısız girişimleri, düzeltmeleri, cevaplanmayan soruları kişinin kontrolündeki kayıtlarda kalır. Yerel programlar bu kayıtları inceleyebilir. Bir dil modeli seçilen bir işe yardımcı olabilir, ancak katkısı eski ve gözden geçirilebilir bir çalışma olarak kayıtlara geri döner. Model daha sonra geçmişi götürmeden değiştirilebilir.

[Bu belgeleri başka bir dilde okuyun.](../README.md)

## Tek görünümdeki fark

| Ticari bir dil modeli hizmeti | Robot Brain |
|---|---|
| Şu anda çalışma görünümünde olan malzemeden bir yanıt üretir. | Kaynağın tamamını ve etrafındaki geçmişi tutar. |
| İş büyüdükçe daha önceki konuşmaları kısaltabilir veya kaybedebilir. | Tekrar kullanılabilmeleri için konuşmaları her modelin dışına kaydeder. |
| Birçok kaynaktan öğrenilen bilgiyi, her kaynağa ve onun koşullarına giden tam bir yol olmaksızın harmanlar. | Bilinen her kaynağı, daha sonra bulunanları, düzeltmeleri ve anlaşmazlıkları ayrı bir kayıt olarak tutar. |
| Tek bir alışverişte kendi cevabını yazabilir, arayabilir, planlayabilir ve değerlendirebilir. | Sınırlı yetki ile ayrı ayrı parçalara kaydetme, arama, analiz etme, yazma, kontrol etme ve onaylama verir. |
| Modeli, hizmet kurallarını, kullanım sınırlarını ve ürün değişikliklerini kontrol eder. | Kalıcı kaydı kişinin kontrolüne bırakır. |
| Başarısız girişimler ve düzeltici değişimlerin yanı sıra faydalı işler için de ödeme yapılır. | Başarısızlıkları ve düzeltmeleri saklar, böylece derslerinin tekrar satın alınmasına gerek kalmaz. |

Robot Brain yerel veya çevrimiçi bir dil modeli olarak adlandırılabilir. Bu onu bir model proxy'ye dönüştürmez. Orijinal görüşmede yer alan modeli çağırmadan önceki çalışmaları koruyabilir, arayabilir, karşılaştırabilir, düzenleyebilir ve yeniden oluşturabilir. Bir model yararlı olduğunda istek, o modelden bağımsız olarak var olan daha büyük bir süreçteki bir adımdır.

## Bu neden inşa edildi

Geliştirme sırasında mevcut olan en güçlü ücretli genel amaçlı modeller, uzun çalışmanın yetenekli ancak güvenilmez koruyucularıydı.

Kaydedilen hatalar arasında kayıp talimatlar, eksik deliller, icat edilmiş bağlantılar, zamanından önce tamamlanma iddiaları, istenmeyen değişiklikler ve çalışma dosyalarındaki hasar yer alıyordu. Bu başarısızlıkların düzeltilmesi daha fazla talep, daha fazla test, daha fazla ödenek ve kişinin daha fazla zaman ve enerji harcamasını gerektirdi. Hizmetler, kullanılamayan işler için harcanan kullanımı veya onarım için gereken değişimleri otomatik olarak iade etmedi.

Sorun herhangi bir kötü cevaptan daha büyüktü. Geçici bir metin oluşturucunun hafıza, tarihçi, araştırmacı, yazar, denetleyici ve son yargıç olarak görev yapması isteniyordu. Modellerin değiştirilmesi bu düzenlemeyi değiştirmedi.

Robot Brain farklı bir düzenleme etrafında inşa edildi: önce insan kaydını tutun, birkaç değiştirilebilir parçanın buna katkıda bulunmasına izin verin ve önemli bir iş kabul edilmeden önce üretim modelinin dışında kanıt isteyin.

## Eğitimli bir modelin tutamadığı şeyler

Büyük bir dil modeli, muazzam insan çalışması koleksiyonlarından kalıpları öğrenir. Bu desenler modeli kullanışlı kılar ancak model, onu şekillendiren tüm eserlerin bulunduğu bir kütüphane değildir.

Modelin içinde kitaplardan, makalelerden, konuşmalardan, çevirilerden, topluluklardan, etiketlerden ve insan geri bildirimlerinden gelen etkiler bir araya getiriliyor. Model genellikle belirli bir cümleyi hangi kaynakların şekillendirdiğini gösteremez. Her yazarın amacını, hedef kitlesini, kanıtlarını, anlaşmazlıklarını, daha sonra düzeltmelerini veya eksik bakış açılarını geri getiremez.

Orijinal eser hâlâ başka bir yerde mevcut olsa bile bu bir anlam kaybıdır. Model, insani ortamına giden güvenilir yolu bir kenara atarken, çalışmanın bazı yararlılıklarını da koruyor.

Aynı sorun normal kullanımda da ortaya çıkıyor. Ona anlam veren konuşma kısaltıldıktan sonra nihai bir cevap hayatta kalabilir. Sonuç kalır ancak başarısız girişimler, belirsizlik ve bunun arkasındaki nedenler modelin çalışma görüşünden kaybolur.

Bu proje, bir insanın hayatı üzerine başka bir model eğiterek bu soruna cevap vermiyor. Kişisel geçmiş, başka bir eğitimli modelle harmanlanmak yerine okunabilir ve izlenebilir kalır. Modeller seçilen kayıtlarla çalışır; kayıt haline gelmezler.

## Her parça ne yapar?

Çalışan yazılım, bir sohbet hizmetinin sıklıkla tek bir aktivite gibi göründüğü işleri ayırır:

1. **Kaynak koruyucusu olanları kaydeder.** Konuşmayı, belgeyi, resmi veya diğer materyali bir özetle değiştirmeden korur.
2. **Aranabilir kopyalar, kaynağın bulunmasını kolaylaştırır.** Kopyalanan metin, açıklamalar ve dizinler, değiştirilmemiş kaynağa işaret eder ve yeniden oluşturulabilir.
3. **Odaklanmış yerel okuyucular belirli özellikleri inceler.** Ayrı yöntemler dil, ifadeler, ilişkiler, akıl yürütme, zaman, insan deneyimi ve değerlere bakar. Her biri yalnızca kendi bulgularını ve bunların arkasındaki pasajları aktarıyor.
4. **Geçmiş kaydı, değişimi görünür tutar.** Yeni bulgular, düzeltmeler, anlaşmazlıklar, başarısız girişimler ve açık sorular, daha önceki olaylar yeniden yazılmadan eklenir.
5. **İstek oluşturucu bir işin ihtiyaç duyduğu şeyleri toplar.** İlgili kaynakları ve bulguları seçip dahil edilenleri veya dışarıda bırakılanları kaydeder.
6. **Dil modeli sınırlı yardım sağlayabilir.** Yerel bir model geniş bir arka plan sağlayabilir. Çevrimiçi bir model, zor araştırma veya yazma işlerinde yardımcı olabilir. Her iki yanıt da kontrol edilebilecek, reddedilebilecek veya değiştirilebilecek tarihli bir katkı olarak kalır.
7. **Ayrı kontroller, sonucu istek ve kanıtlarla karşılaştırır.** Cevap yazan model, kendi çalışmasının kabul edildiğini beyan edemez.
8. **Ekran, kişinin yazılımı kullanmasına olanak tanır.** Birlikte verilenlerLibreChatçatal böyle bir ekrandır. Değiştirilmesi plakların veya diğer çalışan parçaların değiştirilmesi anlamına gelmez.

Hiçbir parça tek başına her şeyi bilen bir yardımcı olarak sunulmuyor. Her bir parçayı değiştirilebilir kılan şey sınırlı işleridir.

## Tamamlanmış bir görüşmeyi yeniden faydalı hale getirmek

Tamamlanan bir konuşma, kişinin isteğini, dil modelinin gerçek yanıtlarını, denenen işi, başarısızlıkları, düzeltmeleri ve alışverişin sona erdiği noktayı içerir. Bu mesajlar, orijinal modelin daha sonra kendisini açıklamasına gerek kalmadan, orijinal modelin katkısını korur.

Odaklanmış yerel okuyucular kaydedilen alışverişi çeşitli açılardan inceler. Geniş dünya bilgisine güvenmeden ayrıntılı kalıpları ve ilişkileri bulabilirler. Ayrı bulguları, konuşmanın belirli bölümleriyle bağlantılı olmaya devam ediyor.

Bu bulguların net bir açıklama oluşturmadan önce hâlâ sıradan arka plan bilgisine ihtiyacı olabilir. Bu sınırlı adım için küçükQwenmodel yerel olarak çalışırvLLM. Ayrıntılı bulguları birleştirmeye ve değişimin neyi başardığını açıklamaya yardımcı olan tarihli bir genel bakış ekler.

Qwençevrimiçi modelin gizli düşüncelerini veya eğitim geçmişini kurtarmaz. Orijinal modele özgü olmayan geniş bir arka plan bilgisi sağlar. Orijinal modelin faydalı katkısı, ürettiği kelimelerde zaten korunmaktadır.

Qwengenel bakış kaynağın ve önceki bulguların yanında saklanır. Düzeltilebilir veya değiştirilebilir. Orijinal görüşme ve ayrıntılı yerel analiz değişmeden kalır.

## Şu anda ne çalışıyor?

Mevcut uygulama, tamamlanmış bir konuşmayı koruyabilir, ayrı yerel yöntemlerle inceleyebilir, yerel bir genel bilgi okuması ekleyebilir ve tutulan her katkıyı daha sonra yeniden oluşturulabilecek bir kayıtta toplayabilir.

Ayrıca dışarıdan yardımın yararlı olacağı durumlarda çevrimiçi bir model için sınırlı bir talep hazırlayabilir. Bu hizmet yalnızca seçilen materyali alır. Cevabı, neyin tutulacağına modelin değil, çeklerin ve insan onayının karar verdiği yerel kayıtlara dönüyor.

Temel başarı budur: Bir zamanlar geçici bir konuşmaya bağlı olan işler, sohbet ekranı, modeli ve sağlayıcısı gittikten sonra da yararlı olmaya devam edebilir.

## Açıklamanın tamamını okuyun

- [Büyük dil modelleri neden hikayenin tamamını koruyamıyor?](01-Why-Large-Language-Models-Cannot-Preserve-the-Full-Story.md)
- [Her bir parça ne yapar ve hiçbir model neyi kontrol etmez?](02-A-Lasting-Record-Outside-the-Model.md)
- [Hatayı silmeden düzeltmeyi sürdürün](03-How-Knowledge-Changes-Without-Erasing-History.md)
- [Bir iddiayı kanıtlara kadar takip edin](04-How-Every-Claim-Can-Be-Checked.md)
- [Düzyazıyı yazmadan önce belgeyi oluşturun](05-How-Evidence-Becomes-a-Finished-Document.md)
- [Aynı gerçeği farklı okuyuculara açıklayın](06-One-Meaning-Different-Readers.md)
- [Özel geçmişi kişinin kontrolü altında tutun](07-Privacy-and-Control-Stay-With-People.md)
- [Mevcut uygulama ne yapıyor?](08-What-Works-Today.md)
- [Tasarım neden birçok alandan ilham alıyor?](09-How-Research-Strengthens-the-System.md)
- [Özel kayıtları teslim etmeden yardım](11-Contribute-Without-Giving-Up-Control.md)
- [Bu belgelerde kullanılan kelimeler](12-A-Short-Guide-to-Key-Terms.md)
- [Çalışan parçalar aracılığıyla bir isteği takip edin](13-The-Parts-Running-Today.md)
- [Bellek olarak değil, iş için bir dil modeli kullanın](15-Why-a-Language-Model-Is-a-Replaceable-Tool.md)
- [Ücretli dil modeli hizmetlerinde gözlemlenen başarısızlıklar ve bunların yol açtığı önlemler](16-What-Commercial-Language-Model-Services-Got-Wrong.md)
- [Tasarımı değiştiren dersler](17-How-Language-Models-Lose-Meaning-and-How-to-Preserve-It.md)
- [Kamu kullanımı, kredi ve gizlilik notları](18-Use-Attribution-and-Limits.md)
- [Tamamlanmış bir konuşma nasıl kalıcı bilgiye dönüşür?](19-What-the-System-Accomplishes.md)
- [Sırada ne var](20-Where-the-System-Goes-Next.md)

## Krediler, kaynaklar ve haklar

- [Bu çalışmanın şekillenmesine ne yardımcı oldu?](10-What-Helped-Shape-This-Work.md)
- [Tasarımın arkasındaki araştırma](14-Sources-Behind-the-Design.md)
- [Kaynaklar, lisanslar ve kamuya açık kontroller](../../SOURCES-LICENSES-AND-PRIVACY.md)

## Lisans

Projenin orijinal yazımı, diyagramları ve illüstrasyonları organizasyonun web sitesinde mevcuttur.[Creative Commons Atıf 4.0 Uluslararası lisansı](../../LICENSE.md)bir belgede farklı terimler belirtilmediği sürece. Başkaları tarafından oluşturulan materyaller kendi haklarını ve koşullarını korur.

## Bağımsızlık ve gizlilik

Bu, kişisel zaman, ekipman, hesaplar ve ücretli hizmetler üzerine geliştirilen bağımsız bir kişisel projedir. Hiçbir işveren buna katılmadı. Herhangi bir kişiden, işverenden, kurumdan, model sağlayıcıdan, araştırma grubundan, ortak kuraldan veya proje dışı projeden bahsetmek katılım, onay, ortaklık veya onay anlamına gelmez.

Kamuya açık sürüm, özel kayıtları, tanımlayıcı ayrıntıları, şifreleri, özel bağlantı bilgilerini, işveren bilgilerini ve özel hizmetlere erişim talimatlarını içermez. Model hatalarının açıklamaları kaydedilen davranış ve bunun etkisiyle sınırlıdır; açıklanmayan sebep veya saikleri iddia etmezler. Belgeler profesyonel tavsiye veya sonuç vaadi değildir.

![Sağlayıcı tarafından kontrol edilen hafızadan, ilgilendikleri kişilerin elinde kalan kayıtlara giden bir yol.](../../illustrations/open-door-human-future.png)
