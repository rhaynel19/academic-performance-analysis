Descripción

Este proyecto realiza un análisis completo del rendimiento académico de estudiantes utilizando herramientas de Ciencia de Datos y Machine Learning.
Incluye limpieza de datos, análisis exploratorio, ingeniería de variables, escalamiento, codificación y entrenamiento de modelos predictivos.

🎯 Objetivo del Proyecto

Identificar los factores que influyen en que un estudiante apruebe o no apruebe, y construir modelos que permitan predecir este resultado con un nivel adecuado de exactitud.

🧠 Tecnologías Utilizadas

Python 3

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Jupyter Notebook

📁 Estructura del Proyecto
proyecto-rendimiento-academico/
│── data/                  # Dataset utilizado (si aplica)
│── notebooks/             # Jupyter Notebook con el análisis y los modelos
│── src/                   # Scripts de código Python
│── images/                # Gráficos generados
│── README.md              # Documentación del proyecto
│── requirements.txt       # Librerías necesarias
│── .gitignore             # Archivos ignorados por Git

📊 Proceso Realizado
1️⃣ Limpieza de Datos

Manejo de valores faltantes

Verificación de tipos de datos

Corrección de inconsistencias

2️⃣ Análisis Exploratorio (EDA)

Distribución de las variables

Visualización de relaciones

Identificación de tendencias

3️⃣ Ingeniería de Características

Creación de la variable binaria:

1 = Aprobado

0 = No aprobado

Transformación de variables categóricas con LabelEncoder

Escalamiento con StandardScaler

4️⃣ Divisiones de Datos

70% entrenamiento

30% prueba

🤖 Modelos Entrenados
🔹 Regresión Logística

Exactitud: 0.78

Buén desempeño prediciendo Aprobados.

Desempeño limitado en No aprobados.

🔹 Árbol de Decisión

Exactitud: 0.75

Alta precisión en la predicción de Aprobados.

Baja capacidad de identificar No aprobados.

(Puedes agregar Random Forest si lo incluyes más adelante.)

📈 Resultados Generales
Modelo	Exactitud
Regresión Logística	0.78
Árbol de Decisión	0.75
🚀 Cómo Ejecutar Este Proyecto
1. Clonar el repositorio:
git clone https://github.com/tu-usuario/proyecto-rendimiento-academico.git

2. Instalar dependencias:
pip install -r requirements.txt

3. Ejecutar el notebook:
jupyter notebook

👨‍💻 Autor

Fraimel Trinidad
Lic en administracion | Analista de Datos | Entusiasta de la Ciencia de Datos

🤝 Contribuciones

Cualquier sugerencia o mejora es bienvenida.
