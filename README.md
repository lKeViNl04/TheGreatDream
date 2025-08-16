# 🌟 The Great Dream

[![Java](https://img.shields.io/badge/Java-24-blue)](https://www.oracle.com/java/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.2.0-green)](https://spring.io/projects/spring-boot)
[![Angular](https://img.shields.io/badge/Angular-20-red)](https://angular.io/)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

## 📖 Descripción del proyecto
The Great Dream es un proyecto full-stack diseñado para la **gestión de finanzas y miembros de una comunidad**.  
Actualmente, la página permite:

- Gestionar **cajas de dinero** (`CashBox`) con operaciones de agregar, editar y eliminar.
- Administrar **miembros** de la comunidad (crear, editar, eliminar).
- Registrar **gastos mensuales** y **cuotas mensuales** de los miembros.
- Mostrar información en **tablas y componentes interactivos** con filtros y paginación.

El proyecto combina un **backend en Java 24 con Spring Boot** y un **frontend en Angular**.

---

## 🛠 Tecnologías utilizadas

### Backend
- **Java 24**
- **Spring Boot**
- **Maven** para gestión de dependencias
- **Spring Data JPA** para acceso a la base de datos
- **Spring Security y validaciones** para seguridad y control de datos
- **Controladores REST** para exponer endpoints
- **DTOs y mappers** para manejo de datos entre capas

### Frontend
- **Angular** (20)
- **TypeScript**
- **SCSS y CSS** para estilos
- **Componentes modulares** organizados por funcionalidad
- **Servicios** para consumo de la API REST
- **Rutas y navegación** para diferentes páginas y vistas

---

## Requisitos previos

Antes de ejecutar el proyecto, asegúrate de tener instalado en tu computadora:

1. **Java 24 JDK**
   
   ```bash
   java -version
3. **Maven**
   
   ```bash
   mvn -v
   
5. **Node.js** (v18+ recomendada)
   
    ```bash
    node -v
    npm -v

7. **Angular CLI**
   
    ```bash
    npm install -g @angular/cli
    ng version

9. **Git**
    
    ```bash
    git --version

---
## 📂 Estructura del proyecto
    
    TheGreatDream/
    ├─ backend/
    │  ├─ src/main/java/com/gatedcommunity/backend/
    │  │  ├─ controller/
    │  │  ├─ entity/
    │  │  ├─ mapper/
    │  │  ├─ repository/
    │  │  ├─ service/
    │  │  └─ config/
    │  ├─ src/main/resources/
    │  └─ pom.xml
    ├─ frontend/
    │  ├─ src/app/
    │  │  ├─ components/
    │  │  ├─ features/
    │  │  └─ services/
    │  ├─ src/environments/
    │  ├─ angular.json
    │  └─ package.json
    └─ README.md

---
## 🚀 Instalación y ejecución paso a paso
1. Clonar el repositorio
   
    ```bash
    git clone https://github.com/lKeViNl04/TheGreatDream.git
    cd TheGreatDream

3. Configurar y ejecutar el backend
    1. Ir a la carpeta backend:
       
        ```bash
        cd backend
    3. Instalar dependencias:
       
        ```bash
        ./mvnw clean install
    5. Ejecutar Spring Boot:
       
        ```bash
        ./mvnw spring-boot:run

4. Configurar y ejecutar el frontend

    1. Abrir otra terminal y moverse a la carpeta frontend:
       
        ```bash
        cd frontend

    3. Instalar dependencias:
       
        ```bash
        npm install
    2. Ejecutar Angular:
       
        ```bash
        ng serve

5. Conexión frontend-backend

    - El frontend consume automáticamente los endpoints REST del backend.
    - Asegúrate de tener ambos servidores corriendo para poder interactuar con la aplicación.

---

## ⚠️ Notas importantes

- El proyecto utiliza DTOs y mappers para separar la capa de datos de la lógica de negocio.

- Se recomienda usar un IDE como IntelliJ o VSCode para facilitar el desarrollo.

- Verifica que tu JAVA_HOME esté apuntando a Java 24.

- Los archivos .gitignore ya están configurados para ignorar dependencias y archivos locales.







