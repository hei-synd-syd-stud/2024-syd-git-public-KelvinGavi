# Answers of Kelvin Gavillet KelvinGavi

## Basics

### Task 1

Dans le répertoire, on retrouve le fichier answers.md ainsi que deux dossiers : .git et img.

Le fichier answers.md correspond au fichier modifiable qui permet de noter les réponses aux points demandés.

Le dossier img permet de stocker les différentes images ou captures d'écran relatives au projet.

Le dossier .git est un dossier caché contenant les informations nécessaires au fonctionnement de git.

### Task 2

Dans le git status, on nous indique que le fichier README.md est non suivi.

Le git log --oneline, quant à lui n'a pas changé.

### Task 3

Après l'ajout du fichier README.md et la commande git status, on nous indique qu'il y a un changement à commit.

### Task 4

Après la modification du fichier README.md et l'entrée de la ligne git status, on retrouve le texte du point précédent mais on nous indique également que le fichier n'est pas prêt à être commit (Change not staged for commit).

### Task 5

La chaine de caractères présente au début des lignes représente le hachage, le hachage correspond à l'identifiant du commit.

HEAD représente la branche active sur laquelle on travaille.

main quant à lui représente la branche par défault.

Ici, cela signifie que la branche HEAD point dans le main.

Le texte présent après les parenthèses correspond au descriptif indiqué par la personne ayant effectué le commit.

### Task 6

Lorsqu'on revient au Initial commit, les fichiers et dossiers retrouvent leur état de création.

Lorsqu'on retourne au dernier commit, les fichiers et dossiers reviennent à leur dernier état qui avait disparu.

## Gitgraph

### Task 7

![Gitgraph](img/gitgraph.svg)

1. develop correspond au nom de la branche dans laquelle on se situe. Ici, develop.

2. baa6795 correspond au hachage qui permet d'identifier le commit.

3. Ce message indique qu'un merge a été effectué. Ici, la branche feature-auth est merge dans develop.

4. Ce point correspond au nom et au mail de la personne effectuant le commit.

5. v1.0.0 indique la version du projet.

6. Ce point est le dernier commit en date après le merge de feature-auth dans develop.

7. Ce point correspond au premier commit de la branche feature-auth

8. Ce point correspond au dernier commit en date de la branche main.

9. Cette branche correspond à la branche nommée develop.

10. Cette branche correspond à la branche main du projet.