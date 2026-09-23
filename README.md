# The Royal Race

Version jouable du jeu de courses hippiques, publiée le 23 septembre 2026.

## Lancer le jeu

Ouvrir `index.html` dans un navigateur récent, ou servir le dossier avec un serveur statique local :

```sh
python3 -m http.server 8000
```

Puis ouvrir `http://localhost:8000`.

La scène 3D charge Three.js depuis un CDN ; une connexion Internet est nécessaire pour cette dépendance. Les images du jeu sont incluses dans `assets/`.

## Commandes

- `F` : sortir des stalles après le compte à rebours.
- Flèches gauche et droite : placement sur la piste.
- Espace ou bouton SPRINT : accélération.
- `A` et `E` : regarder à gauche et à droite.

L'endurance varie selon le sprint, le placement dans le sillage et les trajectoires en virage. Après l'arrivée de tous les chevaux, le classement donne accès au podium.

## Version en ligne

[Ouvrir le jeu](https://the-royal-race.muller-thomas1.chatgpt.site).
