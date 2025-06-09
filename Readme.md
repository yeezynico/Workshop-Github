
# Workshop GitHub : Collaboration, Branches, Pull Requests & Conflits

## Objectif du workshop

Apprendre à collaborer efficacement sur GitHub en petit groupe (3 étudiants), en utilisant :
- des **branches**
- des **pull requests**
- la **résolution de conflits**
- le **merge collaboratif**

---

## Exercice 1 : Branches et Pull Requests (15 minutes)

**Objectif** : Créer une branche fonctionnelle, y travailler, faire une pull request, la faire relire et merger.

### Tâche

1. Réfléchissez à une petite fonctionnalité ou modification (par exemple : ajout d’une ligne dans un fichier `participants.txt`, création d’un fichier de présentation, etc.)
2. Créez une branche nommée `initiales/nom-de-feature` (ex: `AZ/ajout-participant`)
3. Effectuez la modification
4. Faites un commit et poussez votre branche
5. Créez une Pull Request (PR) vers `main`
6. Demandez une relecture (code review) aux autres membres du groupe avant de merger

---

## Exercice 2 : Générer et résoudre un conflit (20 minutes)

**Objectif** : Créer un conflit sur la même ligne d’un fichier et le résoudre manuellement.

### Tâche

1. Chacun crée une branche `[initiales]/modif-conflit` **depuis** `main`
2. Tous modifient **la même ligne** dans `conflit.txt`
3. Poussez votre branche et créez une PR (n'oubliez pas de valider via une code review)
4. Le premier merge passera
5. Les autres devront **résoudre le conflit manuellement** (sans instructions explicites)
6. Validez que les conflits sont bien résolus puis merger

---

## Exercice 3 : Rédaction collaborative (15 minutes)

**Objectif** : Remplir un fichier en groupe via plusieurs branches et reviews croisées.

### Tâche

1. Créez un fichier `recette.md` contenant trois sections : Introduction / Ingrédients / Étapes
2. Attribuez-vous chacun une section
3. Créez une branche `[initiales]/section-nom` (ex : `AZ/ajout-ingredients`)
4. Remplissez votre section
5. Créez une PR, faites-la review par les autres membres avant de merger

---

## Exercice 4 (optionnel) : Rebase avec conflit (20 minutes)

**Objectif** : Découvrir le `rebase` et gérer les conflits qui en découlent.

### Tâche

1. Une personne crée une branche `[initiales]/fonctionnalite-x` et modifie `fichier.txt`
2. Quelqu'un d'autre modifie la même partie sur `main` et merge
3. Le premier fait un `rebase` de sa branche sur `main` et résout les conflits
4. Une fois le `rebase` terminé, force le `push`
5. Crée une PR pour merger proprement dans `main`

---

## Fin du workshop : bonnes pratiques

- Ne pas travailler directement sur `main`
- Créer des branches claires : `[initiales]/feature` ou `fix/login-error`
- Nommer correctement les commits
- Toujours passer par une Pull Request
- Relecture (code review) obligatoire par le reste du groupe
- Résoudre les conflits calmement

---

## Bonus

Pour aller plus loin :
- Rebase interactif (`git rebase -i`)
- Squash de commits
- GitHub Projects / Issues / Labels
