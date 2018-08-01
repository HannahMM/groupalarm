+++
title = "Laufende Alarme"
weight = 1
+++



### Alarm-Feedback 


Sobald ein Alarm ausgelöst wird, erfolgt ein Wechsel der Maske, d.h. der Alarm wird in der Maske **„Alarm-Feedback“** dargestellt. Hier erhalten Sie in Echtzeit 
einen Überblick über Alarmverlauf und Rückmeldungen Ihrer alarmierten Teilnehmer. 

![](/img/status_alarm_status_laufende_alarme.png?width=1200px&classes=shadow)

Mit der Schaltfläche „Alarm schließen“ <img src="/img/status_alarm_status_laufende_alarme_alarm_schliessen.png" alt="end" style='vertical-align:middle;display:inline;margin:0px 5px; '>
können Sie den Alarm beenden.



#### Zusammenfassung Alarm

Im oberen Teil des Feedback-Menüs erhalten Sie eine Zusammenfassung des Alarms.

![](/img/status_alarm_status_laufende_alarme_zusammenfassung.png?classes=shadow&width=1200px)

 - Auslösezeitpunkt und Dauer des Alarms
 
 - Alarmtext und Statusbalken der Quittierungen
 - Ampel: Gibt Aufschluss darüber, ob die vordefinierte Grenze erfolgreicher Alarmierungen erreicht wurde. Bei **Rot** wurde noch keine definierte Grenze erreicht. **Gelb** bedeutet, eine vordefinierte Anzahl Teilnehmer hat
 den Alarm bereits positiv quittiert. **Grün** bedeutet, die in der Registry vordefinierte Anzahl an nötigen positiven Rückmeldungen ist erreicht und Sie können den Alarm beenden. 
 - Übersicht Rückmeldungen <img src="/img/status_alarm_status_laufende_alarme_zusammenfassung_rueckmeldungen.png" alt="feedback" style='vertical-align:middle;display:inline;margin:0px 5px; '>
 
 	- **Ja**: Positive Rückmeldung
	- **Nein**: Negative Rückmeldung
	- **Ungültig**: Rückmeldung mit ungültiger Syntax (mehr Informationen im Abschnitt [„Quittierung“](#quittierung))
	- **Versendet**
	- **Sendefehler**
    - **Nicht quittiert**: Noch keine Rückmeldung
	- **Nicht erreicht**
 
#### Übersicht Teilnehmer

Im unteren Teil des Feedback-Menüs werden die zu alarmierenden Teilnehmer und ihre jeweiligen Status und Alarmmittel aufgelistet. Wählen Sie die Option „Gruppenansicht“ aus, um die alarmierten Einheiten anzuzeigen.

![](/img/status_alarm_status_laufende_alarme_teilnehmer.png?classes=shadow&width=1200px)

Mit der <img src="/img/statussymbol.png" alt="status" style='vertical-align:middle;display:inline;margin:0px 5px; '> Schaltfläche
kann die Liste nach Status der Teilnehmer gefiltert werden, um beispielsweise nur positive Rückmeldungen anzuzeigen. 
![](/img/status_alarm_status_laufende_alarme_status.png?classes=shadow)

 
 Die Spalte **Zeit** gibt Auskunft über den Alarmierungshergang der einzelnen Mittel: 
 <img src="/img/status_alarm_status_laufende_alarme_zeitstempel.png" alt="feedback" style='vertical-align:middle;display:inline;margin:0px 5px; '>
 
 - **z1**: Zeitpunkt der Auslösung
 - **z2**: 
	- für SMS = Eingang der Zustellungsbestätigung
	- für Pager/Mail = Eingang der Übermittlungsbestätigung an Swissphone/Mail-Server
	- für Anrufe = Start der Verbindung bzw. Zeitpunkt des Fehlers
	- für Fax = Versand an den Faxserver
 - **z3**: 
	- für SMS/Mail = Quittierungseingang
	- für Anrufe = Ende der Verbindung
	- für Fax = Versandbericht vom Faxserver
 





### Quittierung

#### Anruf

Bei Alarmierung per Anruf liest eine Ansagestimme den Alarmtext vor und gibt Anweisungen zur korrekten Quittierung („Drücken Sie 1…drücken Sie 2…drücken Sie 3…“). Diese 
erfolgt per Tastenfeld.

#### E-Mail

Bei Alarmierung per E-Mail können Sie entweder eine Antwort E-Mail schicken oder dem Link in der Mail folgen und dort quittieren. 
Folgen Sie dazu den Anleitungen in der Alarmierungsmail.

![](/img/status_alarm_status_laufende_alarme_quittung_email2.png?classes=shadow)

#### SMS

Rückmeldungen per SMS müssen einer bestimmten Syntax entsprechen. Rückmeldungen müssen mit einem der folgenden
Schlüsselwörter beginnen:

{{% panel theme="default" %}}**"Ja"** oder **"Nein"**, **"OK"** oder **"NOK"**, **"Yes"** oder **"No"**, **"Oui"** oder **"Non"**,  **"Si"** oder **"No"**.{{% /panel %}}

Zusätzlicher Text **muss** mit einem Leerzeichen vom Schlüsselwort abgetrennt sein!  

 
Beispiele für gültige Antworten:  
 
| Gültig                 | Ungültig                |
|------------------------|-------------------------|
| JA                     | NEIN                    |
| Ja ich komme in 20 min | nein ich bin verhindert |
| ja bin dabei           | nein geht nicht         |
| OK                     | NOK                     |
| ok ich komme           | nok ich komme nicht     |


![](/img/status_alarm_status_laufende_alarme_quittung_sms.png?classes=shadow)

Beispiele für ungültige Antworten:

-  Ist OK ich komme (Antwort beginnt nicht mit Schlüsselwort)

- JaSofort (Kein Leerzeichen nach Schlüsselwort)




Kann GroupAlarm die Antworten wegen einer falschen Syntax nicht
auswerten, so erhält der Alarmempfänger den Status „ungültig“ und
die komplette Antwort-SMS wird in der Spalte Resultat
angezeigt. ![](/img/status_alarm_status_laufende_alarme_quittung_unklar.png?classes=shadow)

Der Auslöser/Disponent kann aufgrund des Textes das „Resultat“ manuell
auf „Ja“ oder „Nein“ setzten, indem er das grüne Häkchen <img src="/img/status_alarm_status_laufende_alarme_quittung_haken.png" alt="schluessel" style='vertical-align:middle;display:inline;margin:0px 5px; '>
oder das rote Kreuzchen <img src="/img/status_alarm_status_laufende_alarme_quittung_kreuz.png" alt="schluessel" style='vertical-align:middle;display:inline;margin:0px 5px; '>
wählt. Setzt er den Teilnehmer beispielsweise manuell auf „Ja“, wird er
in GroupAlarm folgendermaßen
dargestellt. ![](/img/status_alarm_status_laufende_alarme_quittung_unklar2.png?classes=shadow)
Der ursprüngliche Text im Resultat wird mit der Information zum
manuellen Statuswechsel überschrieben, im Protokoll taucht aber lediglich der letzte gesetzte Status auf, NICHT jedoch die Historie der Statussetzung.



