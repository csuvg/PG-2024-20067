# Desarrollo de Modelado 3D y Algoritmo de Pathfinding en Aplicación de Recorridos Virtuales con Unity

## Descripción
Este proyecto implementa un sistema de recorridos virtuales para el Centro de Innovación y Tecnología (CIT) de la Universidad del Valle de Guatemala, utilizando tecnologías de modelado 3D y realidad aumentada. El sistema incorpora modelos tridimensionales detallados de los diferentes niveles del CIT junto con un algoritmo de pathfinding para guiar a los usuarios a través del edificio.

La aplicación permite a los visitantes navegar de manera intuitiva por las instalaciones del CIT mediante una experiencia inmersiva que combina el mundo real con elementos virtuales. El sistema incluye características como:
- Modelado 3D preciso de las instalaciones
- Sistema de navegación con pathfinding
- Interfaz de usuario intuitiva
- Integración de realidad aumentada

## Requisitos del Sistema

### Software Necesario
- Unity Editor versión `2022.3.18f1`
- Para dispositivos Android: AR Core instalado

### Paquetes Requeridos

Es importante mencionar que para el correcto funcionamiento del proyecto se requiere la instalación completa de todos los paquetes listados, incluso si algunos no son utilizados directamente en cada escena. Por ejemplo, los componentes de XR y AR, aunque no son esenciales para este módulo específico, son fundamentales para la integración completa con otros módulos del tour virtual de la universidad.

- 2D Animation `9.0.4`
- 2D Common `8.0.2`
- 2D Pixel Perfect `5.0.3`
- 2D Sprite `1.0.0`
- 2D Tilemap Editor `1.0.0`
- AI Navigation `1.1.5`
- Apple ARKit XR Plugin `5.1.5`
- AR Foundation `5.1.5`
- Burst `1.8.12`
- Cinemachine `2.9.7`
- Collections `1.2.4`
- Custom NUnit `1.0.6`
- Editor Coroutines `1.0.0`
- Google ARCore XR Plugin `5.1.5`
- Input System `1.7.0`
- Magic Leap XR Plugin `7.0.0`
- Mathematics `1.2.6`
- Newtonsoft Json `3.2.1`
- OpenXR Plugin `1.9.1`
- Test Framework `1.1.33`
- TextMeshPro `3.0.9`
- Unity UI `1.0.0`
- Version Control `2.4.3`
- Visual Studio Editor `2.0.22`
- XR Core Utilities `2.2.3`
- XR Interaction Subsystems `2.0.0`
- XR Plugin Management `4.5.0`

## Instalación y Configuración

### 1. Configuración del Entorno de Desarrollo
1. Instalar Unity Hub
2. Instalar Unity Editor versión `2022.3.18f1`
3. Clonar este repositorio
4. Abrir el proyecto desde Unity Hub

### 2. Compilación del Proyecto
1. Abrir el proyecto en Unity
2. Navegar a `File > Build Settings`
3. Seleccionar la plataforma objetivo
4. Hacer clic en "Switch Platform" si es necesario
5. Seleccionar "Build" o "Build and Run"
6. Elegir el directorio de destino para la compilación

## Pruebas y Limitaciones Conocidas
- La aplicación puede presentar problemas de registro (alineación entre objetos virtuales y reales)
- Se recomienda realizar pruebas en diferentes condiciones de iluminación
- La precisión del tracking puede variar según el dispositivo utilizado

## Resultados y Feedback
Las pruebas con usuarios han demostrado que:
- La aplicación es intuitiva y fácil de usar
- Representa una innovación significativa para la institución
- Proporciona una experiencia de usuario satisfactoria
- Existe margen de mejora en la precisión del registro AR

## Estado del Proyecto
Esta versión representa una implementación preliminar funcional del sistema de recorridos virtuales. Aunque existen áreas de mejora, especialmente en la precisión del registro AR, la aplicación proporciona una base sólida para futuras iteraciones y mejoras.

## Contribuciones y Desarrollo Futuro
Se planea la siguiente mejora principal:
- Implementación de sensores UWB (Ultra-Wideband) para mejorar la precisión del posicionamiento y navegación, reemplazando el sistema actual basado en modelos 3D

## Demostración

El siguiente video muestra una demostración completa del funcionamiento de la aplicación, incluyendo la navegación en tiempo real, la interacción con el sistema de pathfinding y la visualización de los modelos 3D en el entorno del CIT.

[Ver video de demostración](demo/Demo.mp4)

## Trabajo Escrito

Para más detalles sobre la implementación, metodología y resultados del proyecto, consulte el [informe completo](docs/Informe.pdf).
