# Git-formation

Dépôt d’atelier pour pratiquer Git : remote, branches, Pull Request, conflits, rebase.

## Démarrer

1. Cloner ce dépôt :
   ```bash
   git clone https://github.com/AbidHamza/Git-formation.git
   cd Git-formation
   ```
2. Vérifier la config Git : `git config user.name` et `git config user.email`
3. Le fichier **notes.txt** sert de support pour les exercices (premiers commits, conflits, etc.). Ajoutez-y des lignes, modifiez-le, créez des branches à partir de `main`.

## Contenu

- **notes.txt** : fichier prévu pour les exercices (ajouts, modifications, conflits).
- Suivez les slides de l’atelier pour les scénarios Remote, Pull Request, Conflits et Rebase.

## Deux clones pour les exercices Remote / Conflits

Pour simuler push d’un côté et pull de l’autre sans autre personne, créez deux clones sur votre machine :

```bash
git clone https://github.com/AbidHamza/Git-formation.git Git-formation-2
```

Travaillez dans le premier clone (commit, push), puis dans le second (fetch, pull).
