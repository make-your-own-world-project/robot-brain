> Deutsch: Maschinell unterstützte Übersetzung der maßgeblichen englischen Quelle. Korrekturen in der Muttersprache sind willkommen. [Englisch](../../14-Sources-Behind-the-Design.md) | [Alle Sprachen](../README.md)

# Forschung hinter dem Design

![Unterschiedliche Forschungstraditionen steuern begrenzte Methoden bei, behalten aber ihre eigene Geschichte bei.](../../illustrations/academic-framework-lineages.png)

Diese Seite richtet sich an Leser, die den Recherchepfad verfolgen möchten. Die Haupterklärung erfordert dies nicht.

Die Liste enthält Ideen und Tools, die verwendet, getestet, verglichen, abgelehnt oder einfach studiert wurden. Diese Beziehungen sind nicht dieselben. Die Nennung einer Quelle bedeutet nicht, dass deren Autoren am Projekt beteiligt waren oder es befürworteten.

## Behalten Sie Quellen und Änderungen im Laufe der Zeit bei

- Die Erforschung der Quellengeschichte und sich ändernder Informationen prägte die Art und Weise, wie in Aufzeichnungen festgehalten wird, woher das Material stammte, wann es verwendet wurde und was es später ersetzte.
- [Graphiti](https://github.com/getzep/graphiti)wurde als ein Ansatz zur Aufzeichnung von Verbindungen untersucht, die sich im Laufe der Zeit ändern.
- Etablierte Methoden zur Aufzeichnung von Änderungen enthielten die Regel, dass eine aktuelle Zusammenfassung die dahinter stehende Quelle nicht ersetzen darf.

Diese Ideen tragen dazu bei, den Weg zu bewahren, den eine neue Modellantwort oder eine neu geschriebene Zusammenfassung sonst verbergen würde.

## Trennen Sie Ansprüche, Unterstützung und Meinungsverschiedenheiten

- [Die rhetorische Strukturtheorie von Mann und Thompson](https://aclanthology.org/J88-2003/)bereitgestellte Namen für Beziehungen zwischen Teilen eines Dokuments, beispielsweise einem Hauptpunkt und seiner Erklärung.
- [Walton, Reed und Macagnos Argumentationsschemata](https://www.cambridge.org/core/books/abs/argumentation-schemes/introduction/745B75B5933D17D86AC2E85971DA34A2)stellte gezielte Fragen zur Prüfung von Belegen und Schlussfolgerungen bereit.
- [oAMF](https://github.com/arg-tech/oAMF)und xAIF lieferte Ansätze zur Erfassung von Ansprüchen und deren Zusammenhängen.
- [PropBank](https://aclanthology.org/J05-1004/)Einfluss darauf, wie Aussagen und die darin enthaltenen Rollen aufgezeichnet werden.
- [RSTformer](https://aclanthology.org/2023.acl-long.306/)und verwandte Arbeiten wurden getestet, um die Dokumentstruktur zu finden. Sie dienten nicht als endgültige Richter der Bedeutung oder Argumentation.

Diese Quellen helfen zu verhindern, dass ein ausgefeilter Absatz den Unterschied zwischen einer Behauptung, ihrer Unterstützung, einer Korrektur und einer Meinungsverschiedenheit verbirgt.

## Nützliches Material finden, ohne Ähnlichkeit mit Wahrheit zu verwechseln

- [Die maximale marginale Relevanz von Carbonell und Goldstein](https://aclanthology.org/X98-1025/)informierte Wege, um Relevanz und Wiederholung in Einklang zu bringen.
- [Lin und Bilmes zur submodularen Dokumentenzusammenfassung](https://aclanthology.org/P11-1052/)fundierte Möglichkeiten zur Auswahl einer nützlichen Gruppe von Passagen innerhalb einer Größenbeschränkung.
- [FActScore](https://aclanthology.org/2023.emnlp-main.741/)fundierte Fragen dazu, wie genau Ansprüche gestützt werden.
- Forschung zu Zusammenfassungen, die aus aufgezeichneten Beziehungen erstellt wurden, informierte Tests, die den Stoff kürzen, ohne die wichtigen Zusammenhänge zu verwerfen.

Suche und Zusammenfassung können eine Person auf Beweise hinweisen. Sie können nicht entscheiden, warum etwas wichtig ist, oder eine Passage wahr machen.

## Planen Sie vor dem Schreiben

- [Reiter und Dale bauen Systeme zur Erzeugung natürlicher Sprache auf](https://www.cambridge.org/core/books/building-natural-language-generation-systems/0AE70C709A9BFBDC80B349B2D22A78CD)beeinflusste die Trennung von Inhaltsauswahl, Planung und Satzformulierung.
- [Schritt-für-Schritt-NLG](https://aclanthology.org/N19-1236/)Und[Daten-zu-Text-Makroplanung](https://aclanthology.org/D19-1318/)fundierte Vergleiche von Dokumentenplanungsmethoden.
- [SimpleNLG](https://github.com/simplenlg/simplenlg),[Grammatikalischer Rahmen](https://www.grammaticalframework.org/), Und[OpenCCG](https://github.com/OpenCCG/openccg)wurden als Möglichkeiten bewertet, geplante Inhalte in Sätze umzusetzen.
- Die Erforschung bekannter und neuer Informationen, Verbindungen zwischen Sätzen, Kommunikationsarten und Dokumentformen beeinflusste die Reihenfolge der Erklärungen für verschiedene Leser.

Zusammengenommen unterstützt diese Arbeit die Planung eines Dokuments, bevor ein Sprachmodell gebeten wird, es zu schreiben.

## Menschliches Verständnis und Lesekosten

- Untersuchungen darüber, wie Menschen Verständnis aufbauen und geistige Anstrengung bewältigen, informierten über Längengrenzen, neue Konzepte und Wiederholungen.
- [Coh-Metrix](https://www.cambridge.org/core/books/automated-evaluation-of-text-and-discourse-with-cohmetrix/AE4A1D5DCCBA1AE3A9632E9D4D380270),[TAACO](https://www.linguisticanalysistools.org/taaco.html),[DocuScope](https://docuscope.github.io/), TextDescriptives und LFTK wurden als Möglichkeiten zum Vergleich des Schreibens bewertet.
- Selbstbestimmungstheorie, Forschung zum Sinn des Lebens und Forschung zu Werten lieferten begrenzte Fragen zum persönlichen Sinn. Sie unterstützen keine automatische Diagnose oder umfassende Personenprofile.

## Begrenzte Bearbeitungswerkzeuge

[LaserTagger](https://github.com/google-research/lasertagger),[GECToR](https://github.com/grammarly/gector), Und[Bearbeiten5](https://aclanthology.org/2022.findings-acl.260/)wurden auf Bearbeitungsaufgaben hin untersucht, die die mögliche Einführung neuer Formulierungen begrenzen.

## Rechte und umfassendere Aufzeichnungen

Diese Dokumentation umfasst keine Kopien der genannten Bücher, Aufsätze, Programme, Dateien trainierter Modelle oder Forschungssammlungen.[Quellen, Lizenzen und Datenschutz](../../SOURCES-LICENSES-AND-PRIVACY.md)zeichnet die Lizenzüberprüfung für Programme und trainierte Dateien auf, die tatsächlich verwendet oder getestet wurden.

Die private Forschungsaufzeichnung enthält weitere Arbeiten, öffentliche Standards, Werkzeuge, Sammlungen, kulturelle Werke, abgelehnte Ansätze und Testergebnisse. Die öffentliche Anerkennung kann wachsen, wenn diese Aufzeichnungen überprüft werden, einschließlich Ideen, die vor allem dadurch geholfen haben, dass sie zeigten, was nicht funktioniert hat.
