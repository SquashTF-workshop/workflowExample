# Inception - Cucumber

Ce dossier contient tous les éléments pour exécuter de l'inception avec un projet Cucumber.

Le projet de référence est le suivant : https://github.com/SquashTF-workshop/cucumberStockManagement

Les fichiers présents dans ce dossier sont les fichiers générés suite à l'exécution
du projet.

Les rapports doivent respecter le format suivant :

  * report.json
  
  * report.xml

On ne peut envoyer que ces 2 fichiers mais leur contenu peut être contrôlé via des options.

Exemple de référence de test à indiquer côté TM : 

  * cucumberStockManagement/src/test/resources/concombre/DuplicateTags.feature#Stock Management To Check Duplicate Execution#Current stock duplicate : Success

  * cucumberStockManagement/src/test/resources/concombre/DuplicateTags.feature#Stock Management To Check Duplicate Execution#Error in stock duplicate : Failure
  
  * cucumberStockManagement/src/test/resources/concombre/TagInheritance.feature#Stock Management To Check Tag Inheritance : Failure