---
layout: post
title: Installation qgis
published: true
---

Installation qgis suivant osgeo4w.

## Rappel de la procédure:

cf [https://frama.link/SnwLEzXB](https://frama.link/SnwLEzXB)

* installateur réseau osgeo
* ajout de libs (esri gdb, geopandas...)
* mises à jour mensuelles

## install express

![qgis_setup1_1.PNG]({{site.baseurl}}/images/qgis_setup1_1.PNG)

![qgis_setup1_2.PNG]({{site.baseurl}}/images/qgis_setup1_2.PNG)

## install avancée

* ajout du driver esri fileGDB
* ajout du module python geopandas ([http://geopandas.org/](http://geopandas.org/))

![qgis_setup2_1.PNG]({{site.baseurl}}/images/qgis_setup2_1.PNG)

![qgis_setup2_filegdb.PNG]({{site.baseurl}}/images/qgis_setup2_filegdb.PNG)

![qgis_setup2_geopandas.PNG]({{site.baseurl}}/images/qgis_setup2_geopandas.PNG)

## bilan

![about_qgis.PNG]({{site.baseurl}}/images/about_qgis.PNG)

> A noter: la version 3.10.0 connaît quelques bugs (notamment accès au plugin grass). On y remédiera en installant la version ltr (advancedqgis-ltr-full metapackage).
