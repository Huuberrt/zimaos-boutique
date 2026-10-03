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
