Bonjour, bienvenu à vous. 
Ce challenge comporte 6 solutions qui sont stockées dans la **Box Warchall**.
Voyons ci-dessus les étapes à suivre.

# _Solution 1 (level 0)_ :
La solution se trouve dans le répertoire suivant :
```sh
/home/level/00_welcome
```
Suivre les deux étapes ci-dessous : 
- Utiliser la commande **cd** (change directory) , qui permet d'accéder à un répertoire, en mettant le chemin vers le répertoire derrière celle-ci, les deux séparés par un espace ("cd
/home/level/00_welcome")
- Arrivé dans ce répertoire, on peut voir un seul fichier texte nommé **README.md**. La solution à ce niveau se trouve à l'intérieur de ce fichier. Utiliser la commande **cat** (concatenate) pour afficher le contenu de ce fichier. Voici la solution : `bitwarrior`

# _Solution 2 (level 1)_ :
La solution se trouve dans le répertoire suivant : 
```sh
/home/level/01_choice_tree/blue/hats/grey/solution/patience
```
Pour y accéder, il faut utiliser la commande **cd** en mettant le chemin vers le répertoire derrière celle-ci ("cd /home/level/01_choice_tree/blue/hats/grey/solution/patience").
Arrivé dans ce répertoire, on peut voir le fichier texte nommé **SOLUTION.TXT**. Utiliser la commande **cat** . Voici la solution : `patience`.

# _Solution 3 (level 2)_ :
La solution se trouve dans le répertoire suivant :
```sh
/home/level/02/.porb
```
Il faut suivre 4 étapes :
- Utiliser la commande **cd** pour accéder au répertoire **/home/level/02/** .
- Arrivé dans ce dernier, utiliser la commande **ls** (list) , qui permet d'afficher le contenu d'un répertoire, avec le paramétre **-al** (ou **-all**) pour afficher les répertoires cachés (débutant par un "."). 
- Après cela, on remarque le dossier **.porb**. Accéder à ce dernier avec **cd** ("cd .porbs/").
- Dans ce dossier, utiliser la commande **ls -al** . La solution se trouver dans le fichier **.solution** . Employer **cat** . Voici la solution : `HiddenIsConfig`.

# _Solution 4 (level 3)_ :
La solution se trouve dans le répertoire suivant :
```sh
/home/level/03
```
Suivre les 3 étapes suivantes :
- Utiliser **cd** pour accéder au répertoire concerné ("cd /home/level/03").
- Utiliser **ls -al** pour afficher le fichier **.bash_history** .
- Utiliser **cat** pour afficher la solution. Voici la solution : `RepeatingHistory`.
# _Solution 5 (level 4)_ :
La solution se trouve dans le répertoire suivant :
```sh
~/level/04_kwisatz
```
Les 3 étapes pour trouver la solution :
- Accéder au répertoire **~/level/04_kwisatz** par l'intermédiaire de **cd** ("cd ~/level/04_kwisatz").
- On peut constater le fichier **README2.md** qui contient la solution (comme mentionner dans le **README.txt**). Or, on ne peut pas utiliser la commande **cat** car on n'a pas les permissions requises pour ouvrir le fichier. Il faut donc changer les permissions à ce fichier avec la commande **chmod** (change mode ) suivie du paramétre **777** pour permettre la lecture, l'écriture et l'éxécution ("chmod 777 README2.md").
- Ouvrir ce fichier par **cat** . Voici la solution : `AndOfCourseIDoKnowChown`.
# _Solution 6 (level 5)_ :
La solution se trouve dans le répertoire suivant :
```sh
/home/level/05_privacy
```
Ce level se fait en 2 étapes :
- Utiliser la commande **cd** pour accéder à ce répertoire ("cd /home/level/05_privacy").
- Utiiser la commande **cat** pour ouvrir le fichier **README.md** contenu dans le répertoire ci-dessous. Voici la solution : `OKPRIVATE`.