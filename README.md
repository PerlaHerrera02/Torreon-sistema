# 🥩 Sistema de Gestión y Análisis Predictivo - Carnicería El Torreón

Este proyecto consiste en el desarrollo de un sistema web de gestión e informes predictivos para la carnicería **El Torreón**, con el objetivo de digitalizar procesos clave como el control de inventario, registro de ventas, asistencia del personal y análisis de datos históricos.

## 🌐 Descripción general

La solución incluye:
- Una página web funcional en HTML con formularios interactivos.
- Un análisis predictivo desarrollado en Google Colab basado en datos simulados.
- Despliegue en la nube utilizando **Google Cloud Platform (GCP)** y servidor web **NGINX**.

## 🛠️ Tecnologías utilizadas

- **Frontend:** HTML, CSS, JavaScript (básico)
- **Infraestructura:** Google Cloud Platform (Compute Engine - Ubuntu)
- **Servidor:** NGINX
- **Análisis de datos:** Python, pandas, matplotlib, seaborn (Google Colab)
- **Control de versiones:** GitHub

## 📁 Archivos principales

- `index.html`: Interfaz web del sistema (ventas, inventario, asistencia).
- `deploy.sh`: Script Bash que automatiza la instalación del servidor y despliegue de la página en GCP.
- `torreon_predictivo.ipynb`: Notebook de Google Colab con análisis antes y después de implementar el sistema.

## 🚀 Instrucciones de despliegue

1. Crear una instancia en GCP con Ubuntu 20.04 LTS.
2. Conectarse por SSH y subir los archivos `index.html` y `deploy.sh`.
3. Ejecutar el script:
   ```bash
   chmod +x deploy.sh
   ./deploy.sh

 Integrantes del equipo:
Perla Herrera.
Myriam Serrano.
Sergio Pérez.
Hiram Rodríguez.

Proyecto académico desarrollado con fines educativos. Profesor Sebastián González Zepeda.
