+++
title = "Mitbenutzerverwaltung"
weight = 9
+++







### Mitbenutzerverwaltung 



Bei eAlarm emergency kann sich jeder angelegte Teilnehmer mit seinem
persönlichen Login (Benutzername) und Passwort auf der Einstiegsseite
identifizieren und anmelden. Seine Rechte sind zunächst auf **Eigene Daten**
beschränkt, d. h. die einzigen Daten, die er einsehen und bearbeiten
kann, sind seine persönlichen Daten wie Adresse, Alarmmittel-Nummern und
-Adressen, Abwesenheiten und die optionalen Felder.

{{% panel theme="info" header="Wichtig!" %}}Ein Login ist noch kein Mitbenutzer{{% /panel %}}




Die Voraussetzung für einen Mitbenutzer, d. h. für einen Zugang mit mehr
Rechten als nur für **Eigene Daten**, ist ein Benutzerlogin. Sobald der
Teilnehmer ein Benutzerlogin hat, kann er über die Rechteverwaltung zu
einem Mitbenutzer gemacht werden, indem ihm eine Rechte-Rolle zugewiesen
wird.


<a name="mitbenutzer-rollen"></a>
### Mitbenutzer-Rollen 



eAlarm emergency kennt standardmässig 1 bis 4 Mitbenutzer-Rollen.

-   

    **Superuser**: Dieser Nutzer hat uneingeschränkte
    Rechte und kann auch die Rechte anderer uneingeschränkt definieren.

    

-   

    **Alarmieren & Mutieren**: Diese Rolle erlaubt es dem Teilnehmer,
    die dafür definierten Einheiten und alle Untereinheiten zu
    bearbeiten, zu löschen und neue Einheiten zu erstellen. Er kann
    Alarme an sie auslösen. Und schliesslich kann er das Feedback
    einsehen und gegebenenfalls nachalarmieren.

    

-   

    **Alarmieren**: Diese Rolle erlaubt es dem Teilnehmer, die dafür
    definierten Einheiten und alle Untereinheiten zu alarmieren, das
    Feedback einzusehen und gegebenenfalls nachzualarmieren.

    

-   

    **Mutieren**: Diese Rolle erlaubt es dem Teilnehmer, die dafür
    definierten Einheiten und alle Untereinheiten zu bearbeiten, zu
    löschen und neue Einheiten zu erstellen.

    

-   

    **Feedback**: Diese Rolle erlaubt es dem Teilnehmer nur,
    Alarmfeedbacks einzusehen. Der Teilnehmer hat keine funktionalen
    Rechte wie Alarmieren, Nachalarmieren und Mutieren.

    

-   

    **Admin**: Diese Rolle erlaubt dem Mitbenutzer nichts anderes, als
    das Admin-Register einzusehen und zu bearbeiten.

    

**Von diesen Rollen ist die Superuser-Rolle fest dem Hauptaccount des
Kunden zugeordnet und kann nicht an weitere Mitbenutzer vergeben
werden.**  
Es bleiben also vier Rechte-Rollen für die Mitbenutzer. Die
Status-Rolle ist global, d. h. wer sie innehat, kann alles im
Status-Menü einsehen. Die anderen Rollen sind lokal, d. h. die Rechte
beschränken sich auf die Gruppen, Untergruppen und die darin enthaltenen
Teilnehmer. 


<a name="zuweisung_der_rechte-rolle"></a>
### Zuweisung der Rechte


Die Zuweisung von Rechten erfolgt im Organigramm/Baumansicht. Um zur Rechteverwaltung einer Gruppe zu gelangen,
klicken Sie auf das Schlüssel-Symbol <img src="/img/schluesselsymbol.png" alt="schluessel" style='vertical-align:middle;display:inline;margin:0px 5px; '>
des entsprechenden Ordners. 

Hier sehen Sie eine Übersicht der Berechtigungen. Im folgenden Beispiel hat Erika Mustermann Admin-Rechte am Ordner „Test_Ordner2“

![](/img/einfuehrung_mitbenutzerverwaltung3.png?classes=shadow)

Um eine neue Berechtigung hinzuzufügen, wählen Sie die gewünschte Person im Dropdown-Menü und die entsprechenden
Rechte-Rolle aus. Bestätigen Sie mit der Schaltfläche „hinzufügen“.

![](/img/einfuehrung_mitbenutzerverwaltung4.png?classes=shadow)

{{% panel theme="danger" header="Achtung!" %}}Die Zuordnung von Rechte-Rollen an einzelne Teilnehmer hat ihre
Tücken. Stellen Sie sich vor, Sie haben nach dem oben beschriebenen Weg
etlichen Mitbenutzern nun Rechte zugewiesen. Dabei dürfte ein und
derselbe Mitbenutzer sogar in verschiedenen Bäumen und Gruppen bestimmte
Rollen zugeteilt bekommen haben. Wenn nun ein solcher Mitbenutzer
geändert wird oder er andere Rechte erhalten soll, müssen Sie an ihn
jeder Stelle, an denen er Rechte hat, entsprechend mutieren. Das kann
umständlich und bei grösseren Organisationen auch unübersichtlich
werden.{{% /panel %}}





Es ist daher empfehlenswert, eine separate Gruppe/Wurzel „Mitbenutzer“ zu erstellen und
dann ganzen Gruppen (statt einzelnen Teilnehmern) Rechte über die
Rechteverwaltung zuzuordnen. Dieses Vorgehen hat den Vorteil, dass die
Rechteverwaltung praktisch nur einmal konfiguriert werden muss. So
findet die gesamte Rechte-Verwaltung nur noch im Mitbenutzer-Baum statt.


Ist ein Mitbenutzer Mitglied in einer Mitbenutzergruppe, hat er
automatisch alle Rechte auf allen definierten Stufen, die dieser
Mitbenutzergruppe zugeordnet wurden. Wird der Mitbenutzer aus allen
Mitbenutzergruppen entfernt, verfallen auch alle Rechte, die er
ursprünglich hatte, und er fällt zurück auf das Benutzerlogin-Recht
Eigene Daten.

Erstellen Sie also eine neue Wurzel und verschiedene Ordner, die die Rechte-Rollen darstellen. Ordnen Sie dann die Teilnehmer den 
entsprechenden Gruppen zu.
![](/img/einfuehrung_mitbenutzerverwaltung5.png?classes=shadow)

{{% panel theme="info" header="Wichtig!" %}}Zuvor müssen Sie den Ordner als Rechte-Ordner definieren. Klicken Sie dazu auf das Bearbeitungssymbol 
<img src="/img/bearbeitungsicon.png" alt="edit" style='vertical-align:middle;display:inline;margin:0px 5px; '> und
setzen Sie im Organisationsbereich den Typ auf **„Rechtegruppe“**.{{% /panel %}}

![](/img/einfuehrung_mitbenutzerverwaltung.png?classes=shadow)


Wechslen Sie anschließen wieder auf die Wurzel Ihrer Unternehmensstruktur und ordnen Sie den verschiedenen Ordnern die 
entsprechenden Rechte-Ordner zu. Alle Teilnehmer, die im Rechte-Ordner „Berechtigung Mutieren“ sind, haben nun das
Recht, den Ordner „Test_Ordner2“ zu mutieren.

![](/img/einfuehrung_mitbenutzerverwaltung6.png?classes=shadow)




Zusätzliche Rechte-Optionen können im Register **„Admin“** im **„Menü
Registry“** konfiguriert werden.



