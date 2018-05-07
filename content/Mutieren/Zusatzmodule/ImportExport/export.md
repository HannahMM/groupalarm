+++
title = "Export"
weight = 1
+++

Um eine Datei herunterzuladen, klicken Sie den entsprechenden Link an und speichern Sie die Datei an einem beliebigen Ort.
Im Anschluss kann die CSV Datei mit einem geeigneten Programm geöffnet werden
 (bei Windows Computern wird der Dateityp automatisch in Excel geöffnet, falls dieses installiert ist).

Sie können den Report auch nur als Textdatei herunterladen. Klicken Sie dazu auf die Schaltfläche „\[Text\]“ hinter dem entsprechenden
Eintrag. Es öffnet sich ein neues Browserfenster mit den Daten.

![](/img/mutieren_zusatzmodule_imexport_export.png?classes=shadow)




### Dynamischer Export

**Dateiname**: import.csv

Ein dynamischer Export steht zum Beispiel zur externen Sicherung von Daten zur Verfügung.
Hierbei wird eine vollständige Liste aller Teilnehmer und deren Datenfeldern aufgestellt. 

![](/img/mutieren_zusatzmodule_imexport_export_dynamischer_export.png?classes=shadow)

Alle Standarddaten sowie optionale Datenfelder werden hier aufgelistet. 

Folgende Konventionen sind dabei zu beachten:

- **Sprache**:  1 = Deutsch, 2 = Französisch, 3 = Italienisch,  4 = Englisch

- **Pin**: Ist nur mit dem Modul „Teilnehmer-Identifikation” relevant. In diesem Fall muss dies eine systemübergreifend 
eindeutige 6-stellige Zahl sein. Beim Import kann eine „Wunsch-PIN” definiert werden. Falls diese in GroupAlarm schon vergeben ist,
 wird sie einfach ignoriert; das Datenfeld bleibt dann leer. Ohne das Modul „Teilnehmer-Identifikation” kann das Feld leer gelassen werden. 

- **Login**:  Das Login ist der Schlüssel des Teilnehmerdatensatzes und
gleichzeitig der Benutzername für Mitbenutzer in GroupAlarm . Wenn das Feld
leer gelassen wird, definiert das System selbst einen Schlüssel. Falls
sich der Teilnehmer aber auch in GroupAlarm  einloggen können soll, kann hier
sein Benutzername definiert werden. Der Benutzername muss wie die PIN
systemübergreifend eindeutig sein. Auch hier gilt: Falls der
Benutzername bereits vergeben ist, wird beim Import das Feld ignoriert.
In diesem Fall vergibt das System selbst einen eindeutigen Schlüssel für
den Datensatz.


**HINWEIS:** Telefonnummern, die als privat gekennzeichnet sind, werden
beim Export mit dem Symbol \* gekennzeichnet. Darüber hinaus werden die
letzten vier Ziffern mit X maskiert angezeigt, z.B.: 076407XXXX.
Beim Importieren werden die existierenden Telefonnummern mit neuen
Angaben überschrieben. Daher müssen die privaten Nummern erneut
eingegeben werden!

Telefonnummern, die als Konferenzmittel angekreuzt wurden, werden beim
Export mit dem Rautezeichen \# gekennzeichnet.


### Optionale Felder pro Teilnehmer

**Dateiname**: import_o.csv

Hierbei werden nur die optionalen Datenfelder exportiert. In den ersten beiden Spalten werden die Teilnehmer mit Login und Name
aufgelistet, darauf folgen die im Admin-Bereich definierten optionalen Datenfelder.

![](/img/mutieren_zusatzmodule_imexport_export_optionale_felder_pro_teilnehmer.png?classes=shadow)

{{% panel theme="info" header="Wichtig!" %}}Die Titel in der CSV Datei dürfen nicht geändert werden, da ansonsten das System die 
Werte nicht mehr den entsprechenden Zellen in der Datenbank zuordnen kann. Falls die Notwendigkeit besteht, 
an den angelegten optionalen Feldern etwas zu ändern oder diese zu ergänzen, nehmen Sie dies im [Admin-Bereich](/admin/datenfelder/) vor {{% /panel %}}


### Gruppen

**Dateiname**: import_e.csv

Hierbei werden alle Gruppen mit zugehöriger ID und Name exportiert. **LID** bezeichnet hier den Schlüssel für die Gruppen. Der Schlüssel beginnt bei 1 und
wird hochgezählt. 

![](/img/mutieren_zusatzmodule_imexport_export_gruppen.png?classes=shadow)



### Gruppen mit Einsatzplänen 

**Dateiname**: import_ec.csv

Haben Sie im Admin-Bereich [Einsatzpläne](/admin/einsatzplaene/) erstellt und diese Gruppen zugeordnet, können Sie diese Zuordnung hier exportieren.

![](/img/mutieren_zusatzmodule_imexport_export_gruppen_mit_einsatzplaenen.png?classes=shadow)

 - **Gruppen_ID und Gruppen_Name**: Schlüssel (Gruppen_ID entspricht der LID) und Name der entsprechenden Gruppen
 - **Einsatzplan_ID und Einsatzplan_Name**: Nummer und Name des zugehörigen Plans


### Gruppen in Zeitsteuerungen 


**Dateiname**: import_c.csv

Haben Sie wie im Abschnitt [Zeitsteuerung verwalten](/mutieren/zusatzmodule/zeitsteuerungen/) Gruppen 
in Zeitsteuerungen eingeteilt, können Sie diese hier exportieren.

![](/img/mutieren_zusatzmodule_imexport_export_gruppen_in_zeitsteuerungen.png?classes=shadow)

 - **CID**: Der Schlüssel für die Zeitsteuerungen. Der Schlüssel beginnt analog zur LID bei 1 und wird hochgezählt.
 - **Steuerung**: Der Name / die Bezeichnung der Zeitsteuerung
 - **LID und Name**: Schlüssel und Name der zugehörigen Gruppen, siehe [Gruppen](/mutieren/zusatzmodule/importexport/verfuegbare_reports/#gruppen)
 Der Name dient hier nur der besseren Lesbarkeit des Exports, beim Import wird dieser Wert ignoriert.

Über die LID können der Zeitsteuerungen Gruppen hinzugefügt werden. Da eine Zeitsteuerung aus mindestens zwei Untergruppen bestehen
 muss, beginnen immer mindestens zwei Zeilen mit derselben CID, nämlich einmal für jede dazugehörige Gruppe,
 die anschliessend über die LID zugewiesen wird. 


### Hierarchiebaum 

**Dateiname**: import_h.csv

Hier können Sie die Baumstruktur Ihrer Organisation, also Wurzeln, Ordner, Zeitsteuerungen etc., als Tabelle exportieren.


![](/img/mutieren_zusatzmodule_imexport_export_hierarchiebaum.png?classes=shadow)

 - **HID**: Der Schlüssel für die Elemente in der Baumstruktur. 
 Der Schlüssel beginnt analog zur LID und CID bei 1 und wird hochgezählt (also 1, 2, 3, 4, 5 usw.). 
 
 - **Wurzel**: In der Tabelle werden die Elemente der Baumstruktur nach Wurzeln sortiert angezeigt. Die Spalte „Wurzel“ numeriert 
  eben diese und gibt jedem untergeordneten Element der Wurzel dessen Nummer.
  
 - **TopID**: Die HID des direkten Vorgängers der Einheit im Baum, d.h. jener Einheit, der die neue direkt untergeordnet ist.
 (Die TopID einer Wurzel ist immer 0!) 
 
 - **Typ**: Beschreibt Art der Einheit: 0 = Wurzeln/Gruppen, 1 = Alarmvorlagen, 2 = Zeitsteuerung
 
 - **LinkID**: Die Schlüssel der jeweiligen Einheiten (für Wurzeln/Ordner LID, für Zeitsteuerung/Alarmvorlagen CID)


{{% panel theme="danger" header="Achtung!" %}}Wurzeln werden erst mit dieser Datei im System angelegt, d.h. die LID der Wurzeln dürfen noch nicht von 
anderen Einheiten (Gruppen) belegt sein. Beispiel: Beim Import der Gruppen haben Sie LIDs von 1 bis 9 vergeben; 
Ihre erste Wurzel hat dann die LinkID 10, die zweite 11 usw. – nur im Falle einer Wurzel wird das Feld Name ausgewertet,
 sonst dient es allein der Lesbarkeit des Exports. {{% /panel %}} 

 - **Name**: Der Name der Einheit
 


![](/img/mutieren_zusatzmodule_imexport_export_hierarchiebaum_beispiel.png?classes=shadow)



### Teilnehmer in Einheiten


**Dateiname**: import_u.csv

Hierbei können Sie exportieren, welchen Gruppen die einzelnen Teilnehmer zugeordnen sind.

![](/img/mutieren_zusatzmodule_imexport_export_teilnehmer_in_einheiten.png?classes=shadow)

 - **LID**: Bezeichnet den Schlüssel der Einheit, welcher der Teilnehmer angehört.

 - **Login**: Der Schlüssel des Teilnehmers

 - **Einheit/Name/Vorname**: Dienen hier nur der besseren Lesbarkeit des Exports; 
 beim Import werden diese Werte ignoriert.
 
 
 
### TTS Ersetzungen 

**Dateiname**: tts.csv

Haben Sie im Admin-Bereich „Text-to-Speech“-Ersetzungen definiert, können Sie diese hier exportieren.

![](/img/mutieren_zusatzmodule_imexport_export_tts.png?classes=shadow)

 - **row_id**: Schlüssel der Textersetzung. Sollen die vorhandenen Daten aktualisiert werden sollen, 
 so ist hier die ID der entsprechenden Zeile anzugeben.  
 - **text**: Der geschriebene Text-to-Speech“-Ersetzungen
 - **newtext**: Der ausgesprochene Text-to-Speech“-Ersetzungen
 - **lang**: Codierung der Sprache: 1 = Deutsch, 2 = Französisch, 3 = Italienisch,  4 = Englisch

### Telefonliste


Hier können Sie eine Liste mit beliebigen Angaben erstellen und exportieren. Wählen Sie dazu in der Spalte links die gewünschten 
Datenfelder aus. Diese sind farblich sortiert nach Standardfeldern, optionalen Feldern, Einheiten und Alarmmitteln. Per Drag&Drop
können Sie die Reihenfolge der Datenfelder nach Ihren Wünschen sortieren. Anschließend können Sie die Liste als PDF 
<img src="/img/mutieren_zusatzmodule_imexport_export_telefonliste_als_pdf_speichern.png" alt="pdf" style='vertical-align:middle;display:inline;margin:0px 5px; '>
oder CSV Datei 
<img src="/img/mutieren_zusatzmodule_imexport_export_telefonliste_als_csv_speichern.png" alt="csv" style='vertical-align:middle;display:inline;margin:0px 5px; '> 
herunterladen oder die Liste als Report speichern 
<img src="/img/mutieren_zusatzmodule_imexport_export_telefonliste_reportvorlage_speichern.png" alt="report" style='vertical-align:middle;display:inline;margin:0px 5px; '>.

![](/img/mutieren_zusatzmodule_imexport_export_telefonliste.png?width=800px&classes=shadow)


Gespeicherte Reporte werden in einer Liste angezeigt und können bearbeitet <img src="/img/bearbeitungsicon.png" alt="edit" style='vertical-align:middle;display:inline;margin:0px 5px; '>, 
gesperrt <img src="/img/schlosssymbol.png" alt="lock" style='vertical-align:middle;display:inline;margin:0px 5px; '> oder gelöscht <img src="/img/loesch-icon.png" alt="del" style='vertical-align:middle;display:inline;margin:0px 5px; '>werden.


![](/img/mutieren_zusatzmodule_imexport_export_telefonliste2.png?classes=shadow)


### Leere Vorlagen

**Dateiname**: import_lv.csv

Mit diesem Export erhalten Sie eine Liste von Vorlagen, die leer sind und daher nicht mehr verwendet werden sollen, z.B. falls die zugeordneten Teilnehmer inzwischen gelöscht wurden. Gerade bei vielen Alarmvorlagen lassen sich so schnell die 
hinfällig gewordenen Vorlagen identifizieren.


![](/img/mutieren_zusatzmodule_imexport_export_leere_vorlagen.png?classes=shadow)

In der Tabelle werden Typ, Name, Auslösecode und Beschreibung der leeren Vorlagen aufgeführt, so dass Sie diese löschen oder bearbeiten können.


