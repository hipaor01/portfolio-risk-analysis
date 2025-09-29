# portfolio-risk-analysis
Este repositorio contiene un análisis de carteras básico en Python.
El objetivo es seleccionar activos poco correlacionados, construir carteras de inversión, y evaluar su riesgo mediante métricas como CVaR.

# Contenido
1. Selección de activos
   - Cota superior sobre la correlación (máx. 0.6).
   - Datos extraídos de Yahoo Finance.
2. Construcción de carteras
   - Generación de 100 carteras aleatorias.
   - Ponderaciones normalizadas (suma 1).
3. Evaluación de riesgos
   - Cálculo de CVaR (Valor en Riesgo Condicional).
4. Visualizaciones
   - Evolución de rendimientos.
   - Matriz de correlaciones.
# Tecnologías utilizadas
- Python 3.
- Pandas, NumPy, Matplotlib.
- yfinance para descarga de datos.
