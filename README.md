# LIFProjet - Jeu de tir multijoueur 3D

## Description
Ce projet est un jeu de tir multijoueur en 3D, inspiré de jeux comme *Counter-Strike*. Conçu dans le cadre d'une Licence Informatique (L3), il met en avant plusieurs fonctionnalités de gameplay et techniques, notamment :
- Un système multijoueur géré avec [Mirror](https://mirror-networking.com/).
- Des mécaniques de tir et de rechargement.
- La synchronisation des skins et des actions entre les joueurs.
- Une intelligence artificielle basique pour des bots pouvant suivre des parcours et réagir aux ennemis.
- Un système de vote sur sur le scoreboard.
- Gestion dynamique des bots (remplacement par des joueurs humains en cas dépassement de nombre de joueur).

## Objectifs principaux
- **Travailler en autonomie** : chaque membre du projet doit s’approprier les tâches techniques et conceptuelles pour mener à bien le projet.
- **Gestion de projet** : structurer le développement, organiser les étapes et respecter les échéances.
- **Prise de décisions techniques** : évaluer les différentes solutions possibles, faire des choix techniques et être capable de les justifier.
- **Apprentissage autonome** : s'informer sur Unity et comprendre ses bases sans assistance directe.

## Fonctionnalités
### Gameplay
- **Contrôles** :
  - `Q`, `S`, `D`, `Z` : Déplacement.
  - `R` : Recharger.
  - Clic gauche : Tirer.
  - `Tab` : Afficher le tableau des scores.
- **Tir en vue FPS** : Expérience immersive de jeu de tir.
- **Gestion des munitions et du rechargement** : Limitation des tirs par chargeur.
- **Sélection de skins** : Personnalisation visible par tous les joueurs.
- **Interaction avec des bots** : Bots remplaçant les joueurs absents.
- **Système de vote** : Permet de prendre des décisions collectives en jeu, comme redémarrer une partie ou modifier certaines règles.
- **Gestion dynamique des bots** : Les bots quittent automatiquement lorsqu’un joueur humain rejoint, jusqu’à atteindre le maximum de joueurs autorisés.
- **Fin de partie** : La partie se termine lorsqu’un joueur atteint 25 éliminations ou après 5 minutes de jeu.
- **Tableau de scores interactif** : Permet d’identifier les joueurs et bots.

### Technique
- **Multijoueur** : gestion des joueurs et de leurs interactions via Mirror.
- **Skins synchronisés** : chaque joueur voit les skins des autres correctement.
- **IA des bots** : détection des joueurs dans leur champ de vision et réaction (tir, poursuite).
- **Système de tir** : instanciation des projectiles et calcul des dégâts.
- **Tableau des scores** : Affichage des performances des joueurs.

## Prérequis
- Windows 10 ou 11.

## Installation
1. Clonez ce dépôt :
   ```bash
   https://github.com/Siya1809/Project_Alpha.git
   ```
2. Ouvrez le projet et lancez "Project Alpha.exe".

## Utilisation
### Hôte :
1. Créez un serveur en cliquant sur "Host" (mode serveur et client combinés).
2. Donnez votre adresse IP (trouvable via `ipconfig` sur Windows) aux autres joueurs.

### Client :
1. Entrez l’adresse IP de l’hôte dans le champ prévu, en conservant le port par défaut.
2. Cliquez sur "Client" pour rejoindre la partie.

### En jeu :
1. Déplacez-vous avec `Q`, `S`, `D`, `Z`.
2. Rechargez avec `R` et tirez avec le clic gauche de la souris.
3. Consultez le tableau des scores avec `Tab` pour vérifier les performances des joueurs.
4. votez pour trouvez qui sont les vrais joueurs ou des bots


## Contributeurs
- **Mohamad Siyaman** : L’ensemble du développement, incluant la programmation principale, les systèmes de tir et le multijoueur, a été réalisé par moi suite à l’abandon d’un coéquipier.

## Licence
Ce projet est réalisé à des fins académiques. Pour toute utilisation commerciale ou redistribution, merci de contacter les auteurs.

