# 2. Variables booléennes et arithmétiques

Boolean et FpVar fournissent des valeurs calculables dans le circuit. Une opération Rust sur ces objets ne calcule pas seulement un résultat : elle construit aussi la relation qui devra être satisfaite.

Une variable booléenne doit être contrainte à 0 ou 1. Une représentation field non bornée ne suffit pas à exprimer cette propriété.

Les gadgets arithmétiques factorisent l’addition, la multiplication, l’inversion et les sélections conditionnelles. Ils réutilisent les constantes et les variables quand cela réduit le nombre de contraintes.

Les erreurs de synthèse remontent les allocations impossibles et les incohérences du système.

Suite : [Gadgets d’égalité et de comparaison](03-egalite-comparaison.md).
