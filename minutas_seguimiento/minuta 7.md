# Minuta 7

**Período de la Minuta:** 1/10/2025 - 15/10/2025  
**Fecha de Generación de la Minuta:** 3/10/2025  
**Modalidad de Trabajo:** Sincrónica (Reunión Virtual) / Asincrónica (Trabajo Separado)

---

## 1. Asistentes / Participantes

**9/10/2025 (Reunión Virtual):**

- `Achares, Jonatan Francisco Angel`
- `Correa, Martiniano León`
- `Varrenti, Lara`

---

## 2. Temas Tratados y Decisiones Clave

- **9/10/2025- Revisión de cambios del código y decisión de nombre y logo:**

  - **Tema:** Presentación y revisión de los avances asincrónicos en el proyecto durante la semana y debate sobre el nombre, logo y slogan de la app.
  - **Decisión:** Se validó el trabajo realizado y se decidió por el nombre y legajo Skola: conecta tu futuro.
  - **Acciones Pendientes:** Se acordó continuar con la el testeo de ingreso de datos para hallar posibles errores y fallos de la app en general.

---

## 3. Avances del Proyecto

### 3.1. Frontend

- **Cambios Realizados:**

  - Mejora del aspecto del calendario y sus eventos (exámenes).
  - Mejora del funcionamiento del boton `Atrás` de la Sidebar.

- **Adiciones:**

  - Implementación de las vistas `Nuevo exámen`, `Editar exámen`, `Eliminar exámen` y `Subir notas`.
  - Incorporación de la vista de examenes en el calendario para el Docente.


- **Sustracciones:**

### 3.2. Backend

- **Cambios Realizados:**

  - El perfil ahora permite editar datos y estos se guardan en la base de datos, previamente quedaban en memoria.
  - Optimización de validaciones del service de la clase alumnos.

- **Adiciones:**

  - Creación de nueva clase `Evaluación` con su respectivo CRUD para conectar `Exámenes` y `Alumnos`.
  - Implementación de funcionalidad en la BD de las páginas `Nuevo exámen`, `Editar exámen`, `Eliminar exámen` y `Subir notas`.


- **Sustracciones:**


---

## 4. Nuevas Tecnologías / Herramientas Exploradas o Integradas

- _Ninguna por mencionar_

---

## 5. Obstáculos / Desafíos Identificados

- **Creación de clase Evaluación:** Con el desarrollo de la app descubrimos la necesidad de crear una clase `Evaluación` que conecte los alumnos con los exámenes para así poder implementar la Epic "Subir notas".
- **Testeo de ingreso de datos:** Se concluye que se debe realizar un arduo testeo para identificar como procesa los errores la app y como se los notifica al usuario sin romperse.

## 6. Próximos Pasos y Objetivos para la Siguiente Minuta

- **Depurar y verificar la app en general:** Rechequear todo el código y buscar faltantes y/o errores previo a la defensa del proyecto.

  - **Responsable(s):** Todos los integrantes.
  - **Fecha Límite Sugerida: 14/10/25**

## 7. Anexos / Referencias
- Posible logo, nombre y slogan.  
   <img width="454" height="209" alt="image" src="https://github.com/user-attachments/assets/869bdef6-6c03-4633-b219-5b501ba499f3" />

---
