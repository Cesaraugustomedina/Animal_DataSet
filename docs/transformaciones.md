# Bitácora de Transformaciones - Power Query

Registro paso a paso de las operaciones de limpieza y modelado de datos aplicadas al dataset original (`data/raw/`).

## Fase 1: Limpieza Inicial
* [ ] **Configuración de Origen:** Conexión al archivo CSV en la ruta correspondiente.
* [ ] **Promover Encabezados:** Se usó la primera fila como títulos de columna.
* [ ] **Creación de tabla de atributos:** Se duplicó la tabla original y solo se mantuvieron las siguientes características (Color, Diet, Habitat, Predators, Countries found)
* [ ] **Se realizó el proceso de "Normalización":** Se convirtieron esos valores múltiples en filas individuales para cada una de las 5 columnas
* [ ] **Dinamización de las otras columnas:** Se anuló la dinamización de las otras columnas dando clic derecho en la columna de nuestro identificador que es el nombre del Animal

## Fase 2: Calidad de Datos
* [ ] **Eliminación de Duplicados:** Remoción de filas repetidas basadas en el identificador único.
* [ ] **Tratamiento de Nulos:** Sustitución de valores vacíos en columnas críticas por etiquetas de control (ej. "No registrado").
* [ ] **Limpieza de Texto:** Aplicación de funciones de limpieza para eliminar espacios adicionales al inicio o final.

## Fase 3: Enriquecimiento
* [ ] **Columnas Condicionales:** Creación de rangos de edad (Cachorro, Adulto, Senior).
