# comment travailler à plusieurs avec git ??

git pull

# le concept de Branch

-> schéma 

dans git vous avez la branch principale => main (avant master)

cette branch contient la version principal de votre projet 

vous pouvez à tout moment créer "une branch" qui va partir de la branch principale et qui va constituer comme un "univers parallèle"

en général on va créer une branch par nouvelle fonctionnalité

# sur quelle branch je suis / lister toutes les branch disponibles ??

```sh
git branch

# * main
# je n'ai qu'une seule branch ET je suis dessus 
# avant de créer une branch il est conseillé de git add . et commit 
```

# créer une branch  qui s'appelle `feature_1` et on s'est positionné dessus

```sh
# créer la branch
git branch feature_1
# lister les branch disponibles 
git branch
##   feature_1
## * main

# se positionner sur la branch feature_1
git checkout feature_1
git switch feature_1
# Switched to branch 'feature_1'
# vérifier que vous êtes sur la branch 
git branch
```

# etant donné que l'on est désormais sur cette branch 

- toute modification réalisée dans cette branch va être disponible que sur cette branch