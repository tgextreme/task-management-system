# Sistema de Gestión de Tareas

Este proyecto es un **Sistema de Gestión de Tareas** desarrollado por **Tomás González**. Combina un backend robusto con un frontend dinámico para gestionar tareas, usuarios y categorías de manera eficiente.

---

## 🚀 Tecnologías Utilizadas

### Backend
- **Framework**: Symfony (API Platform)
- **Base de datos**: MySQL
- **ORM**: Doctrine
- **Validación de datos**: Symfony Validator
- **Endpoints RESTful**: API Platform
- **Autenticación y Seguridad**: Symfony Security

### Frontend
- **Framework**: Vue.js
- **Estilo**: Bootstrap 5
- **Manejo de estados**: Vue Router
- **Consumo de APIs**: Axios

---

## 📂 Estructura del Proyecto

### Backend (`/backend`)
- **Entidades**:
  - `User`: Gestión de usuarios con roles básicos.
  - `Category`: Gestión de categorías de tareas.
  - `Task`: Gestión de tareas con validaciones.
- **Endpoints**:
  - `/api/users`: CRUD de usuarios.
  - `/api/categories`: CRUD de categorías.
  - `/api/tasks`: CRUD de tareas.

### Frontend (`/frontend`)
- **Vistas**:
  - Usuarios:
    - Listado (`UserList.vue`)
    - Crear (`UserCreate.vue`)
    - Editar (`UserEdit.vue`)
  - Categorías:
    - Listado (`CategoryList.vue`)
    - Crear (`CategoryCreate.vue`)
    - Editar (`CategoryEdit.vue`)
  - Tareas:
    - Listado (`TaskList.vue`)
    - Crear (`TaskCreate.vue`)
    - Editar (`TaskEdit.vue`)

- **Navegación**:
  - Implementada con **Vue Router**.
  - Diseño responsivo con **Bootstrap 5**.
- **Consumo de API**:
  - Integración con el backend mediante **Axios**.

---

## 💻 Instalación y Configuración

### Backend
1. Instalar dependencias:
   ```bash
   composer install
   ```
2. Configurar `.env` con credenciales de la base de datos.
3. Crear la base de datos:
   ```bash
   php bin/console doctrine:database:create
   php bin/console doctrine:migrations:migrate
   ```
4. Iniciar el servidor:
   ```bash
   symfony server:start
   ```

### Frontend
1. Instalar dependencias:
   ```bash
   npm install
   ```
2. Iniciar el servidor de desarrollo:
   ```bash
   npm run serve
   ```

---

## 🌟 Autor

**Tomás González**  
📧 **[tomas@example.com](mailto:tomas@example.com)**  
💼 **Técnico Informático | Desarrollador | Formador**

---

## 📢 Abierto a Nuevas Oportunidades

Estoy abierto a trabajar en proyectos relacionados con desarrollo de software, formación en tecnologías y consultoría tecnológica. ¡Contáctame para colaborar!
#   t a s k - m a n a g e m e n t - s y s t e m  
 