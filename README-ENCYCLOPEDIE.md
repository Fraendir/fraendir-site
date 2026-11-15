# Extension Animoria

Déployer tous les fichiers du dossier à la racine du dépôt GitHub Pages (branche principale).

- `animoria.html` : page Animoria
- `encyclopedie.html` : recherche et filtres
- `animal.html?espece=dodo` : fiche individuelle
- `animaux.json` : catalogue modifiable, une entrée par espèce

Quatre espèces initiales issues des images disponibles. Les photos réelles et cartes de répartition ne sont pas incluses : vérifier les licences et les données avant publication. Les fiches sont une base éditoriale, non un inventaire complet du jeu.

Prévisualisation : servir le dossier avec `python -m http.server 8000`, puis ouvrir http://localhost:8000/ (les fichiers JSON ne chargent pas correctement via file://).
