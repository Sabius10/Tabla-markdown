```mermaid
gantt
title Planificación del Proyecto Informático
dateFormat  YYYY-MM-DD
axisFormat  %d-%m
section Diseño e Investigación
Definición de requerimientos :done,    des1, 2026-11-01, 2026-11-04
Diseño de Arquitectura       :active,  des2, 2026-11-04, 3d
section Desarrollo Backend
Configuración de Base de Datos         : crit, api1, 2026-11-07, 4d
Creación de Endpoints API              : api2, after api1, 5d
section Frontend
Maquetación de la interfaz             : front1, 2026-11-06, 6d
Integración con la API                 : front2, after api2, 4d
   ```
