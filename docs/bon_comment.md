## Comment écrire des commentaires

:memo: Afin de faire les commentaires ajoutés dans les CAO plus claires, plus cohérents et exemptes des fautes d’orthographe et de grammaire plusieurs commentaires prédéfinis ont été modifiés et plusieurs nouveaux commentaires ont été ajoutés dans LIMS en décembre 2025.
 
**Quelques règles de base pour écrire des bons commentaires :**

- Ne pas laisser la première ligne vide;
- Ne pas laisser les lignes vides entre les deux commentaires;
- Mettre un point ' . ' à la fin d’une phrase;
- Mettre une espace avant et après ' : ';
- Mettre chaque commentaire sur une nouvelle ligne;
- Mettre une phrase "Commentaires du client : " avant les commentaires du client;
- Mettre une espace entre le nombre et l’unité de mesure, par exemple '10.36 mg/L';
- Pour les échantillons de BNQ utiliser le commentaire prédéfini en changeant seulement le # d'échantilloneur;
- Utiliser les nom d'analyse complet dans des commentaires, pas d'abréviations, sauf pour les analyses qui ont déjà les abréviations (COV par exemple).


### Mieux comrendre le message du client sur CP

Il est souvent pas facile de dechiffrer ce qu'il est écrit sur le CP, cependant en sachant les paramètres et les unutés associés il est plus facile de bien comprendre le message du client. Dans le tableau ci-dessous les paramètres et les unités de mesure les plus frequents sur CP des client sont présentés. 

| Paramètre      | Unité        | Unité                         |
|----------------|--------------|-------------------------------|
| Température    | °C           | degré Celsius                 |
| Conductivité   | µS/cm        | microsiemens par centimètre   |
| oPO4           | mg/L         | milligramme par litre         |
| Alcalinité     | mg CaCO3/L   | milligramme CaCO3 par litre   |
| Débit          | m3/j         | mètre cube par jour           |


### Completer le commentaire général prédéfini

Plusieurs commentaires prédéfinis sont conçus de façon général et doivent être completés en ajoutant l'information notée sur le CP comme, par exemple, la température mesurée par le client ("Température mesurée par le client : * °C.") ou la date et l'heure d'échantillonage ("Échantillon composé 24 heures, soit du \* au \*."). Ça peut être aussi l'information obtenue au moment de la réception, par exemple le délai dépassé pour l'Une des analyses à l'arrivée au laboratoire ("L'analyse de XXX a été effectuée dans un délai dépassé."). Dans ces cas les symbols "*" et lettres "XXX" ("YYY", "ZZZ") doivent être remplacés correctement.

S’il s’agite d’un commentaire avec « * » (sauf le commentaire **"* La température a été omise lors de la réception de l'échantillon."**) il faudrait remplacer « * » par la valeur appropriée (date, heure, température), cependant il ne faudrait pas supprimer les espaces qui entournent « * » ni ajouter des nouvelles espaces ni avant, ni après.  
Par exemple : « Température à la réception : * °C. » doit être correctement modifieé comme *« Température à la réception : 15.2 °C. »* et pas comme « Température à la réception :     15.2°C. ».  

S’il s’agite d’un commentaire avec « XXX » (YYY ou ZZZ) il faudrait remplacer « XXX » par le nom d’analyse complet.  
Par exemple : « L’échantillon pour l'analyse de XXX a été reçu après l'expiration du délai de conservation réglementaire. L'analyse a été effectuée à la demande du client. » doit être modifié comme ici : *« L’échantillon pour l'analyse du pH-15°C a été reçu après l'expiration du délai de conservation réglementaire. L'analyse a été effectuée à la demande du client. »* (**XXX a été remplacé par 'le pH-15°C'**).
 
 
Par exemple, au lieu d’utiliser le commentaire « pH reçu et analysé hors délai » il faudrait utiliser le commentaire prédéfini *« L’échantillon pour l'analyse du pH-15°C a été reçu après l'expiration du délai de conservation réglementaire. L'analyse a été effectuée à la demande du client. »*
ou *« L'échantillon pour l'analyse du pH EU a été reçu après l'expiration du délai de conservation réglementaire. L'analyse a été effectuée à la demande du client.»*
ou les deux commentaires ensemble si les deux analyses pH-15°C et pH EU sont demandées.

*«L'échantillon pour l'analyse du pH EU a été reçu après l'expiration du délai de conservation réglementaire. L'analyse a été effectuée à la demande du client*.  
*L'échantillon pour l'analyse du pH-15°C a été reçu après l'expiration du délai de conservation réglementaire. L'analyse a été effectuée à la demande du client.»*
 
 
### Commentaires pour les analyses de la DBO

L'analyse de la Demande chimique en oxygène est une analyse avec un court délai analytique, cependant l'échantillon peut être congelé pour ... ('prolonger la durée de vie'). Présentement dans LIMS il existe 6 paramètres distincts pour l'analyse de la Demande biochimique en oxygène: 

| Paramètre | Nom complet                                                |
|---------- |------------------------------------------------------------|
| EDCDBOT01 | Demande biochimiqe en oxygène totale-5 jours               |
| EDCDBOT04 | Demande biochimiqe en oxygène totale-5 jours non-congelé   |
| EDCDBOC01 | Demande biochimiqe en oxygène carbonée-5 jours             |
| EDCDBOC02 | Demande biochimiqe en oxygène carbonée-5 jours non-congelé |
| EDCDBOS01 | Demande biochimiqe en oxygène dissous-5 jours              |
| EDCDBOSC1 | Demande biochimiqe en oxygène carbonée et dissous-5 jours  |

Vu que toutes les analyses de la Demande biochimique en oxygène sont faites en 5 jours, et le fait que les  analyses de EDCDBOT01 et EDCDBOT04, et EDCDBOC01 et EDCDBOC01 sont identiques sauf que T04 et C02 ne doivent pas être congelées, voici le tableau avec les paramètres de la DBO et les noms d'analyse correpondants à utiliser dans des commentaires.

| Paramètre | Nom à utiliser dans les commentaires                                             |
|---------- |------------------------------------------------------------|
| EDCDBOT01 | Demande biochimiqe en oxygène totale                       |
| EDCDBOT04 | Demande biochimiqe en oxygène totale                       |
| EDCDBOC01 | Demande biochimiqe en oxygène carbonée                     |
| EDCDBOC02 | Demande biochimiqe en oxygène carbonée                     |
| EDCDBOS01 | Demande biochimiqe en oxygène dissous                      |
| EDCDBOSC1 | Demande biochimiqe en oxygène carbonée et dissous          |

Si l’échantillon pour l’analyse de la Demande biochimique en oxygène (totale ou carbonée ou dissous ou carbonée et dissous) a été congelé par le client (ou à la réception) il faut utiliser le nom complet d’analyse dans le commentaire ajouté, par exemple :

"*L'échantillon pour l'analyse de la Demande biochimique en oxygène **totale** a été congelé par le client.*"
 
Si les plusieurs paramètres de DBO sont demandées par le client (DBOT01 et DBOC01, ou DBOT04 et DBOC02) il faudrait ajouter le commentaire avec le nom complet d’analyse pour CHAQUE paramètre de la DBO concernée, par exemple :

"*L'échantillon pour l'analyse de la Demande biochimique en oxygène **totale** a été congelé par le client*.   
*L'échantillon pour l'analyse de la Demande biochimique en oxygène **carbonée** a été congelé par le client.*"
