# Inception - Ranorex

Ce dossier contient tous les éléments pour exécuter de l'inception avec un projet Ranorex.

Le projet de référence est le suivant : https://github.com/SquashTF-workshop/ranorexDocCheck

Les fichiers présent dans ce dossier sont les fichiers générés suite à l'exécution
du projet.

En l'état on ne peut envoyer qu'une seule suite Ranorex car l'outil génère un rapport (rxlog.data) 
par suite de test.

Les résultats présents dans ce dossier concernent la suite FirefoxDocCheck qui contient 2 cas de tests :
FirefoxOK et FirefoxKO.

Exemple de référence de test à indiquer côté TM : 

ranorexDocCheck/ranorexDocCheck.sln#RanorexDocCheckCSharp#FirefoxDocCheck#FirefoxOK : Success

ranorexDocCheck/ranorexDocCheck.sln#RanorexDocCheckCSharp#FirefoxDocCheck#FirefoxKO : Failure

ranorexDocCheck/ranorexDocCheck.sln#RanorexDocCheckCSharp#FirefoxDocCheck : Failure

