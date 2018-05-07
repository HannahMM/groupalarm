+++
title = "Konferenzvorlagen verwalten"
weight = 4
+++



<a name="konferenzvorlage"></a>
### Konferenzvorlagen

Konferenzvorlagen sind vordefinierte Konferenzen. Das bedeutet, der Teilnehmerkreis und die Alarmmittel sind bereits festgelegt. 
Im Ernstfall kann bei der Alarmierung die vorher erfasste Konferenzvorlage ausgelöst werden und die definierten Alarmteilnehmer werden über die entsprechenden Mittel für Telefonkonferenzen angerufen.  

Im Menü **„Konferenzvorlagen“** werden Ihre vorhandenen Konferenzvorlagen aufgelistet. Sie können die Vorlagen nach Konferenzname, Auslösecode, 
Beschreibung, Zeitpunkt der letzten Bearbeitung und Disponent filtern. Geben Sie dazu die gewünschten Filterkriterien in die Filterleiste ein 
und bestätigen Sie mit Klick auf das Filtersymbol 
<img src="/img/filtersymbol.png" alt="filter" style='vertical-align:middle;display:inline;margin:0px 5px; '>

![](/img/mutieren_zusatzmodule_konferenzvorlagen.png?classes=shadow)



<a name="funktionen"></a>
#### Funktionen

Folgende Funktionen stehen zur Verfügung

 - **Bearbeiten** <img src="/img/bearbeitungsicon.png" alt="bearbeiten" style='vertical-align:middle;display:inline;margin:0px 5px; '> : 
 Bearbeiten einer vorhandenen Konferenz. Mehr Informationen im Abschnitt [Konferenzvorlage bearbeiten](#konferenzvorlage-bearbeiten).
 
 - **Vorlage sperren** <img src="/img/schlosssymbol.png" alt="schloss" style='vertical-align:middle;display:inline;margin:0px 5px; '> : 
 Option, eine Konferenzvorlage zu sperren. Unberechtigte Personen können eine gesperrte Vorlage weder bearbeiten noch löschen, aber weiterhin auslösen. Entsperrt werden kann eine Vorlage nur vom Ersteller oder dem Superuser.
 ![](/img/mutieren_zusatzmodule_konferenzvorlagen_funktionen_sperren.png?classes=shdadow)
 
 - **Report als PDF herunterladen** <img src="/img/pdfsymbol.png" alt="pdf" style='vertical-align:middle;display:inline;margin:0px 5px; '> : Erstellt einen Report im PDF Format über die Konferenzvorlage. 
 Hier werden Ersteller, Konferenzname und Beschreibung, sowie die Teilnehmer aufgelistet und weitere Optionen aufgeführt.
 ![](/img/mutieren_zusatzmodule_konferenzvorlagen_funktionen_pdf.png?classes=shdadow&width=800px)
 
 - **Löschen**<img src="/img/loesch-icon.png" alt="lösch" style='vertical-align:middle;display:inline;margin:0px 5px; '>: Löschen der Konferenzvorlagevorlage.
 
 - **Kopieren**<img src="/img/kopiersymbol.png" alt="lösch" style='vertical-align:middle;display:inline;margin:0px 5px; '>: Erstellt eine Kopie mit Zusatz „copy“ der Konferenzvorlagevorlage, übernimmt dabei alle Datensätze aber verteilt neuen Auslösecode
 ![](/img/mutieren_zusatzmodule_konferenzvorlagen_kopieren.png?classes=shadow)
 
 
 
Mit der Schaltfläche *„Report herunterladen“* <img src="/img/mutieren_zusatzmodule_konferenzvorlagen_report.png" alt="report" style='vertical-align:middle;display:inline;margin:0px 5px; '>
 können Sie einen PDF Report erstellen, in dem alle aktuell angezeigten Konferenzvorlagen aufgeführt werden. Haben Sie z.B. mit der Filteroption nur die Konferenzvorlagen erstellt am 1.1.2018 angezeigt 
und klicken auf *„Report herunterladen“*, werden auch nur diese Vorlagen im Report aufgeführt.



<a name="neue_konferenzvorlage_anlegen"></a>
### Neue Konferenzvorlage anlegen

Es gibt verschiedene Möglichkeiten, eine neue Konferenzvorlage anzulegen:

 
 1. Im Register **„Mutieren“** im Menü „Teilnehmerliste“ fügen Sie die gewünschten Gruppen per Drag & Drop oder Doppelklick
 der rechten Spalte hinzu und klicken auf Konferenzvorlage erstellen“
 ![](/img/mutieren_zusatzmodule_konferenzvorlagen_neue_vorlage1.png?width=1000px&classes=shadow) 
 
 2. Im Register **„Mutieren“** im Menü „Zusatzmodule“, „Alarmvorlagen verwalten“ mit der Schaltfläche „Neue Konferenzvorlage anlegen“
 <img src="/img/mutieren_zusatzmodule_konferenzvorlagen_neue_konferenzvorlage_anlegen.png" alt="konf" style='vertical-align:middle;display:inline;margin:0px 5px; '>
 Damit gelangen Sie in die bereits bekannte Alarmmaske. Hier können Sie Gruppen per Drag & Drop oder Doppelklick in die rechte Spalte schieben. Klicken Sie dann auf „Konferenzvorlage erstellen“
 ![](/img/mutieren_zusatzmodule_konferenzvorlagen_neue_vorlage2.png?width=1000px&classes=shadow)
 

   
   
Mit beiden Optionen gelangen Sie ins Menü „Konferenzvorlage erstellen“. Hier legen Sie den Namen der Vorlage und Auslösecode fest, sowie optional eine Beschreibung der Konferenz. Die folgenden Optionen können Sie 
per Checkbox auswählen:

![](/img/mutieren_zusatzmodule_konferenzvorlagen_erstellen.png?classes=shadow)
 
 -  **Auslöser in Konferenz aufnehmen:** Dabei wird der
    Konferenzauslöser in die Telefonkonferenz aufgenommen. Dies ist aber
    nicht möglich, wenn die Konferenzauslösung z.B. per Weblink erfolgt.

    

 -  **“First Responder“-Konferenz:** Dabei werden alle der in die
    Konferenzvorlage aufgenommenen Teilnehmer angerufen, die Konferenz
    wird aber nur mit demjenigen stattfinden, der den Anruf als
    Erster entgegennimmt. Alle anderen Teilnehmer erhalten einen Hinweistext „Diese Konferenz ist gesperrt“
	und wissen somit, dass der erste Teilnehmer bereits mit dem Anrufenden in Kontakt ist.
	
Die Funktion „Auslöseberechtigt“ können Sie erst nach Erstellen der Vorlage bearbeiten (Optionales Modul). 
Die Funktion „Auslöseberechtigt“ können Sie erst nach Erstellen der Vorlage bearbeiten (Optionales Modul). Legen Sie hier Name und Nummer der Personen fest, die berechtigt sind, die Konferenzvorlage per 
[Durchwahl](/alarmieren/fernausloese/#auslöse-per-durchwahl-anruf) auszulösen.

![](/img/mutieren_zusatzmodule_konferenzvorlagen_erstellen_ausloeseberechtigt.png?classes=shadow)

Im unteren Bereich der Anzeige werden die Gruppen aufgelistet.  
Speichern Sie am Ende Ihre Vorlage mit der Schaltfläche „Konferenzvorlage speichern“.



<a name="konferenzvorlage_ausloesen"></a>
### Konferenzvorlage auslösen


Um eine Konferenzvorlage auszulösen, wählen Sie im Register **„Alarmieren“** aus der Spalte „Vorlagen“ die gewünschte Vorlage aus. Eventuell
müssen Sie die angezeigten Spalten in dem Dropdown-Menü noch anpassen. 

 ![](/img/mutieren_zusatzmodule_konferenzvorlagen_dropdown.png?classes=shadow)
 
Per Drag & Drop, Doppelklick oder der Schaltfläche „Auswahl übernehmen“ fügen Sie die Vorlage der Teilnehmerliste auf der rechten Seite hinzu.
Mit einem Klick auf „Telefonkonferenz“ gelangen Sie in das bereits bekannte Menü „Telefonkonferenz“. Dort können Sie die Konferenz direkt mit den vordefinierten Attributen auslösen, aber auch Optionen anpassen (z.B. Konferenzmittel deaktivieren)

![](/img/mutieren_zusatzmodule_konferenzvorlagen_ausloesen.png?width=1000px&classes=shadow)

### Konferenzvorlage bearbeiten

Nachdem eine Konfrenzvorlage erstellt wurde, kann Sie bearbeitet werden. Sie können Name, Beschreibung, Auslösecode, Absendernummer sowie die Optionen ändern.

![](/img/mutieren_zusatzmodule_konferenzvorlagen_bearbeiten.png?classes=shadow)

Erst nach dem erstmaligen Erstellen ist es möglich, auslöseberechtigte Nummern hinzuzufügen. Klicken Sie dazu auf *bearbeiten*, geben Sie Nummer und Name der auslöseberechtigten Person ein und bestätigen Sie mit der Schaltfläche „anlegen“.

![](/img/mutieren_zusatzmodule_konferenzvorlagen_bearbeiten_ausloeseberechtigte.png?classes=shadow)

Haben Sie die Option „Auslöser in Konferenz aufnehmen“ gewählt, können Sie zusätzlich einen Ansage- und Schlusstext festlegen.

Bestätigen Sie die Änderungen mit der Schaltfläche „Konferenzvorlage speichern“


<a name="teilnehmer_nachtraeglich_hinzufuegen"></a>
### Teilnehmer nachträglich hinzufügen

Es ist auch möglich, nachträglich Teilnehmer einer Konferenzvorlage zuzuordnen. Wählen Sie dazu im Register **„Mutieren“** im Menü „Teilnehmerliste“ die gewünschten Teilnehmer aus und fügen sie per Drag&Drop, Doppelklick oder der Schaltfläche
„Auswahl übernehmen“ zu der Spalte „Teilnehmer“ am rechten Rand hinzu. Mit der Schaltfläche „Konferenzvorlage aktualisieren“ bestätigen Sie Ihre Auswahl.

 ![](/img/mutieren_zusatzmodule_konferenzvorlagen_aktualisieren1.png?width=1000px&classes=shadow)
 
 Im nachfolgenden Menü „Konferenzvorlage aktualisieren“ können Sie im Dropdown-Menü die Alarmvorlage auswählen, zu der Sie die
 Teilnehmer hinzufügen wollen.
 ![](/img/mutieren_zusatzmodule_konferenzvorlagen_aktualisieren2.png?classes=shadow)
 
 Bestätigen Sie mit einem Klick auf *„übernehmen“*.


