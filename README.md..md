# 🐟 Análisis Cuantitativo: Optimización de la Trucha Arcoíris (2013 vs. 2024)

Este proyecto es una infografía interactiva y un dashboard analítico diseñado para visualizar la evolución tecnológica y productiva en la salmonicultura (específicamente la trucha arcoíris, *Oncorhynchus mykiss*) durante la última década.

El diseño sigue una metodología académica estricta, basada en el framework de investigación cuantitativa del IDC, combinando metadatos, iconografía vectorial semántica y visualizaciones de datos comparativas.

---

## 🎯 Objetivo del Proyecto

Comunicar de manera clara, visual y sintética el "Salto Tecnológico" ocurrido entre 2013 y 2024, evidenciando mejoras críticas en ocho áreas clave de la acuicultura:
1. Supervivencia en Incubación
2. Eficiencia Alimentaria (FCR)
3. Densidad de Cultivo
4. Potencial de Carga Máxima (RAS)
5. Supervivencia en Engorde
6. Productividad Hídrica
7. Toxicidad de Amoníaco
8. Saturación de Oxígeno

---

## 🛠️ Tecnologías Utilizadas

Este proyecto fue desarrollado bajo la premisa de **Cero Dependencias (Zero-Dependency)** para garantizar máxima velocidad de carga, accesibilidad y facilidad de mantenimiento.

* **HTML5 Semántico:** Estructura basada en etiquetas como `<article>`, `<header>`, `<main>` y `<footer>` para mejorar la accesibilidad y el SEO.
* **CSS3 (Vanilla CSS):** * **CSS Grid & Flexbox:** Para un diseño estrictamente responsivo (Mobile First).
    * **Efectos UI Avanzados:** Implementación de *Glassmorphism* (desenfoque de fondo), sombras interiores interactivas y transformaciones espaciales en hover.
* **SVG Nativo (Scalable Vector Graphics):**
    * **Íconos Semánticos:** 8 íconos personalizados integrados directamente en el código para representar cada métrica.
    * **Gráficos de Datos (Data-Viz):** Gráficos de barras, líneas, dispersión (scatter), áreas e histogramas codificados a mano en SVG, eliminando la necesidad de librerías pesadas como Chart.js o D3.js.
* **JavaScript (ES6):** Script ultraligero para orquestar la animación de entrada en cascada de las tarjetas al cargar la página.
* **Tipografía:** [Inter](https://fonts.google.com/specimen/Inter) (textos generales) e [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) (datos y etiquetas) cargadas vía Google Fonts.

---

## 📂 Estructura del Proyecto

Para mantener el proyecto organizado, se recomienda la siguiente estructura de carpetas (aunque actualmente todo funciona desde un único archivo para facilitar la portabilidad):

```text
proyecto-acuicultura/
│
├── index.html          # Archivo principal (Contiene HTML, CSS, JS y SVGs)
├── README.md           # Documentación del proyecto (este archivo)
│
└── /data               # (Opcional) Para futuras integraciones de datos dinámicos
    └── stats2024.json