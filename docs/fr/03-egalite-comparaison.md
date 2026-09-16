# 3. Gadgets d’égalité et de comparaison

EqGadget fournit une égalité contrainte entre deux valeurs de circuit. Enforcer l’égalité ajoute une relation ; comparer hors circuit ne prouve rien sur le witness.

Les gadgets de comparaison construisent des résultats booléens pour supérieur, inférieur ou égal. Ils nécessitent généralement une représentation en bits ou une décomposition compatible avec le champ.

Une sélection conditionnelle choisit entre deux valeurs selon un Boolean déjà contraint. Elle permet d’exprimer des branches sans révéler le chemin suivi.

Le concepteur doit vérifier que les domaines de valeurs sont bornés : comparer des entiers modulo le champ sans range check peut donner une interprétation inattendue.

Suite : [Bits, octets et conversions](04-bits-octets-conversions.md).
