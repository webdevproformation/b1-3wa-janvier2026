# fusionner les branches 

## méthode 1 => merge

```sh
git branch <fonction>
git switch <fonction>
# version courte
git checkout -b <fonction> # créer la branch et se positionner dessus

# travailler 
git add .
git commit 
git switch <main>
git merge <fonction>
```

## méthode 2 => rebase


```sh
git branch <fonction>
git switch <fonction>
# version courte
git checkout -b <fonction> # créer la branch et se positionner dessus

# travailler 
git add .
git commit 
git switch <main>
git rebase <fonction>
```

- reprendre l'ensemble des commits de la branch et les mettre à la suite de la branch principale 
- rapatrier les commits d'une autre branch 

