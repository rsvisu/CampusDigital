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

Repositorio: [CD_HerramientasDocumentacion](https://github.com/rsvisu/CD_HerramientasDocumentacion) *(privado)*

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

## Anexo — Repositorios relacionados

| Repositorio | Descripción |
|---|---|
| [CD_HerramientasDocumentacion](https://github.com/rsvisu/CD_HerramientasDocumentacion) *(privado)* | Pruebas con VuePress (tema default, Hope y Plume) y otras herramientas de documentación. |
| [CD_AprendizajeVue](https://github.com/rsvisu/CD_AprendizajeVue) | Ejercicios y código de los ejercicios realizados para aprender Vue. |
