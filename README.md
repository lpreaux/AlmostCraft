# AlmostCraft

Un moteur de jeu voxel 3D développé en Java avec OpenGL, créé dans un objectif d'apprentissage du développement de jeux vidéo.

> *"It's not Minecraft... but it's almost there!"*

## 🎯 Objectif

Projet éducatif pour comprendre les mécanismes d'un moteur de jeu voxel (type Minecraft) : génération procédurale de terrain, rendu 3D optimisé, physique et systèmes de chunks.

## 🚀 État du moteur

- [x] Configuration du projet avec Gradle
- [x] Rendu OpenGL avec LWJGL
- [x] Système de caméra FPS
- [x] Génération procédurale de terrain
- [x] Gestion des chunks (16×16×256)
- [x] Greedy meshing et suppression des faces cachées
- [x] Textures, shaders, frustum culling et occlusion culling
- [ ] Système de collision et physique joueur
- [ ] Placement et destruction de blocs
- [ ] Système d'éclairage (skylight + block light)

## 🛠️ Technologies

- **Langage** : Java 23
- **Build** : Gradle (Kotlin DSL)
- **Graphique** : LWJGL 3 (OpenGL)
- **Mathématiques** : JOML

## 📦 Installation

```bash
git clone https://github.com/lpreaux/almostcraft.git
cd almostcraft
./gradlew run
```

## 🎮 Contrôles

- **WASD** (**ZQSD** sur un clavier AZERTY) : déplacement horizontal
- **Souris** : Regarder autour
- **Espace / Maj gauche** : monter / descendre en caméra libre
- **F1** : capturer ou libérer le curseur
- **F3** : afficher ou masquer les statistiques mémoire
- **Échap** : Menu/Quitter

Le raycasting et les interactions de placement/destruction figurent encore dans la feuille de route ; aucun contrôle souris n'est annoncé avant leur implémentation.

## 📚 Ressources d'apprentissage

Ce projet suit les concepts de :
- [LWJGL Game Development](http://lwjgl.org/)
- Minecraft Wiki (techniques voxel)
- Articles sur le greedy meshing et l'optimisation

## 🤝 Contribution

Projet personnel d'apprentissage, mais les suggestions et retours sont bienvenus !

## 📝 License

MIT License - Projet éducatif libre d'utilisation

---

*Développé par Lucas Préaux ([@lpreaux](https://github.com/lpreaux)).*
