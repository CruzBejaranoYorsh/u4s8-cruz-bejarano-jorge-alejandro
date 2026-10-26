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

## Historial de unidades
- Unidad 1: portafolio estático con HTML5 + Tailwind.
- Unidad 2: modelo Servicio migrado a MySQL y despliegue dinámico en Render.
- Unidad 3: CRUD con ModelForms, autenticación y sesiones.
- Unidad 4: paginación, búsqueda, revisión de interfaz y defensa final.

