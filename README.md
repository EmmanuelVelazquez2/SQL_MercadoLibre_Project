# SQL_MercadoLibre_Project
# Análisis de Retención de Usuarios - Mercado Libre Project

## Objetivo del Proyecto
Este análisis se centró en medir la fidelización de usuarios a través del tiempo, utilizando SQL para segmentar a los clientes por mes de registro (cohortes) y por ubicación geográfica (país). Se monitoreó el comportamiento en intervalos de 7, 14, 21 y 28 días tras el registro inicial.

## Metodología
Utilicé **SQL** para segmentar y contabilizar usuarios activos en intervalos críticos de tiempo (D7, D14, D21 y D28) tras su registro inicial.

### Herramientas utilizadas:
**SQL**: Consultas avanzadas con `COUNT(DISTINCT CASE WHEN...)` para segmentación dinámica.
**Plataforma**: Análisis ejecutado como parte del **Bootcamp de TripleTen**

## Resultados y Insights
Hallazgo: Existe una caída drástica en la retención para todas las cohortes al llegar al día 28, descendiendo de un promedio del 25% en el día 21 a apenas un 2-3% en el día 28. 
La cohorte de agosto muestra el desempeño más bajo de todo el año, con una retención en el día 7 del 70.8%, comparada con el promedio habitual de 86% de otros meses.
México (86.1%) y Brasil (87.2%) presentan los niveles más altos de retención inicial (D7), y México mantiene el liderazgo en retención a largo plazo en el día 28 con un 3.1%.



