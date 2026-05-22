[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=VaniDani/MSFProyectoFinal)

# MSFProyectoFinal
Proyecto Final: Sistema óptico
<img width="1448" height="1086" alt="ChatGPT Image May 19, 2026, 06_10_45 PM" src="https://github.com/user-attachments/assets/779a3d30-b6dd-4774-8c40-efd1bdab4a0a" />

## Información de las estudiantes

Vania Daniela Rivera Duran \[C22211720]; l22211720@tijuana.tecnm.mx

Adriana Estefania Bañuelos Ocampo \[23210694]; l23210694@tijuana.tecnm.mx

Modelado de Sistemas Fisiológicos

Ingeniería Biomédica

## Docente

Dr. Paul Antonio Valle Trujillo; paul.valle@tectijuana.edu.mx

Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana, Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México.

## Descripción de la asignatura

El modelizado de sistemas fisiológicos es una herramienta importante en Ingeniería Biomédica, permite comprender el funcionamiento del cuerpo humano, así como diseñar y evaluar terapias y dispositivos médicos; se define como el proceso de formular modelos matemáticos o computacionales que representan el comportamiento y la interacción de los sistemas biológicos y fisiológicos. Esta asignatura pretende aportar al perfil del Ingeniero Biomédico la capacidad de realizar investigación científica en el área de Biología de Sistemas con la finalidad de dirigir y participar en equipos de trabajo interdisciplinarios en contextos nacionales e internacionales, así como de proporcionar soluciones informáticas para resolver problemas en el campo de la Ingeniería Biomédica con ética profesional; lo anterior al proporcionar al estudiante bases sólidas para modelizar sistemas y diseñar controladores para la solución de problemas en las áreas de atención médica y del sector industrial médico. La construcción de analogías entre circuitos eléctricos y sistemas fisiológicos para la formulación de modelos matemáticos y el diseño de controladores mediante la experimentación in silico brindan herramientas de gran aplicación en el quehacer profesional del Ingeniero Biomédico.

La asignatura de Modelado de Sistemas Fisiológicos forma parte del plan de estudios de la carrera en Ingeniería Biomédica con la siguiente competencia general del curso: Utiliza las propiedades de los circuitos RLC para describir la dinámica de sistemas fisiológicos, obtener modelos matemáticos y aplicar el control clásico, esto con el objetivo de integrar los principios de la Ingeniería de Control, la Electrónica Analógica y las Ciencias de la Computación con la Anatomía y Fisiología del cuerpo humano para proporcionar descripciones cuantitativas y cualitativas de sistemas fisiológicos complejos con el objetivo de modelizar, analizar, controlar, ilustrar y predecir su dinámica tanto en el corto como en el largo plazo.

# Objetivos
Modelar el sistema ópctico mediante una analogía eléctrica con un circuito RLC de dos mallas, representando el flujo del humor acuoso y la presión intraocular.
Simular la entrada de luz al ojo como una señal sinusoidal y analizar cómo se transforma en información visual.
Relacionar parámetros eléctricos con funciones fisiológicas: impedancia, inductancia, capacitancia y resistencia, para comprender su papel en la formación de la imagen.
Estudiar el efecto del astigmatismo en la dinámica del sistema ocular, identificando los cambios en la impedancia y la inductancia.

Palabras clave: Sistema óptico, circuito de segundo orden, análogía eléctrica, astigmatismo, modelo matemático.

## Descripción detallada del sistema

<img width="720" height="504" alt="Diagrama fisiológico" src="https://github.com/user-attachments/assets/8c6cfc50-83ba-4cdd-adae-6a4d0244c159" />

Se estudió el sistema óptico, enfocándose en el flujo del humor acuoso y la presión intraocular. Para analizar su dinámica se utilizó un modelo eléctrico mediante un circuito RLC de dos mallas, donde cada parámetro representa una característica fisiológica del ojo.
La entrada sinusoidal simula la luz que ingresa al ojo.
La corriente representa el flujo de información visual.
La impedancia (Z) refleja la oposición al paso de la luz, aumentando en el astigmatismo.
La inductancia (L) modela el retardo en la propagación de la señal visual.
El capacitor (C) simboliza la capacidad de adaptación óptica.
La resistencia (R) representa pérdidas de luz.
La salida (Pp(t)) corresponde a la calidad de la imagen en la retina.
El circuito de dos mallas representa:
La circulación del humor acuoso.
El almacenamiento y drenaje de la presión intraocular.

Palabras clave: Sistema óptico, circuito de segundo orden, análogía eléctrica, astigmatismo, modelo matemático.

## Lista de archivos incluidos en el repositorio

1. Cuaderno computacional de MATLAB \[.mlx].
2. Modelo de Simulink \[.slx].
3. Archivos de Spyder \[.py].
4. Imagen con los parámetros del controlador.
5. Imágenes de las simulaciones \[.pdf].
6. Evidencia del análisis matemático: función de transferencia, modelo de ecuaciones integro-diferenciales, error en estado estacionario y estabilidad en lazo abierto.
7. Modelo fisiológico en Biorender o BioArt.

## Referencias

\[1] P. A. Valle, Syllabus para Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México / Instituto Tecnológico de Tijuana, Tijuana, B.C., México, 2025. Permalink: https://biomath.xyz/course/

\[2] M. C. Khoo, Physiological Control Systems Analysis Simulation, and Estimation, 2nd ed. Piscataway, New Jersey, USA: IEEE Press, 2018, Section 4, Page 93.

\[3] N. S. Nise, Control Systems Engineering, 8th ed. Hoboken, New Jersey, USA: John Wiley \& Sons, 2020.

\[4] T. Kind, T. J. Faes, J. W. Lankhaar, A. Vonk-Noordegraaf \& M. Verhaegen, "Estimation of three-and four-element Windkessel parameters using subspace model identification", IEEE Transactions on Biomedical Engineering, vol. 57, issue 7, pp. 1531-1538, Jul 2010. https://doi.org/10.1109/TBME.2010.2041351


