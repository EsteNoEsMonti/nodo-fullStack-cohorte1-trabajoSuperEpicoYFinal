## 💥 Trabajo Práctico Épico y Final
### 🧠 Fullstack React + Node

### 🎯 Objetivo General
Desarrollar una aplicación web fullstack que combine autenticación, administración de perfiles, consumo de APIs externas y un flujo de uso realista. El enfoque debe estar en la **calidad del código, la coherencia del diseño, la experiencia del usuario y la cobertura de funcionalidades básicas y avanzadas**.

---

## 🧱 Requisitos Generales

### ✅ Tecnologías obligatorias
- **Frontend:** React + Vite + TailwindCSS v4
- **Backend:** Node.js + Express + MongoDB
- **Comunicación entre front y back:** Axios/Fetch + Auth Token (JWT)
<!-- - **Herramientas extra:** react-hook-form, SweetAlert2, Toastify, React Router DOM, LocalStorage, etc. -->

### 🎬 Proyecto sugerido: Nodo Cine (sugerimos... pero se valora su creatividad al elegir otra temática)
Una plataforma tipo "mini Netflix" donde un usuario puede:
- Crear perfiles (como Netflix: perfil adulto, niño, etc.).
- Ver un catálogo de películas.
- Agregar películas a su lista personal ("Watchlist").
- Filtrar o restringir películas según edad del perfil.

---

## 🧑‍💻 Funcionalidades obligatorias — Backend

### 🔧 Estructura
- CRUD completo de al menos 3 entidades (Usuario, Perfil, Película)
- Uso de Mongoose
- Autenticación con JWT
- Roles con distintas capacidades (dueño de cuenta, perfil estándar, perfil niño)
<!-- - Validaciones en los endpoints -->
- Endpoints seguros y protegidos según permisos del usuario
- Al menos dos búsquedas o filtros avanzados (por nombre, categoría, etc.)
- Paginado desde servidor en al menos una entidad **(Opcional ✨)**
- Consumo de una API externa (puede ser para obtener ratings, trailers, datos de películas...)

---

## 💻 Funcionalidades obligatorias — Frontend

### 👨‍🎤 Funcionalidad
- Login (guardar token)
- Vista principal con selector de perfiles
- Componente para ver catálogo de películas
- Componente de administración de perfiles
- CRUD completo de entidades conectadas al backend
- Watchlist persistente por perfil
- Visualización y funcionamiento condicional según el tipo de perfil (ejemplo: niño solo ve contenido apto)
- Rutas protegidas
- Ruteo dinámico
- Formularios (ejemplo: de edición de perfil)
- Páginas controladas por React Router DOM

### ⚙️ Técnica
- Peticiones con Axios
- Manejo de Hooks: `useState`, `useEffect`, `useContext` **(mínimo 💀)**, custom hooks si desean
- Formularios validados con `react-hook-form` y validaciones con Yup **(Yup opcional ✨)**
- Manejo de errores del backend
- Toastify o SweetAlert2 para notificaciones
- Paginado desde el servidor en alguna vista **(Opcional ✨)**
- Theme claro / oscuro en toda la app, para cada componente

---

## 🎨 Diseño
- Interfaz clara, coherente y responsive
- Navegación intuitiva
- Estética cuidada (pueden usar bibliotecas visuales si lo desean ✨)
- Consistencia visual entre componentes
- Respetar Leyes de UX

---

## 🎯 Requisitos de Evaluación

### ✅ Obligatorios para aprobar
- Proyecto completo en GitHub (frontend y backend **separados**)
- El backend debe correr correctamente (instrucciones claras en el README)
- El frontend debe ser funcional y demostrar al menos:
  - CRUD funcional
  - Uso real de tokens
  - Rutas protegidas
  - Interfaz visual coherente
- Review individual: el estudiante debe poder **explicar y defender cada parte del código que escribió**
- Aplicación deployada

### ⭐ Bonus
- Exportar reporte de uso (por ejemplo, cuántas veces se vio una película)
- Filtros avanzados
- Integración continua con GitHub Actions

---

## 🔓 Libertad creativa
Los alumnos **pueden (✨y se recomienda que lo hagan✨)** proponer su propio proyecto, siempre que cumpla con:
- Las tecnologías obligatorias
- Los requisitos funcionales mencionados
- Un flujo de uso realista con autenticación y distintos tipos de usuario

Ejemplos alternativos posibles:
- Plataforma de cursos online  
- Agenda de turnos con múltiples perfiles  
- Red social básica con perfiles personalizados  
- App para administrar torneos deportivos

✨ Que la fuerza los acompañe ✨
