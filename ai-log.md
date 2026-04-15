# AI Log - Equipo Scytale

## Herramientas
- Codex / ChatGPT

## Filosofía de uso
Decidimos usar IA únicamente como apoyo técnico para resolver tareas mecánicas, acelerar prototipos de visualización y destrabar detalles de implementación en Quarto y Plotly. La narrativa del dashboard, la selección de variables, la relación entre los ODS 1, 4 y 8, y la interpretación de los datos fueron decisiones del equipo. Nuestro criterio fue simple: si la tarea implicaba juicio analítico, contexto del proyecto o construcción del mensaje, la resolvíamos nosotros.

## Registro de uso

### 2026-03-22 | Codex / ChatGPT | Mapa interactivo de analfabetismo
- **Tarea**: Apoyar en la construcción del mapa coroplético de la República Mexicana con base en el dataset `data/analfabetismo.xlsx`.
- **Prompt**: "Necesito un mapa interactivo de la república mexicana con Plotly en Quarto que muestre el porcentaje de analfabetismo por estado."
- **Resultado**: Se generó la lógica base para leer el archivo, normalizar nombres de estados, enlazar el dataset con un archivo geográfico y renderizar el mapa con Plotly.
- **Decisión**: El equipo conservó la selección del indicador, la narrativa que acompaña la visualización y la forma en la que el mapa se integró a la historia del dashboard.

### 2026-03-22 | Codex / ChatGPT | Archivo geográfico `mexico_estados.geojson`
- **Tarea**: Apoyar en la incorporación de un archivo geográfico local para poder renderizar el mapa estatal de México sin depender de HTML externo.
- **Prompt**: "Integra un geojson local de los estados de México para usarlo con Plotly dentro de Quarto."
- **Resultado**: Se añadió y adaptó un archivo `geojson` de trabajo para la visualización cartográfica, incluyendo el ajuste de identificadores para cruzarlo correctamente con los estados del dataset.
- **Decisión**: La IA solo ayudó en la parte técnica de integración. El uso del mapa, el criterio de visualización y su interpretación dentro del proyecto fueron definidos por el equipo.

### 2026-04-01 | Codex / ChatGPT | Ajustes de diseño y maquetación
- **Tarea**: Resolver detalles de distribución visual, responsividad y organización de las secciones en Quarto.
- **Prompt**: "Haz que los elementos se distribuyan mejor en pantalla, usa todo el ancho disponible y mantén el estilo visual del dashboard."
- **Resultado**: Se propusieron y aplicaron ajustes sobre `styles.css` y `index.qmd` para mejorar el acomodo de tarjetas, gráficas, textos e imágenes en distintas resoluciones.
- **Decisión**: La línea visual, la intención estética y la estructura narrativa del dashboard fueron decididas por el equipo; la IA se usó únicamente como apoyo para implementar esos cambios más rápido.

## NO usamos IA para hacer lo siguiente
- La selección de los indicadores y datasets principales del proyecto.
- La relación conceptual entre los ODS 1, 4 y 8.
- La narrativa del dashboard y la construcción del hilo de Sor Juana Inés de la Cruz.
- La interpretación de los resultados por estado.
- La redacción final del argumento del proyecto y su enfoque temático.
