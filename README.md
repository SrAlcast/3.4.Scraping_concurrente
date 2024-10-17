# 🌦️ Laboratorio 3.4: Selenium y Paralelización: Extracción Asíncrona de Datos Meteorológicos

Este repositorio contiene un Jupyter Notebook diseñado para automatizar la navegación web y extraer datos meteorológicos 🕵️‍♂️ de **todos los municipios** de una lista proporcionada de España, correspondientes a los últimos 10 meses. A diferencia del laboratorio anterior, aquí se implementa paralelización y asincronía para optimizar el proceso, permitiendo que la información de todos los municipios se procese al mismo tiempo.

## 🛠️ Herramientas y librerías utilizadas

El proyecto hace uso de varias librerías populares en Python, especialmente adaptadas para la paralelización de tareas y el procesamiento asincrónico, incluyendo:

- **BeautifulSoup**: Utilizada para el scraping de contenido HTML.
- **Requests**: Empleada para hacer solicitudes HTTP y obtener el código HTML de las páginas web.
- **Pandas** y **Numpy**: Para la manipulación y análisis de datos.
- **Selenium**: Para la automatización de la interacción con navegadores web.
- **Asyncio**: Para manejar tareas asincrónicas y procesar múltiples solicitudes al mismo tiempo.
- **Multiprocessing**: Para la ejecución en paralelo de procesos de scraping.

## 🚀 Funcionalidades principales del Notebook

1. **📌 Procesamiento de todos los municipios simultáneamente**: En lugar de seleccionar un subconjunto de municipios, se extrae información meteorológica para **todos** los municipios de la lista proporcionada, usando técnicas de paralelización y asincronía para realizar estas tareas de manera eficiente.

2. **🌤️ Extracción paralelizada de datos meteorológicos**: El uso de **asyncio** y **multiprocessing** permite realizar la navegación y scraping en paralelo para varios municipios, lo que reduce considerablemente el tiempo total de procesamiento.

3. **🤖 Automatización avanzada del navegador**: A través de Selenium, se simulan interacciones con las páginas meteorológicas para obtener datos de los últimos 10 meses por cada municipio. Al hacerlo de manera paralelizada, la recolección de datos se optimiza.

4. **📊 Organización de datos**: Los datos obtenidos se estructuran de manera eficiente para su análisis posterior, con el manejo de grandes volúmenes de información que provienen de todos los municipios.

5. **⚡ Mejora de rendimiento**: El uso de paralelización asegura que el tiempo de scraping se reduzca significativamente, sin sacrificar la calidad de los datos recolectados.

6. **⚠️ Manejo robusto de excepciones**: Se implementan controles para manejar errores comunes en la automatización y la ejecución asincrónica, tales como elementos no encontrados o límites de tiempo superados en el scraping.

## 💻 Requisitos del sistema

Para ejecutar este notebook correctamente, es necesario instalar las siguientes dependencias, que incluyen soporte para tareas asincrónicas y paralelización:

- Python 3.7 o superior
- `beautifulsoup4`
- `requests`
- `pandas`
- `numpy`
- `selenium`
- `webdriver-manager`
- `asyncio`
- `concurrent.futures`

Puedes instalar todas las dependencias ejecutando el siguiente comando:

```bash
pip install -r requirements.txt
```

## 📝 Cómo usar este proyecto

1. Clona este repositorio en tu máquina local:

   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
   ```

2. Instala las dependencias:

   ```bash
   pip install -r requirements.txt
   ```

3. Ejecuta el notebook en un entorno local o en JupyterLab.

   La ejecución asincrónica y en paralelo garantizará que el proceso sea más rápido y eficiente.

## 🙌 Créditos

Este proyecto fue desarrollado como parte de una práctica que incorpora la mejora de paralelización y asincronía en tareas de automatización y scraping web para mejorar la eficiencia en la recolección de datos meteorológicos.

 
