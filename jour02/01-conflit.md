# un conflit 

- sur votre repository local un fichier index.html 
- ligne 10 => <p class="toto">bonjour</p>


- sur le repository distant le même fichier index.html
- sur la même ligne 10 => <p class="titi">bonjour</p>


- vous voulez importer le fichier distant => `git pull`
- git ne va pas savoir quel ligne il doit prendre ??? 
- <p class="toto">bonjour</p>
- <p class="titi">bonjour</p>