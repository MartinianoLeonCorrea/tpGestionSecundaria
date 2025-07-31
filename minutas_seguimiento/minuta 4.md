# Minuta 4

**Período de la Minuta:** 17/07/2025 - [DD/MM/AAAA]  
**Fecha de Generación de la Minuta:** [DD/MM/AAAA] (cuando se termine realizar)  
**Modalidad de Trabajo:** Asincrónica con Comunicación Continua y Reuniones Virtuales Sincrónicas. 

---

## 1. Asistentes / Participantes

**24/07/2025 (Reunión Virtual):**

- `Achares, Jonatan Francisco Angel`
- `Correa, Martiniano León`
- `Varrenti, Lara`

**30/07/2025 (Reunión Virtual):**

- `Achares, Jonatan Francisco Angel`
- `Correa, Martiniano León`
- `Varrenti, Lara`
---

## 2. Temas Tratados y Decisiones Clave

- **24/07/2025 - Reunión Virtual - Asignación de CRUDs y Elección de Base de Datos:**

  - **Tema:** Definición y asignación de los CRUDs simples para la regularidad, y elección de la base de datos.
  - **Decisión:** Se decidió utilizar mySQL como sistema de gestión de bases de datos por la familiaridad de los integrantes a la herramienta. Además, se asignaron los CRUDs simples de la siguiente manera:
    - Correa: CRUD Materia
    - Achares: CRUD Docente
    - Varrenti: CRUD Curso
  - **Consideración:** Surgió la duda sobre la implementación del CRUD Alumno, ya que si bien solo se requieren tres CRUDs para la regularidad (uno por integrante), el CRUD Alumno es fundamental para el funcionamiento básico de la aplicación.
  - **Acciones Pendientes:** Investigar la viabilidad de una único clase Usuario o Persona en lugar de Docente y Alumno en esta etapa.

- **24/07/2025 - Reunión Virtual - Reporte de avance en los CRUDs:**

  - **Tema:** Se charló sobre el avance individual de cada participante en el CRUD que se le había asignado, se acordó un mismo formato para todos y se charló brevemente sobre el FrontEnd.
  - **Decisión:** Quienes habían avanzado en su CRUD mostraron sus avances y charlaron dudas o sugerencias que le fueron ocurriendo en el proceso. Se acordó llevar una arquitectura de capas con la creación de las carpetas `\controllers`, `\models`, `\routes` y `\services`. Se concluyó que realizaremos una única clase Persona que tendrá un diferencial numérico para saber si se trata de un Alumno, Profesor u otro. Se debatió sobre aspectos del FrontEnd peró se harán efectivos más adelante en el proyecto.
  - **Acciones Pendientes:** Concluir todos los CRUDs simples y comenzar a crear en conjunto los CRUDs dependientes

- ...

---

## 3. Avances del Proyecto

### 3.1. Frontend

**Cambios Realizados**: _No se han implementado avances en el frontend en este período._

- **Adiciones**: _No se han implementado adiciones en el frontend en este período._
- **Sustracciones**: _No se han realizado sustracciones en el frontend en este período._
- **Formato/Ejemplos de Cambios Realizados:**

  - [Descripción del cambio 1, ej. "Implementación de la nueva pantalla de perfil de usuario."]
  - [Descripción del cambio 2, ej. "Optimización del rendimiento de carga de imágenes en la galería."]
  - ...

- **Formato/Ejemplos de Adiciones:**

  - [Descripción de nueva funcionalidad 1, ej. "Nuevo componente de carrito de compras."]
  - [Descripción de nueva biblioteca o framework 1, ej. "Integración de React Router."]
  - ...

- **Formato/Ejemplos de Sustracciones:**
  - [Descripción de elemento eliminado 1, ej. "Eliminación de la sección 'Acerca de' redundante."]
  - [Descripción de código obsoleto 1, ej. "Remoción de la dependencia 'xyz-legacy-ui'."]
  - ...

### 3.2. Backend

- **25/07/2025 - Avance en Conexión a Base de Datos:**

  - **Cambios Realizados:** Se avanzó significativamente con la configuración y prueba de la conexión a la base de datos MySQL.
  - **Adiciones:** Se creó la base de datos `Secundaria`

- **26/07/2025 - Avance en CRUD Materia (Correa):**
  - **Cambios Realizados:** El compañero Correa avanzó con la implementación del CRUD Materia.
  - **Adiciones:** Se comenzó a utilizar Sequelize como ORM para la interacción con la base de datos, facilitando las operaciones CRUD.

**26/07/2025 - Reorganización del proyecto en capas:**

- **Cambios Realizados:** Se reorganizó el sistema de paquetes y archivos del backend para adherirse a una arquitectura de capas, buscando una mejor modularidad y separación de responsabilidades. Como parte de esta refactorización, se redujeron las responsabilidades del archivo index.js, y se creó un nuevo archivo app.js para la ejecución principal de la aplicación.

---

## 4. Nuevas Tecnologías / Herramientas Exploradas o Integradas

- **MySQL:** Sistema de gestión de bases de datos relacionales, elegido para la persistencia de datos del proyecto.
- **MySQL Workbench:** Herramienta visual unificada para desarrolladores de bases de datos.
- **Sequelize:** ORM (Object-Relational Mapper) para Node.js, utilizado para facilitar la interacción con bases de datos relacionales como MySQL.
- ...

---

## 5. Obstáculos / Desafíos Identificados

- **Reflexión sobre el CRUD Alumno:** La decisión sobre si implementar el CRUD Alumno en esta etapa, considerando que no es estrictamente necesario para la regularidad pero sí para la funcionalidad básica, es un desafío. Se terminó pensando en un único CRUD Persona en lugar de uno Docente y otro Alumno por separado.

- **Gestión de Usuarios:** La duda sobre si desarrollar un CRUD Usuario completo con validación o usar usuarios predeterminados es un punto a resolver que impactará la complejidad del backend si se apunta a la regularidad.

- **Coordinación de Desarrollo Backend:** Con tres integrantes trabajando en CRUDs separados y la reestructuración de la arquitectura de capas, mantener la coherencia y la integración fluida del código fue un desafío constante.

- ...

---

## 6. Próximos Pasos y Objetivos para la Siguiente Minuta

- **Finalizar CRUDs Simples Asignados:** Completar la implementación de los CRUDs de Materia, Docente y Curso en el backend, incluyendo la persistencia en MySQL a través de Sequelize.

  - **Responsable(s):** Todos los integrantes
  - **Fecha Límite Sugerida:** [Definir fecha, ej. 08/08/2025]

- **Abordar la Gestión de Usuarios:** Definir la estrategia para la gestión de usuarios (CRUD completo o predeterminados) y proceder con su implementación si corresponde.
  
  - **Responsable(s):** Todos los integrantes
  - **Fecha Límite Sugerida:** [Definir fecha, ej. 08/08/2025]

- **Configuración y Primeros Pasos del Frontend:** Comenzar a configurar el proyecto de React y desarrollar los primeros componentes básicos. El objetivo es realizar un GET ALL desde el frontend hacia uno de los CRUDs ya implementados en el backend.

  - **Responsable(s):** Todos los integrantes
  - **Fecha Límite Sugerida:** [Definir fecha, ej. 30/08/2025]

- ...

---

## 7. Anexos / Referencias

- [Enlace a documentos relevantes, wireframes, prototipos, etc.]
- [Enlace a repositorios de código específicos.]
- ...

---
