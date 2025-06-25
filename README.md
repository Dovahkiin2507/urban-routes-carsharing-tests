# Urban Routes - Pruebas QA de la Funcionalidad de Compartir un Automóvil

Este proyecto tiene como objetivo evaluar la estabilidad, usabilidad y funcionamiento de la funcionalidad **"compartir un automóvil"** dentro de la aplicación Urban Routes. Se diseñaron y ejecutaron pruebas detalladas tanto de la interfaz como de la lógica funcional de la aplicación, utilizando dos entornos de prueba diferentes.

## 🔍 Objetivo del Proyecto

- Validar el comportamiento visual y funcional del formulario de reserva de automóviles.
- Diseñar casos de prueba efectivos para el botón "Reservar", el flujo de alquiler y los métodos de pago.
- Detectar y documentar errores visuales y funcionales en dos navegadores con distintas resoluciones.

## 🛠️ Herramientas Utilizadas

- Google Sheets (documentación de listas de verificación y casos de prueba)
- Google Chrome (800x600)
- Mozilla Firefox (1920x1080)
- Jira (registro y documentación de errores)
- Urban Routes test environment

## 📋 Actividades Realizadas

1. **Lista de comprobación del diseño**  
   Se analizó el diseño del formulario en modalidad "Lujo", comprobando disposición, ortografía y comportamiento visual en distintos entornos.

2. **Lista de comprobación de funcionalidad (Método de pago / Agregar tarjeta)**  
   Se evaluaron escenarios positivos y negativos utilizando clases de equivalencia y valores límite.

3. **Casos de prueba para el botón "Reservar"**  
   Se validó el comportamiento del botón según diferentes combinaciones posibles, excepto cálculo de duración y distancia, que no estaban dentro del alcance.

4. **Casos de prueba para el flujo de alquiler**  
   Se diseñaron pruebas para validar distintas rutas y comportamientos dentro del proceso de alquiler.

5. **Ejecución de pruebas y reporte de errores**  
   Se ejecutaron todas las pruebas previstas y se documentaron errores detectados en Jira, incluyendo su severidad y descripción detallada.

## 🧪 Resultados

- Se completaron todas las pruebas previstas.
- Se detectaron errores importantes tanto visuales como funcionales, por ejemplo:
  - [UR-1: No aparecen íconos de vehículos en el mapa](https://luisarturomedina84.atlassian.net/browse/UR-1)
  - [UR-31: No es posible cancelar un viaje una vez reservado](https://luisarturomedina84.atlassian.net/browse/UR-31)
- El entorno presentó inconsistencias de diseño y navegación en navegadores distintos.

## 👤 Impresiones como Usuario

Mi impresión general es que la aplicación **puede llegar a ser útil situacionalmente**, pero aún tiene demasiadas áreas que mejorar para cumplir con su propósito. En su estado actual, la funcionalidad de **compartir un automóvil** es prácticamente inutilizable. La aplicación debería ser mucho más cómoda y rápida de usar para que las personas realmente quieran recurrir a ella.

A pesar de esto, considero que **Urban Routes tiene potencial**, y con un desarrollo más robusto puede ofrecer una experiencia valiosa a los usuarios.

## 📁 Archivos del Proyecto

- [Google Sheets - Listas de verificación, casos de prueba y resultados](https://docs.google.com/spreadsheets/d/1tvd6pbDRATBCLmLeVhmt8s8-7MxV6MNp/edit?usp=sharing)

## ✅ Conclusiones

Este proyecto fue una excelente oportunidad para aplicar habilidades de diseño de pruebas, análisis de requisitos y reporte de errores en un entorno simulado pero realista. Me permitió:

- Comprender en profundidad cómo debe documentarse y probarse una funcionalidad crítica.
- Desarrollar criterio para evaluar tanto la lógica del sistema como la experiencia del usuario.
- Practicar el uso de herramientas clave del entorno QA como Jira, Google Sheets y herramientas de diagramación.

En definitiva, este trabajo no solo reforzó mi perfil técnico como QA Tester, sino que también consolidó mi confianza para enfrentar proyectos reales en la industria.
