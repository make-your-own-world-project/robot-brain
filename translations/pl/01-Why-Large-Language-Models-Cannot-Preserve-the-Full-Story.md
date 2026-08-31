> Polski: Wspomagane maszynowo tłumaczenie wiarygodnego źródła w języku angielskim. Mile widziane poprawki w języku ojczystym. [angielski](../../01-Why-Large-Language-Models-Cannot-Preserve-the-Full-Story.md) | [Wszystkie języki](../README.md)

# Dlaczego duże modele językowe nie są w stanie zachować pełnej historii

![Zapisane fragmenty tracą wartość, gdy oddziela się ich źródła, powiązania i historię.](../../illustrations/ordinary-storage-loses-context.png)

Najsilniejsze płatne modele językowe użyte przy budowie tego projektu mogą wykonać imponującą pracę. Potrafili pisać, badać, wyjaśniać i pomagać w rozwiązywaniu trudnych problemów. Nadal nie udało im się zachować pełnej historii długiego projektu.

Późniejsza odpowiedź może zapamiętać wniosek, ale utraci nieudane próby, poprawki i dowody, które do niego doprowadziły. Wcześniejsze instrukcje mogły zniknąć, gdy rozmowa stała się zbyt długa. Modelka kontynuowała pisanie, jakby nic ważnego nie zginęło.

Jest to poważny problem, gdy brakująca historia reprezentuje czyjś czas, wiedzę lub doświadczenie.

## Pliki nie wystarczą

W folderze można przechowywać każdą notatkę, rozmowę, obraz i zadanie, jednocześnie tracąc łączącą je historię.

Kilka miesięcy później dana osoba może potrzebować wiedzieć:

- od czego rozpoczęła się praca
- jakie pomysły zostały wzięte pod uwagę
- dlaczego jedna próba się nie powiodła
- jakie dowody zmieniły plan
- który wniosek jest aktualny
- co jest jeszcze nieznane
- dlaczego stara notatka ma teraz znaczenie

Wyszukiwanie może znaleźć plik z podobnymi słowami. Nie jest w stanie wiarygodnie odpowiedzieć na te pytania. Wysłanie większego stosu plików do modelu językowego również nie tworzy trwałej pamięci. Usługa sprawdza, co zostało wybrane dla tego żądania. Po zakończeniu żądania przydatne połączenia mogą ponownie zniknąć.

## Trening również traci pierwotne ustawienie

Modele językowe uczą się wzorców z ogromnych zbiorów ludzkiej pracy. To właśnie czyni je użytecznymi. Dlatego też nie mogą pełnić roli wiernego archiwum wszystkiego, co je ukształtowało.

Pomysły z jednej książki, artykułu, rozmowy, tłumaczenia lub społeczności mieszają się z pomysłami z wielu innych. Model nie zachowuje każdego dzieła w nienaruszonym stanie, wraz z jego autorem, celem, odbiorcami, dowodami, sporami i późniejszymi poprawkami.

Oryginalne dzieło może nadal istnieć gdzie indziej. Dostawca może również przechowywać oddzielne kopie. Opisana tutaj strata ma miejsce wewnątrz wyszkolonego modelu: utrzymuje ona użyteczny wpływ pracy, ale nie jest w stanie odbudować wokół niej pełnego ludzkiego znaczenia.

Powtórzenie zdania nie jest równoznaczne z zachowaniem jego znaczenia. Model może odtworzyć znajome słowa, nie wiedząc, dlaczego zostały napisane, jaką sytuację opisali, czyj pogląd nie był widoczny lub co wydarzyło się później.

## Zaginiona historia kryje także uprzedzenia

Żaden model języka nie został wyuczony od całego świata.

Jej wiedza odzwierciedla to, co zostało spisane, zachowane, zebrane, przetłumaczone, licencjonowane, oznaczone i wybrane. Odzwierciedla także to, czego brakowało. Niektóre języki i społeczności opublikowały znacznie więcej materiałów niż inne. Archiwa częściej przechowują poglądy wpływowych instytucji niż wiedzę prywatną, lokalną czy ustną.

Osoby budujące model dokonują większej liczby wyborów dotyczących tego, co usunąć, nagrodzić, zniechęcić lub potraktować jako dobrą odpowiedź. Reguły dotyczące produktów dodają kolejną warstwę. Gotowa odpowiedź może przenosić wszystkie te wpływy, nie pokazując, który z nich miał wpływ na konkretne zdanie.

Cytat znaleziony podczas nowego wniosku nie ujawnia pełnej historii. Pokazuje źródło użyte lub nazwane w związku z tą prośbą, a nie wszystko, co nauczyło model, jak interpretować temat.

## Co zamiast tego zachowuje ten projekt

Robot Brain zachowuje źródło, zanim poprosi jakikolwiek model o pomoc w jego interpretacji. Źródło nie zmienia się po dodaniu podsumowania, sprostowania lub nowej interpretacji.

Późniejsza praca jest zapisana obok niej z datą i linkiem do odpowiedniego fragmentu. Nieudana próba może pozostać widoczna. Poprawiony wniosek może wskazywać na dowody, które go zmieniły. Jeżeli przyczyna zmiany nie jest znana, zapis o tym mówi.

Kiedy ktoś potrzebuje odpowiedzi lub dokumentu, kreator żądań gromadzi część historii potrzebną do wykonania zadania. Wynik może być krótszy niż pełny rekord, bez udawania, że ​​go zastępuje.

W uzyskaniu tego wyniku może pomóc model językowy. Nie może wymazać źródeł, napisać na nowo przeszłości ani sprawić, że nieuzasadnione domysły staną się częścią zaakceptowanego zapisu.

## Test praktyczny

Przydatny wynik powinien pozwolić czytelnikowi odpowiedzieć na cztery pytania:

1. Co się stało?
2. Jakie dowody potwierdzają tę relację?
3. Co się zmieniło, zawiodło lub pozostaje kwestionowane?
4. Co jest jeszcze nieznane?

Jeżeli płyta nie może odpowiedzieć na jedno z tych pytań, dopracowany język nie powinien zakrywać tej luki.
