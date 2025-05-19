[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=4l3xand3r-ia/practica-5-Analisis-de-sistemas-biologicos-21212848-)

# Gemelos Digitales. Práctica 5:Analisis de sistemas biologicos [Torres21212848]

## Autor
Alexander Torres Avila

Ingeniería Biomédica, Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: l21212848@tectijuana.edu.mx

## Resumen de la práctica
En esta práctica se estudia un sistema dinámico compuesto por tres ecuaciones diferenciales ordinarias (EDOs) de primer orden, basado en modelos clásicos como el sistema presa-depredador de Lotka-Volterra y el modelo de Itik y Banks. El sistema describe la interacción entre tres tipos de células en un entorno biológico: células patológicas (anormales), células normales (sanas) y células efectoras (como las células NK o citotóxicas).

Las ecuaciones se expresan como:

ẋ = r₁x(1 − b₁x) − a₁₂xy − a₁₃xz
Crecimiento logístico de células patológicas con interacción negativa de células normales y efectoras.

ẏ = r₂y(1 − b₂y) − a₂₁xy
Crecimiento logístico de células sanas, afectadas por células patológicas.

ż = (r₃ − a₃₁x)z − d₃z + ρᵢ
Crecimiento de células efectoras regulado por acción de masas, muerte celular e inmunoterapia.

Este modelo permite ilustrar cómo se regulan mutuamente estas poblaciones celulares, simulando fenómenos como infecciones, respuesta inmune, crecimiento tumoral e intervención mediante terapias inmunológicas. El análisis se centra en cómo los parámetros y condiciones iniciales determinan la existencia de diferentes conjuntos compactos invariantes (áreas donde las soluciones del sistema permanecen confinadas), lo que es crucial para predecir la evolución del sistema y establecer control sobre él.

La experimentación in silico con este modelo contribuye a comprender sistemas autorregulados complejos y proporciona una base sólida para el desarrollo de gemelos digitales en salud.

## Objetivos específicos
1. Modelar interacciones celulares complejas mediante EDOs que describen dinámicas como competencia, depredación e inmunorregulación.
2. Analizar el comportamiento cualitativo del sistema, identificando puntos de equilibrio y dominios de estabilidad.
3. Evaluar el impacto de parámetros clave, como tasas de crecimiento, interacción y tratamiento (ρᵢ), en la evolución del sistema.
4. Visualizar trayectorias del sistema y conjuntos invariantes para distintos valores de condiciones iniciales, destacando la sensibilidad del sistema.
5. Aplicar el modelo a contextos clínicos, como el control del crecimiento tumoral y el diseño de terapias personalizadas basadas en inmunología computacional.

## Docente
Dr. Paul A. Valle

Posgrado en Ciencias de la Ingeniería [PCI] y Departamento de Ingeniería Eléctrica y Electrónica [DIEE], Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: paul.valle@tectijuana.edu.mx

## Lecturas
[1] Paul. A. Valle, Syllabus de Biomatemáticas para la asignatura de Gemelos Digitales, Tecnológico Nacional de México/IT Tijuana, Tijuana, B.C., México, 2025. Permalink: https://www.dropbox.com/s/6yf9afxzih9y458/Biomatematicas.pdf
