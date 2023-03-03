---
title: "Training Data Lab - VIP Project: Machine Learning Applications in Public Policy and Economics"
layout: textlay
excerpt: "VIP Project: Machine Learning Applications in Public Policy and Economics"
sitemap: false
permalink: /projects/vip-project-machine-learning
---

# VIP Project: Machine Learning Applications in Public Policy and Economics

**Researchers:** Carla Cisternas and Francisco Castañeda

**Associates:** Bastián González-Bustamante, Rodrigo Cuevas and Diego Aguilar

**Assistants:** Esteban Barrios, Virla Liberona, Felipe Aniñir, Sebastián Saldías, Carolina Ávila, Gonzalo Avaria, Matías Carrillo and Nicolas Garrido

![Project Status: Suspended]({{ site.url }}{{ site.baseurl }}/badges/project_status/project_suspended.svg) &nbsp;&nbsp; [![English]({{ site.url }}{{ site.baseurl }}/badges/lang/english.svg)](https://training-datalab.com/projects/vip-project-machine-learning) &nbsp;&nbsp; [![Spanish]({{ site.url }}{{ site.baseurl }}/badges/lang/spanish_inactive.svg)](https://training-datalab.com/projects/vip-project-machine-learning-spanish)

![]({{ site.url }}{{ site.baseurl }}/images/projects/UMayor.png){: style="width: 350px; float: right; border: 10px"}

## Overview

<p align="justify">This project addresses the complexity of different political, social, and economic phenomena from a multidisciplinary approach by analysing big data. This project seeks, in particular, to develop and use machine learning applications to detect anomalies in data used by decision-makers and understand current social dynamics and information consumption dynamics.  In general, this project aims to study a number of social science research topics using trained algorithms.</p>

<p align="justify">A case in point is Cambridge Analytica, a company accused of manipulating the 2016 US elections by positioning ideas and perceptions on Facebook. Indeed, during the electoral campaign, the company unauthorisedly collected Facebook user data to conduct micro-targeted campaigns with fake news and disinformation subsequently. This emblematic case demonstrates how the manipulation of big data and machine learning techniques make it possible to affect political results and, thus, impact the economy and public policies of entire countries and regions.</p>

<p align="justify">In the first version of this project (2nd semester, 2021), we will focus precisely on misinformation about economic and public policy issues. To this end, our research team has programmed codes that allow the downloading of large volumes of information from the Chilean press and digital social networks in order to benchmark with different algorithms already trained to identify disinformation dynamics on specific topics. This way, we aim to explore and evaluate thematic gaps and compare their scope with more traditional and reliable information sources.</p>

<p align="justify">A distinguishing characteristic of this project is that we will train our algorithm with Chilean data to identify the particular dynamics of the national reality. In this process, the students who join our team will play a fundamental role through coding and labelling data subsamples to provide inputs to train a classification algorithm.</p>

## Objectives

<p align="justify">This project aims to form a vertically integrated multidisciplinary research team to use different machine learning applications in public policy and economics. In this very first version, we will focus on the dynamics of disinformation in economic and public interest issues. We expect to address and analyse other phenomena related to sectoral public policymaking and market regulation in subsequent versions.</p>

<p align="justify">Therefore, our main objective for our first case study is:</p>

<ul>
<li>To train a classification algorithm to identify disinformation levels in public policy and economic issues in the Chilean digital sphere.</li>
</ul>

<p align="justify">The vertical integration with students allows us to establish the following secondary objectives related to the tutoring environment to be developed:</p>

<ul>
<li>To train students in fundamental topics on social science research.</li>
<li>To introduce students to machine learning topics.</li>
<li>To train students in programming fundamentals in R.</li>
</ul>

## Research Methodology

<p align="justify">The vertical integration will be carried out between students from different years, principals and associate researchers in a synchronous tutoring environment (workshops or evaluation meetings of one chronological hour) and asynchronous weekly autonomous work with data (three hours per week).</p>

<p align="justify">Synchronous workshops and weekly meetings:</p>

<ul>
<li>Introduction and presentation of the project.</li>
<li>Fundamental notions of machine learning.</li>
<li>Disinformation and public opinion.</li>
<li>Fundamental elements of methodology.</li>
<li>Data coding and labelling.</li>
<li>Fundamentals of R.</li>
<li>Descriptive statistics in R.</li>
<li>Data coding evaluation.</li>
<li>Linear models in R.</li>
<li>Logistic models in R.</li>
<li>Data coding evaluation.</li>
<li>Regularisation and cross-validation.</li>
<li>Decision trees and Random Forest.</li>
<li>Data coding evaluation.</li>
<li>Presentation and comments on preliminary analysis.</li>
<li>Closing and self-evaluation of this first version.</li>
</ul>

<p align="justify">This project is developed by the Business School of the Universidad Mayor, but it will be carried out entirely online. No previous knowledge of statistics or programming is required, only access to a computer and Internet connection. Students will be evaluated during the data coding progress meetings (25% each) and the final session through self-evaluation (25%).</p>

<p align="justify">The synchronous tutorials, on the one hand, aim to train students in essential social science research topics and introduce them to machine learning and programming in R. For their part, the asynchronous autonomous work is related to data coding and labelling to train our algorithm, which will be constantly evaluated in several scheduled synchronous sessions.</p>

<p align="justify">Data sets compilation and labelling will be carried out with codes programmed in R and Python and on digital platforms developed by the research group comprised of several members of this project, bringing together researchers from different universities.</p>

## Coding and Machine Learning

<p align="justify">We draw two subsamples considering some messages per day from social media data of the Chilean referendum for a new Constitution in October 2020 (*N* = 2,529,134). We will carry out two data coding procedures in these subsamples to identify the position, emotionality, and credibility of the information. Then, we will train models and predict the non-coded social media data using machine learning techniques and incorporating human validation in the workflow.</p>

<p align="justify">It is relevant to note that the complete data set and subsamples have been properly anonymised with a cryptographic algorithm based on a hash function to meet the current ethical considerations on social media research.</p>

## Progress 1st Model

|---|---|---|---|---|---|---|
| 1. Data Gathering | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![100%]({{ site.url }}{{ site.baseurl }}/badges/progress_bar/100.svg) | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | 2. Data Cleaning | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![100%]({{ site.url }}{{ site.baseurl }}/badges/progress_bar/100.svg) |
| 3. Pilot | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![100%]({{ site.url }}{{ site.baseurl }}/badges/progress_bar/100.svg) | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | 4. Labelling | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![59%]({{ site.url }}{{ site.baseurl }}/badges/progress_bar/59.svg) |
| 5. Labelling Iterations | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![29%]({{ site.url }}{{ site.baseurl }}/badges/progress_bar/29.svg) | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | 6. Train Models | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![0%]({{ site.url }}{{ site.baseurl }}/badges/progress_bar/0.svg) |
| 7. Evaluate Models | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![0%]({{ site.url }}{{ site.baseurl }}/badges/progress_bar/0.svg) | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | 8. Predictions | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![0%]({{ site.url }}{{ site.baseurl }}/badges/progress_bar/0.svg) |
| 9. Augmented AI | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![0%]({{ site.url }}{{ site.baseurl }}/badges/progress_bar/0.svg) | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | 10. Benchmarking | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | ![0%]({{ site.url }}{{ site.baseurl }}/badges/progress_bar/0.svg) |

## Intellectual Property

<p align="justify">In order to promote innovation, the intellectual property of what is created in this VIP project will be shared between students and principals and associate researchers. Therefore, team members will be able to use the data collected for their publications, thanking and mentioning the project appropriately. We hope, in future versions, to encourage more experienced students to use the data in co-authorships with team researchers and take on leadership roles to mentor and train new team members.</p>
<br />
<small>Last updated: December 3, 2021.</small>
