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
