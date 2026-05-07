# Testimonial CMS - S03-26-Equipo08

## Descripción del Proyecto

Este proyecto es un **CMS especializado en Edtech** diseñado para que instituciones y empresas con comunidades activas puedan mostrar el impacto de sus programas o productos mediante historias reales. El sistema permite recopilar, organizar y publicar testimonios en distintos formatos (texto, video, imagen) con funciones de curaduría, moderación y analítica de engagement.

> [!IMPORTANT]
> Puedes consultar las especificaciones detalladas de roles, flujos y formularios en el archivo: [CONTEXTO_PROYECTO.md](./CONTEXTO_PROYECTO.md).

**Objetivo:** Construir un sistema CMS especializado en la gestión y publicación de testimonios y casos de éxito para sitios web e instituciones.

## Requerimientos Funcionales

- **Gestión Multimedia:** Creación y edición de testimonios con texto, imagen y video.
- **Clasificación:** Organización por categorías (producto, evento, cliente, industria).
- **Integración:** Embeds y API pública para integrar los testimonios en otras webs.
- **Moderación:** Sistema de revisión antes de la publicación oficial.
- **Búsqueda Avanzada:** Sistema de tags y búsqueda inteligente.

## Stack Tecnológico

- **Frontend:** React, Vanilla CSS.
- **Backend:** Java, Spring Boot, Spring Security (JWT), Hibernate / JPA.
- **Base de Datos:** Hibernate / JPA (vía Spring Data JPA).
- **Servicios Externos:** API de YouTube y Cloudinary (manejo multimedia).

## Roles del Sistema

- **Admin:** Control total del CMS y analíticas.
- **Editor:** Gestión y moderación de contenido.
- **Visitante:** Consulta de testimonios públicos.

## Diseño (Figma)

- [Acceder al diseño en Figma](https://www.figma.com/make/7pSM0BXRpccYHLbzLF5Iz5/CMS-para-testimonios?t=Gv5JJPkex9eRHR4c-0)

## Estructura del Proyecto

- `frontend/`: Interfaz de usuario y dashboard administrativo.
- `backend/`: API REST documentada y lógica de negocio.

## Entregables

- CMS funcional con dashboard de administración.
- Documentación de API para consulta externa.
- Demostración de integración en sitio externo.

## Instalación y Configuración

Instrucciones detalladas en cada subcarpeta.

## 🚀 Mis Contribuciones (Frontend)

En este proyecto, lideré el desarrollo de módulos críticos del dashboard administrativo, priorizando la escalabilidad del código y la fluidez de la interfaz:

* **Arquitectura de Categorías:** Diseñé e implementé la lógica integral de gestión de etiquetas, integrando un selector de color dinámico y sincronización en tiempo real con el backend mediante peticiones asíncronas.
* **UI/UX:** Desarrollé un sistema de modales personalizados con estética "Galaxy Design" y efectos de glassmorphism, elevando la calidad visual del feedback del sistema.
* **Robustez y Seguridad:** Gestioné la integración con la API REST (Spring Boot), implementando el manejo de tokens JWT para asegurar rutas protegidas y una experiencia de usuario sin fricciones.

## Equipo

| Nombre                | Rol                  | LinkedIn                                            |
| :-------------------- | :------------------- | :---------------------------------------------------|
| **Maximo Demo**       | Full Stack Developer | [LinkedIn](https://www.linkedin.com/in/maximodemo/) |
| Hernan Casasola       | Tech Lead            |                                                     |
| Lautaro Frioni        | Frontend Developer   |                                                     |
| Lorenzo Ruggeri       | Backend Developer    |                                                     |
| Federico Spagnolo     | Backend Developer    |                                                     |
| Carla Joumier         | UX/UI Designer       |                                                     |
| Camila Nocella        | QA Tester            |                                                     |

---

Copyright (c) 2026 Equipo 08 - No Country
