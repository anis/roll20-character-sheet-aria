# roll20-character-sheet-aria
Roll20 character sheet for the RPG game Aria by Elder Craft and FibreTigre

# I. Explication des onglets
## 1. Onglet "Caractéristiques"
### a. Caractéristiques
Tableau des caractéristiques de base de votre personnage :

- JET : cliquer sur le petit dé pour effectuer un jet sur la caractéristique (note : le jet se fait sur 1d100)
- VALEUR : correspond à la note initiale de la caractéristique
- BONUS : bonus/malus à appliquer à la note initiale
- TOTAL : note finale, utilisée pour les jets sur la caractéristique

### b. Vivre ou survivre
- PV MAX : nombre de PV maximum de votre personnage (rempli automatiquement sur la base de l'END)
- PV RESTANTS : nombre de PV restants (rempli automatiquement en même temps que PV MAX)
- PROTECTION : points de protection de l'armure, si pertinent
- POINTS DE MORT : nombre de points de magie de la mort acquis

### c. Armes
Tableau des armes et attaques de votre personnage. Cliquez sur "Add" pour rajouter une nouvelle ligne :

- JET : cliquer sur le petit dé pour effectuer un jet qui calcule les dégâts portés par l'attaque
- NOM DE L'ARME : nom de l'arme
- DÉGÂTS : détail du jet de dégâts de l'arme, sous le format `nombre de dés` + `type de dé` + `bonus` (pour des dégâts fixes de 1, vous pouvez faire 0d6 + 1 par exemple)
- COMMENTAIRES : commentaire libre

## 2. Onglet "Compétences"
### a. Compétences
Ce tableau présente la liste des compétences de base de votre personnage. Cliquez sur "Add" pour rajouter une nouvelle compétence.
Lors de la création de votre personnage vous pouvez choisir entre deux méthodes de calcul pour déterminer la valeur de chaque compétence :
- par moyenne : le calcul est entièrement automatique (moyenne de deux caractéristiques)
- par répartition : vous disposez d'un solde de points (60) à répartir comme vous le souhaitez entre vos différentes compétences

Si vous choisissez la méthode par répartition, deux éléments sont rajoutés à l'interface :
- le solde de points restants, juste au-dessus du tableau
- le nombre de points à attribuer pour chaque compétence, sous la forme d'une colonne en plus dans le tableau

Voici une explication du tableau des compétences :
- JET : cliquer sur le petit dé pour effectuer un jet sur cette compétence
- COMPÉTENCE : nom de la compétence
- LIEN : les deux caractéristiques qui servent à calculer la valeur de la compétence
- BASE : valeur de base de la compétence
- POINTS* : points assignés à cette compétence (* uniquement pour la méthode par répartition)
- BONUS : bonus/malus à appliquer à la compétence
- TOTAL : valeur finale, utilisée pour les jets sur la compétence

### b. Compétences spéciales
Ce tableau présente la liste des compétences spéciales de votre personnage. Il s'agit d'une version simplifiée et plus libre du tableau de compétences de base.

## 3. Onglet "Inventaire"
### a. Possessions
Tout ce que possède votre personnage : armes, armures, vêtements, outils, argent, ...

### b. Notes
Notes libre
