# Cours de git

## 1. Récupérer un repository Github :

- Cloner le repository : le clone est fait seulement au début, pour la récupération complète d'un remote. Cela crée le dossier projet et le local repository.

```
git clone https://github.com/xonatis-academy/phi-dwwm6-git.git
```

## 2. Envoyer des modifications vers un remote


- Activer la prise en compte des fichiers (staging). Il faut dire à git de prendre en compte les nouveaux fichiers que l'on a ajouté avec un git add.

```
git add *
```

ou pour ajouter certains fichiers **seulement** :

```
git add index.html style.css script.js
```


- Envoyer les modifications vers le local repository

```
git commit –m "Modification du site internet"
```

- Envoyer le local repository vers le remote

```
git push
```

## 3. Recevoir des modifications depuis un remote

```
git pull
```