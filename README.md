# YouTube-Trending-Canada-Analysis

Proyecto de análisis de tendencias de videos en YouTube en Canadá, aplicando la metodología **CRISP-DM** para extraer insights sobre vistas, likes, dislikes y comentarios, y generar recomendaciones para campañas de marketing digital.

---

## Colaboradores

- Francesca Nicole Bances Torres (Data Analytics)  
- Marsi Valeria Figueroa Larragán (Data Science)  
- Mauricio Eduardo Vera Castellón (Data Engineer)  

---

## Objetivos

- Analizar tendencias por categoría, canal, región y horario.  
- Evaluar interacciones: vistas, likes, dislikes y comentarios.  
- Identificar patrones temporales y geográficos.  
- Construir modelos predictivos de métricas clave.  
- Generar recomendaciones estratégicas para marketing digital.

---

## Dataset

- **Fuente:** [Kaggle – Trending YouTube Video Statistics](https://www.kaggle.com/datasets/datasnaek/youtube-new)  
- **Registros:** 40,881 (24,427 únicos tras limpieza)  
- **Variables:** 20 (video_id, trending_date, title, channel_title, category_id, publish_time, tags, views, likes, dislikes, comment_count, thumbnail_link, comments_disabled, ratings_disabled, video_error_or_removed, description, state, lat, lon, geometry)

---

## Preprocesamiento

- Eliminación de duplicados y limpieza de datos  
- Selección de variables independientes: `likes`, `dislikes`, `comment_count`  
- Variable dependiente: `views`  
- Estandarización de valores numéricos  

---

## Análisis Exploratorio

- Categorías más populares: Entertainment, Music, Comedy  
- Mejor proporción Me gusta / No me gusta: Gaming  
- Mejor proporción Vistas / Comentarios: Shows  
- Horario de publicación más frecuente: 3pm – 4pm  
- Estados con más vistas: Quebec, New Brunswick, Northwest  

---

## Modelado

- **Técnica:** Regresión lineal múltiple  
- **División de datos:** 80% entrenamiento / 20% prueba  
- **Resultado:** Error alto debido a outliers, recomendando refinamiento del modelo y nuevas variables independientes  

---

## Conclusiones

- La categoría Entertainment domina en vistas y likes, clave para campañas de marketing.  
- Otras categorías importantes: Music, Comedy y Gaming según métricas específicas.  
- Publicaciones más efectivas en la tarde (3-4 pm).  
- Modelo predictivo necesita ajustes para manejar outliers y mejorar precisión.  

---

## Tecnologías

Python | Pandas | NumPy | scikit-learn | Matplotlib | Seaborn  


