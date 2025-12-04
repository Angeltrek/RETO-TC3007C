<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/2a7c6295-0681-498e-b0f6-007ac57ce41e" />

----
# RETO-TC3007C
---

## Estructura del repositorio
---

<img width="474" height="740" alt="image" src="https://github.com/user-attachments/assets/049fd38b-47dd-4b4c-a471-d56c05cafdfd" />

> **Integrantes del equipo**
>
> - Cristian Chávez Guía | A01710680
> - Kevin Alejandro Ramírez Luna | A01711063
> - Diego Antonio García Padilla | A01710777
> - José Eduardo Viveros Escamilla | A01710605
> - Fidel Alexander Bonilla Montalvo | A01798199
> - Guadalupe Paulina López Cuevas | A01701095
> - Ángel Mauricio Ramírez Herrera | A01710158

## ¿Qué se atendió en la retroalimentación?
---
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

Link de la aplicación web: https://github.com/CristianChG/prueba-arquitectura-vss

