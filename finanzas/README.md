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
- `comparacion_volatilidad_30D_vs_12M.html`- html que muestra la relación entre la volatilidad a 30D vs 12M
- `retornos_acumulados.png` - imagen con la gráfica correspondiente a los retornos acumulados de los 4 activos

## Contenido del análisis
- Descarga de datos históricos (2019-2026) vía Yahoo Finance
- Cálculo de retornos diarios y acumulados
- Análisis de volatilidad anualizada por activo 
- Volatilidad móvil a 30 días
- Correlación entre activos
- Sharpe Ratio (rentabilidad ajustada al riesgo) rolling 12M vs Sharpe Ratio Total
- Dashboards interactivos con Plotly

## Principales conclusiones
- El BBVA sobrepasó a los demás activos en retornos acumulados pero presenta más dependencia a los shocks.
- El IBEX queda por detrás del S&P en retornos acumulados.
- EL S&P muestra un crecimiento más estable.
- Los bancos presentan una mayor volatilidad estructural que los índices.
- En general, el Sharpe Rolling de S&P 500 es el más estable estructuralmente: la explicación es que tiene mayor diversificación sectorial que los otros activos con los que estamos comparando.
- La banca española tiene mayor sensibilidad a los tipos, el riesgo país y/o el ciclo económico.
- El IBEX 35 tiene una alta correlación con SAN y BBVA, lo cual es lógico ya que ambos bancos son componentes importantes del índice. 
- La correlación del IBEX 35 con el S&P 500 es más baja, lo que refleja la diferencia geográfica y sectorial entre los mercados español y estadounidense.
- La correlación entre los bancos españoles y S&P 500 es todavía más baja.

## Cómo ejecutar el notebook
1. Clona el repositorio: `git clone https://github.com/mary-enc/portfolio-datos.git`
2. Instala las dependencias: `pip install yfinance pandas numpy matplotlib plotly`
3. Abre el notebook: `jupyter notebook analisis_financiero_ibex.ipynb`

## Fuente de datos
[Yahoo Finance](https://finance.yahoo.com/) vía librería yfinance