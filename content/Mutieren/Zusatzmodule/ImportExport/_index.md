+++
title = "Import/Export"
weigth = 6
alwaysopen = false
+++


Im Menü „Im-/Export“ können Sie verschiedene Datenbanken und Teilnehmerdaten exportieren, bearbeiten und importieren.  


![](/img/mutieren_zusatzmodule_imexport.png?classes=shadow)

### Export/Verfügbare Reports

Unter „Verfügbare Reports“ können Sie verschiedene Datensätze als CSV Datei herunterladen, archivieren, verschicken und 
bei Bedarf bearbeiten. CSV Dateien öffnen Sie dabei in der Regel mit Excel. Im Menüpunkt [„Export“](/de/mutieren/zusatzmodule/importexport/export/) werden die einzelnen Reports und 
was zu beachten ist, erklärt.


### Import/Datenbank Import


Der Import erlaubt, die zuvor exportierten und dann mutierten Datensätze wieder in das System zu importieren. 
Der Import ist primär für einen manuellen „Erstimport“ ausgelegt.

**Aktualisieren über den Import:** Jeder Datensatz enthält einen
eindeutigen Schlüssel (ID), der pro Kunde nur einmal vergeben werden
darf. Ist die ID in der bestehenden Datenbank bereits vorhanden, werden
die entsprechenden Daten mit den neuen überschrieben; es findet also ein
Update statt.

**Löschen über den Import:** Über den Import können Einträge gelöscht
werden! Ist die ID eines Datensatzes in einem erneuten Import nicht mehr
vorhanden, so wird der dazugehörige Datensatz gelöscht.



### Beispiel: Anlegen eines neuen Teilnehmers

Zur Verdeutlichung des Export/Import Prozesses folgt nun beispielhaft das Anlegen eines neuen Teilnehmers:

 1. Speichern und Öffnen der Datei „import.cvs“ über den [dynamischen Export](/mutieren/zusatzmodule/importexport/export/#dynamischer-export) ![](/img/mutieren_zusatzmodule_imexport_demo1.png?classes=shadow&width=1000px)

 2. Anlegen des neuen Teilnehmers „Karl Koch“, mit Adresse, einigen Kontaktdaten, Schuhgröße, Führerscheinklasse sowie als Sprache Französisch. Beachten Sie hier die festgelegten Konventionen.

	![](/img/mutieren_zusatzmodule_imexport_demo2.png?classes=shadow&width=1000px)
    
	Speichern Sie anschließend die Datei. Eventuell warnt ein Popup-Fenster davor „einige Features der Arbeitsmappe gehen
	möglicherweise verloren“. Bestätigen Sie trotzdem die Verwendung des Formats mit „Ja“.
	
 3.  Importieren der Datei über den [dynamischen Import](/mutieren/zusatzmodule/importexport/import/#dynamischer-Import). Klicken Sie hierzu auf „Dateien auswählen“, navigieren Sie zu dem Speicherort der Datei und wählen diese aus. Klicken Sie anschließend auf 
 „Übertragen“. 
 
	![](/img/mutieren_zusatzmodule_imexport_demo3.png?classes=shadow)
 
 4. In der Teilnehmerliste können Sie nun den neuen Eintrag sehen. 
 
	![](/img/mutieren_zusatzmodule_imexport_demo4.png?classes=shadow&width=1000px)


