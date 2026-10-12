# Micheline Desktop — releases

Dépôt public des binaires de **Micheline Desktop** (le code source, lui, est privé).

Chaque évolution du dossier `apps/desktop` publiée sur `main` pousse ici :

- l'installateur macOS (`.dmg`) et Windows (`.exe`) ;
- les paquets de mise à jour signés (`.app.tar.gz`, `.sig`) ;
- `latest.json`, le manifeste que l'application installée interroge pour se mettre à jour toute seule.

Rien à faire à la main : Micheline télécharge la nouvelle version en tâche de fond et propose de redémarrer.
