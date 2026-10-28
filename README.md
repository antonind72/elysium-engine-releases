# Moteur d'images Elysium : releases

Ce dépôt ne contient que les versions publiées du moteur d'images Elysium. L'application
Elysium les télécharge pour installer le moteur et le mettre à jour. Le code du moteur reste
privé.

Chaque release `vX.Y.Z` contient :

- le paquet du moteur (`.whl`) ;
- `constraints.txt` : les versions de dépendances testées ;
- `manifest.json` : version, Python, index PyTorch, SHA-256 et taille de chaque fichier.
  L'application vérifie chaque fichier téléchargé avec ce manifeste.

Les releases sont publiées automatiquement par la CI du moteur, à chaque version.
