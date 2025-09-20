# Análisis-ventas-supermercados
Proyecto de análisis exploratorio de datos de ventas de una cadena de supermercados en EE. UU.
## Objetivos del proyecto
- Explorar la distribución de ventas, ganancias y descuentos.
- Identificar los productos y categorías más rentables.
- Analizar patrones de consumo por región, ciudad y segmento de clientes.
- Visualizar los resultados con gráficos claros y fáciles de interpretar.
- ## Conjunto de datos
El dataset contiene información de transacciones en múltiples sucursales de EE. UU. con las siguientes columnas principales:

- **Segmento**: tipo de cliente (ej. consumidor, corporativo).
- **Región, Estado, Ciudad**: ubicación de la venta.
- **Categoría / Subcategoría**: clasificación del producto.
- **Ventas**: valor total de la venta.
- **Cantidad**: unidades vendidas.
- **Descuento**: aplicado a la venta.
- **Ganancia**: beneficio obtenido.

-**Tecnologías utilizadas**
- **Python**
  - pandas
  - matplotlib
  - seaborn
  - plotly
- **Jupyter Notebook**

Principales análisis realizados
1. **Distribución de las ventas y ganancias**  
   - Histogramas y boxplots para detectar outliers.  
2. **Productos y categorías más rentables** 
   - Ranking de top 10 en ventas y ganancias.  
3. **Impacto del descuento en la rentabilidad**  
   - Relación entre % de descuento y ganancia obtenida.  
4. **Análisis geográfico**  
   - Ventas por región y estado, con gráficos de barras y mapas interactivos.  
5. **Análisis por Segmento y Modo de Envío**  
   - Diferencias de consumo entre segmentos (ej. consumidor vs corporativo).
   - Se analiza la popularidad y el impacto de los diferentes modos de envío en las ventas totales

   - ## Ejemplo de visualizaciones
<img width="1189" height="790" alt="Top10" src="https://github.com/user-attachments/assets/208666b7-dd70-4198-bb22-fc0364e6a950" />
- Resultados clave:
- Se identificó que la categoría de Tecnología es la de mayor ventas, mientras que Muebles tiene ventas altas pero menor margen.  
- Los descuentos superiores al 20% disminuyen significativamente las ganancias.
- La Región Oeste concentra la mayor parte de las ventas, pero el margen es más alto en la Región Central.  
- El Estado de California y New York son respectivamente los de mayores ganancias
---

## Próximos pasos
- Implementar un modelo predictivo simple para estimar ventas futuras según región y categoría.  
- Construir un dashboard en Power BI con estos datos.  

---
