+++
title = "Alarmvorlagen verwalten (optionales Modul)"
weight = 1
+++


<!--
### Inhaltsverzeichnis 

- [Alarmvorlagen](#alarmvorlagen)
	- [Funktionen](#funktionen)
- [Neue Alarmvorlage anlegen](#neue_alarmvorlage_anlegen)
	- [Allgemein](#allgemein)
	- [Teilnehmer](#teilnehmer)
	- [Text](#text)
	- [Koordinaten](#koordinaten)
	- [Alarmoptionen](#alarmoptionen)
	- [Versandzeit](#versandzeit)
- [Alarmvorlage auslösen](#alarmvorlage_ausloesen)
- [Teilnehmer nachträglich hinzufügen](#teilnehmer_nachtraeglich_hinzufuegen) -->




<a name="alarmvorlagen"></a>
### Alarmvorlagen
Alarmvorlagen sind vordefinierte Alarme. Das bedeutet, der Teilnehmerkreis und die möglichen Alarmtexte sind bereits vordefiniert. 
Im Ernstfall kann bei der Alarmierung die vorher erfasste Alarmvorlage ausgelöst werden und die definierten Alarmteilnehmer werden über die entsprechenden Mittel mit dem Alarmtext alarmiert.   

Im Menü **„Alarmvorlagen“** werden Ihre vorhandenen Alarmvorlagen aufgelistet. Sie können die Vorlagen nach Alarmname, Auslösecode, 
Beschreibung, Zeitpunkt der letzen Bearbeitung und Disponent filtern. Geben Sie dazu die gewünschten Filterkriterien in die Filterleiste ein 
und bestätigen Sie mit Klick auf das Filtersymbol 
<img src="/img/filtersymbol.png" alt="filter" style='vertical-align:middle;display:inline;margin:0px 5px; '>

![](/img/zusatzmodule_alarmvorlagen.png?classes=shadow)




<a name="funktionen"></a>
#### Funktionen

Folgene Funktionen stehen zur Verfügung

 - **Bearbeiten** <img src="/img/bearbeitungsicon.png" alt="bearbeiten" style='vertical-align:middle;display:inline;margin:0px 5px; '> : 
 Bearbeiten eines vorhandenen Alarms. Mehr Informationen im Abschnitt [Neue Alarmvorlage anlegen](#allgemein).
 
 - **Vorlage sperren** <img src="/img/schlosssymbol.png" alt="schloss" style='vertical-align:middle;display:inline;margin:0px 5px; '> : 
 Option, eine Alarmvorlage zu sperren. Unberechtigte Personen können eine gesperrte Vorlage weder bearbeiten noch löschen, aber weiterhin auslösen. Entsperrt werden kann eine Vorlage nur vom Autor oder einem Superuser.
 ![](/img/zusatzmodule_alarmvorlage_sperren.png?classes=shdadow)
 
 - **Report als PDF herunterladen** <img src="/img/pdfsymbol.png" alt="pdf" style='vertical-align:middle;display:inline;margin:0px 5px; '> : Erstellt einen Report im PDF Format über die Alarmvorlage. 
 Hier werden Ersteller, Alarmname und Beschreibung, die alarmierten Einheiten, die gewählten Texte und weitere Optionen aufgeführt
 
 ![](/img/zusatzmodule_alarmvorlagen_pdfreport.png?width=700px&classes=shadow)
 
 - **Erweiterten Report als PDF herunterladen**<img src="/img/erweitertpdfsymbol.png" alt="pdf" style='vertical-align:middle;display:inline;margin:0px 5px; '>: Erstellt einen Report im PDF Format der zusätzlich noch
 einen Einzelteilnehmerexport enthält, worin alle Teilnehmer inklusive der Alarmmittel, Profile und Optionalen Felder aufgelistet werden.
 
 - **Löschen**<img src="/img/loesch-icon.png" alt="lösch" style='vertical-align:middle;display:inline;margin:0px 5px; '>: Löschen der Alarmvorlage.
 
 - **Kopieren**<img src="/img/kopiersymbol.png" alt="lösch" style='vertical-align:middle;display:inline;margin:0px 5px; '>: Erstellt eine Kopie mit Zusatz „copy“ der Alarmvorlage, übernimmt dabei alle Datensätze aber verteilt neuen Auslösecode
 ![](/img/zusatzmodule_alarmvorlage_kopieren.png?classes=shadow)
 
 
 
Mit der Schaltfläche *„Report herunterladen“* <img src="/img/report_herunterladen.png" alt="report" style='vertical-align:middle;display:inline;margin:0px 5px; '>
 bzw. *„erweiterten Report herunterladen“*  <img src="/img/erweiterten_report_herunterladen.png" alt="report" style='vertical-align:middle;display:inline;margin:0px 5px; '>
 können Sie einen PDF Report erstellen, in dem alle aktuell angezeigten Alarmvorlagen aufgeführt werden. Haben Sie z.B. mit der Filteroption nur die Alarmvorlagen erstellt am 1.1.2018 angezeigt 
und klicken auf *„Report herunterladen“*, werden auch nur diese Vorlagen im Report aufgeführt.




<a name="neue_alarmvorlage_anlegen"></a>
### Neue Alarmvorlage anlegen 

Es gibt verschiedene Möglichkeiten, eine neue Alarmvorlage anzulegen:

 - Im Register **„Mutieren“** im Menü „Organigramm/Baumansicht“ klicken Sie in der rechten Spalte unter „Verfügbar“ auf „Neue Vorlage“
 ![](/img/zusatzmodule_alarmvorlage_anlegen1.png?classes=shadow)
 Damit gelangen Sie in die Teilnehmerliste, weiter im nächsten Stichpunkt
 
 - Im Register **„Mutieren“** im Menü „Teilnehmerliste“ fügen Sie die gewünschten Teilnehmer per Drag&Drop oder Doppelklick
 der rechten Spalte hinzu und klicken auf „Alarmvorlage erstellen“
 ![](/img/zusatzmodule_alarmvorlage_anlegen2.png?width=700px&classes=shadow) 
 
 - Im Register **„Mutieren“** im Menü „Zusatzmodule“, „Alarmvorlagen verwalten“ mit der Schaltfläche „Neue Alarmvorlage anlegen“<img src="/img/zusatzmodule_alarmvorlage_anlegen3.png" alt="lösch" style='vertical-align:middle;display:inline;margin:0px 5px; '>
 Damit gelangen Sie in die bereits bekannte Alarmmaske. Hier können Sie Wurzeln, Gruppen und Teilnehmer per Drag&Drop oder Doppelklick in die rechte Spalte schieben. Klicken Sie dann auf „Alarmvorlage erstellen“
 ![](/img/zusatzmodule_alarmvorlage_anlegen4.png?width=700px&classes=shadow)
 
  
  
  
Mit allen Optionen gelangen Sie ins Menü „Alarmvorlage erstellen“. Ähnlich wie im Abschnitt [„Alarm erstellen“](/de/alarmieren/alarm/) legen Sie
hier die Details des Alarms fest. Speichern Sie zum Abschluss ihre Alarmvorlage mit der Schaltfläche „Alarm als Vorlage speichern“.


<a name="allgemein"></a>
#### Allgemein

Im Reiter „Allgemein“ legen Sie Auslösecode und Alarmname fest sowie optional eine Beschreibung des Alarms.
Die Funktion „Auslöseberechtigt“ können Sie erst nach Erstellen der Vorlage bearbeiten.
![](/img/zusatzmodule_alarmvorlage_erstellen1.png?classes=shadow)


<a name="teilnehmer"></a>
#### Teilnehmer

Hier werden die Teilnehmer aufgelistet. Sie können Teilnehmer mit dem Löschsymbol
<img src="/img/loesch-icon.png" alt="lösch" style='vertical-align:middle;display:inline;margin:0px 5px; '> wieder entfernen.
![](/img/zusatzmodule_alarmvorlage_erstellen2.png?classes=shadow)



<a name="text"></a>
#### Text

Unter allen verfügbaren Texten, also vordefinierte Texte sowie Freitext wählen Sie mit dem Radiobutton <img src="/img/auswahl_rund.png" alt="radiobutton" style='vertical-align:middle;display:inline;margin:0px 5px; '>
einen Standardtext aus. Mit den Checkboxes <img src="/img/auswahl_eckig.png" alt="checkbox" style='vertical-align:middle;display:inline;margin:0px 5px; '>
können Sie alternative Texte auswählen, die bei der Alarmauslösung in die engere Auswahl kommen.  
Im folgenden Screenshot wurde z.B. der Freitext „Test“ als Standardtext ausgewählt und der vordefinierte Alarmtext „Alarm“ als Alternative.
Löst man hinterher die Alarmvorlage aus, werden die ausgewählten Texte im Menü „Text“ angezeigt, wobei der Standardtext (in diesem
Fall „Test“) vorselektiert ist.

![](/img/zusatzmodule_alarmvorlage_erstellen3.png?width=700px&classes=shadow)



<a name="koordinaten"></a>
#### Koordinaten

Analog zum Erstellen eines Alarms können Sie hier entscheiden, ob Sie Koordinaten übermitteln wollen. Sie können eine Adresse angeben und mit 
der Enter-Taste bestätigen, diese wird automatisch in das WGS84-Format umgewandelt, oder direkt Koordinaten angeben.



<a name="alarmoptionen"></a>
#### Alarmoptionen

Analog zum Erstellen eines Alarms legen Sie hier fest, welche Mittel alarmiert werden sollen, ob ein Abbruch nach einer bestimmten Anzahl Quittierungen 
erfolgen soll oder ob ein Info-Versand getätigt werden soll. 



<a name="versandzeit"></a>
#### Versandzeit

Hier legen Sie fest, ob ein Alarm sofort versendet werden soll oder für einen späteren Zeitpunk disponiert werden soll.
 


 
 
<a name="alarmvorlage_ausloesen"></a> 
### Alarmvorlage auslösen

Um eine Alarmvorlage auszulösen, wählen Sie im Register **„Alarmieren“** aus der Spalte „Vorlagen“ die gewünschte Vorlage aus. Eventuell
müssen Sie die angezeigten Spalten in dem Dropdown-Menü noch anpassen. 

 ![](/img/zusatzmodule_alarmvorlage_dropdown.png?classes=shadow)
 
Per Drag&Drop, Doppelklick oder der Schaltfläche „Auswahl übernehmen“ fügen Sie die Vorlage der Teilnehmerliste auf der rechten Seite hinzu.
Mit einem Klick auf „Alarm“ gelangen Sie in das bereits bekannte Menü „Alarm erstellen“. Dort können Sie den Alarm direkt mit seinen vordefinierten Attributen auslösen, aber auch Optionen anpassen (z.B. Koordinaten ändern, 
Einheiten bearbeiten)

![](/img/zusatzmodule_alarmvorlage_ausloesen.png?width=800px&classes=shadow)

<a name="teilnehmer_nachtraeglich_hinzufuegen"></a>
### Teilnehmer nachträglich hinzufügen

Es ist auch möglich, nachträglich Teilnehmer einer Alarmvorlage zuzuordnen. Wählen Sie dazu im Register **„Mutieren“** im Menü „Teilnehmerliste“ die gewünschten Teilnehmer aus und fügen sie per Drag&Drop, Doppelklick oder der Schaltfläche
„Auswahl übernehmen“ zu der Spalte „Teilnehmer“ am rechten Rand hinzu. Mit der Schaltfläche „Alarmvorlage aktualisieren“ bestätigen Sie Ihre Auswahl.

 ![](/img/zusatzmodule_alarmvorlage_teilnehmer_hinzufuegen.png?width=700px&classes=shadow)
 
 Im nachfolgenden Menü „Alarmvorlage aktualisieren“ können Sie im Dropdown-Menü die Alarmvorlage auswählen, zu der Sie die
 Teilnehmer hinzufügen wollen.
 ![](/img/zusatzmodule_alarmvorlage_aktualisieren.png?classes=shadow)
 
 Bestätigen Sie mit einem Klick auf *„übernehmen“*.
 
 




































