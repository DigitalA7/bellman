# 04 — Produire et vérifier une preuve

La preuve Groth16 compresse la satisfaction du R1CS en quelques éléments de courbe.
Le prouveur utilise des aléas pour préserver le zero-knowledge.
Le vérificateur combine preuve, clé préparée et entrées publiques dans des pairings.
Une erreur de désérialisation ou un point invalide doit être rejeté avant le calcul cryptographique.
Les formats canoniques empêchent plusieurs encodages d’un même objet.
Les API de génération aléatoire dépendent d’une source d’entropie correcte.
Une preuve valide n’établit ni fraîcheur ni unicité sans nonce ou contexte public.
Ces propriétés restent à construire au niveau applicatif.

Suite : [rollups et limites](05-rollups-limites.md).
