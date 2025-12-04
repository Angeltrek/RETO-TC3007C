# RETO-TC3007C

## ¿Qué se atendió en la retroalimentación?

**Reporte de Deployment oficial**, plenamente alineado a la metodología **CRISP-DM**, tal como se observa en el documento actualizado.

El nuevo entregable ahora incluye:

- Una **estructura narrativa CRISP-DM**, con secciones claras de:
  - Comprensión del negocio
  - Comprensión de los datos
  - Preparación de los datos
  - Modelado
  - Evaluación
  - Deployment y monitoreo
- Explicaciones textuales de **por qué se tomó cada decisión** en lugar de únicamente mostrar código.
- Una separación explícita entre:
  - **documentación**
  - **código**
  - **pipeline**
  - **modelo entrenado**
  - **dashboard**

El entregable dejó de ser un notebook tutorial y se transformó en un **reporte formal**, acompañado de artefactos independientes para su correcta interpretación.

Esto resuelve la crítica de “no sigue CRISP-DM” al nivel metodológico y de estructura.

**Creamos módulos y documentos separados**, donde:

- La **documentación** ahora vive en Reportes CRISP-DM individuales y consolidados.
- El **código** vive en repositorios organizados por carpetas claras (src/, notebooks/, dashboard/, modelos/).
- El **pipeline** se documenta por escrito (no solo en código).
- Se agregaron **README** con instrucciones simples para el usuario.
- La documentación se estructuró como entregables independientes:
  - Reporte de Comprensión de Datos
  - Reporte de Preparación de Datos
  - Reporte de Modelado
  - Reporte de Evaluación
  - Reporte de Deployment

Esto permite que cualquier cliente o stakeholder acceda a la información **sin tocar un notebook** y sin depender del código para entender el proceso.

En la versión corregida se añadió una explicación exhaustiva del proceso, donde:

- Cada etapa del pipeline ahora se acompaña de la **justificación técnica** detrás de esa decisión.
- Se explica claramente:
  - por qué se reconstruyeron variables,
  - por qué se integraron datasets,
  - por qué se realizó augmentación,
  - por qué se eligió la clasificación multiclase,
  - por qué se eligió XGBoost.
- Se describe cómo cada parte del pipeline alimenta las fases de CRISP-DM.

La arquitectura se actualizó para reflejar:

- la integración real del modelo,
- los componentes entregados (scripts, modelo, dashboard),
- la forma de ejecución local,
- la relación entre datos, pipeline y visualización,
- los límites del sistema (no despliegue total en infraestructura CAETEC).

La arquitectura ahora está alineada con:

- el alcance real del proyecto,
- las fases CRISP-DM,
- la estrategia de deployment descrita en el RD.

Después de recibir la retroalimentación, reestructuramos completamente el entregable. Pasamos de un notebook difícil de seguir a un conjunto de reportes formales, documentados, trazables y separados del código. Esto resolvió todas las observaciones iniciales y llevó el proyecto al nivel técnico y documental que se esperaba.

## Índice

1. Business Understanding
   1. Descripción del Contenido
   2. Reporte de Alineación del Proyecto
   3. Business Objectives (Background)
   4. Business Objectives (Business Objectives)
   5. Business Objectives (Success Criteria)
   6. Assess Situation (Inventory of Resources)
   7. Assess Situation (Requirements, Assumptions and Constraints)
   8. Assess Situation (Risks and Contingencies)
   9. Assess Situation (Terminology)
   10. Assess Situation (Costs and Benefits)
   11. Data Mining Goals (Mining Goals and Success Criteria)
2. Data Understanding
   1. Descripción del Contenido
   2. Reporte de Comprensión de Datos
   3. Collection Report (Fuentes de Datos)
   4. Collection Report (Métodos usados para la obtención de datos)
   5. Collection Report (Problemas para obtener datos)
   6. Collection Report (Decisiones sobre datos adicionales)
   7. Collection Report (Notas y solución a los problemas)
   8. Collection Report (Verificación de la integridad de los datos)
   9. Collection Report (Consistencia entre datasets)
   10. Collection Report (Relevancia de cada fuente)
   11. ID Vaca (1204–8794)
       1. Description Report (ID Vaca)
       2. Exploration Report (ID Vaca)
       3. Quality Report (ID Vaca)
   12. Reporte
       1. Description Report (Reporte)
       2. Exploration Report (Reporte)
       3. Quality Report (Reporte)
   13. Inventario
       1. Description Report (Inventario)
       2. Exploration Report (Inventario)
       3. Quality Report (Inventario)
   14. Patadas
       1. Description Report (Patadas)
       2. Exploration Report (Patadas)
       3. Quality Report (Patadas)
   15. Ficha Vaca
       1. Description Report (Patadas)
       2. Exploration Report (Patadas)
       3. Quality Report (Patadas)
   16. Registro Ordeño
       1. Description Report (Registro Ordeño)
       2. Exploration Report (Registro Ordeño)
       3. Quality Report (Registro Ordeño)
   17. Global HATO
       1. Description Report (Global HATO)
       2. Exploration Report (Global HATO)
       3. Quality Report (Global HATO)
   18. Registro Ordeño HATO
       1. Description Report (Registro Ordeño HATO)
       2. Exploration Report (Registro Ordeño HATO)
       3. Quality Report (Registro Ordeño HATO)
   19. Ficha Vacas HATO
       1. Description Report (Ficha Vacas HATO)
       2. Exploration Report (Ficha Vacas HATO)
       3. Quality Report Ficha Vacas HATO)
3. Data Preparation 1
   1. Descripción del Contenido
   2. Reporte de Preparación de Datos
   3. Resumen de la Preparación de Datos
   4. Enfoque Iterativo
   5. Limpieza (Primera iteración)
   6. Transformaciones (Primera iteración)
   7. Feature engineering (Primera iteración)
   8. Merge de los Datasets (Primera iteración)
   9. Creación de dataset final (Primera iteración)
   10. Descripción del dataset final (Primera iteración)
4. Modeling
   1. Descripción del Contenido
   2. Reporte de Modelado
   3. Modeling Technique (Primera iteración)
   4. Test Design (Primera iteración)
   5. Model Overview (Primera iteración)
   6. Results Evaluation (Primera iteración)
5. Data Preparation 2
   1. Limpieza (Segunda iteración)
   2. Transformaciones (Segunda iteración)
   3. Feature engineering (Segunda iteración)
   4. Merge de los Datasets (Segunda iteración)
   5. Creación de dataset final (Segunda iteración)
   6. Descripción del dataset final (Segunda iteración)
6. Modeling 2
   1. Modeling Technique (Segunda iteración)
   2. Test Design (Segunda iteración)
   3. Model Overview (Segunda iteración)
   4. Results Evaluation (Segunda iteración)
7. Data Preparation 3
   1. Limpieza (Tercera iteración)
   2. Transformaciones (Tercera iteración)
   3. Features engineering (Tercera iteración)
   4. Merge de los Datasets (Tercera iteración)
   5. Creación de dataset final (Tercera iteración)
   6. Descripción del dataset final (Tercera iteración)
8. Modeling 3
   1. Modeling Technique (Tercera iteración)
   2. Test Design (Tercera iteración)
   3. Model Overview (Tercera iteración)
   4. Results Evaluation (Tercera iteración)
9. Evaluation
   1. Descripción del Contenido
   2. Reporte de Evaluación
   3. Evaluate Results
   4. Review Process
   5. Determine Next Steps
10. Deployment
    1. Produce Final Report (Final Report)
