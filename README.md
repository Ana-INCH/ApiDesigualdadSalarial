# ApiDesigualdadSalarial

# Brecha salarial de género en México

Análisis de la brecha salarial de género en México, usando datos oficiales de la OCDE y el Banco Mundial.

## ¿Qué hace?

- Descarga la brecha salarial de género (mediana) desde la API de la OCDE
- Descarga participación laboral por sexo desde la API del Banco Mundial
- Limpia y explora ambos conjuntos de datos
- Compara ambas series en una gráfica

## ¿Cómo usarlo?

1. Abre el notebook en Google Colab
2. Corre todas las celdas (`Entorno de ejecución` → `Ejecutar todas`)
3. Los resultados se guardan como CSV al final del notebook

## Datos

- OCDE: `sdmx.oecd.org` — dataset Gender Wage Gap
- Banco Mundial: `api.worldbank.org` — indicadores `SL.TLF.CACT.FE.ZS` y `SL.TLF.CACT.MA.ZS`

Sin necesidad de API key en ninguna de las dos.
