# 🎓 Predicción del Rendimiento Estudiantil con Inteligencia Artificial

Este repositorio contiene los archivos del proyecto final del curso de Inteligencia Artificial (Universidad Jorge Tadeo Lozano), cuyo objetivo es aplicar técnicas de aprendizaje automático para predecir el rendimiento académico de estudiantes a partir de datos educativos.

## 📋 Tabla de Contenidos

- [Entregables incluidos](#-entregables-incluidos)
- [Descripción del proyecto](#-descripción-del-proyecto)
- [Estructura del repositorio](#-estructura-del-repositorio)
- [Dataset utilizado](#-dataset-utilizado)
- [Instalación y requisitos](#-instalación-y-requisitos)
- [Uso del código](#-uso-del-código)
- [Metodología implementada](#-metodología-implementada)
- [Modelos implementados](#-modelos-implementados)
- [Evaluación y métricas](#-evaluación-y-métricas)
- [Resultados principales](#-resultados-principales)
- [Consideraciones éticas](#-consideraciones-éticas)
- [Integrantes del equipo](#-integrantes-del-equipo)
- [Licencia](#-licencia)

## 📄 Entregables incluidos

### Documentación académica
- ✅ **PDF final del paper**: `PROYECTO INTELIGENCIA ARTIFICIAL - PREDICCION DEL RENDIMIENTO ESTUDIANTIL.pdf`
- ✅ **Archivo fuente en LaTeX**: `PROYECTO_INTELIGENCIA_ARTIFICIAL.tex`
- ✅ **Archivo de bibliografía BibTeX**: `referencias.bib`

### Implementación y datos
- ✅ **Notebook Jupyter**: Implementación completa del proyecto con análisis exploratorio, preprocesamiento, entrenamiento y evaluación de modelos
- ✅ **Datasets CSV**: 
  - `student-mat.csv` - Datos de estudiantes de matemáticas
  - `student-por.csv` - Datos de estudiantes de portugués
- ✅ **Archivo LICENSE**: Licencia MIT

## 🧠 Descripción del proyecto

El objetivo del proyecto es desarrollar un modelo de clasificación supervisada capaz de predecir si un estudiante universitario tendrá un **rendimiento académico alto (nota ≥ 10) o bajo (nota < 10)**, utilizando un conjunto completo de variables:

### Variables analizadas (33 atributos)

**📊 Rendimiento académico:**
- G1: Nota del primer período
- G2: Nota del segundo período
- G3: Nota final (variable objetivo)

**📚 Factores académicos:**
- Horas de estudio semanal
- Número de ausencias
- Reprobaciones previas
- Apoyo académico escolar y familiar
- Clases particulares pagadas

**👨‍👩‍👧‍👦 Contexto familiar:**
- Educación de los padres (Medu, Fedu)
- Trabajo de los padres (Mjob, Fjob)
- Calidad de relaciones familiares
- Tamaño de la familia
- Estado civil de los padres

**🌐 Factores sociales y personales:**
- Edad y género
- Tiempo de viaje a clases
- Acceso a internet
- Actividades extracurriculares
- Tiempo libre y frecuencia de salidas
- Consumo de alcohol (entre semana y fin de semana)
- Estado de salud
- Relación romántica

## 📂 Estructura del repositorio
ProyectoIA/
│
├── 📄 PROYECTO INTELIGENCIA ARTIFICIAL - PREDICCION DEL RENDIMIENTO ESTUDIANTIL.pdf
├── 📄 PROYECTO_INTELIGENCIA_ARTIFICIAL.tex
├── 📄 referencias.bib
│
├── 📓 Notebooks
│   ├── exploracion_datos.ipynb          # Análisis exploratorio completo
│   └── modelo_prediccion.ipynb          # Entrenamiento y evaluación de modelos
│
├── 📊 Datasets
│   ├── student-mat.csv                  # Dataset de matemáticas (395 estudiantes)
│   └── student-por.csv                  # Dataset de portugués (649 estudiantes)
│
├── 📋 LICENSE
└── 📋 README.md

## 🗃️ Dataset utilizado

- **Nombre**: Student Performance Dataset  
- **Fuente**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Student+Performance)
- **Formato**: CSV (separado por punto y coma)
- **Dataset utilizado**: Matemáticas (`student-mat.csv`)
- **Registros**: 395 estudiantes  
- **Variables**: 33 atributos (30 predictores + 3 calificaciones)
- **Licencia**: Uso público para investigación
- **Clases**: 
  - **Bajo rendimiento**: G3 < 10 (nota final menor a 10)
  - **Alto rendimiento**: G3 ≥ 10 (nota final mayor o igual a 10)

### Distribución de clases
El dataset presenta un desbalance natural que refleja la realidad educativa:
- **Bajo rendimiento**: ~33% de los estudiantes
- **Alto rendimiento**: ~67% de los estudiantes

## 💻 Instalación y requisitos

### Requisitos previos

- Python 3.8 o superior
- Jupyter Notebook / JupyterLab / Google Colab
- pip (gestor de paquetes de Python)

### Librerías necesarias
```bash
Perfecto, ahora que veo el código completo del notebook, te voy a crear un README mucho más detallado y preciso. Aquí está:
markdown# 🎓 Predicción del Rendimiento Estudiantil con Inteligencia Artificial

Este repositorio contiene los archivos del proyecto final del curso de Inteligencia Artificial (Universidad Jorge Tadeo Lozano), cuyo objetivo es aplicar técnicas de aprendizaje automático para predecir el rendimiento académico de estudiantes a partir de datos educativos.

## 📋 Tabla de Contenidos

- [Entregables incluidos](#-entregables-incluidos)
- [Descripción del proyecto](#-descripción-del-proyecto)
- [Estructura del repositorio](#-estructura-del-repositorio)
- [Dataset utilizado](#-dataset-utilizado)
- [Instalación y requisitos](#-instalación-y-requisitos)
- [Uso del código](#-uso-del-código)
- [Metodología implementada](#-metodología-implementada)
- [Modelos implementados](#-modelos-implementados)
- [Evaluación y métricas](#-evaluación-y-métricas)
- [Resultados principales](#-resultados-principales)
- [Consideraciones éticas](#-consideraciones-éticas)
- [Integrantes del equipo](#-integrantes-del-equipo)
- [Licencia](#-licencia)

## 📄 Entregables incluidos

### Documentación académica
- ✅ **PDF final del paper**: `PROYECTO INTELIGENCIA ARTIFICIAL - PREDICCION DEL RENDIMIENTO ESTUDIANTIL.pdf`
- ✅ **Archivo fuente en LaTeX**: `PROYECTO_INTELIGENCIA_ARTIFICIAL.tex`
- ✅ **Archivo de bibliografía BibTeX**: `referencias.bib`

### Implementación y datos
- ✅ **Notebook Jupyter**: Implementación completa del proyecto con análisis exploratorio, preprocesamiento, entrenamiento y evaluación de modelos
- ✅ **Datasets CSV**: 
  - `student-mat.csv` - Datos de estudiantes de matemáticas
  - `student-por.csv` - Datos de estudiantes de portugués
- ✅ **Archivo LICENSE**: Licencia MIT

## 🧠 Descripción del proyecto

El objetivo del proyecto es desarrollar un modelo de clasificación supervisada capaz de predecir si un estudiante universitario tendrá un **rendimiento académico alto (nota ≥ 10) o bajo (nota < 10)**, utilizando un conjunto completo de variables:

### Variables analizadas (33 atributos)

**📊 Rendimiento académico:**
- G1: Nota del primer período
- G2: Nota del segundo período
- G3: Nota final (variable objetivo)

**📚 Factores académicos:**
- Horas de estudio semanal
- Número de ausencias
- Reprobaciones previas
- Apoyo académico escolar y familiar
- Clases particulares pagadas

**👨‍👩‍👧‍👦 Contexto familiar:**
- Educación de los padres (Medu, Fedu)
- Trabajo de los padres (Mjob, Fjob)
- Calidad de relaciones familiares
- Tamaño de la familia
- Estado civil de los padres

**🌐 Factores sociales y personales:**
- Edad y género
- Tiempo de viaje a clases
- Acceso a internet
- Actividades extracurriculares
- Tiempo libre y frecuencia de salidas
- Consumo de alcohol (entre semana y fin de semana)
- Estado de salud
- Relación romántica

## 📂 Estructura del repositorio
```
ProyectoIA/
│
├── 📄 PROYECTO INTELIGENCIA ARTIFICIAL - PREDICCION DEL RENDIMIENTO ESTUDIANTIL.pdf
├── 📄 PROYECTO_INTELIGENCIA_ARTIFICIAL.tex
├── 📄 referencias.bib
│
├── 📓 Notebooks
│   ├── exploracion_datos.ipynb          # Análisis exploratorio completo
│   └── modelo_prediccion.ipynb          # Entrenamiento y evaluación de modelos
│
├── 📊 Datasets
│   ├── student-mat.csv                  # Dataset de matemáticas (395 estudiantes)
│   └── student-por.csv                  # Dataset de portugués (649 estudiantes)
│
├── 📋 LICENSE
└── 📋 README.md
```

## 🗃️ Dataset utilizado

- **Nombre**: Student Performance Dataset  
- **Fuente**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Student+Performance)
- **Formato**: CSV (separado por punto y coma)
- **Dataset utilizado**: Matemáticas (`student-mat.csv`)
- **Registros**: 395 estudiantes  
- **Variables**: 33 atributos (30 predictores + 3 calificaciones)
- **Licencia**: Uso público para investigación
- **Clases**: 
  - **Bajo rendimiento**: G3 < 10 (nota final menor a 10)
  - **Alto rendimiento**: G3 ≥ 10 (nota final mayor o igual a 10)

### Distribución de clases
El dataset presenta un desbalance natural que refleja la realidad educativa:
- **Bajo rendimiento**: ~33% de los estudiantes
- **Alto rendimiento**: ~67% de los estudiantes

## 💻 Instalación y requisitos

### Requisitos previos

- Python 3.8 o superior
- Jupyter Notebook / JupyterLab / Google Colab
- pip (gestor de paquetes de Python)

### Librerías necesarias
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### Lista completa de dependencias
```python
pandas          # Manipulación de datos
numpy           # Operaciones numéricas
matplotlib      # Visualizaciones
seaborn         # Visualizaciones estadísticas
scikit-learn    # Modelos de machine learning y métricas
```

## 🚀 Uso del código

### 1. Clonar el repositorio
```bash
git clone https://github.com/Santiageoff/ProyectoIA.git
cd ProyectoIA
```

### 2. Ejecutar el análisis exploratorio

El notebook de exploración incluye:
- Carga y visualización inicial de datos
- Detección de valores nulos y duplicados
- Análisis estadístico descriptivo
- Visualizaciones de distribuciones
- Matriz de correlación entre variables
- Análisis de relaciones con la variable objetivo
```bash
jupyter notebook exploracion_datos.ipynb
```

### 3. Ejecutar el modelo de predicción

El notebook principal ejecuta el pipeline completo:
- Preprocesamiento de datos
- Codificación de variables categóricas
- División train/test (80/20)
- Entrenamiento de 3 modelos
- Evaluación comparativa
- Visualizaciones de resultados
```bash
jupyter notebook modelo_prediccion.ipynb
```

### 4. Estructura del código

#### **Fase 1: Exploración de Datos**
- Carga del dataset de matemáticas
- Análisis de 6 variables clave: `studytime`, `failures`, `absences`, `G1`, `G2`, `G3`
- Creación de variable objetivo binaria (`rendimiento`)
- Visualizaciones: histogramas, boxplots, scatter plots
- Matriz de correlación de variables numéricas

#### **Fase 2: Preprocesamiento**
- Codificación de 17 variables categóricas con LabelEncoder
- Selección de 32 features (15 numéricas + 17 categóricas)
- División estratificada 80% entrenamiento / 20% prueba
- Diccionario de traducción español para interpretabilidad

#### **Fase 3: Modelado**
- **Modelo Base**: DummyClassifier (predicción por frecuencia)
- **Árbol de Decisión**: max_depth=3, min_samples_split=30, min_samples_leaf=15
- **Regresión Logística**: max_iter=1000, solver por defecto

#### **Fase 4: Evaluación**
- Métricas: Accuracy, Precision, Recall, F1-Score
- Matrices de confusión visualizadas
- Curvas ROC y cálculo de AUC
- Comparación visual de todos los modelos

#### **Fase 5: Interpretabilidad**
- Importancia de características del árbol de decisión
- Clasificación por categorías temáticas
- Visualización del árbol completo en español
- Top 15 factores más influyentes

## ⚙️ Modelos implementados

### 1. 🎯 Modelo Base (Baseline)
- **Tipo**: DummyClassifier
- **Estrategia**: Predicción por clase más frecuente
- **Propósito**: Establecer línea base de comparación
- **Rendimiento esperado**: ~67% (proporción de clase mayoritaria)

### 2. 🌳 Árbol de Decisión
- **Algoritmo**: DecisionTreeClassifier
- **Hiperparámetros**:
  - Profundidad máxima: 3 niveles
  - Mínimo de muestras para dividir: 30
  - Mínimo de muestras por hoja: 15
- **Ventajas**: 
  - Alta interpretabilidad
  - Visualización gráfica del proceso de decisión
  - Identificación de variables clave
- **Salidas adicionales**:
  - Importancia de características (feature importance)
  - Árbol visualizado con etiquetas en español

### 3. 📈 Regresión Logística
- **Algoritmo**: LogisticRegression
- **Hiperparámetros**:
  - Iteraciones máximas: 1000
  - Random state: 42 (reproducibilidad)
- **Ventajas**:
  - Probabilidades calibradas
  - Eficiencia computacional
  - Robustez con múltiples variables

## 📈 Evaluación y métricas

### Metodología de evaluación

- **División de datos**: 80% entrenamiento (316 estudiantes) / 20% prueba (79 estudiantes)
- **Estratificación**: Mantiene proporción de clases en train/test
- **Random state**: 42 (garantiza reproducibilidad)
- **Validación**: Hold-out simple (apropiado para el tamaño del dataset)

### Métricas calculadas

| Métrica | Descripción | Interpretación |
|---------|-------------|----------------|
| **Accuracy** | Proporción de predicciones correctas | ¿Qué porcentaje total acierta el modelo? |
| **Precision** | Proporción de positivos correctos | De los que predice alto, ¿cuántos son realmente altos? |
| **Recall** | Proporción de positivos detectados | De los realmente altos, ¿cuántos detecta el modelo? |
| **F1-Score** | Media armónica de precisión y recall | Balance entre precisión y cobertura |
| **AUC-ROC** | Área bajo la curva ROC | Capacidad de discriminación del modelo |

### Visualizaciones generadas

1. **Matrices de confusión** para los 3 modelos (comparación lado a lado)
2. **Gráfico de barras** comparativo de las 4 métricas principales
3. **Curvas ROC** con AUC para Árbol y Regresión Logística
4. **Gráfico de importancia** de características (top 15)
5. **Árbol de decisión completo** visualizado con etiquetas en español

## 📊 Resultados principales

### Variables más influyentes (Top 5)

Según el análisis de importancia de características del árbol de decisión:

1. **📝 G2 (Nota 2do Corte)**: Mayor predictor (~60-70% de peso)
2. **📝 G1 (Nota 1er Corte)**: Segundo predictor más importante (~15-20%)
3. **❌ Reprobaciones Previas**: Indicador crítico de riesgo académico
4. **🚫 Número de Ausencias**: Factor de riesgo significativo
5. **⏰ Horas de Estudio Semanal**: Influencia moderada positiva

### Categorización de factores

**🔴 Impacto Alto (>10%):**
- Calificaciones de períodos anteriores (G1, G2)

**🟠 Impacto Medio (5-10%):**
- Historial académico (reprobaciones, ausencias)
- Tiempo de estudio

**🔵 Impacto Bajo (<5%):**
- Factores familiares y socioeconómicos
- Variables demográficas
- Factores de estilo de vida

### Correlaciones clave

- **G2 ↔ G3**: r ≈ 0.90 (correlación muy alta)
- **G1 ↔ G3**: r ≈ 0.80 (correlación alta)
- **failures ↔ G3**: Correlación negativa moderada

### Rendimiento de modelos

Los resultados específicos se encuentran en el notebook, pero el objetivo es superar:
- **Baseline**: ~67% accuracy (predicción por frecuencia)
- **Objetivo**: >80% accuracy
- **Mejor modelo**: Comparación entre Árbol y Regresión Logística

### Interpretación del árbol de decisión

El árbol visualizado muestra:
- **Nodo raíz**: Primera división por G2 (nota del segundo corte)
- **Ramas izquierdas**: Estudiantes en riesgo (notas bajas en G2)
- **Ramas derechas**: Estudiantes con buen rendimiento
- **Colores**: 
  - 🟧 Naranja = Predicción de bajo rendimiento
  - 🟦 Azul = Predicción de alto rendimiento
  - Intensidad = Confianza de la predicción

## ⚖️ Consideraciones éticas

Este proyecto se ha desarrollado teniendo en cuenta los siguientes principios éticos:

### ✅ Principios aplicados

- **Uso académico**: Este modelo es exclusivamente para fines de investigación y aprendizaje
- **No discriminación**: Se han analizado y documentado posibles sesgos por género, edad y condición socioeconómica
- **Transparencia**: Todo el código, datos y metodología están disponibles públicamente
- **Privacidad**: El dataset original ya está anonimizado (sin nombres ni identificadores personales)
- **Responsabilidad**: Los resultados NO deben usarse para tomar decisiones reales sobre estudiantes

### ⚠️ Limitaciones y advertencias

1. **No es un sistema de toma de decisiones**: Los modelos son herramientas de análisis, no reemplazan el juicio de educadores
2. **Sesgo de datos**: El modelo refleja patrones históricos que pueden contener sesgos sistémicos
3. **Contexto limitado**: Solo considera 33 variables; muchos factores educativos no están representados
4. **Generalización**: Entrenado con datos de dos escuelas portuguesas; puede no generalizarse a otros contextos
5. **Profecía autocumplida**: Etiquetar estudiantes como "bajo rendimiento" podría afectar sus oportunidades

### 🎯 Uso responsable

Este proyecto debe utilizarse para:
- ✅ Identificar patrones y factores de riesgo a nivel poblacional
- ✅ Generar hipótesis para investigación educativa
- ✅ Diseñar intervenciones preventivas generales
- ✅ Aprender sobre técnicas de machine learning

**NO** debe utilizarse para:
- ❌ Tomar decisiones individuales sobre estudiantes
- ❌ Asignar recursos de forma automatizada
- ❌ Etiquetar o estigmatizar estudiantes
- ❌ Reemplazar la evaluación profesional de educadores

## 👥 Integrantes del equipo

| Nombre | Correo electrónico |
|--------|-------------------|
| **Santiago Martínez Beltrán** | santiago.martinezb@utadeo.edu.co |
| **Sergio Daniel Aza Ocampo** | Sergiod.azaocampo@utadeo.edu.co |
| **Julián Santiago Hernández González** | julians.hernandezg@utadeo.edu.co |

**Universidad**: Jorge Tadeo Lozano  
**Curso**: Inteligencia Artificial  
**Año**: 2025  
**Profesor**: [Jorge Ivan Romero Gelvez]

## 📚 Referencias

- **Dataset**: Cortez, P. & Silva, A. (2008). *Using Data Mining to Predict Secondary School Student Performance*. UCI Machine Learning Repository.
- **Documentación**: Ver archivo `referencias.bib` para bibliografía completa en formato BibTeX

## 📜 Licencia

Este proyecto se distribuye bajo la **Licencia MIT**. Consulta el archivo [LICENSE](LICENSE) para más información.
```
MIT License - Copyright (c) 2025
Santiago Martínez, Sergio Aza, Julián Hernández
```

## 🔄 Reproducibilidad

Para garantizar la reproducibilidad de los resultados:
- ✅ Random state fijado en 42 para todas las operaciones aleatorias
- ✅ División train/test estratificada con mismo random state
- ✅ Versiones de librerías documentadas
- ✅ Código comentado y estructurado en secciones claras

## 📞 Contacto y contribuciones

Para preguntas, sugerencias o colaboraciones, contacta a cualquiera de los integrantes del equipo a través de los correos institucionales listados arriba.

---

<div align="center">

**⭐ Si este proyecto te resulta útil para tu investigación o aprendizaje, considera darle una estrella en GitHub ⭐**

*Desarrollado con 🧠 y ☕ para el curso de Inteligencia Artificial - UJTL 2025*

</div>
