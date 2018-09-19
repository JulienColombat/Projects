# Mes projets

## Iago
Iago est une reprise du jeu de plateau Othello (ou Reversi). Le but du jeu est donc d'avoir le plus de pions de sa couleur sur le plateau. Il est possible de conquérir du terrain, en encadrant une ligne de pions adverses, par d'autres de sa couleur.
Cette version de l'Othello, prénommée Iago (en référence à l'œuvre de Shakespeare) apporte plusieurs améliorations à la version originale:
* Possibilité de jouer jusqu'à 4 joueurs.
* Dispositions de différents types de bombes sur le terrains.
* Possibilités de récupérer des cartes jouables sur le terrains.

Et quelques ajouts permis grâce au passage sur ordinateur:
* L'ajout d'un mode en ligne.
* Différents niveau de difficultés.
* Possibilités de jouer contre l'ordinateur.

En ce qui concerne les différentes bombes et cartes, n'hésitez pas à aller voir les règles dans les options du jeu.

#### Réalisation
Le jeu a été codé en C avec la librairie graphique SDL, par un groupe de 2 programmeurs. A l'exception du fond en bois, l'intégralité des assets graphiques ont été conçus pour ce jeu.

## Gauntlet
Gauntlet est une reprise du jeu d'arcade du même nom, sorti en 1985. C'est un jeu du genre Hack'n'slash, dans un style héroïque fantasy, jouable jusqu'à 4 joueurs. Il est possible de jouer à plusieurs sur une même machine, mais la caméra suivra uniquement le joueur principal, ou alors, il est aussi possible de jouer sur plusieurs machines, en créant un serveur de jeu.
Chacun des 4 héros jouables à ses propres caractéristiques, comme par exemple le guerrier est plus résistant que l'archer, mais attaquera de moins loin.

Le jeu est une succession de salles à l'infini, ou plutôt jusqu'à la mort de tous les joueurs. Les premières salles sont fixes, puis elles sont générées aléatoirement parmi une listes de salles pré-créées, ou à l'aide d'un générateur de salles. De temps en temps, une salle aux trésors apparait, il faut alors sortir de la salle avant la fin du temps imparti, sinon la totalité des trésors récoltés dans cette salle seront perdus.

Le jeu a été pensé pour être très modulaire, avec par exemple la possibilité de changer les touches d'actions, ou encore le thème graphique, mais il est aussi possible de modifier les caractéristiques de tous les personnages et les monstres, comme par exemple leur vie, ou leur vitesse de déplacement.

Pour plus de détails, n'hésitez pas à lire le manuel utilisateur fourni avec le jeu.

#### Réalisation
Le jeu a été codé en Java, avec la librairie graphique JavaFX, par un groupe de 7 programmeurs. Les assets graphiques du thème "old" sont les sprites du jeu d'origine (1985). Pour le thème "classique", la plupart des sprites ont été refait, à l'exception des héros et des monstres.

## IndianaBot
IndianaBot est un jeu textuel ou vous incarnez un explorateur, qui doit contrôler par ordinateur, un petit robot, lors de l'exploration d'un temple. Le but du jeu est de trouver un éventuel trésor dissimulé quelque part dans le temple. Afin de réussir cet objectif, il faut entrer des commandes simples dans l'ordinateur (go, open, look, ...), pour que le robot les exécute. Mais attention, le robot possède une petite batterie, et si vous ne le ramener pas régulièrement vers vous, il risque de tomber à cours de batterie, et le jeu sera perdu.

#### Réalisation
Le jeu a été codé en Java, sans graphisme (c'est un jeu en console), par un groupe de deux programmeurs.

## BattleShip_Chatroom
