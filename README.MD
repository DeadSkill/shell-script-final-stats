# Stats'
![Monkey](https://media.giphy.com/media/T8Dhl1KPyzRqU/giphy.gif)

## Installation
🎶 It's easy as 1, 2, 3 :
1) Télécharger le fichier `stats` et le placer dans un dossier au choix.
2) Lancer la commande `vim ~/.bash_profile`.
3) À la fin du fichier, ajouter la ligne `export PATH=/chemin/vers/le/fichier:$PATH` (remplacer par le chemin absolu du dossier où stats est installé).


## Description
Permet de d'obtenir un log du débit descendant. Le fichier de log est automatiquement créé dans le dossier home sous le nom `.server_log` s'il n'existe pas déjà.

Exemple de fichier log :
```
$ ./stats log
[Sun Dec 23 20:18:40 CET 2018] 	 5.09 MB/s
[Sun Dec 23 20:19:08 CET 2018] 	 5.41 MB/s
[Sun Dec 23 20:19:15 CET 2018] 	 4.61 MB/s
```

## Options
`stats` : Le test se fait en téléchargeant, par défaut, un fichier de 10Mo (le fichier n'est pas conservé).

`stats [url]` : Le fichier téléchargé est spécifié par `[url]`. Le fichier n'est pas conservé non plus.

`stats log` : Permet d'afficher le log.

## But
Le but est de pouvoir visualiser la variation du débit descendant au cours du temps. Il serait donc pertinent que l'utilisateur fasse de ce script une tâche cron (pour ajouter une tâche, lancer la commande `crontab -e`).

## Equipe
[Thomas Flitterman](https://github.com/tofl)

[Julien SEIXAS](https://github.com/MrZyr0)
