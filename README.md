# 😴 NightGuard: Sistema Wearable para la Detección de Microsueño en Conductores

## 📖 Descripción General

NightGuard es un sistema wearable inteligente diseñado para detectar de forma temprana episodios de fatiga y microsueño en conductores mediante visión artificial e inteligencia artificial embebida.

El proyecto surge como respuesta a una problemática real relacionada con la seguridad vial. La fatiga al conducir es uno de los factores que contribuyen a accidentes de tránsito en todo el mundo, especialmente durante recorridos prolongados o jornadas de trabajo extensas.

Para abordar esta problemática, se desarrolló un prototipo funcional capaz de monitorear en tiempo real el estado visual del conductor, identificando si sus ojos se encuentran abiertos o cerrados. Cuando el sistema detecta un posible episodio de microsueño, genera una alerta auditiva inmediata para recuperar la atención del usuario.

NightGuard fue concebido como un dispositivo portátil y autónomo, integrando hardware embebido, inteligencia artificial y diseño wearable dentro de una única solución.

---

# 🎯 Problema

Los episodios de microsueño representan un riesgo significativo para la seguridad vial. Estos eventos pueden durar apenas unos segundos, pero son suficientes para provocar la pérdida del control de un vehículo y generar accidentes graves.

Muchas soluciones comerciales presentan limitaciones relacionadas con costos elevados, dependencia de infraestructura externa o requerimientos complejos de instalación.

NightGuard propone una alternativa basada en hardware de bajo costo e inteligencia artificial ejecutada directamente sobre dispositivos embebidos, permitiendo la detección local y en tiempo real sin necesidad de conexión a internet.

---

# 🎯 Objetivo General

Diseñar e implementar un sistema wearable capaz de detectar estados de somnolencia en conductores mediante inteligencia artificial embebida y emitir alertas preventivas en tiempo real.

---

# 🏗️ Arquitectura del Sistema

El sistema está compuesto por tres elementos principales:

### Captura de Imágenes

Una cámara integrada en el dispositivo permite obtener imágenes del rostro del usuario durante la conducción.

### Procesamiento Inteligente

Un modelo de inteligencia artificial entrenado específicamente para identificar estados de ojo abierto y ojo cerrado analiza las imágenes capturadas y realiza inferencias en tiempo real.

### Sistema de Alerta

Cuando el modelo detecta un posible episodio de microsueño, se activa una alerta sonora diseñada para recuperar la atención del conductor.

---

# 🤖 Inteligencia Artificial y Entrenamiento del Modelo

Uno de los componentes más importantes del proyecto fue el desarrollo y entrenamiento del modelo de inteligencia artificial encargado de clasificar el estado visual del usuario.

Para ello se implementó un proceso de aprendizaje supervisado basado en imágenes capturadas específicamente para el proyecto.

El flujo de desarrollo incluyó:

* Recolección de imágenes.
* Clasificación manual de datos.
* Creación del conjunto de entrenamiento.
* Entrenamiento supervisado.
* Validación del modelo.
* Optimización para dispositivos embebidos.
* Implementación en hardware.

El entrenamiento fue realizado utilizando la plataforma Edge Impulse, permitiendo desarrollar un modelo optimizado para ejecutarse directamente sobre microcontroladores con recursos limitados.

Las evidencias del proceso de entrenamiento, validación y despliegue del modelo pueden observarse dentro de este repositorio mediante capturas y documentación del proyecto.

---

# 🔧 Desarrollo del Hardware

El prototipo fue desarrollado desde cero utilizando una arquitectura basada en sistemas embebidos de bajo consumo.

Durante el proceso se integraron distintos componentes electrónicos para permitir:

* Captura de imágenes.
* Procesamiento local.
* Generación de alertas.
* Alimentación autónoma mediante batería recargable.

El sistema fue diseñado para operar de forma inalámbrica y portátil, permitiendo su integración dentro de una estructura wearable.

---

# 👓 Diseño Wearable

Como parte del desarrollo se implementó una estructura física basada en gafas inteligentes.

El objetivo fue integrar todos los componentes electrónicos dentro de un formato ergonómico y funcional, manteniendo un equilibrio entre:

* Comodidad.
* Portabilidad.
* Estética.
* Viabilidad técnica.

La estructura fue fabricada mediante impresión 3D y adaptada para alojar los componentes electrónicos necesarios para el funcionamiento del sistema.

---

# 🧪 Desarrollo y Validación

El proyecto fue desarrollado siguiendo un proceso iterativo de diseño, integración y pruebas.

Las etapas principales incluyeron:

### Investigación del Problema

Análisis de los riesgos asociados a la fatiga y microsueño en conductores.

### Diseño de la Solución

Definición de la arquitectura de hardware y software.

### Entrenamiento del Modelo

Desarrollo del modelo de inteligencia artificial para clasificación visual.

### Integración del Sistema

Implementación del modelo sobre hardware embebido.

### Construcción del Prototipo

Montaje físico del dispositivo wearable.

### Pruebas de Funcionamiento

Validación de la detección de estados visuales bajo condiciones controladas.

---

# 📈 Resultados

El prototipo desarrollado logró identificar estados de ojo abierto y ojo cerrado mediante inteligencia artificial ejecutada localmente sobre hardware embebido.

Durante las pruebas realizadas, el sistema fue capaz de generar alertas auditivas cuando se detectaban condiciones asociadas a posibles episodios de microsueño, demostrando la viabilidad técnica de implementar soluciones de detección temprana utilizando tecnologías de bajo costo.

Asimismo, el proyecto permitió validar la integración exitosa entre visión artificial, inteligencia artificial embebida y diseño wearable dentro de una única plataforma funcional.

---

# 🚀 Tecnologías Utilizadas

* ESP32-CAM
* Edge Impulse
* TinyML
* Inteligencia Artificial
* Visión por Computador
* Machine Learning
* Sistemas Embebidos
* Electrónica Digital
* Impresión 3D
* Wearable Technology

---

# 📚 Competencias Aplicadas

* Desarrollo de Sistemas Embebidos
* Inteligencia Artificial Aplicada
* TinyML
* Computer Vision
* Integración Hardware-Software
* Diseño de Prototipos
* Electrónica
* Prototipado Rápido
* Desarrollo de Productos Tecnológicos
* Resolución de Problemas Reales

---

# 💡 Impacto del Proyecto

NightGuard demuestra cómo la combinación de inteligencia artificial embebida, visión por computador y sistemas portátiles puede utilizarse para desarrollar soluciones innovadoras orientadas a la seguridad vial.

El proyecto valida la posibilidad de implementar sistemas inteligentes de monitoreo en tiempo real utilizando hardware de bajo costo, abriendo oportunidades para futuras aplicaciones en el área de movilidad, salud y tecnologías wearables.

---

# 👨‍💻 Autor

**José Miguel Rico Acosta**

Estudiante de Ingeniería de Sistemas Cibernéticos.

Interesado en Inteligencia Artificial, Sistemas Embebidos, Internet de las Cosas (IoT), Analítica de Datos y Desarrollo de Soluciones Tecnológicas Innovadoras.
