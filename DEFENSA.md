# Guion de defensa — U4S7

Ajusta las partes entre corchetes para que describan tu proyecto y tus decisiones reales. Ensáyalo en voz alta con cronómetro; el objetivo es que dure cerca de dos minutos.

**0:00–0:30 — Qué hace el sistema**

“Mi proyecto es una aplicación para consultar y administrar servicios. Un usuario puede crear una cuenta, iniciar sesión y gestionar sus propios registros.”

**0:30–1:15 — Decisiones técnicas**

“Usé Django para organizar el proyecto con modelos, vistas y plantillas, y para aprovechar su sistema de autenticación. La aplicación guarda los servicios en MySQL con Aiven. El listado filtra por `propietario=request.user`, y las vistas de edición y eliminación buscan el registro junto con su propietario. Así cada cuenta trabaja solo con sus datos.”

**1:15–1:45 — Pulido de la interfaz**

“En esta versión agregué búsqueda por título, paginación de cinco registros y mensajes claros cuando no hay resultados. En pantallas pequeñas, la tabla permite desplazamiento horizontal. En la revisión por pares encontré [hallazgo real] y lo corregí con [cambio real].”

**1:45–2:00 — Cierre**

“La aplicación está en [URL real de Render] y el código está en [URL de GitHub]. Una mejora que puedo mostrar es [elige una: búsqueda, paginación o aislamiento entre usuarios].”
