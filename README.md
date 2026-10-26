# U4S8 — Cruz Bejarano Jorge Alejandro

## Demo en vivo (producción)
https://u4s8-cruz-bejarano-jorge-alejandro.onrender.com

## Qué hace este proyecto
Esta aplicación permite consultar y administrar servicios. Las personas pueden crear una cuenta e iniciar sesión para gestionar sus propios servicios, con información como título, descripción, precio y categoría.

El listado incluye búsqueda por título y paginación. Cada usuario ve y modifica únicamente los servicios que le pertenecen.

## Stack técnico
Django + MySQL (Aiven) + Tailwind CSS + Render

## Cómo se prueba el aislamiento por usuario
Inicia sesión con dos cuentas distintas. Crea un servicio con la primera cuenta y luego entra con la segunda: ese servicio no debe aparecer en su listado. La aplicación filtra los servicios por el usuario autenticado y verifica también la propiedad del registro al editarlo o eliminarlo, por lo que una cuenta no puede gestionar los servicios de otra.

## Historial de prácticas por unidad

### Unidad 1 — Front-End esencial
- **Semana 1:** estructura semántica con HTML5, secciones del portafolio personal, formulario con etiquetas y validación HTML, Git/GitHub y primer despliegue como sitio estático en Render.
- **Semana 2:** estilos con Tailwind CSS, diseño responsivo mobile-first con grid/flex, tarjetas y formulario estilizados, estados de interacción y revisión de accesibilidad/rendimiento con Lighthouse.

### Unidad 2 — Django y MySQL en la nube
- **Semana 3:** entorno virtual y proyecto Django; arquitectura MTV, vistas, rutas y plantillas; conexión mediante variables de entorno a MySQL en Aiven y migraciones.
- **Semana 4:** modelo `Servicio`, ORM y panel de administración; migraciones del modelo y despliegue dinámico en Render con Gunicorn, archivos estáticos y configuración del entorno.

### Unidad 3 — CRUD, autenticación y sesiones
- **Semana 5:** operaciones de crear, listar, editar y eliminar servicios con `ModelForm`, protección CSRF y validación de formularios; prueba del CRUD publicado.
- **Semana 6:** registro, login y logout con `django.contrib.auth`; sesiones, mensajes y `login_required`; asociación de servicios con su propietario y comprobación del aislamiento entre cuentas.

### Unidad 4 — Pulido y entrega final
- **Semana 7:** mejoras de experiencia de usuario, búsqueda, paginación y estados vacíos; revisión de interfaz, responsividad y accesibilidad; simulacro de live coding y preparación del guion de defensa.
- **Semana 8:** auditoría final de seguridad, respaldo de datos y revisión de migraciones; preparación del despliegue final, etiquetado y Release en GitHub, defensa oral y organización del portafolio final.
