> Türkçe: Yetkili İngilizce kaynağın makine destekli çevirisi. Ana dildeki düzeltmeler memnuniyetle karşılanır. [İngilizce](../../15-Why-a-Language-Model-Is-a-Replaceable-Tool.md) | [Tüm diller](../README.md)

# Bellek olarak değil, iş için bir dil modeli kullanın

![Araçlar, eğitilmiş dosyalar ve kaynak koleksiyonları, kökenlerine ve terimlerine ilişkin ayrı kayıtlar tutar.](../../illustrations/tool-model-source-index.png)

Robot Brain ekstra belleğe sahip bir dil modeli değildir. Bir dil modelinin ne zaman yardımcı olacağına ve hangi sınırlı işi gerçekleştirebileceğine karar veren, kayıt tutma, analiz, birleştirme ve kontrol yazılımıdır.

Mevcut en güçlü model her zaman bu iş için en iyi seçim olmayabilir.

Ücretli bir dil modeli zorlu araştırma veya yazılar için uygun olabilir. Arka plan açıklaması için küçük bir yerel model yeterli olabilir. Bir geçit bulmak için arama yeterli olabilir. Yanıtın kesin bir kurala uyması gerektiğinde sabit bir süreç daha güvenli olabilir. Bazen en iyi yanıt, daha önce kontrol edilmiş ve kaydedilmiş olan yanıttır.

İstek oluşturucu işin gereksinimlerine göre bu seçimi yapar. Bir model kullanabilir, birkaç sınırlı yöntemi birleştirebilir, kontrol edilen çalışmayı yeniden kullanabilir veya hiçbir model çağrısı yapmayabilir. Bu nedenle bu, istekleri başka bir hizmete ileten bir proxy değildir.

## Ücretli çevrimiçi modeller

Ticari dil modeli hizmetleri bu projenin oluşturulmasına yardımcı oldu. Araştırmayı, kodlamayı, yazmayı ve incelemeyi desteklediler.

Ayrıca daha önceki talimatları kaybettiler, konuşmaları kısalttılar, nedenleri tahmin ettiler, kısa cevapları doldurucuya gömdüler ve kontrol etmeden önce işi tamamlanmış olarak bildirdiler. Bu başarısızlıkların düzeltilmesi için daha fazla ödenen ödenek ve daha fazla insan zamanı kullanıldı.

Daha derin sınırları kötü bir ipucu değil. Eğitilmiş bir model, kendisine öğreten insan çalışmasının tüm geçmişini yeniden oluşturamaz. Her yazara, amaca, izleyiciye, tartışmaya, düzeltmeye ve eksik bakış açısına olan güvenilir bağlantıları kaybederken kalıpları korur.

Bu geniş bilgi hala faydalıdır. Birinin tarihinin var olduğu tek yer burası olmamalıdır.

Çevrimiçi talep için,Robot Brain hangi modelin kullanıldığını, ne aldığını, neleri iade ettiğini, hizmet bedelinin ne kadar olduğunu, hangi kontrollerin yapıldığını ve sonucun tutulup tutulmadığını kaydeder. Desteklenmeyen arka plan, kaynaklı bir gerçek olmaktan ziyade modelin önerisi olmaya devam ediyor.

## Yerel model kişiye göre eğitilmiyor

Mevcut kurulum küçük bir çalışma yürütüyorQwendil modelivLLMyerel donanım hakkında.Qwenprojenin kendisi değil, değiştirilebilir bir katılımcıdır.

Kişinin konuşmalarını, işini, hayatını eğitim alarak öğrenmez. Eğitim, bu tarihi bir modele karıştıracak ve orijinal kelimelere ve olaylara giden yolu zayıflatacaktır.

Yerine,Qwenbir konuşma bittikten sonra bir iş için seçilen materyali alır. Diğer yerel yöntemler, alışverişteki dili, ifadeleri, ilişkileri, akıl yürütmeyi, zamanı, insan deneyimini ve değerleri zaten incelemiştir.Qwenbu yöntemlerin paylaşmadığı geniş arka planı ekler. Bu, ne olduğunu ve nedenini açıklamayı kolaylaştırır.

Qwençevrimiçi asistanın gizli düşüncelerini, eğitimini veya özel mantığını açığa çıkarmaz. Çevrimiçi asistanın yararlı katkısı kayıtlı görüşmede zaten mevcuttur. Genel arka plan bilgisi bu asistana özgü değildir, dolayısıyla başka bir uygun model kaydedilen parçaların birbirine bağlanmasına yardımcı olabilir.

Qwenokuma model adı ve tarihiyle birlikte kaydedilir. Konuşmadan ayrı kalır ve daha sonra düzeltilebilir veya değiştirilebilir. İsteğin hiçbir zaman yerel donanımdan ayrılması gerekmez.

## Arama bir açıklama değil

Arama, ilgili kelimeleri veya konuları içeren pasajları bulabilir. Bir olayın neden önemli olduğuna, bir eylemin diğerine neden olup olmadığına ya da birinin ne demek istediğine karar veremez.

Bu sonuçların kanıta, tarihe ve düzeltilecek alana ihtiyacı var.

## Maliyet, kişinin zamanını içerir

Maliyetler yalnızca fiyat ve hız değildir. Birisi hatayı bulmak, geçmişi tekrar açıklamak ve sonucu onarmak için saatler harcadığında ucuz bir cevap pahalı hale gelir.

Bu nedenle istek oluşturucu hizmet ücretlerini, beklemeyi, yeniden denemeleri, enerji kullanımını ve insan kontrolünü dikkate alır. Daha küçük bir model, sabit bir yerel yöntem veya kayıtlı bir sonuç, çalışmasının incelenmesi daha kolay olduğunda daha fazla değer yaratabilir.

## Kaynaklar tanımlanabilir olmaya devam ediyor

Orijinal kayıtlar, kopyalanan metinler, örnek yanıtlar, kamuya açık araştırmalar, alıntılar ve daha sonra yapılan incelemeler farklı şeyler olarak kalır.

Bilindiğinde ve izin verildiğinde kayıt, yaratıcıyı, amacı, hedef kitleyi, tarihi, dili, kanıtları, anlaşmazlıkları, hakları ve daha sonra yapılacak düzeltmeleri tutar. Kamuya açık olma ve kredi, tek başına, korunan materyalin yeniden dağıtımına izin vermez.

Bu depo, kamuya açık belgeleri ve proje tarafından oluşturulan illüstrasyonları içerir. Özel kayıtları, şifreleri, erişim ayrıntılarını, sağlayıcı sırlarını ve yayınlanmak üzere onaylanmamış dış materyalleri dışarıda bırakır.
