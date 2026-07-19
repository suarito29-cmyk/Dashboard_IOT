# 🌍 Dashboard IoT - Plataforma de Gestión Ambiental

Este repositorio contiene la estructura visual de la **Plataforma de Gestión y Monitoreo Ambiental OpenAQ**. Fue desarrollado utilizando exclusivamente **HTML5 y CSS3** basándose en un diseño de referencia.

## 📁 Estructura del Proyecto

El proyecto está organizado de la siguiente manera para separar la lógica de marcado del diseño:

- `index.html`: Archivo principal con la estructura semántica y la división de áreas (Grid/Flexbox).
- `README.md`: Documentación del proyecto.
- `stylesheet/`: Carpeta que contiene los estilos.
  - `styles.css`: Hoja de estilos vinculada de forma dinámica al HTML.

## 🚀 Características

- **Diseño Responsivo adaptado a Dashboard:** Layout de tres columnas que incluye un menú lateral, un área central de visualización de datos (KPIs, Mapa y Tablas) y un panel derecho de detalles.
- **Iconografía:** Uso de la librería de FontAwesome.
- **Simulación de Componentes IoT:** Interfaz preparada para mostrar telemetría de sensores DHT22 en placas ESP32 (Wokwi).

## 🛠️ Tecnologías Utilizadas

* HTML5
* CSS3 (Flexbox & CSS Grid)

## 🌐 Despliegue en GitHub Pages

Este proyecto se encuentra desplegado en GitHub Pages. Al realizar cualquier actualización en la carpeta `stylesheet/styles.css`, los cambios se verán reflejados de manera automática en la web gracias a la etiqueta de vinculación `<link>`.

Para ver la pagina entrar a: https://suarito29-cmyk.github.io/Dashboard_IOT/
