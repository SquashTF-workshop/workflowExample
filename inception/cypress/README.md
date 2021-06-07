# Inception - Cypress

Ce dossier contient tous les éléments pour exécuter de l'inception avec un projet Cypress.

Le projet de référence est le suivant : https://github.com/SquashTF-workshop/cypressCalcSingleSpec

Le fonctionnement de Cypress cause quelques soucis car il créé un rapport par spec.
Des outils externes existent pour merge des rapports mais ceux-ci n'ont pas été testés car ils ne sont pas
présent par défaut avec Cypress.

Les rapports doivent respecter le format suivant :

  * {filename}-report.xml

Attention au nom du fichier, le parsing se fait sur le nom du fichier et sur les ".", donc un fichier sous 
la forme calculator.add.ok.spec.js sera identifié sous "calculator" et non le nom du fichier dans son intégralité.

Exemple de référence de test à indiquer côté TM : 

  * cypressCalcSingleSpec/cypress/integration/calculator.add.ok.spec.js : Success

  * cypressCalcSingleSpec/cypress/integration/subFolder/reverse.calculator.ko.spec.js : Failure