# Gold Finance — Analyse d'activité bancaire

Application web statique pour analyser les extraits bancaires de Gold Finance
(MoneyGram, Western Union, RIA, versements espèces).

## Contenu

- `index.html` — application complète (React + Recharts + PapaParse via CDN)

## Déploiement Vercel

Aucune build step. Vercel sert directement `index.html` à la racine.

## Stockage

Toutes les données restent dans le navigateur de l'utilisateur (`localStorage`).
Aucun serveur, aucune base de données. Idéal pour la confidentialité des
extraits bancaires.
