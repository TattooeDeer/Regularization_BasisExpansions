# Regularización basica y expansiones de base

Este es un notebook de ejemplo donde se trabaja con datos recopilados por tres administradores de conexiones (Enexis, Liander y Stedin) en los Paises Bajos. Para mayor información sobre el dataset visitar: https://www.kaggle.com/lucabasa/dutch-energy

La mayor parte de ese ejemplo se centra en regresionar el consumo anual (agrupado por zipcode para 10 conexiones, de forma de garantizar el anonimato de las fuentes).

El objetivo es mostrar a los alumnos como instanciar modelos de regresión lineal con regularizaciones clásicas (Ridge, Lasso y Elastic-Net), finalmente, se muestra la resolución del mismo modelo utilizando modelos lineales aditivos generalizados utilizando la librería `pygam`.