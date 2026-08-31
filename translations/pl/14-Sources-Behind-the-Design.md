> Polski: Wspomagane maszynowo tłumaczenie wiarygodnego źródła w języku angielskim. Mile widziane poprawki w języku ojczystym. [angielski](../../14-Sources-Behind-the-Design.md) | [Wszystkie języki](../README.md)

# Badania stojące za projektem

![Różne tradycje badawcze wnoszą ograniczone metody, zachowując jednocześnie własną historię.](../../illustrations/academic-framework-lineages.png)

Ta strona jest przeznaczona dla czytelników, którzy chcą poznać szlak badawczy. Główne wyjaśnienie tego nie wymaga.

Na liście znajdują się pomysły i narzędzia, które zostały wykorzystane, przetestowane, porównane, odrzucone lub po prostu przestudiowane. Te relacje nie są takie same. Podanie źródła nie oznacza, że ​​jego autorzy uczestniczyli w projekcie lub go popierali.

## Zachowywanie źródeł i zmian w czasie

- Badania nad historią źródeł i zmieniającymi się informacjami ukształtowały sposób, w jaki rejestruje się, skąd pochodzi materiał, kiedy został zastosowany i co później go zastąpiło.
- [Grafit](https://github.com/getzep/graphiti)zostało zbadane jako jedno z podejść do rejestrowania połączeń zmieniających się w czasie.
- Ustalone metody rejestrowania zmian wpłynęły na zasadę, że aktualne podsumowanie nie może zastępować źródła, które się za nim kryje.

Pomysły te pomagają zachować ścieżkę, którą w przeciwnym razie ukryłaby odpowiedź nowego modelu lub przepisane podsumowanie.

## Oddzielenie roszczeń, wsparcia i sporu

- [Teoria struktury retorycznej Manna i Thompsona](https://aclanthology.org/J88-2003/)podał nazwy relacji między częściami dokumentu, takimi jak główny punkt i jego wyjaśnienie.
- [Schematy argumentacyjne Waltona, Reeda i Macagno](https://www.cambridge.org/core/books/abs/argumentation-schemes/introduction/745B75B5933D17D86AC2E85971DA34A2)dostarczyło ukierunkowanych pytań w celu sprawdzenia wsparcia i wniosków.
- [oAMF](https://github.com/arg-tech/oAMF)i xAIF dostarczyły metody rejestrowania roszczeń i ich powiązań.
- [ProBank](https://aclanthology.org/J05-1004/)wpłynął na sposób rejestrowania wypowiedzi i ról w nich występujących.
- [RSTformer](https://aclanthology.org/2023.acl-long.306/)i powiązane prace zostały przetestowane pod kątem znalezienia struktury dokumentu. Nie używano ich jako ostatecznych sędziów znaczenia lub rozumowania.

Źródła te zapobiegają ukryciu w jednym dopracowanym akapicie różnicy między twierdzeniem, jego poparciem, poprawką i sporem.

## Znajdowanie przydatnego materiału bez mylenia podobieństwa z prawdą

- [Maksymalna istotność krańcowa Carbonella i Goldsteina](https://aclanthology.org/X98-1025/)świadome sposoby równoważenia trafności i powtórzeń.
- [Lin i Bilmes o submodularnym podsumowaniu dokumentu](https://aclanthology.org/P11-1052/)świadome sposoby wyboru użytecznej grupy fragmentów w ramach limitu rozmiaru.
- [FactScore](https://aclanthology.org/2023.emnlp-main.741/)świadome pytania dotyczące tego, w jaki sposób roszczenia są potwierdzane.
- Badania nad podsumowaniami zbudowanymi na podstawie zarejestrowanych relacji oparte na testach, które skracają materiał bez odrzucania ważnych połączeń.

Wyszukiwanie i podsumowywanie może wskazać osobę w kierunku dowodów. Nie mogą zdecydować, dlaczego coś miało znaczenie, ani sprawić, że dany fragment będzie prawdziwy.

## Planowanie przed napisaniem

- [Reiter i Dale budują systemy generowania języka naturalnego](https://www.cambridge.org/core/books/building-natural-language-generation-systems/0AE70C709A9BFBDC80B349B2D22A78CD)wpłynęło na rozdzielenie wyboru treści, planowania i pisania zdań.
- [NLG krok po kroku](https://aclanthology.org/N19-1236/)I[planowanie makro zamiany danych na tekst](https://aclanthology.org/D19-1318/)świadome porównania metod planowania dokumentów.
- [ProsteNLG](https://github.com/simplenlg/simplenlg),[Ramy gramatyczne](https://www.grammaticalframework.org/), I[OpenCCG](https://github.com/OpenCCG/openccg)zostały ocenione jako sposoby na przekształcenie zaplanowanej treści w zdania.
- Badania znanych i nowych informacji, powiązań między zdaniami, rodzajów przekazu i form dokumentów wpływały na sposób uporządkowania wyjaśnień dla różnych czytelników.

Łącznie ta praca wspiera planowanie dokumentu przed poproszeniem modelu językowego o jego napisanie.

## Koszt ludzkiego zrozumienia i czytania

- Badania nad tym, jak ludzie budują zrozumienie i zarządzają wysiłkiem umysłowym na podstawie ograniczeń długości, nowych koncepcji i powtórzeń.
- [Coh-Metrix](https://www.cambridge.org/core/books/automated-evaluation-of-text-and-discourse-with-cohmetrix/AE4A1D5DCCBA1AE3A9632E9D4D380270),[TAAKO](https://www.linguisticanalysistools.org/taaco.html),[DocuScope](https://docuscope.github.io/), TextDescriptives i LFTK zostały ocenione jako sposoby porównania pisma.
- Teoria samostanowienia, badania nad znaczeniem życia i badania nad wartościami dostarczyły ograniczonych informacji na temat osobistego znaczenia. Nie obsługują automatycznej diagnozy ani szerokich profili osób.

## Ograniczone narzędzia do edycji

[LaserTagger](https://github.com/google-research/lasertagger),[GECToR](https://github.com/grammarly/gector), I[EdiT5](https://aclanthology.org/2022.findings-acl.260/)zostały ocenione pod kątem zadań edycyjnych, które ograniczają ilość nowych sformułowań, które można wprowadzić.

## Prawa i pełniejsze zapisy

Niniejsza dokumentacja nie obejmuje kopii wymienionych książek, artykułów, programów, plików przeszkolonych modeli ani zbiorów badawczych.[Źródła, licencje i prywatność](../../SOURCES-LICENSES-AND-PRIVACY.md)rejestruje przegląd licencji dla programów i przeszkolonych plików, które były faktycznie używane lub testowane.

Prywatny rekord badań zawiera więcej artykułów, publicznych standardów, narzędzi, zbiorów, dzieł kultury, odrzuconych podejść i wyników testów. Kredyt publiczny może wzrosnąć w miarę sprawdzania tych rejestrów, w tym pomysłów, które pomogły głównie poprzez pokazanie, co się nie sprawdziło.
