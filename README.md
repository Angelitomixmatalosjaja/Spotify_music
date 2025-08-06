# Spotify_music
# 🎧 Análisis de Historial de Spotify

Este proyecto analiza el historial de reproducciones de un usuario de Spotify con el objetivo de identificar patrones de escucha, detectar los artistas y canciones más reproducidas, y predecir cuándo una canción será saltada utilizando machine learning.

## 📁 Archivos del Proyecto

- `spotify.ipynb`: Notebook con todo el análisis exploratorio, procesamiento, visualizaciones y modelo predictivo.
- `spotify_history.csv`: Dataset principal con el historial de reproducción.
- `spotify_data_dictionary Description.csv`: Diccionario de datos con descripciones de las columnas.

## 🧠 Herramientas y Librerías

- `Python`
- `pandas`, `numpy`
- `matplotlib`
- `scikit-learn`
- `imbalanced-learn`
- `Jupyter Notebook`

## 🧪 Qué se hizo

- Limpieza y preparación del dataset.
- Análisis exploratorio de datos (EDA).
- Visualización de canciones, artistas, plataformas y comportamiento de skip.
- Clasificación con `RandomForestClassifier` para predecir skips.
- Análisis de razones por las que se empieza o se termina una canción.

## 📊 Hallazgos Clave

- **Canción más escuchada:** *Ode To The Mets*  
- **Artista más escuchado:** *The Beatles* (13,621 reproducciones)
- **Plataforma más usada:** Android  
- **Años con más actividad:** 2016 en adelante, con un pico durante la pandemia (2020)

## 🤖 Modelo Predictivo

Se desarrolló un modelo para predecir si una canción será saltada.  
Resultados del modelo (Random Forest):
- **Accuracy general:** 61%
- **Recall para skips:** 99%
- **Precisión para no skips:** 100%

El modelo detecta eficazmente cuándo una canción será saltada, aunque es menos preciso en predecir las que se escuchan completas.

## 🧩 Reflexión Final

Este proyecto combina análisis real con datos personales, ofreciendo insights valiosos mientras se practican habilidades clave de ciencia de datos. Representa un avance sólido en el camino profesional hacia el análisis de datos.

---

📌 *Creado por [@Angelitomixmatalosjaja](https://github.com/Angelitomixmatalosjaja)*
