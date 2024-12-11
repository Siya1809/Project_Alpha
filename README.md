# Projet Alpha - Jeu Multijoueur 3D

## 🎮 Objectifs
Le **Projet Alpha** est un jeu multijoueur en 3D développé avec Unity. Les principales fonctionnalités incluent :

- Un système multijoueur géré avec [Mirror](https://mirror-networking.com/).
- Des mécaniques de tir et de rechargement immersives.
- La synchronisation des skins et des actions entre les joueurs.
- Une intelligence artificielle basique pour les bots, capable de suivre des parcours et de réagir aux joueurs.
- Un système de vote dans le tableau des scores.
- Une gestion dynamique des bots, remplacés par des joueurs humains lorsqu’ils rejoignent la partie.

## 🚀 Installation

### **Prérequis**
- Unity version 2022.3.52f1.
- Mirror (intégré via le Unity Package Manager).
- Git pour cloner le dépôt.

### **Étapes d'installation**
1. Clonez le projet :
   ```bash
   git clone https://github.com/Siya1809/Project_Alpha
   ```
2. Le jeu se trouve directement sur la racine. avec Projet Alpha.exe
## 🔄 Utilisation

### Hôte
1. Lancez un serveur en cliquant sur "Host" (mode serveur + client combiné).
2. Fournissez votre adresse IP (trouvable via `ipconfig` sous Windows) aux autres joueurs.

### Client
1. Entrez l’adresse IP de l’hôte dans le champ prévu, en gardant le port par défaut.
2. Cliquez sur "Client" pour rejoindre la partie.

### Local
Pour des fins académiques, il est possible de lancer plusieurs instances du jeu.
1. Lancer plusieurs fois Projet Alpha.exe
2. L’hôte peut lancer le jeu comme d'habitude.
3. Les clients peuvent rejoindre directement en cliquant sur "Client", en gardant l’adresse et le port par défaut.


### En jeu
- **Déplacements** : `Q`, `S`, `D`, `Z`.
- **Tir** : clic gauche de la souris.
- **Rechargement** : touche `R`.
- **Tableau des scores** : `Tab` pour consulter les performances des joueurs.
- **Vote** : Identifiez si un joueur est un bot ou non via le tableau des scores.

## 🏆 Fonctionnalités

- **Tir en vue FPS** : Une expérience immersive de jeu de tir.
- **Gestion des munitions et du rechargement** : Limitation des tirs par chargeur.
- **Personnalisation des skins et noms des joueurs** : Visibles par tous les participants.
- **Interaction avec les bots** : Réactions réalistes aux tirs et détections des joueurs.
- **Système de vote** : Permet de voter pour décider si un joueur est un bot (score à implémenter).
- **Gestion dynamique des bots** : Les bots quittent automatiquement lorsque des joueurs humains rejoignent, jusqu’à 8 joueurs maximum.
- **Fin de partie** : La partie se termine lorsqu’un joueur atteint 25 éliminations ou après 5 minutes de jeu.
- **Tableau des scores interactif** : Affiche les noms, kills, morts, et un bouton de vote (par défaut assigné aux bots).


## 🕵️‍♂️ Contributeurs
- **Mohamad Siyaman** :
  - Programmation principale, systèmes de tir, multijoueur, et intégration d’une intelligence artificielle pour les bots.
  - Réalisation complète du projet suite à l’abandon d’un coéquipier.

## 📃 Licence
Ce projet utilise des assets Unity disponibles sans licence spécifique. Il est réalisé à des fins académiques. Pour toute utilisation commerciale, veuillez contacter l’auteur.

---
