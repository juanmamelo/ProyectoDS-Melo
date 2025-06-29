
# 🏋️‍♀️📈 Análisis de Seguimiento de Ejercicios en Gimnasios

Este repositorio contiene el proyecto final de la materia **Data Science I**. El objetivo es analizar los datos de seguimiento de ejercicios de los miembros de un gimnasio para comprender mejor los factores que influyen en el rendimiento físico y en los resultados de salud.

---

## 📌 Abstract

El dataset `gym_members_exercise_tracking.csv`, obtenido de Kaggle, contiene 15 variables relacionadas con la actividad física, entre ellas:

- Edad
- Género
- Peso y altura
- Duración de los entrenamientos
- Calorías quemadas
- Tipo y frecuencia del entrenamiento
- Nivel de experiencia

Se exploraron relaciones entre variables para responder preguntas como:

- ¿Qué tipo de entrenamiento quema más calorías?
- ¿Qué duración es más común?
- ¿Existe correlación entre duración, experiencia y calorías?

---

## 🎯 Objetivos del proyecto

- Realizar análisis exploratorio (EDA) y limpieza del dataset
- Visualizar relaciones entre variables clave
- Interpretar patrones de entrenamiento en diferentes perfiles

---

## 📈 Herramientas y tecnologías utilizadas

- Python 3.x
- `pandas`, `numpy` para manejo de datos
- `matplotlib`, `seaborn` para visualización
- `scikit-learn` para futuros modelos predictivos

---

## 🗃️ Estructura del proyecto

```
ProyectoDS-Melo/
├── gym_members_exercise_tracking.csv   # Dataset original
├── ProyectoDS+Melo.ipynb               # Análisis completo en notebook
├── README.md                           # Este archivo
```

---

## 📊 Ejemplo de análisis

```python
# Comparar calorías quemadas según tipo de entrenamiento
sns.boxplot(data=gym_data, x='tipo_entrenamiento', y='calorias_quemadas')
plt.title('Calorías quemadas por tipo de entrenamiento')
plt.xticks(rotation=45)
plt.show()
```

---

## 🧑‍💻 Autor

Juan Manuel Melo  
🔗 [LinkedIn](https://www.linkedin.com/in/juan-manuel-melo95/)  
📧 juanmanuelmelo95@gmail.com

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Ver el archivo `LICENSE` para más detalles.
