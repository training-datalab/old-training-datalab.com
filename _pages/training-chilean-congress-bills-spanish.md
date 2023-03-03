---
title: "Training Data Lab - Entrenamiento de datos sobre los proyectos de ley del Congreso chileno"
layout: textlay
excerpt: "Entrenamiento de datos sobre los proyectos de ley del Congreso chileno"
sitemap: false
permalink: /projects/chilean-congress-bills-spanish
---

# Entrenamiento de datos sobre los proyectos de ley del Congreso chileno

**Investigadores:** Carla Cisternas, Bastián González-Bustamante, Jaquelin Morillo y Diego Aguilar

![Project Status: Suspended]({{ site.url }}{{ site.baseurl }}/badges/project_status/project_suspended.svg) &nbsp;&nbsp; [![English]({{ site.url }}{{ site.baseurl }}/badges/lang/english_inactive.svg)](https://training-datalab.com/projects/chilean-congress-bills) &nbsp;&nbsp; [![Spanish]({{ site.url }}{{ site.baseurl }}/badges/lang/spanish.svg)](https://training-datalab.com/projects/chilean-congress-bills-spanish)

![]({{ site.url }}{{ site.baseurl }}/images/lab-diagrams/bills_training.png){: style="width: 250px; float: right; border: 10px"}

## Datos y muestras

<p align="justify">A partir de un conjunto de datos de proyectos de ley de la Cámara de Diputados de Chile entre 2006 y 2018 (*N* = 4.139), período que corresponde a tres administraciones, extraemos una submuestra aleatoria considerando algunos proyectos de ley por mes. En esta submuestra realizamos dos procedimientos de codificación de datos para identificar tanto el tema del proyecto de ley como su alcance territorial. </p>

## Codificación de los proyectos de ley del Congreso chileno

<p align="justify">Buscamos codificadores *ad honorem* para etiquetar nuestra submuestra de proyectos de ley del Congreso para esta investigación. Necesitamos estudiantes de licenciatura o de magíster de programas de ciencias sociales. Nuestros codificadores recibirán formación general y dedicarán una cantidad de tiempo variable y flexible a esta tarea.</p>

<p align="justify">No trabajamos con un número concreto de codificadores porque iteramos el proceso de etiquetado para mejorar la precisión de la codificación hasta alcanzar un nivel de alta confiabilidad. Cada observación de la submuestra requiere la validación de un número diferente de codificadores en función de las categorías de la tarea de clasificación específica. Por ejemplo, la identificación del ámbito territorial de los proyectos posee un umbral más alto de codificadores que la identificación del tema, que tiene menos resultados posibles.</p>

<p align="justify">Para más detalles, póngase en contacto con <a href="mailto:c.g.cisternas.guasch@hum.leidenuniv.nl">c.g.cisternas.guasch@hum.leidenuniv.nl</a>.</p>

## Clasificación con aprendizaje automático

<p align="justify">Una vez codificada la base de datos, entrenamos un modelo y predecimos los datos no codificados mediante técnicas de aprendizaje automático. En esta fase, es posible incorporar la validación humana en el flujo de trabajo para revisar las observaciones con valores de confianza bajos. Finalmente, tendremos los datos necesarios para realizar nuestro análisis principal, en este caso, modelos estocásticos basados en actores para redes dinámicas, con el objetivo de observar las estrategias de copatrocinio en el Congreso de Chile a lo largo del período.</p>

## Fases

|---|---|---|---|---|---|---|
| 1. Recopilación de datos | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![100%]({{ site.url }}{{ site.baseurl }}/badges/progress_bar/100.svg) | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | 2. Limpieza de datos | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![100%]({{ site.url }}{{ site.baseurl }}/badges/progress_bar/100.svg) |
| 3. Etiquetado | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![88%]({{ site.url }}{{ site.baseurl }}/badges/progress_bar/88.svg) | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | 4. Iteraciones del etiquetado | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![64%]({{ site.url }}{{ site.baseurl }}/badges/progress_bar/64.svg) |
| 5. Entrenamiento del modelo | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![33%]({{ site.url }}{{ site.baseurl }}/badges/progress_bar/33.svg) | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | 6. Evaluación del modelo | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![33%]({{ site.url }}{{ site.baseurl }}/badges/progress_bar/33.svg) |
| 7. Predicciones | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![0%]({{ site.url }}{{ site.baseurl }}/badges/progress_bar/0.svg) | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | 8. IA aumentada | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![0%]({{ site.url }}{{ site.baseurl }}/badges/progress_bar/0.svg) |

<br />
<small>Arte por DALL·E en un estilo impresionista.</small><br />
<small>Última actualización: 17 de febrero de 2023.</small>
