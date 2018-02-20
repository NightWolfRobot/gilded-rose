# gilded-rose
[![Build Status](https://travis-ci.org/NightWolfRobot/gilded-rose.svg?branch=master)](https://travis-ci.org/NightWolfRobot/gilded-rose)
[![Coverage Status](https://coveralls.io/repos/github/NightWolfRobot/gilded-rose/badge.svg?branch=master)](https://coveralls.io/github/NightWolfRobot/gilded-rose?branch=master)

## Objectif
Le projet reprend les spécifications suivantes :
- https://github.com/emilybache/GildedRose-Refactoring-Kata/blob/master/GildedRoseRequirements.txt
- https://github.com/ledoyen/tp-java/tree/master/projet/4A_2018

## Spring-boot
Pour le projet on a donc 3 adresses pour nous permettre d'effectuer les differentes tâches:
* `/buy_item`
* `/list_items`
* `/add_item`

## Exemple
### Add item
```
add_item?name=coquelicot&sellin=10&quality=40&quantity=5&price=5.77
```

Pour ajouter un item il faut préciser les paramètres suivants :
- name (nom de l'item)
- sellin (nombre de jour avant péremption)
- quality (qualité de l'item)
- quantity (quantité disponible)
- price (prix de l'item à l'unité)

### Buy item
```
buy_item?name=coquelicot&quantity=2
```

Pour acheter un item il suffit simplement de préciser le nom et la quantité voulue avec les paramètres suivants:
- name
- quantity
> **Note:** On ne peut pas acheter plus d'items que disponible.

### List items
```
list_items
```

Enfin pour observer la liste des différents items disponibles au format Json il suffit de se rendre sur l'adresse `list_items`.

## Membres du projet
* CHAFFOT Anthony ([NightWolfRobot](https://github.com/NightWolfRobot "NightWolfRobot"))
* LE HOLLOCO Jean Antoine ([LeHolloco](https://github.com/LeHolloco "LeHolloco"))
* OUMOURI ASSOUMANI Daroui Dine ([daroui27](https://github.com/daroui27 "daroui27"))
* PERRAULT William ([Timezer](https://github.com/Timezer "Timezer"))
* RASNER Amin ([AminRas](https://github.com/AminRas "AminRas"))
