GOMYCODE — CRM B2B | PAQUET COMPLET

Cette archive contient le code source et les fichiers compilés du site et de son API.
Le fichier preview-dashboard.jpg montre le tableau de bord tel qu’affiché dans le preview Replit, avec les nouvelles cartes Charges estimées et Gain estimé HT.

STRUCTURE
- artifacts/b2b-pipeline/ : interface React, sources et build compilé
- artifacts/api-server/ : API, sources et build compilé
- lib/ : contrat API, client généré et schémas PostgreSQL
- pnpm-workspace.yaml et pnpm-lock.yaml : configuration des dépendances

LANCEMENT DANS REPLIT
1. Installer les dépendances : pnpm install
2. Configurer une base PostgreSQL dans Replit Database.
3. Créer les tables : pnpm --filter @workspace/db run push
4. Démarrer l’API : pnpm --filter @workspace/api-server run dev
5. Démarrer le site : pnpm --filter @workspace/b2b-pipeline run dev

Les fichiers de secrets (.env, clés et mots de passe) ne sont pas inclus dans cette archive.
