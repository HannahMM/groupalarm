+++
title = "Serielle vertikale Eskalation"
weight = 6
+++


### Serielle vertikale Eskalation (serielle Alarmierung) 



Es besteht die Möglichkeit, Ordner seriell vertikal alarmieren zu
lassen.

Üblicherweise werden Teilnehmer (bei mehr als zwei) gleichzeitig
alarmiert. Dabei wird immer das erste definierte Alarmierungsmittel
alarmiert, dann das zweite und so weiter.

Dies gilt jedoch nicht für die serielle vertikale Eskalation.

Der Grundgedanke dahinter ist, dass ein Teilnehmer vollständig über alle
festgelegten Alarmierungsmittel alarmiert wird, bevor der Alarm zum
nächsten Teilnehmer übergeht. Bestätigt jedoch der erste Teilnehmer eine
Alarmierung positiv, wird der nächste Teilnehmer **NICHT** mehr
alarmiert. Bestätigt der erste Teilnehmer die Alarmierung hingegen
negativ, wird der nächsten Teilnehmer alarmiert. Der Alarm geht auch zum
zweiten Teilnehmer über falls der erste Teilnehmer keines seiner
Alarmierungsmittel bestätigt.

Gehen Sie hierzu im Register **„Mutieren“** in das Menü **„Organigramm / Baumansicht“.**
Klicken Sie auf das Bearbeitungs-Icon <img src="/img/bearbeitungsicon.png" alt="edit" style='vertical-align:middle;display:inline;margin:0px 5px; '>
der gewünschten Gruppe (in dieser dürfen nur Teilnehmer gespeichert sein, 
keine Vorlagen, Zeitsteuerungen etc.).
Im Bereich „Name“ ändern Sie nun den Typ des Ordners auf **„seriell vertikal“**(standardmäßig steht dieser auf „default“).

![](/img/serielle_vertikale_eskalation.png?classes=shadow)

Bestätigen Sie die Änderung mit der Schaltfläche „speichern“. Im Organigramm wird der Ordner nun mit einem Pfeilsymbol angezeigt <img src="/img/serielle_vertikale_eskalation_symbol.png" alt="edit" style='vertical-align:middle;display:inline;margin:0px 5px; '>.

Sortieren Sie in diesem Ordner die Teilnehmer per Drag & Drop nach der gewünschten Alarmierungs-Reihenfolge.




