# 🏦 Sistema de Gestión Bancaria — Proyecto Final UTN

Este sistema fue desarrollado como **proyecto integrador final** para la **Tecnicatura Universitaria en Programación** en la UTN. Representa una solución completa para la gestión de un banco, integrando múltiples roles, operaciones y validaciones sobre una base de datos relacional.

📌 **Con la aprobación de este proyecto, finalizo mi carrera como Técnico Universitario en Programación.**

---

## 🚀 Demo

🔗 [Ver capturas y demo del proyecto](https://drive.google.com/drive/folders/1t8DK7pkJbPGbzHIlmLR53qEWtzNX_Gxe?usp=sharing)

---

## 🧠 Tecnologías utilizadas

- Java (JSP + Servlets)
- MySQL
- HTML, CSS, JavaScript
- Patrón de capas: JSP (Vista) — Servlet (Controlador) — Negocio (Lógica) — DAO (Acceso a datos)
- Manejo de sesiones con Cookies

---

## 👤 Roles y funcionalidades

### 🔐 Autenticación
- Login con distinción entre **Administrador** y **Cliente**
- Gestión de sesión mediante Cookies

### 🧑‍💼 Rol Administrador
- **Gestión de usuarios clientes** (ABML)
- **Gestión de cuentas bancarias** de cada cliente (hasta 3 por usuario)
- **Gestión y validación de préstamos** solicitados por los clientes
- **Generación de reportes y estadísticas** desde los datos en base

### 🧑‍💻 Rol Cliente
- Visualización de su perfil y cuentas
- **Transferencias entre cuentas** propias o de terceros
- **Solicitud de préstamos** en cuotas
- **Pago de cuotas** de préstamos vigentes
- Máximo de **3 cuentas activas por cliente**

---

## 📊 Características destacadas

- Validaciones completas en cada operación (por ejemplo, disponibilidad de fondos o cantidad de cuentas permitidas)
- División clara en capas para mantener la escalabilidad del código
- Interfaz simple y funcional para facilitar la interacción del usuario
- Manejo eficiente de estados de préstamos, cuotas y saldos

---

## 📚 Aprendizajes clave

- Implementación de autenticación y control de acceso por rol
- Aplicación del patrón MVC adaptado a Servlets y JSP
- Separación de lógica en capas (Vista - Controlador - Negocio - DAO)
- Conexión robusta a base de datos MySQL con consultas seguras y dinámicas
- Uso práctico de sesiones, cookies y validación de formularios
- Diseño e implementación de operaciones bancarias reales simuladas

---

## 📝 Notas finales

Este sistema me permitió integrar y aplicar de forma práctica los conocimientos adquiridos a lo largo de toda la carrera: desde la lógica de programación, el trabajo con bases de datos relacionales y la arquitectura de aplicaciones empresariales, hasta la experiencia del usuario y el control de flujo del sistema.

