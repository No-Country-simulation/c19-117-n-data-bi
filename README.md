# c19-117-n-data-bi

# Project: Vehicle Insurance Claim

## Project Summary
El proyecto se centra en la detección de fraude en seguros de vehículos, utilizando un conjunto de datos real proporcionado por Oracle, proveniente de una aseguradora en Estados Unidos. El fraude en seguros de vehículos incluye prácticas como la presentación de reclamos falsos o exagerados relacionados con daños materiales o lesiones personales tras un accidente.

## link de acceso a presentacion en tableu

https://public.tableau.com/app/profile/juan.felipe116/viz/ProjectVehicleInsuraceClaimNoCountry/Story1?publish=yes

## link de acceso de entorno colab

https://colab.research.google.com/drive/1xPsdH56G_hoi9MMGB2pSl6rKMC69PhzC#scrollTo=0CFH-bWL5_6V

### Definición del problema de negocio

### Main Goal
El objetivo principal del proyecto es desarrollar y evaluar métodos de detección de fraude en reclamos de seguros de vehículos utilizando técnicas de ciencia de datos. La intención es identificar patrones fraudulentos en los datos proporcionados por una aseguradora de Estados Unidos para reducir las pérdidas financieras causadas por reclamos falsos o exagerados.

### Question to be Resolved 
El problema a resolver es la identificación de reclamos fraudulentos en seguros de vehículos. El fraude en seguros de vehículos es una práctica común que implica la presentación de reclamos falsos o exagerados por daños a la propiedad o lesiones personales tras un accidente. Este tipo de fraude puede incluir accidentes simulados, el uso de pasajeros fantasma y reclamos exagerados por lesiones personales.

### Habilidades y Herramientas Necesarias
- **Lenguajes de Programación:** Python para análisis de datos y machine learning.
- **Bibliotecas y Frameworks:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn para el análisis y visualización de datos.
- **Herramientas de Visualización:** Tableau, u otras herramientas de visualización de datos.
- **Bases de Datos:** SQL para la consulta y manipulación de datos.
- **Conocimientos de Estadística:** Fundamentos de estadística y probabilidad.
- **Comunicación:** Habilidades para comunicar resultados complejos de manera clara y concisa tanto a audiencias técnicas como no técnicas.

### Entregables Específicos del Proyecto
1. ✅Informes de Análisis Exploratorio de Datos (EDA) Documento 1
2. ✅Modelos de Machine Learning entrenados y evaluados Documento 2
3. ✅Métricas de Evaluación y Matrices de Confusión Documento 3
4. ✅Reportes de Importancia de Características y SHAP Values Documento 4
5. ✅Documentación Detallada del Proceso Documento 5 / ipnyb
6. ✅Informes y Presentaciones Ejecutivas/ Dashboard

### Context
El proyecto utiliza un conjunto de datos real proporcionado por Oracle, originario de una aseguradora en Estados Unidos. Estos datos han sido liberados con fines educativos y contienen información relevante para la detección de fraude en seguros de vehículos. El contexto del estudio implica entender las prácticas comunes de fraude y aplicar técnicas de análisis de datos y algoritmos de machine learning para identificar patrones que indiquen posibles actividades fraudulentas.

## Objetivos y métricas de desempeño

### Goal
#### Success Criteria
**Mejorar la Precisión en la Detección de Fraude**

Uno de los objetivos principales del proyecto es mejorar la precisión en la detección de reclamos de seguros fraudulentos. Identificar correctamente los reclamos fraudulentos ayudará a la compañía de seguros a minimizar las pérdidas financieras y garantizar que los reclamantes legítimos sean compensados adecuadamente.

- **Precisión:** La proporción de reclamos fraudulentos correctamente identificados sobre el total de reclamos identificados como fraudulentos. Una alta precisión indica una baja tasa de falsos positivos.
- **Recall (Sensibilidad):** La proporción de reclamos fraudulentos correctamente identificados sobre el total de reclamos realmente fraudulentos. Un alto recall indica una baja tasa de falsos negativos.
- **F1 Score:** La media armónica de precisión y recall, proporcionando una métrica única que equilibra tanto los falsos positivos como los falsos negativos.

**Identificar las Características Más Relevantes para la Detección de Fraude**

Otro objetivo es identificar y comprender las características más importantes que contribuyen a la detección de fraude. Esto no solo ayuda a mejorar la precisión del modelo, sino que también proporciona información valiosa a los analistas de fraude sobre los factores que más influyen en la identificación de actividades fraudulentas.

- **Importancia de las Características:** Evaluar la importancia de las características utilizando técnicas como el análisis de importancia de características de los modelos de árboles (por ejemplo, Random Forest) o métodos de eliminación secuencial.
- **SHAP Values (Shapley Additive Explanations):** Utilizar SHAP values para obtener una comprensión detallada del impacto de cada característica en las predicciones del modelo.
- **Reducción de la Dimensionalidad:** Evaluar la precisión del modelo después de reducir el número de características utilizando técnicas como PCA (Análisis de Componentes Principales) o selección de características, para verificar que el modelo se mantenga preciso con un conjunto de características más pequeño y relevante.

### Constraints

#### Timeline
El proyecto debe completarse en 3 semanas.

#### Budget
El presupuesto total es de \$ 0 US

### Stakeholders

- **Manage Closely (High Interest, High Power)**
  - Pablo Roblesh,Pablo López S16-11-N-Python-React (TL), Facility Manager

## Requerimientos Funcionales

### Requerimientos Funcionales Específicos para un Analista de Datos

1. **Ingesta y Preprocesamiento de Datos**
   - **Carga de Datos:** Utilizar herramientas y técnicas para cargar y leer el conjunto de datos proporcionado.
   - **Limpieza de Datos:** Aplicar métodos para eliminar o imputar valores faltantes, corregir errores y manejar datos duplicados.
   - **Transformación de Datos:** Convertir variables categóricas a numéricas, normalizar y escalar características según sea necesario.

2. **Análisis Exploratorio de Datos (EDA)**
   - **Visualización de Datos:** Crear gráficos y visualizaciones para entender la distribución de los datos, relaciones entre variables y detectar posibles patrones de fraude.
   - **Estadísticas Descriptivas:** Calcular estadísticas descriptivas básicas (media, mediana, desviación estándar, etc.) para resumir las características de los datos.

3. **Modelado y Entrenamiento**
   - **Selección de Características:** Identificar y seleccionar las características más relevantes para la detección de fraude.
   - **Entrenamiento del Modelo:** Implementar y entrenar algoritmos de machine learning (e.g., árboles de decisión, regresión logística) para identificar el fraude.
   - **Validación Cruzada:** Utilizar técnicas de validación cruzada para evaluar la robustez del modelo.
   - **Optimización de Hiperparámetros:** Ajustar los hiperparámetros de los modelos para mejorar el rendimiento.

4. **Evaluación del Modelo**
   - **Métricas de Evaluación:** Calcular y reportar métricas clave como precisión, recall, F1 score y AUC-ROC para evaluar la efectividad del modelo.
   - **Confusion Matrix:** Generar matrices de confusión para analizar el rendimiento del modelo en términos de verdaderos positivos, falsos positivos, verdaderos negativos y falsos negativos.

5. **Interpretabilidad y Explicabilidad del Modelo**
   - **SHAP Values:** Implementar explicaciones de SHAP para interpretar el impacto de cada característica en las predicciones del modelo.
   - **Reportes de Importancia de Características:** Generar reportes que indiquen las características más importantes y su contribución a la detección de fraude.

6. **Documentación y Comunicación**
   - **Documentación del Proceso:** Mantener una documentación detallada del proceso de análisis, desde la ingesta de datos hasta la evaluación del modelo.
   - **Informes y Presentaciones:** Preparar informes y presentaciones que resuman los hallazgos del análisis y los resultados del modelo.

