+++
title = "Konferenzvorlagen verwalten (optionales Modul)"
weight = 4
+++
<!--
### Inhaltsverzeichnis

- [Konferenzvorlagen](#konferenzvorlagen)
	- [Funktionen](#funktionen)
- [Neue Konferenzvorlage anlegen](#neue_konferenzvorlage_anlegen)
- [Konferenzvorlage auslösen](#konferenzvorlage_ausloesen)
- [Teilnehmer nachträglich hinzufügen](#teilnehmer_nachtraeglich_hinzufuegen)


-->



<a name="konferenzvorlage"></a>
### Konferenzvorlagen

Konferenzvorlagen sind vordefinierte Konferenzen. Das bedeutet, der Teilnehmerkreis und die Alarmmittel sind bereits vordefiniert. 
Im Ernstfall kann bei der Alarmierung die vorher erfasste Konferenzvorlage ausgelöst werden und die definierten Alarmteilnehmer werden über die entsprechenden Mittel für Telefonkonferenzen angerufen.  

Im Menü **„Konferenzvorlagen“** werden Ihre vorhandenen Konferenzvorlagen aufgelistet. Sie können die Vorlagen nach Konferenzname, Auslösecode, 
Beschreibung, Zeitpunkt der letzen Bearbeitung und Disponent filtern. Geben Sie dazu die gewünschten Filterkriterien in die Filterleiste ein 
und bestätigen Sie mit Klick auf das Filtersymbol 
<img src="/img/filtersymbol.png" alt="filter" style='vertical-align:middle;display:inline;margin:0px 5px; '>

![](/img/zusatzmodule_konferenzvorlagen.png?classes=shadow)



<a name="funktionen"></a>
#### Funktionen

Folgene Funktionen stehen zur Verfügung

 - **Bearbeiten** <img src="/img/bearbeitungsicon.png" alt="bearbeiten" style='vertical-align:middle;display:inline;margin:0px 5px; '> : 
 Bearbeiten einer vorhandenen Konferenz. Mehr Informationen im Abschnitt [Neue Konferenzvorlage anlegen](#neue_konferenzvorlage_anlegen).
 
 - **Vorlage sperren** <img src="/img/schlosssymbol.png" alt="schloss" style='vertical-align:middle;display:inline;margin:0px 5px; '> : 
 Option, eine Konferenzvorlage zu sperren. Unberechtigte Personen können eine gesperrte Vorlage weder bearbeiten noch löschen, aber weiterhin auslösen. Entsperrt werden kann eine Vorlage nur vom Autor oder einem Superuser.
 ![](/img/zusatzmodule_alarmvorlage_sperren.png?classes=shdadow)
 
 - **Report als PDF herunterladen** <img src="/img/pdfsymbol.png" alt="pdf" style='vertical-align:middle;display:inline;margin:0px 5px; '> : Erstellt einen Report im PDF Format über die Konferenzvorlage. 
 Hier werden Ersteller, Konferenzname und Beschreibung, sowie die Teilnehmer aufgelistet und weitere Optionen aufgeführt.
 
 
 - **Erweiterten Report als PDF herunterladen**<img src="/img/erweitertpdfsymbol.png" alt="pdf" style='vertical-align:middle;display:inline;margin:0px 5px; '>: Erstellt zusätzlich zu den 
 Informationen des normalen Reports noch eine detaillierte Liste der Teilnehmer mit Profilen und Alarmmitteln.
 
 - **Löschen**<img src="/img/loesch-icon.png" alt="lösch" style='vertical-align:middle;display:inline;margin:0px 5px; '>: Löschen der Konferenzvorlagevorlage.
 
 - **Kopieren**<img src="/img/kopiersymbol.png" alt="lösch" style='vertical-align:middle;display:inline;margin:0px 5px; '>: Erstellt eine Kopie mit Zusatz „copy“ der Konferenzvorlagevorlage, übernimmt dabei alle Datensätze aber verteilt neuen Auslösecode
 ![](/img/zusatzmodule_konferenzvorlagen_kopieren.png?classes=shadow)
 
 
 
Mit der Schaltfläche *„Report herunterladen“* <img src="/img/report_herunterladen.png" alt="report" style='vertical-align:middle;display:inline;margin:0px 5px; '>
 bzw. *„erweiterten Report herunterladen“*  <img src="/img/erweiterten_report_herunterladen.png" alt="report" style='vertical-align:middle;display:inline;margin:0px 5px; '>
 können Sie einen PDF Report erstellen, in dem alle aktuell angezeigten Konferenzvorlagen aufgeführt werden. Haben Sie z.B. mit der Filteroption nur die Konferenzvorlagen erstellt am 1.1.2018 angezeigt 
und klicken auf *„Report herunterladen“*, werden auch nur diese Vorlagen im Report aufgeführt.



<a name="neue_konferenzvorlage_anlegen"></a>
### Neue Konferenzvorlage anlegen

Es gibt verschiedene Möglichkeiten, eine neue Konferenzvorlage anzulegen:

 
 - Im Register **„Mutieren“** im Menü „Teilnehmerliste“ fügen Sie die gewünschten Teilnehmer per Drag&Drop oder Doppelklick
 der rechten Spalte hinzu und klicken auf Konferenzvorlage erstellen“
 ![](/img/zusatzmodule_konferenzvorlagen_anlegen1.png?width=700px&classes=shadow) 
 
 - Im Register **„Mutieren“** im Menü „Zusatzmodule“, „Alarmvorlagen verwalten“ mit der Schaltfläche „Neue Konferenzvorlage anlegen“<img src="/img/zusatzmodule_konferenzvorlagen_anlegen2.png" alt="konf" style='vertical-align:middle;display:inline;margin:0px 5px; '>
 Damit gelangen Sie in die bereits bekannte Alarmmaske. Hier können Sie Wurzeln, Gruppen und Teilnehmer per Drag&Drop oder Doppelklick in die rechte Spalte schieben. Klicken Sie dann auf „Konferenzvorlage erstellen“
 ![](/img/zusatzmodule_konferenzvorlagen_anlegen3.png?width=700px&classes=shadow)
 

   
   
Mit beiden Optionen gelangen Sie ins Menü „Konferenzvorlage erstellen“. Hier legen Sie den Namen der Vorlage und Auslösecode fest, sowie optional eine Beschreibung der Konferenz. Die folgenden Optionen können Sie 
per Checkbox auswählen:


 -  **Auslöser in Konferenz aufnehmen:** Dabei wird der
    Konferenzauslöser in die Telefonkonferenz aufgenommen. Dies ist aber
    nicht möglich, wenn die Konferenzauslösung z.B. per Weblink erfolgt.

    

 -  **“First Responder“-Konferenz:** Dabei werden alle der in die
    Konferenzvorlage aufgenommenen Teilnehmer angerufen, die Konferenz
    wird aber nur mit demjenigen stattfinden, der den Anruf als
    Erster entgegennimmt. Alle anderen Teilnehmer erhalten eine Absage.
	
 ![](/img/zusatzmodule_konferenzvorlagen_erstellen.png?classes=shadow)
Im unteren Bereich der Anzeige werden die Teilnehmer aufgelistet.  
Speichern Sie am Ende Ihre Vorlage mit der Schaltfläche „Konferenzvorlage speichern“.



<a name="konferenzvorlage_ausloesen"></a>
### Konferenzvorlage auslösen


Um eine Konferenzvorlage auszulösen, wählen Sie im Register **„Alarmieren“** aus der Spalte „Vorlagen“ die gewünschte Vorlage aus. Eventuell
müssen Sie die angezeigten Spalten in dem Dropdown-Menü noch anpassen. 

 ![](/img/zusatzmodule_konferenzvorlagen_dropdown.png?classes=shadow)
 
Per Drag&Drop, Doppelklick oder der Schaltfläche „Auswahl übernehmen“ fügen Sie die Vorlage der Teilnehmerliste auf der rechten Seite hinzu.
Mit einem Klick auf „Telefonkonferenz“ gelangen Sie in das bereits bekannte Menü „Telefonkonferenz“. Dort können Sie die Konferenz direkt mit den vordefinierten Attributen auslösen, aber auch Optionen anpassen (z.B. Konferenzmittel deaktivieren)

![](/img/zusatzmodule_konferenzvorlagen_ausloesen.png?width=800px&classes=shadow)


<a name="teilnehmer_nachtraeglich_hinzufuegen"></a>
### Teilnehmer nachträglich hinzufügen

Es ist auch möglich, nachträglich Teilnehmer einer Konferenzvorlage zuzuordnen. Wählen Sie dazu im Register **„Mutieren“** im Menü „Teilnehmerliste“ die gewünschten Teilnehmer aus und fügen sie per Drag&Drop, Doppelklick oder der Schaltfläche
„Auswahl übernehmen“ zu der Spalte „Teilnehmer“ am rechten Rand hinzu. Mit der Schaltfläche „Konferenzvorlage aktualisieren“ bestätigen Sie Ihre Auswahl.

 ![](/img/zusatzmodule_konferenzvorlagen_teilnehmer_hinzufuegen.png?width=700px&classes=shadow)
 
 Im nachfolgenden Menü „Konferenzvorlage aktualisieren“ können Sie im Dropdown-Menü die Alarmvorlage auswählen, zu der Sie die
 Teilnehmer hinzufügen wollen.
 ![](/img/zusatzmodule_konferenzvorlagen_aktualisieren.png?classes=shadow)
 
 Bestätigen Sie mit einem Klick auf *„übernehmen“*.


