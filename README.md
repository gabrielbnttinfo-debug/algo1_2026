# Exercice du cours **Algo. et structures de données** de première années

## Exécution programme
La plus pars des programmes issues des éxercices sont fait en **language c** pour pouvoir les éxécuter vous devrez utilisé cette commande.

```bash
gcc -Wall -Wextra -o "NOM_EXECUTABLE" "NOM_FICHIER.c" -lm
```

**gcc**: est le compilateurs.
**-Wall + -Wextra**: servent a révélé les erreur/warning.
**-lm**: permet au application utilisant math.h.

Ou sinon il peux avoir un fichier make.sh et run.sh qui permet de lancé l'application.

```bash
./make.sh
./run.sh
```

**make*: Le fichier qui permet de compilé.
**run*: Le fichier qui permet de compilé + lancé l'éxécutable

## Liens sur les projets


## Convention des commits

Les messages de commit suivent ce format :

`type(portée): description`

La portée est facultative. Elle précise la partie du projet concernée.

| Type | Utilisation | Exemple |
|---|---|---|
| `feat:` | Ajouter une fonctionnalité | `feat: ajouter une page de profil` |
| `fix:` | Corriger un bug | `fix: corriger la validation du formulaire` |
| `docs:` | Ajouter ou modifier la documentation | `docs: expliquer l'installation dans le README` |
| `style:` | Modifier le formatage sans changer le comportement du code | `style: formater les fichiers JavaScript` |
| `refactor:` | Réorganiser le code sans changer son comportement | `refactor: simplifier la logique de connexion` |
| `test:` | Ajouter ou modifier des tests | `test: couvrir la création d'un compte` |
| `perf:` | Améliorer les performances | `perf: accélérer le chargement de la liste` |
| `build:` | Modifier la compilation ou les dépendances de build | `build: mettre à jour la configuration Vite` |
| `ci:` | Modifier la configuration d'intégration continue | `ci: lancer les tests à chaque pull request` |
| `chore:` | Effectuer une tâche de maintenance | `chore: mettre à jour les dépendances` |
