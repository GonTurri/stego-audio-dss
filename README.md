# Esteganografía en Audio mediante Espectro Ensanchado (DSSS)

Trabajo Práctico para la materia **Procesamiento de Señales e Imágenes** (UTN).

Este proyecto implementa y demuestra un sistema de modulación y demodulación esteganográfica en señales de audio digital utilizando **Direct-Sequence Spread Spectrum (DSSS)**. El sistema permite ocultar información binaria por debajo del umbral de audibilidad y extraerla sin conocer la señal portadora original mediante **correlación cruzada**[cite: 1, 3].

---

## Estructura del Repositorio

* `stego_demo.ipynb`: Notebook principal con la simulación, gráficos y reproducción[cite: 4].
* `audio_portador.wav`: Señal de audio original en formato PCM (debe ubicarse en la raíz).
* `requirements.txt`: Dependencias de Python necesarias para el entorno.
* `.gitignore`: Archivos y carpetas excluidos del control de versiones.

---

## Requisitos Previos

* Python 3.9 o superior.
* Terminal de comandos (probado en macOS y Linux).

---

## Instalación y Configuración del Entorno

1. **Clonar el repositorio y situarse en la carpeta:**
   ```bash
   cd ruta/al/repositorio