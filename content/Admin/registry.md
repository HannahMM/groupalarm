+++
title = "Registry"
weight = 6
+++



![](/img/admin_registry.png?classes=shadow)

In der Registry können Sie viele detaillierte Konfigurationen vornehmen um GroupAlarm pro nach Ihren Bedürfnissen zu gestalten, z.B. das Verwalten von Mitbenutzer-Rechte, Automatischen Versand von Protokollen, Login-Timeout uvm.

Um einen neuen Eintrag hinzuzufügen, wählen Sie ihn im Dropdown-Menü aus, geben den entsprechenden Wert ein und für welche Nutzer der Eintrag gelten soll und bestätigen  mit „hinzufügen“. Einträge können Sie mit „entfernen“
wieder entfernen.
In der folgenden Tabelle werden die Konfigurationselemente beschrieben sowie deren gültige Werte:
{{% panel theme="info" header="Wichtig!" %}}Durch Komma getrennte Werte müssen zwingend ohne Leerzeichen
eingegeben werden (z.B. de,fr,it).{{% /panel %}}




| Name | Funktion/Beschreibung |  Gültige Werte | Standard  |
|------|------|---|---|
|Add Text Coordinate |Hängt an einen Alarm die Koordinaten an |	0,1 ||
|Alarmsheet (Kundenspezifische Option)|Bezeichnung des Mittelbezeichners der für das Alarmsheet verwendet werden soll|Gültiger Mittelbezeichner|leer|
|Alarmprotokoll|Bezeichnung des Mittelbezeichners der für das Alarmprotokoll verwendet werden soll|Gültiger Mittelbezeichner|leer|
|Alert Number Of Columns(Basismodul) | Anzahl Spalten in der Spaltenansicht(alarmieren) | Zahl zwischen 1 und 4 (mindestens eine Spalte, höchstens vier Spalten)  |  4 |
|Alternative Feedback Text| Alternativer Feedback Text bei SMS Report Versand| 0,1 |
|Always Alert Group Nr (Basismodul)   | Gruppe, die automatisch JEDEM Alarm hinzugefügt wird      | LID einer Gruppe gem. Gruppenexport  | Inaktiv  |
|Auto Advance Alert Deputy Seconds (Basismodul)|Automatische Eskalation zum nächsten Stellvertreter x Sekunden nach einem StV, d.h. x Sekunden, nachdem ein StV ausgelöst wurde, wird der nächste ausgelöst, unabhängig davon, ob beim ersten Mal die Mittel-Prioliste durchlaufen worden ist. Vorausgesetzt natürlich, dass der Vorgänger bis dahin noch nicht quittiert hat.|Ganze Zahl zwischen 1 und 900. Sinnvoll ist ein Wert um 180, je nachdem, wie viele Mittel ein durchschnittlicher Teilnehmer zugewiesen hat. Wert 1 → parallele Auslösung an alle StV.|300|
|Auto Advance Alert Fax Seconds (Modul E-Mail/Fax)|Automatische Eskalation zum nächsten Mittel x Sekunden nach einem Fax, d. h. nach einem Fax wird x Sekunden auf ein Feedback gewartet, bevor auf das nächste Mittel der Mittel-Prioliste zurückgegriffen wird.|Ganze Zahl zwischen 1 und 300. Sinnvoll ist ein Wert ab 10.|10|
|Auto Advance Alert SMS Seconds (Basismodul)|Automatische Eskalation auf das nächste Mittel nach x Sekunden einer SMS, d. h. nach einer SMS wird x Sekunden auf ein Feedback gewartet, bevor auf das nächste Mittel der Mittel-Prioliste zurückgegriffen wird.|Ganze Zahl zwischen 1 und 300. Sinnvoll ist ein Wert zwischen 60 und 300 Sekunden.|120|
|Auto Advance Alert Call Seconds (Modul Alarmanruf)|Automatische Eskalation auf das nächste Mittel, x Sekunden nach einem Alarm-Anruf. Bedeutet, nach einem Alarm-Anruf wird x Sekunden auf ein Feedback gewartet, bevor auf das nächste Mittel der Mittel-Prioliste zurückgegriffen wird.|Ganze Zahl zwischen 1 und 300. Sinnvoll ist ein Wert zwischen 75 und 300 Sekunden (Grund: Da der Rufaufbau und die Verbindung selbst im Durchschnitt 50 Sekunden dauern, ist kein Feedback vor 60 Sekunden zu erwarten. Wenn also ein kürzeres Timeout gesetzt wird, kann dies dazu führen, dass der Teilnehmer schon auf dem nächsten Mittel alarmiert wird, während er den Alarm-Anruf noch abhört und quittiert!)|240|
|Auto Advance Alert Email Seconds (Modul E-Mail/Fax)|Automatische Eskalation zum nächsten Mittel x Sekunden nach einem E-Mail, d. h. nach einem E-Mail wird x Sekunden auf ein Feedback gewartet, bevor auf das nächste Mittel der Mittel-Prioliste zurückgegriffen wird.|Ganze Zahl zwischen 1 und 300. Sinnvoll ist ein Wert zwischen 10 und 60 Sekunden.|10|
|Auto Advance Alert Pager Seconds (Modul Pager)|Automatische Eskalation zum nächste Mittel x Sekunden nach einem Pager-Ruf. Nach einem Pager-Ruf wird also x Sekunden auf ein Feedback gewartet, bevor auf das nächste Mittel der Mittel-Prioliste zurückgegriffen wird.|Ganze Zahl zwischen 1 und 300. Sinnvoll ist ein Wert ab 60 Sekunden, da die Übermittlung der Pager-Nachricht etwa 30 Sekunden benötigt.|120|
|Auto Advance Alert Serial Seconds (Basismodul)|Gibt an, wie lange bei der vertikalen Eskalation die Wartezeit zwischen den einzelnen Teilnehmern ist.|Ganze Zahl zwischen 1 und 300. Bitte beachten: Wenn die Weiterschaltzeit zu kurz angegeben ist, können unter Umständen nicht alle Alarmierungsmittel des Alarmteilnehmers alarmiert werden.|Inaktiv|
|Auto Close Alert After Minutes (Basismodul)|Automatische Alarmterminierung nach x Minuten|Ganze Zahl ab 1|Inaktiv|
|Auto Close Alert Light Green (Basismodul)|Automatische Alarmterminierung, sobald die Ampel auf Grün springt (siehe Light Percent Green)|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|Auto Close Conference After Minutes|Gibt an in Minuten, wie lange eine Konferenz aktiv ist.|Ganze Zahl zwischen ab 1 |60|
|Basket Commit Delayed (kundenspezifisch)|Verzögerte Freigabe des Warenkorbs in Sekunden nach Mitternacht. Zu diesem Zeitpunkt wird eine freigegebene Schattentabelle in die Live-Tabelle kopiert.|Ganze Zahl ab 1…|Inaktiv|
|Billing Mail To (Basismodul)|Nach Abschluss eines Alarms das Billing-Protokoll automatisch per E-Mail versenden an|Gültige E-Mail-Adresse|Inaktiv|
|Call PIN Auth (Modul Empfängeridentifikation für Alarm-Anrufe)|Für Alarm-Anrufe wird vor der Sprachausgabe der Meldung die Identifikations-PIN des Empfängers verlangt|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|Call Waytime Acknowledge (Modul Alarm-Anruf)|Wegzeit-Angabe per DTMF nach positiver Quittierung eines Alarm-Anrufes|Ganze Zahl ab 0 (0: inaktiv, >0: aktiv). Wenn der Teilnehmer die Wegzeit nicht angibt, dann wird der hier gesetzte Wert verwendet.|Inaktiv|
|Check Min Max Unit Value|Schaltet Min/Max Teilnehmer Überprüfung in Gruppen/Vorlagen/Konferenzen ein/aus|0 oder 1 ||
|Check Unit Edit|Schaltet Bearbeitungszeiträume bei Gruppen/Vorlagen/Konferenzen ein/aus|0 oder 1||
|Conference Min Members (Modul Telefonkonferenz(en))|Mindestzahl an Konferenzteilnehmern (Y) - wird diese Zahl für X Sekunden unterschritten, wird die Konferenz automatisch beendet (für X siehe „Conference Timeout Seconds“).|Ganze Zahl zwischen 1 und maximale Anzahl Konferenzteilnehmer|1|
|Conference Timeout Seconds (Modul Telefonkonferenz(en))|Konferenztimeout (X) - Wenn X Sekunden weniger als Y Teilnehmer in der Konferenz sind, dann wird diese automatisch beendet (für Y siehe „Conference Min Members“).|Ganze Zahl ab 1. Sinnvoll ist ein Wert zwischen 60 und 900 Sekunden.|300|
|Custom Report Columns (Basismodul)|Definiert welche optionalen Felder im Alarmprotokoll ausgewiesen werden sollen.|Name von definierten optionalen Feldern. Mehrere sind durch „|“ (Alt Gr + 7) zu trennen. Maximal 3 Spalten.|Inaktiv, d.h. es werden keine optionalen Felder eingeblendet.|
|Custom Report Footer (Basismodul)|Definiert die Fusszeile im kundenspezifischen Seitenlayout (z.B. Alarmprotokoll und -Log)|Beliebig, z.B. Kontaktinformationen. Mehrere Zeilen sind durch „|“ (Alt Gr + 7) zu trennen. Es sind maximal 3 Zeilen möglich.|Inaktiv, d.h. es wird der Standard-Footer verwendet.|
|Custom Report Header (Basismodul)|Definiert die Kopfzeile im kundenspezifischen Seitenlayout (z.B. Alarmprotokoll und -Log)|Beliebig, z.B. Organisationsnamen. Nur einzeilig möglich.|Inaktiv, d.h. leer (aktuell kann das Swisscom-Logo der Kopfzeile noch nicht ersetzt werden).|
|Definite Identification|Bestimmt, welche optionale Felder im Namen der Teilnehmer angezeigt werden sollen. |Namen der optionalen Felder |Inaktiv|
|Disable Combox Key (Modul Telefonkonferenz(en))|Unterdrückt den Tastendruck für den Eintritt in die Telefonkonferenz. ACHTUNG: Durch das Deaktivieren gelangen auch Comboxen und Anrufbeantworter in die Telefonkonferenzen.|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|Disable Flash Sms|Schaltet die Alarmoption Flash-SMS(SMSPrio) ab, sodass SMS im normal Modus versendet werden|0,1|Flash standardmässig an |
|Dry Run Validity (Modul Dry Run)| Bestimmt, ob Teilnehmer bei der Auslösung Dry Run Wert berücksichtigen soll oder nicht.| 0 oder 1 (0: nicht berücksichtigen, 1: berücksichtigen)|0 : nicht berücksichtigen|
|Emergency Call Always Add Group Nr (Modul Notalarmierung)|Gruppe die automatisch JEDEM Notalarm hinzugefügt wird||Inaktiv|
|Emergency Call Mail To (Modul Notalarmierung)|Nach jeder Mutation die aktualisierte Notalarmierungsliste automatisch per E-Mail versenden an|Gültige E-Mail-Adresse|Inaktiv|
|Emergency Call Report To (Modul Notalarmierung)|Nach jeder Notalarmierung das Notalarm-Konferenzprotokoll automatisch per E-Mail versenden an|Gültige E-Mail-Adresse|Inaktiv|
|Email Alert Subject (Modul Email/Fax)|Ersetzt XXX im Betreff-Präfix bei der Email-Alarmierung „[ALARM XXX]“.|Beliebig, z.B. Organisationskürzel.|Inaktiv, d.h. es wird der Standard-Präfix verwendet: „[ALARM GroupAlarm ]“.|
|Email Attach All Languages (Modul Email/Fax)|Bei der E-Mail-Alarmierungen werden alle verfügbaren Attachment-Sprachen angehängt, statt nur die Sprache des Teilnehmers.|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|Export Template Group|Export für Alarmvorlagen mit Gruppen  |||
|Feedback Hide Progressbar|Feedback Progress Bar wird ausgeblendet|0 oder 1 ||
|Feedback SMS Group Limit (Feedback SMS By Groups)| Max. Anzahl an Gruppen in SMS Feedback| 0 oder ganze Zahl ||
|Info -SMS Originator (Basismodul)|Legt den Absender für Info-SMS fest.|Beliebig, z.B. Organisationskürzel. Länge ist auf 8 Zeichen beschränkt!|Inaktiv, d.h. es wird der Standard-Absender verwendet.|
|Light Percent Green (Basismodul)|Schwellenwert für grünes Licht der Ampel, d. h. sobald der definierte Prozentsatz an positiven Quittierungen erreicht ist, springt die Ampel auf Grün. (Siehe auch Auto Close Alert Light Green)|Ganze Zahl zwischen 1 und 100 (muss grösser sein als Light Percent Yellow)|80%|
|Light Percent Yellow (Basismodul)|Schwellenwert für Gelblicht der Ampel, d. h. sobald der definierte Prozentsatz an positiven Quittierungen erreicht ist, springt die Ampel auf Gelb.|Ganze Zahl zwischen 0 und 99 (muss kleiner sein als Light Percent Green)|50%|
|Login IP Restriction IP (kundenspezifisch)|Definiert die IP oder IP-Range von der aus sich ein Mitbenutzer oder eine Rechtegruppe einloggen darf. **ACHTUNG**: Diese Mitbenutzer können sich aus anderen IP-Ranges NICHT mehr einloggen!|IP-Adresse. Für Platzhalter bzw. IP-Ranges „\*“ verwenden.|Inaktiv|
|Login Parallel Sessions| Ein User mit denselben Credentials kann sich gleichzeitig mehrfach an mehreren Arbeitsstationen in GroupAlarm  einloggen. Seine aktuellen Handlungen (beispielsweise das Befüllen der Alarmierungsliste etc.) werden auf den jeweils anderen Sessions resp. Arbeitsstationen angezeigt. D.h. die Sessions beeinflussen sich gegenseitig.|Ganze Zahl 0 bis 20 ||
|Login Timeout Seconds (Basismodul)|Login-Timeout nach x Sekunden|Ganze Zahl ab 1.|900 (=15 Min)|
|Mass Alert Threshold| Anzahl der Teilnehmer, ab wann ein Alarm als Grossalarm gilt 
|Max alert participants warnlevel| Ab dieser Anzahl an Teilnehmern wird eine Warnung beim Alarm angezeigt| ganze Zahl ab 1| 0 - deaktiviert|
|Max alert participants blocklevel| Ab dieser Anzahl an Teilnehmern wird die Alarmierung verhindert (GUI) | ganze Zahl ab 1| 0 - deaktiviert |
|Max Conference Show (Modul Conference Call)| Anzahl angezeigten Konferenzen in der Alarmierungsansicht| ganze Zahl ab 1 | 100| 
|Max Events Show (Modul Alert Event)| Anzahl angezeigten Ereignissen in der Alarmierungsansicht| ganze Zahl ab 1| 100 | 
|Max Scenario Show (Modul Alert Scenario)| Anzahl angezeigten Drehbüchern in der Alarmierungsansicht| ganze Zahl ab 1| 100|                        
|Max Templates Show (Modul Alert Templates)| Anzahl angezeigten Alarmvorlagen in der Alarmierungsansicht| ganze Zahl ab 1| 100|                       
|Memberlist Keep Filter On Login (Basismodul)|Behält den zuletzt verwendeten Filter auf der Teilnehmerliste über die Session hinaus bei.|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|Multiple Folder In Tree (kundenspezifisch)|Erlaubt das mehrfache Einfügen der gleichen Gruppe in einen Baum.|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|Multiple Sessions| Ein User mit denselben Credentials kann sich, "Login Parallel Sessions" vorausgesetzt, gleichzeitig mehrfach an mehreren Arbeitsstationen in GroupAlarm  einloggen. Seine aktuellen Handlungen werden jedoch nicht auf den jeweils anderen Sessions resp. Arbeitsstationen angezeigt. D.h. das Aktivieren dieses Keys führt dazu, dass die Sessions als eigenständig betrachtet werden, ohne dass die eine Session eine andere beeinflusst.  | 0 oder 1||
|Num Temporary Texts (Basismodul)|Definiert die Anzahl der angezeigten „bisherigen Alarmtexte“. Bedingt die Aktivierung von „Show Temporary Texts“.|Ganze Zahl ab 1.|5|
|Parallel Alert Is Default (Basismodul)|Setzt „parallele Mittel“ als Standard.|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|PDF on demand| Erlaubt das Erzeugen von PDFs auf der Feedback-Seite|||
|Privacy Flag (Basismodul)|Aktiviert die Checkbox „Privat“ bei den Alarmmitteln. Privat Alarmmittel werden maskiert (z.B.: +4179123XXXX)|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|Report Language (Basismodul)|Verfassersprache der Alarm-Protokolle (gilt für den gesamten Kundenaccount!)|de: Deutsch, fr: Französisch, it: Italienisch, en: Englisch (Modul Englische Sprachversion). Mehrere Sprachen sind durch „,“ zu trennen. Die erstgenannte Sprache gilt als Standard (default).|en|
|Report Window Days (Basismodul)|Definiert die Anzahl Tage die unter geschlossene Alarme anfänglich geladen werden.|Ganze Zahl zwischen 1 und 100|100|
|Send Alert Log (Basismodul)|Definiert, dass das Alarm-Log IMMER mit dem Protokoll mitversandt werden soll.|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|Send Alert Report Fax (Modul E-Mail/Fax)|Nach Abschluss eines Alarms das Alarm-Protokoll automatisch per Fax versenden an|+41xxxxxxxxx oder +4186079xxxxxxx|Inaktiv|
|Send Alert Report Mail (Basismodul)|Nach Abschluss eines Alarms das Alarm-Protokoll automatisch per E-Mail versenden an|Gültige E-Mail-Adresse|Inaktiv|
|Send Alert Report SMS| Nach Abschluss eines Alarms das Alarm-Protokoll automatisch per SMS versenden an| Gültige Mobilenummer +417xxxxxxxx| Inaktiv|
|Send Alert Summery Fax (Modul E-Mail/Fax)|Während eines laufenden Alarms alle X Sekunden eine Feedback-Zusammenfassung per Fax versenden an. X wird in „Send Alert Summary Intervall Seconds“ definiert.|+41xxxxxxxxx oder +4186079xxxxxxx|Inaktiv|
|Send Alert Summery Intervall Seconds (Basismodul)|Definiert das Intervall, in welchem die Feedbackzusammenfassung versendet werden, solange ein Alarm offen ist.|Ganze Zahl ab 1. Sinnvoll ist ein Wert zwischen 60 und 900 Sekunden.|180|
|Send Alert Summery Mail (Basismodul)|Während eines laufenden Alarms alle X Sekunden eine Feedback-Zusammenfassung per Mail versendet an. X wird in „Send Alert Summary Intervall Seconds“ definiert.|Gültige E-Mail-Adresse|Inaktiv|
|Send Alert Summery SMS (Basismodul)|Während eines laufenden Alarms alle X Sekunden eine Feedback-zusammenfassung per SMS versendet an. X wird in „Send Alert Summary Intervall Seconds“ definiert.|Gültige Mobilfunknummer +417xxxxxxxx|Inaktiv|
|Send Billing Info (Basismodul)|Definiert, dass die Billing-Info IMMER mit dem Protokoll mit versandt werden soll.|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|Send Bounce Mail List To (Basismodul)| E-Mail Adresse, an die die bounced E-Mails verschickt werden.| gültige E-Mail-Adresse| Inaktiv| 
|Set User Dataset (Check User Dataset)| Definiert, welcher Daten bei der Bearbeitung eines Teilnehmers geprüft werden müssen.| Text mit gültigen Einträgen durch Pipe getrennt - pin,rank,name,firstname,street,zipCode,town,kanton,lang,alert,group,optional:Feldname1,Feldname1,...| name,firstname,alert,lang| 
|Show Admin Registry (Basismodul)|Mitbenutzern das Recht zuordnen, „Generelle SMS-Auslösung“ zu konfigurieren.|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|Show All Alerts| Ermöglicht die Anzeige aller laufenden Alarme auf der Feedbackseite| 0 oder 1||
|Show General Sms Trigger (Modul Fernauslösung)| Mitbenutzer das Recht zuordnen, "Generelle SMS-Auslösung" zu konfigurieren.| 0 oder 1 (0: inaktiv, 1: aktiv)| Inaktiv| 
|Show Languages (Basismodul)|Verwendete bzw. angezeigte Alarmsprachen (gilt für den gesamten Kundenaccount!)|de, fr, it, en (Modul Englische Sprachversion) (mehrere durch Komma getrennt: de,fr,it)|de,fr,it,(en)|
|Show Temporary Texts (Basismodul)|History bisheriger Texte in der Textauswahl einblenden. Die Anzahl wird über „Num Temporary Textes“ definiert.|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|Suppress SMS Reply (Modul Fernauslösung)|Unterdrückt die Bestätigungs-SMS bei der Auslösung per SMS|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|Table Block Size| Default Anzahl abgeschlossene Alarme| ganz Zahl| 100| 
|Tree Session Persistant| die aktuelle Baumansicht wird beim Verlassen der Seite gespeichert| 0,1| inaktiv|
|Unitronic Allow Alert |  Der hier eingetrage Teilnehmer ist berechtigt den Nachrichtenstil „Alarm“ auszuwählen| 0 oder 1| Inaktiv| 
|Unitronic Allow Prio Alert| Der hier eingetrage Teilnehmer ist berechtigt den Nachrichtenstil „Prio-Alarm“ auszuwählen| 0 oder 1| Inaktiv|
|User Allow Billing-Info (Basismodul)|Mitbenutzer das Recht zuordnen, die Billing-Info PDF`s einzusehen.|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|User Allow Gis Config (kundenspezifisch)|Mitbenutzern das Recht zuordnen, Ortungsbaken und Endgeräte zu pflegen.|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|User Allow Import Export (Basismodul)|Mitbenutzern das Recht zuordnen, die Im-/Export-Funktionalität zu nutzen|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|User No Change Remote Alerting| Mitbenutzer darf den Auslösecode der Objekte nicht ändern| 0,1| inaktiv| 
|User No Create Clocks (Modul Rotations- und Einsatzplanung)|Mitbenutzer darf keine neuen Zeitsteuerungen anlegen|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|User No Create Conference (Modul Conference Call)| Mitbenutzer darf keine Konferenzen erstellen.| 0 oder 1 (0: inaktiv, 1: aktiv)| Inaktiv| 
|User No Create Event| Mitbenutzer darf keine neuen Ereignisse anlegen| 0,1| Inaktiv| 
|User No Create Members (Basismodul)|Mitbenutzer darf keine neuen Teilnehmer anlegen|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|User No Create Quicklogin (Basismodul)|Mitbenutzer darf keine Quicklogins erstellen.|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|User No Create Rotation Group| Mitbenutzer darf keine neuen Rotationsgruppen anlegen| 0,1| Inaktiv|
|User No Create Szenarios (Modul Alarmvorlagen und Drehbücher)|Mitbenutzer darf kein neues Drehbuch anlegen|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|User No Create Templates (Modul Alarmvorlagen und Drehbücher)|Mitbenutzer darf keine neuen Alarmvorlagen anlegen|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|User No Create Text (Basismodul)|Mitbenutzer darf nicht auf das Menü „Mutieren-Texte“ zugreifen.|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|User No Create Units (Basismodul)|Mitbenutzer darf keine neuen Wurzeln und Gruppen anlegen|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|User Save Column Layout (Basismodul)|Jeder Mitbenutzer darf die Anordnung der Alarmspalten und den Standardbaum für sein Login selbst definieren|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|User Show Own Numbers Only| Versteckt TN-Mittel auf die der Mitbenutzer keine Mutieren Rechte hat| 0 oder 1 (0: inaktiv, 1: aktiv)| Inaktiv| 
|User Show Own Alerts Only (Basismodul)|Jeder Mitbenutzer sieht nur seinen eigenen Alarm, bzw. alle Alarme der gleichen Rechtegruppe, wenn die Berechtigungen über Rechtegruppen konfiguriert sind.|0 oder 1 (0: inaktiv, 1: aktiv)|Inaktiv|
|Userlist Max Entries| Maximale Anzahl an Einträgen in der Teilnehmerliste| -1 bis 10000 (-1: unendlich)| 10000| 




