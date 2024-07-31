# 🛒 Comparador de Precios de Supermercado con Python 🏷️

¡Hola y bienvenidos a mi proyecto! 🎉 En este proyecto, realizamos scraping de precios de productos en un supermercado para comparar cómo varían los precios en diferentes fechas. Con esta información, podemos analizar tendencias y tomar decisiones informadas sobre nuestras compras. 📊💰

## **📝 Descripción**

Este proyecto se centra en extraer datos de precios de productos de un sitio web de supermercado usando Selenium y BeautifulSoup. Los datos son almacenados en archivos CSV y posteriormente analizados para observar cambios en los precios a lo largo del tiempo.

## **🚀 ¿Cómo Funciona?**

1. **Scraping de Datos 🕷️**:
   - **Inicialización**: Configuramos el entorno y las opciones de Chrome para el scraping.
   - **Acceso a la Página**: Usamos Selenium para abrir el navegador, buscar el sitio web del supermercado, y aceptar cookies y avisos necesarios.
   - **Extracción de Datos**: Navegamos por las categorías de productos y extraemos información sobre nombres, pesos y precios de los productos utilizando BeautifulSoup.

2. **Almacenamiento de Datos 📂**:
   - Los datos extraídos se almacenan en archivos CSV en Google Drive para su posterior análisis.

3. **Procesamiento de Datos 🔄**:
   - **Unificación de DataFrames**: Combinamos los datos extraídos en diferentes fechas, eliminamos duplicados y consolidamos la información en un único DataFrame.
   - **Comparación de Precios 📉**: Se realiza un merge para unir los precios de todos los DataFrames, facilitando la comparación de precios entre fechas.
