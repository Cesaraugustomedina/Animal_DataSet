# Bitácora de Transformaciones - Power Query

Registro paso a paso de las operaciones de limpieza y modelado de datos aplicadas al dataset original (`data/raw/`).

## Fase 1: Limpieza Inicial
* [ ] **Configuración de Origen:** Conexión al archivo CSV en la ruta correspondiente.
* [ ] **Promover Encabezados:** Se usó la primera fila como títulos de columna.
* [ ] **Detección de Tipos:** Ajuste automático y corrección manual de formatos (Fechas y Números).

## Fase 2: Calidad de Datos
* [ ] **Eliminación de Duplicados:** Remoción de filas repetidas basadas en el identificador único.
* [ ] **Tratamiento de Nulos:** Sustitución de valores vacíos en columnas críticas por etiquetas de control (ej. "No registrado").
* [ ] **Limpieza de Texto:** Aplicación de funciones de limpieza para eliminar espacios adicionales al inicio o final.

## Fase 3: Enriquecimiento
* [ ] **Columnas Condicionales:** Creación de rangos de edad (Cachorro, Adulto, Senior).
