# les commandes de versionning

- créer / modifier / supprimer un fichier 
- Ctrl + S


```sh
git add .
git commit -m"texte explicatif sur le commit réalisé"

# visualiser les commits 
gitk 
```

# comprendre la commande git add 

- étape AVANT la création du COMMIT (enregistrement de la version)
- permet de lister l'ensemble des fichiers que l'on veut COMMIT 
- pour que le commit soit associé clairement au fichiers concernés la version 

quand un fichier est modifié ET que l'on vient de faire un git add  =>

le fichier est dans un état `staged` 

# connaitre l'état de chaque fichier 


```sh
git status
```

Untracked files: jour01/06-versionner.md

```sh
git add . 
git add -A
git add --all 
```

```sh
git status

git commit -m "ajout d'un footer"
```

```sh
git status

nothing to commit, working tree clean
```

```sh
git commit -a -m "modification ..."
```