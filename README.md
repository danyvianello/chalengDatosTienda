# Alura Store Latam — Análisis para decisión de venta de tienda

Proyecto de análisis de datos para apoyar al **Señor Juan** en la decisión de **qué tienda vender** para invertir en un nuevo negocio. Se comparan 4 tiendas con métricas de facturación, categorías, productos y costos de envío.

## Objetivo

Identificar la **tienda menos lucrativa** entre cuatro opciones, de modo que al venderla se libere capital para el nuevo negocio con el menor impacto en los ingresos actuales.

## Contenido del análisis

El notebook `AluraStoreLatam.ipynb` incluye:

| # | Análisis | Descripción |
|---|----------|-------------|
| 1 | **Facturación total por tienda** | Suma de ingresos (Precio) por cada tienda |
| 2 | **Categorías más populares** | Ventas y facturación por categoría de producto en cada tienda |
| 3 | **Promedio de facturación por venta** | Ticket promedio (cuánto se factura en promedio por venta) |
| 4 | **Productos más y menos vendidos** | Top y bottom de productos por cantidad de ventas por tienda |
| 5 | **Costo promedio de envío** | Promedio y total de costos de envío por tienda |
| 6 | **Reporte ejecutivo** | Resumen, ranking y recomendación de qué tienda vender |

## Datos

- **Fuente:** 4 archivos CSV (una tienda por archivo), cargados desde GitHub en el notebook.
- **Columnas principales:** Producto, Categoría del Producto, Precio, Costo de envío, Fecha de Compra, Vendedor, Lugar de Compra, Calificación, Método de pago, Cantidad de cuotas, lat, lon.

También hay copia local en `base-de-datos-challenge1-latam/` (tienda_1.csv, tienda_2.csv, tienda_3.csv, tienda_4.csv).

## Requisitos

- **Python** 3.x  
- **pandas** — manejo de datos  
- **matplotlib** — gráficos  

Instalación:

```bash
pip install pandas matplotlib
```

## Cómo ejecutar

1. Clona o descarga el proyecto.
2. Abre `AluraStoreLatam.ipynb` en Jupyter Notebook, JupyterLab o VS Code.
3. Ejecuta todas las celdas (Run All) para ver los análisis y el reporte final.

El reporte al final del notebook indica **qué tienda se recomienda vender** según la facturación total y las métricas analizadas.

## Estructura del proyecto

```
challenge1-data-science-latam-main/
├── README.md
├── AluraStoreLatam.ipynb          # Notebook con el análisis completo
└── base-de-datos-challenge1-latam/
    ├── tienda_1 .csv
    ├── tienda_2.csv
    ├── tienda_3.csv
    └── tienda_4.csv
```

## Créditos

Challenge de Data Science — Alura Latam.
