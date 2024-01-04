# Etiquetas de HTML 5

<br>

## ¿Qué es HTML? 🚀

_HTML es un lenguaje de marcado de texto, esto sirve para crear la estructura o esqueleto de una pagina web, son las condiciones que va seguir la página web de cómo va estar diseñada. Esta tecnología es estándar a nivel mundial, ya que todos tenemos que trabajar sobre este marco de reglas para mostrar una página web en internet._

<br>

## Elementos Raíz 🌱

| Elemento              | Descripción                                                                                                  |
|:---------------------:|--------------------------------------------------------------------------------------------------------------|
| ```<!DOCTYPE html>``` | Define que el documento esta bajo el estandar de HTML 5.                                                     |
| ```</html>```         | Representa la raíz de un documento HTML. Todos los demás elementos deben ser descendientes de este elemento. |

<br>

## Metadatos ☄

| Elemento      | Descripción                                                                                                                     |
|:-------------:|---------------------------------------------------------------------------------------------------------------------------------|
| ```<head>```  | Representa una colección de metadatos acerca del documento, incluyendo enlaces a, o definiciones de, scripts y hojas de estilo. |
| ```<title>``` | Define el título del documento, el cual se muestra en la barra de título del navegador o en las pestañas de página.             |
| ```<link>```  | Usada para enlazar JavaScript y CSS externos con el documento HTML actual.                                                      |
| ```<meta>```  | Define los metadatos que no pueden ser definidos usando otro elemento HTML.                                                     |
| ```<style>``` | Etiqueta de estilo usada para escribir CSS en línea.                                                                            |
| ```<script>``` | Define ya sea un script interno o un enlace hacia un script externo. El lenguaje de programación es JavaScript.                                                                            |

<br>

## Secciones 📚

| Elemento                            | Descripción                                                                                                                                                                                                                        |
|:----------------:|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ```<body>```                        | Representa el contenido principal de un documento HTML. Solo hay un elemento de este tipo en un documento.                                                                                                                         |
| ```<section>```                     | Define una sección en un documento.                                                                                                                                                                                                |
| ```<nav>```                         | Define una sección que solamente contiene enlaces de navegación                                                                                                                                                                    |
| ```<article>```                     | Define contenido autónomo que podría existir independientemente del resto del contenido.                                                                                                                                           |
| ```<aside>```                       | Define algunos contenidos vagamente relacionados con el resto del contenido de la página. Suele estar al costado de la seccion general                                                                          |
| ```<h1>,<h2>,<h3>,<h4>,<h5>,<h6>``` | Los elemento de cabecera  implementan seis niveles de cabeceras de documentos; ```<h1>``` es la de mayor y ```<h6>``` es la de menor importancia. Un elemento de cabecera describe brevemente el tema de la sección que introduce. |
| ```<header>```                      | Define la cabecera de una página o sección. Usualmente contiene un logotipo, el título del sitio Web y una tabla de navegación de contenidos.                                                                                      |
| ```<footer>```                      | Define el pie de una página o sección. Usualmente contiene un mensaje de derechos de autoría, algunos enlaces a información legal o direcciones para dar información de retroalimentación.                                         |
| ```<address>```                     | Define una sección que contiene información de contacto.                                                                                                                                                                           |
| ```<main>```                        | Define el contenido principal o importante en el documento. Solamente existe un elemento ```<main>``` en el documento.                                                                                                             |

<br>

## Agrupación de Contenido ✨

| Elemento           | Descripción                                                                                    |
|:------------------:|------------------------------------------------------------------------------------------------|
| ```<p>```          | Define una parte que debe mostrarse como un párrafo.                                           |
| ```<hr>```         | Representa un quiebre temático entre párrafos de una sección o articulo o cualquier contenido. |
| ```<blockquote>``` | Representa un contenido citado desde otra fuente.                                              |
| ```<ol>```         | Define una lista ordenada de artículos.                                                        |
| ```<ul>```         | Define una lista de artículos sin orden.                                                       |
| ```<li>```         | Define un artículo de una lista enumerada.                                                     |
| ```<div>```        | Representa un contenedor genérico sin ningún significado especial.                             |

<br>

## Textos 🔠

| Elemento       | Descripción                                                           |
|:--------------:|-----------------------------------------------------------------------|
| ```<a>```      | Representa un hiperenlace, enlazando a otro recurso.                  |
| ```<em>```     | Representa un texto enfatizado, como un acento de intensidad cursiva. |
| ```<strong>``` | Representa un texto especialmente importante en negrita.              |
| ```<small>```  | Representa textos menos importantes y de un tamaño menor.             |
| ```<cite>```   | Representa un mensaje o frase representativa.                         |
| ```<q>```      | Representa una cita textual inline.                                   |
| ```<var>```    | Representa a una variable.                                            |
| ```<span>```   | Representa texto sin un significado específico.                       |
| ```<br>```     | Representa un salto de línea.                                         |


<br>

## Contenido Incrustado 🖼

| Elemento       | Descripción                                                                                                                                                             |
|:----------------:|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ```<img>```    | Representa una imagen.                                                                                                                                                  |
| ```<iframe>``` | Representa un contexto anidado de navegación, es decir, un documento HTML embebido.                                                                                     |
| ```<object>``` | Representa un recurso externo, que será tratado como una imagen, un sub-documento HTML o un recurso externo a ser procesado por un plugin.                              |
| ```<param>```  | Define parámetros para el uso por los plugins invocados por los elementos ```<object>```.                                                                               |
| ```<video>```  | Representa un video, y sus archivos de audio y capciones asociadas, con la interfaz necesaria para reproducirlos.                                                       |
| ```<audio>```  | Representa un sonido o stream de audio.                                                                                                                                 |
| ```<source>``` | Permite a autores especificar recursos multimedia alternativos para los elementos multimedia como ```<video>``` o ```<audio>```.                                        |
| ```<canvas>``` | Representa un área de mapa de bits  en el que se pueden utilizar scripts para renderizar gráficos como gráficas, gráficas de juegos o cualquier imagen visual al vuelo. |
| ```<map>```    | En conjunto con ```<area>```, define un mapa de imagen.                                                                                                                 |
| ```<area>```   | En conjunto con ```<map>```, define un mapa de imagen.                                                                                                                  |


<br>

## Tablas 📋

| Elemento         | Descripción                                                                          |
|:----------------:|--------------------------------------------------------------------------------------|
| ```<table>```    | Representa datos con más de una dimensión.                                           |
| ```<caption>```  | Representa el título de una tabla.                                                   |
| ```<colgroup>``` | Representa un conjunto de una o más columnas de una tabla.                           |
| ```<col>```      | Representa una columna de una tabla.                                                 |
| ```<tbody>```    | Representa el bloque de filas que describen los datos concretos de una tabla.        |
| ```<thead>```    | Representa el bloque de filas que describen las etiquetas de columna de una tabla.   |
| ```<tfoot>```    | Representa los bloques de filas que describen los resúmenes de columna de una tabla. |
| ```<tr>```       | Representa una fila de celdas en una tabla.                                          |
| ```<td>```       | Representa una celda de datos en una tabla.                                          |
| ```<th>```       | Representa una celda encabezado en una tabla.                                        |


<br>

## Formularios 📑

| Elemento         | Descripción                                                                                                 |
|:----------------:|-------------------------------------------------------------------------------------------------------------|
| ```<form>```     | Representa un formulario, consistiendo de controles que puede ser enviado a un servidor para procesamiento. |
| ```<label>```    | Representa el título de un control de formulario.                                                           |
| ```<input>```    | Representa un campo de datos escrito que permite al usuario editar los datos.                               |
| ```<button>```   | Representa un botón.                                                                                        |
| ```<select>```   | Representa un control que permite la selección entre un conjunto de opciones.                               |
| ```<option>```   | Representa una opción en un elemento.                                                                       |
| ```<textarea>``` | Representa un control de edición de texto multilínea.                                                       |

<br><br>
