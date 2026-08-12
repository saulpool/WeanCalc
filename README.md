# Weaning Ventilatorio & Mecánica Pulmonar - PWA SPA (PB-840 Retro)

Aplicación Web Progresiva (PWA) diseñada para intensivistas y personal de Terapia Intensiva para la captura, monitoreo en tiempo real y cálculo automático de variables de mecánica pulmonar y escalas clínicas durante la Prueba de Ventilación Espontánea (SBT).

## Características Clínicas y Técnicas

- **Estética Puritan-Bennett 840**: Interfaz oscura de alto contraste con paleta retro PB-840.
- **Offline-First (PWA)**: Funciona sin conexión a internet directamente en tabletas o smartphones.
- **Paso 1 (Demográficos)**: Generación automática de Folio `000[E/Q][M/Z/U]`, cálculo de IMC, PBW y gestión por Subgrupo (`0/ZEEP`, `PSV+`, `Card`).
- **Paso 2 (Pre-SBT & Escalas)**: Cálculo e interconexión dinámica de 6 escalas clínicas (`FOUR`, `GCS`, `MRC`, `SOFA-2`, `ExPreS`, `Visage`).
- **Paso 3 (Trans-SBT Live Panel)**:
  - Cronómetro ascendente (00:00 a 30:00) con virado visual de color.
  - Intervalos muestrales configurables (3, 4 o 5 minutos).
  - Arrastre automático progresivo de datos (**Forward-Carrying Values**).
  - Componente de captura **Master Thumb Scroller** para facilitar el ajuste con el pulgar.
- **Exportación CSV**: Salida idéntica al esquema estricto de 19 columnas de `BD Weaning.csv`.

## Instalación en Dispositivos Móviles

1. Abre el enlace de la app en Safari (iOS) o Chrome (Android).
2. Toca el botón de compartir / menú de opciones del navegador.
3. Selecciona **"Agregar a la pantalla de inicio"**.

## Despliegue en GitHub Pages

1. Sube los archivos (`index.html`, `manifest.json`, `sw.js`, `README.md`) a tu repositorio de GitHub.
2. Ve a **Settings -> Pages**.
3. En **Branch**, selecciona `main` o `master` y guarda.
4. Tu enlace PWA HTTPS estará listo en un par de minutos.
