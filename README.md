# Simulador Movimiento Parabólico

Un simulador educativo interactivo desarrollado en Unity que permite visualizar y analizar el movimiento parabólico. Este proyecto incluye la posibilidad de ajustar parámetros clave como la velocidad inicial, el ángulo de lanzamiento y la altura inicial. Los datos de la simulación pueden exportarse a un archivo CSV para su posterior análisis.


## Características

- **Ajuste interactivo de parámetros**:
  - Velocidad inicial.
  - Ángulo de lanzamiento.
  - Altura inicial.
- **Simulación visual**:
  - Movimiento parabólico en tiempo real.
  - Cámara dinámica que sigue el proyectil.
- **Generación de datos**:
  - Exporta datos del movimiento (velocidad, distancia, aceleración) a un archivo CSV.
- **Educativo**:
  - Ideal para enseñar y aprender los fundamentos del movimiento parabólico en física.

---

## Requisitos del Sistema

- Unity 2021 o superior.
- Sistema operativo: Windows, macOS o Linux.

---

## Instrucciones de Uso

### 1. Ejecutar el Simulador
1. Abre el proyecto en Unity.
2. Ejecuta la escena principal (`MainScene`).
3. Ajusta los parámetros del movimiento usando la interfaz interactiva.
4. Presiona el botón **Disparar** para iniciar la simulación.

### 2. Exportar Datos
- Los datos del movimiento se exportan automáticamente al archivo `DatosSimulacion.csv` en la carpeta raíz del proyecto (`Assets/`).

---

## Estructura del Proyecto

```plaintext
SimuladorMovimientoParabolico/
│
├── Assets/
│   ├── Scripts/           # Scripts C# del simulador
│   ├── Prefabs/           # Prefabs del cañón y proyectil
│   ├── DatosSimulacion.csv # Archivo CSV con los datos de la simulación
│   └── Scenes   # Escenas de ejecucion del Unity
│
├── README.md              # Documentación del proyecto


## Python

El proyecto tiene un archivo python de ejemplo para correl el archivo csv para realizar graficas de la simulación
