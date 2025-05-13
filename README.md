# Simple Fishing Bot v0.1.16

Un bot de pêche simple pour **World of Warcraft**, écrit en AutoIt. Il simule l'appui sur une touche pour lancer la ligne et détecte les mouvements du flotteur afin de remonter automatiquement le poisson.

## 🎯 Fonctionnalités

- Simulation de l'appui sur la touche de pêche
- Recherche du flotteur à l'écran via la couleur
- Détection des mouvements du flotteur
- Clic automatique pour remonter le poisson
- Interface graphique (GUI) simple et intuitive
- Fonction de debug intégrée
- Zone de détection configurable
- Fichiers compilés disponibles pour une utilisation immédiate

## 🖥️ Prérequis

- Windows
- Résolution adaptée à la zone de détection définie
- Jeu lancé en mode fenêtré recommandé
- Couleurs et tolérances ajustées en fonction de votre interface

## 🔧 Utilisation

1. Lancer **World of Warcraft** et placer le flotteur dans la zone visible définie.
2. Exécuter `FishingBot.exe` (ou lancer le script `.au3` avec AutoIt).
3. Définir :
   - La zone de détection (X/Y haut gauche et bas droite)
   - La couleur du flotteur et ses variations
   - La touche de pêche utilisée (par défaut `i`)
4. Appuyer sur `F10` pour lancer le bot.
5. `F11` pour mettre en pause, `K` pour quitter.

## 🚀 Télécharger

Rendez-vous dans l'onglet [Releases](https://github.com/tonutilisateur/tonrepo/releases) pour télécharger la dernière version compilée (`.exe`).

## 🛠️ Compilation (optionnel)

Tu peux compiler le script avec AutoIt si tu veux l’adapter ou l'améliorer :

```bash
Aut2Exe.exe /in "FishingBot.au3" /out "FishingBot.exe"
```

## 📷 Aperçu

![Fishing Bot in action](./turtle.jpg)

## ❗ Avertissement

Ce projet est fourni à titre éducatif uniquement. L’utilisation de bots dans les jeux en ligne peut violer les conditions d’utilisation du jeu. Utilisez-le à vos risques et périls.

---

**Auteur** : [GeoHolz](https://github.com/GeoHolz)

N’hésitez pas à ouvrir une *Issue* ou à proposer une *Pull Request* pour contribuer !




