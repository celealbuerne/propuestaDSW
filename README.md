# TP Desarrollo de Software (DSW)

## Objetivo

Desarrollar en grupo una aplicación web full stack en base a un alcance propuesto por los integrantes. Durante el desarrollo se deberá aplicar todo lo aprendido en la materia Desarrollo de Software.

## Tema y alcance

El grupo debe proponer a los docentes un tema para el trabajo práctico de su preferencia, utilizando la plantilla de propuesta.

## Requisitos

El desarrollo de la aplicación debe:

- Desarrollarse en 2 partes, Frontend y Backend, agnósticas entre sí y comunicadas mediante una API.
- Cumplir con los requisitos técnicos y funcionales.
- Desarrollarse en grupo utilizando metodologías de gestión de proyecto y llevar evidencia de ello.
- Cumplir con las entregas estipuladas.
- Utilizar GitHub o GitLab para la gestión del código fuente.
- Realizar una defensa oral del trabajo práctico para la regularidad.
- Realizar otra defensa oral del trabajo práctico para la aprobación.
- Presentar la documentación durante la defensa.

### Requisitos técnicos

La app cuenta con 2 partes, Backend y Frontend, agnósticas entre sí, que se comunican mediante una API.

#### Backend

**Regularidad**

- Desarrollarse en JavaScript.
- Utilizar un framework web que permita integrarse con otras herramientas a través de middlewares, plugins o módulos.
- Exponer una API web (REST, tRPC o gRPC) para interactuar con el frontend.
- Utilizar una base de datos persistente a la que se acceda a través de un servicio externo (no embebida).
- Realizar la persistencia mediante un mapper (ORM/ODM/OXM). Si la base de datos no tiene un mapper disponible para JavaScript, se deberá implementar la persistencia con el patrón Repository.
- Realizarse mediante capas.
- Validar la entrada de datos, y manejar e informar apropiadamente los errores a través de la API.
- Registrar las dependencias de ejecución, desarrollo y test para que se instalen automáticamente (por ejemplo, en `package.json`).

**Aprobación directa o en examen**

- Cumplir con todas las condiciones de regularidad.
- Implementar 1 test automatizado por integrante.
- Implementar 1 test de integración.
- Implementar un login con autenticación propia o de third-party, con al menos 2 niveles de acceso diferentes.
- Proteger las rutas según el nivel de acceso requerido.
- Definir ambientes, ya sea mediante el environment del framework o `.env`.

#### Frontend

**Regularidad**

- Desarrollarse utilizando un framework de frontend.
- Utilizar HTML5.
- Utilizar CSS según las directrices de alguna biblioteca de componentes, guía de estilo o framework de CSS, y la metodología propuesta por el framework de frontend elegido. Se sugiere el uso de bibliotecas de componentes, preprocesadores (Sass, SCSS, Less, Stylus, etc.) o frameworks de CSS (Pico.css, Bulma, Material, Tailwind, Bootstrap, etc.).
- Guía de estilos sugerida: [Airbnb JavaScript](https://github.com/airbnb/javascript).
- Aplicar la estrategia **mobile-first** en la escritura del CSS.
- La app debe visualizarse correctamente en al menos 3 breakpoints: **SM, MD y LG**.
- Seguir buenas prácticas de UX/UI (que no requiera manual de usuario ni explicaciones específicas para usar la interfaz).
- Mostrar, entre sus componentes, las siguientes características:
  - Manejo de eventos del usuario: click, input, etc.
  - Ante una posibilidad de fallo, manejar los errores adecuadamente y de manera amigable para el usuario.
  - Reactividad ante un estado.
  - Input property.
  - Output property.
- Implementar al menos un servicio.
- Para el manejo de la información (por ejemplo, la respuesta de un endpoint o los datos a enviar en una request), representar en el código los modelos de objetos con clases, interfaces y tipos de datos custom.
- De ser posible, implementar algún patrón de diseño orientado a objetos.
- Registrar las dependencias de ejecución, desarrollo y test para que se instalen automáticamente (por ejemplo, en `package.json`).

**Aprobación directa o en examen**

- Cumplir con las condiciones de regularidad.
- Realizar al menos 1 test unitario de un componente.
- Realizar al menos 1 test end-to-end.
- Implementar el login y proteger el acceso a las distintas partes del frontend según los niveles de usuario del backend.
- Definir ambientes, ya sea mediante el environment del framework o `.env`.

### Requisitos funcionales

**Regularidad**

- 1 CRUD simple por integrante.
- 1 CRUD dependiente cada 2 integrantes o fracción.
- 1 listado con filtro (al menos un atributo) cada 2 integrantes o fracción.
- Para cada listado, al seleccionar un elemento se debe mostrar un detalle.
- Implementar un caso de uso de usuario o epic, con valor para el negocio, cada 2 integrantes o fracción.

**Aprobación directa o en examen**

- CRUDs de todas las clases de negocio necesarias para el funcionamiento de la app.
- Implementar 1 caso de uso de usuario o epic, con valor para el negocio, por cada integrante.
- Se deben implementar un mínimo de 2 relacionados entre sí; es decir, los datos registrados por un CU o epic deben servir de input para otro.

**Alcance adicional (voluntario)**

De forma opcional, los grupos podrán realizar casos de uso o epics, listados más complejos que los solicitados u otros requisitos (notificaciones, logs, etc.) para completar la funcionalidad del sistema propuesto. Esto se considerará en la nota final en función de la complejidad y el esfuerzo relativos a lo ya realizado.

### Entregas

**Propuesta del enunciado**

Se debe entregar a los profesores la plantilla de propuesta actualizada con las condiciones de regularidad y de aprobación. Los profesores analizarán la propuesta y, de ser necesario, sugerirán ajustes hasta que esté correcta y sea aceptada.

**Regularidad**

- El `README.md` (o un link) con las instrucciones para instalar y ejecutar el proyecto sin conocimientos de cómo está desarrollado. El proyecto debe poder ejecutarse con scripts y herramientas según las convenciones del lenguaje o framework utilizado (scripts en `package.json` o tools específicas del framework).
- La proposal actualizada, con links al pull request de back y/o front, mediante el formulario publicado para cada año.
- Coordinar una defensa grupal con los profesores.

**Aprobación directa o en examen**

- Video explicando el funcionamiento del sistema.
- Documentación de la API de backend (según la tecnología y el estándar utilizados).
- Evidencia del resultado de la ejecución de los tests automáticos.
- La proposal actualizada, con links al pull request de back y/o front.
- En el `README.md` (o con un link), las instrucciones para instalar y ejecutar el proyecto sin conocimientos de cómo está desarrollado. El proyecto debe poder ejecutarse con scripts y herramientas según las convenciones del lenguaje o framework utilizado.
- Links de deploy.
- Credenciales para utilizar la aplicación deployada.
- Contacto para coordinar la defensa.

El envío se realiza por el formulario https://kutt.it/DSWEntregaSistemaFinal y se coordina con el docente una defensa grupal con los profesores.

- **Aprobación directa:** la defensa debe pactarse con los docentes dentro de los plazos indicados a continuación.
- **Aprobación en examen:** la defensa debe pactarse con los docentes y realizarse antes de la fecha de la mesa de examen.

### Fechas de entrega

| Instancia | Fecha |
| --- | --- |
| Propuesta | Durante abril |
| Muestra de avance | Inicio del segundo cuatrimestre |
| Primera entrega de regularidad / AD | 17/10/2025 |
| Primer recuperatorio / globalizador de regularidad / AD | 31/10/2025 |
| Última instancia de recuperatorio / globalizador de regularidad / AD | 14/11/2025 |

### Documentación

La documentación debe presentarse para la instancia de defensa. Para conocer el detalle, referirse a *docs*.

## Gestión del proyecto

> TODO: en revisión

El desarrollo de la app debe realizarse utilizando metodologías ágiles para la gestión del proyecto (Scrum, XP, etc.).

El grupo deberá llevar un registro de lo realizado que incluya, como mínimo:

- Tipo de metodología a utilizar para el seguimiento (Scrum, XP, etc.).
- Minutas de avances o reuniones de coordinación del equipo.
- Documentación de trackeo, como desarrollo de features y bugfix, asignación de tareas, etc.

La herramienta de trackeo es de libre elección. Se recomienda GitHub/GitLab Projects para integrarlo con el desarrollo; si se usa otra, en la documentación deberán incluirse los links a la herramienta.

## Evaluación

Durante la evaluación de cada entrega se considerarán:

- Requisitos técnicos y funcionales de la etapa.
- Adhesión a las directrices de UX/UI y buenas prácticas de programación.
- Uso apropiado de la tecnología: librerías, frameworks, patrones, etc.
- Documentación requerida.
- Participación de los miembros del grupo.
- Uso de git para el desarrollo.
- Defensa oral del trabajo práctico.
- Gestión y seguimiento del desarrollo de la app.
- Innovación, investigación y desafíos asumidos.

## FAQ

En la sección de FAQ se encuentran las respuestas a las consultas más frecuentes.
