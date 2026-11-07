# Aura

Lecteur FLAC perso, installable sur l'écran d'accueil. Les fichiers audio restent sur l'appareil (stockés dans le navigateur), rien n'est envoyé en ligne.

## Mise en ligne (GitHub Pages)
1. Crée un dépôt `aura` sur GitHub et envoie tous les fichiers de ce dossier à la racine.
2. Settings → Pages → Source : « Deploy from a branch » → `main` / `(root)` → Save.
3. Après 1 à 2 minutes : `https://<ton-pseudo>.github.io/aura/`

## Installation sur le téléphone
Ouvre l'adresse dans Chrome → ⋮ → **Installer l'application**.

## Mise à jour
Après avoir modifié des fichiers, change `aura-v1` en `aura-v2` dans `sw.js` pour forcer le rafraîchissement du cache.
