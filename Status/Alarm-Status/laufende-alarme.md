+++
title = "Laufende Alarme"
weight = 1
+++



### Alarm-Feedback 


Sobald ein Alarm ausgelöst wird, erscheint er in der Maske **„Alarm-Feedback“**. Hier erhalten Sie in Echtzeit 
einen Überblick über Alarmverlauf und Rückmeldungen Ihrer Teilnehmer. 

![](/img/laufender_alarm.png?width=900px&classes=shadow)

Mit der Schaltfläche „Alarm schließen“ <img src="/img/alarm_schliessen.png" alt="end" style='vertical-align:middle;display:inline;margin:0px 5px; '>
wird der Alarm beendet.


#### Übersicht Alarm

Im oberen Teil des Feedback-Menüs erhalten Sie eine Zusammenfassung des Alarms.

![](/img/laufender_alarm_zusammenfassung.png?classes=shadow)

 - Auslösezeitpunkt und Dauer des Alarms, Alarmtext
 - Statusbalken der Quittierungen
 - Ampel: Gibt Aufschluss darüber, ob vordefinierte Grenze erfolgreicher Alarmierungen erreicht wurde. Orange bedeutet, eine vordefinierte Anzahl Teilnehmer hat
 den Alarm bereits positiv quittiert. Grün bedeutet, die 
 in der Registry vordefinierte Anzahl an nötigen positiven Rückmeldungen ist erreicht und Sie können den Alarm beenden. 
 - Übersicht Rückmeldungen <img src="/img/laufender_alarm_rueckmeldungen.png" alt="feedback" style='vertical-align:middle;display:inline;margin:0px 5px; '>
 
 	- **Ja**: Positive Rückmeldung
	- **Nein**: Negative Rückmeldung
	- **Ungültig**: Rückmeldung mit ungültigem Syntax (mehr Informationen im Abschnitt "Quittierung")
	- **Versendet**
	- **Sendefehler**
    - **Nicht quittiert**: Noch keine Rückmeldung
	- **Nicht erreicht**
 
#### Übersicht Teilnehmer

Im unteren Teil des Feedback-Menüs werden die zu alarmierenden Teilnehmer und ihre jeweiligen Status und Alarmmitteln aufgelistet. 

![](/img/laufender_alarm_teilnehmer.png?classes=shadow)

Mit der <img src="/img/statussymbol.png" alt="status" style='vertical-align:middle;display:inline;margin:0px 5px; '> Schaltfläche
kann die Liste nach Status der Teilnehmer gefiltert werden, um beispielsweise nur postitive Rückmeldungen anzuzeigen. 
![](/img/laufender_alarm_teilnehmer2.png?classes=shadow)

 
 Die Spalte Zeit gibt Auskunft über den Alarmierungshergang  der einzelnen Mittel 
 <img src="/img/laufender_alarm_zeitstempel.png" alt="feedback" style='vertical-align:middle;display:inline;margin:0px 5px; '>
 
 - **z1**: Zeitpunkt der Auslösung
 - **z2**: 
	- für SMS = Eingang der Zustellungsbestätigung
	- für Pager/Mail = Eingang der Übermittlingsbestätigung an Swissphone/Mail-Server
	- für Anrufe = Start der Verbindung bzw. Zeitpunkt des Fehlers
	- für Fax = Versand an den Faxserver
 - **z3**: 
	- für SMS/Mail = Quittierungseingang
	- für Anrufe = Ende der Verbindung
	- für Fax = Versandbericht vom Faxserver
 

Wählen Sie die Option „Gruppenansicht“ aus, um die alarmierten Einheiten anzuzeigen.



### Quittierung

Bei Alarmierung per Anruf liest einen Ansagestimme den Alarmtext vor und gibt Anweisungen zur korrekten Quittierung. Diese 
erfolgt per Tastenfeld.

Rückmeldungen per SMS müssen einem bestimmten Syntax entsprechen. Rückmeldungen müssen mit einem der folgenden
Schlüsselwörter beginnen:

{{% panel theme="default" %}}**"Ja"** oder **"Nein"**, **"OK"** oder **"NOK"**, **"Yes"** oder **"No"**, **"Oui"** oder **"Non"**,  **"Si"** oder **"No"**.{{% /panel %}}

 
 Zusätzlicher Text muss mit einem Leerzeichen vom Schlüsselwort abgetrennt sein!  

 
Beispiele für gültige Antworten:  
 
| Positiv                | Negativ                 |
|------------------------|-------------------------|
| JA                     | NEIN                    |
| Ja ich komme in 20 min | nein ich bin verhindert |
| ja bin dabei           | nein geht nicht         |
| OK                     | NOK                     |
| ok ich komme           | nok ich komme nicht     |

Beispiele für ungültige Antworten:

-  Ist OK ich komme (Antwort beginnt nicht mit Schlüsselwort)

- Ja, in 15 min (Abtrennung des Schlüsselwortes durch Komma)

Kann eAlarm emergency die Antworten wegen einer falschen Syntax nicht
auswerten, so erhält der Feedback-Empfänger den Status „ungültig“ und
die komplette Antwort-SMS wird in der Spalte Resultat
angezeigt. ![](/img/feedback_ungueltig_de.png?classes=shadow)

Der Feedback-Empfänger kann aufgrund des Textes das „Resultat“ manuell
auf „Ja“ oder „Nein“ setzten, indem er das grüne Häckchen <img src="/img/gutzeichengruenklien.png" alt="schluessel" style='vertical-align:middle;display:inline;margin:0px 5px; '>
oder das rote Kreuzchen <img src="/img/roteskreuzklein.png" alt="schluessel" style='vertical-align:middle;display:inline;margin:0px 5px; '>
wählt. Setzt er den Teilnehmer beispielsweise manuell auf „Ja“ wird er
in eAlarm emergency folgendermassen
dargestellt. ![](/img/status_manuel_gesetzt_de.png?classes=shadow)
Der ursprüngliche Text im Resultat wird mit der Information zum
manuellen Statuswechsel überschrieben.



