# Encuentra Compañeros de Piso - Proyecto de Compatibilidad

Este es un proyecto desarrollado en Python que utiliza la biblioteca Streamlit para crear una aplicación web interactiva. La aplicación ayuda a encontrar compañeros de piso compatibles en función de ciertas características.

## Funcionalidades

- **Ingreso de Datos de Inquilinos Actuales**: Los usuarios pueden ingresar información sobre los inquilinos actuales en el piso, como sus horarios, preferencias de música, etc.
  
- **Búsqueda de Nuevos Compañeros**: Los usuarios pueden especificar cuántos nuevos compañeros de piso desean buscar y la aplicación utiliza un algoritmo de búsqueda para encontrar los inquilinos más compatibles.

- **Visualización de Resultados**: La aplicación muestra los resultados en forma de un gráfico de barras que representa el nivel de compatibilidad de cada nuevo compañero de piso, así como una tabla comparativa que muestra las características de los inquilinos buscados y los inquilinos compatibles encontrados.

## Archivos del Proyecto

- **app.py**: Contiene el código principal de la aplicación Streamlit.
  
- **ayudantes.py**: Contiene funciones auxiliares para generar gráficos y tablas.
  
- **dataset_inquilinos.csv**: Archivo CSV que contiene los datos de los inquilinos.
  
- **logica.py**: Contiene la lógica principal del proyecto, incluyendo la carga de datos, la codificación one-hot, el cálculo de la matriz de similitud y la búsqueda de inquilinos compatibles.

## Uso

1. Clona este repositorio en tu máquina local.
  
2. Instala las dependencias necesarias utilizando el archivo `requirements.txt`:
   ```
   pip install -r requirements.txt
   ```
  
3. Ejecuta la aplicación utilizando el comando:
   ```
   streamlit run app.py
   ```

4. Ingresa los datos de los inquilinos actuales y especifica cuántos nuevos compañeros de piso deseas buscar.

5. Haz clic en el botón "BUSCAR NUEVOS COMPAÑEROS" para ver los resultados.