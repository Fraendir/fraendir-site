# Encyclopédie Animoria V2

La page d'accueil `index.html` et son CSS `accueil-v2.css` n'ont pas été modifiés.

## Installation
Téléverser tous les fichiers du ZIP dans le dépôt GitHub Pages, à la racine, en conservant les noms. La page est accessible via `encyclopedie.html`.

## Contenu
- `animaux.json` : 159 entrées extraites du fichier Dart transmis, classées par nom lors de l'affichage, avec filtres Terre/Eau/Air.
- `encyclopedie.html`, `encyclopedie.js`, `encyclopedie-v2.css` : interface avec liste à gauche et fiche à droite.
- Les quatre illustrations existantes sont réutilisées lorsqu'un nom correspond. Les autres sont volontairement remplacées par un espace réservé.
- Les informations zoologiques proviennent de la base de l'application et n'ont pas encore été vérifiées auprès de sources scientifiques. Les cartes de répartition et photographies ne sont pas encore incluses.
- Les 159 entrées correspondent au fichier transmis, pas nécessairement aux espèces actuellement publiées sur Google Play. Il faut confirmer le périmètre avant mise en ligne publique.

## Ajouts futurs
Ajouter un objet dans `animaux.json` avec un `slug` unique et ses informations, puis placer une image dans le dépôt et renseigner son chemin dans `carte`. Le catalogue se met à jour automatiquement lors du rechargement du site.

## Prévisualisation locale
Depuis le dossier : `python -m http.server 8000`, puis ouvrir `http://localhost:8000/encyclopedie.html`.
