#  
Dashboard Ordenes PAL - Power BI 

Documentación técnica de la herramienta Ordenes PAL

--- 

##  
Objetivo 

El objetivo principal del tablero de Órdenes PAL es gestionar de forma integral el ciclo de vida de las órdenes de fabricación, desde su apertura hasta su cierre técnico y liquidación, asegurando control operativo, trazabilidad y cumplimiento del plan de producción.

--- 

##  
Tecnologías Utilizadas 
- **Power BI Desktop** (*[modo de conexión: Import / DirectQuery]*)
- - **[Fuente de datos, ej. SharePoint / SQL Server / SAP / Excel]**
- - **DAX** (*[tipo de cálculos: medidas de forecast, métricas de calidad, etc.]*)
- - **GitHub** (para control de versiones y documentación técnica)   --- 
##  
Estructura del Repositorio 
```plaintext 
[Nombre_Repositorio]/ 
├── pbix/               → Archivos PBIX del tablero                     
├── README.md           → Descripción general del repositorio                     
├── docs/ 
├── Medidas.md                   → Medidas DAX documentadas                          
├── Columnas_Calculadas.md       → Columnas calculadas documentadas        
├── Tablas_Calculadas.md         → Tablas calculadas documentadas        
└── video_tutorial.md            → Guía de uso del dashboard        
├── img/ 
│ 
├── preview_dashboard.png        → Captura del dashboard        
│   
└── modelo_datos.png             → Relación entre tablas 
       

```

--- 
##  
Preview del Dashboard 
![Preview](img/preview_dashboard.png)
