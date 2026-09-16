# 4. Bits, octets et conversions

Les traits de conversion transforment un gadget en bits little-endian, octets ou éléments de champ. Une conversion peut être uniquement représentative ou ajouter les contraintes garantissant l’unicité du résultat.

Les méthodes non uniques sont utiles quand le protocole connaît déjà une borne ou n’a besoin que d’un encodage pratique. Elles ne doivent pas être utilisées comme range check implicite.

Les conversions vers le champ de contrainte sont importantes pour les hashes, signatures et encodages d’objets composites. La convention d’ordre des octets doit être stable.

Toute frontière de sérialisation doit préciser l’endianness, la longueur et les valeurs refusées.

Suite : [Groupes, champs et gadgets composés](05-gadgets-composes.md).
