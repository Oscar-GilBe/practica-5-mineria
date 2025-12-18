# Visualización Web: K-Medias

Este directorio contiene la visualización web interactiva de los resultados del Ejercicio 2.

## Archivos

- **visualizacion_kmeans.html**: Página web principal con las gráficas interactivas
- **datos_kmeans.json**: Datos exportados desde R

## Características de la visualización

### Menú principal

- 4 opciones de visualización:
  - Aeropuerto origen
  - Aeropuerto destino
  - Aerolínea
  - Modelo de avión

### Gráficas interactivas

- **Eje X**: Índice de la entidad
- **Eje Y**: Retraso medio (minutos)
- **Colores**:
  - 🟢 Verde: Retraso bajo
  - 🟡 Amarillo: Retraso moderado
  - 🔴 Rojo: Retraso alto

### Interactividad

- **Hover**: Al pasar el ratón sobre un punto, se muestra:
  - Nombre de la entidad
  - Valor del retraso medio
  - Grupo al que pertenece
- **Zoom**: Usa las herramientas de Plotly
- **Pan**: Arrastra para moverte por el gráfico
- **Reset**: Botón para volver a la vista original

### Estadísticas

Cada visualización incluye:

- Total de entidades analizadas
- Retraso promedio, máximo y mínimo
- Cantidad de entidades en cada grupo (bajo, moderado, alto)

## Tecnologías utilizadas

- **Plotly.js**: Librería de gráficos interactivos
- **HTML5/CSS3**: Estructura y diseño responsivo
- **JavaScript**: Lógica de interacción y carga de datos
- **JSON**: Formato de intercambio de datos entre R y web
