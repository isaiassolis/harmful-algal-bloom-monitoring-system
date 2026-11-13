# Proyecto Marea Roja — Ingeniería, instrumentación e inteligencia artificial

## El proyecto

Participé como **ingeniero de hardware y software y líder técnico** en el desarrollo de un sistema para estudiar y monitorear **floraciones algales nocivas**.

La investigación comenzó en **2011** con el proyecto *«Prototipo innovador para el pronóstico de fitoplancton potencialmente nocivo basado en herramientas bayesianas y biomarcadores lipídicos»*. En el trabajo multidisciplinario participaron organizaciones como **Comercializadora de Soluciones Móviles, S. A. de C. V.**, la **Universidad Autónoma de Campeche** y la **Universidad Riviera**.

Durante tres años avanzamos desde la automatización de un laboratorio hasta la construcción de un equipo autónomo y una plataforma web de monitoreo.

## Primer año — Desarrollo de laboratorio

### Diseño mecánico y automatización

Diseñé en **CAD** un robot cartesiano pequeño basado en **coordenadas euclidianas**, destinado al movimiento automático durante la captura de muestras con un microscopio.

Utilicé **Arduino** para controlar el desplazamiento del sistema y trabajé en su integración con el software de captura.

### Visión computacional

Desarrollé el procesamiento de imágenes utilizando **OpenCV** para la **clasificación de dinoflagelados** observados mediante microscopía.

### Adquisición de datos e instrumentación

Integré una **sonda multiparamétrica de 16 parámetros de calidad del agua**, utilizando **comunicación TTL** con el software.

También integré un **espectrofotómetro**, junto con el microscopio y el resto de la instrumentación del sistema de laboratorio.

### Modelado probabilístico

Diseñé el **modelo bayesiano**: seleccioné variables, preparé y limpié información histórica e integré datos del trabajo de laboratorio en sitio.

Programé la red bayesiana mediante **ProBT de ProBayes**, vinculándola al sistema de análisis.

## Segundo año — Equipo autónomo

En esta etapa construimos el equipo físico e integramos una **microcomputadora con el software automatizado**, además del microscopio, sistema cartesiano, espectrofotómetro, sonda multiparamétrica y componentes de análisis.

Llevamos a cabo **pruebas en sitio** para evaluar el funcionamiento integrado del equipo.

## Tercer año — Monitoreo web y comunicación remota

Desarrollamos una **plataforma web de monitoreo**, utilizando tecnologías como **ASP.NET**, e integramos la comunicación del dispositivo con tierra.

El sistema utilizaba **GPS para asociar las mediciones con una ubicación** y **GPRS para transmitir la información** a la plataforma.

## Tecnologías utilizadas

| Área | Herramientas |
| --- | --- |
| Diseño | CAD y robot cartesiano |
| Automatización | Arduino |
| Programación | C++ y C# |
| Imágenes | OpenCV y microscopía |
| Instrumentación | Sonda multiparamétrica, TTL y espectrofotómetro |
| Inferencia | Redes bayesianas y ProBT (ProBayes) |
| Web | ASP.NET |
| Equipamiento | Microcomputadora integrada |
| Comunicación | GPS y GPRS |

## Mi responsabilidad

Participé directamente en el diseño del robot, la programación del movimiento, el procesamiento de imágenes, la comunicación con instrumentos científicos, la limpieza de datos históricos y el diseño y programación del modelo bayesiano.

También trabajé en la integración física y de software del equipo y en su evolución hacia el monitoreo web y remoto, ejerciendo funciones de **liderazgo técnico**.

Este desarrollo estuvo relacionado con mis **estudios de Maestría en Ingeniería Mecatrónica**.

## Resultado

El producto fue **construido, probado en campo y comercializado a una empresa privada**.

Posteriormente el cliente dejó de utilizarlo debido a una decisión económica sobre el costo de prevención en su operación. Esa decisión formó parte de las circunstancias comerciales del proyecto, sin invalidar el desarrollo tecnológico alcanzado.

## Propiedad técnica

Los algoritmos, archivos de diseño, planos, circuitos y código originales pertenecen a sus titulares y no se distribuyen en este repositorio.

[← Volver al proyecto](../README.md)
