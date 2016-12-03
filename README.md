
kibana-plugin-line
==================

![screenshot](./screenshot.png)

Introduction
-------------

Ce plugin permet la création d'une vue avec plusieurs types de graphiques sur Kibana Version 4.x et 5.x :

* Choix du type de graphiques
* Définition du label des courbes
* Choix des couleurs
* Ajout d'un axe Y
* Format des axes Y et X
* Ajout d'une ligne sur l'axe Y 
* Modification du range Y
* Seuil de couleur


Contenu
-------
```
.
+-- index.js
+-- package.json
+-- public
    +-- bower_components
    ¦   +-- c3
    ¦   +-- moment
    +-- line_sg_controller.js
    +-- line_sg.html
    +-- line_sg.js
    +-- line_sg.less
    +-- line_sg_params.html
    +-- styles
        +-- accordion.css
```
Le plugin a été créé à partir des librairies Kibana et basé sur le framework Angularjs.

Liste des librairies ajoutées:

* c3.js: C3 makes it easy to generate D3-based charts by wrapping the code required to construct the entire chart. We don't need to write D3 code any more. (http://c3js.org/)
* moment.js: Parse, validate, manipulate, and display dates in JavaScript.(http://momentjs.com/)


Installation
------------

Pour les version de kibana-4.x
```
        $ cd <path>/kibana/installedPlugins
        $ git clone -b 4.x <depot> line-sg
```

Pour les version de kibana-5.x
```
        $ cd <path>/kibana/installedPlugins
        $ git clone <depot> line-sg
```

Désinstallation
---------------

```
	$ bin/kibana plugin  --remove line_sg
```
