# 5. Groupes, champs et gadgets composés

La bibliothèque compose des gadgets pour les champs, courbes elliptiques, matrices, vecteurs et autres structures cryptographiques. Chaque composant expose des opérations de circuit plutôt qu’une simple valeur native.

Les gadgets de groupe doivent préserver les lois attendues et les conditions de sous-groupe. Une addition contrainte n’est utile que si les points d’entrée ont été validés dans le modèle choisi.

Les structures composées propagent le mode de visibilité à leurs éléments et réutilisent les implémentations d’allocation et de conversion.

Cette composition réduit le code de circuits, mais elle masque parfois un coût élevé : plusieurs opérations de champ peuvent se cacher derrière une méthode apparemment simple.

Suite : [Coût, invariants et limites](06-cout-invariants-limites.md).
