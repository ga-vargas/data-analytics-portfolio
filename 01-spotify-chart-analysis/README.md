# Spotify Chart Analysis: What Separates a Top 10 Hit?

[Versión en español](#versión-en-español)

**Business question:** What characteristics differentiate songs that reach the Top 10 of the Spotify Global chart from those that never get past the Top 50?

## Data
Spotify Charts Global Weekly Top 200 (2025–2026). I combined 91 weekly files (18,398 rows), removed duplicates, and cleaned artist names, leaving **1,272 unique songs** and **826 artists**.

## Key findings
- **Chart success is not about the sound.** None of the audio features (danceability, energy, valence, tempo, loudness, acousticness) correlate with peak rank (all between -0.12 and +0.09).
- **The artist matters far more.** Taylor Swift (73%) and BTS (62%) have hit rates far above the 16.8% average. The top 20 artists make up 35% of songs but 44% of Top 10 hits.
- **Genre matters too.** Pop (28.7%) and K-Pop (28.6%) lead on Top 10 hit rate, while Regional Mexicano sits at 1.3%.
- Explicit content is slightly less common in hits (27%) than in minor hits (34%).

## Tools and methods
- **Excel:** COUNTIFS, SUMPRODUCT, AVERAGEIFS, CORREL, INDEX+MATCH, FILTER, IFERROR, TRIM, pivot table
- **Interactive lookup dashboard** to search any song or artist
- **Python (Pandas):** merging and cleaning the weekly files

## Files
- [`spotify_chart_analysis.xlsm`](spotify_chart_analysis.xlsm): full workbook with data, analysis, charts, and dashboard

---

# Versión en español

# Análisis de Spotify Charts: ¿Qué diferencia a un éxito del Top 10?

**Pregunta de negocio:** ¿Qué características diferencian a las canciones que llegan al Top 10 del ranking global de Spotify de las que nunca pasan del puesto 50?

## Datos
Spotify Charts, Top 200 semanal global (2025–2026). Combiné 91 archivos semanales (18.398 filas), eliminé duplicados y limpié los nombres de artistas, y quedaron **1.272 canciones únicas** y **826 artistas**.

## Hallazgos principales
- **El éxito en el ranking no depende del sonido.** Ninguna característica de audio (bailabilidad, energía, valencia, tempo, volumen, acústica) se correlaciona con la posición máxima alcanzada (todas entre -0,12 y +0,09).
- **El artista importa mucho más.** Taylor Swift (73%) y BTS (62%) tienen tasas de éxito muy por encima del promedio de 16,8%. Los 20 artistas principales concentran el 35% de las canciones, pero el 44% de los éxitos del Top 10.
- **El género también influye.** Pop (28,7%) y K-Pop (28,6%) lideran la tasa de éxito en el Top 10, mientras que Regional Mexicano llega solo al 1,3%.
- El contenido explícito es algo menos frecuente en los éxitos (27%) que en los éxitos menores (34%).

## Herramientas y métodos
- **Excel:** COUNTIFS, SUMPRODUCT, AVERAGEIFS, CORREL, INDEX+MATCH, FILTER, IFERROR, TRIM, tabla dinámica
- **Dashboard interactivo de búsqueda** para consultar cualquier canción o artista
- **Python (Pandas):** unión y limpieza de los archivos semanales

## Archivos
- [`spotify_chart_analysis.xlsm`](spotify_chart_analysis.xlsm): libro completo con datos, análisis, gráficos y dashboard
