# CISSM Cleaning.
## Integrantes.
- Equipo de Matemáticas: Nacho Sánchez y María González.
- Equipo de Machine Learning: 

## Información.
1. **Event Description**: Descripción textual del evento.
2. **Event Date**: Fecha del evento.
3. **Actor**: Nombre del actor involucrado.
4. **Actor Type**: Categoría que clasifica al tipo de actor involucrado en el incidente.
5. **Event Type**: Tipo de evento que ocurrió.
6. **Organization**: Organización involucrada en el evento.
7. **Event Subtype**: Subcategoría del tipo de evento.
8. **Motive**: Motivo del evento.
9. **Event Source**: Fuente de información sobre el evento.
10. **Country**: País donde ocurrió el evento.
11. **Industry**: Industria relacionada con el evento. Viene representado numéricamente por **Industry Code**.
12. **Industry Code**: Código de la industria correspondiente.
13. **Dnx Id**: Identificador único para cada evento.
14. **Date Uploaded**: Fecha de carga de los datos. Considerada irrelevante para el análisis y eliminada.

## Notas de la limpieza.
Esto son algunas aclaraciones sobre los cambios grandes que hizo el equipo de matemáticas.
- Eliminación de Columnas Irrelevantes: Se eliminaron **Event Date**, **Country**, y **Date Uploaded** para simplificar el dataset y enfocarse en la información clave para el análisis.
- Transformación de Variables Temporales: La fecha del evento original fue descompuesta en tres columnas (**Year**, **Month**, **Day**) para hacer más sencillo el análisis temporal.
- Columnas Dummy de Continentes: Originalmente, los eventos estaban clasificados por país en la columna **Country**. Sin embargo, dado que algunos eventos abarcan varios países, hemos simplificado esta información creando variables dummy para cada continente. Estas variables son columnas binarias (0 o 1), donde 1 indica que el evento está asociado a un continente específico y 0 indica que no lo está. Las columnas dummy incluyen: Africa, Asia, Australia, Europe, North America, y South America. Esto permite un análisis regional más claro sin detallar cada país. Finalmente, se elimina la columna **Country**.
