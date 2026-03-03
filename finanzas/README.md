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
- numpy - cálculos matemáticos
- matplotlib — visualización estática
- plotly — gráficos interactivos
- Jupyter Notebook — entorno de análisis

## Estructura del proyecto
- `analisis_financiero_ibex.ipynb` — notebook principal con el análisis completo
- `correlacion_2019_2026.html` - html con el gráfico que muestra la correlación entre los índices bursátiles
- `sharpe_rolling_2019_2026.html` - html con el gráfico que muestra la relación entre el Ratio Sharpe total y el rolling a 12 meses

## Contenido del análisis
- Descarga de datos históricos (2019-2026) vía Yahoo Finance
- Cálculo de retornos diarios y acumulados
- Análisis de volatilidad anualizada por activo 
- Volatilidad móvil a 30 días
- Correlación entre activos
- Sharpe Ratio (rentabilidad ajustada al riesgo)
- Dashboards interactivos con Plotly

## Estado
🚧 En desarrollo — conclusiones en revisión

## Cómo ejecutar el notebook
1. Clona el repositorio: `git clone https://github.com/mary-enc/portfolio-datos.git`
2. Instala las dependencias: `pip install yfinance pandas matplotlib seaborn plotly`
3. Abre el notebook: `jupyter notebook analisis_financiero_ibex.ipynb`

## Fuente de datos
[Yahoo Finance](https://finance.yahoo.com/) vía librería yfinance