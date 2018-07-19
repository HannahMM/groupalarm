+++
title = "Texte"
weight = 3
+++



### Texte

Mit **GroupAlarm pro** können Sie vordefinierte Alarmtexte in vier
Sprachen verfassen: **Deutsch, Englisch, Französisch und Italienisch**.  
Im Menü **„Texte“** können Sie Ihre vorhandenen Alarmtexte einsehen und bearbeiten sowie mit dem Text-Editor neue Texte in entsprechender Sprache anlegen.
![](/img/mutieren_mutation_texte.png?width=700px&classes=shadow)

#### Neuer Text

Um einen neuen Text anzulegen, geben Sie den Text in das der jeweiligen Sprache entsprechende Eingabefenster ein und bestätigen Sie mit der Schaltfläche „anlegen“.
Für einen Alarm bzw. eine Nachricht stehen 160 Zeichen zur Verfügung.   

{{% panel theme="danger" header="Achtung!" %}}Die Zeichen  <strong> | ^ € { } [  ] ~ \ </strong>,  **Seitenumbruch (sogenannter „Page Break“)** und ein **ESC** benötigen im GSM-Alphabet (d.h. in einer SMS) zwei Zeichen, werden im Textfeld von **GroupAlarm** 
jedoch nur als ein Zeichen angezeigt.
Es kann daher zu einer Diskrepanz zwischen der Anzeige und dem eigentlichen Versand entstehen. Wir empfehlen daher, die oben erwähnten Zeichen nur sporadisch zu verwenden.{{% /panel %}}

Beachten Sie auch die Hinweise im unteren Bereich des Text-Editors:

- Ein Zeitstempel des Formates **03Apr2135** (für 3.4. 21:35 Uhr) wird durch den Platzhalter <strong>###dat###</strong> in den Nachrichtentext eingefügt.

- Ein Zeitstempel im 'Date-Time-Group' Format **032135Apr04** (für 3.4.2004 21:35 Uhr) wird durch den Platzhalter <strong>###dtg###</strong> in den Nachrichtentext eingefügt.

- Ein Zeitstempel im 'Time-Day-Month' Format **21:35 04 Apr** (für 3.4. 21:35 Uhr) wird durch den Platzhalter <strong>###tdm###</strong> in den Nachrichtentext eingefügt.

- Der Platzhalter <strong>!name!</strong> wird beim Versand durch den Namen des Teilnehmers ersetzt. So wird eine persönliche Ansprache möglich.

- Der Platzhalter <strong>###onum###</strong> teilt dem Empfänger bei einer Alarmauslösung per Voice-Anruf die Rufnummer des Auslösenden mit.

 
#### Angelegte Texte

![](/img/mutieren_mutation_texte_angelegt.png?classes=shadow)

Hier finden Sie eine Übersicht aller angelegten Texte und ihrer Textcodes.
Vor dem angelegten Text wird die Textsprache (DE, FR, IT, EN) angezeigt, die für die
Umwandlung des Textes in Sprache (über die Text-to-Speech-Schnittstelle)
relevant ist.
 Die angelegten Texte können über *Sprachmenü* angehört, mit *Ändern*
geändert und mit *Löschen* gelöscht werden. 

### Sprachausgabe-Optionen für Alarm-Texte (Optionales Modul)

Jeder angelegte Text kann über das  *[Sprachmenü]* abgespielt werden.
 Im Sprachmenü können Audiodateien im Windows-Wave-Format (*.wav) hochgeladen werden. Wenn keine Audiodatei hochgeladen werden kann, 
 besteht alternativ die Möglichkeit, die Telefonnummer 0241 98099076 anzurufen und einen Text aufzunehmen.
 Nach der Einwahl wird nach einer Legitimations-PIN gefragt, die dem Sprachmenü entnehmbar ist. Die PIN wird nach 5 Minuten ungültig. 


![](/img/mutieren_mutation_texte_sprachmenue.png?classes=shadow)


