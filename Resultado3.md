---
title: "Resultado3.md"
author: "ErickGutierrez"
date: "05/05/2016"
output: html_document
---

##Resultado del estudio de la popularidad de las versiones.

Para este estudio tomé encuenta las columnas del dataset: 

* Las instalaciones actuales en dispositivos.
* Las instalaciones actuales de usuarios.
* La cantidad diarias de aplicaciones instaladas en dispositivos.
* La cantidad diarias de aplicaciones instaladas de usuarios
* Instalaciones totales de usuarios.

Hacemos el estudio filtrando por el total de intalaciones por usuarios, poniendo un parámetro de mayor/igual para poder clasificar posteriormente desde el mínimo que serían 0 instalaciones hasta el máximo de instalaciones.

Generamos un cluster usando 4 grupos donde las similitudes resultantes mostraran la popularidad de las aplicaciones instaladas segun la cantidad de descargas en cada clasificación y con 10 iteraciones.

Podemos ver en la tabla de centroides que se generaron 4 clusters sobre las columnas seleccionadas con los resultados de las iteraciones.
En el modelo de clusters nos muestra:
Cluster 0: 128 items
Cluster 1: 320 items
Cluster 2: 1596 items
Cluster 3: 32 items
Número total de items: 2076
Por último vemos el grafo del resultado el cual no es muy complicado.