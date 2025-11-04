# Challenge 1 Data Science Latam - Análisis de Alura Store

Este proyecto es parte del Challenge 1 de Data Science de Alura Latam. Consiste en un análisis completo de datos de ventas de 4 tiendas en línea, utilizando Python, Pandas, Matplotlib y Seaborn para explorar diversos aspectos del negocio.

## Descripción

El notebook `AluraStoreLatam.ipynb` realiza un análisis exhaustivo de los datos de ventas, incluyendo:

1. **Análisis de facturación**: Cálculo y visualización de los ingresos totales por tienda.
2. **Ventas por categoría**: Análisis de las categorías de productos más vendidas por tienda.
3. **Calificación promedio**: Evaluación de las calificaciones promedio de las compras por tienda.
4. **Productos más y menos vendidos**: Identificación de los productos con mayor y menor volumen de ventas.
5. **Envío promedio por tienda**: Análisis de los costos promedio de envío.
6. **Análisis geográfico**: Exploración de patrones geográficos en las ventas, incluyendo mapas de dispersión y calor.

## Tecnologías Utilizadas

- **Python 3.x**
- **Pandas**: Para manipulación y análisis de datos.
- **Matplotlib**: Para creación de gráficos básicos.
- **Seaborn**: Para visualizaciones estadísticas avanzadas.
- **Jupyter Notebook**: Para la ejecución interactiva del análisis.

## Instalación

1. Asegúrate de tener Python 3.x instalado en tu sistema.
2. Instala las dependencias necesarias ejecutando:
   ```
   pip install pandas matplotlib seaborn
   ```
3. Si usas Jupyter Notebook, instala también:
   ```
   pip install jupyter
   ```

## Uso

1. Clona o descarga este repositorio.
2. Abre el archivo `AluraStoreLatam.ipynb` en Jupyter Notebook, VS Code o cualquier entorno compatible con notebooks.
3. Ejecuta las celdas en orden para cargar los datos y generar los análisis.
4. Los datos se cargan automáticamente desde URLs de GitHub, por lo que no es necesario descargar archivos adicionales.

## Datos

Los datos utilizados provienen de 4 archivos CSV alojados en GitHub:
- `tienda_1 .csv`
- `tienda_2.csv`
- `tienda_3.csv`
- `tienda_4.csv`

Cada archivo contiene información sobre productos vendidos, incluyendo precio, categoría, calificación, costo de envío, fecha de compra, ubicación geográfica (latitud y longitud), entre otros.

## Estructura del Proyecto

```
challenge1-data-science-latam/
├── AluraStoreLatam.ipynb    # Notebook principal con el análisis
├── README.md                 # Este archivo
└── base-de-datos-challenge1-latam/  # Carpeta con datos (opcional, ya que se cargan desde URLs)
    ├── tienda_1 .csv
    ├── tienda_2.csv
    ├── tienda_3.csv
    └── tienda_4.csv
```

## Resultados Clave

- **Facturación**: Tienda 1 tiene la mayor facturación total.
- **Categorías**: "Muebles" y "Electrónicos" son las categorías más vendidas en general.
- **Calificaciones**: Todas las tiendas tienen calificaciones promedio alrededor de 4.0.
- **Productos**: Los productos más vendidos varían por tienda.
- **Envío**: Los costos de envío promedio son similares entre tiendas.
- **Geografía**: Las ventas están distribuidas en diversas ubicaciones, con correlaciones bajas entre ubicación y precio/calificación.

## Contribuciones

Este proyecto es educativo y parte de un challenge de Alura. Si deseas contribuir, puedes:
- Reportar issues
- Sugerir mejoras
- Crear pull requests

## Licencia

Este proyecto es para fines educativos y no tiene una licencia específica.

## Autor

Proyecto desarrollado como parte del Challenge 1 de Data Science de Alura Latam.