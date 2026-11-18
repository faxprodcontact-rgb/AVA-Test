# AVA — site de test

Site de test d'AVA (jeu de Simon, dépôt `AVA`), servi par GitHub Pages : https://faxprodcontact-rgb.github.io/AVA-Test/

- `ava/` : la version web du jeu (fabriquée par Godot, `index.html` + `index.pck` + moteur), l'APK Android
  (`ava/AVA.apk`) et la page de connexion Google des applis (`ava/connexion-google.html`).
- `ava-serveur.json` : l'adresse du serveur du jeu (Supabase) et sa clé publique, lue par la version web (`../ava-serveur.json`).
- `index.html` (= `ava-accueil.html`) : la page d'accueil ; `ava-confidentialite.html`, `ava-conditions.html`,
  `ava-mentions.html` : les pages légales.

Avant le 18/11/2026, ce site était dans le dépôt `fuze-arena-test`, dossier `ava/`.
