+++
title = "Ereignisse verwalten"
weight = 2
+++

### Ereignisse

Mit dem Modul „Ereignisse“ können Sie bestimmten Ereignissen eine Ihrer erstellten Vorlagen zuordnen. Diese Ereignisse können z.B. von 
externen Systemen aktiviert werden. Der Vorteil dabei ist, dass Änderungen direkt an der Vorlage vorgenommen werden können, während das
Ereignis unverändert bleibt.


Im Menü **„Ereignisse“** werden Ihre vorhandenen Ereignisse aufgelistet. Sie können die Vorlagen nach Ereignisname, Beschreibung, Bearbeitungszeitpunkt und Disponent filtern. Geben Sie dazu die gewünschten Filterkriterien in die Filterleiste ein 
und bestätigen Sie mit Klick auf das Filtersymbol 
<img src="/img/filtersymbol.png" alt="filter" style='vertical-align:middle;display:inline;margin:0px 5px; '>

![](/img/mutieren_zusatzmodule_ereignis.png?classes=shadow)

<a name="funktionen"></a>
#### Funktionen

Folgende Funktionen stehen zur Verfügung

 - **Bearbeiten** <img src="/img/bearbeitungsicon.png" alt="bearbeiten" style='vertical-align:middle;display:inline;margin:0px 5px; '> : 
 Bearbeiten eines vorhandenen Ereignisses. Mehr Informationen im Abschnitt [Neues Ereignis anlegen](#neues_ereignis_anlegen).
 
 - **Ereignis sperren** <img src="/img/schlosssymbol.png" alt="schloss" style='vertical-align:middle;display:inline;margin:0px 5px; '> : 
 Unberechtigte Personen können ein gesperrtes Ereignis weder bearbeiten noch löschen, aber weiterhin auslösen. Entsperrt werden kann ein Ereignis nur vom Ersteller oder dem Superuser.
 
 ![](/img/mutieren_zusatzmodule_ereignis_funktionen_sperren.png?classes=shadow)
 
  
 - **Löschen**<img src="/img/loesch-icon.png" alt="lösch" style='vertical-align:middle;display:inline;margin:0px 5px; '>
 
 - **Kopieren**<img src="/img/kopiersymbol.png" alt="lösch" style='vertical-align:middle;display:inline;margin:0px 5px; '>: Erstellt eine Kopie mit Zusatz „copy 1“ des Ereignisses  und übernimmt dabei alle Datensätze 

![](/img/mutieren_zusatzmodule_ereignis_funktionen_kopieren.png?classes=shadow)





<a name="neues_ereignis_anlegen"></a>
### Neues Ereignis anlegen

Um ein neues Ereignis anzulegen, klicken Sie im Menü **„Ereignisse“** auf *„Neues Ereignis anlegen“* <img src="/img/mutieren_zusatzmodule_ereignis_neues_ereignis_anlegen.png" alt="report" style='vertical-align:middle;display:inline;margin:0px 5px; '>.
Damit gelangen Sie ins Menü „Ereignis“, wo Sie verschiedene Optionen festlegen können.   
  
Speichern Sie Ihre Einstellungen/Änderungen mit einem Klick auf „Ereignis speichern“



#### Allgemein

Im Reiter „Allgemein“ legen Sie Ereignis-Code und -Name fest sowie optional eine Beschreibung. 
 

![](/img/mutieren_zusatzmodule_ereignis_allgemein.png?classes=shadow)

Die Funktion „Auslöseberechtigt“ können Sie erst nach erstmaligem Erstellen der Vorlage bearbeiten. Legen Sie hier Name und Nummer der Personen fest, die berechtigt sind, das Ereignis per Durchwahl (kostenpflichtiges Zusatzmodul) auszulösen.

![](/img/mutieren_zusatzmodule_ereignis_allgemein_ausloeseberechtigt.png?classes=shadow)

#### Vorlagen-/Drehbuchzuordnung

Im Dropdown-Menü „Vorlagen/Drehbuch zuweisen“ werden alle vorhandenen Alarm- und Konferenzvorlagen aufgelistet. Wählen Sie die gewünschte Vorlage aus.

 
![](/img/mutieren_zusatzmodule_ereignis_vorlagenzuordnung.png?classes=shadow)



<a name="text"></a>
#### Text

Unter allen verfügbaren Texten, also vordefinierte Texte sowie Freitext wählen Sie mit dem Radiobutton <img src="/img/auswahl_rund.png" alt="radiobutton" style='vertical-align:middle;display:inline;margin:0px 5px; '>
einen Standardtext aus. Mit den Checkboxes <img src="/img/auswahl_eckig.png" alt="checkbox" style='vertical-align:middle;display:inline;margin:0px 5px; '>
können Sie alternative Texte auswählen. Bei der späteren Auslösung ist der als Standardtext gewählte Text vorselektiert und nur die als Alternativen markierten Texte werden angezeigt.  

![](/img/mutieren_zusatzmodule_ereignis_texte.png?classes=shadow)

<a name="koordinaten"></a>
#### Koordinaten

Analog zum Erstellen eines Alarms können Sie hier entscheiden, ob Sie Koordinaten übermitteln wollen. Sie können eine Adresse angeben und mit 
der Enter-Taste bestätigen, diese wird automatisch in das WGS84-Format umgewandelt, oder direkt Koordinaten angeben.

![](/img/mutieren_zusatzmodule_ereignis_koordinaten.png?classes=shadow)




### Ereignis auslösen

Um ein Ereignis auszulösen, wählen Sie im Register „Alarmieren“ aus der Spalte „Ereignisse“ die gewünschte Vorlage aus. Eventuell müssen Sie die angezeigten Spalten in dem Dropdown-Menü noch anpassen.

![](/img/mutieren_zusatzmodule_ereignis_dropdown.png?classes=shadow)

Per Drag & Drop, Doppelklick oder der Schaltfläche „Auswahl übernehmen“ fügen Sie das Ereignis der Teilnehmerliste auf der rechten Seite hinzu. Mit einem Klick auf „Alarm“ gelangen Sie in das entsprechende Auslöse-Menü. 
Dort können Sie das Ereignis direkt mit seinen vordefinierten Attributen auslösen, aber auch Optionen anpassen.

![](/img/mutieren_zusatzmodule_ereignis_ausloesen.png?classes=shadow&width=1000)


