# 🎲 Latice - Le Jeu de Stratégie et de Couleurs

Bienvenue dans Latice ! Un jeu de société stratégique adapté en version numérique, où votre objectif est de combiner des tuiles par la couleur ou la forme pour marquer des points et être le premier à vider votre rack.

Ce projet propose deux expériences de jeu :
* **Mode Console :** Pour une expérience pure et rapide, directement dans votre terminal.
* **Mode Interface Graphique (IHM) :** Pour une expérience visuelle et immersive, avec une musique de fond pour accompagner vos parties.

---

## 📜 Règles du Jeu

### Objectif Principal
Il y a deux manières de remporter la partie :
1.  **Victoire immédiate :** Être le premier joueur à vider complètement son rack de tuiles (la pioche doit également être vide).
2.  **Victoire aux points (fin de temps) :** Si aucun joueur n'a vidé son rack après 10 cycles complets (soit 20 tours de jeu), le joueur ayant posé le plus de tuiles sur le plateau est déclaré vainqueur.

### Joueurs
* Cette version simplifiée se joue exclusivement à **2 joueurs**.

### Déroulement d'un tour
À chaque tour, vous disposez d'une action principale. Vous pouvez choisir parmi les options suivantes.

### Actions Disponibles
1.  **Jouer une tuile :** Placez une tuile de votre rack sur une case vide du plateau. La tuile doit correspondre en **couleur** ou en **forme** à toutes les tuiles adjacentes (non diagonales).
2.  **Acheter une action supplémentaire :** Dépensez des points pour pouvoir jouer une autre tuile durant le même tour.
    * **Coût :** 2 points par action supplémentaire.
3.  **Échanger son rack :** Défaussez toutes les tuiles de votre rack et piochez-en de nouvelles. Cette action met fin à votre tour.
4.  **Passer son tour :** Ne rien faire et mettre fin à votre tour.

### Comment Marquer des Points
Les points sont essentiels pour acheter des actions supplémentaires. Vous en gagnez lorsque vous posez une tuile :

* **Association de 3 tuiles :** `+1 point`
    * _Exemple : Votre tuile touche deux autres tuiles sur le plateau._
* **Association de 4 tuiles :** `+2 points`
    * _Exemple : Votre tuile est placée au milieu de trois autres tuiles._
* **Association de 5 tuiles :** `+4 points`
    * _Exemple : Votre tuile est complètement entourée._
* **Bonus Soleil ☀️ :** `+2 points`
    * Si vous posez une tuile sur une case spéciale "soleil", vous gagnez 2 points bonus en plus des points d'association.

---

### Prérequis
* Assurez-vous d'avoir Java 8 installé.
* Maven


---

# 🎲 Latice - The Strategy and Color Game

Welcome to Latice! A strategic board game adapted into a digital version, where your goal is to match tiles by color or shape to score points and be the first to empty your rack.

This project offers two gameplay experiences:

* **Console Mode:** For a pure and fast experience directly in your terminal.
* **Graphical User Interface (GUI) Mode:** For a visual and immersive experience, with background music to enhance your gameplay.

---

## 📜 Game Rules

### Main Objective

There are two ways to win the game:

1. **Immediate Victory:** Be the first player to completely empty your tile rack (the draw pile must also be empty).
2. **Point-Based Victory (time limit):** If no player has emptied their rack after 10 full cycles (i.e., 20 total turns), the player who has placed the most tiles on the board is declared the winner.

### Players

* This simplified version is designed for **2 players only**.

### Turn Structure

During each turn, you have one main action. You may choose from the following options.

### Available Actions

1. **Play a Tile:** Place a tile from your rack onto an empty space on the board. The tile must match in **color** or **shape** with all adjacent (non-diagonal) tiles.
2. **Buy an Extra Action:** Spend points to play an additional tile during the same turn.

   * **Cost:** 2 points per additional action.
3. **Exchange Your Rack:** Discard all tiles from your rack and draw new ones. This ends your turn.
4. **Pass Your Turn:** Do nothing and end your turn.

### How to Score Points

Points are essential to buy extra actions. You earn points when placing a tile:

* **3-Tile Match:** `+1 point`

  * *Example: Your tile touches two others on the board.*
* **4-Tile Match:** `+2 points`

  * *Example: Your tile is placed between three others.*
* **5-Tile Match:** `+4 points`

  * *Example: Your tile is completely surrounded.*
* **Sun Bonus ☀️:** `+2 bonus points`

  * If you place a tile on a special "sun" space, you earn 2 bonus points in addition to the match points.

---

### Prerequisites

* Make sure you have Java 8 installed.
* Maven

