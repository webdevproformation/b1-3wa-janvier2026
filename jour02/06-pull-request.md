# Pull Request (PR)

- je te travaille en local sur un branch 
- et je veux la soumettre à mon équipe
- 
- push MAIS sur une branch qui n'est la branch MAIN 
- sur le dépôt github 

- créer une nouvelle branch qui s'appelle fonction_2


```sh
git checkout -b fonction_2
# travail
git add .
git commit 
git push 
# erreur !!! 
# il faut PUSH ET créer la branch fonction_2 sur le dépôt distant
git push --set-upstream origin fonction_2

# sur github => proposition de réaliser un PR (Pull Request)
# equivalent de faire un merge DIRECTEMENT dans github 
```

# en local 

```sh
git checkout main
git pull 
# ça va récupérer les lignes de codes que vous avez pull request
git branch -d fonction_2
# supprimer la branch qui a été PR 
```

git rebase -i HEAD~3