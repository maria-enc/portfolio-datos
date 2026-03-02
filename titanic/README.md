# 🚢 Análisis de Supervivencia del Titanic

## Descripción
Análisis exploratorio del dataset del Titanic usando Python, Pandas, Matplotlib y Seaborn.
El objetivo es identificar qué factores influyeron más en la probabilidad de supervivencia de los pasajeros.

## Herramientas utilizadas
- Python 3.11
- pandas — manipulación y limpieza de datos
- matplotlib / seaborn — visualización
- Jupyter Notebook — entorno de análisis

## Estructura del proyecto
- `analisis_titanic.ipynb` — notebook principal con el análisis completo
- `train.csv` — dataset original de Kaggle
- `supervivencia_titanic.png` — gráfico resumen de la tasa de supervivencia
- `supervivencia_titanic_barras_apiladas.png` - gráfico resumen ampliado con barras apiladas para mostrar el total por cada categoría

## Principales conclusiones
- La tasa de supervivencia general fue del 38.2 %.
- Las mujeres y los niños tenían mayor probabilidad de salvarse; en los gráficos se aprecia claramente el efecto de “first women and children”.
- Viajar en primera clase daba ventaja: el porcentaje de supervivientes decae con la clase (1 > 2 > 3).
- Los grupos de edad muestran que los más jóvenes presentan tasas más altas de supervivencia.
- Los niños menores de 10 años pertenecientes a la tercera clase tenían menos probabilidad de sobrevivir que los pertenecientes a las otras dos clases.
- Las personas pertenecientes a familias con un número de miembros entre 1 y 2 tuvieron más probabilidad de sobrevivir que las más o menos numerosas. 
- A pesar de que más personas embarcaron en Southampton respecto a los otros dos puertos, presentan una menor tasa de supervivencia, sobre todo comparando con el puerto de Cherbourg. En este puerto hubo en proporción más embarcados pertenecientes a la primera clase.

## Cómo ejecutar el notebook
1. Clona el repositorio: `git clone https://github.com/maria-enc/portfolio-datos.git`
2. Instala las dependencias: `pip install pandas matplotlib seaborn jupyter`
3. Abre el notebook: `jupyter notebook analisis_titanic.ipynb`

## Dataset
[Titanic Dataset - Kaggle](https://www.kaggle.com/c/titanic/data)
```

