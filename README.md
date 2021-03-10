# Datasets de Productos de Electrónica

<a href="https://datamarket.es">
  <img src="https://datamarket.es/static/core/img/banners/productos-de-electronica-banner.png">
</a>

## Descripción

Precios de portátiles, televisores, móviles... __Cualquier producto de electrónica en las principales plataformas online__. 

Las características de este dataset son las siguientes:

* __Frecuencia de actualización__: actualizado cada 12h
* __Volumen estimado__: en construcción
* __Histórico__: en construcción

El dataset completo se puede adquirir en [DataMarket](https://datamarket.es/#productos-de-electronica-dataset), plataforma de referencia de datos externos en España. 

Este repositorio contiene los siguientes recursos:

* La documentación completa del dataset.
* Una muestra representativa del mismo disponible para su evaluación y uso gratuito.

## Muestra

La muestra se encuentra disponible para descarga en el siguiente [link](https://github.com/Data-Market/productos-de-electronica/blob/main/productos-de-electronica-sample.csv).

## Documentación
A continuación se muestran las columnas de las que consta el dataset junto con su descripción.

| nombre      | tipo     | descripción                                                                                                            | ejemplo                                                                         |
|-------------|----------|------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|
| website     | str      | Páginas webs de venta de productos electrónicos (encriptado). Este campo será visible tras la subscripción al dataset. | 36025B45AABC6C3B282A0DCD6578DFBF                                                |
| category    | str      | Diferentes tipos de productos electrónicos que se ofertan.                                                             | ordenadores_portatiles                                                          |
| name        | str      | Nombre de cada producto electrónico en venta.                                                                          | Gigabyte AORUS 7 KB-7ES1130SD Intel Core i7-10750H/16GB/512GB SSD/RTX2060/17.3" |
| price       | float    | Precio de los diferentes productos electrónicos en euros.                                                              | 1159.0                                                                          |
| score       | float    | Valoraciones de los compradores para cada producto.                                                                    | 4.4                                                                             |
| n_reviews   | int      | Número de opiniones por parte de los compradores para cada producto electrónico.                                       | 60                                                                              |
| n_units     | int      | Número de unidades disponibles de cada producto.                                                                       | 50                                                                              |
| insert_date | datetime | Fecha de extracción de la información.                                                                                 | 2021-01-09 11:10:00                                                             |
