# Documentation du tuto github avec Git

## Initialiser un depot

```bash
git init
git remote add origin SSH_REPO
```

## Rediger un commit

```
Titre du commit 

Description de notre commit avec des informations sur l'evolution du projet
```

## Envoyer un commit sur le depot distant

```bash
git add .
git commit -m "Titre du commit"
git push origin main
```

## Creation d'une nouvelle branch

```bash
git checkout -b NOM-BRANCH
```

Pour les bonnes pratiques on va integrer la notion de revue de code. Pour cela on va creer une branche, faire des modifications, les envoyes sur le depot distant, puis creer une pull request pour demander une revue de code.
