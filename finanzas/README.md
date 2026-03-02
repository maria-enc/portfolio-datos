# 📈 Análisis Financiero IBEX 2020-2025

## Descripción
Análisis financiero comparativo de activos del mercado español y americano
usando Python. El proyecto forma parte de mi portfolio de datos con enfoque
en IA.

## Activos analizados
- **Banco Santander (SAN.MC)**
- **BBVA (BBVA.MC)**
- **IBEX 35 (^IBEX)**
- **S&P 500 (^GSPC)**

## Herramientas utilizadas
- Python 3.11
- yfinance — descarga de datos financieros en tiempo real
- pandas — manipulación y análisis de series temporales
- matplotlib / seaborn — visualización estática
- plotly — gráficos interactivos
- Jupyter Notebook — entorno de análisis

## Estructura del proyecto
- `analisis_financiero_ibex.ipynb` — notebook principal con el análisis completo

## Contenido del análisis
- Descarga de datos históricos (2020-2025) vía Yahoo Finance
- Cálculo de retornos diarios y acumulados
- Análisis de volatilidad anualizada por activo con días reales de cotización
- Volatilidad móvil a 30 días
- Correlación entre activos
- Sharpe Ratio (rentabilidad ajustada al riesgo)
- Dashboard interactivo con Plotly

## Estado
🚧 En desarrollo — análisis de volatilidad en revisión

## Cómo ejecutar el notebook
1. Clona el repositorio: `git clone https://github.com/mary-enc/portfolio-datos.git`
2. Instala las dependencias: `pip install yfinance pandas matplotlib seaborn plotly`
3. Abre el notebook: `jupyter notebook analisis_financiero_ibex.ipynb`

## Fuente de datos
[Yahoo Finance](https://finance.yahoo.com/) vía librería yfinance