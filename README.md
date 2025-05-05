# Análisis de Datos con Pandas, Matplotlib y SQLite

Este proyecto tiene como objetivo aplicar un flujo de trabajo completo de análisis de datos utilizando `pandas`. Cada paso ha sido documentado en celdas de Markdown, mientras que el código asociado se presenta sin comentarios dentro de celdas de código, siguiendo las directrices especificadas.

## Estructura del Proyecto

El notebook se divide en las siguientes secciones:

### 1. Importación de Datasets

Se utiliza la librería `pandas` para cargar el/los dataset(s) proporcionados en el entorno de trabajo. Se parte del supuesto de que los archivos están en formato CSV, aunque pueden adaptarse a otros formatos si es necesario.

### 2. Exploración Inicial

Aplicación de métodos de inspección como:

- `.head()`, `.tail()`
- `.info()`, `.describe()`
- `.shape`, `.columns`, `.dtypes`

Esto permite entender la estructura general de los datos.

### 3. Limpieza y Normalización de Datos

Se realiza limpieza de valores nulos, transformación de tipos de datos, eliminación de duplicados y normalización de columnas. Esto incluye:

- Reemplazo de valores faltantes
- Conversión de tipos de datos
- Renombrado de columnas si es necesario

### 4. Estadísticas Descriptivas

Obtención de medidas estadísticas clave como:

- Media, mediana, moda
- Desviación estándar, percentiles
- Conteo de valores únicos por categoría

## 📝 Requisitos

- Python 3.12
- Jupyter Notebook
- pandas

Puedes instalar los paquetes necesarios con:

```bash
pip install pandas matplotlib
```

---

## Cómo usar

1. Abre el archivo `.ipynb` con Jupyter Notebook o JupyterLab.
2. Sigue el flujo del notebook. Cada paso está precedido por una celda de Markdown explicativa.
3. Asegúrate de tener el archivo del dataset en el mismo directorio del notebook o ajusta la ruta en la celda de importación.
4. Al finalizar, se genera un archivo `.sqlite` con los datos limpios.

---

## Salidas

- Visualizaciones en el notebook
- Estadísticas en formato tabular
- Archivo `datos_limpios.sqlite` exportado

---
