# Aplicación Web con Registro, Login y Dashboard en Docker

Este proyecto es una aplicación web que permite registrar usuarios, iniciar sesión y visualizar un dashboard con una lista de usuarios. Se ha implementado utilizando **Flask**, **MySQL**, y **Bootstrap**, y está contenida en un entorno **Docker** para facilitar su despliegue.

---

## Características

1. **Registro de usuarios**:
   - Permite crear una cuenta con un nombre de usuario y contraseña.
   - Las contraseñas se almacenan de forma segura utilizando **hashes**.

2. **Inicio de sesión (Login)**:
   - Valida las credenciales del usuario y crea una sesión segura.
   - Redirige al dashboard tras el inicio de sesión.

3. **Dashboard**:
   - Muestra a todos los usuarios registrados en formato **Bootstrap cards**.
   - Acceso restringido únicamente a usuarios autenticados.

4. **Cierre de sesión (Logout)**:
   - Finaliza la sesión activa y redirige a la página de inicio de sesión.

5. **Gestión de sesiones**:
   - Implementación completa para restringir el acceso a páginas según el estado de autenticación del usuario.

6. **Diseño visual**:
   - Utiliza **Bootstrap** para un diseño responsivo.
   - Incluye un estilo personalizado en el archivo `style.css` con efectos visuales y transiciones.

---

## Tecnologías Utilizadas

- **Backend**: Flask, SQLAlchemy, Flask-Login.
- **Base de datos**: MySQL.
- **Frontend**: Bootstrap 5.
- **Gestión de contenedores**: Docker y Docker Compose.
- **Panel de administración de base de datos**: PhpMyAdmin.

---

## Cómo Ejecutar el Proyecto

1. Construir y ejecutar los contenedores con Docker Compose:

   ```bash
   docker-compose up
   ```

2. Acceder a las interfaces:

   - **Aplicación web**: [http://localhost:8080](http://localhost:8080)
   - **PhpMyAdmin**: [http://localhost:8081](http://localhost:8081)  
     - Usuario: `root`
     - Contraseña: `root`

3. Para detener los contenedores, utiliza:

   ```bash
   docker-compose down
   ```

---


