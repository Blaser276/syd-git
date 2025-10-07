# Answers of Frédéric Fugazza Blaser276

## Basics
### Task 1
1 unstaged file = en changeant des données dans le fichier answers.md on crée des divergences entre la première version du fichier et la version actuelle. Il faut stage le fichier afin qu'il soit pris comme une nouvelle version dans le repo git.
### Task 2
1. CHG: personal data in answers.md = changement des données personnels dans le fichier answers.md --> on quittance donc execution de la tâche 1.
2. Non un commit doit toujours avoir un message (impossible de créer un commit sans message) afin de tracer les changements effectuer dans le "branch view".
3. en créant un nouveau commit on a créé un nouvel embranchement donc une nouvelle version du fichier answers.md enregistrée en plus des versions déjà existantes.
4. Nous le dépôt distant n'est pas à jour, car il faut transmettre les modifications locales au fork via une commande. (sûrement push)
### Task 3
On a un "unstaged file" dans le depôt git. Normal, on vient de créer un fichier inconnu au depôt et non commité.
### Task 4
Quand on revient au "commit initial" une nouvelle branche se forme en préparation des modifications qui pourraient être apportées sur le commit initial. Modifier le "commit initial" revient à créer une nouvelle version de ce-dernier. Les commits suivants sont donc sur la nouvelle branche signifiant qu'il utilise un "commit initial" différent de la première version du "commit initial".
### Task 5
1. On travail dans le dépôt local pas sur le distant. Le distant sert de backup, c'est pour quoi il est important de push les éléments du local sur le distant afin de toujours avoir un backup.
2. On pourrait simplement cloner le dépôt distant et retrouver l'entièreté du dernier push et donc du dernier travail sauvegardé. 

### Task 6
Le dépôt originel ne subit pas les modifications même si on les push. L'idée de forker est de créer une branche qui a pour base la dépôt originel. Mon dépôt distant, et par extension local, est situé sur la branche créée en forkant le depot originel. Forker permet donc de travailler en parallèle, donc sur les "children" de notre dépot originel. Le dépôt originel reste donc non-modifié tout en conservant le versionnage dans des branches.
## Gitgraph
![Gitgraph](img/gitgraph.svg)
### Task 7
1. branche
2. ash 
3. Commit message
4. nom utilisateur de la personne faisant la modification
5. Tag
6. Dernier commit de la branche develop
7. unique commit de la branche feature-auth
8. dernier commit dela branche main
9. premier commit de la branche develop
10. premier commit de la branche main 
