# Dashboard Interactivo: Seguimiento a Pacientes de Cáncer de Mama Triple Negativo (CMTN)

[![R](https://img.shields.io/badge/Code-R-276DC3?style=for-the-badge&logo=r)](https://www.r-project.org/) [![Quarto](https://img.shields.io/badge/Dashboard-Quarto-blue?style=for-the-badge&logo=quarto)](https://quarto.org/) [![DT](https://img.shields.io/badge/Tables-DT-1E90FF?style=for-the-badge)]()

> **Ver el dashboard interactivo final publicado:** [**Ver Dashboard**](https://94810.quarto.pub/dashboard-censo-yo-soy-triple/)

Este repositorio contiene el código fuente para un dashboard interactivo que visualiza los resultados de un seguimiento a pacientes de Cáncer de Mama Triple Negativo en Chile realizado por el Observatorio del Cáncer. El objetivo fue transformar un informe estático en PDF en una herramienta dinámica para la exploración de datos.

---

### 🎯 Principales Hallazgos Visualizados

*   **La Carga de Síntomas:** Se destaca la alta prevalencia de efectos secundarios (como cambios cognitivos y dolor) que persisten incluso después de finalizar el tratamiento activo.
*   **Barreras de Acceso:** El dashboard visualiza la brecha significativa en el acceso a terapias innovadoras, donde solo un 15.2% de las pacientes reporta recibir inmunoterapia.
*   **La Brecha Psicosocial:** Se resalta que un preocupante 40.9% de las pacientes no recibe apoyo psicológico, y de las que sí lo reciben, menos de la mitad lo considera "muy efectivo".

---

### 📊 Visualización Destacada

**Recomendaciones de las Pacientes para Mejorar Tratamientos**
*Este gráfico de barras horizontales muestra las áreas de mejora más mencionadas por las propias pacientes, destacando el acceso a terapias y la información como las principales prioridades.*

![Gráfico de Recomendaciones](figure-html/unnamed-chunk-14-1.png)

---

### 🛠️ Herramientas Utilizadas

*   **Lenguaje:** R
*   **Paquetes Principales:** `tidyverse` (para `dplyr` y `ggplot2`), `readxl`, `DT` (para tablas interactivas).
*   **Documentación Reproducible:** Quarto Dashboards.

---

### 🚀 Cómo Ejecutar este Análisis

1.  Clonar el repositorio principal del portfolio. Este proyecto se encuentra en la carpeta `observatorio-del-cancer/cancer-de-mama-triple-negativo-CMTN`.
2.  Abrir el archivo `dashboard.qmd` en RStudio.
3.  Colocar el archivo de datos (`CMTN.xlsx`) en la misma carpeta. (El archivo de datos no se incluye en este repositorio).
4.  Instalar las librerías de R necesarias (`tidyverse`, `readxl`, `DT`, `fontawesome`).
5.  Renderizar el archivo `dashboard.qmd`.