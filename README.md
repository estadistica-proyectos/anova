# Anova: Ánalisis de Varianza.

## Introducción
- Link: https://github.com/estadistica-proyectos/anova.git
- Integrantes del grupo: Alejandro Martínez; Claudia López; Frank Llonch; María González.

## Repositorio
El archivo `main.py` contiene un Jupyter Notebook programado en Python para la resolución de análisis de varianza, ANOVA. A continuación, se proporciona una breve descripción y las librerías utilizadas en el código:

#### **Descripción**
Resuelve ejercicios relacionados con análisis de varianza utilizando Python. El análisis de varianza es una técnica estadística utilizada para comparar las medias de más de dos muestras. Este código aborda este tipo de análisis y proporciona soluciones utilizando las funciones y métodos de las librerías mencionadas.

#### **Librerías Utilizadas**
El código hace uso de las siguientes librerías de Python:

- `pandas`: Utilizada para la manipulación y análisis de datos tabulares.
- `numpy`: Proporciona funciones para realizar operaciones numéricas eficientes.
- `scipy.stats`: Utilizada para realizar análisis estadísticos, en este caso, se utiliza para acceder a la tabla Snedecor, que es comúnmente utilizada en análisis de varianza.
- `matplotlib.pyplot`: Se emplea para la generación de gráficos y visualización de datos.

Se deben de tener estas librerías instaladas antes de ejecutar el código. Se indica como instalarlas en caso de no tenerlas.

#### **Instrucciones de Uso**
1. Abre el archivo `main.py` en un entorno de Jupyter Notebook o en tu entorno de desarrollo preferido.
2. Instalar las librerías en caso de no tenerlas.
3. Ejecutar el código.

## Enunciado
El calcio es un mineral esencial que regula el corazón, es importante para la coagulación de la sangre y para la formación de huesos sanos. La Fundación Nacional de Osteoporosis, FNO, recomienda una ingesta diaria de calcio de 1000 a 1200 mg/día para hombres y mujeres adultos. Si bien algunos alimentos contienen calculo, la mayoría de los adultos no obtienen suficiente calcio en sus dietas y toman suplementos. Lamentablemente, algunos de los suplementos tienen efectos secundarios, como malestar gástrico, lo que dificulta que algunos pacientes los puedan tomar de forma regular. </br>

Se ha diseñado un estudio para comprobar si existe una diferencia en la ingesta media diaria de calcio en adultos con densidad ósea normal, adultos con osteopenia (una densidad baja que puede provocar osteoporosis) y adultos con osteoporosis. Se seleccionan al azar adultos de 60 años con densidad ósea normal, osteopenia y osteoporosis de los registros hospitalarios y se les invita a participar en el estudio. La ingesta diaria de calcio de cada participante se mide en función de la ingesta de alimentos y suplementos informados. Los datos se muestran a continuación.

| Densidad ósea normal | Osteopenia | Osteoporosis |
|-----------------------|------------ |--------------|
| 1200                  |1000         | 890          |
| 1000                  |1100         | 650          |
| 980                   |700          | 1100         |
| 900                   |800          | 900          |
| 750                   |500          | 400          |
| 800                   |700          | 350          |

