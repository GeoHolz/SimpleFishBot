# Simple Fishing Bot v0.2.1

Un bot de pêche simple pour **World of Warcraft**, écrit en AutoIt. Il simule l'appui sur une touche pour lancer la ligne et détecte les mouvements du flotteur afin de remonter automatiquement le poisson. Il intègre désormais un système OCR pour filtrer les poissons à conserver.

## 🎯 Fonctionnalités

- Simulation de l'appui sur la touche de pêche
- Recherche du flotteur à l'écran via la couleur
- Détection des mouvements du flotteur
- Clic automatique pour remonter le poisson
- Interface graphique (GUI) simple et intuitive
- Fonction de debug intégrée
- Zone de détection configurable
- **OCR intégré** (via UWPOCR) pour reconnaître les poissons pêchés
- **Filtrage intelligent** : clic droit uniquement si le poisson est dans la liste souhaitée
- Case à cocher pour activer/désactiver l’OCR
- Saisie libre des noms de poissons à garder (ex : "Bar, Saumon doré")

## 🖥️ Prérequis

- Windows
- Résolution adaptée à la zone de détection définie
- Jeu lancé en mode fenêtré recommandé
- Couleurs et tolérances ajustées en fonction de votre interface
- [UWPOCR](https://github.com/adamdriscoll/UniversalWindowsPlatformOCR) installé (pour la reconnaissance de texte)

## 🔧 Utilisation

1. Lancer **World of Warcraft** et placer le flotteur dans la zone visible définie.
2. Exécuter `FishingBot.exe` (ou lancer le script `.au3` avec AutoIt).
3. Dans l’interface :
   - Définir la zone de détection (X/Y haut gauche et bas droite)
   - Entrer la couleur du flotteur et la tolérance
   - Spécifier la touche de pêche (par défaut `i`)
   - **Cocher la case "OCR Choix poisson"** si vous souhaitez filtrer les prises
   - Saisir les noms des poissons à conserver dans la zone prévue (séparés par des virgules)
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
