## Les branches d'un repo git

Il est de bonne pratique de ne pas travailler sur la branche principale qui est dédiée à la production.

Les branches de développement permettent de faire évoluer le repo sans endommager le code principal.

- Créer une nouvelle branche *dev* et basculer dessus
```git checkout -b dev```

- la commande *git banch* renvoie

```
git branch
* dev
  main
```

- pour pousser cette nouvelle branche, le premier push se fait avec :
```
git push -u origin dev
```

- en suite si on modifie il n'y a qu'un push simple à faire au final

```
git commit -a -m "modif"
```

```
git push
```
=> ma branche dev est mise à jour !
