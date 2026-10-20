# Screen Time, Sleep and Adolescent Depression

[Versión en español](#versión-en-español)

**Business question:** How do screen time and sleep quality affect adolescent depression risk, and what should schools and health organizations do about it?

## Data
Public dataset from a peer-reviewed study (Hökby et al., 2025, *PLOS Global Public Health*): **4,810 adolescents** with screen time, sleep measures, and depression scores (BDI-II, 0–63). I checked for missing values and duplicate IDs and reviewed outliers.

## Key findings
- **Screen time alone barely predicts depression.** It explains about 1% of the variation in scores.
- **Sleep quality is the strongest predictor.** It explains 14.5%, roughly 13 times more than screen time. 50% of poor sleepers fall in the clinical range vs. 9% of good sleepers.
- **High screen time plus poor sleep flags a high-risk group:** 61 adolescents with 2.3x higher depression scores (16.3 vs. 7.2) and 1.5 fewer hours of sleep. 77% are girls.

## Recommendations
1. Screen for sleep quality in school check-ups.
2. Focus on difficulty falling asleep and early waking, the sleep problems most linked to depression.
3. Use high screen time plus poor sleep as a triage flag.

## Tools and methods
- **Interactive Excel dashboard:** 4 slicers, 4 VBA macros (clear filters, show at-risk group, timestamp, export to PDF), conditional formatting, 13 charts
- **Statistics in Excel:** CORREL, RSQ, SLOPE/INTERCEPT, STDEV.S, CONFIDENCE.NORM, PERCENTILE, COUNTIFS, AVERAGEIFS, nested IF
- **PowerPoint** presentation with business recommendations

## Files
- [`adolescent_depression_presentation.pdf`](adolescent_depression_presentation.pdf): 7-slide presentation
- [`adolescent_depression_dashboard.xlsm`](adolescent_depression_dashboard.xlsm): full workbook and interactive dashboard

---

# Versión en español

# Tiempo de pantalla, sueño y depresión adolescente

**Pregunta de negocio:** ¿Cómo afectan el tiempo de pantalla y la calidad del sueño al riesgo de depresión en adolescentes, y qué deberían hacer las escuelas y las organizaciones de salud?

## Datos
Dataset público de un estudio con revisión por pares (Hökby et al., 2025, *PLOS Global Public Health*): **4.810 adolescentes** con datos de tiempo de pantalla, sueño y puntaje de depresión (BDI-II, 0–63). Verifiqué valores faltantes e IDs duplicados y revisé los valores extremos.

## Hallazgos principales
- **El tiempo de pantalla por sí solo casi no predice la depresión.** Explica alrededor del 1% de la variación en los puntajes.
- **La calidad del sueño es el predictor más fuerte.** Explica el 14,5%, unas 13 veces más que el tiempo de pantalla. El 50% de quienes duermen mal está en rango clínico, contra el 9% de quienes duermen bien.
- **Mucho tiempo de pantalla más mal sueño marca un grupo de alto riesgo:** 61 adolescentes con puntajes de depresión 2,3 veces más altos (16,3 vs. 7,2) y 1,5 horas menos de sueño. El 77% son chicas.

## Recomendaciones
1. Evaluar la calidad del sueño en los controles escolares.
2. Poner el foco en la dificultad para dormirse y el despertar temprano, los problemas de sueño más ligados a la depresión.
3. Usar mucho tiempo de pantalla más mal sueño como señal de triage.

## Herramientas y métodos
- **Dashboard interactivo en Excel:** 4 segmentadores, 4 macros en VBA (borrar filtros, mostrar grupo en riesgo, marca de tiempo, exportar a PDF), formato condicional, 13 gráficos
- **Estadística en Excel:** CORREL, RSQ, SLOPE/INTERCEPT, STDEV.S, CONFIDENCE.NORM, PERCENTILE, COUNTIFS, AVERAGEIFS, IF anidados
- **Presentación en PowerPoint** con recomendaciones de negocio

## Archivos
- [`adolescent_depression_presentation.pdf`](adolescent_depression_presentation.pdf): presentación de 7 diapositivas
- [`adolescent_depression_dashboard.xlsm`](adolescent_depression_dashboard.xlsm): libro completo y dashboard interactivo
