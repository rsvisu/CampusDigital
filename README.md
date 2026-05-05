# Campus Digital | Prácticas 2º DAW

Repositorio central donde recopilo toda la información relacionada con mis prácticas de 2º de DAW en el **Campus Digital** (curso 2025-2026).

### Contenido

- [**Proyectos**](#proyectos) — Proyectos asignados durante las prácticas, con su descripción y repositorio correspondiente.
- [**Diario de prácticas**](#diario-de-prácticas) — Registro diario de las tareas y avances realizados.
- [**Anexo — Repositorios relacionados**](#anexo--repositorios-relacionados) — Índice de todos los repositorios vinculados a las prácticas.

## Proyectos

### Documentación interna

**Inicio:** 04/03/2026  
**Estado:** En progreso

#### Objetivo

Crear un sitio web para servir la documentación interna del Campus Digital, que actualmente está escrita en Markdown. Se están evaluando distintas herramientas de generación de sitios estáticos:

| Herramienta | Ecosistema |
|---|---|
| VuePress | Vue |
| Nuxt Content / Docus | Vue (Nuxt) |
| MKDocs | Python |

Aspectos a resolver:

- Sistema de **búsqueda interna** sobre la documentación.
- Mecanismo para **importar la documentación ya existente** (archivos `.md`).
- Seleccionar la herramienta que mejor se adapte a las necesidades del equipo.

#### Trabajo realizado

Repositorios:
- [CD_HerramientasDocumentacion](https://github.com/rsvisu/CD_HerramientasDocumentacion) *(privado)* — Pruebas iniciales con diferentes herramientas
- [Nueva_Documentacion](https://github.com/FPVirtual/Nueva_Documentacion) *(en desarrollo)* — Solución final con Astro + Starlight

## Diario de prácticas

### Marzo 2026

#### Semana 1

| Día | Actividad |
|---|---|
| **Lunes 2** | Primer día de prácticas. Tour por las instalaciones del Campus Digital y preparación de los equipos de trabajo (instalación de herramientas, configuración de entornos, etc.). |
| **Martes 3** | Nos presentaron los proyectos disponibles. A mí y a mi compañero nos asignaron dos proyectos distintos; yo elegí el de **documentación**. Empecé a investigar las herramientas candidatas (VuePress, Nuxt Content, Docus, MKDocs). |
| **Miércoles 4** | Descargué VuePress y lo probé con el tema por defecto. También probé otros dos temas (Hope y Plume). Creé el repositorio [CD_HerramientasDocumentacion](https://github.com/rsvisu/CD_HerramientasDocumentacion) para subir cada prueba. |

#### Semana 2

| Día | Actividad |
|---|---|
| **Lunes 9** | Decidí aprender Vue antes de seguir evaluando herramientas, ya que la mayoría (VuePress, Nuxt/Docus) se basan en él. Empecé el curso *Learn Vue 3 Step by Step* de Laracasts. |
| **Martes 10** | Seguí avanzando con los tutoriales de Vue (componentes, props, eventos…). Creé el repositorio [CD_AprendizajeVue](https://github.com/rsvisu/CD_AprendizajeVue) para subir el código de los ejercicios. |
| **Miércoles 11** | Continué con el curso de Vue, avanzando con más secciones del tutorial (Options API, beyond the basics, slots, componentes flexibles…). |
| **Jueves 12** | Seguí con los tutoriales de Vue, continuando con la Composition API. |
| **Viernes 13** | Configuré una GitHub Action en el repositorio [CD_HerramientasDocumentacion](https://github.com/rsvisu/CD_HerramientasDocumentacion) para desplegar automáticamente los distintos proyectos (VuePress con temas default, Hope y Plume) en un hosting externo (InfinityFree), facilitando la comparativa visual entre las diferentes alternativas. |

#### Semana 3

| Día | Actividad |
|---|---|
| **Lunes 16** | Continué con los tutoriales de Vue, viendo videos sobre manejo de estado (Pinia), composables avanzados, y organización del código. |
| **Martes 17** | Añadí la documentación del Campus Digital al tema Hope de VuePress para hacer una prueba visual. Los resultados son muy buenos con configuraciones básicas. Presenté al tutor de la empresa el avance realizado hasta ahora. |
| **Miércoles 18** | Continué avanzando en el tutorial de Laracasts, profundizando en conceptos de Composition API y patrones de uso. |
| **Jueves 19** | Completé el tutorial *Learn Vue 3 Step by Step* de Laracasts. Ahora tengo una base sólida en Vue 3 (Options API y Composition API) para poder continuar con la evaluación de herramientas de documentación más informadamente. |
| **Viernes 20** | Dedicé el día a practicar Vue consolidando conceptos, y luego asistí a la tutoría de seguimiento en el instituto. |

#### Semana 4

| Día | Actividad |
|---|---|
| **Lunes 23** | Continué practicando Vue, profundizando en composables personalizados y patrones avanzados de manejo de estado. |
| **Martes 24** | Trabajé en la construcción de componentes más complejos, integrando validación y gestión de datos con Pinia. |
| **Miércoles 25** | Experimenté con Vue Router en un proyecto de prueba, creando varias vistas y navegación entre ellas. |
| **Jueves 26** | Continué mejorando mis proyectos prácticos, añadiendo funcionalidades como componentes dinámicos basados en condiciones. |
| **Viernes 27** | Dediqué el día a refactorizar código anterior, aplicando buenas prácticas de Vue y consolidando lo aprendido en los últimos días. |

### Abril 2026

#### Semana 5

| Día | Actividad |
|---|---|
| **Martes 7** | Vuelta de semana santa. Retomé las actividades de prácticas en el Campus Digital y comencé la preparación de una presentación sobre frameworks web para exponer ante estudiantes de primero. |
| **Miércoles 8** | Continué preparando la presentación sobre frameworks, profundizando en los conceptos, ventajas y casos de uso, usando Vue 3 como framework de referencia. |
| **Jueves 9** | Finalicé la preparación de la presentación, puliendo el contenido y los ejemplos de código. |
| **Viernes 10** | Realicé la presentación en la sala de actos del Campus Digital ante estudiantes de **1º Desarrollo Web** y **1º Desarrollo Multiplataforma**. Expliqué qué son los frameworks web, sus principales ventajas (productividad, mantenibilidad, comunidad), casos de uso comunes, y presenté Vue como ejemplo de framework moderno y progresivo. |

#### Semana 6

| Día | Actividad |
|---|---|
| **Lunes 13** | Tras decidir que **Astro con Starlight** es la herramienta elegida para el proyecto de documentación, inicié el repositorio e instalé el proyecto base con la configuración inicial. Además estuve investigando sobre Astro y el uso de Starlight. |
| **Martes 14** | Configuré la infraestructura del proyecto: Docker, Nginx, variables de entorno, y un script de sincronización de documentación desde un repositorio externo. Configuré también el GitHub Action para auto-deploy automático en el servidor. |
| **Miércoles 15** | Refactoricé la arquitectura del proyecto e hice ajustes en la estructura de carpetas y configuración general. |
| **Jueves 16** | Implementé funcionalidades adicionales como la personalización de temas (CSS y configuraciones) desde el repositorio externo y realicé varios fixes y optimizaciones al proyecto. |
| **Viernes 17** | Tuve una reunión con el tutor de la empresa para presentar y discutir los progresos realizados en el proyecto de documentación, y luego asistí a la tutoría de seguimiento en el instituto. |

#### Semana 7

| Día | Actividad |
|---|---|
| **Lunes 20** | Continuó el desarrollo del proyecto de documentación. Trabajé en la mejora de la sincronización de documentación con mejor manejo de cambios en el repositorio externo. |
| **Martes 21** | Realicé múltiples refactorizaciones y mejoras del proyecto: refactoricé el Dockerfile como imagen genérica con entrypoint dinámico, mejoré los mensajes de log del script de entrypoint, configuré el servicio Nginx como proceso principal, actualicé configuraciones de docker-compose de desarrollo, configuré un flujo de trabajo en GitHub Actions para construir y publicar imagen Docker, fusioné main con ci/static, y actualicé el tag de la imagen a latest. |
| **Miércoles 22** | Implementé la posibilidad de elegir carpeta base y rama del repositorio de documentación, añadiendo mayor flexibilidad al sistema. También trabajé en mejoras de CI/CD y realicé documentación de cambios en los puertos (4321 a 8080). Implementé una mejora importante: el pull del repositorio de documentación ahora no da error aunque falle, permitiendo que el contenedor siga usando lo que ya tiene. |

#### Semana 8

| Día | Actividad |
|---|---|
| **Lunes 27** | Cambié de enfoque para profundizar en herramientas fundamentales. Dediqué el día a estudiar **Git** con el objetivo de afianzar conocimientos y aprender **GitHub Flow** (manejo de ramas, pull requests y workflows colaborativos). |
| **Martes 28** | Continué la formación técnica. Realicé tutoriales sobre **Node.js** y llevé a cabo un pequeño ejercicio práctico construyendo una aplicación con **Express**. |
| **Miércoles 29** | Comencé la investigación del ecosistema **Nuxt** y la herramienta **Nuxt Studio**. Estudié sus características, integración con repositorios, y flujo de trabajo. |
| **Jueves 30** | Continué investigando **Nuxt Studio**. Realicé un despliegue completo de **Nuxt Studio** en el Mini PC del servidor de la empresa, implementando **autenticación con GitLab local** para integración con el flujo de trabajo del equipo. |

## Anexo — Repositorios relacionados

| Repositorio | Descripción |
|---|---|
| [Nueva_Documentacion](https://github.com/FPVirtual/Nueva_Documentacion) | Proyecto de documentación interna usando **Astro + Starlight** con sincronización automática de contenido desde repositorio externo, Docker, Nginx, y GitHub Actions para auto-deploy. |
| [CD_HerramientasDocumentacion](https://github.com/rsvisu/CD_HerramientasDocumentacion) *(privado)* | Pruebas con VuePress (tema default, Hope y Plume) y otras herramientas de documentación. |
| [CD_AprendizajeVue](https://github.com/rsvisu/CD_AprendizajeVue) | Ejercicios y código de los ejercicios realizados para aprender Vue. |
