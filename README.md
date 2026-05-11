# Animal DataSet

```text
Estructura del Repositorio:

├── data/
│   ├── raw/                 # Dataset original de animales (sin tocar)
│   └── processed/           # Opcional: Respaldos de datos limpios

├── reports/
│   └── analisis_animales.pbix # Tu archivo principal de Power BI

├── docs/
│   ├── diccionario_datos.md # Explicación de columnas y tipos de datos
│   └── transformaciones.md  # Bitácora de pasos limpios en Power Query
├── .gitignore               # Para evitar subir archivos temporales de PBIX
└── README.md                # Presentación general de tu proyecto
```
# 📂 Gestión de Datos (`data/`)

Este directorio contiene los conjuntos de datos del proyecto, organizados por su ciclo de vida y estado de procesamiento para garantizar la reproducibilidad del análisis.

---

## 📥 1. Datos Originales (`data/raw/`)

* **Propósito:** Almacenar las fuentes de datos en su estado más puro.
* **Regla de oro:** **NO** modificar, renombrar ni sobrescribir los archivos de esta carpeta. Power BI lee directamente de aquí para iniciar el proceso de extracción.

### Archivos contenidos:
* 📊 [Dataset Original de Animales (CSV)](data/raw) :
Dataset nativo con registros históricos de especies, edades y estados de salud, sin filtros previos.

---

## ⚙️ 2. Datos Procesados (`data/processed/`)

* **Propósito:** Guardar respaldos intermedios o instantáneas de datos limpios.
* **Uso en Power BI:** Este archivo es útil si exportas tablas calculadas complejas o si necesitas almacenar históricos ya transformados que no requieran pasar nuevamente por Power Query.

### Archivos contenidos:
* 📊 [Dataset Limpio de Animales (CSV)](data/processed) :: (Opcional) Copia de seguridad de la tabla consolidada tras la remoción de duplicados y nulos.

---

## 📂 Documentación del Proyecto
Para conocer más detalles sobre el diseño de este proyecto, consulta los siguientes archivos:
* 📖 [Diccionario de Datos](docs/diccionario_datos.md)
* ⚙️ [Bitácora de Transformaciones en Power Query](docs/transformaciones.md)


![Mono asintiendo](https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExN3l6eTJtczFnM3l6cWljYm90Y2xvamwwZXE3NHR4NThiMDRjNzNzOSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/SMy35IM1uiP59hm4Q0/giphy.gif)
