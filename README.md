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

En este proyecto, me enfoqué en la arquitectura del dashboard administrativo y la experiencia de usuario. Mis principales tareas incluyeron:
* **Módulo de Categorías:** Desarrollé desde cero la lógica de gestión de categorías, integrando selectores de color dinámicos y validaciones personalizadas con el backend.
* **Componentes Globales:** Implementé un sistema de modales dinámicos (estilo galaxia) con efectos de desenfoque (glassmorphism) para mejorar el feedback de usuario.
* **Consumo de APIs:** Conexión y manejo de estados asíncronos para la integración con el backend de Spring Boot, asegurando la consistencia de los datos multimedia.

## Equipo

| Nombre                | Rol                  | LinkedIn                                         |
| :-------------------- | :------------------- | :------------------------------------------------|
| **Maximo Demo**       | Full Stack Developer | [LinkedIn](www.linkedin.com/in/maximodemo/)      |
| Hernan Casasola       | Tech Lead            |                                                  |
| Lautaro Frioni        | Frontend Developer   |                                                  |
| Lorenzo Ruggeri       | Backend Developer    |                                                  |
| Federico Spagnolo     | Backend Developer    |                                                  |
| Carla Joumier         | UX/UI Designer       |                                                  |
| Camila Nocella        | QA Tester            |                                                  |

---

Copyright (c) 2026 Equipo 08 - No Country
