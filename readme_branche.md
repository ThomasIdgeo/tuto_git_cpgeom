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