# 01 — Circuit et synthèse R1CS

Bellman représente un calcul par un système de contraintes de rang 1.
Le trait `Circuit` synthétise variables et relations dans un `ConstraintSystem`.
Les allocations publiques et privées ont des rôles différents lors de la vérification.
Une contrainte impose le produit de deux combinaisons linéaires égal à une troisième.
Le témoin fournit les valeurs, mais seules les contraintes définissent ce qui est prouvé.
Une variable allouée sans relation peut rester arbitraire.
La revue doit donc suivre chaque sortie vers les contraintes qui la lient aux entrées.
Cette discipline prévient les circuits sous-contraints.

Suite : [Groth16 et paramètres](02-groth16-parametres.md).
