# Projet-IAA-ISEN-2020
Projet IAA ISEN 2020 / CECCOTTI Romain, DELPIERRE Baptiste, HOCHART Louis, KUCUKAL Burak.
Ce projet a été réalisé dans le cadre de l'enseignement d'Intelligence Artificielle Avancée en Master2 à l'ISEN Lille.

## Description
Le projet consiste en la création d'une intelligence artificielle qui, à partir d'une photo, applique à cette dernière le style d'un peintre choisi au préalable.

## Utilisation
Ci-joint, vous trouverez le script Python qui permet de modifier vos photos telles des filtres. Pour cela il vous suffit simplement de modifier ces deux lignes dans le script :

```python
style_path = "../images/style/Piet.jpg"
content_path = "../images/contenu/Lille.jpg"
```

Comme leur nom l'indique, `style_path` est l'endroit où il faut mettre la peinture que vous voulez utiliser en tant que filtre, et `content_path`, la photo que vous voulez transformer.
Ensuite il ne reste plus qu'à exécuter.
Ce script peut être utilisé par une commande en console, via un IDE mais aussi sur un notebook de type *[colab google](https://colab.research.google.com)* ou encore *[Jupyter notebook](https://jupyter.org/)*.
De plus, un dossier d'exemples est fourni avec le script.

Pour effectuer ce script, nous nous sommes appuyés sur *[https://nextjournal.com/gkoehler/pytorch-neural-style-transfer](https://nextjournal.com/gkoehler/pytorch-neural-style-transfer)*.
