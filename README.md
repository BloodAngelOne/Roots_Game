# Ressources

Nous avons trouvé un wiki intéressant pour découvrir de nouvelles choses et s'inspirer [WIKI](https://www.pygame.org/wiki/resources)

La doc de Pygame prend du temps à décortiquer mais nous a aidé à comprendre quelques fonctionnalités [PYGAME](https://www.pygame.org/docs/)

Comme nous avons beaucoup aimé Mario plus jeunes, nous avons cherché des projets correspondants sur github, et avons cherché à comprendre le code :

- [MARIOMAKER](https://github.com/clear-code-projects/PirateMaker)
- [SUPERMARIO](https://github.com/mx0c/super-mario-python)

# Comment lancer le projet

Via terminal, il suffit de se positionner dans le dossier 'Code', et d'exécuter le fichier 'main.py'

```
cd code
code> py -m main.py
```

Attention, le projet ne se lance qu'avec les versions 3.10 ou 3.11 de python, et donc pas la version 3.9 !

# Qu'avons-nous fait ?

- nous avons suivi un gros tutoriel pour essayer de comprendre comment le projet PirateMaker était construit [CLEARCODE](https://www.youtube.com/watch?v=KJpP85tnOKg&list=RDCMUCznj32AM2r98hZfTxrRo9bQ&start_radio=1&rv=KJpP85tnOKg&t=13)

- nous testé plusieurs fonctionnalités (barre de vie, décors, collisions, menus, etc...)

- nous avons simplifié le projet pour apprendre comment gérer les tuiles graphiques (tiles) 

- nous avons utilisé l'éditeur de niveau Tiled pour construire et visualiser le contenu du niveau 0 que nous avons créé [TILED](https://doc.mapeditor.org/en/stable/manual/introduction/)

- nous avons remplacé une grosse partie des éléments graphiques du projet (terrain, arbres, ciel, nuages, buissons...) et avons dû essayer de gérer les collisions des nouveaux éléments graphiques

- nous avons créé les fichiers CSV, TMX et TSX (du dossier level)

- nous avons appris comment marche github, l'avons configuré et avons sauvegardé notre projet sur la plateforme [GITHUB DU PROJET](https://github.com/FabienFr/Roots)

# Ce que nous n'avons pas eu le temps de faire

- bien gérer toutes les collisions

- rendre fonctionnelle la barre de vie du personnage malgré le fait que nous avions travaillé en groupe sur ce sujet

- nous n'avons pas du tout eu le temps de créer le menu du jeu malgré le fait que nous avions préparé cette action

Vous n'avez donc accès qu'à un niveau, et quand vous mourrez, vous devez pour l'instant relancer 'main.py'