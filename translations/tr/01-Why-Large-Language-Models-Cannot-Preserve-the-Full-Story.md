> Türkçe: Yetkili İngilizce kaynağın makine destekli çevirisi. Ana dildeki düzeltmeler memnuniyetle karşılanır. [İngilizce](../../01-Why-Large-Language-Models-Cannot-Preserve-the-Full-Story.md) | [Tüm diller](../README.md)

# Büyük dil modelleri neden hikayenin tamamını koruyamıyor?

![Kaydedilen parçalar, kaynakları, ilişkileri ve geçmişi birbirinden ayrıldığında değer kaybeder.](../../illustrations/ordinary-storage-loses-context.png)

Bu projeyi oluştururken kullanılan en güçlü ücretli dil modelleri etkileyici işler yapabilir. Zor problemleri yazabilir, araştırabilir, açıklayabilir ve çözmeye yardımcı olabilirler. Uzun bir projenin ardındaki tarihin tamamını hâlâ koruyamadılar.

Daha sonraki bir yanıt, sonucu hatırlayabilir ancak başarısız girişimleri, düzeltmeleri ve buna yol açan kanıtları kaybedebilir. Konuşma çok uzadığında önceki talimatlar kaybolabiliyordu. Model sanki önemli hiçbir şey kaybolmamış gibi yazmaya devam edecekti.

Eksik geçmiş birinin zamanını, bilgisini veya deneyimini temsil ediyorsa bu ciddi bir sorundur.

## Dosyalar yeterli değil

Bir klasör her notu, konuşmayı, resmi ve görevi barındırabilir ancak bunları birbirine bağlayan hikayeyi kaybetmeye devam edebilir.

Aylar sonra kişinin şunları bilmesi gerekebilir:

- işi ne başlattı
- hangi fikirler dikkate alındı
- neden bir deneme başarısız oldu
- planı hangi kanıt değiştirdi
- hangi sonuç güncel
- hala bilinmeyen ne
- Eski bir not neden şimdi önemli?

Arama, benzer sözcükleri içeren bir dosyayı bulabilir. Bu sorulara güvenilir bir şekilde cevap veremez. Daha büyük bir dosya yığınını bir dil modeline göndermek de kalıcı bellek oluşturmaz. Hizmet, bu istek için neyin seçildiğini görür. İstek sona erdiğinde yararlı bağlantılar yeniden kaybolabilir.

## Eğitim aynı zamanda orijinal ayarı da kaybeder

Dil modelleri, insan çalışmalarının muazzam koleksiyonundan kalıpları öğrenir. Onları yararlı kılan da budur. Onları şekillendiren her şeyin sadık bir arşivi olarak hareket edememelerinin nedeni de budur.

Bir kitaptan, makaleden, sohbetten, çeviriden veya topluluktan gelen fikirler, diğer birçok kişinin fikirleriyle karışır. Model, her eseri yazarı, amacı, hedef kitlesi, delilleri, anlaşmazlıkları ve sonradan yapılan düzeltmelerle birlikte eksiksiz tutmaz.

Orijinal eser hâlâ başka bir yerde mevcut olabilir. Sağlayıcı ayrıca ayrı kopyalar da tutabilir. Burada açıklanan kayıp, eğitimli modelin içinde meydana gelir: çalışmanın yararlı etkisini korur ancak etrafındaki tüm insani anlamı yeniden inşa edemez.

Bir cümleyi tekrarlamak o anlamı korumakla aynı şey değildir. Bir model, neden yazıldığını, hangi durumu anlattığını, kimin görüşünün eksik olduğunu veya daha sonra ne olduğunu bilmeden tanıdık kelimeleri yeniden üretebilir.

## Eksik tarih aynı zamanda önyargıyı da gizliyor

Bütün dünyadan öğrenilen bir dil modeli yok.

Bilgisi yazılanları, saklananları, toplananları, tercüme edilenleri, lisanslananları, etiketlenenleri ve seçilenleri yansıtır. Aynı zamanda neyin eksik olduğunu da yansıtıyor. Bazı diller ve topluluklar diğerlerinden çok daha fazla yayınlanmış materyale sahiptir. Arşivler güçlü kurumların görüşlerini özel, yerel veya sözlü bilgilerden daha sık korur.

Modeli oluşturan insanlar neyi çıkaracakları, ödüllendirecekleri, caydıracakları veya iyi bir cevap olarak değerlendirecekleri konusunda daha fazla seçim yaparlar. Ürün kuralları başka bir katman ekler. Tamamlanmış bir yanıt, hangisinin belirli bir cümleyi etkilediğini göstermeden bu etkilerin tümünü taşıyabilir.

Yeni bir talep sırasında bulunan bir alıntı bu tarihin tamamını ortaya çıkarmaz. Modele konuyu nasıl yorumlayacağını öğreten her şeyi değil, o istek için kullanılan veya adlandırılmış bir kaynağı gösterir.

## Bunun yerine bu projenin sakladığı şey

Robot Brain Herhangi bir modelden yorumlanmasında yardım istemeden önce kaynağı saklar. Özet, düzeltme veya yeni yorum eklendiğinde kaynak değişmez.

Daha sonra yapılan çalışmalar, bir tarih ve ilgili pasaja giden bir bağlantıyla birlikte yanına kaydedilir. Başarısız bir girişim görünür durumda kalabilir. Düzeltilmiş bir sonuç, onu değiştiren kanıtlara işaret edebilir. Bir değişikliğin nedeni bilinmiyorsa kayıtta öyle yazıyor.

Birisinin bir cevaba veya belgeye ihtiyacı olduğunda, istek oluşturucu bu geçmişin iş için gereken kısmını toplar. Sonuç, onu değiştirmeye gerek kalmadan tam kayıttan daha kısa olabilir.

Bir dil modeli bu sonuca yardımcı olabilir. Kaynakları silemez, geçmişi yeniden yazamaz veya desteklenmeyen bir tahminin kabul edilen kayıtların bir parçası haline gelmesini sağlayamaz.

## Pratik test

Yararlı bir sonuç, okuyucunun dört soruyu yanıtlamasına olanak tanımalıdır:

1. Ne oldu?
2. Bu anlatımı hangi kanıtlar destekliyor?
3. Ne değişti, başarısız oldu ya da tartışmalı kaldı?
4. Hala bilinmeyen ne?

Kayıt bu sorulardan birine cevap veremezse, cilalı dil boşluğu gizlememelidir.
