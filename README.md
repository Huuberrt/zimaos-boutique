# Boutique ZimaOS de Hubert

Boutique d'applications pour le NAS (ZimaOS 1.7) : annoncer dans ZimaOS les
mises à jour des applications suivies, et proposer des applications à essayer.

**Public : n'y mettre aucun secret.**

Les fiches sources sont dans `Apps/<Nom>/docker-compose.yml` (bloc `x-casaos`,
avec `id` et `version`). À chaque push sur `main`, le workflow
`.github/workflows/publier.yml` les transforme au format v2 de ZimaOS avec
`IceWhaleTech/build-appstore-action` et publie le résultat sur GitHub Pages.

Adresse à déclarer dans ZimaOS (boutique communautaire, bouton +) :

    https://huuberrt.github.io/zimaos-boutique/store.json

**En archive depuis le 2026-10-14** (décision de Hubert) : publication sur
GitHub Pages coupée, dépôt archivé sur GitHub. La génération refusait le
dossier `Apps/` vide (workflow en échec depuis le 2026-10-07), si bien que la
boutique publiée annonçait encore les deux fiches whoami de l'essai du
chantier 24 (`nas-zimaos`). Elle n'était déclarée dans aucun ZimaOS. Projet
pour plus tard : voir `ETAT.md`.
