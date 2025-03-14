Tuto initiation git
----------------------

**Préalable.** Création d'un repo distant sur la plateforme Github

1 . Création d'un dossier sur le PC => pour le moment un dossier classique

2. On créé le premier fichier readme.md (qui va être la page d'accueil de notre repo)

3. On va initialiser ce dossier classique, comme un repo local avec la commande 

```git init```

Cette commande entraîne la création d'un sous répertoire .git, notre dossier *"classique"* local est devenu un repository au sens git du terme.

4. on va *"stagger"* le fichier readme.md

```git add readme.md```

5. on *"commit"* avec l'option message -m (qui appraîtra dans le repo github)

![](img/message_commit.png)

```git commit -m "first commit"```

6. On renomme la branche principale en main (car git en local a créer la branche master, mais github attend main par convention)

```git branch -M main```

git remote add origin https://github.com/ThomasIdgeo/tuto_git_cpgeom.git
git push -u origin main