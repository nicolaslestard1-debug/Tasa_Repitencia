# Tasa_Repitencia
Este código de Python está diseñado para procesar y visualizar la Tasa de Repitencia en la educación secundaria argentina, automatizando la transición desde archivos Excel desestructurados hacia un análisis regional comparativo

📊 Procesamiento de Tasa de Repitencia (Serie 2019-2023)

Este script automatiza la captura y limpieza de datos provenientes de los datasets oficiales del Ministerio de Educación, permitiendo observar la evolución de la repitencia con un enfoque territorial.


Funcionalidades Principales:

Limpieza Inteligente: Implementa funciones de normalización de texto (norm_txt) y detección automática de años escolares dentro de las pestañas del Excel, manejando las inconsistencias de formato habituales en archivos públicos.


Mapeo Regional: Transforma datos a nivel de jurisdicción/provincia en las seis regiones estadísticas utilizadas por el INDEC (Cuyo, GBA, Noreste, Noroeste, Pampeana y Patagonia).


Normalización Numérica: Convierte y valida las tasas de repitencia, manejando errores de formato y valores nulos para garantizar la integridad del cálculo del promedio regional.
isualización de Tendencias: Genera automáticamente un gráfico de líneas que muestra el comportamiento de la repitencia. Esto permite identificar visualmente la caída "artificial" durante el período de unidad pedagógica (2020-2021) y el posterior rebote tras la vuelta a la presencialidad en 2022.


Stack Técnico:

Pandas: Para la estructuración y agregación de datos tipo tidy data.


Matplotlib & Seaborn: Para la creación de gráficos con consistencia visual y estética profesional.


Regex: Para la extracción de patrones temporales en los encabezados.

Este código fue fundamental para confirmar la hipótesis de que las políticas de excepcionalidad por la pandemia no resolvieron las brechas de aprendizaje, sino que las visibilizaron al retornar a los patrones estructurales previos

<img width="1665" height="825" alt="image" src="https://github.com/user-attachments/assets/b69fce14-88f5-45b9-a25e-4c26770b82ec" />


### 📊 Evolución de la Tasa de Repitencia por Región

| Año escolar | Región | Tasa de Repitencia (%) |
| :--- | :--- | :--- |
| 2019-2020 | Cuyo | 5.12 |
| 2019-2020 | Gran Buenos Aires | 5.88 |
| 2019-2020 | Noreste | 8.00 |
| 2019-2020 | Noroeste | 8.09 |
| 2019-2020 | Pampeana | 8.94 |
| 2019-2020 | Patagonia | 6.03 |
| 2020-2021 | Cuyo | 4.44 |
| 2020-2021 | Gran Buenos Aires | 5.05 |
| 2020-2021 | Noreste | 6.84 |
| 2020-2021 | Noroeste | 6.65 |
| 2020-2021 | Pampeana | 7.15 |
| 2020-2021 | Patagonia | 5.90 |
| 2021-2022 | Cuyo | 1.80 |
| 2021-2022 | Gran Buenos Aires | 0.06 |
| 2021-2022 | Noreste | 3.96 |
| 2021-2022 | Noroeste | 2.84 |
| 2021-2022 | Pampeana | 4.53 |
| 2021-2022 | Patagonia | 2.13 |
| 2022-2023 | Cuyo | 6.75 |
| 2022-2023 | Gran Buenos Aires | 8.62 |
| 2022-2023 | Noreste | 9.24 |
| 2022-2023 | Noroeste | 8.79 |
| 2022-2023 | Pampeana | 10.13 |
| 2022-2023 | Patagonia | 7.03 |
