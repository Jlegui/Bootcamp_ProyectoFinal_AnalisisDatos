# Bootcamp MITIC - Proyecto Final  
## Global Electronics Retail: Caracterización del Mercado

**Autor:** Juan Leguizamón  
**Fecha:** Marzo 2025  

---

## Descripción del Proyecto

Este proyecto tiene como objetivo caracterizar el mercado global de electrónicos entre los años 2016 y 2021. A través de técnicas de análisis exploratorio, estadístico y visual, se busca entender cómo varían las ventas, rentabilidad y comportamiento del consumidor según continente, canal de compra, grupo etario y frecuencia de compra.

El análisis fue realizado utilizando Python (Colab) para la preparación, modelado y análisis de los datos, y Power BI para sintetizar visualmente los hallazgos clave.

---

## Dataset Utilizado

- Nombre del archivo: Electronicos_ventas.csv
- Período: 2016 - 2021  
- Columnas destacadas: Fecha, País, Continente, Categoría, Subcategoría, Precio, Costos, Utilidad, Edad, Género, Canal de compra, Cliente.

---

## Metodología del Análisis

1. **Carga y Exploración Inicial**  
   - Lectura del CSV con Pandas  
   - Visualización general del volumen de ventas y columnas clave  
   - Revisión de tipos de datos y valores nulos

2. **Limpieza y Preparación**  
   - Tratamiento de valores faltantes  
   - Conversión de monedas utilizando tasas de cambio  
   - Categorización de edades por grupo etario  
   - Normalización y winsorización de variables monetarias  
   - Clasificación de clientes según frecuencia de compra (Único vs Recurrente)

3. **Análisis Estadístico**  
   - Medidas de tendencia central y dispersión  
   - Visualización de distribuciones (PDF, CDF)  
   - Detección y tratamiento de outliers por categoría  
   - Análisis de correlación entre variables financieras  
   - Pruebas de hipótesis: diferencias significativas de ganancias entre continentes

4. **Segmentación para Análisis**  
   - Por continente: América del Norte, Europa y Oceanía  
   - Por canal de compra: In-Store vs Online  
   - Por género y grupo etario  
   - Por frecuencia de compra (compradores únicos vs recurrentes)

5. **Visualización y Storytelling**  
   - Desarrollo de un dashboard interactivo en Power BI con 4 páginas:
     - Resumen global  
     - Rentabilidad por categoría  
     - Perfil de cliente  
     - Cierre y hallazgos clave

---

## Archivos del Proyecto

- **Proyecto_Final_Análisis_de_Datos_MITIC.ipynb**  
  Notebook completo con limpieza, análisis y comentarios.

- **Electronicos_ventas.csv**  
  Tabla final de ventas procesada y enriquecida.

- **Calendario_ventas.csv**  
  Dimensión calendario para análisis en Power BI.

- **Presentación final.pbix**  
  Dashboard interactivo con visualizaciones segmentadas.

- **README_Proyecto_Final_JuanLeguizamon.md**  
  Documento explicativo con metodología, resultados y conclusiones.

---

## Conclusiones Relevantes

- Europa lidera en rentabilidad promedio por unidad, con márgenes y precios más altos.
- América del Norte tiene el mayor volumen de ventas, pero márgenes más bajos.
- Oceanía muestra un menor volumen de ventas y mayor dispersión de precios.
- El 80% de las ventas se realiza en tiendas físicas, aunque el canal online crece año a año.
- La edad promedio del comprador es de aproximadamente 55 años.
- Las categorías más rentables no siempre son las más vendidas, lo que sugiere oportunidades de optimización.
- Se verificaron diferencias estadísticamente significativas entre los continentes en términos de rentabilidad.

---

## Reflexión Final

Este análisis muestra cómo, mediante herramientas de análisis de datos y visualización, es posible transformar registros en decisiones estratégicas: entender a los clientes, optimizar márgenes y redefinir canales de venta.

---
