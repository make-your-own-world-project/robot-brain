> Deutsch: Maschinell unterstützte Übersetzung der maßgeblichen englischen Quelle. Korrekturen in der Muttersprache sind willkommen. [Englisch](../../01-Why-Large-Language-Models-Cannot-Preserve-the-Full-Story.md) | [Alle Sprachen](../README.md)

# Warum große Sprachmodelle nicht die ganze Geschichte bewahren können

![Gespeicherte Teile verlieren an Wert, wenn ihre Quellen, Beziehungen und Geschichte getrennt werden.](../../illustrations/ordinary-storage-loses-context.png)

Die am stärksten bezahlten Sprachmodelle, die beim Aufbau dieses Projekts verwendet wurden, könnten beeindruckende Arbeit leisten. Sie könnten schreiben, recherchieren, erklären und bei der Lösung schwieriger Probleme helfen. Sie konnten immer noch nicht die gesamte Geschichte eines langen Projekts bewahren.

Eine spätere Antwort erinnert sich möglicherweise an die Schlussfolgerung, verliert jedoch die fehlgeschlagenen Versuche, Korrekturen und Beweise, die zu dieser Schlussfolgerung geführt haben. Frühere Anweisungen könnten verschwinden, wenn ein Gespräch zu lang wird. Das Modell schrieb weiter, als ob nichts Wichtiges verloren gegangen wäre.

Das ist ein ernstes Problem, wenn der fehlende Verlauf die Zeit, das Wissen oder die Erfahrung einer Person widerspiegelt.

## Dateien reichen nicht aus

Ein Ordner kann jede Notiz, Konversation, jedes Bild und jede Aufgabe enthalten, ohne dabei die Geschichte zu verlieren, die sie verbindet.

Monate später muss eine Person möglicherweise Folgendes wissen:

- Womit begann die Arbeit?
- welche Ideen berücksichtigt wurden
- warum ein Versuch scheiterte
- Welche Beweise haben den Plan geändert?
- welche Schlussfolgerung aktuell ist
- was noch unbekannt ist
- Warum eine alte Notiz jetzt wichtig ist

Durch die Suche kann eine Datei mit ähnlichen Wörtern gefunden werden. Es kann diese Fragen nicht zuverlässig beantworten. Auch das Senden eines größeren Dateistapels an ein Sprachmodell erzeugt keinen permanenten Speicher. Der Dienst sieht, was für diese Anfrage ausgewählt wurde. Wenn die Anfrage endet, verschwinden die nützlichen Verbindungen möglicherweise wieder.

## Auch beim Training geht die ursprüngliche Einstellung verloren

Sprachmodelle lernen Muster aus riesigen Sammlungen menschlicher Arbeit. Das macht sie nützlich. Aus diesem Grund können sie auch nicht als treues Archiv all dessen dienen, was sie geprägt hat.

Ideen aus einem Buch, Artikel, Gespräch, einer Übersetzung oder einer Community vermischen sich mit Ideen aus vielen anderen. Das Modell hält nicht jedes Werk mit seinem Autor, Zweck, Publikum, Beweisen, Meinungsverschiedenheiten und späteren Korrekturen intakt.

Das Originalwerk existiert möglicherweise noch woanders. Ein Anbieter kann auch separate Kopien aufbewahren. Der hier beschriebene Verlust geschieht innerhalb des trainierten Modells: Es behält den nützlichen Einfluss der Arbeit, kann aber nicht die vollständige menschliche Bedeutung um sie herum wiederherstellen.

Einen Satz zu wiederholen ist nicht dasselbe wie die Bedeutung beizubehalten. Ein Modell reproduziert möglicherweise bekannte Wörter, ohne zu wissen, warum sie geschrieben wurden, welche Situation sie beschrieben, wessen Sichtweise fehlte oder was später geschah.

## Die fehlende Historie verbirgt auch Voreingenommenheit

Kein Sprachmodell, das von der ganzen Welt gelernt wurde.

Sein Wissen spiegelt wider, was niedergeschrieben, aufbewahrt, gesammelt, übersetzt, lizenziert, gekennzeichnet und ausgewählt wurde. Es spiegelt auch wider, was fehlte. Einige Sprachen und Gemeinschaften haben weitaus mehr veröffentlichtes Material als andere. Archive bewahren die Ansichten mächtiger Institutionen häufiger als privates, lokales oder mündliches Wissen.

Menschen, die das Modell erstellen, treffen mehr Entscheidungen darüber, was sie entfernen, belohnen, entmutigen oder als gute Antwort behandeln möchten. Produktregeln fügen eine weitere Ebene hinzu. Eine fertige Antwort kann alle diese Einflüsse enthalten, ohne dass ersichtlich ist, welcher davon einen bestimmten Satz beeinflusst hat.

Ein bei einer neuen Anfrage gefundenes Zitat gibt nicht den vollständigen Verlauf preis. Es zeigt eine für diese Anfrage verwendete oder benannte Quelle, nicht alles, was dem Modell beigebracht hat, wie das Thema zu interpretieren ist.

## Was dieses Projekt stattdessen behält

Robot Brain Behält die Quelle bei, bevor er ein Modell um Hilfe bei der Interpretation bittet. Die Quelle ändert sich nicht, wenn eine Zusammenfassung, Korrektur oder neue Interpretation hinzugefügt wird.

Spätere Arbeiten werden daneben mit einem Datum und einem Link zurück zur entsprechenden Passage gespeichert. Ein fehlgeschlagener Versuch kann sichtbar bleiben. Eine korrigierte Schlussfolgerung kann auf die Beweise hinweisen, die sie geändert haben. Wenn der Grund für eine Änderung unbekannt ist, wird dies im Protokoll angegeben.

Wenn jemand eine Antwort oder ein Dokument benötigt, sammelt der Request Builder den Teil dieses Verlaufs, der für die Aufgabe benötigt wird. Das Ergebnis kann kürzer als der gesamte Datensatz sein, ohne den Anspruch zu erheben, ihn zu ersetzen.

Ein Sprachmodell kann bei diesem Ergebnis hilfreich sein. Es kann nicht die Quellen löschen, die Vergangenheit nicht neu schreiben oder eine nicht bestätigte Vermutung zu einem Teil der akzeptierten Aufzeichnung machen.

## Der Praxistest

Ein nützliches Ergebnis sollte es einem Leser ermöglichen, vier Fragen zu beantworten:

1. Was ist passiert?
2. Welche Beweise stützen diese Darstellung?
3. Was hat sich geändert, ist gescheitert oder bleibt umstritten?
4. Was ist noch unbekannt?

Wenn die Akte eine dieser Fragen nicht beantworten kann, sollte eine ausgefeilte Sprache die Lücke nicht verdecken.
