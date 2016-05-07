---
title: "Resultado2.md"
author: "ErickGutierrez"
date: "04/05/2016"
output: html_document
---

##Resultado del estudio sobre una posible predicción de las aplicaciones que serán las más vendidas

Para este estudio tomé encuenta las columnas del dataset: 

* La versión de la app.
* Las instalaciones actuales en dispositivos.
* Las instalaciones actuales de usuarios.
* La cantidad diarias de aplicaciones instaladas en dispositivos.
* Instalaciones totales de usuarios.
* Las actualizaciones diarias en dispositivos.
* La cantidad diarias de aplicaciones instaladas de usuarios

Usamos un arbol de decision ya que deseamos ver segun los datos presentes, cuáles serán las aplicaciones con mayor descarga a futuro de manera que se pueda tener una idea de como trabaja Google Store en el mercadeo de sus productos.

Utilizamos Set Role para definir sobre qué parámetro se va a realizar el estudio, posteriormente usamos Select Attributes para escoger las columnas anteriormente mencionadas y posteriormente usamos un Decision Tree para el algoritmo de predicción.

Verificamos con el resultado del arbol que realiza comparaciones entre cada valor de cada columna en comparación a sus datos segun mayor y menor.
Con esto tambien podemos ver que no siempre el dato mayor puede obtener un mejor resultado a futuro.
También podemos observar que el arbol se redujo a los parámetros de Las actualizaciones diarias en dispositivos y Instalaciones totales de usuarios donde, con comparaciones de mayor que y menor o igual que vemos que las versiones 41 y 20400201 serán las que perdurarán más tiempo en el mercado.
