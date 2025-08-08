# Minuta 5

**Período de la Minuta:** 07/08/2025 - DD/MM/2025  
**Fecha de Generación de la Minuta:** DD/MM/2025  
**Modalidad de Trabajo:** Asincrónica con Comunicación Continua y Reuniones Virtuales Sincrónicas.

---

## 1. Asistentes / Participantes

**07/08/2025 (Reunión Virtual):**

- `Achares, Jonatan Francisco Angel`
- `Correa, Martiniano León`
- `Varrenti, Lara`

**14/08/2025 (Reunion Virtual):**

---

## 2. Temas Tratados y Decisiones Clave

- **07/08/2025 - Reunión Virtual - Informe de Avance en FrontEnd y próximos pasos:**

  - **Tema:** Presentación y discusión del primer avance funcional del frontend, incluyendo la integración con el backend.
  - **Decisión:** Se revisó el código del frontend y se confirmó que la conexión con el backend mediante fetch funcionaba correctamente, mostrando los datos de las materias.
  - **Acciones Pendientes:**
    - Continuar con la reestructuración del frontend y la creación de los demás componentes y rutas.
    - Avanzar con el desarrollo de los CRUDs dependientes Dictado y Examen.

---

## 3. Avances del Proyecto

### 3.1. Frontend

- **Cambios Realizados**: Se implementó el archivo App.jsx como componente principal de la aplicación React, gestionando la estructura de rutas mediante react-router-dom.

- **Adiciones**:
  - Se creó una página de inicio ("Home") que actúa como pantalla principal, presentando un botón que permite navegar al listado de materias.
  - Se desarrolló una página específica accesible mediante la ruta /materias, en la cual se realiza una petición GET al backend para obtener y mostrar el listado completo de materias. En la misma página de materias, se incorporó un buscador que permite consultar una materia específica por su ID, mostrando sus detalles si es encontrada.
- **Sustracciones:** Se eliminó el archivo index.js y styles.css ya que dejaron de ser parte de la estructura base del proyecto.

### 3.2. Backend

- **Cambios Realizados**:
- **Adiciones**:
- **Sustracciones**: Se eliminó el middleware que servía el frontend directamente al backend ya que no era lo que se pedía.

---

## 4. Nuevas Tecnologías / Herramientas Exploradas o Integradas

- **React:** Biblioteca de JavaScript para crear interfaces de usuario, basada en componentes reutilizables que gestionan su propio estado.
- **Vite:** Herramienta de construcción que ofrece un servidor de desarrollo ultrarrápido y carga instantánea de los cambios, optimizando el flujo de trabajo en proyectos de frontend.
- **React Router DOM:** Biblioteca de enrutamiento que permite la navegación entre las "páginas" de una aplicación de React sin necesidad de recargar la página completa.

---

## 5. Obstáculos / Desafíos Identificados

- **:**

---

## 6. Próximos Pasos y Objetivos para la Siguiente Minuta

- **:**

  - **Responsable(s):** Todos los integrantes.
  - **Fecha Límite Sugerida:**

---

## 7. Anexos / Referencias

- _-_

---
