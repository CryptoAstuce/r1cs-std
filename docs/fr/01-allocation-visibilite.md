# 1. Allocation et modes de visibilité

Le trait AllocVar transforme une valeur native en variable utilisable dans un système de contraintes. Le mode distingue une constante, une entrée publique et un témoin privé.

Une allocation publique ajoute une valeur aux instances vérifiées par le protocole ; une allocation witness conserve la donnée dans le circuit. Cette distinction est une propriété de confidentialité, pas seulement une optimisation.

Les types de gadgets conservent une référence au ConstraintSystem et exposent des opérations qui ajoutent les contraintes nécessaires.

Un constructeur doit rejeter une valeur qui ne peut pas être représentée correctement dans le champ ou le format attendu.

Suite : [Variables booléennes et arithmétiques](02-booleens-arithmetique.md).
