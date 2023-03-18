---
title: "Training Data Lab - Data Mining Chilean Civil Service"
layout: textlay
excerpt: "Data Mining Chilean Civil Service"
sitemap: false
permalink: /projects/chilean-civil-service-spanish
---

# Minería de datos del servicio civil chileno

![]({{ site.url }}{{ site.baseurl }}/images/lab-diagrams/civil_service.png){: style="width: 250px; float: right; border: 10px"}

**Investigador:** Bastián González-Bustamante

**Asistentes:** Matías Astete y Berenice Orvenes

![Project Status: Completed]({{ site.url }}{{ site.baseurl }}/badges/project_status/project_completed.svg) &nbsp;&nbsp; [![English]({{ site.url }}{{ site.baseurl }}/badges/lang/english_inactive.svg)](https://training-datalab.com/projects/chilean-civil-service) &nbsp;&nbsp; [![Spanish]({{ site.url }}{{ site.baseurl }}/badges/lang/spanish.svg)](https://training-datalab.com/projects/chilean-civil-service-spanish)

## Creación del conjunto de datos

<p align="justify">Las fuentes originales de información corresponden a datos liberados por la DNSC en respuesta a las solicitudes AE004T0000240 y AE004T0000484 en el marco de la Ley 20.285 sobre Acceso a la Información Pública, realizadas el 26 de diciembre de 2016 y el 26 de abril de 2018, respectivamente. Con la primera solicitud elaboramos una base de datos de altos directivos públicos para el período 2009-2015 (*N* = 391, véase también <a href="https://doi.org/10.1111/blar.13044" target="_blank">González-Bustamante, 2020</a>).</p>

<p align="justify">Con esta base de datos y la segunda solicitud elaboramos un listado de 452 directivos del primer nivel jerárquico para el período 2009-2017. Posteriormente, recopilamos 1.396 documentos públicos, entre decretos de nombramiento, actas de los concursos, noticias institucionales, entre otros similares.</p>

<p align="justify">Los documentos fueron cargados en la plataforma <a href="https://doi.org/10.17605/OSF.IO/WBF6M" target="_blank">Open Science Framework (OSF)</a> y se les asignó una URL permanente única que nos permitió aplicar un algoritmo de reconocimiento óptico (OCR) programado específicamente para este propósito. De esta forma, los documentos PDF fueron convertidos en imágenes PNG que fueron cargadas en el <a href="https://github.com/bgonzalezbustamante" target="_blank">repositorio del proyecto en GitHub</a> que está conectado con OSF (*surv-civil-servants*, actualmente privado y pronto disponible para consulta pública).</p>

<p align="justify">Las imágenes se convirtieron a un formato de texto manejable a través del proceso previamente descrito con el fin de emparejar y verificar los documentos con los casos identificados. Esto nos permitió validar los casos.</p>

## Recursos

- <a href="https://doi.org/10.31235/osf.io/vshcz" target="_blank">SocArXiv preprint en inglés</a>.
- <a href="https://doi.org/10.22370/rgp.2020.9.2.2920" target="_blank">Artículo publicado en español</a>.

<small>Arte por DALL·E en un estilo impresionista.</small><br />
<small>Última actualización: 23 de agosto de 2021.</small>
