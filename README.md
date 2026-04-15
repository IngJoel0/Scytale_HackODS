# Scytale

## Equipo
**Nombre del equipo:** Scytale

## Integrantes
- **Reyna Mayela Giles Vieyra:** Participó en la construcción y presentación del proyecto, con énfasis en la narrativa visual y la comunicación del análisis.
- **Joel Enrique Urquiza Martinez:** Colaboró en la organización del dashboard, la interpretación de datos y la integración de contenidos.
- **Johan Argenis Franco Rogel:** Apoyó en la estructuración técnica, la revisión del dashboard y la articulación de los hallazgos principales.

## ODS Elegidos
- **ODS 1:** Fin de la pobreza
- **ODS 4:** Educación de calidad
- **ODS 8:** Trabajo decente y crecimiento económico

## Descripción del Proyecto
Este proyecto presenta un dashboard interactivo en Quarto y Plotly que relaciona educación, pobreza, analfabetismo, acceso a idiomas, salario y seguridad social en México. A partir de distintos datasets por estado, el proyecto muestra cómo la educación influye directamente en las oportunidades de desarrollo y en la calidad de vida de la población.

---

## Contenidos de las Carpetas

### `data`
La carpeta `data` contiene los archivos de datos utilizados en el dashboard. Aquí se incluyen hojas de cálculo y archivos geográficos con información sobre analfabetismo, pobreza, educación, idiomas, salarios, seguridad social y la geometría de los estados de México.

#### Metadatos de los datos

##### `analfabetismo.xlsx`
- **Fuente:** Instituto Nacional de Estadística y Geografía (INEGI).
- **Fecha de descarga:** 14/03/2026.
- **Licencia:** Uso libre de la información pública del INEGI con cita de fuente.
- **Descripción de variables:** `Entidad federativa`, `Total`, `Analfabeta` y `Porcentaje`. El archivo resume la población de 15 años y más por entidad federativa según condición de alfabetismo en 2020.

##### `Educacion_04.xlsx`
- **Fuente:** Instituto Nacional de Estadística y Geografía (INEGI).
- **Fecha de descarga:** 01/04/2026.
- **Licencia:** Uso libre de la información pública del INEGI con cita de fuente.
- **Descripción de variables:** `Entidad federativa`, `Total`, `Licenciatura o equivalente` y `PORCENTAJE UNIVERSIDAD`. Se utilizó el porcentaje de población de 3 años y más con nivel de licenciatura o equivalente por entidad federativa.

##### `Hogares_15.xlsx`
- **Fuente:** Instituto Nacional de Estadística y Geografía (INEGI).
- **Fecha de descarga:** 22/03/2026.
- **Licencia:** Uso libre de la información pública del INEGI con cita de fuente.
- **Descripción de variables:** `Entidad federativa` y, para cada año `2016`, `2018`, `2020`, `2022` y `2024`, las columnas `Total`, `Pobreza moderada` y `Pobreza extrema`. El dashboard usa principalmente la serie de `Pobreza extrema` para comparar la evolución por estado.

##### `idiomas.xlsx`
- **Fuente:** Indicada en el archivo como `DGE. Tercer Censo de Población de los Estados Unidos Mexicanos 1910. Tabulados básicos`.
- **Fecha de descarga:** 22/03/2026.
- **Licencia:** DGE. Tercer Censo de Población de los Estados Unidos Mexicanos 1910. Tabulados básicos.
- **Descripción de variables:** `estado` y, para cada idioma (`Francés`, `Inglés`, `Italiano`), las columnas `Hombres`, `Mujeres` y `Total`. Se utilizó para construir el comparativo por entidad del total de personas que hablan cada idioma.

##### `pobreza (1).xlsx`
- **Fuente:** CONEVAL. El propio archivo indica que las estimaciones se elaboran con base en el `Módulo de Condiciones Socioeconómicas` y la `Encuesta Nacional de Ingresos y Gastos de los Hogares (ENIGH)`.
- **Fecha de descarga:** 22/03/2026.
- **Licencia:** Uso libre con cita de fuente, conforme a la difusión pública de datos de CONEVAL.
- **Descripción de variables:** `Entidad` y `Porcentaje de la población en situación de pobreza`. Se usó como indicador porcentual de pobreza por entidad federativa.

##### `salarios.xlsx`
- **Fuente:** No especificada de forma explícita dentro del archivo entregado.
- **Fecha de descarga:**01/04/2026.
- **Licencia:** Cifras actualizadas al primer trimestre de 2025 de la Encuesta Nacional de Ocupación y Empleo, STPS-INEGI
- **Descripción de variables:** `Entidad`, `Número de profesionistas ocupados`, `Ingreso promedio mensual`, `Hombres (%)` y `Mujeres (%)`. En el dashboard se utiliza principalmente `Ingreso promedio mensual` para relacionarlo con el porcentaje de educación universitaria.

##### `Seguro.xlsx`
- **Fuente:** Instituto Nacional de Estadística y Geografía (INEGI).
- **Fecha de descarga:** 01/04/2026.
- **Licencia:** Uso libre de la información pública del INEGI con cita de fuente.
- **Descripción de variables:** `Entidad federativa`, `Total afiliado a servicios`, `Total de su población` y `Porcentaje con servicios`. Se utilizó el porcentaje de población con afiliación a servicios de salud por estado.

##### `mexico_estados.geojson`
- **Fuente:** Archivo geográfico de trabajo basado en la división estatal de México para visualización cartográfica.
- **Fecha de descarga:** 14/03/2026.
- **Licencia:** Uso libre de la información pública del INEGI con cita de fuente.
- **Descripción de variables:** geometrías por entidad federativa y atributos de identificación estatal empleados para el mapa coroplético interactivo.

> Nota: cuando un archivo no incluye de forma visible su fuente o licencia dentro del propio recurso, se deja indicado expresamente para no atribuir metadatos no verificados.

### `imgs`
La carpeta `imgs` contiene las imágenes usadas en la presentación visual del proyecto. Aquí se encuentran la portada, ilustraciones, recursos de cierre del dashboard y materiales gráficos relacionados con los ODS seleccionados.
