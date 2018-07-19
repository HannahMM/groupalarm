+++
title = "Fernauslösung"
weight = 4
+++


GroupAlarm pro unterstützt neben der Auslösung über die Web-Oberfläche mehrere Arten der Fernauslösung. So können Sie entweder per Anruf oder SMS eine zuvor definierte Alarmvorlage, Konferenzvorlage oder Drehbuch auslösen.

### Auslösung per SMS


Um eine Vorlage per SMS auszulösen, müssen Sie eine SMS mit festgelegter Syntax an eine festgelegte Auslösenummer senden. Diese wird jedem Kunden individuell bei Übergabe des Accounts mitgeteilt.

**Wichtig**: Damit die Auslösung per SMS funktioniert, muss die Absendernummer im Menü [Grundeinstellungen](/admin/grundeinstellungen/) unter „Auslöseberechtigt“ gespeichert sein.

Der Inhalt der Auslöse-SMS muss folgender Syntax folgen:
**PIN @xyz TEXT**

 - **PIN:** Die 4-stellige PIN muss mit der in den Grundeinstellungen hinterlegten Auslöse-PIN korrespondieren


 - **@:** Steht für den auszulösenden Einheitstyp:
 
	- „#“ (Raute/Hash)        =     Alarmvorlage 
	- „*“ (Stern/Star)        =       Drehbuch 
	- „!“ (Ausrufezeichen)     =  Konferenzvorlage


 - **xyz:** steht für den jeweiligen Auslösecode der gewählten Einheit.

 - **TEXT:** Beliebiger Alarmtext. Wird dieser Parameter leer gelassen, wird der Alarmtext aus der Vorlage verwendet
 
**Wichtig**: Beachten Sie die Leerzeichen zwischen PIN, Einheitstyp + Auslösecode und Alarmtext
 
Um beispielsweise die Alarmvorlage mit Auslösecode 1 und dem Alarmtext „Test“ auszulösen, senden Sie folgende SMS (1234 entspricht hier der Auslöse-PIN):

![](/img/admin_grundeinstellungen_ausloese_sms.png?width=300px&classes=shadow)



#### Bestätigung per SMS

Standardmäßig wird eine Auslösung per SMS mit einer Antwort-SMS an die
auslösende Nummer bestätigt. Dies kann durch den Master-User bei Bedarf in
der Admin Registry unterdrückt werden, indem der Key „Suppress SMS
Reply“ mit einer 1 aktiviert wird.

Die Bestätigung kann sowohl positiv ausfallen (OK) als auch negativ
(NOT\_OK), wenn aufgrund fehlender oder falscher Informationen der Alarm
nicht ausgelöst werden konnte. Details zu einem auffälligen Fehler sind
in englischer Sprache ebenfalls in der SMS enthalten.


### Auslösung per Anruf mit DTMF-Menü

Bei  der  Auslösung  per  Anruf  mit  DTMF-Menü  wird  der  Anrufer  durch  ein  Sprachmenü  geführt,  in dem er Schritt  für  Schritt  angeleitet  wird,  die  nötigen  Eingaben  über  die  Telefontastatur  zu  machen,  um  eine 
Vorlage auszulösen. Die Auslöseberechtigung wird entweder über die Absendernummer oder anhand der 6-stelligen Syspin in Kombination mit der 4-stelligen PIN (siehe Auslösung per SMS) sichergestellt. 
Sie finden beide Nummern im Menü [Grundeinstellungen](/admin/grundeinstellungen/).

#### Ablauf 

Wählen Sie die {{< button >}} 0241 98099000 {{< /button >}}. Folgen Sie anschließend den Anweisungen der Sprachansage:

 1. Sprache wählen
 2. 4-stellige Auslöse-PIN eingeben
 3. 6-stellige Syspin eingeben (nur wenn die Absendernummer nicht berechtigt ist!)
 4. Auszulösenden Einheitstyp wählen (Alarmvorlage, Drehbuch oder Konferenzvorlage)
 5. Auslösecode eingeben und mit der Raute-Taste abschließen

 
### Auslösung per Durchwahl-Anruf

Die  Auslösung  per  Durchwahl-Anruf  erlaubt  die  direkte  Auslösung  einer Vorlage  (Alarmvorlage,  Drehbuch,    Konferenzvorlage)    ohne    Umwege    über  ein    DTMF-Menü    oder    andere    Abfragen.    Die Auslöseberechtigung  wird  hierfür  über  eine
eindeutige  Kombination  aus  Absender-  und  Zielnummer  sichergestellt.

Die Auslösung per Durchwahl wird direkt in den Einstellungen der entsprechenden Vorlagen ([Alarmvorlage](/mutieren/zusatzmodule/alarmvorlagen-verwalten/#allgemein), [Konferenzvorlage](/mutieren/zusatzmodule/konferenzvorlagen-verwalten/#konferenzvorlage-bearbeiten), [Drehbuch](/mutieren/zusatzmodule/drehbuecher-verwalten/#allgemein)) konfiguriert. 

Legen Sie dazu im Menüpunkt „Auslöseberechtigt“ der jeweiligen Vorlage einen neuen Eintrag an.

![](/img/alarmieren_fernausloese_durchwahl.png?classes=shadow)

 - **Nummer**: Die Telefonnummer des Auslöseberechtigten. Beachten Sie das vom System festgelegte Format.
 - **Durchwahl**: Liste von 200 möglichen Durchwahlnummern. Wählen Sie eine Zielnummer aus, um eine eindeutige Zuordnung zu ermöglichen.
 - **Name**: Dient der besseren Lesbarkeit
 
#### Ablauf

Mit   einem   Anruf   auf   die   definierte   Zielnummer wird  überprüft, ob die    Absendernummer für diese als auslöseberechtigt hinterlegt ist. Wenn ja, wird die
entsprechende  Einheit  ausgelöst,  ohne  dass  zusätzlich  Abfragen  wie  PIN  oder  Bestätigungen  abgefragt werden. Die erfolgreiche Auslösung wird dem Anrufer über den Sprachkanal als „Alarmierung abgesendet“ signalisiert.  





















