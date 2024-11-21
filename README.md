# Financial Data Scraper

Este proyecto es un script en Python diseñado para extraer datos financieros, específicamente los ingresos históricos de empresas como Tesla y GameStop, a partir de tablas HTML. Utiliza `BeautifulSoup` para el web scraping y `pandas` para procesar y estructurar los datos, haciéndolos adecuados para análisis y visualización.

## Características principales

- **Web Scraping**: Obtiene datos de tablas HTML usando `BeautifulSoup`.
- **Limpieza de datos**: Elimina caracteres no deseados (como comas y signos de dólar) y convierte los ingresos a valores numéricos.
- **Organización estructurada**: Los datos se almacenan en un `DataFrame` de pandas para facilitar su manipulación y análisis.
- **Adaptabilidad**: Puede ajustarse fácilmente para extraer datos de otras tablas HTML con estructuras similares.

## Tecnologías utilizadas

- Python
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)
- [pandas](https://pandas.pydata.org/)

## Uso potencial

Este proyecto puede servir como base para:
- Análisis financiero.
- Visualización de tendencias de ingresos históricos.
- Modelos de predicción financiera.
