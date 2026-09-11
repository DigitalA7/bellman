# 02 — Groth16 et paramètres

Le crate `groth16/` met en œuvre génération des paramètres, preuve et vérification.
La phase de paramètres dépend de la structure exacte du circuit.
La clé de preuve contient les éléments nécessaires au prouveur.
La clé de vérification lie les entrées publiques à ce même circuit.
Une paire de clés ne doit jamais être réutilisée pour un circuit structurellement différent.
Les contributions secrètes d’une cérémonie doivent être détruites pour préserver la soundness.
La préparation de la clé de vérification optimise les contrôles répétés.
Les artefacts doivent être versionnés avec le code qui les a produits.

Suite : [témoin et entrées publiques](03-temoin-entrees.md).
