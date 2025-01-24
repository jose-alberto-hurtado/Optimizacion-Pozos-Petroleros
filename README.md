# Optimizacion-Pozos-Petroleros

Proyecto para seleccionar las mejores regiones para pozos petroleros utilizando modelos predictivos y análisis de riesgos con bootstrapping.

Tabla de Contenidos
Descripción del Proyecto
Estructura del Repositorio
Metodología
Tecnologías Utilizadas
Resultados Principales
Cómo Ejecutar el Proyecto
Autor
Descripción del Proyecto
El objetivo de este proyecto es identificar la región con el mayor margen de beneficio para la extracción de petróleo mediante:

Modelos predictivos de regresión lineal.
Evaluación de riesgos utilizando simulaciones de bootstrapping.
Visualización de métricas clave como RMSE, ganancias esperadas y riesgos.
La selección final ayuda a optimizar la decisión de apertura de 200 pozos de petróleo para maximizar las ganancias y minimizar los riesgos.

Estructura del Repositorio
optimización_pozos_petroleros_modelos_bootstrapping.ipynb: Notebook principal con el análisis, entrenamiento de modelos y visualizaciones.
README.md: Archivo de documentación del proyecto.
.gitignore: Archivo que define los archivos y carpetas ignorados por Git.
Metodología
Exploración de Datos: Limpieza y análisis de las características de cada región.
Entrenamiento de Modelos: Uso de regresión lineal para predecir la producción de los pozos.
Evaluación de Métricas: Comparación de RMSE, ganancias y riesgos entre regiones.
Visualización: Gráficas de ganancias esperadas, intervalos de confianza y riesgos.
Selección Final: Identificación de la mejor región basándose en métricas de rendimiento.
Tecnologías Utilizadas
Python: Lenguaje principal.
Pandas: Manipulación y análisis de datos.
NumPy: Operaciones matemáticas y estadísticas.
Matplotlib: Visualización de datos.
Scikit-learn: Entrenamiento y evaluación de modelos predictivos.
Resultados Principales
La Región 0 fue seleccionada como la mejor opción, con una ganancia esperada de $39,960,488.77 y riesgo de pérdida del 0.0%.
Comparación de regiones:
Región 0: Ganancia alta y bajo riesgo.
Región 1: Menor ganancia, aunque con menor RMSE.
Región 2: Ganancia intermedia con mayor RMSE.
Cómo Ejecutar el Proyecto
Clonar el repositorio:
bash
Copiar
Editar
git clone https://github.com/jose-alberto-hurtado/Optimizacion-Pozos-Petroleros.git
Instalar las dependencias necesarias:
bash
Copiar
Editar
pip install -r requirements.txt
Abrir el archivo optimización_pozos_petroleros_modelos_bootstrapping.ipynb en Jupyter Notebook o JupyterLab.
Ejecutar las celdas paso a paso para replicar el análisis.
Autor
José Alberto Hurtado Echeverría
Científico de datos en formación.

LinkedIn
GitHub

