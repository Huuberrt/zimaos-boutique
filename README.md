# Boutique ZimaOS de Hubert

Source d'applications ajoutée à ZimaOS (format des boutiques tierces :
`Apps/<Nom>/docker-compose.yml`, identifiant = `name:`). Elle sert à :

- annoncer dans ZimaOS les mises à jour des applications du NAS ;
- proposer des applications à essayer.

**Public : n'y mettre aucun secret.** Lors d'une mise à jour, ZimaOS garde le
Compose installé sur le NAS et ne prend à la fiche que l'image.

Contexte et décisions : dépôt `nas-zimaos`, chantier 24.

Adresse à déclarer dans ZimaOS :
`https://github.com/Huuberrt/zimaos-boutique/archive/refs/heads/main.zip`
