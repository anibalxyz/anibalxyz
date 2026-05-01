<h1 align="center">👋 Hola, soy Anibal Boggio</h1>

<p align="center">
  <em>Desarrollador Web enfocado en <strong>Backend</strong> con interés en <strong>Platform Engineering</strong>, <strong>automatizaciones</strong> e <strong>integraciones de IA</strong>.</em>
</p>

<div align="center">
  <a href="#proyectos-destacados">💼 Proyectos</a> •
  <a href="#sobre-mi">✨ Un poco sobre mí</a> •
  <a href="#contacto">📬 Contacto</a> •
  <a href="README.md">🇬🇧 English Version</a>
</div>

---

<h2 id="proyectos-destacados">💼 Proyectos Destacados</h2>

### **[Reconciler](https://github.com/anibalxyz/reconciler)** (Proyecto personal, en desarrollo)

| Backend | Frontend | Infraestructura & Herramientas |
| ------- | -------- | ------------------------------- |
| ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Javalin](https://img.shields.io/badge/Javalin-000000?style=flat-square) ![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![Flyway](https://img.shields.io/badge/Flyway-CC3333?style=flat-square&logo=flyway&logoColor=white) ![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=junit5&logoColor=white) ![Mockito](https://img.shields.io/badge/Mockito-8F0000?style=flat-square) ![SLF4J](https://img.shields.io/badge/SLF4J-000000?style=flat-square) ![OpenAPI](https://img.shields.io/badge/OpenAPI-6BA539?style=flat-square&logo=openapi-initiative&logoColor=white) ![Swagger UI](https://img.shields.io/badge/Swagger_UI-85EA2D?style=flat-square&logo=swagger&logoColor=black) | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![Astro](https://img.shields.io/badge/Astro-FF5D01?style=flat-square&logo=astro&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Typer](https://img.shields.io/badge/Typer-000000?style=flat-square) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) ![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apache-maven&logoColor=white) |

**Descripción:** Plataforma modular para la conciliación de transacciones financieras. Construida siguiendo principios de Arquitectura Limpia y flujos de desarrollo profesionales.

La versión inicial (v0.1.0) incluye:

- **Sistema de autenticación:** Registro de usuarios, login, refresh de tokens y control de acceso basado en JWT
- **API Backend:** Microframework Javalin con PostgreSQL, suite de pruebas extensa que cubre casi todo el código
- **Infraestructura:** Entorno de desarrollo basado en Docker, CI/CD con GitHub Actions y releases automatizados
- **Herramienta CLI:** Python + Typer para simplificar flujos de trabajo (ver sección dedicada abajo)
- **Documentación:** READMEs completos (inglés y español), CONTRIBUTING.md, OpenAPI/Swagger UI y documentación interna de paquetes

Estructura de frontend preparada (dashboard en React + sitio público en Astro), implementación de UI en progreso.

---

### **[Reconciler CLI](https://github.com/anibalxyz/reconciler)** (Parte de Reconciler)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Typer](https://img.shields.io/badge/Typer-000000?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)

**Descripción:** Interfaz de línea de comandos para gestionar el entorno Docker de Reconciler y automatizar flujos de desarrollo. Construida con Python y Typer, siguiendo una arquitectura modular para facilitar su extensión.

Incluye:

- **Gestión simplificada de Docker:** Abstrae comandos complejos de `docker compose` con múltiples flags y configuraciones
- **Cambio de entornos:** Alternancia fluida entre entornos dev, test y prod
- **Ejecución de tests:** Lanzamiento rápido de pruebas con el entorno correcto
- **Gestión de imágenes:** Build y tag de imágenes Docker con nombres consistentes
- **Diseño modular:** Separación clara de responsabilidades (módulos compose, image, resource, config) para facilitar mantenimiento

---

### **[Simulador MARIE - Modernizado](https://github.com/anibalxyz/marie)** (Automatización y Accesibilidad)

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apache-maven&logoColor=white)
![Shell Script](https://img.shields.io/badge/Shell_Script-121011?style=flat-square&logo=gnu-bash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)

**Descripción:** Modernización del simulador MARIE original (v1.3.01) para permitir que usuarios de cualquier nivel puedan ejecutarlo sin fricciones técnicas. El programa original se mantuvo casi intacto, centrando el trabajo en automatizar la configuración y unificar la navegación entre herramientas.

Características clave:

- **Sin Fricciones Técnicas:** Scripts automatizados para Linux y Windows que instalan Java (JRE/JDK) de forma portátil y local, sin necesidad de permisos de administrador ni configuración manual de variables de entorno.
- **Herramientas Unificadas:** Unificación de los dos programas independientes en un solo punto de entrada, añadiendo un menú para navegar fluidamente entre el Simulador y el DataPath.
- **Listo para Usar:** Optimizado para ejecutarse desde un JAR pre-compilado, permitiendo a usuarios no técnicos saltarse el proceso de compilación por completo.
- **Accesos Directos:** Generadores de accesos directos al escritorio para facilitar el acceso rápido desde el sistema operativo.

---

### **[Sistema de Gestión de E-commerce](https://github.com/anibalxyz/proyectoeme)** (Proyecto académico)

| Backend | Frontend |
| ------- | -------- |
| ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Apache](https://img.shields.io/badge/Apache-D22128?style=flat-square&logo=apache&logoColor=white) ![Composer](https://img.shields.io/badge/Composer-885630?style=flat-square&logo=composer&logoColor=white) | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |

**Descripción:** Proyecto académico para la gestión de múltiples tiendas de e-commerce utilizando un framework MVC propio inspirado en Laravel. Incluye enrutamiento, plantillas de vistas, autenticación JWT, ORM y API RESTful.

---

<h2 id="github-stats">📊 Estadísticas de GitHub</h2>

<div align="center">
  <img alt="Estadísticas de GitHub" src="https://github-readme-stats-fast.vercel.app/api?username=anibalxyz&show_icons=true&count_private=true&theme=tokyonight&locale=es" />
  <img alt="Lenguajes Principales" src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=anibalxyz&layout=compact&hide=hack&theme=tokyonight&locale=es" />
</div>

---

<h2 id="sobre-mi">✨ Un poco sobre mí</h2>

- Español nativo | Inglés: B1 (CEFR), certificado en examen Cambridge A2
- Estudiante de **Tecnólogo en Informática** en **UTU (LATU)** - Horario nocturno, con disponibilidad para trabajar a tiempo completo
- Graduado de **Bachillerato de Informática Bilingüe con énfasis en Desarrollo Web** en UTU IAE Montevideo (2022–2024)
- Ex-estudiante de **Ingeniería en Computación** en **FING, UDELAR (2025)**; pausado en su momento para centrarme en mi formación autodidacta
- **Asistente Técnico Junior** en Arnaldo C. Castro (2023–2024)

---

<h2 align="center" id="contacto">👋 Gracias por visitar</h2>

<div>
  <p align="center">¡Ponte en contacto conmigo a través de cualquiera de las plataformas a continuación!</p>
</div>

<div align="center">
  <a href="mailto:anibalboggioict@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://linkedin.com/in/anibalboggio"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://wa.me/59895578511"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=flat-square&logo=whatsapp&logoColor=white" alt="WhatsApp"></a>
</div>
