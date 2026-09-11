# 03 — Témoin et entrées publiques

Le prouveur connaît une affectation complète satisfaisant les contraintes.
Le vérificateur ne reçoit que la preuve et les entrées déclarées publiques.
L’ordre des entrées publiques fait partie du contrat cryptographique.
Une application doit lier explicitement racine, domaine, version et autres données métier.
Omettre un engagement public peut rendre une preuve réutilisable dans un autre contexte.
Les valeurs sont interprétées dans un corps fini ; les bornes entières ne sont pas implicites.
Les contrôles de plage doivent être encodés dans le circuit lorsqu’ils sont nécessaires.
La confidentialité ne corrige jamais une spécification de circuit incomplète.

Suite : [preuve et vérification](04-preuve-verification.md).
