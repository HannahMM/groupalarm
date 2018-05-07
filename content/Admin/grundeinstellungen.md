+++
title = "Grundeinstellungen"
weight = 1
+++


![](/img/admin_grundeinstellungen.png?classes=shadow)
	
### Auslöseberechtigungen

In „Grundeinstellungen” werden die Berechtigungen für die Auslösung per SMS und per Anruf mit DTMF-Menü konfiguriert. 


Als Auslöse-PIN dient ein 4-stelliger Code. Dieser kann beliebig gewählt
werden und darf innerhalb des Systems mehrfach vorkommen. In Kombination
mit einer auslöseberechtigten Nummer kann der Teilnehmer damit einen
Alarm per SMS auslösen.


#### Auslöseberechtigte Nummern

Hier wird angezeigt, wie viele Nummern auslöseberechtigt sind. 

Über den Link \[*bearbeiten*\] gelangt man zu einer Liste mit den
Nummern, die eine Auslöseberechtigung für den Account haben. Sie können die Einträge ändern oder löschen. Unter
**„Neuer Eintrag“** kann eine neue Nummer mit folgenden Parametern erstellt werden:

 -  Nummer: Absender-Nummer des berechtigten Endgeräts. Das Format muss
    dabei exakt mit dem signalisierten Format übereinstimmen; der
    Hinweis zum Format ist daher zu beachten.

 -  Name: Name des auslöseberechtigten Teilnehmers. Der Name dient
    ausschliesslich der späteren Lesbarkeit der Liste
    der Auslöseberechtigten.

![](/img/admin_grundeinstellungen_ausloeseberechtigte.png?width=700px&classes=shadow)

#### Berechtigung am Telefon mit Syspin
	
Anstatt die Absendernummer zu berechtigen, besteht für die Auslösung per
Anruf mit DTMF-Menü zusätzlich die Möglichkeit der
Anrufer-Identifizierung über die sogenannte Syspin. Ist die Checkbox
**Berechtigung am Telefon mit Syspin XXXXXX** aktiviert, wird damit die
Möglichkeit geschaffen, von einem beliebigen Telefonanschluss aus Alarme
auszulösen. Voraussetzung ist dann die Kenntnis der 6-stelligen Syspin,
die im Sprachmenü eingegeben werden muss.

**Die Syspin ist eine global eindeutige Nummer und wird von groupAlarm fest vorgegeben.** Sie stellt sicher, dass ein Anrufer dem
richtigen Kundenaccount zugeordnet werden kann. Als weitere Sicherheit
wird auch bei einer Berechtigung über die Syspin zusätzlich die
4-stellige Auslöse-PIN abgefragt.


### Alarmauslösung per SMS


**GroupAlarm pro** unterstützt die Auslösung per SMS. Hierfür wird
eine SMS mit definiertem Inhalt an **groupAlarm pro** gesendet. Die
Auslöseberechtigung wird zum einen über die Absendernummer und zum
anderen über eine im SMS-Text enthaltene PIN sichergestellt.

{{% panel theme="info" header="Wichtig!" %}}Mit der Auslösung per SMS kann immer nur genau **EINE**
Einheit, d.h. eine Vorlage, ein Drehbuch oder eine Konferenzvorlage
ausgelöst werden, die Kombination mehrerer Einheiten wird nicht
unterstützt. Dieser Umstand ist bei der Definition von Alarmvorlagen/Drehbüchern und Konferenzvorlagen zu berücksichtigen.{{% /panel %}}


Um in **GroupAlarm pro** eine Alarmvorlage, ein Drehbuch oder eine
Konferenzvorlage per SMS auszulösen muss eine Auslöse-SMS an die Nummer
079 252 76 32 gesendet werden.

Beachten Sie dabei: Damit von GroupAlarm überhaupt eine Auslösung per SMS
in Betracht gezogen wird, muss die Absendernummer der Auslöse-SMS mit
einer der als „auslöseberechtigt“ konfigurierten Nummern übereinstimmen.



Der Inhalt der Auslöse-SMS muss folgender Syntax folgen:
**PINa\_@xyz\_TEXT**

 - **PIN:** Die 4-stellige PIN muss mit der online konfigurierten
Auslöse-PIN korrespondieren

 - **a:** a=0 Wird a=0 gesetzt, so wird der TEXT-Teil nicht als Freitext
interpretiert, sondern nach definierten Alarm- Variablen geparst

 - **@:** Steht für den auszulösenden Einheitstyp, dabei gilt folgende
Konvention:
  - „#“ (Raute/Hash)        =     Alarmvorlage 
  - „*“ (Stern/Star)        =       Drehbuch 
  - „!“ (Ausrufezeichen)     =  Konferenzvorlage


 - **xyz:** steht für den jeweiligen Auslösecode der gewählten Einheit.
Dieser kann aus 1 – n Stellen bestehen. (der Auslösecode ist bei
aktiviertem Modul Fernauslösung online in der jeweiligen Verwaltung
(Alarmvorlagen, Drehbücher oder Konferenzvorlagen) ersichtlich!

 - **\_:** Leerschlag (ist zwingend!!)

 - **TEXT:** Alarmtext
 
 Ist der Parameter a=0 gesetzt, dann wird der TEXT-Teil nicht
1:1 als Alarmtext übernommen, sondern der Inhalt des Freitextes nach
auffälligen Variablen geparst und entsprechend die Platzhalter im
Standard-Alarmtext der ausgelösten Einheit mit den Parsing-Ergebnissen
substituiert

#### Bestätigung per SMS

Standardmässig wird eine Auslösung per SMS mit einer Antwort-SMS an die
auslösende Nummer bestätigt. Dies kann durch den Masteruser bei Bedarf in
der Admin Registry unterdrückt werden, indem der Key „Suppress SMS
Reply“ mit einer 1 aktiviert wird.

Die Bestätigung kann sowohl positiv ausfallen (OK) oder negativ
(NOT\_OK), wenn aufgrund fehlender oder falscher Informationen der Alarm
nicht ausgelöst werden konnte. Details zu einem allfälligen Fehler sind
in englischer Sprache ebenfalls in der SMS enthalten.

	
###	Sprach- und Konferenzanrufe

In diesem Abschnitt können für die Sprachanrufe und die Konferenzanrufe die Anrufzeit,
Anzahl Wiederholungen und die Klingeldauer angepasst werden.




