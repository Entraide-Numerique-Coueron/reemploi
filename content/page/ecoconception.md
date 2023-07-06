---
title: Ecoconception
menu:
  - bottomFooter
date: 2023-06-20T08:02:36.770Z
weight: 10
description: Réduire les impacts environnementaux de ce site Internet
---
Ce site Internet a été créé dans une démarche d'écoconception afin d'en réduire les impacts environnementaux.

## Un constat

Le secteur du numérique est responsable à l'échelle mondiale de 4% des émissions de CO2, un gaz à effet de serre responsable du réchauffement climatique.

Le numérique est aussi gourmand en métaux, qu'il faut extraire puis purifier à l'aide de nombreux produits chimiques. Ces métaux, une fois qu'ils se retrouvent dans les circuits imprimés, sont difficilement récupérables et recyclables. Ils sont pourtant aussi nécessaire à d'autres secteurs d'activités important, comme celui des énergies renouvelables nécessaire à la transition écologique. A terme, c'est s'exposer à des risques de pénuries.

L'essentiel des impacts du numériques réside dans les milliards d'objets numériques que nous avons fait fabriquer : nos TV, smartphones, ordinateurs, console de jeux, robots de cuisine et objets connectés divers etc...

## L'écoconception

L'objectif de l'écoconception vise à minimiser les impacts sur l'environnement sur tout le cycle de vie d'un service numérique.

Par exemple, l'un des principal enjeu est avant tout de ne pas provoquer chez le visiteur un sentiment d'obsolescence : le site Internet doit fonctionner, et s'afficher rapidement, sur tous les ordinateurs et smartphones qu'ils soient récents ou très vieux.

Lorsqu'un smartphone de quelques années qui fonctionne toujours, rencontre des problèmes de compatibilités avec des applications ou sites Internet, ou de grosses lenteurs, nous nous retrouvons dans la situation absurde où son propriétaire va être tenté d'en acheter un nouveau.
Le problème n'est pas le vieux smartphone ou le vieil ordinateur, mais ces sites Internet et applications qui sont mal conçus.

## Ce site Internet

### Compatibilité maximale

Ce site Internet a été pensé pour fonctionner correctement et rapidement sur un maximum de matériel.
Il a été testé sur iPhone 6 et Android 4.4, qui ne disposent plus des dernières mises à jour de leurs navigateurs et dont les résolutions d'écran sont petites.

### Sobriété

Ce site Internet a été conçu de sorte que la navigation sur celui-ci consomme le moins d'énergie possible, en limitant les calculs et en évitant de trop solliciter le réseau Internet.
Peu ou pas de vidéos, images optimisées, sobriété éditoriale.

### Impression

Imprimer une page Internet va utiliser du papier et de l'encre, qui est un produit polluant.
Le site a été optimisé pour réduire la consommation de papier et d'encre en cas d'impression. 

### Technique

Pour ce faire un générateur de site statique a été utilisé ([Hugo](https://gohugo.io)), et afin d'en faciliter l'administration il a été couplé avec l'outil [DecapCMS](https://decapcms.org).

Les librairies CSS utilisées sont : [HTML5Boilerplate](https://html5boilerplate.com/) et [PureCss](https://purecss.io/), qui lui même embarque [Normalize.css](https://necolas.github.io/normalize.css/) et permet de faciliter le fait d'avoir un rendu identique sur les différents navigateurs.

Côté Javascript la librairie [Modernizr](https://modernizr.com/) est utilisée à nouveau pour harmoniser l'affichage entre les différents navigateurs.

Ces librairies ont été choisies pour leur minimalisme et leur légèreté. Les fichiers CSS et Javacript sont combinés et minimifiés.

### Référentiels

* [115 bonnes pratiques de GreenIt](https://github.com/cnumr/best-practices)
* [GR491, Le guide de Référence de Conception Responsable de Services Numériques](8https://gr491.isit-europe.org/)
* [Guide d'écoconception de services numériques](https://eco-conception.designersethiques.org/guide/fr/)
* [Référentiel général d'écoconception de services numériques (RGESN)](https://ecoresponsable.numerique.gouv.fr/publications/referentiel-general-ecoconception/)

### Formation et certification

GreenIt propose [plusieurs formations](https://formation.greenit.fr/) dont l'une sur l'écoconception, elle débouche sur une certification.

Le site a été réalisé par une personne ayant cette certification.

### Validation de la démarche

#### Avec l' EcoIndex

La page d'accueil du site Internet (qui est la plus grosse page du site) a été testé sur ecoindex.fr

En juin 2023, la page a un score de 82/100 ce qui lui accorde la meilleure note : "A" !

En effet l'EcoIndex confirme que la page :

* est légère (grâce aux images optimisés)
* simple (grâce à un visuel simple, non surchargé)
* effectue peu de requête HTTP (charge à un nombre d'image et d'éléments rédduits)

La page reste pour autant pratique et élégante.

Cliquez ici pour voir le [détails des résultats de la page d'accueil avec l'EcoIndex de juin 2023](https://www.ecoindex.fr/resultat/?id=49dc1979-c3d1-4f7e-993c-39da35ac3407).

![EcoIndex de la page](/img/eco_index.jpg "EcoIndex de la page")

#### Sur le site Kastor

La page d'accueil a une note de 93/100.

#### Evaluer l'empreinte environnementale de votre site Internet

* [Evaluer l'empreinte environnementale de votre site Internet](https://www.francenum.gouv.fr/guides-et-conseils/pilotage-de-lentreprise/numerique-durable/evaluer-lempreinte-environnementale-de)

#### Audit d'audit de performance/vitesse d'un site web

* [GTMetrix](https://gtmetrix.com/)
* [Pingdom Tools](https://tools.pingdom.com/)
* [PageSpeed Insights](https://pagespeed.web.dev/?utm_source=psi&utm_medium=redirect&hl=fr)
* [FastorSlow](https://www.fastorslow.com/)
