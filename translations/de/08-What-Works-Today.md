> Deutsch: Maschinell unterstützte Übersetzung der maßgeblichen englischen Quelle. Korrekturen in der Muttersprache sind willkommen. [Englisch](../../08-What-Works-Today.md) | [Alle Sprachen](../README.md)

# Was die aktuelle Implementierung bewirkt

![Ideen, Tests, Misserfolge und nachgewiesene Fähigkeiten bleiben klar getrennt.](../../illustrations/evidence-implementation-gates.png)

Robot Brain betreibt Software zum Bewahren und Wiederherstellen der Bedeutung aufgezeichneter Werke. Es handelt sich nicht um einen Vorschlag für einen Chatbot und seine aktuelle Implementierung ist kein Sprachmodell.

## Funktionen in der aktuellen Implementierung

Aufgezeichnete Läufe zeigen, dass die Software Folgendes kann:

- Bewahren Sie ein abgeschlossenes Gespräch auf, ohne es durch eine Zusammenfassung zu ersetzen
- Halten Sie die Worte der Person von Musterantworten und späteren Interpretationen getrennt
- Erstellen Sie detaillierte Erkenntnisse über Sprache, Bedeutung, Argumentation, Zeit, menschliche Erfahrung und Werte
- Verbinden Sie jedes gespeicherte Ergebnis mit dem Teil des Gesprächs dahinter
- Behalten Sie Korrekturen, Meinungsverschiedenheiten, fehlgeschlagene Arbeiten und unbeantwortete Fragen bei
- Fügen Sie einen veralteten lokalen Allgemeinwissensüberblick hinzu, ohne das ursprüngliche Online-Modell aufzurufen
- Sammeln Sie die einbehaltenen Beiträge für einen angeforderten Wiederaufbau
- Aufzeichnen, was überprüft, abgelehnt, korrigiert und akzeptiert wurde
- Ersetzen Sie einen Bildschirm oder ein teilnehmendes Sprachmodell, ohne den gespeicherten Verlauf zu ersetzen

Dabei handelt es sich um Funktionen der Software rund um die Modelle. Es handelt sich hierbei nicht um Fähigkeiten, die beansprucht werdenQwen,LibreChat, oder ein Online-Assistent.

## Was ist im Meilenstein „Abgeschlossene Konversation“ passiert?

Die getestete Konversation wurde mit den Nachrichten der Person und den Antworten des Online-Modells in der Reihenfolge gespeichert.

Fokussierte lokale Methoden erstellten dann separate Aufzeichnungen über den Austausch. Ihre Arbeit umfasste Sprache und Bedeutung, Argumentation, psychologische Beobachtungen, philosophische Beobachtungen, Beziehungen und Veränderungen im Laufe der Zeit. Jeder beibehaltene Beitrag blieb an das Ausgangsmaterial und die Methode, mit der er erstellt wurde, gebunden.

Diese detaillierten Methoden verfügen bewusst nicht über das breite Hintergrundwissen eines Allzweckmodells. Ein kleiner EinheimischerQwenModell, serviert vonvLLM, ausgewähltes Material gelesen und eine datierte Übersicht hinzugefügt. Seine Aufgabe bestand darin, allgemeine Hintergrundinformationen bereitzustellen, die die einzelnen Erkenntnisse miteinander verknüpften und den Austausch als Ganzes verständlich machten.

Qwenhat die verborgenen Gedanken, den Trainingsverlauf oder den privaten internen Zustand des ursprünglichen Modells nicht wiederhergestellt. Der nützliche Beitrag des ursprünglichen Modells war bereits in seinen gespeicherten Nachrichten vorhanden. Ein umfassendes Hintergrundwissen wurde durch ein austauschbares lokales Modell bereitgestellt, da dieses Wissen nicht nur dem ursprünglichen Anbieter vorbehalten war.

## Was „vollständig“ für diesen Meilenstein bedeutet

Das Wort bezieht sich auf die gepflegte Beitragsliste für diesen Lauf. Jede Quellmeldung und jeder Beitrag, den der Prozess für die Rekonstruktion erhalten hat, kann wiedergefunden und gesammelt werden.

Dies bedeutet nicht, dass ein Modell eine vollständige Interpretation lieferte. Die Errungenschaft besteht darin, dass die akzeptierten Stücke erhalten bleiben, nach Quelle und Methode getrennt sind und für die Rekonstruktion verfügbar sind, ohne dass der ursprüngliche Online-Austausch erneut ausgeführt werden muss.

## Wie der Anspruch gestützt wird

Der Lauf zeichnet auf, welche Teile ausgeführt wurden, was jeder empfangen hat, was jeder zurückgegeben hat, welche Beiträge abgelehnt wurden und welche Prüfungen bestanden wurden. Die Rekonstruktion wird anhand der eigenen gespeicherten Liste der erwarteten Datensätze gemessen.

Ein Komponententest wird als Komponententest bezeichnet. Ein verbundener Lauf wird als zusammenhängender Lauf bezeichnet. Geplante Arbeiten bleiben von der aktuellen Umsetzung getrennt.

Zu den nächsten Arbeiten gehören umfassendere unabhängige Tests, die Unterstützung weiterer Arten von Aufzeichnungen, mehr Sprachen und Kulturen, klarere Überprüfungsbildschirme und eine bessere Messung der Zeit, die Menschen mit dem Lesen und Korrigieren von Ergebnissen verbringen.
