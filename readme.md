# FullStack E-Commerce App – Spring Boot 3.2.0 & Angularv16

## 📦 Tecnologías

- **Back-end:** Java 21, Spring Boot 3.2.0, Spring Security, Spring Data JPA, Hibernate
- **Front-end:** Angular 16, Bootstrap, Font Awesome
- **Base de Datos:** MySQL (Dockerizada)
- **Autenticación:** JWT (JSON Web Tokens)
- **API:** RESTful APIs

## 🎯 Descripción

Aplicación full-stack de e-commerce desarrollada con Java y Angular. El sistema permite experiencia de compra para clientes, autenticación segura. 

## ✅ Aspectos principales

### 🔧 Back-end (Spring Boot)
- Estructura modular con servicios, controladores y repositorios
- Pager
- Registro y login de usuarios con JWT (Stateless)
- Seguridad de endpoints con Spring Security
- Manejo de roles (ADMIN, USER)
- Persistencia de datos con Spring Data JPA
- Caché Cart management con Redis

### 🎨 Front-end (Angular)
- Interfaz de usuario responsive con Bootstrap
- Navegación entre páginas con Angular Router
- Formularios reactivos
- Carrito de compras
- Registro e inicio de sesión de usuarios
- Protección de rutas mediante guards
- Componentes modulares
- Emisores de Eventos
- Subscripciones y Behavior Subject
- Landing Page
- LocalStorage for cart

## 🧩 Estructura del proyecto

### Server Side (`springboot-backend`)
```
src/
├── config
├── controller
├── entity
├── exception
├── model
├── repository
├── security
├── service
```

### Client Side (`angular-frontend`)
```
src/
├── app
│   ├── pages**
│   ├── core**
│   ├── shared
│   ├── guards
│   └── assests
```

## 📈 Flujo de la aplicación

1. El cliente accede a la aplicación web y navega entre productos.
2. Puede registrarse e iniciar sesión.
3. Una vez autenticado, puede agregar productos al carrito y realizar pedidos.


## 📌 Estado del proyecto

- Proyecto funcional, se incluyen funcionalidades básicas de un e-commerce moderno con autenticación, roles y diseño responsive.
