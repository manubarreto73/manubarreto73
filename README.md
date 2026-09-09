# Manuel Barreto Amaya

## Fullstack Developer || Analista Programador Universitario (APU)

Desarrollador Fullstack con experiencia en desarrollo de aplicaciones web, construcción de interfaces frontend y desarrollo de APIs REST. Actualmente estoy especializándome en el desarrollo web utilizando React con TypeScript y Tailwind para el front y Java con SpringBoot para el back, pero también participé en otros desarrollos utilizando .NET, Ruby on Rails o Flask, entre otros.

Como desarrollador, tengo interés técnico en diseño de software sostenible, aplicando patrones de diseño y realizando refactoring, así como interés en la gestión de bases de datos, con experiencia en frameworks de manejo de BD relaciones (Hibernate, entre otros) y no relaciones (MongoDb). También tengo experiencia encargandome de la elicitación y específicación de los requerimientos y el trato con el cliente en proyectos reales. 

Estoy graduado de Analista Programador Universitario por la Universidad Nacional de La Plata. Actualmente finalizando la Licenciatura en Sistemas y desempeñándome como ayudante alumno en materias las materias Bases de Datos I y II.

## Proyectos

### Modelo PipoE: plataforma web de planificación

Espacio de trabajo colaborativo para llevar adelante procesos de planificación con el Modelo PipoE. Cada proyecto se recorre paso por paso sobre un editor de texto enriquecido con guardado continuo e historial de cambios, admite equipos de trabajo con permisos diferenciados por componente, y exporta los productos de cada etapa a Word y PDF. Incluye un panel de administración para resolver solicitudes de acceso, editar contenidos del sitio y definir cupos del sistema.

- Rol: relevamiento de requerimientos con la autora del modelo, modelado de base de datos, diseño de la arquitectura, desarrollo de la API y del frontend, testing y puesta en producción.
- Autenticación y seguridad: JWT con refresh token rotativo y detección de reuso, autorización por rol y control de acceso granular por componente, y bloqueo por intentos fallidos sobre Redis.
- Despliegue: Docker y Docker Compose, VPS Linux endurecido (UFW, fail2ban, SSH por clave), nginx como proxy inverso con HTTPS y Let's Encrypt, DNS, SMTP y backups automatizados de la base.
- Tecnologías: Java, Spring Boot, Spring Security, Spring Data JPA, Hibernate, Maven, PostgreSQL, Redis, Flyway, React, TypeScript, Vite, Tailwind CSS, Docker, nginx y Linux.
- Sitio: https://modelopipoe.com
- Repositorio: https://github.com/manubarreto73/Sistema-Pipoe

### Chatbot FedPat: atención automatizada por WhatsApp

Chatbot de WhatsApp que atiende a los clientes de un proveedor de seguros de Federación Patronal, resolviendo consultas frecuentes —pólizas, siniestros, asistencia mecánica, cotizaciones y ART— mediante menús interactivos. Cuando el cliente pide hablar con una persona, el bot abre un ticket y la conversación pasa a un inbox web donde los operadores la atienden en tiempo real. Incluye historial de conversaciones con imágenes y audios, notificaciones al operador por WhatsApp, y un panel para configurar horarios de atención y feriados.

- Rol: elicitación de requerimientos con el cliente, diseño del motor de flujos conversacionales y la arquitectura, modelado de base de datos, desarrollo de la API y del frontend, gestión del alta ante Meta y la aseguradora, testing y puesta en producción.
- Integración con WhatsApp API: recepción de mensajes por webhook con validación de firma HMAC, envío de mensajes interactivos y plantillas aprobadas, y gestión de archivos multimedia con política de retención.
- Integración con API de Federación Patronal: autenticación OAuth2 con cacheo y rotación del token sobre Redis, y consulta en línea del certificado de tarjeta de circulación desde el flujo conversacional.
- Autenticación y seguridad: JWT con refresh token rotativo y revocación por lista negra sobre Redis, autorización por rol, bloqueo por intentos fallidos, y autenticación del canal WebSocket durante el handshake.
- Despliegue: Docker y Docker Compose, VPS Linux endurecido (UFW, fail2ban, SSH por clave), nginx como proxy inverso con HTTPS y Let's Encrypt, DNS, y tareas programadas de backups y depuración de archivos multimedia.
- Tecnologías: Java, Spring Boot, Spring Security, Spring Data JPA, Hibernate, Maven, PostgreSQL, Redis, Flyway, WebSocket con STOMP, React, TypeScript, Vite, React Query, Docker, nginx y Linux.
- Sitio: https://bot.ecaconsultores.com.ar
- Repositorio: https://github.com/manubarreto73/Chatbot-FedPat

### API REST para sistema de punto de venta

Sistema multiempresa orientado a la gestión comercial de negocios, permitiendo administrar productos, stock, precios, ventas, compras a proveedores y clientes. Incluye gestión de usuarios por negocio con control de roles y permisos.

- Rol: relevamiento de requerimientos, modelado de base de datos, diseño de la arquitectura del sistema, desarrollo de la API y testing.
- Tecnologías: Java, Spring Boot, Spring Security, Spring Data JPA, Hibernate, PostgreSQL y Flyway.
- Repositorio: https://github.com/manubarreto73/stockeate-API

### Sistema de Gestión de Expedientes – Facultad de Ciencias Médicas UNLP

Sistema para la gestión administrativa del Honorable Consejo Directivo.

- Rol: elicitación y especificación de requerimientos, desarrollo e implementación, testing.
- Tecnologías: Ruby on Rails, Tailwind, SQLite.
- Repositorio: https://github.com/manubarreto73/Sistema-HCD-Facultad-de-Ciencias-Medicas

## Actividad académica

### Ayudante alumno en:
- Conceptos de Algoritmos, Datos y Programas (2024-2025)
- Taller de Programación (2024-2025)
- Bases de Datos 1 y 2 (2026-Actualidad)

## Idiomas

- Italiano nativo
- Inglés C1 (EF SET: https://cert.efset.org/es/NqiG7v)
