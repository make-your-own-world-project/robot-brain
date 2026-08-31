> Polski: Wspomagane maszynowo tłumaczenie wiarygodnego źródła w języku angielskim. Mile widziane poprawki w języku ojczystym. [angielski](../../17-How-Language-Models-Lose-Meaning-and-How-to-Preserve-It.md) | [Wszystkie języki](../README.md)

# Lekcje, które zmieniły projekt

![Wyciągnięte wnioski ze skutecznych i nieudanych podejść można wykorzystać w następnym projekcie.](../../illustrations/discoveries-engineering-lessons.png)

Projekt rozwinął się dzięki testom, w tym nieudanym próbom. Poniższe lekcje wyjaśniają, dlaczego wygląda ona inaczej niż komercyjna usługa czatu.

## W badaniu pisarskim wykorzystano oczyszczony materiał publiczny

Aby zbadać organizację różnych rodzajów pisma, w ramach projektu zbadano wybrane książki, przemówienia, pisma rządu Stanów Zjednoczonych i gazety historyczne, należące do domeny publicznej. Odrębnie zbadano niewielką liczbę norm publicznych, które wyraźnie zezwalają na użytek publiczny.

W pracy zmierzono i porównano pisanie. Nie trenował nowego ogólnego modelu języka. Dokumenty publiczne nie zawierają kopii tekstów źródłowych.

Każdy zapis badania określa źródło publiczne, powód, dla którego można je zbadać, jaką część wykorzystano, a także krótki cyfrowy odcisk palca potwierdzający dokładny materiał. Duży indeks Projektu Gutenberg opublikowany podCC BY 4.0został sprawdzony jedynie w celu zrozumienia jego zawartości; indeksowane książki nie zostały pobrane ani zmierzone za pomocą tego indeksu.

## Oddzielne metody zachowują to, co znajdą

Metody lokalne badają język, znaczenie, relacje, rozumowanie, czas, ludzkie doświadczenie i wartości. Każda metoda zapisuje własne ustalenia wraz z częścią rozmowy, która za nimi stoi.

Dzięki temu jedna metoda nie połknie pozostałych. Ustalenie można poprawić bez konieczności przepisywania źródła lub jakiejkolwiek innej analizy.

## Ogólna wiedza łączy elementy

Metody ukierunkowane mogą dawać dokładne wyniki, które trudno jest zrozumieć łącznie. Nie podzielają szerokiej wiedzy ogólnej, z której korzysta model językowy podczas czytania zwykłej rozmowy.

MałyQwenmodel działający lokalnie dodaje to tło po zakończeniu skoncentrowanej pracy. Pomaga wyjaśnić sytuację, cele uczestników, powód prośby i sposób, w jaki jedno wydarzenie doprowadziło do drugiego.

Model lokalny nie odzyskuje ukrytej wiedzy pierwotnego asystenta. Wkład asystenta jest już obecny w jego komunikatach.Qwendostarcza ogólnego tła, które jest wystarczająco szerokie, aby mógł je zapewnić inny odpowiedni model.

Jej odczyt jest datowany i przechowywany oddzielnie. Późniejszy model może dodać inny widok bez przepisywania wcześniejszego.

## Trening modelowy utrzymuje wpływ, ale traci pełny zapis ludzki

Model językowy uczy się przydatnych wzorców z materiału stworzonego przez człowieka. Nie zachowuje każdego dzieła w nienaruszonym stanie, wraz z jego twórcą, celem, dowodami, sporami i późniejszą historią.

Model może odtworzyć słowa lub dobrze wykorzystać pomysł. Nadal nie da się rzetelnie odtworzyć, dlaczego te słowa istniały, co miał na myśli ich autor, czyja relacja zaginęła i co później korygowało dzieło.

Żadne oprogramowanie nie jest w stanie odzyskać historii, której model nigdy nie zachował. Dzięki takiemu rozwiązaniu można zapobiec takim samym stratom w aktach danej osoby.

## Odchylenie nie jest jednym prostym ustawieniem

To, co model może rozpoznać, zależy od tego, co stworzyli ludzie, jakie zachowano archiwa, w jakich językach zebrano, w jaki sposób materiał został przetłumaczony i oznaczony, co nagrodzono budowniczych i jakie zasady produktu zostały dodane później.

Żaden pojedynczy wynik nie jest w stanie tego wszystkiego wyjaśnić. Praktyczną reakcją jest zapewnienie widoczności źródeł, określenie modelu i daty ustalenia, zachowanie niezgodności i pozostawienie brakujących informacji oznaczonych jako brakujące.

## Większy monit ma nadal charakter tymczasowy

Nadanie modelowi większej ilości tekstu może pomóc w jednej prośbie. Nie tworzy niezawodnej pamięci. Wybrany materiał może zostać w trakcie rozmowy skrócony, a inny model może go później zinterpretować inaczej.

Zapisany rekord musi istnieć przed i po żądaniu.

## Podobne słowa nie dowodzą związku

Wyszukiwanie może znaleźć możliwe dopasowania. Nie można ustalić, czy jeden fragment spowodował, skorygował, zaprzeczył lub był kontynuacją innego.

Te relacje potrzebują własnych dowodów.

## „Brak odpowiedzi” może być poprawną odpowiedzią

„Nie znaleziono”, „nie dotyczy”, „nieznany” i „fałszywy” oznaczają różne rzeczy. Każdy skupiony czytelnik i wkład w model językowy musi zachować te różnice, a nie generować prawdopodobną odpowiedź jedynie po to, aby podtrzymać rozmowę.

## Odrzucona praca wciąż czegoś uczy

Niepotwierdzona odpowiedź nie wchodzi do zaakceptowanej wiedzy. Odpowiedź i powód jej odrzucenia mogą w dalszym ciągu zapobiec ponownemu zakupowi i sprawdzeniu tego samego błędu.

## Śledź, kto co powiedział

Ludzkie słowa, cytaty, wzorcowe odpowiedzi, lokalne ustalenia i późniejsze recenzje nie mogą być łączone ze sobą bez zmiany ich znaczenia.

Każdy wkład jest oznaczony etykietą ze swoim źródłem.

## Planowanie, pisanie i sprawdzanie to różne zadania

Konstruktor żądań może wybrać właściwe dowody, podczas gdy model językowy nadal pisze źle. Model może jasno pisać na podstawie błędnych dowodów. Może także podążać za dowodami, a mimo to zawieść czytelnika, tworząc o wiele za dużo tekstu.

Oddzielne zaznaczanie, zapisywanie i sprawdzanie sprawia, że ​​awaria jest widoczna. Uszkodzoną część można wymienić bez konieczności odbudowy wszystkiego.

## Pełny dokument wymaga jednego planu

Niezależne pisanie sekcji powodowało powtarzanie, zmianę terminów i nieobsługiwane połączenia. Dokument musi być zaplanowany i sprawdzony jako jedna całość, nawet jeśli pomaga w jego tworzeniu kilka narzędzi.

## Czytanie i poprawianie to realne koszty

Czytanie wypełniaczy, szukanie ukrytych odpowiedzi i poprawianie powtarzających się błędów zajmuje czas i energię. Koszt ten należy uwzględnić w każdym uczciwym rachunku wyniku.

## Pomoc z zewnątrz nie potrzebuje całej historii

Model języka online może uzyskać wystarczającą ilość dowodów dla jednego zadania bez konieczności otrzymywania niepowiązanych zapisów, prywatnej historii lub narzędzi przygotowujących przyszłe żądania.

Przydatna odpowiedź powraca. Pełny zapis pozostaje tam, gdzie dana osoba go kontroluje.
