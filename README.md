# Bod's Biome Macro — canal de mise à jour

Ce dépôt ne sert qu'à **une chose** : `version.json` indique à la macro la dernière version disponible.

## Comment publier une mise à jour

1. Héberge le nouveau `.zip` de la macro quelque part (Discord, un hébergeur de fichiers, etc.).
2. Édite `version.json` ici :
   - `version` : le nouveau numéro (ex. `2.3`)
   - `url` : le lien de téléchargement du zip
   - `notes` : ce qui change (affiché dans le popup)
3. Sauvegarde. Les macros de tout le monde verront la mise à jour au prochain lancement.

La macro **ne télécharge jamais** toute seule : elle ouvre le lien dans le navigateur.
