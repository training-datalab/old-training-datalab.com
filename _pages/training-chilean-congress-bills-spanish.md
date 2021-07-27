---
title: "Training Data Lab - Entrenamiento de datos sobre los proyectos de ley del Congreso chileno"
layout: textlay
excerpt: "Entrenamiento de datos sobre los proyectos de ley del Congreso chileno"
sitemap: false
permalink: /projects/chilean-congress-bills-spanish
---

# Entrenamiento de datos sobre los proyectos de ley del Congreso chileno

**Investigadores:** Carla Cisternas y Bastián González-Bustamante

**Asociados:** Diego Aguilar

**Asistentes:** Elinor Luco y Beatriz Herrera

[Ver proyecto en inglés]({{ site.url }}{{ site.baseurl }}/projects/chilean-congress-bills) 

## Datos y muestras

![]({{ site.url }}{{ site.baseurl }}/images/lab-diagrams/diagram_bills.png){: style="width: 350px; float: right; border: 10px"}

<p align="justify">A partir de un conjunto de datos de proyectos de ley de la Cámara de Diputados de Chile entre 2006 y 2018 (*N* = 4.139), período que corresponde a tres administraciones, extraemos una submuestra aleatoria considerando algunos proyectos de ley por mes. En esta submuestra realizamos dos procedimientos de codificación de datos para identificar tanto el tema del proyecto de ley como su alcance territorial. </p>

## Codificación de los proyectos de ley del Congreso chileno

<p align="justify">Buscamos codificadores *ad honorem* para etiquetar nuestra submuestra de proyectos de ley del Congreso para esta investigación. Necesitamos estudiantes de licenciatura o de magíster de programas de ciencias sociales. Nuestros codificadores recibirán formación general y dedicarán una cantidad de tiempo variable y flexible a esta tarea.</p>

<p align="justify">No trabajamos con un número concreto de codificadores porque iteramos el proceso de etiquetado para mejorar la precisión de la codificación hasta alcanzar un nivel de alta confiabilidad. Cada observación de la submuestra requiere la validación de un número diferente de codificadores en función de las categorías de la tarea de clasificación específica. Por ejemplo, la identificación del ámbito territorial de los proyectos posee un umbral más alto de codificadores que la identificación del tema, que tiene menos resultados posibles.</p>

<p align="justify">Para más detalles, póngase en contacto con <a href="mailto:c.g.cisternas.guasch@hum.leidenuniv.nl">c.g.cisternas.guasch@hum.leidenuniv.nl</a>.</p>

## Clasificación con aprendizaje automático

<p align="justify">Una vez codificada la base de datos, entrenamos un modelo y predecimos los datos no codificados mediante técnicas de aprendizaje automático. En esta fase, es posible incorporar la validación humana en el flujo de trabajo para revisar las observaciones con valores de confianza bajos. Finalmente, tendremos los datos necesarios para realizar nuestro análisis principal, en este caso, modelos estocásticos basados en actores para redes dinámicas, con el objetivo de observar las estrategias de copatrocinio en el Congreso de Chile a lo largo del período.</p>

## Fases

|---|---|---|---|---|---|---|
| 1. Recopilación de datos | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![100%](https://progress-bar.dev/100) | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | 2. Limpieza de datos | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![100%](https://progress-bar.dev/100) |
| 3. Etiquetado | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![33%](https://progress-bar.dev/33) | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | 4. Iteraciones del etiquetado | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![7%](https://progress-bar.dev/7) |
| 5. Entrenamiento del modelo | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![0%](https://progress-bar.dev/0) | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | 6. Evaluación del modelo | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![0%](https://progress-bar.dev/0) |
| 7. Predicciones | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![0%](https://progress-bar.dev/0) | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | 8. IA aumentada | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![0%](https://progress-bar.dev/0) |

<small>Última actualización: 27 de julio de 2021.</small>
