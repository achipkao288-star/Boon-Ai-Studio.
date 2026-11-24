# BOON AI STUDIO — Prototype 0.1

## Ce que contient cette première version
- Interface responsive pour téléphone et ordinateur.
- Français / anglais.
- Choix cinéma réaliste ou animation 3D.
- Préparation d'un storyboard à partir d'une histoire.
- Modification et ajout / suppression de scènes.
- Construction de prompts de génération par scène.
- Import et aperçu local d'une image de référence.
- Sauvegarde locale dans le navigateur.
- Export du projet au format JSON et copie des prompts.

## Lancer le site
1. Décompressez `boon_ai_studio_prototype.zip`.
2. Ouvrez le dossier `boon_ai_studio`.
3. Ouvrez `index.html` avec Chrome, Firefox ou Edge.
4. Sur Android, vous pouvez ouvrir le fichier avec Chrome depuis le gestionnaire de fichiers. Si le navigateur bloque l'ouverture locale, utilisez un hébergement statique gratuit (par exemple GitHub Pages).

## Important : génération vidéo
Cette version est un prototype de préproduction. Elle ne génère pas encore de clips vidéo réels.
Pour cela, il faudra ajouter un backend sécurisé qui appelle un fournisseur de génération vidéo (modèle hébergé ou API). Ne placez jamais une clé API secrète dans `index.html` ou dans le JavaScript visible du navigateur.

## Prochaine étape technique
- Choisir un fournisseur vidéo et vérifier ses quotas, sa disponibilité régionale, ses conditions et ses coûts.
- Créer un backend (par exemple Python + FastAPI).
- Ajouter une file de tâches, car la génération vidéo peut prendre du temps.
- Stocker les clips et assembler le résultat avec FFmpeg.
- Ajouter la gestion des erreurs, des limites d'utilisation et des droits sur les images importées.

## Fichiers
- `index.html` : application complète autonome.
- `README.md` : instructions.
