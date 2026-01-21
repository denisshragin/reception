## Comment écrire des commentaires
:memo: Afin de faire les commentaires ajoutés dans les CAO plus claires, plus cohérents et exemptes des fautes d’orthographe et de grammaire plusieurs commentaires prédéfinis ont été modifiés et plusieurs nouveaux commentaires ont été ajoutés dans LabPlus en décembre 2025.
 
### Les changements dans les commentaires de saisie / vérif.
 
Voir le fichier joint pour les explications des changements effectués.

**Voici quelques règles de base pour écrire des bons commentaires :**

- Ne pas laisser la première ligne vide.
- Mettre un point ‘ . ‘ à la fin d’une phrase.
- Mettre une espace avant et après ‘ : ’.
- Mettra chque commentaire sur une nouvelle ligne.
- Mettre une espace entre le nombre et l’unité de mesure, par exemple ’10.36 mg/L’.

| Paramètre      | Unité    | Unité                      |
|----------------|----------|-------------------------------|
| Température    | °C       | degré Celcius                 |
| Conductivité   | µS/cm    | microSymens par centimètre    |
| oPO4           | mg/L     | milligram par litre           |
| Débit          | m3/j     | metre cubic par jour          |


S’il s’agite d’un commentaire avec « * » (sauf le commentaire **"* La température a été omise lors de la réception de l'échantillon."**) il faudrait remplacer « * » par la valeur appropriée (date, heure, température), cependant il ne faudrait pas supprimer les espaces qui entournent « * » ni ajouter des nouvelles espaces ni avant, ni après.  
Par exemple : « Température à la réception : * °C. » doit être correctement modifieé comme *« Température à la réception : 15.2 °C. »* et pas comme « Température à la réception :     15.2°C. ».  

S’il s’agite d’un commentaire avec « XXX » (YYY ou ZZZ) il faudrait remplacer « XXX » par le nom d’analyse complet.  
Par exemple : « L’échantillon pour l'analyse de XXX a été reçu après l'expiration du délai de conservation réglementaire. L'analyse a été effectuée à la demande du client. » doit être modifié comme ici : *« L’échantillon pour l'analyse du pH-15°C a été reçu après l'expiration du délai de conservation réglementaire. L'analyse a été effectuée à la demande du client. »* (**XXX a été remplacé par 'le pH-15°C'**).
 
 
Par exemple, au lieu d’utiliser le commentaire « pH reçu et analysé hors délai » il faudrait utiliser le commentaire prédéfini *« L’échantillon pour l'analyse du pH-15°C a été reçu après l'expiration du délai de conservation réglementaire. L'analyse a été effectuée à la demande du client. »*
ou *« L'échantillon pour l'analyse du pH EU a été reçu après l'expiration du délai de conservation réglementaire. L'analyse a été effectuée à la demande du client.»*
ou les deux commentaires ensemble si les deux analyses pH-15°C et pH EU sont demandées.

*«L'échantillon pour l'analyse du pH EU a été reçu après l'expiration du délai de conservation réglementaire. L'analyse a été effectuée à la demande du client*.  
*L'échantillon pour l'analyse du pH-15°C a été reçu après l'expiration du délai de conservation réglementaire. L'analyse a été effectuée à la demande du client.»*
 
 
#### DBO congélation par le client / au laboratoire.
Si l’échantillon pour l’analyse de la Demande biochimique en oxygène (totale ou carbonée ou dissous ou carbonée et dissous) a été congelé par le client (ou à la réception) il faut utiliser le nom complet d’analyse dans le commentaire ajouté, par exemple :

"*L'échantillon pour l'analyse de la Demande biochimique en oxygène **totale** a été congelé par le client.*"
 
Si les plusieurs paramètres de DBO sont demandées par le client (DBOT01 et DBOC01, ou DBOT04 et DBOC02) il faudrait ajouter le commentaire avec le nom complet d’analyse pour CHAQUE paramètre de la DBO concernée, par exemple :

"*L'échantillon pour l'analyse de la Demande biochimique en oxygène **totale** a été congelé par le client*. 
*L'échantillon pour l'analyse de la Demande biochimique en oxygène **carbonée** a été congelé par le client.*"
