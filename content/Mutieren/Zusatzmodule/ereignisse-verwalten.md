+++
title = "Ereignisse verwalten (Optionales Modul)"
weight = 2
+++

### Ereignisse

Mit dem Modul „Ereignisse“ können Sie bestimmten Ereignissen eine Ihrer erstellten Vorlagen zuordnen. Diese Ereignisse können z.b. von 
externen Systemen aktiviert werden. Der Vorteil dabei ist, das Änderungen direkt an der Vorlage vorgenommen werden können, wärend das
Ereignis unverändert bleibt.


Im Menü **„Ereignisse“** werden Ihre vorhandenen Ereignisse aufgelistet. Sie können die Vorlagen nach Ereignissname,  
Beschreibung, Bearbeitungszeitpunkt und Disponent filtern. Geben Sie dazu die gewünschten Filterkriterien in die Filterleiste ein 
und bestätigen Sie mit Klick auf das Filtersymbol 
<img src="/img/filtersymbol.png" alt="filter" style='vertical-align:middle;display:inline;margin:0px 5px; '>

![](/img/zusatzmodule_ereignisse.png?classes=shadow)

<a name="funktionen"></a>
#### Funktionen

Folgene Funktionen stehen zur Verfügung

 - **Bearbeiten** <img src="/img/bearbeitungsicon.png" alt="bearbeiten" style='vertical-align:middle;display:inline;margin:0px 5px; '> : 
 Bearbeiten eines vorhandenen Ereignisses. Mehr Informationen im Abschnitt [Neues Ereignis anlegen](#neues_ereignis_anlegen).
 
 - **Ereignis sperren** <img src="/img/schlosssymbol.png" alt="schloss" style='vertical-align:middle;display:inline;margin:0px 5px; '> : 
 Option, ein Ereignis zu sperren. Unberechtigte Personen können ein gesperrtes Ereignis weder bearbeiten noch löschen, aber weiterhin auslösen. Entsperrt werden kann ein Ereignis nur vom Autor oder einem Superuser.
 
 - **Report als PDF herunterladen** <img src="/img/pdfsymbol.png" alt="pdf" style='vertical-align:middle;display:inline;margin:0px 5px; '> : Erstellt einen Report im PDF Format über das Ereignis. 
 Hier werden allgemeine Informationen, die gewählten Vorlagen und Texte und weitere Optionen aufgeführt
 
 ![](/img/zusatzmodule_ereignisse_report.png?width=700px&classes=shadow)
  
 - **Löschen**<img src="/img/loesch-icon.png" alt="lösch" style='vertical-align:middle;display:inline;margin:0px 5px; '>: Löschen des Ereignisses.
 
 - **Kopieren**<img src="/img/kopiersymbol.png" alt="lösch" style='vertical-align:middle;display:inline;margin:0px 5px; '>: Erstellt eine Kopie mit Zusatz „copy“ des Ereignisses  und übernimmt dabei alle Datensätze 



 
Mit der Schaltfläche *„Report herunterladen“* <img src="/img/report_herunterladen.png" alt="report" style='vertical-align:middle;display:inline;margin:0px 5px; '>
 können Sie einen PDF Report erstellen, in dem alle aktuell angezeigten Ereignisse aufgeführt werden. Haben Sie z.B. mit der Filteroption nur die Ereignisse erstellt von Max Mustermann angezeigt 
und klicken auf *„Report herunterladen“*, werden auch nur diese im Report aufgeführt.




<a name="neues_ereignis_anlegen"></a>
### Neues Ereignis anlegen

Um ein neues Ereignis anzulegen, klicken Sie im Menü **„Ereignisse“** auf *„Neues Ereignis anlegen“* <img src="/img/zusatzmodule_ereignisse_neu_anlegen.png" alt="report" style='vertical-align:middle;display:inline;margin:0px 5px; '>.
Damit gelangen Sie ins Menü „Ereignis“, wo Sie verschieden Optionen festlegen.   
  
Speichern Sie Ihre Einstellungen/Änderungen mit einem Klick auf „Ereignis speichern“


<a name="allgemein"></a>
#### Allgemein

Im Reiter „Allgemein“ legen Sie Ereignis-Code und -name fest sowie optional eine Beschreibung. 
Die Funktion „Auslöseberechtigt“ können Sie erst nach Erstellen der Vorlage bearbeiten. 

![](/img/zusatzmodule_ereignisse_allgemein.png?classes=shadow)


<a name="vorlagenzuordnung"></a>
#### Vorlagen-/Drehbuchzuordnung

Im Dropdown-Menü „Vorlagen/Drehbuch zuweisen“ werden alle vorhandenen Alarm- und Konferenzvorlagen aufgelistet. Wählen Sie die gewünschte Vorlage aus und bestätigen Sie dies mit Klick auf „einfügen“

 
![](/img/zusatzmodule_ereignisse_vorlagenzuordnung.png?classes=shadow)





<a name="text"></a>
#### Text

Unter allen verfügbaren Texten, also vordefinierte Texte sowie Freitext wählen Sie mit dem Radiobutton <img src="/img/auswahl_rund.png" alt="radiobutton" style='vertical-align:middle;display:inline;margin:0px 5px; '>
einen Standardtext aus. Mit den Checkboxes <img src="/img/auswahl_eckig.png" alt="checkbox" style='vertical-align:middle;display:inline;margin:0px 5px; '>
können Sie alternative Texte auswählen, die bei der Auslösung in die engere Auswahl kommen \(analog zu [Alarmvorlagen verwalten](/de/mutieren/zusatzmodule/alarmvorlagen-verwalten/#text) \)



<a name="koordinaten"></a>
#### Koordinaten

Analog zum Erstellen eines Alarms können Sie hier entscheiden, ob Sie Koordinaten übermitteln wollen. Sie können eine Adresse angeben und mit 
der Enter-Taste bestätigen, diese wird automatisch in das WGS84-Format umgewandelt, oder direkt Koordinaten angeben.

