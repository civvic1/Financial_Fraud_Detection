# Financial_Fraud_Detection
Desarrollo de un modelo de machine learning que pueda distinguir de manera precisa entre transacciones legítimas y fraudulentas, estableciendo así un estándar de seguridad en el sector financiero móvil global.

# 💸Financial Fraud detection📊


![](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)![](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)![](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)![](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

## Objetivo 📋

La urgencia por detectar fraudes en transacciones móviles de dinero ha llevado a una empresa del segmento Fintech a buscar soluciones innovadoras.

### **Preguntas** ❓

1. Preprocesamiento de Datos: Realizar limpieza de datos, manejar valores faltantes, codificación de variables categóricas y normalización/escalado de datos. 📉

2. Exploración de Datos: Analizar y comprender el conjunto de datos proporcionado, identificar variables llaves y realizar visualizaciones para entender las relaciones entre las variables y seleccionar las características relevantes. 📊

3. Construcción de Modelos: Experimentar con algunos algoritmos de machine learning como Regresión Logística, Árboles de Decisión, Random Forest, Naive Bayes, entre otros. ⚙️

4. Evaluación y Selección del Modelo: Evaluar los modelos utilizando métricas como precisión, recall, área bajo la curva ROC, y F1-score. Seleccionar el modelo con el mejor rendimiento para la detección de transacciones bancarias fraudulentas. 💻 


#  **Preguntas y respuestas** ❔

## **Pregunta 1: Preprocesamiento de Datos 📋

- Realizamos la limpieza de datos manejando valores faltantes, nulos, etc

- Utilizamos la técnica de one-hot encoding para pasar los valores de la columna type_1 y type_2 a nuevas columnas 

![boxplot](https://github.com/GabrielChavezC/Store_Sales_Analysis_SQL/assets/155968191/ae861238-c44d-4bc4-a1d2-fff80c74b073)


## **Pregunta 2: Análisis Exploratório (EDA) 📖 

- En nuestro box plot de step tenemos outliers pero esto corresponde a los horarios de mayor frecuencia en el fraude.

- Mientras que el Histograma de la amount podemos observar un marcado sesgo a la derecha. No sigue una distribución normal.

![boxplot](https://github.com/GabrielChavezC/Store_Sales_Analysis_SQL/assets/155968191/ae861238-c44d-4bc4-a1d2-fff80c74b073)


## **Pregunta 3: Construcción de Modelos ⚙️

- Tenemos en cuenta la matriz de confusión para entender mejor las métricas a utilizar.

- Discernimos el tipo de Naive Bayes que más convenga para su predicción. En este caso el tipo ha sido multinomial.

![boxplot](https://github.com/GabrielChavezC/Store_Sales_Analysis_SQL/assets/155968191/ae861238-c44d-4bc4-a1d2-fff80c74b073)

## **Pregunta 4: Evaluación y selección del modelo 📊

- Utilizamos distintas métricas para observar su funcionamiento

- Creamos la gráfica que nos permite ver cuál es el modelo con mejor desempeño.

![boxplot](https://github.com/GabrielChavezC/Store_Sales_Analysis_SQL/assets/155968191/ae861238-c44d-4bc4-a1d2-fff80c74b073)


# Conclusión 💯
+ El análisis de los datos revela importantes insights sobre el negocio que pueden guiar estratégicamente las decisiones para paliar el fraude.
+ Se identificó la métrica maás relevante, lo cual permite enfocar esfuerzos en esta dirección.
+ Para mejorar la exactitud, se recomienda profundizar en las distintas técnicas para disminuir el tiempo de computación cuando se haga el análisis para el big data. Así como la atención que se le ha de otorgar
  a las horas de mayor previsión de posible fraude🌟📊📝

# Creadores del proyecto: 💻

- **Elvis Donayre** 
- **Alexangel** 
- **Víctor Carracedo**

## Agradecimientos especiales:

- **Alejandro Gamarra:** Instructor del Bootcamp. 📝🎓
