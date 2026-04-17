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
