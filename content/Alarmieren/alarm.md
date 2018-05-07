+++
title = "Alarm erstellen"
weight = 1
+++


### Alarm erstellen 

Sobald Teilnehmer, Gruppen und Wurzeln ausgewählt und die Schaltfläche
**„Alarm“** <img src="/img/alarmieren_alarm.png" alt="alarm" style='vertical-align:middle;display:inline;margin:0px 5px; '>
geklickt wurde, öffnet sich die Maske „Alarm erstellen“.

![](/img/alarmieren_alarm_erstellen.png?classes=shadow&width=1000px)


Hier können Sie verschiedene Einstellung für Ihren Alarm vornehmen und anschließend mit der Schaltfläche 
![](/img/alarmieren_alarm_erstellen_ausloesen.png?classes=shadow) auslösen. Die Schaltfläche wird grau dargestellt solange noch 
nicht alle nötigen Einstellungen vorgenommen wurden.



Neben einer Alarmauslösung direkt aus dem Webbrowser unterstützt
**GroupAlarm pro** mehrere Wege der Fernauslösung. Ob Alarm per SMS,
Anruf und DTMF-Menü, Durchwahl und über einen Web-Link, die Auslösung
ist von nahezu allen Plattformen realisierbar. 



#### Allgemein 

![](/img/alarmieren_alarm_erstellen_allgemein.png?classes=shadow)

Legen Sie hier Alarmname und optional eine Beschreibung des Alarms fest. 
Ebenfalls ist hier Ersteller und Erstellzeitpunkt ersichtlich.



#### Einheiten 

![](/img/alarmieren_alarm_erstellen_einheiten.png?classes=shadow)

Unter **„Einheiten“** werden Ihnen die selektierten Teilnehmer und Einheiten angezeigt. Mit <img src="/img/loesch-icon.png" alt="del" style='vertical-align:middle;display:inline;margin:0px 5px; '>
können Sie Teilnehmer oder Gruppen direkt löschen, über *\[bearbeiten\]* gelangen Sie zurück in das Menü *Alarm erstellen* und können
weitere Teilnehmer und Gruppen hinzufügen.


<a name="text"></a>
#### Text 


![](/img/alarmieren_alarm_erstellen_text1.png?classes=shadow)

Bevor ein Alarm ausgelöst werden kann, muss ein Alarmtext gewählt werden. Folgende Möglichkeiten stehen zur Verfügung:

 - **Definierte Texte:**  Wählen Sie einen vordefinierten Text aus. Diese müssen zuvor im Register **„Mutieren“** im Menü [„Texte“](/mutieren/mutation/texte/)
 erstellt werden. Durch einen Klick auf *\[QuickEdit\]* 
 können Sie die Vorlage direkt anpassen.
 
 - **Freitext**: Verfassen Sie einen neuen Alarmtext. Mit der Schaltfläche „Datei auswählen“ können Sie der Nachricht eine Datei anhängen. 
 
 ![](/img/alarmieren_alarm_erstellen_text2.png?classes=shadow)
 
 - **Live-Sprachaufnahme**: Option, eine eigene Sprachnachricht aufzunehmen. Geben Sie hierzu eine gültige Rufnummer ein und klicken Sie auf „Alarmansage aufnehmen“. Sie werden nun auf dieser Nummer angerufen; folgen Sie den Anweisungen der Ansage um die
 Nachricht aufzunehmen.
 
 - **Audio-Datei hochladen**: Laden Sie eine gespeicherte Audio-Datei hoch (Dateiformate: mp3, wav)


#### Koordinaten 

Unter „Koordinaten übermitteln“ können Sie entscheiden, ob Sie Koordinaten oder eine Adresse eingeben möchten.
![](/img/alarmieren_alarm_erstellen_koordinaten.png?classes=shadow)


 - **Adresse angeben**: Geben Sie hier eine Adresse, z.B. „Hauptstraße 10, Berlin“ oder ein Sonderziel, z.B. „Bahnhof Berlin“ ein 
  und bestätigen Sie mit der Eingabetaste. Die gefundene Adresse wird automatisch in das WGS84 Format umgewandelt.
  ![](/img/alarmieren_alarm_erstellen_koordinaten_adresse.png?classes=shadow)

 - **Koordinaten angeben**: Geben Sie hier Koordinaten im gewünschten Format (Schweizer Gitter, Milgrid, WGS84) an. 
Die Koordinaten werden automatisch in das WGS84 Format umgewandelt.



#### Alarmoptionen 

![](/img/alarmieren_alarm_erstellen_alarmoptionen.png?width=1000px&classes=shadow)

Unter den **„Alarmoptionen“** sind weitere Optionen definierbar.:

 - **Folgende Mittel alarmieren**: Welche Alarmmittel sollen alarmiert werden?
 
 - **Alert-SMS**(Flash-SMS): SMS wird direkt auf dem Handy-Display dargestellt wird, sobald sie eingegangen ist.

 - **Dry-Run**: Startet den Alarm nur als eine Art Probealarm, die Alarmmittel der Teilnehmer werden hierbei nicht ausgelöst. 
 
 - **PIN-Schutz**: Relevant für Alarmierung via Anruf. Wurde im [Teilnehmerbereich](/mutieren/mutation/teilnehmerliste/#teilnehmerbereich) ein PIN definiert, muss dieser vom Teilnehmer zunächst eingegeben werden, bevor die Sprachnachricht abgespielt wird.
 
 - **Wochenplaner**:(optionales Modul)

	- Aus Teilnehmerdaten: Die Teilnehmer werden anhand des [vordefinierten
    Wochenplaners](/admin/wochenplaner) alarmiert

	- Standard (default): Bei dieser Option wird der vordefinierte
    Wochenplaner (optionales Modul) nicht berücksichtigt

 - **Abbruch**: Bestimmung der Abbruchkriterien für die automatische Beendigung eines
Alarms. Wird ein definiertes Abbruchkriterium erreicht, wird der Alarm
gestoppt und geschlossen.

	- Abbruch aufgrund x % der Teilnehmer, welche positiv quittiert haben

	- Abbruch aufgrund x Teilnehmern, welche positiv quittiert haben

	- Abbruch nach x Minuten nach der Alarmauslösung

 - **Info-Versand**: Versand eines Alarm-Reports und/oder periodische Zusammenfassungen an Fax-/Mailadresse/ERIC Pager (Pagernummer eintragen inkl. PG)
 
 - **Unitronic Alarm Prio**: Art der Benachrichtigung/Alarmierung 
	- Textnachricht: Nicht lautstärken-übersteuernde Nachricht an den Pager (eigener Klingelton kann gesetzt werden)
	- Alarm: Lautstärken-übersteuernde Nachricht (eigener Klingelton kann gesetzt werden)
	- Prio-Alarm: Maximale Signalisierung (max. Lautstärke, Vibration) der Nachricht am Pager (eigener Klingelton kann gesetzt werden)


#### Zeitsteuerung 

![](/img/alarmieren_alarm_erstellen_zeitsteuerung.png?classes=shadow)

Grundsätzlich ist **GroupAlarm pro** so eingestellt, dass ein Alarm unmittelbar
ausgelöst wird. Unter Zeitsteuerung („Zu dem nachfolgenden Termin
versenden“) kann ein Alarm auch disponiert werden, indem Tag und Uhrzeit
der Alarmauslösung angegeben werden, beispielsweise für Probealarme.
 Disponierte Alarme können im Register **„Status“** im Menü [„disponierte Alarme“](/status/alarm-status/disponierte-alarme/)
abgefragt und gelöscht werden.

