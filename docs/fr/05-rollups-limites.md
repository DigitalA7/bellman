# 05 — Usage rollup et limites

Un rollup peut utiliser Groth16 pour vérifier succinctement une transition d’état.
Le circuit doit engager l’ancienne racine, la nouvelle racine et les données de lot pertinentes.
La disponibilité des données n’est pas garantie par Bellman lui-même.
La résistance à la censure et les règles de séquenceur restent hors du système de preuve.
Ce parcours couvre R1CS, paramètres Groth16, témoins, entrées publiques et vérification.
Il ne valide aucun circuit utilisateur, cérémonie ni contrat vérificateur.
Le dépôt a déplacé Groth16 dans un crate dédié ; les versions doivent être suivies ensemble.
Aucune installation, compilation ou exécution n’a été effectuée ; les tests amont restent la référence.
