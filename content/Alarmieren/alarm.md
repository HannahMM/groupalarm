+++
title = "Alarm erstellen"
weight = 1
+++



<a name="alarm_erstellen"></a>
### Alarm erstellen 

Sobald Teilnehmer, Gruppen und Wurzeln ausgewählt und die Schaltfläche
**„Alarm“** <img src="/img/alarmieren_alarm.png" alt="alarm" style='vertical-align:middle;display:inline;margin:0px 5px; '>
geklickt wurde, öffnet sich die Maske „Alarm erstellen“.

![](/img/alarmieren_alarm_erstellen.png?classes=shadow&width=900px)


Hier können Sie verschiedene Einstellung für Ihren Alarm vornehmen und anschließend mit der Schaltfläche 
![](/img/alarmieren_alarm_erstellen_ausloesen.png?classes=shadow) auslösen. Die Schaltfläche wird grau dargestellt solange noch 
nicht alle nötigen Einstellungen vorgenommen wurden.



Neben einer Alarmauslösung direkt aus dem Webbrowser unterstützt
**GroupAlarm pro** mehrere Wege der Fernauslösung. Ob Alarm per SMS,
Anruf und DTMF-Menü, Durchwahl und über einen Web-Link, die Auslösung
ist von nahezu allen Plattformen realisierbar. 


<a name="allgemein"></a>
#### Allgemein 

![](/img/alarmieren_alarm_erstellen_allgemein.png?width=700px&classes=shadow)

Der **„Alarmname“** kann den Wünschen entsprechend angepasst werden.
Unter **„Beschreibung“** kann der Alarm beschrieben werden (optional).
Unter **„Ersteller“** wird ersichtlich, wer diesen Alarm erstellt hat
und unter **„Datum/Zeit“** wird angezeigt, wann der Alarm erstellt
wurde.


<a name="teilnehmer"></a>
#### Teilnehmer 

![](/img/alarmieren_alarm_erstellen_einheiten.png?width=700px&classes=shadow)

Unter **„Einheit“** werden Ihnen die selektierten Teilnehmer und Einheiten angezeigt. Mit <img src="/img/loesch-icon.png" alt="del" style='vertical-align:middle;display:inline;margin:0px 5px; '>
können Sie Teilnehmer direkt löschen, über *\[bearbeiten\]* gelangen Sie zurück in das Menü *Alarm erstellen* und können
weitere Teilnehmer hinzufügen.


<a name="text"></a>
#### Text 


![](/img/alarmieren_alarm_erstellen_text.png?classes=shadow)

Bevor ein Alarm ausgelöst werden kann, muss ein Alarmtext gewählt werden. Folgende Möglichkeiten stehen zur Verfügung:

 - **Definierte Texte:**  Wählen Sie einen vordefinierten Text aus. Diese müssen zuvor im Register **„Mutieren“** im Menü [„Texte“](/mutieren/mutation/texte/)
 erstellt werden. Durch einen Klick auf *\[QuickEdit\]* 
 können Sie die Vorlage direkt anpassen.
 
 - **Freitext**: Verfassen Sie einen neuen Alarmtext. Mit der Schaltfläche „Datei auswählen“ können Sie der Nachricht eine Datei anhängen. (Dateiformate: TODO, PDF, Word-Doc)
 
 - **Live-Sprachaufnahme**: Option, eine eigene Sprachnachricht aufzunehmen. Geben Sie hierzu eine gültige Rufnummer ein und klicken Sie auf „Alarmansage aufnehmen“. Sie werden nun auf dieser Nummer angerufen; folgen Sie den Anweisungen der Ansage um die
 Nachricht aufzunehmen.
 
 - **Audio-Datei hochladen**: Laden Sie eine gespeicherte Audio-Datei hoch (Dateiformate: TODO)




<a name="koordinaten"></a>
#### Koordinaten 

Unter „Koordinaten übermitteln“ können Sie entscheiden, ob Sie Koordinaten oder eine Adresse übermitteln möchten.
![](/img/alarmieren_alarm_erstellen_koordinaten.png?width=700px&classes=shadow)


 - **Adresse angeben**: Geben Sie hier eine Adresse, z.B. „Hauptstraße 10, Berlin“ oder ein Sonderziel, z.B. „Bahnhof Berlin“ ein 
  und bestätigen Sie mit der Eingabetaste. Die gefundene Adresse wird automatisch in das WGS84 Format umgewandelt.
  ![](/img/alarmieren_alarm_erstellen_koordinaten_adresse.png?classes=shadow)

 - **Koordinaten angeben**: Geben Sie hier Koordinaten im gewünschten Format (Schweizer Gitter, Milgrid, WGS84) an. 
Die Koordinaten werden automatisch in das WGS84 Format umgewandelt.



<a name="alarmoptionen"></a>
#### Alarmoptionen 

![](/img/alarmieren_alarm_erstellen_alarmoptionen.png?width=700&classes=shadow)

Unter den **„Alarmoptionen“** sind weitere Optionen definierbar.:

 - **Folgende Mittel alarmieren**: Welche Alarmmittel sollen alarmiert werden?
 
 - **Alert-SMS**: TODO

 - **Dry-Run**: TODO
 
 - **PIN-Schutz**: TODO
 
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

 - **Info-Versand**: Versand eines Alarm-Reports und/oder periodische Zusammenfassungen an Fax-/Mailadresse
 
 - **Unitronic Alarm Prio**: TODO


<a name="versandzeitzeitsteuerung"></a>
#### Versandzeit/Zeitsteuerung 

![](/img/alarmieren_alarm_erstellen_zeitsteuerung.png?classes=shadow)

Grundsätzlich ist **GroupAlarm pro** so eingestellt, dass ein Alarm unmittelbar
ausgelöst wird. Unter Zeitsteuerung („Zu dem nachfolgenden Termin
versenden“) kann ein Alarm auch disponiert werden, indem Tag und Uhrzeit
der Alarmauslösung angegeben werden, beispielsweise für Probealarme.
 Disponierte Alarme können im Register **„Status“** im Menü [„disponierte Alarme“](/status/alarm-status/disponierte-alarme/)
abgefragt und gelöscht werden.

