---
layout: post
title: Installations diverses et ajustage PATH
---

## Installations diverses

* winSCP - Putty: installation depuis les repos officiels (Putty.exe posé dans le dossier par défaut, communication établie).
* notepad++, sublime text
* KeepAss2

## Ajout des exe python dans le PATH

Par défaut les installatios standard de qgis, arcgis 10.7 et arcgis pro n'inscrivent aucun executable python dans le path. On les ajoute manuellement en plusieurs étapes:
* identification des exe nécessaires: 
  - C:\Python27\ArcGISx6410.7\python.exe
  - C:\Program Files\ArcGIS\Pro\bin\Python\envs\arcgispro-py3\python.exe
  - C:\OSGeo4W64\bin\python-qgis.bat
* création d'un .bat pour chaque exe dans un dossier python_path (actuellement dans %USERPROFILE%\Documents)
  - python27..bat
  - python36.bat
  - python37.bat
* ajout de ce dossier dans le path utilisateur

Ce système permet d'invoquer une version spécifique de python par une commande console. Cette version s'accompagne de sa bibliothèque sig spécifique (arcpy ou gqis).

A l'heure actuelle cette opération est réalisée à titre de test et devra être généralisée dans dossier /path système.
