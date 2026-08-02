#  Análisis de tickets de Mercadona

Proyecto de la asignatura **Tratamiento de Datos** — Grado en Ciencia de Datos, Universitat de València.

Análisis de más de 100 tickets electrónicos de Mercadona (recibidos en PDF) para extraer patrones de consumo y comportamiento de compra.

##  Objetivo

Extraer y analizar la información contenida en tickets electrónicos de Mercadona para responder preguntas como:
- ¿Cuáles son los productos más vendidos (por unidades y por categoría)?
- ¿A qué horas del día hay más afluencia de compra?
- ¿Qué productos se compran juntos con más frecuencia (ventas cruzadas)?
- ¿Cuánto se gasta de media por compra?

##  Tecnologías

- **R** (R Markdown)
- `tidyverse`, `dplyr`, `tidyr`, `purrr` — manipulación de datos
- `lubridate` — tratamiento de fechas
- `arules` — reglas de asociación / análisis de ventas cruzadas (market basket analysis)
- `hrbrthemes`, `ggplot2`, `scales` — visualización
- `gt`, `flextable`, `officer` — tablas

##  Proceso

1. **Extracción**: los tickets en PDF se convierten a texto plano (.txt).
2. **Estructuración**: se generan dos tablas de trabajo — `df.ticket` (datos generales de cada ticket) y `df.productos` (productos comprados y su precio).
3. **Análisis y visualización**: se responden las preguntas propuestas mediante gráficos y tablas resumen.
4. **Reglas de asociación**: se aplica `arules` para detectar qué productos se compran juntos con más frecuencia.

##  Resultado

El informe completo con todos los gráficos, tablas y conclusiones está disponible en `ProyectoTD2025.html` / `ProyectoTD2025.pdf`, junto con la presentación del proyecto.

##  Nota sobre los datos

Los tickets originales (carpeta `data/`) contienen información personal de compra (fechas, importes, establecimiento) y no se incluyen completos en este repositorio por privacidad.

##  Equipo

Proyecto realizado para la asignatura Tratamiento de Datos


##  Contacto

David Puertes Santonja — Estudiante de Ciencia de Datos, Universitat de València
[LinkedIn](https://www.linkedin.com/in/) · [Email](mailto:davidpuertes5@gmail.com)
