# 📊 Alura Store – Análisis de Desempeño de Tiendas
Este proyecto tiene como objetivo analizar el desempeño de las cuatro tiendas de la cadena Alura Store con el fin de recomendar cuál de ellas debería venderse para iniciar un nuevo emprendimiento.

El análisis se basa en datos de ventas, categorías de productos, calificaciones de clientes, productos más y menos vendidos, costos de envío y, de manera opcional, un análisis geográfico de las ventas.

---

## 🎯 Objetivo del proyecto
Identificar la tienda con menor eficiencia comercial, utilizando métricas cuantitativas y visualizaciones de datos, para apoyar la toma de decisiones del Sr. Juan.

---

## 📂 Estructura del proyecto
```bash
alura-store-analysis/
│
├── data/
│   └── raw/
│       ├── tienda_1.csv
│       ├── tienda_2.csv
│       ├── tienda_3.csv
│       └── tienda_4.csv
│
├── notebooks/
│   └── alura_store_analysis.ipynb
│
├── README.md
└── .gitignore
```

---

## 📊 Análisis realizados
- Ingresos totales por tienda
- Ventas por categoría de productos
- Calificación promedio de los clientes
- Productos más y menos vendidos por tienda
- Costo de envío promedio
- (Extra) Análisis del desempeño geográfico utilizando latitud y longitud

---

## 📈 Visualizaciones
Se generaron distintos tipos de gráficos utilizando Matplotlib, tales como:
  - Gráficos de barras para ingresos y ventas por categoría
  - Gráficos de barras para productos más y menos vendidos
  - Gráficos de dispersión para la distribución geográfica de las ventas
Estas visualizaciones permiten identificar patrones y comparar el desempeño entre tiendas de manera clara.

---

## 🧰 Tecnologías utilizadas
- Python 3
- Pandas
- Matplotlib
- Google Colab

---

## ▶️ Cómo ejecutar el proyecto
1. Clonar el repositorio:
```bash
git clone https://github.com/tu-usuario/alura-store-analysis.git
```
2. Abrir el archivo alura_store_analysis.ipynb en:
  - Google Colab
  - Jupyter Notebook
3. Ejecutar las celdas en orden para reproducir el análisis.

---

## ✅ Conclusión
Tras analizar todos los indicadores, se concluye que la Tienda 4 presenta el menor desempeño general en términos de ingresos, rotación de productos y competitividad, por lo que se recomienda que sea la tienda a vender.

---

## ✨ Autor
Proyecto desarrollado por Valentina \
Desafío de Data Science – Alura Latam

---
