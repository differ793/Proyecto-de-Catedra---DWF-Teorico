# Proyecto de Catedra DWF Teorico
sistema de venta y administración de boletos aéreos

Link de TRELLO https://trello.com/invite/b/68a5dc407c94cf05d6608688/ATTIb3b71990969fce1dc7ff2146742342dd46472A23/proyectodwf

Daniel Alexander Girón Cornejo GC221469 Cristian Gerardo Ventura Rendón VR221500 Francisco Armando Morales Flores MF230357 Diego Fernando Ruiz Valle RV232739

Cobertura funcional esperada: El sistema deberá ser capaz de gestionar aerolíneas, aeropuertos, rutas, aeronaves, tripulación y pasajeros infinitos; así como soportar búsqueda de vuelos, selección de asiento, creación de reserva, pago, cancelación y gestión de reclamos infinitos.

Consistencia de datos: Con restricciones relacionales y controles transaccionales permiten que un asiento no pueda asignarse a su vez a una reserva y que las operaciones críticas sean atómicas.

Control de concurrencia: En teoría, el uso de bloqueos/locks o mecanismos optimistas evita el double-booking (overbooking) ante accesos concurrentes.

Accesibilidad y capacidad de respuesta: La indexación y el diseño modular garantizan respuestas rápidas en búsquedas y un tratamiento eficaz de reservas; la capacidad operativa real dependerá de la infraestructura y su dimensionado con el hardware adecuado.

Seguridad y acceso: Un modelo de roles proporciona una separación y especificación de los permisos (administración, personal de aerolínea, agentes, pasajeros, soporte) para garantizar que las operaciones sensibles sólo sean ejecutadas por los actores adecuados.

Conclusión

Esperamos que nuestra API REST sea efectiva y logre simular de forma integral el funcionamiento de una aerolínea; aplicaremos todo lo aprendido en el curso, trabajando en equipo y bajo la guía de nuestro docente, para garantizar que cada funcionalidad opere de la mejor manera posible y que el proyecto se consolide como una experiencia de aprendizaje sólida y práctica.
