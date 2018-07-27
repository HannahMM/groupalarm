+++
title = "Drehbücher verwalten"
weight = 3
+++






<a name="drehbuch"></a>
### Drehbücher



In Drehbüchern können mehrere Alarm- und Konferenzvorlagen auf einem
Zeitstrahl hintereinander gereiht werden. So wird erreicht, dass nach
einer gewissen vordefinierten Zeit – falls der Alarm bis dahin nicht
schon beendet wurde – automatisch eine nächste Alarm- / Konferenzvorlage
ausgelöst wird. So können automatische Alarm-Eskalationen vordefiniert
werden, die ansonsten manuell durchgeführt werden müssten.


Im Menü **„Drehbücher“** werden Ihre vorhandenen Drehbücher aufgelistet. Sie können die Vorlagen nach Drehbuchname, Auslösecode, 
Beschreibung und Disponent filtern. Geben Sie dazu die gewünschten Filterkriterien in die Filterleiste ein 
und bestätigen Sie mit Klick auf das Filtersymbol 
<img src="/img/filtersymbol.png" alt="filter" style='vertical-align:middle;display:inline;margin:0px 5px; '>.

![](/img/mutieren_zusatzmodule_drehbuecher.png?classes=shadow)

<a name="funktionen"></a>
#### Funktionen

Folgende Funktionen stehen zur Verfügung:

 - **Bearbeiten** <img src="/img/bearbeitungsicon.png" alt="bearbeiten" style='vertical-align:middle;display:inline;margin:0px 5px; '> : 
 Bearbeiten eines vorhandenen Drehbuchs. Mehr Informationen im Abschnitt [Neues Drehbuch anlegen](#neues_drehbuch_anlegen).
 
 - **Drehbuch sperren** <img src="/img/schlosssymbol.png" alt="schloss" style='vertical-align:middle;display:inline;margin:0px 5px; '> : 
 Unberechtigte Personen können ein gesperrtes Drehbuch weder bearbeiten noch löschen, aber weiterhin auslösen. Entsperrt werden kann ein Drehbuch nur vom Ersteller oder dem Superuser.
 ![](/img/mutieren_zusatzmodule_drehbuecher_funktionen_sperren.png?classes=shdadow)
  
 - **Löschen**<img src="/img/loesch-icon.png" alt="lösch" style='vertical-align:middle;display:inline;margin:0px 5px; '>
 
 - **Kopieren**<img src="/img/kopiersymbol.png" alt="lösch" style='vertical-align:middle;display:inline;margin:0px 5px; '>: Erstellt eine Kopie mit Zusatz „copy 1“ des Drehbuches, übernimmt dabei alle Datensätze aber verteilt neuen Auslösecode.
 ![](/img/mutieren_zusatzmodule_drehbuecher_funktionen_kopieren.png?classes=shadow)


 



<a name="neues_drehbuch_anlegen"></a>
### Neues Drehbuch anlegen

Um ein neues Drehbuch anzulegen, klicken Sie im Menü **„Drehbücher“** auf *„Neues Drehbuch anlegen“* <img src="/img/mutieren_zusatzmodule_drehbuecher_neues_drehbuch_anlegen.png" alt="report" style='vertical-align:middle;display:inline;margin:0px 5px; '>.
Damit gelangen Sie ins Menü „Drehbuch“, wo Sie verschieden Optionen für das Drehbuch festlegen.   
  
Speichern Sie Ihre Einstellungen/Änderungen mit einem Klick auf „Drehbuch speichern“


<a name="allgemein"></a>
#### Allgemein

Im Reiter „Allgemein“ legen Sie Auslösecode und Drehbuchname fest sowie optional eine Beschreibung des Drehbuches. 
 

![](/img/mutieren_zusatzmodule_drehbuecher_allgemein.png?classes=shadow)

Die Funktion „Auslöseberechtigt“ können Sie erst nach Erstellen der Vorlage bearbeiten. Legen Sie hier Name und Nummer der Personen fest, die berechtigt sind, das Drehbuch per 
[Durchwahl](/alarmieren/fernausloese/#auslöse-per-durchwahl-anruf) (kostenpflichtiges Zusatzmodul) auszulösen.

![](/img/mutieren_zusatzmodule_drehbuecher_allgemein_ausloeseberechtigt.png?classes=shadow)

<a name="vorlagenzuordnung"></a>
#### Vorlagenzuordnung

Im Dropdown-Menü „Zuweisbare Vorlagen“ werden alle vorhandenen Alarm- und Konferenzvorlagen aufgelistet. Wählen Sie die gewünschte(n) Vorlage(n) aus und bestätigen Sie dies jeweils mit Klick auf „einfügen“

 
![](/img/mutieren_zusatzmodule_drehbuecher_vorlagenzuordnung1.png?classes=shadow)


Die ausgewählten Vorlagen werden unter „Zugewiesene Vorlagen“ in einem grauen Kasten angezeigt.


![](/img/mutieren_zusatzmodule_drehbuecher_vorlagenzuordnung2.png?classes=shadow)

Hier können Sie die Reihenfolge, in der die Vorlagen ausgelöst werden sollen, festlegen. Ziehen Sie dazu per Drag & Drop die Vorlage auf die gewünschte Position.   
Sie können auch manuell die „zeitliche Verzögerung nach der Drehbuchauslösung“ festlegen, indem Sie die Minuten und Sekunden in die Felder eintragen und mit *„ändern“* bestätigen. Mit einem Klick auf das Löschsymbol
<img src="/img/loesch-icon.png" alt="loesch" style='vertical-align:middle;display:inline;margin:0px 5px; '>
können Sie Vorlagen wieder entfernen. 
  
Die Reihenfolge und Verzögerungen werden auch auf einem Zeitstrahl visualisiert und können dort verändert werden. Ziehen Sie dazu die Vorlage mit der entsprechenden Nummer auf die gewünschte Position. 
![](/img/mutieren_zusatzmodule_drehbuecher_vorlagenzuordnung3.png?classes=shadow)


<a name="texte"></a>
#### Texte

Im Menü Texte können Sie entscheiden, ob Sie die in den Vorlagen festgelegten Texte verwenden oder einen neuen globalen Freitext definieren.

![](/img/mutieren_zusatzmodule_drehbuecher_texte.png?classes=shadow)




### Drehbuch auslösen


Um ein Drehbuch auszulösen, wählen Sie im Register **„Alarmieren“** aus der Spalte „Drehbücher“ das gewünschte Drehbuch aus. Eventuell
müssen Sie die angezeigten Spalten in dem Dropdown-Menü noch anpassen. 

 ![](/img/mutieren_zusatzmodule_drehbuecher_dropdown.png?classes=shadow)
 
Per Drag & Drop, Doppelklick oder der Schaltfläche „Auswahl übernehmen“ fügen Sie das Drehbuch der Teilnehmerliste auf der rechten Seite hinzu.
Mit einem Klick auf „Alarm“ gelangen Sie in das Menü „Drehbuch auslösen“. Dort können Sie das Drehbuch direkt mit seinen vordefinierten Attributen auslösen, aber auch Optionen anpassen (z.B. Reihenfolge der Vorlagen ändern)

![](/img/mutieren_zusatzmodule_drehbuecher_ausloesen.png?width=1000px&classes=shadow)



