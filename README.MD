# Bandswitch statistiques

## Description

Le but est d'avoir un log d'un test de débit complet toutes les heures.
ça pourrait ressembler à ça :
```bash
[19/12/18 - 16:29] UP (min: 1mo/s, max: 1go/s, moy: 512mo/s) | DOWN (min: 1mo/s, max: 1go/s, moy: 512mo/s) | LATENCY (min: 1ms, max: 10ms, moy: 5ms)
```

## Fonctionnalitées supplémentaires
- le script est configurable avec un fichier
- le script à une première étape d'initialisation (permet de créer le fichier de conf interactivement)
- le script a un log séparé qui stocke les moments où le dbit est mauvais (par rapport au fichier de conf)
- le script envoie une notification par email lorsque le débit est en dessous du seuil défini

## Equipe
[Thomas Flitterman](https://github.com/tofl)

[Julien SEIXAS](https://github.com/MrZyr0)
