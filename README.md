# notificaciones-service

Microservicio de la actividad Arepa Express (DOSW 1, semana 14). Escucha la cola `notificaciones.pedidos`, unida al exchange `arepas.eventos` con la routing key `pedido.creado`, y registra el aviso al cliente de que su pedido fue recibido.

**Autor:** Juan Nicolás Álvarez Muñoz
