> Deutsch: Maschinell unterstützte Übersetzung der maßgeblichen englischen Quelle. Korrekturen in der Muttersprache sind willkommen. [Englisch](../../16-What-Commercial-Language-Model-Services-Got-Wrong.md) | [Alle Sprachen](../README.md)

# Bei kostenpflichtigen Sprachmodelldiensten beobachtete Fehler: und die Sicherheitsmaßnahmen, zu denen sie führten

![Aufgezeichnete Fehler wurden zu Tests und Sicherheitsvorkehrungen für spätere Arbeiten.](../../illustrations/failures-became-blueprint.png)

## Dies waren die am stärksten bezahlten Optionen, die verfügbar waren

Dieses Projekt nutzte kostenpflichtige Online-Sprachmodelldienste für Recherche, Codierung, Schreiben und Überprüfung. Die Konten umfassten die stärksten allgemeinen Modelle, die die Dienste zu dieser Zeit anboten. Die Wahl einer leistungsfähigeren kostenpflichtigen Option konnte die unten aufgeführten Fehler nicht verhindern.

Jedes Beispiel stammt aus einer datierten Projektaufzeichnung. Die Tabellen beschreiben, was ein kostenpflichtiges Modell tat, was als nächstes geschah und welche Schutzmaßnahmen außerhalb des Modells eingebaut wurden. Hierbei handelt es sich um Fehler, die bei kommerziellen Diensten beobachtet werden, nicht um Fehler, die dadurch verursacht werdenRobot Brain. Die rechte Spalte beschreibt, wie dieses Projekt reagiert.

Die Aufzeichnungen lassen keine Rückschlüsse auf das Motiv eines Anbieters zu und behaupten auch nicht, eine nicht offengelegte technische Ursache zu kennen. Anbieternamen werden weggelassen, da die Schutzmaßnahmen auf wiederholtes Verhalten und nicht auf ein Unternehmen reagieren.

## Was die Ausfälle kosten

Der Preis beschränkte sich nicht nur auf eine falsche Antwort.

- **Zeit ging verloren.** Die als abgeschlossen bezeichneten Arbeiten mussten von der Person überprüft, erneut erklärt, repariert und getestet werden. Einige Ausfälle dauerten Stunden.
- **Bezahltes Nutzungskontingent, manchmal auch Kontingent genannt, ging verloren.** Für Wiederholungsversuche, wiederholten Kontext, Ersatzentwürfe und Korrekturen wurde dasselbe begrenzte Kontingent wie für nützliche Arbeit verwendet. In diesen aufgezeichneten Sitzungen wurde kein automatisches Kontingent für nicht verwendbare Ausgaben oder Korrekturaustausche zurückgegeben.
- **Der Service wurde in beide Richtungen bezahlt.** Die Abonnement- oder Nutzungsgebühr blieb bestehen, während die Person auch die Zeit und Mühe auf sich nahm, die erforderlich war, um den Fehler zu finden und zu beheben.
- **Funktionierende Dinge waren kaputt.** Unvollständige Bearbeitungen führten dazu, dass ein Live-Dienst nicht ausgeführt werden konnte. Es wurden Änderungen an der falschen Kopie einer Einstellung vorgenommen. Die Ausgabe wurde von ihrem erforderlichen Speicherort verschoben, anstatt den Zugriff zu reparieren.
- **Die historischen Aufzeichnungen wurden gefährdet.** Der generierte Text wurde mit menschlichem Material vermischt und Aufzeichnungen wurden geändert oder entfernt, bevor die Person diese Änderung genehmigte.
- **Aufmerksamkeit wurde ohne Erlaubnis in Anspruch genommen.** Wichtige Antworten wurden in wiederholten Erklärungen vergraben, sodass die Person gezwungen war, alles zu lesen, um den kleinen Teil wiederzugewinnen, auf den es ankam.

Deshalb leben wichtige Regeln hier nicht nur in einer Aufforderung.Robot Brain prüft, was tatsächlich passiert ist und kann einen Beitrag auch dann ablehnen, wenn das Modell sagt, dass er erfolgreich war.

## Kontinuität und Wissensdefizite

| Beobachteter Fehler | Was ist passiert | Schutz außerhalb des Sprachmodells hinzugefügt |
|---|---|---|
| Klingt kontinuierlich, nachdem die Geschichte verloren gegangen ist | Ein Dienst hat das frühere Gespräch gekürzt, um es an seine Arbeitsgrenze anzupassen. Einige Schlussfolgerungen wurden beibehalten, Quellen, Korrekturen, abgelehnte Alternativen, Ereignisreihenfolge und Benutzerabsichten gingen jedoch verloren, während der Klang weiterhin flüssig blieb. | Halten Sie das gesamte Gespräch in Ordnung. Speichern Sie die gekürzte Version separat und notieren Sie, was darin enthalten, weggelassen und möglicherweise verloren gegangen ist. |
| Eine neue Antwort ersetzt den aufgezeichneten Verlauf | Eine neuere Sprachmodell-Antwort könnte scheinbar alles davor ersetzen, auch wenn sie auf anderen Informationen, Regeln und Entscheidungen über die Welt beruht. | Speichern Sie jede Entdeckung mit ihrer Zeit. Lassen Sie niemals zu, dass die neueste Antwort früher akzeptierte, abgelehnte oder unsichere Ergebnisse überschreibt. |
| Das Erlernen von Sprachmodellen zerstörte den Weg zurück zur Quelle | Das Sprachmodell behielt nützliche Muster bei und trennte sie gleichzeitig vom Ersteller, Zweck, Publikum, Beweisen, Meinungsverschiedenheiten und der späteren Geschichte der Quelle. | Behalten Sie unveränderte Quellen und ihre bekannten Verbindungen außerhalb jedes Sprachmodells. Behandeln Sie nicht unterstütztes Wissen über das Sprachmodell als Vorschlag, es sei denn, separate Beweise stellen eine Verbindung zu einer Quelle her. |
| Verlust der Umstände, aus denen das Sprachmodell gelernt hat | Das Sprachmodell blieb nützlich, obwohl seine Antwort nicht alle Menschen, Quellen, Zwecke, Meinungsverschiedenheiten, Berechtigungen und Kulturen offenlegen konnte, die es geprägt haben. | Behalten Sie bekannte Umstände und Quellenangaben bei, die außerhalb des Sprachmodells gespeichert sind. Behandeln Sie nicht unterstütztes erlerntes Wissen als Vorschlag eines Sprachmodells und nicht als eine an eine Quelle gebundene Tatsache. |
| Versteckte Voreingenommenheit gegenüber dem, was ausgewählt wurde | Was das Sprachmodell erkennen konnte, spiegelte die Sprachen, Quellen, Archive, Labels, menschlichen Prüfer und Ziele wider, die zu seiner Erstellung verwendet wurden. Die Antwort offenbarte nicht alle diese Einflüsse. | Notieren Sie die bekannten Grenzen des Sprachmodells und was über das Material bekannt ist, aus dem es gelernt hat. Vergleichen Sie mehrere begrenzte Tools und betrachten Sie eine einfache Antwort nicht als vollständige Ansicht. |
| Gemeinsame Geschichte wird stillschweigend neu geschrieben | Mehrere Mitarbeiter, die einen Hauptverlauf bearbeiten, könnten inkompatible Entscheidungen verlieren oder kombinieren. | Fügen Sie einen neuen Quellverlauf hinzu, ohne frühere Einträge zu überschreiben. Erstellen Sie aktuelle Ansichten aus diesem Verlauf, ohne den Ereignisdatensatz neu zu schreiben. |
| Unterschiedliche Zeiten und Zustände werden als gleich behandelt | Aktuelle, historische, experimentelle, separat getestete und ersetzte Aussagen wurden so dargestellt, als hätten sie den gleichen Stellenwert. | Speichern Sie den Zeitpunkt und den aktuellen Stand aller wichtigen Schadensfälle und Anlagenteile. |
| Entfernen eines Teils, ohne zu prüfen, wer es verwendet | Ein Teil, der im aktuellen Prozess nicht verwendet wurde, wurde als veraltet behandelt, ohne dass spätere Arbeiten, die davon abhingen, überprüft wurden. | Erfassen Sie die Aufgaben, Benutzer, den aktuellen Zustand und die Ersetzungen jedes Teils. Überprüfen Sie diese Benutzer, bevor Sie sie entfernen. |
| Einmischen von generiertem Text in den Datensatz einer Person | Die auf einem Sprachmodell basierende schriftliche Erklärung wurde neben menschlichem Material in einer Form gespeichert, die später mit den eigenen Worten oder Überzeugungen der Person verwechselt werden konnte. | Halten Sie wörtliches menschliches Material, Transkripte und durch Sprachmodelle generierte Interpretationen klar getrennt. Lassen Sie niemals zu, dass generierter Text stillschweigend Teil der menschlichen Aufzeichnung wird. |
| Verlauf wird während der Bereinigung entfernt | Frühere Datensätze wurden geändert oder entfernt, weil ein Sprachmodell sie als falsch oder unordentlich beurteilte. Dadurch wurden die Beweise zerstört, die nötig waren, um zu verstehen, was passiert ist und warum es sich verändert hat. | Bewahren Sie die historischen Aufzeichnungen auf. Fügen Sie eine Korrektur oder eine spätere Erkenntnis hinzu, anstatt die Vergangenheit stillschweigend neu zu schreiben. |

## Befehls- und Umfangsfehler

| Beobachteter Fehler | Was ist passiert | Schutz außerhalb des Sprachmodells hinzugefügt |
|---|---|---|
| Regeln gehen während der Aufgabe verloren | Ein Sprachmodell könnte eine Regel in derselben Aufgabe lesen, neu formulieren und dann verletzen. | Wandeln Sie Regeln, deren Ausfall hohe Kosten verursacht, in erforderliche Bedingungen und Prüfungen um, die die Arbeit ablehnen können. |
| Die Anspruchsregeln wurden ohne Beweise befolgt | Das Model behauptete, Anweisungen oder Dokumente seien befolgt worden, obwohl das Ergebnis etwas anderes zeigte. | Verlangen Sie den Nachweis, dass die entsprechende Prüfung durchgeführt und bestanden wurde. Ein Sprachmodell, das besagt, dass es gelungen ist, ist kein Beweis. |
| Ersetzen der angeforderten Aufgabe | Eine spezifische Anfrage wurde durch den bevorzugten Rahmen des Sprachmodells ersetzt, wodurch der Benutzer gezwungen wurde, erneut für das Originalwerk zu argumentieren. | Halten Sie die geforderten Grenzwerte ein. Lehnen Sie eine unaufgeforderte Änderung des Rahmens ab, es sei denn, ein tatsächlicher Sicherheits- oder Berechtigungskonflikt erfordert dies. |
| Ohne Erlaubnis zusätzliche Arbeit leisten | Verwandte Arbeiten wurden durchgeführt, weil sie nützlich erschienen, obwohl sie nicht angefordert wurden. | Verknüpfen Sie jede Aktion mit der deklarierten Aufgabe. Behandeln Sie jede Erweiterung als eine neue Entscheidung. |
| Ändern des gewünschten Ziels | Wenn der angeforderte Standort nicht erreichbar war, wurde das Ergebnis an einen einfacheren Ort verschoben, anstatt den Zugang zu reparieren. | Behalten Sie das gewählte Ziel bei. Eine Änderung erfordert die Entscheidung des Benutzers. |
| Über die angeforderte Korrektur hinausgehen | Feedback wurde als eine Anweisung zur kontinuierlichen Änderung der Arbeit betrachtet, statt als eine präzise zu erreichende Korrektur. | Notieren Sie den angeforderten Endzustand und vergleichen Sie das Ergebnis nach der Änderung damit. |
| Neues Material an die falsche Stelle zwingen | Einem bestehenden Dokument wurde neues Material hinzugefügt, ohne es in die Struktur einzupassen, was beides beschädigte. | Planen Sie das Gesamtergebnis, verfolgen Sie, was sich durch den Zusatz ändert, und erstellen Sie ein separates Dokument, wenn es nicht dazugehört. |
| Ausgabe verschieben statt Zugriff festlegen | Wenn der angeforderte Ordner nicht erreichbar war, verschob ein Assistent das Ergebnis an einen einfacheren Ort. Dadurch wurden die Aufzeichnungen der Person aufgeteilt und die Ablage, Berechtigungen und Gewohnheiten verworfen, die bereits um den ursprünglichen Standort herum aufgebaut waren. | Reparieren Sie den Zugang zum gewählten Standort. Die Änderung des Ziels bleibt die Entscheidung der Person. |

## Beweis- und Abschlussfehler

| Beobachteter Fehler | Was ist passiert | Schutz außerhalb des Sprachmodells hinzugefügt |
|---|---|---|
| Erklären Sie den Abschluss zu früh | Das Bearbeiten oder Starten eines Teils wurde als abgeschlossen gemeldet, bevor seine Wirkung getestet wurde. | Für den Abschluss sind Nachweise für das angeforderte Ergebnis erforderlich, keine generierte Statuserklärung. |
| Eine Diagnose akzeptieren, ohne sie zu überprüfen | Eine Fehlermeldung wurde akzeptiert, ohne zu prüfen, woher und wann sie kam und ob sie die aktuelle Aufgabe beschrieb. | Behalten Sie Beweise im Zusammenhang damit, wo, wann und unter welchen Umständen sie erstellt wurden. |
| Plausible Vermutung | Gründe und nächste Schritte wurden vorgeschlagen, weil sie vernünftig klangen, nicht weil Beweise darauf hinwiesen. | Unbekanntes bewahren. Trennen Sie das Beobachtete, eine mögliche Erklärung, den Test und die bestätigte Ursache. |
| Vorausgesetzt, die neueste Änderung war korrekt | Es wurde davon ausgegangen, dass die jüngsten schriftlichen Änderungen des Sprachmodells korrekt waren, während andere Teile zuerst vermutet wurden. | Überprüfen Sie die neueste Änderung und konkurrierende Erklärungen, bevor Sie die Ursache zuweisen. |
| Das Timing als Beweis für die Ursache betrachten | Der in der Nähe eines Fehlers aktive Teil wurde dafür verantwortlich gemacht, ohne dass normales Verhalten oder andere veränderte Bedingungen verglichen wurden. | Sorgen Sie dafür, dass das Problem erneut auftritt. Vergleichen Sie normale und veränderte Bedingungen, suchen Sie nach Gegenbeweisen und ermitteln Sie die Ursache. |
| Einen kleinen Test als Beweis für Live-Verhalten betrachten | Als Beweis dafür, dass das gesamte System im normalen Gebrauch funktioniert, wurde eine Nachbildung, ein vorbereitetes Beispiel oder ein kleiner Test vorgelegt. | Geben Sie genau an, was getestet wurde, und behaupten Sie nicht, dass das Ergebnis mehr beweist. |
| Testen mit den falschen Berechtigungen | Eine Prüfung wurde mit dem Entwicklerzugriff bestanden, obwohl das Live-Programm mit anderen Berechtigungen ausgeführt wurde. | Testen Sie mit demselben Konto und denselben Berechtigungen, die vom Live-Programm verwendet werden, oder lassen Sie das Ergebnis ungeprüft. |
| Reparieren Sie einen Fehler, bevor Sie ihn aufzeichnen | Ein Fehler wurde behoben, bevor er offengelegt wurde, wodurch die Aufzeichnung sauberer aussah als die Arbeit. | Behalten Sie den Fehler und die Korrektur in der richtigen Reihenfolge bei. Lassen Sie nicht zu, dass durch Reparaturen Beweise gelöscht werden. |
| Wiederholte Überarbeitung vor den Augen des Benutzers | Ein Ergebnis wurde vor den Augen des Benutzers wiederholt überarbeitet, da sich die Planung bis nach dem ersten Ergebnis verzögerte. | Wählen Sie das Material aus und planen Sie das gesamte Ergebnis, bevor Sie eine Überprüfung anfordern. Präsentieren Sie nach Möglichkeit einen begrenzten Entwurf. |
| Unterbrechung eines Live-Dienstes durch eine unvollständige Bearbeitung | Ein Sprachmodell hat nur einen Teil einer Arbeitsdatei geändert und ist dann weitergegangen. Der laufende Dienst konnte seine Aufgabe nicht abschließen. | Behandeln Sie eine Änderung als unvollendet, bis die gesamte Datei gültig ist und der eigentliche Dienst die beabsichtigte Aufgabe abschließt. |
| Ändern der falschen Kopie einer Einstellung | Ein Sprachmodell hat die Haupteinstellungsdatei bearbeitet, den Dienst neu gestartet, eine erfolgreiche Neustartantwort erhalten und den Erfolg gemeldet. Der Dienst verwendete eine andere generierte Kopie, sodass die alte Einstellung aktiv blieb. | Überprüfen Sie das sichtbare Ergebnis, nicht nur die Bearbeitungs- oder Neustartmeldung. Behalten Sie einen klaren Pfad von der Haupteinstellung zur Kopie bei, die ein Dienst tatsächlich verwendet. |
| Wiederholte Korrekturen, die das Problem nicht beheben konnten | Für ein Problem wurden vier Änderungen vorgenommen. Jeder bewies, dass Code ausgeführt wurde, aber keiner bewies, dass das ursprüngliche Problem behoben war. | Definieren Sie das Ergebnis, das vor der Bearbeitung geändert werden muss. Testen Sie das Ergebnis nach jeder Änderung direkt. |
| Überprüfung mit Zugriff, den der Live-Dienst nicht hatte | Ein Ordner funktionierte beim Testen über das Konto der Person, aber der Live-Dienst verwendete ein anderes Konto und konnte immer noch nicht darauf zugreifen. | Führen Sie die Prüfung unter den gleichen Bedingungen wie den Live-Dienst durch. |

## Fehler darüber, wer was sagen oder genehmigen darf

| Beobachteter Fehler | Was ist passiert | Schutz außerhalb des Sprachmodells hinzugefügt |
|---|---|---|
| Verschiedene Jobs werden gleich behandelt | Beobachter, Autoren, Prüfer, Personen, die die Arbeit unterbrechen können, und Freigabegenehmiger wurden gleich behandelt, da jeder das Ergebnis berührte. | Jede Komponente hat eine festgelegte Aufgabe und begrenzt die Entscheidungen, die sie treffen kann. Ein Autor kann keine Behauptung wahr machen. Ein Beobachter kann nicht veröffentlichen. |
| Ersatzwerte als real anzeigen | Auf den Bildschirmen wurden leere Messwerte oder plausible Ersatzwerte angezeigt, sodass die Installation vollständig aussah. | Zeigen Sie einen Messwert an und geben Sie an, woher er stammt, oder geben Sie deutlich an, dass er nicht verfügbar ist. |
| Durch das Aktualisieren einer Seite wurde der Platz des Benutzers zerstört | Eine Aktualisierung ersetzte eine ganze Seite und zerstörte den Fokus, die Auswahl, die Bildlaufposition oder das Kopieren. | Behandeln Sie den Bildschirm als menschlichen Arbeitsplatz. Aktualisieren Sie sich ändernde Werte, ohne den Platz des Benutzers zu zerstören. |
| Passwörter in ungeschütztem Text aufbewahren | Passwörter und Zugriffsschlüssel wurden in gewöhnlichen Dateien statt im geschützten Speicher abgelegt. | Bewahren Sie sie in einem geschützten Speicher auf und überprüfen Sie jede Datei vor der Veröffentlichung. |
| Meldet, dass ein Dienst gestoppt wurde, während er weiter ausgeführt wurde | Die Stoppanforderung wurde erfolgreich zurückgegeben, aber der Prozess arbeitete weiter. | Überprüfen Sie den Prozess und seine tatsächliche Wirkung nach einer Kontrollanfrage. Melden Sie die Anfrage nicht als Ergebnis. |

## Versagen der menschlichen Aufmerksamkeit

| Beobachteter Fehler | Was ist passiert | Schutz außerhalb des Sprachmodells hinzugefügt |
|---|---|---|
| Die Worte einer Person auffüllen | Eine kurze menschliche Aussage wurde mit generiertem Material erweitert, bis die ursprünglichen Worte kaum noch zu finden waren. | Behalten Sie die Originalaussage als Hauptdatensatz bei. Die generierte Interpretation bleibt separat und optional. |
| Zirkuläres Schreiben | Die Antwort wurde erklärt, neu formuliert, zusammengefasst und abgeschlossen, nachdem der nützliche Inhalt aufgebraucht war. | Stoppen Sie, wenn das angeforderte Ergebnis vollständig ist. Entfernen Sie wiederholte Schlussfolgerungen. |
| Die Antwort vergraben | Ein oder zwei nützliche Fakten wurden in Bildschirmen mit Material platziert, das der Benutzer nicht angefordert hatte. | Stellen Sie die kürzeste vollständige Antwort zuerst und machen Sie tiefergehendes Material optional. |
| Verschwende nicht geschenkte Aufmerksamkeit | Eine korrekte, aber unnötige Erklärung zwang den Leser dazu, Zeit damit zu verbringen, zu entscheiden, dass sie unnötig sei. | Zählen Sie Lektüre und Korrektur als tatsächliche Kosten. Lassen Sie den Leser optionale Tiefe einleiten. |
| Zu viel Betonung | Fast jeder Punkt war fett gedruckt, mit Überschriften versehen oder in einer Tabelle platziert, sodass echte Warnungen nicht mehr auffielen. | Betonen Sie nur die wenigen Unterscheidungen, die die Entscheidungs- oder Sicherheitslast tragen. |

## Fehler im Zusammenhang mit Kosten- und Anbieteranreizen

| Beobachteter Fehler | Was ist passiert | Schutz außerhalb des Sprachmodells hinzugefügt |
|---|---|---|
| Ein kostenpflichtiges großes Sprachmodell, das standardmäßig verwendet wird | Die Arbeit wurde über ein kostenpflichtiges Online-Modell gesendet, weil sie verfügbar war, selbst wenn ein einfacher fester Prozess, ein gespeichertes Ergebnis oder ein eingeschränktes Tool dies zuverlässiger erledigen konnte. | Messen Sie den vollen Wert und die Kosten des Auftrags. Wählen Sie die kleinste Kombination von Werkzeugen, deren Arbeit überprüft und gerechtfertigt werden kann. |
| Die Korrekturkosten sind aus den Gesamtbeträgen verschwunden | Wiederholungsversuche, wiederholter Kontext, Warten und menschliche Korrekturen wurden nach einem schlechten Ergebnis als kostenlos behandelt, obwohl sie eine bezahlte Aufwandsentschädigung in Anspruch nahmen und mehr Zeit und Energie der Person in Anspruch nahmen. | Erfassen Sie Wartezeiten, Wiederholungsversuche, Ablehnungen, wiederholte Servicenutzung und menschliche Aufmerksamkeit als Teil der tatsächlichen Kosten. |
| Für fehlgeschlagene Arbeiten wird kein Kontingent zurückgegeben | Unbrauchbare Leistungen und die zur Korrektur erforderlichen Umtausche wurden auf das bezahlte Kontingent angerechnet. Die Person erhielt keinen automatischen Ersatz für die verlorene Vergütung oder Zeit. | Erfassen Sie fehlgeschlagene und korrigierende Verwendung getrennt. Verwenden Sie gespeicherten Kontext und abgelehnte Ergebnisse erneut, damit derselbe Fehler nicht erneut erworben wird. |
| Nützlicher Fehler wurde verworfen | Eine abgelehnte Antwort verschwand, sodass spätere Arbeiten denselben Fehler wiederholten und erneut dafür bezahlten. | Halten Sie abgelehnte Ergebnisse und ihre Ablehnungsgründe außerhalb des anerkannten Wissens. Nutzen Sie die Lektion erneut, ohne die nicht unterstützte Behauptung zu akzeptieren. |
| Der gleiche Kontext musste erneut bereitgestellt werden | Wenn frühere Informationen aus der Arbeitsansicht des Sprachmodells verschwanden, musste die Person die Anfrage rekonstruieren und den bereits in einer kostenpflichtigen Sitzung bereitgestellten Verlauf erneut senden. | Halten Sie den dauerhaften Kontext außerhalb des Gottesdienstes. Erstellen Sie für jeden Auftrag ein begrenztes Paket und bewahren Sie die zurückgegebenen Arbeiten, Korrekturen und Ablehnungen zur späteren Verwendung auf. |

## Wie diese Serviceausfälle zum Entwurf dieses Projekts wurden

Das beobachtete Problem war nicht auf ein schwaches Modell beschränkt. Derselbe vorübergehende Assistent wurde gebeten, als Erinnerung, Historiker, Planer, Autor, Prüfer und Beurteiler seiner eigenen Arbeit zu fungieren. Selbst die bestbezahlten Models konnten eine einzelne Aufgabe erfolgreich bewältigen und dabei die menschliche Geschichte verlieren, die sie mit allem anderen verband.

Robot Brain gibt diese Jobs, um Teile zu trennen. Der Quellenverwalter bewahrt das Ereignis auf. Fokussierte lokale Leser untersuchen definierte Merkmale. Der Request Builder sammelt Beweise für einen Zweck. Ein Modell kann Hintergrundinformationen oder Formulierungen beisteuern. Unabhängige Kontrollen und menschliche Zustimmung entscheiden über die Akzeptanz.

Der Verlauf bleibt außerhalb des kostenpflichtigen Dienstes. Ein Modell kann bei einem gewählten Job helfen, aber es speichert nicht das Leben der Person und wird nicht zur einzigen Möglichkeit, bereits geleistete Arbeit zu nutzen.

Das lokale Modell hat die gleiche Grenze. Es wird nicht auf die Akten der Person trainiert. Es liest ausgewähltes Material, gibt einen datierten Vorschlag zurück und kann ersetzt werden. Die Worte, die Zeit, die Erfahrung, die Entscheidungen, Misserfolge und Korrekturen der Person sind der wertvolle Teil.
