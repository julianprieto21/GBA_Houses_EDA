# GBA_Houses_EDA
![image](https://user-images.githubusercontent.com/114876710/230691558-63009951-161e-4897-96e5-17c6490662b4.png)


Analisis Exploratorio de casas en venta en el Gran Buenos Aires publicadas en Mercado Libre Ar. https://www.mercadolibre.com.ar/
Para esto se realizó "scraping" para recolectar la mayor cantidad de publicaciones de diferentes localidades.
De cada publicacion se recolectó la zona, la localidad, los metros cuadrados, la cantidad de ambientes y el valor(USD).
Luego se realizó un analisis exploratorio de las informacion conseguida utilizando pandas, matplotlib y seaborn.
Durante este analisis se "limpio" el dataset de datos leidos erroneamente y otros que se prefirió omitir para este analisis (Explicado casos en el codigo).
El dataset fue creado utilizando las librerias de scraping de BeautifulSoup 4 y request. Se convirtio en un archivo .csv utilizando la libreria del mismo nombre.

