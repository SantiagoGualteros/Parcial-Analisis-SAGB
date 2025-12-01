REQUERIMIENTOS
REQUERIMIENTOS FUNCIONALES
RF1. Registro de solicitudes:
El sistema debe permitir que los usuarios registrados (estudiantes, docentes y administrativos) creen solicitudes de soporte técnico indicando categoría, descripción y prioridad inicial.

RF2. Autenticación y gestión de roles:
El sistema debe permitir el inicio de sesión y controlar el acceso según el rol del usuario (Usuario, Técnico, Administrador).

RF3. Asignación de solicitudes:
El sistema debe permitir que los administradores asignen solicitudes de soporte a los técnicos disponibles.

RF4. Actualización del estado de las solicitudes:
El sistema debe permitir que los técnicos modifiquen el estado de las solicitudes a cualquiera de los estados definidos: Pendiente, En progreso, Escalada, Resuelta, Cerrada.

RF5. Consulta de solicitudes por usuario:
El sistema debe permitir que cada usuario visualice únicamente sus solicitudes junto con su estado y detalles relevantes.

RF6. Generación de reportes:
El sistema debe permitir a los administradores generar reportes sobre solicitudes por técnico, estado, prioridad y tiempos de resolución.



REQUERIMIENTOS NO FUNCIONALES
RNF1. Seguridad:
El sistema debe proteger la información mediante autenticación segura, manejo adecuado de contraseñas y restricciones de acceso basadas en roles.

RNF2. Rendimiento:
El sistema debe permitir la carga de dashboards y listas de solicitudes en menos de 3 segundos bajo operación normal.

RNF3. Escalabilidad:
El sistema debe estar diseñado de forma modular para soportar un aumento en la cantidad de usuarios y solicitudes sin afectar el rendimiento.

RNF4. Usabilidad:
La interfaz del sistema debe ser intuitiva, clara y accesible, permitiendo a los usuarios registrar o consultar solicitudes sin necesidad de capacitación previa.

RNF5. Disponibilidad:
El sistema debe estar disponible como mínimo el 99% del tiempo laboral de la universidad (lunes a sábado de 8am a 6pm).

RNF6. Mantenibilidad:
El código debe estar estructurado y documentado para facilitar futuras actualizaciones, correcciones o ampliaciones del sistema.
