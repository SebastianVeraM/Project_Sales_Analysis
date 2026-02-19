# 📊 Proyecto: Análisis de ventas de videojuegos y planificación de campaña 2017

Trabajé con datos abiertos de reseñas (usuarios y críticos), géneros, plataformas y ventas históricas para identificar patrones que explicaron el éxito comercial de los videojuegos. El objetivo fue detectar títulos y plataformas prometedoras y diseñar estrategias publicitarias para 2017, utilizando información disponible hasta 2016. Todo el análisis se desarrolló aplicando buenas prácticas de programación, asegurando resultados claros, trazables y útiles para la toma de decisiones.

## 🎯 Objetivo: 
Identificar patrones de éxito en ventas de videojuegos usando datos hasta 2016 para planificar campañas de marketing del 2017.

## 💡 Enfoque:
Limpieza y análisis de datos, correlación ventas–reseñas, segmentación regional, y pruebas de hipótesis para decisiones de marketing.

## 📂 Datos
- Archivo: `games.csv` (No incluido por temas de licencia)
- Variables: `Name`, `Platform`, `Year_of_Release`, `Genre`, `NA_sales`, `EU_sales`, `JP_sales`, `Other_sales`, `Critic_Score`, `User_Score`, `Rating`.


## 🔎 Metodología
- Preparación:
  - Unificar el formarto de las columnas a letras minúsculas.
  - Conversión a tipos adecuados para fechas y datos numéricos.
  - Manipulación y tratamiento justificado de valores ausentes.
  - Generación de información a partir de información dada.
- Análisis: 
  - Tendencias, líderes y declive de plataformas.
  - Top 5 plataformas y géneros; efecto de ESRB en ventas de acuerdo a las regiones (NA, EU, JP).
  - Selección de plataformas más adecuadas con base en su estabilidad y consistencia de ventas.
- Test de Hipótesis:
  - H0/HA: Comparación de calificaciones de usuarios para plataformas Xbox One y PC.
  - H0/HA: Comparación de calificaciones de usuarios para juegos de Acción y Deportes.

## 📈 Resultados y conclusiones
- Hallazgos clave: Plataformas y géneros prometedores; impacto de reseñas; diferencias regionales.
- Recomendaciones: Foco de campaña por región, plataformas a priorizar, géneros a impulsar.
- Limitaciones: Posibles datos incompletos en 2016; sesgos por disponibilidad de reseñas.

## 🛠️ Tecnologías
- Lenguajes: Python. 
- Librerías: (Pandas, NumPy, SciPy, Functools).
- Visualización: Matplotlib.
- Entorno: Jupyter Notebook / VS Code.

## 📋 Uso
- Abrir el jupyter notebook y seguir el flujo del proyecto tal y como está ordenado, yendo desde el apartado de **Descripción** hasta el apartado de **Conclusiones**.

## 📧 Contacto
Para cualquier duda, aclaración, recomendación o sugerencia por favor contactar a:

- Autor: Sebastian Vera Morales
- LinkedIn: [www.linkedin.com/in/sebastian-vera-morales]
- Correo: [sebastianvera4997@gmail.com]