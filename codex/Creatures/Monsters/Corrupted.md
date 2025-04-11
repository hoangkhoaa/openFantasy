```markdown
# Understanding Git Concepts

This document aims to explain some fundamental Git concepts.

## Repositories

A Git repository is a virtual storage of your project. It can be:

*   **Local:** On your computer. This is where you'll primarily be working.
*   **Remote:** Hosted on a server, like GitHub, GitLab, or Bitbucket.

## Commits

A commit is a snapshot of your project at a specific point in time.  It's like saving your progress in a video game. Each commit has:

*   A unique ID (SHA-1 hash).
*   Author information (name, email).
*   A commit message describing the changes made.

## Branches

A branch is a parallel version of your project. It allows you to work on new features or bug fixes without affecting the main codebase (often called `main` or `master`).

### Creating a Branch

You can create a new branch using the following command:

```bash
git branch <branch_name>
```

### Switching Branches

To switch to a different branch:

```bash
git checkout <branch_name>
```

## Merging

Merging is the process of combining changes from one branch into another.  For example, you might merge a feature branch back into the `main` branch after it's been reviewed and approved.

```bash
git merge <branch_name>
```

## Common Git Workflow

A typical Git workflow might look like this:

1.  Create a new branch for your feature or bug fix.
2.  Make changes and commit them to your branch.
3.  Push your branch to the remote repository.
4.  Create a pull request (or merge request) to merge your changes into the main branch.
5.  After review and approval, merge the pull request.

## Staging Area

The staging area is an intermediate area between your working directory and the Git repository. It allows you to select which changes you want to include in your next commit.

```bash
git add <file_name>
```

## Undoing Changes

Git provides various ways to undo changes.  For example, `git revert` creates a new commit that undoes the changes of a previous commit.  `git reset` is another powerful tool but can be more destructive. Use with caution!
```
```markdown
# Comprendre les concepts Git

Ce document vise à expliquer certains concepts fondamentaux de Git.

## Dépôts

Un dépôt Git est un stockage virtuel de votre projet. Il peut être :

*   **Local :** Sur votre ordinateur. C'est là que vous travaillerez principalement.
*   **Distant :** Hébergé sur un serveur, comme GitHub, GitLab ou Bitbucket.

## Commits

Un commit est un instantané de votre projet à un moment précis. C'est comme sauvegarder votre progression dans un jeu vidéo. Chaque commit a :

*   Un identifiant unique (hachage SHA-1).
*   Les informations sur l'auteur (nom, email).
*   Un message de commit décrivant les modifications apportées.

## Branches

Une branche est une version parallèle de votre projet. Elle vous permet de travailler sur de nouvelles fonctionnalités ou des corrections de bugs sans affecter la base de code principale (souvent appelée `main` ou `master`).

### Création d'une branche

Vous pouvez créer une nouvelle branche à l'aide de la commande suivante :

```bash
git branch <branch_name>
```

### Changement de branche

Pour passer à une autre branche :

```bash
git checkout <branch_name>
```

## Fusion

La fusion est le processus consistant à combiner les modifications d'une branche dans une autre. Par exemple, vous pouvez fusionner une branche de fonctionnalité dans la branche `main` une fois qu'elle a été examinée et approuvée.

```bash
git merge <branch_name>
```

## Flux de travail Git courant

Un flux de travail Git typique pourrait ressembler à ceci :

1.  Créer une nouvelle branche pour votre fonctionnalité ou correction de bug.
2.  Apporter des modifications et les commiter dans votre branche.
3.  Pousser votre branche vers le dépôt distant.
4.  Créer une pull request (ou merge request) pour fusionner vos modifications dans la branche principale.
5.  Après examen et approbation, fusionner la pull request.

## Zone de préparation

La zone de préparation est une zone intermédiaire entre votre répertoire de travail et le dépôt Git. Elle vous permet de sélectionner les modifications que vous souhaitez inclure dans votre prochain commit.

```bash
git add <file_name>
```

## Annuler les modifications

Git fournit différents moyens d'annuler les modifications. Par exemple, `git revert` crée un nouveau commit qui annule les modifications d'un commit précédent. `git reset` est un autre outil puissant, mais il peut être plus destructeur. À utiliser avec prudence !
```

---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._