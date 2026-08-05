# Top 10 Empresas Peruanas en Bolsa — Ingresos vs. Crecimiento

Proyecto de práctica en Python aplicado a datos financieros reales, 
como parte de mi transición hacia el análisis de datos.

## 📊 Objetivo
Comparar el tamaño (ingresos anuales) y la rentabilidad (crecimiento 
de utilidad por acción) de las 10 empresas peruanas con mayores 
ingresos que cotizan en la Bolsa de Valores de Lima (BVL).

## 🔍 Hallazgos principales
- El Banco de Crédito del Perú lidera en ingresos (S/ 23,220 millones), 
  seguido de InRetail Perú y Southern Copper.
- Minsur, pese a tener ingresos bastante menores que el top 5, registró 
  el mayor crecimiento de utilidad por acción del grupo (+66% TTM YoY).
- Ferreycorp fue la única empresa del top 10 con caída en su utilidad 
  por acción (-25%), a pesar de tener ingresos altos — evidencia de que 
  tamaño y rentabilidad no siempre van de la mano.

## ⚠️ Nota sobre la fuente de datos
Los datos provienen de TradingView (proveedor: FactSet), basados en 
estados financieros públicos reportados por cada empresa. Solo incluye 
empresas que cotizan en bolsa — no representa a todas las empresas 
peruanas, ya que las privadas no están obligadas a reportar cifras 
públicamente.

## 🛠️ Herramientas utilizadas
- Python (Pandas, Matplotlib)
- Fuente de datos: TradingView / FactSet

## 📁 Contenido
- `Top10_Empresas_Peru.ipynb` — Notebook con el análisis completo.
- `Top10_Empresas_Peru_BVL.csv` — Dataset con ingresos, sector y 
  crecimiento BPA de cada empresa.
