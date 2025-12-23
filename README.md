# Dispensador de pasta para soldar

## Descripción del proyecto / Project Overview

Máquina operada por CNC diseñada para dispensar pasta de soldadura en componentes electrónicos SMD (Surface Mount Device). El proyecto busca automatizar este proceso de forma eficiente y económica, facilitando la soldadura de componentes SMD y promoviendo el uso de soluciones electrónicas.
<!--Descripción breve del proyecto. Explica qué problema se aborda, el objetivo principal y el enfoque general del proyecto.-->

**Contexto del proyecto:** *`Académico / Prototipo`*
<!--- Académico
- Personal
- Industrial
- Simulación / Prototipo-->

**Impacto del proyecto:** *`Automatización`*

<!--
- Mejora en procesos
- Apoyo a la toma de decisiones
- Optimización del mantenimiento
- Reducción de tareas manuales-->

## Tecnologías utilizadas / Technologies

**Lenguajes de Programación:** *`Python`*
<!--
- Python
- VBA
- SQL -->

**Software:** *`Solid Works`*
<!--
- AutoCAD
- SolidWorks
- Excel
- AppSheet -->

**Hardware:** *`Arduino`*, *`Motores paso a paso`*
<!--
- Arduino
- Sensores
- PLC (si aplica) -->

<!--
** Metodologías:**
- Gestión de mantenimiento
- Mantenimiento preventivo y correctivo
- Mejora continua -->

## Funciones principales / Features

- Programa para interpretar el código `Gerber` y generar un `G code` (código G).
- Programa para reconocer puntos de dispensación y generar un `reporte de la presición del trabajo de la máquina`.
- `Sistema de acoples magnéticos` que permite cambiar herramientas y fijar la pieza a la cama de la máquina de forma sencilla.
- Estructura de la máquina diseñada para ser fabricada fácilmente mediante `máquinas CNC`, construida en `MDF` (Trupan).

<!--
Para software → Funciones principales
Para mecánica/mantenimiento → Alcances del proyecto o Características principales
-->

## Implementación / Running the project

1. Se necesita un archivo Gerber con el diseño de la PCB, donde es importante solo importar la capa `F_paste`.
2. Cargar y configurar el programa para generar el `código G`.
3. Posicionar correctamente la PCB dentro de la máquina.
4. Ejecutar y esperar a que termine el proceso de dispensación.
5. `Opcional` Tomar fotos y resaltar los bordes de las pistas y los puntos.
6. `Opcional` Subir las imágenes y ejecutar el programa para evaluar la calidad de dispensación.

<!--
En software → pasos técnicos
En proyectos mecánicos/mantenimiento → pasos de implementación, pruebas o puesta en marcha
-->

---

## Aprendizajes / What I Learned
- Flujo del proceso para `manufactura de PCB` y `ensamblaje de componentes electrónicos`.
- Estructura del código Gerber.
- Estructura del código G.
- Desarrollo de aplicación en Python con `PyQT5`.
- Validación del trabajo de dispensación.
- Estrategia de micro dispensación para un `fluido no-newtoniano`.
- Diseño y construcción de una máquina CNC.
<!--
- Aprendizaje técnico
- Aprendizaje de ingeniería o mantenimiento
- Uso de herramientas o metodologías -->

## Posibles mejoras / How can it be improved?

- Estandarizar y optimizar el proceso de exportación de archivos Gerber.
- Mejorar la interfaz de programación de la dispensación, incorporando un modo simple e intuitivo y un modo avanzado para usuarios experimentados.
- Optimizar el diseño de la estructura para reducir la cantidad de piezas, simplificar su fabricación y disminuir el uso de acoples con tornillos.
- Mejorar y optimizar el sistema de carga de la pasta de soldadura.
- Realizar pruebas para identificar y ajustar parámetros como temperatura ambiente, temperatura de la pasta, velocidad de dispensación y velocidad de retracción, adaptando el funcionamiento de la máquina según su entorno operativo.
- Desarrollar un sistema de visión artificial que reconozca los puntos de dispensación y las pistas SMT de la PCB, facilitando la validación de la calidad de la dispensación.

## Video de Demostración
https://github.com/DDn-1/Dispensador-de-pasta-para-soldar/blob/main/Demostraci%C3%B3n%20-%202.mp4

