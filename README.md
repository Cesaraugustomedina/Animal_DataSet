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





El siguiente dataset tiene las siguientes características:

| Columna | Data Type | Descripción |
| :--- | :--- | :--- |
| `Animal` | `UUID` | Identificador único - Nombre de los animales |
| `Height(cm)` | `Decimal` |Altura |
| `Weight(kg)` | `Decimal`| Peso |
| `Color` | `Texto` | Color |
| `Diet` | `Texto` | Dieta |
| `Lifespan(years)` | `Entero` | Esperanza de vida |
| `Habitat` | `Texto` | Habitat |
| `Predators` | `Texto` | Depredadores |
| `Average Speed (km/h)` | `Entero` | Promedio de velocidad |
| `Countries found` | `Texto` | Países donde ha sido encontrado |
| `Conservation status` | `Texto` | Estado de conservación del animal |
| `Family` | `Texto` | Familia |
| `Gestation Period` | `Entero` | Periodo de gestación del animal |
| `Top speed (km/h)` | `Entero` | Máxima velocidad alcanzada por el animal |
| `Social Structure` | `Texto` | Estructura social|
| `Offspring per Birth` | `Entero` | Cantidad de descendencia por gestación. |

![Mono asintiendo](https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExN3l6eTJtczFnM3l6cWljYm90Y2xvamwwZXE3NHR4NThiMDRjNzNzOSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/SMy35IM1uiP59hm4Q0/giphy.gif)
