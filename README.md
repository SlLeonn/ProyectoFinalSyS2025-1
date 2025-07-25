# 📡 Proyecto Final – Señales y Sistemas 2025

### _De Fourier al WiFi/5G: Anatomía de una Señal Inalámbrica_

## 🎓 Universidad Nacional de Colombia – Sede Manizales
**Curso:** Señales y Sistemas  
**Profesor:** Dr. Andrés Marino Álvarez Meza  
**Integrantes:**  
- Javier Estiven Leon Calderon
- Valeria Lopez Marin
- Evelin Giraldo Obando

---

## 📘 Descripción del Proyecto

Este proyecto implementa un sistema interactivo completo de comunicaciones digitales basado en modulación QAM, utilizando Streamlit como interfaz. El objetivo es ilustrar visualmente conceptos fundamentales de Señales y Sistemas aplicados a tecnologías modernas como WiFi y 5G.

El sistema permite:
- Seleccionar una señal de entrada (sintética o audio real desde YouTube).
- Visualizar la señal en el dominio del tiempo y su contenido espectral.
- Aplicar filtrado paso-bajo y obtener la señal analítica (Hilbert).
- Separar las componentes I/Q.
- Modular con QAM, transmitir por un canal ruidoso (AWGN), y demodular.
- Visualizar constelaciones transmitidas y recibidas.

---

## 🧰 Tecnologías y Librerías

- `Python 3`
- `Streamlit`
- `NumPy`, `SciPy`, `Matplotlib`
- `yt-dlp` para descarga de audio
- `soundfile`, `ffmpeg` para procesamiento

---

## ▶️ Cómo ejecutar

1. Clona este repositorio:

    git clone https://github.com/tu_usuario/proyecto_final_sys.git  
    cd proyecto_final_sys

2. Instala las dependencias:

    pip install -r requirements.txt

3. Ejecuta el dashboard:

    streamlit run 📝_Proy_Fin.py

⚠️ Asegúrate de tener `ffmpeg` y `yt-dlp` correctamente instalados en tu sistema para poder procesar audio desde YouTube.

---

## 📁 Estructura del proyecto

.
├── pages/
│   ├── 📻_Concepto_Teorico.py         # Módulo de teoría (Fourier, QAM, etc.)
│   ├── 🎵_Entrada_Senal.py            # Simulación de señales y filtrado
│   ├── 🔁_Senales_IQ.py               # Transformada de Hilbert y señales I/Q
│   └── 🧩_Sistema_Completo.py         # Simulación completa QAM + Canal + Demodulación
├── 📝_Proy_Fin.py                      # Archivo principal del dashboard
├── requirements.txt                   # Dependencias del proyecto
└── README.md                          # Este archivo

---

## 📡 Aplicaciones en WiFi/5G

El sistema implementado representa una versión simplificada de las cadenas de comunicación digital utilizadas en tecnologías como WiFi y 5G. A través de la modulación QAM, separación I/Q, transmisión por canal ruidoso (AWGN) y demodulación coherente, se simula cómo se procesan y transmiten datos en estos estándares modernos. El proyecto incluye una animación y un diagrama de bloques explicativo para complementar esta sección.

---

## ✅ Estado del Proyecto

- ✔️ Sistema completo y funcional  
- ✔️ Visualizaciones interactivas y en tiempo real  
- ✔️ Probado en Google Colab con Streamlit  
- ✔️ Parámetros ajustables vía sliders

---

## 📜 Licencia

Este proyecto ha sido desarrollado con fines académicos en el marco del curso de Señales y Sistemas. Todos los derechos reservados a los autores.
