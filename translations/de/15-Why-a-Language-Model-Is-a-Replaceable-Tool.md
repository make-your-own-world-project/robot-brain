> Deutsch: Maschinell unterstützte Übersetzung der maßgeblichen englischen Quelle. Korrekturen in der Muttersprache sind willkommen. [Englisch](../../15-Why-a-Language-Model-Is-a-Replaceable-Tool.md) | [Alle Sprachen](../README.md)

# Verwenden Sie ein Sprachmodell für den Job, nicht als Gedächtnis

![Tools, trainierte Dateien und Quellensammlungen führen separate Aufzeichnungen über ihre Herkunft und Begriffe.](../../illustrations/tool-model-source-index.png)

Robot Brain ist kein Sprachmodell mit zusätzlichem Speicher. Es ist die Aufzeichnungs-, Analyse-, Zusammenstellungs- und Prüfsoftware, die entscheidet, wann ein Sprachmodell hilfreich ist und welche begrenzte Aufgabe es erfüllen kann.

Das leistungsstärkste verfügbare Modell ist nicht immer die beste Wahl für diese Aufgabe.

Für schwierige Recherchen oder Schreibarbeiten kann ein kostenpflichtiges Sprachmodell geeignet sein. Ein kleines lokales Modell kann zur Hintergrunderklärung ausreichen. Die Suche kann ausreichen, um eine Passage zu finden. Ein fester Prozess kann sicherer sein, wenn die Antwort einer genauen Regel folgen muss. Manchmal ist die beste Antwort eine, die bereits überprüft und gespeichert wurde.

Der Anforderungsersteller trifft diese Auswahl anhand der Anforderungen des Jobs. Es kann ein Modell verwenden, mehrere eingeschränkte Methoden kombinieren, geprüfte Arbeit wiederverwenden oder überhaupt keinen Modellaufruf durchführen. Deshalb handelt es sich hier nicht um einen Proxy, der Anfragen einfach an einen anderen Dienst weiterleitet.

## Bezahlte Online-Modelle

Kommerzielle Sprachmodelldienste halfen beim Aufbau dieses Projekts. Sie unterstützten Recherche, Codierung, Schreiben und Überprüfung.

Sie verloren auch frühere Anweisungen, verkürzten Gespräche, vermuteten Ursachen, vergruben kurze Antworten in Füllmaterial und meldeten die Arbeit als abgeschlossen, bevor sie sie überprüften. Die Behebung dieser Fehler erforderte mehr bezahlte Vergütung und mehr menschliche Zeit.

Ihre tiefere Grenze ist kein schlechter Hinweis. Ein trainiertes Modell kann nicht die vollständige Geschichte der menschlichen Arbeit nachbilden, die es gelehrt hat. Es behält Muster bei, verliert aber verlässliche Verbindungen zu jedem Autor, Zweck, Publikum, Streit, jeder Korrektur und jedem fehlenden Standpunkt.

Dieses umfassende Wissen ist immer noch nützlich. Es sollte einfach nicht der einzige Ort sein, an dem die Geschichte eines Menschen existiert.

Für eine Online-Anfrage,Robot Brain Protokolliert, welches Modell verwendet wurde, was es erhalten hat, was es zurückgegeben hat, was der Service gekostet hat, welche Prüfungen durchgeführt wurden und ob das Ergebnis beibehalten wurde. Der nicht unterstützte Hintergrund ist nach wie vor ein Vorschlag des Modells und keine Quellenfakten.

## Das lokale Modell wird nicht auf die Person trainiert

Die aktuelle Installation läuft kleinQwenSprachmodell durchvLLMauf lokaler Hardware.Qwenist ein austauschbarer Mitwirkender, nicht das Projekt selbst.

Es lernt nicht durch Training der Gespräche, der Arbeit oder des Lebens der Person. Training würde diese Geschichte in ein Modell vermischen und den Weg zurück zu den ursprünglichen Worten und Ereignissen schwächen.

Stattdessen,Qwenerhält ausgewähltes Material für einen Auftrag nach Beendigung eines Gesprächs. Andere lokale Methoden haben bereits die Sprache, Aussagen, Beziehungen, Argumentation, Zeit, menschliche Erfahrung und Werte im Austausch untersucht.Qwenfügt den breiten Hintergrund hinzu, den diese Methoden nicht teilen. Dadurch lässt sich leichter erklären, was passiert ist und warum.

Qwenenthüllt nicht die verborgenen Gedanken, die Ausbildung oder die privaten Überlegungen des Online-Assistenten. Der nützliche Beitrag des Online-Assistenten ist bereits in der gespeicherten Konversation vorhanden. Allgemeines Hintergrundwissen ist nicht nur diesem Assistenten vorbehalten, daher kann ein anderes geeignetes Modell dabei helfen, die aufgenommenen Stücke zu verbinden.

DerQwenDer Messwert wird mit Modellname und Datum gespeichert. Es bleibt vom Gespräch getrennt und kann später korrigiert oder ersetzt werden. Die Anfrage muss niemals die lokale Hardware verlassen.

## Suche ist keine Erklärung

Durch die Suche können Passagen mit verwandten Wörtern oder Themen gefunden werden. Es kann nicht entscheiden, warum ein Ereignis wichtig war, ob eine Aktion eine andere verursachte oder was jemand meinte.

Diese Schlussfolgerungen erfordern Beweise, Geschichte und Raum für Korrekturen.

## Die Kosten beinhalten die Zeit der Person

Preis und Geschwindigkeit sind nicht die einzigen Kosten. Eine billige Antwort wird teuer, wenn jemand Stunden damit verbringt, den Fehler zu finden, den Verlauf noch einmal zu erklären und das Ergebnis zu reparieren.

Der Anforderungsersteller berücksichtigt daher Servicegebühren, Wartezeiten, Wiederholungsversuche, Energieverbrauch und menschliche Überprüfungen. Ein kleineres Modell, eine feste lokale Methode oder ein gespeichertes Ergebnis können mehr Wert schaffen, wenn die Arbeit einfacher zu überprüfen ist.

## Quellen bleiben identifizierbar

Originalaufzeichnungen, kopierter Text, Musterantworten, öffentliche Forschung, Zitate und spätere Rezensionen bleiben unterschiedliche Dinge.

Sofern bekannt und zulässig, werden in der Aufzeichnung der Ersteller, der Zweck, die Zielgruppe, das Datum, die Sprache, Beweise, Meinungsverschiedenheiten, Rechte und spätere Korrekturen gespeichert. Die öffentliche Verfügbarkeit und die Nennung allein berechtigen nicht zur Weiterverbreitung geschützten Materials.

Dieses Repository umfasst öffentliche Dokumentation und vom Projekt erstellte Illustrationen. Private Aufzeichnungen, Passwörter, Zugangsdaten, Anbietergeheimnisse und externes Material, das nicht zur Veröffentlichung freigegeben wurde, werden nicht berücksichtigt.
