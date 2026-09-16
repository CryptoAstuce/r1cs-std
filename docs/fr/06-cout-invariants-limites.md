# 6. Coût, invariants et limites

Un gadget correct doit documenter les contraintes ajoutées, les hypothèses sur les plages et les erreurs possibles. Le nombre de contraintes dépend du champ, de la représentation et de la version du backend R1CS.

Une méthode peut produire la bonne valeur sur un témoin de test tout en oubliant une contrainte essentielle. La validation doit donc vérifier les contraintes, les cas limites et les entrées mal formées.

La bibliothèque fournit des composants génériques ; elle ne choisit pas le système de preuve, les paramètres de sécurité ni la sémantique métier du circuit.

Périmètre : ce parcours traduit allocation, booléens, champs, comparaisons, conversions et gadgets composés du dépôt. Aucune installation, compilation ou exécution de test n’a été effectuée. Consulter les suites officielles pour une validation concrète.

Retour : [sommaire du parcours](README.md).
