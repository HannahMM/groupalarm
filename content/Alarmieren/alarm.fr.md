+++
title = "Alarme"
weight = 1
+++

### Table des matières 

- [Général](#general)

- [Participant(s)](#participant_s)

- [Textes](#textes)

- [Coordonnées](#coordonnees)

- [Options d\`alarme](#options_d_alarme)

- [Délai d'envoi de suite](#delai_d_envoi_de_suite)


Dès que vous avez sélectionné un participant, un groupe ou une racine et
cliqué sur \*Alarme\*, le masque Créer l’alarme s’ouvre.

**Général:** le nom de l’alarme actuelle ainsi que son éventuelle
description s’affichent.

**Participants:** Le nombre de participants par groupe devant être
alarmés s’affiche sous Participant(s).

**Texte:** vous pouvez saisir un nouveau texte sous «Texte libre» avant
de le confirmer via le bouton «Déclencher l’alarme». Si vous avez créé
un texte prédéfini, vous pouvez l’utiliser en tant que texte d’alarme en
cliquant sur
![](/img/runderblauesdings.png)
ou à l’aide de *Editeur rapide*. Les textes des alarmes précédentes
peuvent être réutilisés dans le texte libre via *Editeur rapide*.

**Options d’alarme:** Ici, vous pouvez définir des paramètres
supplémentaires concernant les moyens d’alarme, les critères
d’interruption, l’envoi d’informations, etc.

**Délais d’envoi:** Ici, vous définissez si l’alarme doit être
déclenchée immédiatement ou après un certain délai. Une fois tous les
paramètres de votre choix définis, vous pouvez déclencher l’alarme en
cliquant sur le bouton «Déclencher l’alarme» (qui apparaît entre temps
en rouge).

Outre le déclenchement de l’alarme directement à partir de l’interface
GUI, eAlarm emergency prend en charge plusieurs modes de déclenchement à
distance. Vous pouvez déclencher l’alarme par SMS, appel vocal, menu
DTMF, sélection directe ou via un lien Web.

Vous trouverez plus d’informations sur le déclenchement à distance dans
l’aide-mémoire: *eAlarm emergency - Déclenchement à distance*

![](/img/alarmeralarmer.dcecaefe829ad5a126881decfb7d83a0.png?width=700px&classes=shadow)

<a name="general"></a>
### Général 

![](/img/creer_alarme_general_fr.png?classes=shadow)

Vous pouvez modifier le **Nom de l’alarme**. Vous pouvez décrire
l’alarme sous **Description** (facultatif). La personne ayant crée
l’alarme est indiquée sous **Créateur**, la date et l’heure de création
de l’alarme le sont sous **Date/heure**.

<a name="participant_s"></a>
### Participant(s) 

![](/img/creeralarm_participants_fr.png?classes=shadow)

Les participants sélectionnés pour l’alarme et les unités auxquelles ils
appartiennent sont indiqués sous **dossiers/groupes**. De plus, les
participants ne pouvant pas être alarmés ou apparaissant deux fois sont
affichés. Il est possible d’ajouter d’autres groupes/participants sous
\[Traiter\]

<a name="textes"></a>
### Textes 

![](/img/creer_alarm_textes_fr.05cb05d76d4c9ed1b87ed2b4dfedc615.png?classes=shadow)

Avant de déclencher l’alarme, vous pouvez encore définir si vous
souhaitez sélectionner le texte prédéfini (en cliquant
sur ![](/img/blauerpunkt_en.png))
ou créer un nouveau
![](/img/freitext_fr.png)
texte libre. Un texte prédéfini peut être repris et adapté en cliquant
sur «Editeur rapide». «Editeur rapide» permet au participant de ne pas
avoir à saisir un nouveau texte, mais d’utiliser un texte déjà existant
sur lequel il peut effectuer les adaptations nécessaires.

<a name="coordonnees"></a>
### Coordonnées 

Sous “Transmettre les coordonnées”, vous pouvez décider si vous
souhaitez transmettre ou non les
coordonnées.![](/img/koordinaten_1.png?classes=shadow)

Sous “Indiquer l’adresse”, saisissez l’adresse souhaitée.

![](/img/koordinaten_2.png?classes=shadow)

Ou précisez les coordonnées:

![](/img/koordinaten_3.png?classes=shadow)

Dès que vous avez saisi une adresse, la conversion au format WGS84
s’effectue automatiquement.

![](/img/koordinaten_4.bdd9679dd5521cf4eec46a71dbc17b4e.png?width=700px&classes=shadow)


<a name="options_d_alarme"></a>
### Options d'alarme 

![](/img/alarmoptionen_fr.4a19022fafcab4b75d3faa2c4c4f173a.png?width=700px&classes=shadow)

**Alarmer les moyens suivants:** vous pouvez décider des moyens à
alarmer et de ceux qui ne doivent pas l’être.

**SMSprio:** définissez si votre alarme doit passer ou non par SMSprio.
Si vous sélectionnez «NON», le Flash SMS n’est pas envoyé.

**Semainier** (s’affiche uniquement avec le module Moyen-Liste
prioritaire Plus).

- Comme données du participant: les participants sont alarmés au moyen
    du semainier prédéfini.

- Test (par défaut): avec cette option, le semainier prédéfini
    (module optionnel) n’est pas pris en compte.

**Interrompre:** définissez ici les critères pour l’interruption
automatique d’une alarme. Dès que l’un des critères d’interruption
définis pour l’alarme est atteint, cette dernière est interrompue.

- Interrompre après que x% des participants ont quittancé positivement

- Interrompre après que x participants ont quittancé positivement

- Interrompre x minutes après le déclenchement de l’alarme 

**Envoi de l’info:** vous pouvez définir à qui quel document doit être
directement adressé par mail/fax. Vous pouvez également définir ici
quelle adresse e-mail ou quel numéro de fax et/ou de mobile doit
recevoir un résumé périodique sur le statut de l’alarme. Remarque: des
résumés périodiques sur une alarme en cours peuvent également être
envoyés.

<a name="delai_d_envoi_de_suite"></a>
### Délai d'envoi de suite 

![](/img/versandzeit_zeitsteuerung_fr.png?classes=shadow)

Par principe, eAlarm est réglé de manière à ce qu’une alarme soit
déclenchée immédiatement. Vous pouvez également planifier une alarme
sous Délai d’envoi («Envoyer selon délai prédéfini»), en définissant le
jour et l’heure auxquels l’alarme doit être déclenchée. Ces alarmes
«planifiées» peuvent, par exemple, être utilisées pour des exercices
d’alerte, car ceux-ci peuvent être prévus suffisamment à l’avance. Les
alarmes planifiées peuvent être consultées et supprimées dans le menu
«Statut».

