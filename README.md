# Grupo 14 - Proyecto DS

Miembros:

 - Martínez, Alam / Ingeniero de Petróleos
 - Ulloa, Gabriel / Upstream
 - Quinteros, Julián Ezequiel / Ingeniero de Petróleos

Proyecto:

Datos de producción de petróleo y gas en los Estados Unidos. El objetivo es desarrollar un modelo predictivo sobre la producción de O&G, tanto onshore como offshore

- Tabla: 470830 líneas y 11 columnas
- Datos nulos: varios en State, County, FIPS Code (similar a CP), y offshore region.
- Dropeamos las columnas County y FIPS Code ya que consideramos que sería un análisis demasiado fino; aquellos datos que no tengan el dato State se le coloca "sin datos"; aquellas regiones que sean onshore, se le coloca "onshore" en la columna Offshore Región para eliminar los valores null.
