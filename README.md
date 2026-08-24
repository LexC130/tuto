# Documentation de ma formation

## initialisation du dépot

```bash
git init
git remote add origin SSH_Repo
```

## Rédiger un commit

```
Titre du commit

Description De notre commit avec des infos sur l'évolution du projet

```

## Envoyer un commit sur le repo

```
git add . ##ajoute les fichier dans la file d'attente

git commit -m "un commentaire" ##nomme les changement et les mets dans la voiture du repo

git push origin main ##démarre la voiture vers le repo


```
## Création d'une branche

```bash
git checkout -b nom-branche

```

pour les bonnes pratiques, on va intégrer la notion de revue de code. Pour cela, on va créer une branche, faire des modifications, les envoyer sur le dépôt distant, puis créer une pull request pour demander une revue de code.