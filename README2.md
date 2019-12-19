# Les étapes à respecter

## 1ère partie : Le Dataset

1.1. Télécharger le dataset :

```
    https://www.kaggle.com/c/GiveMeSomeCredit/data
```

## 2eme partie : L'environnement :

1.1. Installer Docker :

```
    https://www.docker.com/
```
1.2. Créer le fichier auth.env dans le même dossier que le projet :

```
    BIGML_USERNAME=xxx
    BIGML_API_KEY=xxx
    KAGGLE_USERNAME=xxx
    KAGGLE_KEY=xxx
```  

## 3eme partie : Lancement :

1.1. Utiliser l'invité de commande :

```
   $ cd Give-me-some-credit
   $ cd docker
   docker-compose up -- build 
```

## 4eme partie : L'éxecution :

```
    Ouvrez votre navigateur préféré, et allé à l'adresse suivante :

    http://localhost:8888/tree/Desktop/give-me-some-credit

    Il ne reste plus que a modifier l'id de votre projet sur BigML.

    Vous avez maintenant accès aux notes books :)   
```
