# Workshop 1 Machine Learning - Análisis Exploratorio de Datos (Students Performance in Exams)

## Descripción del proyecto

Este proyecto presenta un **Análisis Exploratorio de Datos (EDA)** sobre el dataset **Students Performance in Exams**, con el propósito de identificar patrones relacionados con el desempeño académico de un grupo de estudiantes.

El análisis se desarrolla a través de un proceso dividido en cinco fases, que comprende desde la exploración y comprensión inicial de los datos hasta la identificación de patrones, visualización de resultados y formulación de preguntas para una futura etapa de Machine Learning.

El análisis se centra principalmente en las calificaciones obtenidas en:

* Matemáticas (`math score`)
* Lectura (`reading score`)
* Escritura (`writing score`)

y estudia su relación con diferentes variables categóricas, entre ellas:

* Género (`gender`)
* Grupo de raza/etnia (`race/ethnicity`)
* Nivel educativo de los padres (`parental level of education`)
* Tipo de almuerzo (`lunch`)
* Curso de preparación para el examen (`test preparation course`)

---

## Objetivo

Realizar un proceso completo de **Análisis Exploratorio de Datos (EDA)** que permita:

1. Comprender la estructura y composición del dataset.
2. Identificar los tipos de variables presentes.
3. Evaluar la calidad de los datos.
4. Detectar valores faltantes, duplicados e inconsistencias.
5. Analizar la distribución de las variables numéricas.
6. Identificar posibles valores atípicos.
7. Comparar el rendimiento académico entre diferentes grupos.
8. Analizar relaciones entre las variables numéricas.
9. Identificar patrones relevantes mediante visualizaciones.
10. Formular preguntas que puedan ser abordadas posteriormente mediante técnicas de Machine Learning.

---

## Dataset

El dataset utilizado corresponde a **Students Performance in Exams** y contiene información académica y sociodemográfica de **1.000 estudiantes**.

El conjunto de datos contiene **8 variables**:

| Variable                      | Tipo       | Descripción                                              |
| ----------------------------- | ---------- | -------------------------------------------------------- |
| `gender`                      | Categórica | Género del estudiante                                    |
| `race/ethnicity`              | Categórica | Grupo de raza/etnia                                      |
| `parental level of education` | Categórica | Nivel educativo de los padres                            |
| `lunch`                       | Categórica | Categoría correspondiente al almuerzo                    |
| `test preparation course`     | Categórica | Indica si el estudiante completó el curso de preparación |
| `math score`                  | Numérica   | Puntaje obtenido en matemáticas                          |
| `reading score`               | Numérica   | Puntaje obtenido en lectura                              |
| `writing score`               | Numérica   | Puntaje obtenido en escritura                            |

Las tres variables de calificación utilizan una escala de **0 a 100**.

---

## Tecnologías y herramientas

El análisis fue desarrollado utilizando **Python** y un entorno de Notebook.

Principales herramientas utilizadas:

* **Python**
* **Pandas** — manipulación y análisis de datos.
* **NumPy** — operaciones numéricas.
* **Matplotlib** — generación de visualizaciones.
* **Seaborn** — visualización estadística.
* **Jupyter Notebook** — desarrollo y presentación del análisis.

---

## Estructura del proyecto

La estructura del entregable se organiza de la siguiente manera:

```text
|
├── README.md
├── workshop1.ipynb
└── data/
    └── StudentsPerformance.csv
```

### Archivos principales

**`README.md`**

Documento principal del proyecto. Presenta la descripción, metodología, resultados y conclusiones generales.

**`workshop1.ipynb`**

Notebook que contiene el desarrollo completo del Análisis Exploratorio de Datos, incluyendo código, resultados, tablas, gráficos y conclusiones correspondientes a las cinco fases.

**`StudentsPerformance.csv`**

Dataset utilizado como fuente de información para el análisis.

---

# Metodología

El análisis se desarrolló en cinco fases.

## Fase 1 — Exploración inicial
## Fase 2 — Calidad y limpieza de los datos
## Fase 3 — Análisis estadístico y relaciones entre variables
## Fase 4 — Visualización
## Fase 5 — Conclusiones

---

# Visualización resumen

Como síntesis de los principales resultados se construyó un subplot de dimensiones **2 × 2**, compuesto por:

1. Distribución del nivel educativo de los padres.
2. Distribución de los puntajes de matemáticas.
3. Relación entre matemáticas y lectura.
4. Puntaje total según el curso de preparación.

Estos cuatro gráficos permiten resumir visualmente los principales patrones identificados durante el EDA.

---

# Proyección hacia Machine Learning

Los resultados obtenidos permiten plantear una futura etapa de Machine Learning.

Algunas preguntas que podrían investigarse son:

* ¿Qué variables presentan mayor capacidad predictiva sobre el desempeño académico?
* ¿Es posible identificar estudiantes con riesgo de obtener bajos resultados?
* ¿El curso de preparación mantiene su importancia cuando se consideran simultáneamente las demás variables?
* ¿Qué combinación de variables permite realizar predicciones más precisas?
* ¿Qué factores presentan mayor relación con el desempeño académico?

---

# Cómo ejecutar el proyecto

## 1. Clonar el repositorio

```bash
git clone https://github.com/Salazar1022/machine-learning-workshop-1.git
```

## 2. Ingresar al directorio

```bash
cd machine-learning-workshop-1
```

## 3. Instalar las dependencias

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## 4. Ejecutar el Notebook

Abrir Jupyter Notebook:

```bash
jupyter notebook
```

Posteriormente, abrir:

```text
workshop1.ipynb
```

y ejecutar las celdas en orden.

Es importante ejecutar las fases secuencialmente, ya que algunas variables creadas durante el análisis, como `total_score`, son utilizadas posteriormente.

---

# Reproducibilidad

Para reproducir el análisis se recomienda:

1. Mantener el archivo `StudentsPerformance.csv` en la ubicación esperada por el Notebook.
2. Ejecutar las celdas del Notebook en orden.
3. No modificar los datos originales antes de ejecutar el análisis.
4. Utilizar las mismas versiones o versiones compatibles de las bibliotecas utilizadas.
5. Verificar que el entorno tenga instaladas las dependencias requeridas.

---

## Autores

**Andres Velez**
**Nathalia Cardoza**
**Samuel Samper**
**Sebastian Salazar**
