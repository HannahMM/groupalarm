+++
title = "Texte"
weight = 3
+++



<a name="texte_bearbeiten"></a>
### Texte

Mit **eAlarm emergency** können Sie vordefinierte Alarmtexte in vier
Sprachen verfassen: **Deutsch, Französisch, Italienisch und Englisch**
(optionales Modul).   
Im Menü **„Texte“** können Sie Ihre vorhandenen Alarmtexte einsehen und bearbeiten sowie mit dem Text-Editor neue Texte in entsprechender Sprache anlegen.
![](/img/texte.png?width=700px&classes=shadow)

#### Neuer Text

Um einen neuen Text anzulegen, geben Sie den Text in das der jeweiligen Sprache entsprechende Eingabefenster ein und bestätigen Sie mit der Schaltfläche „anlegen“
<img src="/img/anlegen.png" alt="anlegen" style='vertical-align:middle;display:inline;margin:0px 5px; '>
Für einen Alarm bzw. eine Nachricht stehen 160 Zeichen zur Verfügung.   

{{% panel theme="danger" header="Achtung!" %}}Die Zeichen  <strong> | ^ € { } [  ] ~ \ </strong>,  **Seitenumbruch (sogenannter „Page Break“)** und ein **ESC** benötigen im GSM-Alphabet (d.h in einer SMS) zwei Zeichen, werden im Textfeld von **eAlarm** jedoch nur als ein Zeichen angezeigt.
Es kann daher zu einer Diskrepanz zwischen der Anzeige und dem eigentlichen Versand entstehen. Wir empfehlen daher, die oben erwähnten Zeichen nur sporadisch zu verwenden.{{% /panel %}}

Beachten Sie auch die Hinweise im unteren Bereich des Text-Editors :

- Ein Zeitstempel des Formates **03Apr2135** (für 3.4. 21:35 Uhr) wird durch den Platzhalter <strong>###dat###</strong> in den Nachrichtentext eingefügt.

- Ein Zeitstempel im 'Date-Time-Group' Format **032135Apr04** (für 3.4.2004 21:35 Uhr) wird durch den Platzhalter <strong>###dtg###</strong> in den Nachrichtentext eingefügt.

- Ein Zeitstempel im 'Time-Day-Month' Format **21:35 04 Apr** (für 3.4. 21:35 Uhr) wird durch den Platzhalter <strong>###tdm###</strong> in den Nachrichtentext eingefügt.

- Der Platzhalter <strong>!name!</strong> wird beim Versand durch den Namen des Teilnehmers ersetzt. So wird eine persönliche Ansprache möglich.

- Der Platzhalter <strong>###onum###</strong> teilt dem Empfänger bei einer Alarmauslösung per Voice-Anruf die Rufnummer des Auslösenden mit.

 
#### Angelegte Texte

![](/img/texte_angelegte.png?classes=shadow)
Hier finden Sie eine übersicht aller angelegten Texte und ihrer Textcodes.
Vor dem angelegten Text wird die Textsprache (DE, FR, IT, EN) angezeigt, die für die
Umwandlung des Textes in Sprache (über die Text-to-Speech-Schnittstelle)
relevant ist.
 Die angelegten Texte können über *Sprachausgabe* angehört, mit *Ändern*
geändert und und mit *Löschen* gelöscht werden. Mit dem Pfeilkreuz <img src="/img/pfeilkreuz.png" alt="pfeilkreuz" style='vertical-align:middle;display:inline;margin:0px 5px; '>
können Sie die Reihenfolge der Texte verändern.


### Sprachausgabe-Optionen für Alarm-Texte

Jeder angelegte Text kann über das Sprachmenü *[Sprachmenü]* abgespielt werden.
 Im Sprachmenü können Audiodateien im Windows-Wave-Format (*.wav) hochgeladen werden. Wenn keine Audiodatei hochgeladen werden kann, 
 besteht alternativ die Möglichkeit, die Telefonnummer 058 252 76 76 anzurufen und entsprechend Freitext aufzunehmen.
 Nach der Einwahl wird nach der Legitimations-PIN gefragt, die dem Sprachmenü entnehmbar ist. Die PIN wird nach 5 Minuten ungültig. 


![](/img/texte_sprachausgabe.png?classes=shadow)

