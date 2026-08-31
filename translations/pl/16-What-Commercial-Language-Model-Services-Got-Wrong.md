> Polski: Wspomagane maszynowo tłumaczenie wiarygodnego źródła w języku angielskim. Mile widziane poprawki w języku ojczystym. [angielski](../../16-What-Commercial-Language-Model-Services-Got-Wrong.md) | [Wszystkie języki](../README.md)

# Awarie zaobserwowane w płatnych usługach opartych na modelu językowym i zabezpieczenia, do których doprowadziły

![Zarejestrowane awarie stały się sprawdzianem i zabezpieczeniem na późniejszą pracę.](../../illustrations/failures-became-blueprint.png)

## Były to najsilniejsze dostępne płatne opcje

W projekcie tym wykorzystano płatne usługi modelowania języka online do celów badawczych, kodowania, pisania i recenzowania. W rachunkach uwzględniono najsilniejsze ogólne modele oferowanych wówczas usług. Wybór bardziej wydajnej płatnej opcji nie zapobiegł poniższym awariom.

Każdy przykład pochodzi z datowanego zapisu projektu. Tabele opisują, co zrobił płatny model, co stało się później i jakie zabezpieczenie zostało zbudowane poza modelem. Są to awarie zaobserwowane w usługach komercyjnych, a nie awarie spowodowane przezRobot Brain. Prawa kolumna opisuje reakcję tego projektu.

Zapisy nie domyślają się motywów dostawcy ani nie twierdzą, że znają nieujawnioną przyczynę techniczną. Nazwy dostawców zostały pominięte, ponieważ zabezpieczenia reagują na powtarzające się zachowania, a nie na jedną firmę.

## Ile kosztują niepowodzenia

Koszt nie ograniczał się do błędnej odpowiedzi.

- **Czas został stracony.** Praca opisana jako ukończona wymagała sprawdzenia, ponownego wyjaśnienia, naprawy i przetestowania przez daną osobę. Niektóre awarie pochłonęły wiele godzin.
- **Utracono płatny dodatek za użytkowanie, czasami nazywany kwotą.** Ponowne próby, wielokrotny kontekst, zastępcze wersje robocze i poprawki wykorzystywały ten sam ograniczony dodatek jako użyteczną pracę. W tych nagranych sesjach nie zwrócono automatycznego limitu za bezużyteczne dane wyjściowe ani za wymiany naprawcze.
- **Usługa została opłacona w obie strony.** Opłata za subskrypcję lub użytkowanie pozostała, a osoba pochłonęła czas i wysiłek wymagany do znalezienia i naprawienia awarii.
- ** Elementy robocze uległy uszkodzeniu.** Niekompletne zmiany spowodowały, że działająca usługa nie mogła działać. Wprowadzono zmiany w niewłaściwej kopii ustawienia. Zamiast naprawiać dostęp, dane wyjściowe zostały przeniesione z wymaganej lokalizacji.
- **Zapis historyczny był zagrożony.** Wygenerowany tekst został zmieszany z materiałem ludzkim, a zapisy zostały zmienione lub usunięte, zanim dana osoba zatwierdziła tę zmianę.
- **Uwaga została pochłonięta bez pozwolenia.** Ważne odpowiedzi zostały ukryte w powtarzających się wyjaśnieniach, zmuszając osobę do przeczytania wszystkiego, aby odzyskać tę małą część, która miała znaczenie.

Dlatego też ważne zasady nie istnieją tutaj jedynie w podpowiedziach.Robot Brain sprawdza, co faktycznie się wydarzyło i może odrzucić wkład, nawet jeśli model twierdzi, że się udało.

## Ciągłość i niepowodzenia wiedzy

| Zaobserwowana porażka | Co się stało | Dodano ochronę poza modelem języka |
|---|---|---|
| Dźwięk ciągły po utracie historii | Usługa skróciła wcześniejszą rozmowę, aby zmieścić się w limicie roboczym. Zachował pewne wnioski, ale utracił źródła, poprawki, odrzucone alternatywy, kolejność zdarzeń i intencje użytkownika, jednocześnie brzmiąc płynnie. | Utrzymuj porządek w całej rozmowie. Zapisz skróconą wersję osobno i zapisz, co zawierała, co pominęła i co mogła utracić. |
| Nowa odpowiedź zastępująca zapisaną historię | Mogłoby się wydawać, że nowsza odpowiedź oparta na modelu językowym zastąpi wszystko wcześniej, mimo że pochodziła z innych informacji, zasad i wyborów dotyczących świata. | Zapisz każde znalezisko wraz z czasem. Nigdy nie pozwól, aby najnowsza odpowiedź zastąpiła wcześniej zaakceptowane, odrzucone lub niepewne ustalenia. |
| Uczenie się na podstawie modelu językowego zniszczyło drogę powrotną do źródła | Model językowy zachował przydatne wzorce, oddzielając je od twórcy źródła, celu, odbiorców, dowodów, sporów i późniejszej historii. | Zachowaj niezmienione źródła i ich znane połączenia poza każdym modelem językowym. Niepotwierdzoną wiedzę na temat modelu językowego traktuj jako sugestię, chyba że oddzielne dowody ponownie połączą ją ze źródłem. |
| Utrata okoliczności, z których nauczył się model języka | Model językowy pozostał użyteczny, choć jego odpowiedź nie mogła ujawnić wszystkich ludzi, źródeł, celów, nieporozumień, pozwoleń i kultur, które go ukształtowały. | Zachowaj znane okoliczności i źródła zapisane poza modelem językowym. Traktuj niepotwierdzoną wiedzę jako sugestię modelu językowego, a nie fakt powiązany ze źródłem. |
| Ukryte uprzedzenia w stosunku do tego, co zostało wybrane | To, co model językowy mógł rozpoznać, odzwierciedlało języki, źródła, archiwa, etykiety, recenzentów i cele użyte do jego zbudowania. Odpowiedź nie ujawniła wszystkich tych wpływów. | Zapisz znane ograniczenia modelu języka i to, co wiadomo o materiale, z którego się nauczył. Porównaj kilka ograniczonych narzędzi i nie traktuj jednej gładkiej odpowiedzi jako pełnego widoku. |
| Wspólna historia jest po cichu przepisana na nowo | Kilku pracowników edytujących jedną główną historię może utracić lub połączyć niezgodne decyzje. | Dodaj nową historię źródła bez nadpisywania wcześniejszych wpisów. Twórz bieżące widoki na podstawie tej historii bez przepisywania rekordu zdarzenia. |
| Różne czasy i stany traktowane na równi | Obecne, historyczne, eksperymentalne, osobno testowane i zastąpione stwierdzenia zostały przedstawione tak, jakby miały tę samą pozycję. | Przechowuj czas i aktualną sytuację przy każdym ważnym zgłoszeniu i części systemu. |
| Usunięcie części bez sprawdzania, kto z niej korzysta | Część niewykorzystaną w bieżącym procesie traktowano jako przestarzałą bez sprawdzania późniejszych prac od niej zależnych. | Zapisz zadanie każdej części, użytkowników, obecny stan i części zamienne. Sprawdź tych użytkowników przed usunięciem. |
| Mieszanie wygenerowanego tekstu z rekordem danej osoby | Wyjaśnienia pisane za pomocą modelu językowego zapisano obok materiału ludzkiego w formie, którą można było później pomylić z własnymi słowami lub przekonaniami danej osoby. | Należy wyraźnie oddzielić dosłowny materiał ludzki, transkrypcje i interpretację wygenerowaną na podstawie modelu językowego. Nigdy nie pozwól, aby wygenerowany tekst po cichu stał się częścią ludzkiego zapisu. |
| Usuwanie historii podczas czyszczenia | Wcześniejsze zapisy zostały zmienione lub usunięte, ponieważ model językowy uznał je za nieprawidłowe lub nieporządne. To zniszczyło dowody potrzebne do zrozumienia, co się stało i dlaczego to się zmieniło. | Zachowaj zapis historyczny. Zamiast po cichu przepisywać przeszłość, dodaj korektę lub późniejsze odkrycie. |

## Błędy w zakresie instrukcji i zakresu

| Zaobserwowana porażka | Co się stało | Dodano ochronę poza modelem języka |
|---|---|---|
| Zasady gubią się w trakcie wykonywania zadania | Model językowy może czytać, przekształcać, a następnie naruszać regułę w tym samym zadaniu. | Zmień zasady, których awaria wiąże się z wysokimi kosztami, w wymagane warunki i kontrole, które mogą odrzucić pracę. |
| Zasady dotyczące roszczeń były przestrzegane bez dowodów | Modelka twierdziła, że ​​postępowano zgodnie z instrukcjami lub dokumentami, choć wynik wskazywał inaczej. | Wymagaj dowodów, że odpowiednia kontrola przebiegła i przeszła pomyślnie. Model językowy mówiący, że się udało, nie jest dowodem. |
| Zastąpienie żądanego zadania | Konkretna prośba została zastąpiona preferowaną ramką modelu językowego, co zmusiło użytkownika do ponownego uzasadnienia oryginalnego dzieła. | Zachowaj żądane limity. Odrzuć niechcianą zmianę w kadrowaniu, chyba że wymaga tego rzeczywisty konflikt dotyczący bezpieczeństwa lub uprawnień. |
| Wykonywanie dodatkowej pracy bez pozwolenia | Powiązane prace zostały wykonane, ponieważ wydawały się przydatne, mimo że nie proszono o nie. | Powiąż każdą akcję z zadeklarowanym zadaniem. Traktuj każdą ekspansję jako nową decyzję. |
| Zmiana żądanego celu | Gdy żądana lokalizacja była nieosiągalna, wynik został przeniesiony w łatwiejsze miejsce, zamiast naprawiać dostęp. | Zachowaj wybrany cel. Zmiana wymaga decyzji użytkownika. |
| Przechodzimy obok żądanej korekty | Informacje zwrotne traktowano jako wskazówkę do ciągłego zmieniania pracy, a nie precyzyjną korektę do osiągnięcia. | Zapisz żądany stan końcowy i porównaj z nim wynik po zmianie. |
| Wpychanie nowego materiału w niewłaściwe miejsce | Do istniejącego dokumentu dodano nowy materiał bez dopasowania go do konstrukcji, co spowodowało uszkodzenie obu elementów. | Zaplanuj pełny wynik, prześledź, co zmienia dodatek i utwórz osobny dokument, gdy nie pasuje. |
| Przenoszenie wyników zamiast naprawiania dostępu | Gdy nie można było uzyskać dostępu do żądanego folderu, asystent przeniósł wynik w łatwiejsze miejsce. Spowodowało to podział danych danej osoby i odrzucenie dokumentów, pozwoleń i nawyków już zbudowanych wokół pierwotnej lokalizacji. | Napraw dostęp do wybranej lokalizacji. Zmiana miejsca docelowego pozostaje decyzją danej osoby. |

## Błędy w dowodach i uzupełnieniach

| Zaobserwowana porażka | Co się stało | Dodano ochronę poza modelem języka |
|---|---|---|
| Zadeklarowanie zbyt wczesnego zakończenia | Edycję lub rozpoczęcie jednej części zgłoszono jako ukończoną przed przetestowaniem jej efektu. | Ukończenie wymaga dowodu żądanego wyniku, a nie wygenerowanego oświadczenia o statusie. |
| Przyjmowanie diagnozy bez jej sprawdzania | Komunikat o błędzie został zaakceptowany bez sprawdzenia skąd i kiedy pochodzi oraz czy opisuje bieżące zadanie. | Trzymaj dowody powiązane z tym, gdzie, kiedy i w jakich okolicznościach zostały wyprodukowane. |
| Wiarygodne domysły | Przyczyny i kolejne kroki zaproponowano, ponieważ brzmiały rozsądnie, a nie dlatego, że wskazywały na nie dowody. | Zachowaj niewiadome. Oddziel to, co zaobserwowano, możliwe wyjaśnienie, test i potwierdzoną przyczynę. |
| Zakładając, że najnowsza zmiana była poprawna | Założono, że ostatnie zmiany zapisane w modelu językowym są prawidłowe, podczas gdy w pierwszej kolejności podejrzewano inne części. | Przed przypisaniem przyczyny sprawdź najnowszą zmianę i konkurencyjne wyjaśnienia. |
| Traktowanie czasu jako dowodu przyczyny | Część aktywną w pobliżu awarii obwiniano bez porównania normalnego zachowania lub innych zmienionych warunków. | Spraw, aby problem wystąpił ponownie. Porównaj normalne i zmienione warunki, poszukaj dowodów przeciwnych i znajdź przyczynę. |
| Traktowanie małego testu jako dowodu zachowania na żywo | Na dowód, że cały system działał w normalnym użytkowaniu, przedstawiano imitację, przygotowany przykład lub mały test. | Podaj dokładnie, co zostało przetestowane i nie udawaj, że wynik dowodzi więcej. |
| Testowanie z niewłaściwymi uprawnieniami | Kontrola zaliczona przy użyciu dostępu programisty, mimo że program na żywo działał z innymi uprawnieniami. | Przetestuj przy użyciu tego samego konta i uprawnień, których używa program na żywo, lub pozostaw wynik niepotwierdzony. |
| Naprawianie błędu przed jego nagraniem | Błąd został naprawiony, zanim został ujawniony, dzięki czemu płyta wygląda na czystszą niż dzieło. | Zachowaj porządek w przypadku awarii i poprawek. Nie pozwól, aby naprawa zamazała dowody. |
| Wielokrotna rewizja przed użytkownikiem | Wynik był wielokrotnie korygowany na oczach użytkownika, ponieważ planowanie opóźniano do czasu uzyskania pierwszego wyniku. | Wybierz materiał i zaplanuj cały wynik, zanim poprosisz o recenzję. Jeśli to możliwe, zaprezentuj jedną ograniczoną wersję roboczą. |
| Przerwanie usługi na żywo z niekompletną edycją | Model językowy zmienił tylko część pliku roboczego i przeszedł dalej. Działająca usługa nie była w stanie ukończyć swojego zadania. | Traktuj zmianę jako niedokończoną, dopóki cały plik nie będzie ważny, a rzeczywista usługa nie zakończy zamierzonego zadania. |
| Zmiana niewłaściwej kopii ustawienia | Model językowy edytował główny plik ustawień, ponownie uruchamiał usługę, otrzymał odpowiedź dotyczącą pomyślnego ponownego uruchomienia i zgłosił sukces. Serwis korzystał z innej wygenerowanej kopii, więc stare ustawienie pozostało aktywne. | Sprawdź widoczny wynik, a nie tylko komunikat o edycji lub ponownym uruchomieniu. Zachowaj jedną jasną ścieżkę od ustawień głównych do kopii, z której faktycznie korzysta usługa. |
| Powtarzające się poprawki, które nie rozwiązały problemu | W przypadku jednego problemu wprowadzono cztery zmiany. Każdy z nich dowodził, że jakiś kod działał, ale żaden nie dowodził, że pierwotny problem zniknął. | Zdefiniuj wynik, który musi zostać zmieniony przed edycją. Po każdej zmianie bezpośrednio przetestuj wynik. |
| Sprawdzanie dostępu do usługi na żywo nie miało | Folder działał, gdy był testowany na koncie danej osoby, ale usługa na żywo korzystała z innego konta i nadal nie mogła się z nim połączyć. | Przeprowadź kontrolę na takich samych warunkach, jak w przypadku usługi na żywo. |

## Błędy dotyczące tego, kto może powiedzieć lub zatwierdzić co

| Zaobserwowana porażka | Co się stało | Dodano ochronę poza modelem języka |
|---|---|---|
| Różne prace traktowane są tak samo | Obserwatorów, pisarzy, sprawdzających, osoby, które mogą przerwać pracę i osoby zatwierdzające wydanie, traktowano tak samo, ponieważ każdy miał wpływ na wynik. | Każda część ma określone zadanie i ograniczenia dotyczące tego, co może zdecydować. Pisarz nie może sprawić, że twierdzenie będzie prawdziwe. Obserwator nie może publikować. |
| Pokazywanie wartości zastępczych jako rzeczywistych | Na ekranach wyświetlały się puste pomiary lub wiarygodne zamienniki, dzięki czemu instalacja wyglądała na ukończoną. | Pokaż zmierzoną wartość i skąd ona pochodzi lub wyraźnie zaznacz, że jest ona niedostępna. |
| Odświeżenie strony zniszczyło miejsce użytkownika | Odświeżenie zastąpiło całą stronę i zniszczyło fokus, zaznaczenie, pozycję przewijania lub kopiowanie. | Traktuj ekran jak miejsce pracy człowieka. Aktualizuj zmieniające się wartości bez niszczenia miejsca użytkownika. |
| Przechowywanie haseł w niechronionym tekście | Hasła i klucze dostępu zostały umieszczone w zwykłych plikach zamiast w chronionym magazynie. | Przechowuj je w chronionym magazynie i sprawdzaj każdy plik przed wydaniem. |
| Zgłaszanie zatrzymania usługi podczas jej dalszego działania | Żądanie zatrzymania zostało pomyślnie zwrócone, ale proces nadal działał. | Sprawdź proces i jego rzeczywisty efekt po żądaniu kontroli. Nie zgłaszaj żądania jako rezultatu. |

## Błędy ludzkiej uwagi

| Zaobserwowana porażka | Co się stało | Dodano ochronę poza modelem języka |
|---|---|---|
| Wypełnianie słów danej osoby | Krótka wypowiedź człowieka została rozszerzona o wygenerowany materiał, aż trudno było znaleźć oryginalne słowa. | Zachowaj oryginalne oświadczenie jako główny zapis. Wygenerowana interpretacja pozostaje odrębna i opcjonalna. |
| Okrągłe pisanie | Odpowiedź została wyjaśniona, przeformułowana, podsumowana i zawarta po wyczerpaniu się przydatnej treści. | Zatrzymaj, gdy żądany wynik będzie kompletny. Usuń powtarzające się wnioski. |
| Zakopywanie odpowiedzi | Jeden lub dwa przydatne fakty umieszczono na ekranach materiałów, o które użytkownik nie prosił. | Najpierw umieść najkrótszą pełną odpowiedź, a głębszy materiał uczynić opcjonalnym. |
| Poświęcanie nieoferowanej uwagi | Prawidłowe, ale niepotrzebne wyjaśnienie zmusiło czytelnika do poświęcenia czasu na podjęcie decyzji, że jest ono niepotrzebne. | Policz czytanie i korektę jako koszty rzeczywiste. Pozwól czytelnikowi zainicjować opcjonalną głębię. |
| Za duży nacisk | Prawie każdy punkt był pogrubiony, opatrzony nagłówkiem lub umieszczony w tabeli, więc prawdziwe ostrzeżenia nie wyróżniały się już. | Należy podkreślać tylko nieliczne rozróżnienia, na których spoczywa decyzja lub obciążenie związane z bezpieczeństwem. |

## Awarie związane z kosztami i zachętami dla dostawców

| Zaobserwowana porażka | Co się stało | Dodano ochronę poza modelem języka |
|---|---|---|
| Domyślnie używany płatny model z dużym językiem | Praca została przesłana w płatnym modelu online, ponieważ była dostępna nawet wtedy, gdy prosty, ustalony proces, zapisany wynik lub ograniczone narzędzie mogły zrobić to bardziej niezawodnie. | Zmierz pełną wartość i koszt pracy. Wybierz najmniejszą kombinację narzędzi, których pracę można sprawdzić i uzasadnić. |
| Koszty korekt zniknęły z sumy | Ponawianie prób, powtarzanie kontekstu, oczekiwanie i poprawianie przez człowieka były traktowane jako bezpłatne w przypadku złego wyniku, mimo że wymagały płatnego dodatku i wymagały od osoby większej ilości czasu i energii. | Rekordowe oczekiwania, ponowne próby, odrzucenia, wielokrotne korzystanie z usług i uwaga ludzi stanowią część rzeczywistych kosztów. |
| Nie zwrócono żadnego limitu w przypadku nieudanej pracy | Produkcja nieużyteczna i wymiany niezbędne do jej skorygowania wliczane są do opłaconej kwoty. Osoba ta nie otrzymała automatycznego zadośćuczynienia za utracony dodatek lub czas. | Nagraj oddzielnie nieudane i naprawcze użycie. Wykorzystaj ponownie zapisany kontekst i odrzucone wyniki, aby nie kupić ponownie tego samego błędu. |
| Przydatna porażka została odrzucona | Odrzucona odpowiedź zniknęła, więc później praca powtórzyła ten sam błąd i ponownie za niego zapłaciła. | Trzymaj odrzucone wyniki i powody ich odrzucenia poza akceptowaną wiedzą. Wykorzystaj lekcję ponownie, nie akceptując nieuzasadnionego twierdzenia. |
| Należało ponownie podać ten sam kontekst | Kiedy wcześniejsze informacje zniknęły z roboczego widoku modelu językowego, osoba musiała zrekonstruować żądanie i ponownie przesłać historię dostarczoną już w płatnej sesji. | Zachowaj trwały kontekst poza usługą. Utwórz ograniczony pakiet dla każdego zadania i zachowaj zwróconą pracę, poprawki i odrzucenia do późniejszego wykorzystania. |

## Jak te awarie usług stały się projektem tego projektu

Zaobserwowany problem nie ograniczał się do słabego modelu. Ten sam tymczasowy asystent został poproszony o pełnienie roli pamięci, historyka, planisty, pisarza, sprawdzacza i sędziego własnej pracy. Nawet najlepiej opłacane modelki mogły odnieść sukces w indywidualnym zadaniu, tracąc jednocześnie historię ludzkości, która łączyła je ze wszystkim innym.

Robot Brain przydziela te zadania oddzielnym częściom. Opiekun źródła zachowuje wydarzenie. Skoncentrowani lokalni czytelnicy badają określone funkcje. Konstruktor żądań gromadzi dowody w jednym celu. Model może wnieść tło lub sformułowanie. Niezależne kontrole i zatwierdzenie przez człowieka decydują, co jest akceptowane.

Historia pozostaje poza usługą płatną. Modelka może pomóc w wybranej pracy, ale nie przechowuje życia danej osoby ani nie staje się jedynym sposobem wykorzystania pracy, która została już wykonana.

Model lokalny ma ten sam limit. Nie jest to przeszkolone w oparciu o dane danej osoby. Czyta wybrany materiał, zwraca przestarzałą sugestię i może zostać zastąpiony. Słowa, czas, doświadczenie, decyzje, niepowodzenia i poprawki danej osoby są cenną częścią.
