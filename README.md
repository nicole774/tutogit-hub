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