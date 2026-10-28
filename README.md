# Portfolio de Tom Guimont

Portfolio local en français, avec une direction artistique qui mêle informatique et nature : vert forêt, accents vert tendre et illustration d’un arbre connecté à un terminal. HTML, CSS et JavaScript, sans dépendances ni compilation.

## Lancement

Depuis ce dossier :

```bash
npm run dev
```

Ouvrir http://localhost:3000. Arrêter le serveur avec Ctrl+C.

La page principale met en avant quatre projets et évoque brièvement le parcours. Chaque carte ouvre une page HTML distincte : Groupie Tracker, ASCII Art Web, Forum et Blabla.

## Personnalisation

- `dist/app.js` : textes, profil Git, descriptions des projets et illustrations vectorielles.
- `dist/styles.css` : mise en page responsive, couleurs et typographie.
- `dist/assets/blabla.png` : illustration reprise des ressources locales de Blabla.

Les descriptions s’appuient sur les projets locaux dans `../autre/projets finis`, `../forum` (branche `commentaire`) et `../blabla`. Les illustrations de Groupie Tracker, ASCII Art Web et Forum sont conceptuelles et explicitement identifiées. Aucun CV, adresse email ou coordonnées personnelles supplémentaires n’ont été inventés.

Le portfolio est autonome : il n’exécute pas les quatre applications et n’appelle pas leurs API. Il ne nécessite pas de connexion Internet ; le lien du profil Git est externe. Aucune publication n’a été effectuée.
