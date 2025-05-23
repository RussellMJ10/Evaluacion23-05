# Evaluacion23-05
Estudiante: Russell Madariaga Jara  Seccion 2. 

1. Diagrama de Caso de Uso:
Error 1: Consultar Disponibilidad externa deberia de estar unida con un include a Revisar sala
Error 2: Estudiante no dberia de poder ver el historal de otras personas
Error 3:

2. Diagrama de Clases:
Error 1: Clase Reserva aislada de las demas, lo solocionaria uniendola a la clase SitemaReservas mediante una linea de una a muchas.
Error 2: NotificacionCorreo y NotificacionSMS tienen el mismo metodo notificar(), pero no hay interfaz comun, como solucion crearia una interfaz Notificador con el metodo notificar(mensaje: String).
Error 3: el atributo estado en la clase Reserva deberia ser un enum para estado que posea PENDIENTE, APROBADA, RECHAZADA, CANCELADA. 

3. Diagrama de Implementación:
Error 1: Que el navegador del estudiante implemente un singleton, los navegadores no deberian ser singleton, ya que mas usuarios podrian necesitar instancias independientes, de solucion daria el eliminar la mencion Singleton y lo reestructuraria como un modulo stateless.
Error 2: Adaptador sin implementacion clara, no se explica como se adapta la interfaz del sistema externo, la slucion seria mostrar la clase adaptadora. 
Error 3: No se muestran como se comunican el Navegador, el Controlador de Reservas y la Base de datos con exactitud, agregaria flechas con protocolos. 
