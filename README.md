# Visualización Interactiva con Tableau o Power BI

## Descripción del Proyecto
Este proyecto tiene como objetivo realizar un análisis exploratorio y una visualización interactiva de datos utilizando **Tableau Public** o **Power BI Desktop**. A través del procesamiento y limpieza de datos en Python, se genera un archivo CSV listo para ser importado en herramientas de visualización.

## Estructura del Proyecto
```
Visualización Interactiva con Tableau o Power BI
│
├── data
│   └── tu_dataset.csv  # Archivo con los datos originales
│
├── notebooks
│   └── 01_visualizacion_interactiva.ipynb  # Notebook con análisis y limpieza de datos
│
├── outputs
│   └── clean_data.csv  # Archivo procesado listo para visualización en Tableau/Power BI
│
├── README.md  # Este archivo con la documentación del proyecto
│
└── .gitignore  # Archivos y carpetas ignoradas en el control de versiones
```

## Dataset
- **Nombre:** `tu_dataset.csv`
- **Tamaño:** 5000 registros
- **Formato:** CSV
- **Columnas:**
  - `ID`: Identificador único.
  - `Fecha`: Timestamp de la transacción.
  - `Categoria`: Categoría de la transacción.
  - `Ventas`: Monto de la venta en dólares.
  - `Clientes`: Cantidad de clientes en la transacción.
  - `Region`: Zona geográfica de la transacción.
  - `Descuento`: Porcentaje de descuento aplicado.
  - `Satisfaccion`: Puntuación de satisfacción del cliente (1-5).

## Instalación y Configuración
### 1. Clonar el repositorio
```bash
git clone https://github.com/tu_usuario/tu_repositorio.git
cd tu_repositorio
```

### 2. Crear y activar un entorno virtual
```bash
python -m venv ../environments/my_interactive_viz
```
- En Windows:
```bash
../environments/my_interactive_viz/Scripts/activate
```
- En macOS/Linux:
```bash
source ../environments/my_interactive_viz/bin/activate
```

### 3. Instalar dependencias
```bash
pip install -r requirements.txt
```

## Uso del Proyecto
### 1. Ejecutar el notebook de limpieza de datos
Abre Jupyter Notebook y ejecuta `notebooks/01_visualizacion_interactiva.ipynb` para generar `clean_data.csv`.

### 2. Importar `clean_data.csv` en Tableau o Power BI
- **En Tableau Public:**
  1. Abre Tableau y selecciona "Connect" → "Text File".
  2. Carga `outputs/clean_data.csv`.
  3. Crea visualizaciones interactivas.

- **En Power BI Desktop:**
  1. Abre Power BI y selecciona "Obtener Datos" → "Texto/CSV".
  2. Carga `outputs/clean_data.csv`.
  3. Diseña dashboards interactivos.

## Resultados Esperados
- **Gráficos de barras, líneas y mapas interactivos** para analizar las tendencias de ventas y clientes.
- **Dashboards interactivos** con filtros que permitan explorar los datos.
- **Análisis de patrones de ventas y comportamiento de los clientes** en distintas regiones y categorías.

## Control de Versiones y Buenas Prácticas
### Creación de una rama para el proyecto
```bash
git checkout -b feature/interactive-viz
git add .
git commit -m "Inicio del proyecto de visualización interactiva"
git push origin feature/interactive-viz
```

### Archivo .gitignore recomendado
Se recomienda ignorar archivos y carpetas innecesarias como entornos virtuales, cachés y datos temporales.

## Contribuciones
Si deseas contribuir, por favor:
1. Haz un fork del repositorio.
2. Crea una rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit.
4. Abre un Pull Request.

## Contacto
Si tienes preguntas o sugerencias, no dudes en contactarme en [tu email o LinkedIn].

