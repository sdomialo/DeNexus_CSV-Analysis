# DeNexus: Limpieza de CSVs.

Este proyecto se centra en la limpieza de archivos CSV, utilizando Jupyter Notebooks (.ipynb) para documentar y ejecutar el proceso en cada rama del repositorio. Cada notebook es nombrado en mayúsculas con la convención `NOMBRE_DEL_CSV_clean`, donde `NOMBRE_DEL_CSV` corresponde al archivo original.

## Estructura del Proyecto.

1. **Entrada de Datos**: Los archivos CSV de entrada están organizados en la carpeta `data`.
2. **Salida de Datos**: Los archivos resultantes de la limpieza se almacenan en la misma carpeta `data`, con el sufijo `_clean` añadido al nombre original.

## Organización.

Cada archivo `CSV` será analizado en una rama independiente, la cual llevará el nombre del archivo correspondiente. El proceso de trabajo será el siguiente:

1. El especialista de ML analizará el archivo `CSV` en su respectiva rama.
2. Al finalizar, notificará al encargado de matemáticas de que el análisis está listo para revisión.
3. El encargado de matemáticas revisará el análisis, realizará las correcciones si es necesario, y notificará al especialista de `ML` sobre los cambios realizados y las cosas que deberá de hacer posteriormente.

Ambos podrán solicitar ayuda entre sí en cualquier momento para aclarar o resolver dudas.

**Importante:** En cada rama se incluye un notebook correspondiente en la carpeta `resources`, elaborado inicialmente por el equipo de matemáticas como apoyo. Es necesario crear un nuevo notebook para el desarrollo del proyecto, documentando cada paso con comentarios claros en celdas de tipo Markdown.

## Integrantes.
A continuación se indican los integrantes que participaron en la limpieza de cada archivo CSV:

1. **CISSM.csv**: Guillermo Hita, Gerardo Cuerva, Nacho Sánchez y María González.
2. **CYBER INCIDENTS MASTER.csv**: Ignacio Herrero, Jose Maria Hernandez, Alejandro Serrano y María González.
3. **EUROREPO.csv**: Daniel Bolaños, Jacobo Calviño y María González.
4. **HACKMAGEDDON.csv**: Adrián González, Claudia López y María González.
5. **ICSSTRIVE.csv**: Alejandra Cervantes, Sara Domínguez, Frank Llonch, Jose Antonio Sánchez y María González.
6. **KONBRIEFING.csv**: Emily Aguilar, María Isabel Serrano, Lucia Cantos y María González.
7. **TISAFE.csv**: Ouidad Hakimi, Andrea Carmona, Claudia López, Martina García y María González.
8. **WATERFALL.csv**: Ouidad Hakimi, Noa Baoting, Alejandro Martínez y María González.

Cada integrante fue responsable de la limpieza de su respectivo archivo, documentando el proceso en un notebook específico.

## Metodología
Para el desarrollo de este proyecto, utilizaremos la metodología CRISP-DM (Cross-Industry Standard Process for Data Mining), que guiará nuestro enfoque en la limpieza de datos y el análisis. La metodología se compone de las siguientes fases:

1. **Comprensión del Negocio**:
Definir los objetivos del proyecto y los requisitos desde la perspectiva del negocio, asegurando que la limpieza de datos esté alineada con las metas de la organización.

2. **Comprensión de los Datos**:
Familiarizarse con los datos en los archivos CSV, identificar problemas potenciales y realizar un análisis inicial para obtener una visión general de los datos disponibles.

3. **Preparación de los Datos**:
Limpiar, transformar y estructurar los datos para que sean aptos para el análisis. Esta fase incluye la estandarización de formatos, la gestión de valores ausentes y la eliminación de duplicados.

4. **Modelado**:
(Opcional según el alcance del proyecto) Seleccionar y aplicar técnicas de modelado adecuadas si es necesario para el análisis exploratorio, asegurando que los datos estén en el formato requerido.

5. **Evaluación**:
Revisar los resultados del proceso de limpieza para verificar si cumplen con los objetivos definidos en la fase de comprensión del negocio. Esta evaluación asegura que los datos resultantes sean adecuados para futuros análisis o aplicaciones.

6. **Despliegue**:
Implementar los resultados del análisis o la limpieza en el entorno productivo, o generar un informe final documentando el proceso y los resultados para futuras referencias.


