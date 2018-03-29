+++
title = "Alarmes en cours"
weight = 1
+++

Dès que l’alarme est déclenchée, le masque “Feedback d'alarme”
s’affiche. Tous les destinataires auxquels une alarme a été envoyée sont
enregistrés dans le \$\$Feedbackspeicher, d’où on peut suivre la
procédure exacte d’alarme en temps réel.

Les feedback des participants s’affichent immédiatement dans la vue
“Feedback d'alarme” et sont actualisés en permanence. Un graphique
d'évaluation des quittances s’affiche dans la boîte de dialogue (“cadre
rouge”). Il indique combien de participants se trouvent dans quel
statut. Les quittances positives, négatives et invalides y sont listés.

![](/img/laufender_alarm_fr.00b7f4f7b62867a3012867a56424f61a.png?width=700&classes=shadow)

Les personnes alarmées doivent quittancer l’alarme dans la syntaxe
prédéfinie, afin que les réponses puissent être évaluées. La syntaxe
prévoit qu’un quittancement commence obligatoirement par l’un des deux
mots-clés “Oui” ou “Non”, ou encore “OK”/“NOK”, ou encore “Si”/“No”, ou
encore “Yes”/“No” ou “1”/“2”. Si un texte supplémentaire est transmis,
il doit obligatoirement être séparé du mot-clé par un espace (la virgule
ou le point après le mot-clé ne pouvant pas être compris).

Exemples de bonnes réponses:

  ------------------------------- --------------------------
  OUI                             NON
  Oui j\`arrive dans 20 minutes   Non j\`ai un empêchement
  Oui je participe                Non ça ne va pas
  OK                              NOK
  OK j\`arrive dans 20 minutes    NOK j\`ai un empêchement
  OK je participe                 NOK ça ne va pas
  ------------------------------- --------------------------


Exemples de mauvaises réponses:

- C’est OK j’arrive (mauvais mot-clé)

- Oui, dans 15 minutes (séparation du mot-clé par une virgule)

Si eAlarm emergency ne peut pas comprendre les réponses en raison d’une
mauvaise syntaxe, le destinataire du feed-back reçoit le statut
«invalide» et le SMS de réponse complet s’affiche dans la colonne
Resultat.

![](/img/alarm_falschesfeedback_fr.png)

Le destinataire du feedback peut, en fonction du texte, définir
manuellement le “résultats” sur “Oui” ou “Non”, en sélectionnant la
coche verte
![](/img/gruenesgutzeichen_fr.png)
ou la croix rouge
![](/img/rotesx_fr.png).
S’il définit manuellement le participant sur “Oui”, par exemple, ce
dernier est représenté ainsi dans eAlarm.

![](/img/statusmanuel_fr.png)

Le texte d’origine dans Résultat est écrasé par les informations
relatives au changement de statut manuel.

Le feed-back sur l’alarme indique dans un histogramme l’avancement du
quittancement des participants. On peut donc connaître d’un coup d’œil
le taux relatif de destinataires ayant donné un feed-back positif ou
négatif ainsi que le nombre de participants n’ayant pas encore quittancé
l’alarme.

La liste des détails de l’alarme indique quand cette dernière a été
planifiée et déclenchée ainsi que depuis quand elle est en cours. Le feu
de circulation indique quand la limite de l’alarme réussie est atteinte.
Lorsque la lampe passe de rouge à orange, un nombre prédéfini de
participants a déjà quittancé l’alarme de façon positive. Si la lampe
passe au vert, le nombre prédéfini dans le registre de feed-back
positifs nécessaires est atteint et vous pouvez arrêter l’alarme.

Lorsque la session eAlarm emergency est terminée, vous devez vous
déconnecter de l’application. Pour ce faire, cliquez sur Logout dans
l’onglet **“Session”**.
