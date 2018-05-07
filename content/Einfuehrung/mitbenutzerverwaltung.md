+++
title = "Mitbenutzerverwaltung"
weight = 5
+++



### Mitbenutzerverwaltung 



Bei GroupAlarm pro kann sich jeder angelegte Teilnehmer mit seinem
persönlichen Login (Benutzername) und Passwort (diese Daten werden über den Hauptaccount vergeben)auf der Einstiegsseite
identifizieren und anmelden. 
Seine Rechte sind zunächst auf **Eigene Daten**
beschränkt, d.h. die einzigen Daten, die er einsehen und bearbeiten
kann, sind seine persönlichen Daten wie Adresse, Alarmmittel-Nummern und
-Adressen, Abwesenheiten und die optionalen Felder.

**Wichtig:** Ein Login ist noch kein Mitbenutzer.


Die Voraussetzung für einen Mitbenutzer, d. h. für einen Zugang mit mehr
Rechten als nur für **Eigene Daten**, ist ein Benutzerlogin. Sobald der
Teilnehmer ein Benutzerlogin hat, kann er über die Rechteverwaltung zu
einem Mitbenutzer gemacht werden, indem ihm eine Mitbenutzer-Rolle zugewiesen
wird.


<a name="mitbenutzer-rollen"></a>
### Mitbenutzer-Rollen 



GroupAlarm pro hat verschiedene Mitbenutzer-Rollen.

-   

    **Masteruser**: Dieser Nutzer hat uneingeschränkte
    Rechte und kann auch die Rechte anderer uneingeschränkt definieren.
**Diese Rolle ist fest dem Hauptaccount des
Kunden zugeordnet und kann nicht an weitere Mitbenutzer vergeben
werden.**  
    

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

    

Es bleiben also verschiedene Rechte-Rollen für die Mitbenutzer. Diese sind lokal, d. h. die Rechte
beschränken sich auf die Gruppen, Untergruppen und die darin enthaltenen
Teilnehmer. 


<a name="zuweisung_der_rechte-rolle"></a>
### Zuweisung der Rechte


#### Rechtevergabe an Einzelpersonen

Die Zuweisung von Rechten erfolgt im Organigramm/Baumansicht. Um zur Rechteverwaltung einer Gruppe zu gelangen,
klicken Sie auf das Schlüssel-Symbol <img src="/img/schluesselsymbol.png" alt="schluessel" style='vertical-align:middle;display:inline;margin:0px 5px; '>
des entsprechenden Ordners. 

Hier sehen Sie eine Übersicht der Berechtigungen. Im folgenden Beispiel hat Anna Bauer Admin-Rechte am Ordner „Ordner_1“. Alle untergeordneten Ordner erben diese Berechtigungen.

![](/img/einfuehrung_mitbenutzerverwaltung_berechtigung1.png?classes=shadow)

Um eine neue Berechtigung hinzuzufügen, wählen Sie die gewünschte Person im Dropdown-Menü und die entsprechenden
Rechte-Rolle aus. Bestätigen Sie mit der Schaltfläche „hinzufügen“.

![](/img/einfuehrung_mitbenutzerverwaltung_berechtigung2.png?classes=shadow)

{{% panel theme="danger" header="Achtung!" %}}Die Zuordnung von Mitbenutzer-Rollen an einzelne Teilnehmer hat ihre
Tücken. Stellen Sie sich vor, Sie haben nach dem oben beschriebenen Weg
etlichen Mitbenutzern nun Rechte zugewiesen. Dabei dürfte ein und
derselbe Mitbenutzer sogar in verschiedenen Bäumen und Gruppen bestimmte
Rollen zugeteilt bekommen haben. Wenn nun ein solcher Mitbenutzer
geändert wird oder er andere Rechte erhalten soll, müssen Sie an ihn
jeder Stelle, an denen er Rechte hat, entsprechend mutieren. Das kann
umständlich und bei grösseren Organisationen auch unübersichtlich
werden.{{% /panel %}}

Es ist daher empfehlenswert, eine separate Gruppe/Wurzel „Mitbenutzerverwaltung“ zu erstellen und
dann ganzen Gruppen (statt einzelnen Teilnehmern) Rechte über die
Rechteverwaltung zuzuordnen. Dieses Vorgehen hat den Vorteil, dass die
Rechte-Verwaltung praktisch nur einmal konfiguriert werden muss. So
findet die gesamte Rechte-Verwaltung nur noch in der Wurzle „Mitbenutzerverwaltung“ statt.

#### Rechtevergabe an Rechtegruppen (empfohlen)




Ist ein Mitbenutzer in einer Rechtegruppe, hat er
automatisch alle Rechte auf allen definierten Stufen, die dieser
Rechtegruppe zugeordnet wurden. Wird der Mitbenutzer aus allen
Rechtegruppe entfernt, verfallen auch alle Rechte, die er
ursprünglich hatte, und er fällt zurück auf das Benutzerlogin-Recht
Eigene Daten.

Erstellen Sie also eine neue Wurzel und verschiedene Ordner, die die Mitbenutzer-Rollen darstellen. Ordnen Sie dann die Teilnehmer den 
entsprechenden Gruppen zu.
![](/img/einfuehrung_mitbenutzerverwaltung_berechtigung3.png?classes=shadow)

**Wichtig:** Zuvor müssen Sie den Ordner als Rechtegruppe definieren. Klicken Sie dazu auf das Bearbeitungssymbol 
<img src="/img/bearbeitungsicon.png" alt="edit" style='vertical-align:middle;display:inline;margin:0px 5px; '> und
setzen Sie im Organisationsbereich den Typ auf **„Rechtegruppe“**.

![](/img/einfuehrung_mitbenutzerverwaltung_berechtigung4.png?classes=shadow&width=1200px)


Wechslen Sie anschließen wieder auf die Wurzel Ihrer Unternehmensstruktur und ordnen Sie den verschiedenen Ordnern die 
entsprechenden Rechte-Ordner zu. Alle Teilnehmer, die in der Rechtegruppe „Berechtigung Admin“ sind, haben nun Admin-Rechte für den Ordner „Ordner_1“.

![](/img/einfuehrung_mitbenutzerverwaltung_berechtigung5.png?classes=shadow)




Zusätzliche Rechte-Optionen können im Register **„Admin“** im **„Menü
Registry“** konfiguriert werden.




