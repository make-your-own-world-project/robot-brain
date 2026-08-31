> Deutsch: Maschinell unterstützte Übersetzung der maßgeblichen englischen Quelle. Korrekturen in der Muttersprache sind willkommen. [Englisch](../../README.md) | [Alle Sprachen](../README.md)

# Behalten Sie das Protokoll. Ersetzen Sie das Modell.

![Die Aufzeichnungen einer Person bleiben an einem Ort, während separate Arbeitsteile begrenzte Aufgaben erledigen.](../../illustrations/specialist-assembly-line-vs-giant-chatbot.png)

Robot Brain ist eine Software zur Bewahrung der Geschichte und Bedeutung langjähriger menschlicher Arbeit. Es handelt sich nicht um ein Sprachmodell, keinen Chatbot oder einen Dienst, der jede Frage an ein Modell weiterleitet.

Große Sprachmodelle können recherchieren, schreiben, erklären und bei der Lösung schwieriger Probleme helfen. Die darauf aufbauenden kostenpflichtigen Dienste sind immer noch temporäre Arbeitsbereiche. Sie können ein langes Gespräch abkürzen, frühere Anweisungen verlieren, Schlussfolgerungen von ihren Beweisen trennen und weiterschreiben, als ob die fehlende Geschichte noch vorhanden wäre. Eine Person verbringt dann mehr Zeit und bezahlte Nutzung damit, bereits bereitgestellten Kontext wiederherzustellen.

Diese Software verändert dort, wo der bleibende Wert lebt. Die Gespräche, Dokumente, Entscheidungen, Fehlversuche, Korrekturen und unbeantworteten Fragen der Person bleiben in den von der Person kontrollierten Aufzeichnungen. Lokale Programme können diese Datensätze untersuchen. Ein Sprachmodell kann bei einer ausgewählten Aufgabe hilfreich sein, sein Beitrag wird jedoch als veraltete, überprüfbare Arbeit in die Akte aufgenommen. Das Modell kann dann ausgetauscht werden, ohne dass die Historie mitgenommen wird.

[Lesen Sie diese Dokumentation in einer anderen Sprache.](../README.md)

## Der Unterschied in einer Ansicht

| Ein kommerzieller Sprachmodelldienst | Robot Brain |
|---|---|
| Erstellt eine Antwort aus dem Material, das sich derzeit in der Arbeitsansicht befindet. | Behält die vollständige Quelle und die dazugehörige Geschichte. |
| Kann frühere Gespräche verkürzen oder verlieren, wenn die Arbeit zunimmt. | Speichert Gespräche außerhalb jedes Modells, sodass sie wiederverwendet werden können. |
| Kombiniert Wissen aus vielen Quellen ohne einen vollständigen Weg zurück zu jeder Quelle und ihren Umständen. | Bewahrt jede bekannte Quelle, spätere Entdeckung, Korrektur und Meinungsverschiedenheit als separate Aufzeichnung auf. |
| Kann in einem Austausch seine eigene Antwort schreiben, suchen, planen und beurteilen. | Ermöglicht das Speichern, Suchen, Analysieren, Schreiben, Überprüfen und Genehmigen einzelner Teile mit eingeschränkter Berechtigung. |
| Steuert das Modell, Serviceregeln, Nutzungsbeschränkungen und Produktänderungen. | Belässt die bleibende Aufzeichnung unter der Kontrolle der Person. |
| Wird für Fehlversuche und Nachbesserungen sowie nützliche Arbeiten vergütet. | Behält Fehler und Korrekturen bei, sodass ihre Lektionen nicht erneut gekauft werden müssen. |

Robot Brain kann ein lokales oder Online-Sprachmodell aufrufen. Das macht es nicht zu einem Modell-Proxy. Es kann frühere Arbeiten bewahren, durchsuchen, vergleichen, organisieren und neu erstellen, ohne das Modell aufzurufen, das an der ursprünglichen Konversation teilgenommen hat. Wenn ein Modell nützlich ist, ist die Anfrage ein Schritt in einem größeren Prozess, der unabhängig von diesem Modell existiert.

## Warum das gebaut wurde

Die am stärksten bezahlten Allzweckmodelle, die während der Entwicklung verfügbar waren, waren fähige, aber unzuverlässige Verwalter langer Arbeit.

Zu den aufgezeichneten Fehlern gehörten verlorene Anweisungen, fehlende Beweise, erfundene Verbindungen, vorzeitige Fertigstellungsansprüche, unerwünschte Änderungen und Schäden an Arbeitsdateien. Die Behebung dieser Fehler erforderte mehr Anfragen, mehr Tests, mehr bezahlte Zuschüsse und mehr Zeit und Energie der Person. Die Dienste erstatteten nicht automatisch den für unbrauchbare Arbeiten aufgewendeten Verbrauch oder den für die Reparatur erforderlichen Austausch.

Das Problem war größer als jede einzelne schlechte Antwort. Ein temporärer Textgenerator wurde gebeten, als Gedächtnis, Historiker, Forscher, Autor, Prüfer und endgültiger Richter zu fungieren. Durch einen Modellwechsel änderte sich an dieser Regelung nichts.

Robot Brain wurde auf einer anderen Grundlage aufgebaut: Behalten Sie zuerst die menschlichen Aufzeichnungen bei, lassen Sie mehrere austauschbare Teile dazu beitragen und verlangen Sie Beweise außerhalb des erzeugenden Modells, bevor wichtige Arbeiten angenommen werden.

## Was ein trainiertes Model nicht halten kann

Ein großes Sprachmodell lernt Muster aus riesigen Sammlungen menschlicher Arbeit. Diese Muster machen das Modell nützlich, aber das Modell ist keine Bibliothek der vollständigen Werke, die es geprägt haben.

Innerhalb des Modells wird der Einfluss von Büchern, Artikeln, Gesprächen, Übersetzungen, Communities, Labels und menschlichem Feedback miteinander vermischt. Das Modell kann in der Regel nicht zeigen, welche Quellen einen bestimmten Satz geprägt haben. Es kann nicht den Zweck, das Publikum, die Beweise, Meinungsverschiedenheiten, späteren Korrekturen oder fehlenden Standpunkte jedes Autors wiederherstellen.

Das ist ein Bedeutungsverlust, selbst wenn das Originalwerk noch an anderer Stelle existiert. Das Modell behält einen gewissen Nutzen aus der Arbeit, verzichtet jedoch auf den zuverlässigen Weg zurück zu seiner menschlichen Umgebung.

Das gleiche Problem tritt bei normalem Gebrauch auf. Eine endgültige Antwort kann erhalten bleiben, nachdem das Gespräch, das ihr Bedeutung gab, gekürzt wurde. Die Schlussfolgerung bleibt bestehen, aber die gescheiterten Versuche, die Unsicherheit und die Gründe dafür verschwinden aus der Arbeitsansicht des Modells.

Dieses Projekt löst dieses Problem nicht, indem es ein anderes Modell für das Leben einer Person trainiert. Die persönliche Geschichte bleibt lesbar und nachvollziehbar, anstatt in ein anderes trainiertes Modell eingeblendet zu werden. Modelle arbeiten mit ausgewählten Datensätzen; sie werden nicht zu den Aufzeichnungen.

## Was jeder Teil tut

Die Arbeitssoftware trennt Aufgaben, die ein Chat-Dienst oft wie eine einzige Aktivität aussehen lässt:

1. **Der Quellenverwalter speichert, was passiert ist.** Er behält die Konversation, das Dokument, das Bild oder anderes Material bei, ohne es durch eine Zusammenfassung zu ersetzen.
2. **Durchsuchbare Kopien erleichtern das Auffinden der Quelle.** Kopierter Text, Beschreibungen und Indizes verweisen auf die unveränderte Quelle und können neu erstellt werden.
3. **Konzentrierte Leser vor Ort untersuchen spezifische Merkmale.** Separate Methoden befassen sich mit Sprache, Aussagen, Beziehungen, Argumentation, Zeit, menschlicher Erfahrung und Werten. Jeder berichtet nur über seine eigenen Erkenntnisse und die dahinter stehenden Passagen.
4. **Durch die Verlaufsaufzeichnung bleiben Änderungen sichtbar.** Neue Erkenntnisse, Korrekturen, Meinungsverschiedenheiten, Fehlversuche und offene Fragen werden hinzugefügt, ohne frühere Ereignisse neu zu schreiben.
5. **Der Request Builder sammelt, was ein Job benötigt.** Er wählt relevante Quellen und Erkenntnisse aus und zeichnet auf, was einbezogen oder weggelassen wurde.
6. **Ein Sprachmodell bietet möglicherweise begrenzte Hilfe.** Ein lokales Modell kann umfassende Hintergrundinformationen liefern. Ein Online-Modell kann bei schwierigen Recherchen oder beim Schreiben hilfreich sein. Jede Antwort bleibt ein veralteter Beitrag, der überprüft, abgelehnt oder ersetzt werden kann.
7. **Getrennte Prüfungen vergleichen das Ergebnis mit der Anfrage und den Beweisen.** Das Modell, das eine Antwort geschrieben hat, kann seine eigene Arbeit nicht für akzeptiert erklären.
8. **Ein Bildschirm ermöglicht es einer Person, die Software zu verwenden.** Das enthalteneLibreChatFork ist ein solcher Bildschirm. Durch den Austausch werden weder die Schallplatten noch die anderen funktionierenden Teile ersetzt.

Kein einzelner Teil wird als allwissender Assistent dargestellt. Ihre begrenzten Aufgaben machen jedes Teil austauschbar.

## Ein abgeschlossenes Gespräch wieder nutzbar machen

Ein abgeschlossenes Gespräch enthält die Anfrage der Person, die tatsächlichen Antworten des Sprachmodells, die versuchten Arbeiten, die Fehler, die Korrekturen und den Punkt, an dem der Austausch endete. Diese Nachrichten bewahren den Beitrag des ursprünglichen Modells, ohne dass sich das Modell später selbst erklären muss.

Konzentrierte Leser vor Ort beleuchten den gespeicherten Austausch aus mehreren Blickwinkeln. Sie können detaillierte Muster und Beziehungen finden, ohne sich auf umfassendes Weltwissen verlassen zu müssen. Ihre einzelnen Erkenntnisse bleiben mit genauen Teilen des Gesprächs verbunden.

Diese Erkenntnisse erfordern möglicherweise noch normales Hintergrundwissen, bevor sie eine klare Darstellung ergeben. Für diesen begrenzten Schritt ein kleinerQwenModell läuft lokal durchvLLM. Es fügt eine datierte Übersicht hinzu, die dabei hilft, die detaillierten Ergebnisse zu verknüpfen und zu erklären, was der Austausch erreicht hat.

Qwenstellt die verborgenen Gedanken oder den Trainingsverlauf des Online-Modells nicht wieder her. Es liefert umfassendes Hintergrundwissen, das nicht nur für das Originalmodell gilt. Der nützliche Beitrag des ursprünglichen Modells ist bereits in den von ihm hervorgebrachten Worten erhalten.

DerQwenDie Übersicht wird neben der Quelle und früheren Erkenntnissen gespeichert. Es kann korrigiert oder ersetzt werden. Das ursprüngliche Gespräch und die detaillierte lokale Analyse bleiben unverändert.

## Was funktioniert jetzt?

Die aktuelle Implementierung kann eine abgeschlossene Konversation bewahren, sie mit separaten lokalen Methoden untersuchen, eine lokale Allgemeinwissenslesung hinzufügen und jeden beibehaltenen Beitrag in einem Datensatz sammeln, der später neu erstellt werden kann.

Es kann auch eine begrenzte Anfrage für ein Online-Modell vorbereiten, wenn externe Hilfe hilfreich ist. Dieser Dienst erhält nur das ausgewählte Material. Die Antwort wird an den lokalen Datensatz zurückgegeben, wo Kontrollen und menschliche Zustimmung: nicht das Modell: darüber entscheiden, was aufbewahrt wird.

Dies ist die zentrale Errungenschaft: Arbeit, die einst von einer vorübergehenden Konversation abhing, kann auch dann nützlich bleiben, wenn der Chat-Bildschirm, das Modell und der Anbieter verschwunden sind.

## Lesen Sie die vollständige Erklärung

- [Warum große Sprachmodelle nicht die ganze Geschichte bewahren können](01-Why-Large-Language-Models-Cannot-Preserve-the-Full-Story.md)
- [Was jedes Teil tut: und was kein Modell kontrolliert](02-A-Lasting-Record-Outside-the-Model.md)
- [Behalten Sie die Korrektur bei, ohne den Fehler zu löschen](03-How-Knowledge-Changes-Without-Erasing-History.md)
- [Folgen Sie einer Behauptung zurück zu den Beweisen](04-How-Every-Claim-Can-Be-Checked.md)
- [Erstellen Sie das Dokument, bevor Sie die Prosa schreiben](05-How-Evidence-Becomes-a-Finished-Document.md)
- [Erklären Sie verschiedenen Lesern dieselbe Wahrheit](06-One-Meaning-Different-Readers.md)
- [Behalten Sie den privaten Verlauf unter der Kontrolle der Person](07-Privacy-and-Control-Stay-With-People.md)
- [Was die aktuelle Implementierung bewirkt](08-What-Works-Today.md)
- [Warum das Design aus vielen Bereichen schöpft](09-How-Research-Strengthens-the-System.md)
- [Helfen Sie ohne die Herausgabe privater Unterlagen](11-Contribute-Without-Giving-Up-Control.md)
- [In diesen Dokumenten verwendete Wörter](12-A-Short-Guide-to-Key-Terms.md)
- [Folgen Sie einer Aufforderung durch die Arbeitsteile](13-The-Parts-Running-Today.md)
- [Verwenden Sie ein Sprachmodell für den Job, nicht als Gedächtnis](15-Why-a-Language-Model-Is-a-Replaceable-Tool.md)
- [Bei kostenpflichtigen Sprachmodelldiensten beobachtete Fehler: und die Sicherheitsmaßnahmen, zu denen sie führten](16-What-Commercial-Language-Model-Services-Got-Wrong.md)
- [Lektionen, die das Design veränderten](17-How-Language-Models-Lose-Meaning-and-How-to-Preserve-It.md)
- [Hinweise zur öffentlichen Nutzung, zur Kreditwürdigkeit und zum Datenschutz](18-Use-Attribution-and-Limits.md)
- [Wie aus einem abgeschlossenen Gespräch bleibendes Wissen wird](19-What-the-System-Accomplishes.md)
- [Was kommt als nächstes?](20-Where-the-System-Goes-Next.md)

## Credits, Quellen und Rechte

- [Was hat diese Arbeit geprägt?](10-What-Helped-Shape-This-Work.md)
- [Forschung hinter dem Design](14-Sources-Behind-the-Design.md)
- [Quellen, Lizenzen und Veröffentlichungsprüfungen](../../SOURCES-LICENSES-AND-PRIVACY.md)

## Lizenz

Die Originaltexte, Diagramme und Illustrationen des Projekts sind unter der Website der Organisation verfügbar[Creative Commons Attribution 4.0 Internationale Lizenz](../../LICENSE.md), es sei denn, in einem Dokument sind andere Bedingungen angegeben. Von anderen erstelltes Material behält seine eigenen Rechte und Bedingungen.

## Unabhängigkeit und Privatsphäre

Dies ist ein unabhängiges persönliches Projekt, das auf persönlicher Zeit, Ausrüstung, Konten und kostenpflichtigen Diensten basiert. Kein Arbeitgeber beteiligte sich daran. Die Erwähnung einer Person, eines Arbeitgebers, einer Institution, eines Modellanbieters, einer Forschungsgruppe, einer gemeinsamen Regel oder eines externen Projekts bedeutet keine Teilnahme, Genehmigung, Partnerschaft oder Befürwortung.

Von der öffentlichen Veröffentlichung ausgeschlossen sind private Aufzeichnungen, Identifikationsdaten, Passwörter, private Verbindungsinformationen, Arbeitgeberinformationen und Anweisungen zum Erreichen privater Dienste. Beschreibungen von Modellfehlern beschränken sich auf aufgezeichnetes Verhalten und seine Auswirkungen. Sie behaupten nicht, dass es sich dabei um unbekannte Ursachen oder Motive handelt. Bei den Unterlagen handelt es sich weder um eine professionelle Beratung noch um ein Ergebnisversprechen.

![Ein Weg vom vom Anbieter kontrollierten Speicher hin zu Datensätzen, die bei den Personen verbleiben, die sie betreffen.](../../illustrations/open-door-human-future.png)
