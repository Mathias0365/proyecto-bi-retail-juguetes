# Análisis y Predicción de Demanda - Tienda Retail (Jugetes)

Proyecto completo de **Inteligencia de Negocio (BI) y Machine Learning** para una cadena de tiendas retail de juguetes. Incluye modelado de datos (Data Warehouse), dashboard en Power BI y modelos de análisis descriptivo y predicción de demanda.

## 📊 Alcance del proyecto

- **Limpieza y transformación de datos** con notebooks Python
- **Modelado multidimensional (Data Warehouse)** en SQL Server
- **Dashboard interactivo en Power BI** con medidas DAX
- **Análisis descriptivo** de ventas, demanda, descuentos, inventario y promociones
- **Modelos de predicción de demanda** (Machine Learning)
- **KPIs** clave: demanda, descuento, ventas por día/mes, inventario, promoción, top productos y tiendas

## 🛠️ Tecnologías

- **Power BI Desktop**: dashboard interactivo
- **DAX**: medidas avanzadas (comparativas anuales, ranking, KPIs)
- **SQL Server**: Data Warehouse (modelo estrella)
- **Python**: limpieza de datos, análisis descriptivo y predicción
  - pandas, matplotlib, scikit-learn, notebooks Jupyter
- **Excel**: datos fuente y apoyo analítico

## 📂 Estructura del proyecto

```
CURSO MIERCOLES/
├── dashboard retai.pbix              # Dashboard Power BI
├── dashboard retai_v2.pbix           # Versión actualizada
├── DW_RETAIL.sql                     # Script Data Warehouse
├── KPIs_Modelos.ipynb                # KPIs y modelos de Machine Learning
├── Limpieza_datos.ipynb              # Notebook de limpieza de datos
├── MEDIDAS DAX.txt                   # Medidas DAX del modelo
├── Retail.csv                        # Dataset fuente
├── TIENDA DE JUGUETES DATA.csv       # Dataset original
├── ANALISIS DESCRIPTIVO Y PREDICCION.xlsx
├── kpi_charts/                       # Gráficos KPI generados
│   ├── kpi_demanda.png
│   ├── kpi_descuento.png
│   ├── kpi_ventas_mes.png
│   ├── kpi_top_producto.png
│   └── ...
├── INFORME FINAL/                    # Informe y presentación final
│   ├── INFORME BI ZEGEL - COMPLETADO.docx
│   └── Presentacion Evaluacion Final - BI ZEGEL.pptx
├── GRAFICO_DRIVERS.png               # Drivers de ventas
└── GRAFICO_MODELO.png                # Resultados del modelo
```

## 🔍 Medidas DAX destacadas

- **Ventas Netas** (con descuento)
- **Comparativa anual** (año actual vs año anterior, % variación)
- **Ranking** de tiendas y productos por ventas
- **Utilidad estimada**
- **KPIs** de demanda, inventario y promoción

## 🚀 Cómo usar

1. Abrir `dashboard retai_v2.pbix` en Power BI Desktop.
2. Los modelos de predicción están en `KPIs_Modelos.ipynb`.

## 📄 Fuente de datos

Dataset de ventas de tienda retail de juguetes (archivos CSV/Excel incluidos en el proyecto).

---

*Proyecto académico de Business Intelligence y Machine Learning.*
