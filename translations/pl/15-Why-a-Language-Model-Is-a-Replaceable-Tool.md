> Polski: Wspomagane maszynowo tłumaczenie wiarygodnego źródła w języku angielskim. Mile widziane poprawki w języku ojczystym. [angielski](../../15-Why-a-Language-Model-Is-a-Replaceable-Tool.md) | [Wszystkie języki](../README.md)

# Używaj modelu językowego do zadania, a nie jako pamięci

![Narzędzia, przeszkolone pliki i kolekcje źródłowe przechowują oddzielne zapisy dotyczące ich pochodzenia i terminów.](../../illustrations/tool-model-source-index.png)

Robot Brain nie jest modelem językowym z dodatkową pamięcią. To oprogramowanie do prowadzenia rejestrów, analiz, składania i sprawdzania decyduje, kiedy model językowy będzie pomocny i jakie ograniczone zadanie może wykonać.

Najmocniejszy dostępny model nie zawsze jest najlepszym wyborem do tego zadania.

Płatny model językowy może być odpowiedni w przypadku trudnych badań lub pisania. Do wyjaśnienia tła może wystarczyć mały model lokalny. Wyszukiwanie może wystarczyć, aby znaleźć przejście. Ustalony proces może być bezpieczniejszy, gdy odpowiedź musi być zgodna z dokładną regułą. Czasami najlepszą odpowiedzią jest ta, która została już sprawdzona i zapisana.

Konstruktor żądań dokonuje wyboru na podstawie potrzeb zadania. Może używać modelu, łączyć kilka ograniczonych metod, ponownie wykorzystywać sprawdzoną pracę lub w ogóle nie wywoływać modelu. Dlatego nie jest to serwer proxy, który po prostu przekazuje żądania do innej usługi.

## Płatne modele online

W budowie tego projektu pomogły komercyjne usługi oparte na modelach językowych. Wspierali badania, kodowanie, pisanie i recenzowanie.

Gubili także wcześniejsze instrukcje, skracali rozmowy, domyślali się przyczyn, zakopywali krótkie odpowiedzi w wypełniaczach i zgłaszali pracę jako ukończoną przed jej sprawdzeniem. Naprawianie tych błędów wymagało więcej płatnego zasiłku i więcej ludzkiego czasu.

Ich głębsza granica nie jest złą wskazówką. Wyszkolony model nie jest w stanie odbudować pełnej historii ludzkiej pracy, która go nauczyła. Zachowuje wzorce, tracąc jednocześnie niezawodne powiązania z każdym autorem, celem, odbiorcą, sporem, korektą i brakującym punktem widzenia.

Ta szeroka wiedza jest nadal przydatna. Po prostu nie powinno stać się jedynym miejscem, w którym istnieje czyjaś historia.

Aby złożyć wniosek online,Robot Brain rejestruje, jakiego modelu użyto, co otrzymał, co zwrócił, jaki był koszt usługi, jakie kontrole przeprowadzono i czy wynik został zachowany. Niepotwierdzone tło pozostaje raczej sugestią modelu niż faktem źródłowym.

## Model lokalny nie jest trenowany na danej osobie

Obecna instalacja działa na małą skalęQwenmodel języka poprzezvLLMna sprzęcie lokalnym.Qwenjest jednym wymiennym wkładem, a nie samym projektem.

Nie uczy się poprzez szkolenie z rozmów, pracy czy życia danej osoby. Szkolenie połączyłoby tę historię w model i osłabiłoby drogę powrotną do oryginalnych słów i wydarzeń.

Zamiast,Qwenpo zakończeniu rozmowy otrzymuje wybrany materiał do jednego zadania. Inne lokalne metody zbadały już język, wypowiedzi, relacje, rozumowanie, czas, ludzkie doświadczenie i wartości w wymianie.Qwendodaje szerokie tło, którego te metody nie mają wspólnego. Dzięki temu łatwiej będzie wyjaśnić, co się stało i dlaczego.

Qwennie ujawnia ukrytych myśli, przeszkolenia ani prywatnego rozumowania asystenta online. Przydatny wkład asystenta online jest już obecny w zapisanej rozmowie. Ogólna wiedza nie jest przypisana wyłącznie temu asystentowi, dlatego inny odpowiedni model może pomóc w połączeniu nagranych utworów.

TheQwenodczyt jest zapisywany z nazwą modelu i datą. Pozostaje oddzielony od rozmowy i można go później poprawić lub wymienić. Żądanie nigdy nie musi opuszczać lokalnego sprzętu.

## Wyszukiwanie nie jest wyjaśnieniem

Funkcja wyszukiwania pozwala znaleźć fragmenty zawierające powiązane słowa lub tematy. Nie może decydować, dlaczego dane wydarzenie miało znaczenie, czy jedno działanie spowodowało drugie, ani co ktoś miał na myśli.

Wnioski te wymagają dowodów, historii i miejsca na korektę.

## Koszt obejmuje czas danej osoby

Cena i szybkość to nie jedyne koszty. Tania odpowiedź staje się kosztowna, gdy ktoś spędza godziny na szukaniu błędu, ponownym wyjaśnianiu historii i naprawianiu wyniku.

Dlatego kreator żądań bierze pod uwagę opłaty za usługi, oczekiwanie, ponowne próby, zużycie energii i sprawdzanie przez człowieka. Mniejszy model, ustalona metoda lokalna lub zapisany wynik mogą stworzyć większą wartość, gdy łatwiej będzie sprawdzić jego pracę.

## Źródła pozostają możliwe do zidentyfikowania

Oryginalne zapisy, skopiowany tekst, odpowiedzi modelowe, badania publiczne, cytaty i późniejsze recenzje pozostają różnymi rzeczami.

Jeśli jest to znane i dozwolone, w zapisie zapisuje się twórcę, cel, odbiorców, datę, język, dowody, spory, prawa i późniejsze poprawki. Publiczna dostępność i uznanie same w sobie nie dają pozwolenia na redystrybucję materiałów chronionych.

To repozytorium zawiera publiczną dokumentację i ilustracje utworzone w ramach projektu. Pomija prywatne zapisy, hasła, dane dostępu, tajemnice dostawców i materiały zewnętrzne, które nie zostały dopuszczone do publikacji.
