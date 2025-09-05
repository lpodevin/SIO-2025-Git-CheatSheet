# SIO-2025-Git-CheatSheet

# PHASE 1

## 1) Pourquoi utiliser Git/GitHub ?

On peut utiliser Git et GitHub car ils nous permettent de bénéficier de nombreux avantages pour la création de logiciels.

→ On utilise **GitHub** afin d’héberger les dépôts de **Git**  
Cela nous permet de ne pas se marcher dessus lors de notre travail en groupe.

---

**test** *test*

## 2) En entreprise ? En cours ?

On utilise Git/GitHub en entreprise et en cours afin de travailler plus efficacement à plusieurs, sans écraser le travail des autres, 
avec une sauvegarde automatique, et pour pouvoir travailler hors ligne lorsque l’on veut.

---

## 3) Qu’est-ce qu’un dépôt (repo) ? Un commit ? Une branche ?

- **Dépôt** : c’est un espace de stockage où est conservé tout le contenu (les commits et les branches).
- **Commit** : c’est un point de sauvegarde dans l’historique de ton code.
- **Branche** : c’est une ligne de développement indépendante et qui permet de tester certaines feature sans endommager le projet initial 

---

## 4) Schéma simple à dessiner pour expliquer

```
Dépôt Git
│
├── Branche principale (main/master)
│ ├─ Commit 1 ── Commit 2 ── Commit 3
│
└── Branche feature
├─ Commit A ── Commit B

```
## 5) Quelles sont les commandes Git de base ? 

Les commandes de Git de base sont : 
"git init" : Initialise un nouveau dépôt Git, 
"git clone <url>" : Clone un dépôt distant sur votre machine locale, 
"git status" : Affiche l'état des fichiers dans le dépôt (modifié, non suivi, etc.) , 
"git commit -m message" : , 
"git pull" : Récupère et fusionne les modifications du dépôt distant ,
"git push" : Envoie les commits locaux vers le dépôt distant.



## 6) Quelle est la différence entre Git et GitHub ?
Github permet de stoker des données dans le monde alors que Git lui permet de modifier
des infos de maniere hors ligne ou en ligne 
