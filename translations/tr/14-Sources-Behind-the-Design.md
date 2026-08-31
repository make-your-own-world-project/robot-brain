> Türkçe: Yetkili İngilizce kaynağın makine destekli çevirisi. Ana dildeki düzeltmeler memnuniyetle karşılanır. [İngilizce](../../14-Sources-Behind-the-Design.md) | [Tüm diller](../README.md)

# Tasarımın arkasındaki araştırma

![Farklı araştırma gelenekleri kendi tarihlerini korurken sınırlı yöntemlere katkıda bulunur.](../../illustrations/academic-framework-lineages.png)

Bu sayfa araştırma izini isteyen okuyucular içindir. Ana açıklama bunu gerektirmez.

Liste, kullanılan, test edilen, karşılaştırılan, reddedilen veya yalnızca üzerinde çalışılan fikirleri ve araçları içerir. Bu ilişkiler aynı değil. Bir kaynağın listelenmesi, yazarlarının projeye katıldığı veya projeyi desteklediği anlamına gelmez.

## Kaynakları ve zaman içindeki değişiklikleri korumak

- Kaynak geçmişi ve değişen bilgiler üzerine yapılan araştırmalar, kayıtların malzemenin nereden geldiğini, ne zaman uygulandığını ve daha sonra onun yerini ne aldığını tutma şeklini şekillendirdi.
- [Grafiti](https://github.com/getzep/graphiti)zamanla değişen bağlantıları kaydetmeye yönelik bir yaklaşım olarak incelenmiştir.
- Yerleşik değişiklik kaydetme yöntemleri, güncel bir özetin arkasındaki kaynağın yerine geçmemesi gerektiği kuralını bildirdi.

Bu fikirler, yeni bir model cevabının veya yeniden yazılmış bir özetin aksi takdirde gizleyeceği yolun korunmasına yardımcı olur.

## İddiaları, desteği ve anlaşmazlığı ayırma

- [Mann ve Thompson'ın Retorik Yapı Teorisi](https://aclanthology.org/J88-2003/)Ana nokta ve açıklaması gibi bir belgenin bölümleri arasındaki ilişkiler için sağlanan adlar.
- [Walton, Reed ve Macagno'nun Tartışma Şemaları](https://www.cambridge.org/core/books/abs/argumentation-schemes/introduction/745B75B5933D17D86AC2E85971DA34A2)destek ve sonuçları incelemek için odaklanmış sorular sağladı.
- [oAMF](https://github.com/arg-tech/oAMF)ve xAIF, iddiaların ve bunların bağlantılarının kaydedilmesine yönelik yaklaşımlar sağladı.
- [PropBank](https://aclanthology.org/J05-1004/)ifadelerin ve bunların içindeki rollerin nasıl kaydedildiğini etkiledi.
- [RSTformer](https://aclanthology.org/2023.acl-long.306/)ve ilgili çalışmalar belge yapısını bulmak için test edildi. Anlam veya muhakeme konusunda nihai yargıçlar olarak kullanılmadılar.

Bu kaynaklar, gösterişli bir paragrafın bir iddia, onun desteği, bir düzeltme ve bir anlaşmazlık arasındaki farkı gizlemesini önlemeye yardımcı olur.

## Benzerliği gerçekle karıştırmadan yararlı materyal bulma

- [Carbonell ve Goldstein'ın Maksimum Marjinal Uygunluğu](https://aclanthology.org/X98-1025/)tekrara karşı ilgiyi dengelemenin bilinçli yolları.
- [Alt modüler belge özetleme üzerine Lin ve Bilmes](https://aclanthology.org/P11-1052/)Belirli bir boyut sınırı dahilinde yararlı bir pasaj grubu seçmenin bilinçli yolları.
- [GerçekScore](https://aclanthology.org/2023.emnlp-main.741/)İddiaların tam olarak nasıl desteklendiğine dair bilgilendirilmiş sorular.
- Kayıtlı ilişkilerden oluşturulan özetler üzerinde yapılan araştırmalar, önemli bağlantıları atmadan materyali kısaltan testlere bilgi sağladı.

Arama ve özetleme, kişiyi kanıtlara yönlendirebilir. Bir şeyin neden önemli olduğuna karar veremezler veya bir pasajı doğru hale getiremezler.

## Yazmadan önce planlama

- [Reiter ve Dale'in Doğal Dil Üretme Sistemleri Oluşturması](https://www.cambridge.org/core/books/building-natural-language-generation-systems/0AE70C709A9BFBDC80B349B2D22A78CD)içerik seçme, planlama ve cümle yazma ayrımını etkiledi.
- [Adım Adım NLG](https://aclanthology.org/N19-1236/)Ve[veriden metne makro planlama](https://aclanthology.org/D19-1318/)belge planlama yöntemlerinin bilinçli karşılaştırmaları.
- [BasitNLG](https://github.com/simplenlg/simplenlg),[Dilbilgisi Çerçevesi](https://www.grammaticalframework.org/), Ve[OpenCCG](https://github.com/OpenCCG/openccg)Planlanan içeriği cümleye dönüştürmenin yolları olarak değerlendirildi.
- Bilinen ve yeni bilgiler, cümleler arasındaki bağlantılar, iletişim türleri ve belge biçimleri üzerine yapılan araştırmalar, açıklamaların farklı okuyucular için nasıl sıralanacağını etkiledi.

Bu çalışma birlikte, bir dil modelinden onu yazmasını istemeden önce bir belgenin planlanmasını destekler.

## İnsanın anlama ve okuma maliyeti

- İnsanların uzunluk, yeni kavramlar ve tekrarlama konusundaki sınırları nasıl anladığını ve zihinsel çabayı nasıl yönettiğini araştıran araştırmalar.
- [Coh-Metrix](https://www.cambridge.org/core/books/automated-evaluation-of-text-and-discourse-with-cohmetrix/AE4A1D5DCCBA1AE3A9632E9D4D380270),[TAACO](https://www.linguisticanalysistools.org/taaco.html),[DocuScope](https://docuscope.github.io/), TextDescriptives ve LFTK, yazıyı karşılaştırmanın yolları olarak değerlendirildi.
- Kendi Kaderini Belirleme Kuramı, yaşamın anlamı üzerine yapılan araştırmalar ve değerler üzerine yapılan araştırmalar, kişisel anlam hakkında sınırlı sorulara yol açtı. Otomatik teşhisi veya geniş insan profillerini desteklemezler.

## Sınırlı düzenleme araçları

[LazerTagger](https://github.com/google-research/lasertagger),[GEKTÖR](https://github.com/grammarly/gector), Ve[EditT5](https://aclanthology.org/2022.findings-acl.260/)ne kadar yeni ifadenin eklenebileceğini sınırlayan düzenleme görevleri için değerlendirildi.

## Haklar ve daha kapsamlı kayıtlar

Bu belgeler, adı geçen kitapların, makalelerin, programların, eğitilmiş model dosyalarının veya araştırma koleksiyonlarının kopyalarını içermez.[Kaynaklar, lisanslar ve gizlilik](../../SOURCES-LICENSES-AND-PRIVACY.md)gerçekte kullanılan veya test edilen programlar ve eğitimli dosyalar için lisans incelemesini kaydeder.

Özel araştırma kayıtları daha fazla makale, kamu standartları, araçlar, koleksiyonlar, kültürel çalışmalar, reddedilen yaklaşımlar ve test sonuçları içerir. Esas olarak neyin işe yaramadığını göstererek yardımcı olan fikirler de dahil olmak üzere, bu kayıtlar kontrol edildikçe kamunun kredisi artabilir.
