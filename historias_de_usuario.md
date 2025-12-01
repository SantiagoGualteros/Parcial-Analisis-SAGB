HISTORIAS DE USUARIO
HU-01 – Registrar solicitud de soporte
Como usuario del CAT (estudiante, docente o administrativo),
quiero registrar una solicitud de soporte técnico,
para recibir atención organizada y asegurar trazabilidad de mi caso.

Estimación: 5 puntos
Justificación: Requiere formulario, validaciones, conexión con API y almacenamiento. Es funcionalidad esencial pero no tiene lógica compleja.



HU-02 – Autenticación y roles
Como usuario del sistema,
quiero poder iniciar sesión según mi rol (usuario, técnico, administrador),
para acceder únicamente a las funcionalidades correspondientes a mi perfil.

Estimación: 8 puntos
Justificación: Involucra seguridad, manejo de sesiones, roles, permisos y control de acceso. Es más complejo e involucra backend y middleware.



HU-03 – Asignar solicitudes a técnicos
Como administrador o coordinador,
quiero asignar solicitudes a técnicos disponibles,
para distribuir el trabajo adecuadamente y agilizar la atención.

Estimación: 8 puntos
Justificación: Implica lógica de negocio, estado de solicitudes, disponibilidad, endpoints y controles adicionales.



HU-04 – Cambiar estado de las solicitudes
Como técnico,
quiero actualizar el estado de las solicitudes (Pendiente, En Progreso, Escalada, Resuelta, Cerrada),
para reflejar el avance del trabajo de manera transparente.

Estimación: 5 puntos
Justificación: Implica manejo de estados y actualizaciones simples, sin algoritmos complejos.



HU-05 – Gestionar prioridades
Como administrador,
quiero modificar la prioridad de una solicitud (Baja, Media, Alta, Crítica),
para garantizar que los casos urgentes reciban atención inmediata.

Estimación: 3 puntos
Justificación: Cambio de atributos y validaciones simples; no requiere desarrollo intensivo.



HU-06 – Consultar solicitudes propias
Como usuario del CAT,
quiero ver el estado y los detalles de mis solicitudes,
para hacer seguimiento sin necesidad de contactar al soporte.

Estimación: 5 puntos
Justificación: Requiere consultas filtradas por usuario, interfaz dedicada y validación de roles.



HU-07 – Dashboard para técnicos
Como técnico del CAT,
quiero ver en un panel mis solicitudes asignadas con sus prioridades y estados,
para gestionar mi trabajo de forma eficiente.

Estimación: 8 puntos
Justificación: Interfaz con múltiples listas, ordenamiento, filtros y consumo de varios endpoints.



HU-08 – Reportes del sistema
Como administrador,
quiero generar reportes sobre tiempos de atención, solicitudes por estado, técnico y prioridades,
para analizar el rendimiento del CAT y tomar decisiones informadas.

Estimación: 13 puntos
Justificación: Requiere agregaciones, filtros complejos, posible exportación de datos y cálculo de métricas.



HU-09 – Notificaciones de cambios
Como usuario,
quiero recibir notificaciones cuando una solicitud cambie de estado, prioridad o técnico,
para estar informado oportunamente sin revisar manualmente el sistema.

Estimación: 8 puntos
Justificación: Implica triggers o eventos internos, posible integración con correo o notificaciones internas, y manejo de colas.



HU-10 – Registro de actividades (bitácora)
Como administrador,
quiero que el sistema registre cada cambio realizado sobre una solicitud,
para garantizar trazabilidad y auditoría completa.

Estimación: 5 puntos
Justificación: Implica crear un historial y guardar eventos, pero con lógica relativamente sencilla.



HU-11 – Interfaz de registro de solicitudes (frontend)
Como usuario,
quiero una interfaz fácil de usar para registrar solicitudes,
para asegurar que el proceso sea intuitivo y rápido.

Estimación: 3 puntos
Justificación: Desarrollo de UI, validaciones y conexión a APIs; no es complejo a nivel backend.



HU-12 – Pruebas del sistema
Como equipo de desarrollo,
quiero realizar pruebas unitarias e integradas del sistema,
para garantizar la calidad del software antes de su despliegue.

Estimación: 5 puntos
Justificación: Requiere cubrir módulos clave; depende de las historias principales pero no involucra nuevas funcionalidades.
