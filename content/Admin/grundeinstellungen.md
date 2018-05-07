+++
title = "Grundeinstellungen"
weight = 1
+++


![](/img/admin_grundeinstellungen.png?classes=shadow)
	
### Auslöseberechtigungen

In „Grundeinstellungen” werden die Berechtigungen für die [Fernauslösung](/alarmieren/fernausloese/) per SMS und per Anruf mit DTMF-Menü konfiguriert. 


Als Auslöse-PIN dient ein 4-stelliger Code. Dieser kann beliebig gewählt
werden und darf innerhalb des Systems mehrfach vorkommen. In Kombination
mit einer auslöseberechtigten Nummer kann der Teilnehmer damit einen
Alarm per SMS oder Anruf auslösen.


#### Auslöseberechtigte Nummern

Hier wird angezeigt, wie viele Nummern für die Fernauslöse berechtigt sind. 

Über den Link \[*bearbeiten*\] gelangt man zu einer Liste mit den
Nummern, die eine Auslöseberechtigung für den Account haben. Sie können die Einträge ändern oder löschen. Unter
**„Neuer Eintrag“** kann eine neue Nummer mit folgenden Parametern erstellt werden:

 -  Nummer: Absender-Nummer des berechtigten Endgeräts. Das Format muss
    dabei exakt mit dem signalisierten Format übereinstimmen; der
    Hinweis zum Format ist daher zu beachten.

 -  Name: Name des auslöseberechtigten Teilnehmers. Der Name dient
    ausschliesslich der späteren Lesbarkeit der Liste
    der Auslöseberechtigten.

![](/img/admin_grundeinstellungen_ausloeseberechtigte.png?classes=shadow)

{{% panel theme="danger" header="Achtung" %}}Für die Fernauslöse per Anruf muss die Nummer ohne Ländervorwahl hinterlegt sein, also 0178 1234567.
Für die Fernauslöse per SMS muss die Nummer jedoch dem Angezeigten Syntax entsprechen, also Ländervorwahl ohne + oder Ähnliches, z.B. 491781234567{{% /panel %}}



#### Berechtigung am Telefon mit Syspin
	
Anstatt die Absendernummer zu berechtigen, besteht für die Auslösung per
Anruf mit DTMF-Menü zusätzlich die Möglichkeit der
Anrufer-Identifizierung über die sogenannte Syspin. Ist die Checkbox
**Berechtigung am Telefon mit Syspin XXXXXX** aktiviert, wird damit die
Möglichkeit geschaffen, von einem beliebigen Telefonanschluss aus Alarme
auszulösen. Voraussetzung ist dann die Kenntnis der 6-stelligen Syspin,
die im Sprachmenü eingegeben werden muss.

**Die Syspin ist eine global eindeutige Nummer und wird von GroupAlarm fest vorgegeben.** Sie stellt sicher, dass ein Anrufer dem
richtigen Kundenaccount zugeordnet werden kann. Als weitere Sicherheit
wird auch bei einer Berechtigung über die Syspin zusätzlich die
4-stellige Auslöse-PIN abgefragt.



	
###	Sprach- und Konferenzanrufe

In diesem Abschnitt können für die Sprachanrufe und die Konferenzanrufe die Anrufzeit,
Anzahl Wiederholungen und die Klingeldauer angepasst werden.




