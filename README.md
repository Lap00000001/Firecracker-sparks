# Firecracker Sparks

> Petit jeu en cours de développement avec **Godot 4** et **GDScript** — un projet d’apprentissage, pas seulement un dépôt de code.

[![Godot](https://img.shields.io/badge/Godot-4.6-478CBF?logo=godot-engine&logoColor=white)](https://godotengine.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![GDScript](https://img.shields.io/badge/Langage-GDScript-478CBF)](https://docs.godotengine.org/fr/stable/tutorials/scripting/gdscript/index.html)

---

## À propos

**Firecracker Sparks** est un projet personnel pour apprendre le développement de jeux : scènes, scripts, physique et itérations dans l’éditeur Godot, avec le code versionné sur GitHub.

Le dépôt est volontairement simple au départ : une base saine (Git, `.gitignore`, structure claire) sur laquelle construire les mécaniques de jeu au fil de l’eau.

## Prérequis

| Outil | Version recommandée |
|--------|----------------------|
| [Godot Engine](https://godotengine.org/download) | **4.6** (édition Standard) |
| [Git](https://git-scm.com/) | 2.x |

> Utilise l’édition **Standard** (pas .NET) tant que le projet reste en GDScript pur.

## Démarrage rapide

1. **Cloner le dépôt**
   ```bash
   git clone https://github.com/Lap00000001/Firecracker-sparks.git
   cd Firecracker-sparks
   ```

2. **Ouvrir dans Godot**
   - Lance le *Project Manager*
   - *Import* ou *Open* → sélectionne le fichier `project.godot`

3. **Lancer le jeu**
   - Dans l’éditeur : **F5** (ou le bouton ▶ Play)

4. **Éditer le code (optionnel)**
   - Ouvre le même dossier dans Cursor / VS Code pour travailler sur les fichiers `.gd`
   - Garde Godot ouvert pour les scènes, l’inspecteur et les tests en direct

## Structure du projet

```
firecracker-sparks/
├── project.godot      # Configuration principale du projet
├── icon.svg           # Icône du jeu
├── icon.svg.import    # Métadonnées d’import (à versionner)
├── .gitignore         # Fichiers exclus de Git
├── .gitattributes     # Normalisation des fins de ligne
└── README.md          # Ce fichier
```

Les dossiers de scripts (`scripts/`), scènes (`scenes/`) et assets (`assets/`) seront ajoutés au fur et à mesure du développement.

## Stack technique

- **Moteur** : Godot 4.6
- **Langage** : GDScript
- **Physique 3D** : Jolt Physics
- **Rendu** : GL Compatibility (Windows : D3D12)

## Ce qui est versionné (et ce qui ne l’est pas)

| Versionné ✅ | Ignoré ❌ |
|-------------|----------|
| `project.godot`, scènes, scripts | `.godot/` (cache éditeur) |
| Assets sources (`.svg`, images, sons…) | Builds d’export (`export/`, `.apk`, …) |
| Fichiers `.import` à côté des assets | Fichiers système (`Thumbs.db`, `.DS_Store`) |

Le dossier `.godot/` est recréé automatiquement à l’ouverture du projet — inutile (et déconseillé) de le pousser sur GitHub.

## Objectifs d’apprentissage

- [ ] Créer une première scène jouable
- [ ] Écrire un script GDScript (mouvement ou interaction)
- [ ] Comprendre la différence éditeur Godot ↔ éditeur de code
- [ ] Utiliser Git pour sauvegarder chaque étape

## Contribution

Projet personnel pour l’instant. Les idées et retours restent les bienvenus via les *Issues* GitHub.

## Licence

Ce projet est sous licence **MIT** — voir le fichier [LICENSE](LICENSE).

---

<p align="center">
  <sub>Fait avec Godot — en apprenant, une étincelle à la fois.</sub>
</p>
