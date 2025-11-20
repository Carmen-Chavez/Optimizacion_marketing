# 🖥️ Análisis de negocio; diferentes fuentes de marketing (9)

## 📋 Descripción
Se realizó un analisis de negocio para obtener metricas de usuario (dau, wau y mau). Economia unitaria por cliente (LTV). De los diferentes canales de publicidad, determinar cual era el mas costoso Vs el mas economico (CAC). Y finalmente el ROMI total (rendimiento de la campaña).

## 🎯 Objetivos
- Manipulación de datos (data wrangling).
- Métricas de usuario.
- Economía unitaria.

## 📊 Datasets Utilizados
'/datasets/visits_log_us.csv'
'/datasets/orders_log_us.csv'
('/datasets/costs_us.csv'

## 🔧 Tecnologías
Entorno de desarrollo:

Jupyter Notebook.
Python 3.9.19.
### Líbrerias:
Pandas.
Matplotlib.
Seaborn.
Numpy

## 📈 Conclusión
### Visitas
Las visitas diarias de usuarios unicos fueron (dau) 364, las visitas semanales de usuarios unicos fueron (wau) 52 y finalmente las visitas mensuales de usuarios unicos fueron (mau) 12. En promedio hay 1.08 sesiones por usuario al día y la duración promedio (en segundos) es de 643.5. El porcentaje con la que los usuarios regresan va del 1.9% al 8.5%.

### Ventas
Los usuarios usualmente compran desde el día de su primer visita y en los 2 días posteriores. Durante la temporada decembrina se llego a alcanzar más de 6 000 ordenes (periodo mensual) y el mes mas bajo fue agosto con 1 800 ordenes aproximadamente. El promedio de compra por usuarios es de 1.14 ordenes y el ingreso promedio que un usuario aporta (LTV) es de $7.97 dolares.

### Marketing
Se gasto un total de 329131.62 dolares y la fuente de adquisición mas cara fue la número tre con un costo de 141 321.64 dolares y la mas economica la número 9 con un costo de $55.49 dolares. El costo de adquisición más caro por cliente fue por la fuente número 1 y la mas economica la número 9. El ROMI total fue de 76.58%, esto es que obtuvo una ganancia del 76.58% del lo que invirtio en las campañas.

