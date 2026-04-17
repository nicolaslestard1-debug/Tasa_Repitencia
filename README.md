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


Año escolar	Region	Tasa
0	2019-2020	Cuyo	5.117033
1	2019-2020	Gran Buenos Aires	5.884256
2	2019-2020	Noreste	8.000258
3	2019-2020	Noroeste	8.090659
4	2019-2020	Pampeana	8.937025
5	2019-2020	Patagonia	6.030302
6	2020-2021	Cuyo	4.435219
7	2020-2021	Gran Buenos Aires	5.046505
8	2020-2021	Noreste	6.837618
9	2020-2021	Noroeste	6.651913
10	2020-2021	Pampeana	7.153849
11	2020-2021	Patagonia	5.896464
12	2021-2022	Cuyo	1.804511
13	2021-2022	Gran Buenos Aires	0.061426
14	2021-2022	Noreste	3.960710
15	2021-2022	Noroeste	2.839502
16	2021-2022	Pampeana	4.526335
17	2021-2022	Patagonia	2.126904
18	2022-2023	Cuyo	6.751448
19	2022-2023	Gran Buenos Aires	8.619813
20	2022-2023	Noreste	9.242594
21	2022-2023	Noroeste	8.794753
22	2022-2023	Pampeana	10.127377
23	2022-2023	Patagonia	7.026764
