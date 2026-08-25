# Cabinet de Psychologie Veiga - Démonstration Cloudflare

Version autonome de démonstration du logiciel PC et de la borne patient.

## Déploiement Cloudflare Pages

1. Dans Cloudflare, ouvrez **Workers & Pages** puis **Create application**.
2. Choisissez **Pages** puis **Connect to Git**.
3. Sélectionnez le dépôt `zlatinho92/veigapsychotest`.
4. Paramètres de construction :
   - Framework preset : `None`
   - Build command : laisser vide
   - Build output directory : `/`
5. Lancez le déploiement.

Les données de test restent dans le navigateur avec `localStorage`. Cette version n’utilise ni Discord, ni base de données, ni informations réelles.
