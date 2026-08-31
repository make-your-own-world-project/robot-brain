> Polski: Wspomagane maszynowo tłumaczenie wiarygodnego źródła w języku angielskim. Mile widziane poprawki w języku ojczystym. [angielski](../../README.md) | [Wszystkie języki](../README.md)

# Zachowaj zapis. Wymień model.

![Dane danej osoby pozostają w jednym miejscu, podczas gdy oddzielne części robocze obsługują ograniczone zadania.](../../illustrations/specialist-assembly-line-vs-giant-chatbot.png)

Robot Brain to oprogramowanie służące do zachowania historii i znaczenia długotrwałej pracy ludzkiej. To nie jest model językowy, chatbot czy usługa przekazująca każde pytanie do modela.

Duże modele językowe mogą badać, pisać, wyjaśniać i pomagać w rozwiązywaniu trudnych problemów. Zbudowane wokół nich płatne usługi są nadal tymczasowymi przestrzeniami do pracy. Mogą skrócić długą rozmowę, zgubić wcześniejsze instrukcje, oddzielić wnioski od dowodów i kontynuować pisanie tak, jakby brakująca historia wciąż była obecna. Osoba spędza wtedy więcej czasu i płatnego wykorzystania na odbudowie kontekstu, który został już dostarczony.

To oprogramowanie zmienia się tam, gdzie żyje trwała wartość. Rozmowy danej osoby, dokumenty, decyzje, nieudane próby, poprawki i pytania bez odpowiedzi pozostają w rejestrach, które kontroluje ta osoba. Lokalne programy mogą badać te zapisy. Model językowy może pomóc w przypadku wybranej pracy, ale jego wkład powraca do rejestru jako praca przestarzała i możliwa do sprawdzenia. Model można następnie zastąpić bez zabrania ze sobą historii.

[Przeczytaj tę dokumentację w innym języku.](../README.md)

## Różnica w jednym widoku

| Usługa komercyjnego modelu językowego | Robot Brain |
|---|---|
| Tworzy odpowiedź na podstawie materiału aktualnie znajdującego się w widoku roboczym. | Zachowuje pełne źródło i związaną z nim historię. |
| Może skrócić lub utracić wcześniejszą rozmowę w miarę rozwoju pracy. | Zapisuje rozmowy poza każdym modelem, dzięki czemu można z nich skorzystać ponownie. |
| Łączy wiedzę zdobytą z wielu źródeł bez pełnej ścieżki powrotnej do każdego źródła i jego okoliczności. | Każde znane źródło, późniejsze ustalenia, poprawki i spory są przechowywane w oddzielnym rejestrze. |
| Potrafi pisać, wyszukiwać, planować i oceniać własną odpowiedź w jednej wymianie zdań. | Umożliwia zapisywanie, wyszukiwanie, analizę, pisanie, sprawdzanie i zatwierdzanie oddzielnych części z ograniczonymi uprawnieniami. |
| Kontroluje model, zasady świadczenia usług, limity użytkowania i zmiany produktów. | Pozostawia trwały zapis pod kontrolą danej osoby. |
| Otrzymuje wynagrodzenie za nieudane próby i wymiany naprawcze, a także użyteczną pracę. | Zapamiętuje awarie i poprawki, dzięki czemu ich lekcje nie muszą być kupowane ponownie. |

Robot Brain może wywołać model języka lokalnego lub internetowego. To nie zmienia go w modelowy serwer proxy. Może zachowywać, wyszukiwać, porównywać, organizować i odbudowywać wcześniejsze prace bez wywoływania modelu, który brał udział w pierwotnej rozmowie. Kiedy model jest użyteczny, żądanie jest jednym z kroków w większym procesie, który istnieje niezależnie od tego modelu.

## Dlaczego to zbudowano

Najsilniej płatne modele ogólnego przeznaczenia dostępne w trakcie opracowywania były zdolnymi, ale zawodnymi opiekunami długiej pracy.

Odnotowane awarie obejmowały utracone instrukcje, brakujące dowody, wymyślone połączenia, przedwczesne roszczenia o ukończenie, niechciane zmiany i uszkodzenie działających plików. Naprawienie tych błędów wymagało większej liczby próśb, większej liczby testów, wyższych płatnych zasiłków i pochłaniało więcej czasu i energii danej osoby. Usługi nie zwracały automatycznie zużycia wydanego na bezużyteczną pracę lub wymiany potrzebne do jej naprawy.

Problem był większy niż jakakolwiek zła odpowiedź. Poproszono tymczasowy generator tekstu, który miał służyć jako pamięć, historyk, badacz, pisarz, weryfikator i ostateczny sędzia. Zmiana modeli nie zmieniła tego układu.

Robot Brain został zbudowany w oparciu o inny układ: najpierw prowadź dokumentację ludzką, pozwól, aby kilka wymiennych części miało na nią swój udział, i wymagaj dowodów poza modelem generującym, zanim ważna praca zostanie zaakceptowana.

## Czego wytrenowany model nie jest w stanie utrzymać

Duży model językowy uczy się wzorców z ogromnych zbiorów ludzkiej pracy. Te wzorce czynią model użytecznym, ale model nie jest biblioteką kompletnych dzieł, które go ukształtowały.

Wewnątrz modelu wpływ książek, artykułów, rozmów, tłumaczeń, społeczności, etykiet i opinii ludzi jest mieszany. Model zazwyczaj nie jest w stanie pokazać, które źródła ukształtowały dane zdanie. Nie może przywrócić celu, odbiorców, dowodów, sporów, późniejszych poprawek lub brakującego punktu widzenia każdego autora.

Jest to utrata znaczenia, nawet jeśli oryginalne dzieło nadal istnieje gdzie indziej. Model zachowuje pewną użyteczność z pracy, odrzucając niezawodną ścieżkę powrotną do swojego ludzkiego otoczenia.

Ten sam problem pojawia się podczas normalnego użytkowania. Ostateczna odpowiedź może przetrwać po skróceniu rozmowy, która nadała jej znaczenie. Wniosek pozostaje, ale nieudane próby, niepewność i przyczyny znikają z roboczego punktu widzenia modelu.

Projekt ten nie rozwiązuje tego problemu poprzez uczenie innego modelu życia człowieka. Historia osobista pozostaje czytelna i możliwa do prześledzenia, zamiast być łączona z innym wyszkolonym modelem. Modele działają z wybranymi rekordami; nie stają się zapisami.

## Co robi każda część

Działające oprogramowanie oddziela zadania, które często sprawiają, że usługa czatu wygląda jak jedna czynność:

1. **Opiekun źródła zapisuje to, co się wydarzyło.** Zachowuje rozmowę, dokument, obraz lub inny materiał, nie zastępując go streszczeniem.
2. **Kopie z możliwością przeszukiwania ułatwiają znalezienie źródła.** Skopiowany tekst, opisy i indeksy wskazują na niezmienione źródło i można je odbudować.
3. **Skoncentrowani lokalni czytelnicy badają konkretne cechy.** Oddzielne metody analizują język, wypowiedzi, relacje, rozumowanie, czas, ludzkie doświadczenie i wartości. Każdy raportuje jedynie własne ustalenia i fragmenty za nimi.
4. **Zapis historii sprawia, że ​​zmiany są widoczne.** Nowe ustalenia, poprawki, nieporozumienia, nieudane próby i pytania otwarte są dodawane bez przepisywania wcześniejszych wydarzeń.
5. **Kreator żądań gromadzi to, czego potrzebuje jedno zadanie.** Wybiera odpowiednie źródła i ustalenia oraz rejestruje, co zostało uwzględnione, a co pominięte.
6. **Model językowy może zapewnić ograniczoną pomoc.** ​​Model lokalny może zapewnić szerokie tło. Model online może pomóc w trudnych badaniach lub pisaniu. Każda odpowiedź pozostaje przestarzałym wkładem, który można sprawdzić, odrzucić lub zastąpić.
7. **Oddzielne kontrole porównują wynik z prośbą i dowodami.** Modelka, która napisała odpowiedź, nie może oświadczyć, że zaakceptowała swoją pracę.
8. **Ekran umożliwia korzystanie z oprogramowania.** DołączoneLibreChatwidelec jest jednym z takich ekranów. Wymiana nie zastępuje płyt ani pozostałych części roboczych.

Żadna część nie jest przedstawiana jako wszechwiedzący asystent. Ich ograniczone zadania sprawiają, że każda część jest wymienna.

## Sprawienie, że ukończona rozmowa znów stanie się użyteczna

Zakończona rozmowa zawiera prośbę danej osoby, rzeczywiste odpowiedzi modelu językowego, podjęte próby pracy, niepowodzenia, poprawki i moment zakończenia wymiany. Komunikaty te zachowują to, co wniósł oryginalny model, bez konieczności późniejszego wyjaśniania tego modelu.

Skoncentrowani lokalni czytelnicy badają zapisaną wymianę zdań pod różnymi kątami. Potrafią znaleźć szczegółowe wzorce i zależności bez polegania na szerokiej wiedzy światowej. Ich oddzielne ustalenia pozostają powiązane z dokładnymi częściami rozmowy.

Ustalenia te mogą nadal wymagać zwykłej wiedzy ogólnej, zanim staną się jasne. Na ten ograniczony krok, małyQwenmodel przebiega lokalnievLLM. Dodaje przegląd datowany, który pomaga połączyć szczegółowe ustalenia i wyjaśnić, czego dokonała wymiana.

Qwennie odzyskuje ukrytych myśli ani historii treningów modela online. Dostarcza szerokiej wiedzy ogólnej, która nie jest unikalna dla oryginalnego modelu. Użyteczny wkład oryginalnego modelu jest już zachowany w słowach, które stworzył.

TheQwenprzegląd jest przechowywany obok źródła i wcześniejszych ustaleń. Można to poprawić lub wymienić. Oryginalna rozmowa i szczegółowa analiza lokalna pozostają niezmienione.

## Co teraz działa

Obecna implementacja może zachować ukończoną rozmowę, zbadać ją oddzielnymi metodami lokalnymi, dodać lokalny odczyt wiedzy ogólnej i zebrać każdy zachowany wkład w rekord, który można później odbudować.

Może również przygotować ograniczoną prośbę o model online, gdy przydatna będzie pomoc z zewnątrz. Usługa ta otrzymuje wyłącznie wybrany materiał. Odpowiedź powraca do lokalnych rejestrów, gdzie to kontrole i ludzka zgoda: a nie model: decydują o tym, co zostanie zachowane.

To jest główne osiągnięcie: praca, która kiedyś polegała na jednej tymczasowej rozmowie, może pozostać użyteczna, gdy zniknie ekran czatu, model i dostawca.

## Przeczytaj pełne wyjaśnienie

- [Dlaczego duże modele językowe nie są w stanie zachować pełnej historii](01-Why-Large-Language-Models-Cannot-Preserve-the-Full-Story.md)
- [Co robi każda część i czego nie kontroluje żaden model](02-A-Lasting-Record-Outside-the-Model.md)
- [Zachowaj poprawkę bez usuwania błędu](03-How-Knowledge-Changes-Without-Erasing-History.md)
- [Postępuj zgodnie z roszczeniem i wróć do dowodów](04-How-Every-Claim-Can-Be-Checked.md)
- [Zbuduj dokument przed napisaniem prozy](05-How-Evidence-Becomes-a-Finished-Document.md)
- [Wyjaśnij tę samą prawdę różnym czytelnikom](06-One-Meaning-Different-Readers.md)
- [Trzymaj prywatną historię pod kontrolą danej osoby](07-Privacy-and-Control-Stay-With-People.md)
- [Co robi obecna implementacja](08-What-Works-Today.md)
- [Dlaczego projekt czerpie z wielu dziedzin](09-How-Research-Strengthens-the-System.md)
- [Pomagaj bez przekazywania prywatnych akt](11-Contribute-Without-Giving-Up-Control.md)
- [Słowa użyte w tych dokumentach](12-A-Short-Guide-to-Key-Terms.md)
- [Wykonaj jedno żądanie poprzez części robocze](13-The-Parts-Running-Today.md)
- [Używaj modelu językowego do zadania, a nie jako pamięci](15-Why-a-Language-Model-Is-a-Replaceable-Tool.md)
- [Awarie zaobserwowane w płatnych usługach opartych na modelu językowym i zabezpieczenia, do których doprowadziły](16-What-Commercial-Language-Model-Services-Got-Wrong.md)
- [Lekcje, które zmieniły projekt](17-How-Language-Models-Lose-Meaning-and-How-to-Preserve-It.md)
- [Uwagi dotyczące użytku publicznego, kredytów i prywatności](18-Use-Attribution-and-Limits.md)
- [Jak zakończona rozmowa staje się trwałą wiedzą](19-What-the-System-Accomplishes.md)
- [Co będzie dalej](20-Where-the-System-Goes-Next.md)

## Twórcy, źródła i prawa

- [Co pomogło ukształtować tę pracę](10-What-Helped-Shape-This-Work.md)
- [Badania stojące za projektem](14-Sources-Behind-the-Design.md)
- [Źródła, licencje i kontrole udostępnień publicznych](../../SOURCES-LICENSES-AND-PRIVACY.md)

## Licencja

Oryginalne teksty projektu, diagramy i ilustracje są dostępne na stronie organizacji[Creative Commons Uznanie autorstwa 4.0 Licencja międzynarodowa](../../LICENSE.md), chyba że dokument określa inne warunki. Materiał stworzony przez innych zachowuje swoje własne prawa i warunki.

## Niezależność i prywatność

Jest to niezależny projekt osobisty opracowany w oparciu o czas osobisty, sprzęt, konta i usługi płatne. Żaden pracodawca nie brał w tym udziału. Wzmianka o jakiejkolwiek osobie, pracodawcy, instytucji, dostawcy modeli, grupie badawczej, zasadach wspólnych lub projekcie zewnętrznym nie oznacza udziału, zgody, partnerstwa ani poparcia.

Publiczne udostępnienie nie obejmuje prywatnych rejestrów, danych identyfikacyjnych, haseł, informacji o połączeniu prywatnym, informacji o pracodawcy i instrukcji dotyczących dostępu do usług prywatnych. Opisy niepowodzeń modelu ograniczają się do zarejestrowanego zachowania i jego skutków; nie powołują się na nieujawnione przyczyny i motywy. Dokumenty nie stanowią profesjonalnej porady ani obietnicy rezultatów.

![Ścieżka od pamięci kontrolowanej przez dostawcę do zapisów, które pozostają przy ludziach, których dotyczą.](../../illustrations/open-door-human-future.png)
