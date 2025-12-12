# 📊 Proyecto: Análisis de ventas de videojuegos y planificación de campaña 2017

## 📖 Descripción:
Trabajé con datos abiertos de reseñas (usuarios y críticos), géneros, plataformas y ventas históricas para identificar patrones que determinan el éxito comercial de videojuegos. El objetivo fue detectar títulos y plataformas prometedoras y planificar campañas publicitarias para 2017, usando información hasta 2016 y buenas prácticas de análisis reproducible.

## 🎯 Objetivo: 
Identificar patrones de éxito en ventas de videojuegos usando datos hasta 2016 y planificar campañas 2017.

## 💡 Enfoque:
Limpieza y análisis de datos, correlación ventas–reseñas, segmentación regional, y pruebas de hipótesis para decisiones de marketing.

---
## 📂 Datos
- Ruta: games.csv
- Variables: Name, Platform, Year_of_Release, Genre, NA_sales, EU_sales, JP_sales, Other_sales, Critic_Score, User_Score, Rating.
- Preparación:
- Normalización: columnas en minúsculas.
- Conversión: tipos adecuados para fechas y numéricos.
- Ausentes: tratamiento justificado (incluye “TBD”).
- Nueva columna: total_sales = NA + EU + JP + Other.
---
## 🔎 Metodología
- Periodo relevante: Selección basada en estabilidad de plataformas y consistencia de ventas.
- Plataformas: Tendencias, líderes y declive; boxplots de ventas globales por plataforma.
- Reseñas: Dispersión y correlación entre critic_score/user_score y ventas en una plataforma elegida; comparación cross-platform.
- Géneros: Distribución y rentabilidad por género.
- Regiones (NA, EU, JP): Top 5 plataformas y géneros; efecto de ESRB en ventas.
- Hipótesis:
  - H0/HA: Xbox One vs PC (medias de user_score).
  - H0/HA: Acción v.s Deportes (medias de user_score).
- Prueba y α: Criterio estadístico y umbral definidos en el notebook.
---
## 📈 Resultados y conclusiones
- Hallazgos clave: Plataformas y géneros prometedores; impacto de reseñas; diferencias regionales.
- Recomendaciones: Foco de campaña por región, plataformas a priorizar, géneros a impulsar.
- Limitaciones: Posibles incompletos en 2016; sesgos por disponibilidad de reseñas.
---
## 🛠️ Tecnologías
- Lenguajes: Python (Pandas, NumPy, SciPy), SQL.
- Visualización: Matplotlib, Seaborn.
- Entorno: Jupyter Notebook / VS Code.
---
## 📋 Uso
- Abrir notebook: Formato con celdas Markdown y código; encabezados y explicaciones.
- Ejecutar análisis: Seguir secciones del notebook en orden (datos → EDA → regiones → hipótesis → conclusiones).
---
## 📧 Contacto
- Autor: Sebastian Vera Morales
- LinkedIn: [www.linkedin.com/in/sebastian-vera-morales]
- Correo: [sebastianvera4997@gmail.com]
