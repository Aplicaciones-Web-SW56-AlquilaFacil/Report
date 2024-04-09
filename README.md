# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping
**Propietario de Espacio para Eventos**
![toBePropietario](/assets/img/Tobe_Scenario_Mapping_Propietario.jpg)

**Usuario para Búsqueda de Espacio para Eventos**
![tobeUsuario](/assets/img/Tobe_Scenario_Mapping_Usuario.jpg)

## 3.2. User Stories
<table>
    <thead>
        <tr>
            <th>Epic / Story ID</th>
            <th>Título</th>
            <th>Descripción</th>
            <th>Criterios de Aceptación</th>
            <th>Relacionado con (Epic ID)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>EPIC-001</td>
            <td>Registro y Gestión de Espacios</td>
            <td>
                <strong>Como</strong> propietario de un espacio para eventos en AlquilaFácil, 
                <strong>quiero</strong> poder registrar y gestionar fácilmente mis espacios disponibles 
                <strong>para</strong> atraer a potenciales organizadores de eventos y administrar eficientemente las reservas.
            </td>
            <td>N/A</td>
            <td>N/A</td>         
        </tr>
        <tr>
            <td>EPIC-002</td>
            <td>Búsqueda y Reserva de Espacios</td>
            <td>
                <strong>Como</strong> organizador de eventos en AlquilaFácil, 
                <strong>quiero</strong> poder buscar y reservar espacios para mis eventos de manera sencilla y conveniente 
                <strong>para</strong> encontrar la ubicación perfecta que se adapte a mis necesidades y preferencias.
            </td>
            <td>N/A</td>
            <td>N/A</td>
        </tr>
        <tr>
            <td>EPIC-003</td>
            <td>Interacción y Comunicación Directa</td>
            <td>
                <strong>Como</strong> usuario de AlquilaFácil, 
                <strong>quiero</strong> poder interactuar y comunicarme directamente con los propietarios de espacios 
                <strong>para</strong> aclarar dudas, discutir detalles y confirmar reservas de manera efectiva y rápida.
            </td>
            <td>N/A</td>
            <td>N/A</td>
        </tr> 
        <tr>
            <td>EPIC-004</td>
            <td>Calificaciones y Comentarios</td>
            <td>
                <strong>Como</strong> usuario de AlquilaFácil, 
                <strong>quiero</strong> poder dejar calificaciones y comentarios sobre los espacios y su experiencia de alquiler 
                <strong>para</strong> ayudar a otros usuarios a tomar decisiones informadas y mejorar la calidad del servicio.
            </td>
            <td>N/A</td>
            <td>N/A</td>
        </tr> 
        <tr>
            <td>EPIC-005</td>
            <td>Gestión de Reservas</td>
            <td>
                <strong>Como</strong> usuario de AlquilaFácil, 
                <strong>quiero</strong> tener la capacidad de gestionar mis reservas de manera eficiente y flexible 
                <strong>para</strong> adaptarme a cambios de horarios y necesidades de evento.
            </td>
            <td>N/A</td>
            <td>N/A</td>       
        </tr>   
        <tr>
            <td>EPIC-006</td>
            <td>Seguridad y Confianza</td>
            <td>
                <strong>Como</strong> usuario de AlquilaFácil, 
                <strong>quiero</strong> sentirme seguro al realizar transacciones y reservas en la plataforma 
                <strong>para</strong> confiar en la integridad del servicio y la protección de mis datos personales.
            </td>
            <td>N/A</td>
            <td>N/A</td>
        </tr>  
    </tbody>
</table>

<table>
    <thead>
        <tr>
            <th>Epic / Story ID</th>
            <th>Título </th>
            <th>Descripción</th>
            <th>Criterios de Aceptación</th>
            <th>Relacionado con (Epic ID)</th>
        </tr>
    </thead>
    <body>
        <tr style="text-align:center">
            <td>UH01</td>
            <td>Hipervínculos en el encabezado</td>
            <!-- Descripción -->
            <td> 
            <strong>Como</strong> visitante de la plataforma AlquilaFácil, 
            <strong>quiero</strong> que las opciones del menú de navegación me dirijan a las diferentes secciones de la plataforma 
            <strong>para</strong> poder acceder rápidamente a la información que necesito. 
            </td>
            <!-- ---------- -->
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: Navegación fluida</h5>
            <strong>Dado</strong> que un usuario ha ingresado a la plataforma AlquilaFácil.
            <strong>Cuando</strong> el usuario hace clic en una opción del menú de navegación.
            <strong>Entonces</strong> la página se desplaza suavemente a la nueva sección seleccionada.
            <strong>Y</strong> la URL de la página cambia para reflejar la nueva sección.
            <!-- ---------- -->
            <h5>Escenario 02: Adaptación a dispositivos</h5>
            <strong>Dado</strong> que un usuario visita la plataforma desde un dispositivo móvil.
            <strong>Cuando</strong> el usuario hace clic en una opción del menú de navegación.
            <strong>Entonces</strong> la página se desplaza suavemente a la sección correspondiente, adaptándose al tamaño de la pantalla del dispositivo.
            </td> 
            <td>EPIC-001</td>           
        </tr>
        <tr style="text-aling:center">
            <td>UH02</td>
            <td>Registro de Propietario</td>
            <!-- Descripción -->
            <td> 
            <strong>Como</strong> propietario de un espacio para eventos, 
            <strong>quiero</strong> poder registrarme fácilmente en AlquilaFácil 
            <strong>para</strong> ofrecer mi espacio en alquiler y llegar a más clientes potenciales.
            </td>
            <!-- ---------- -->
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: Registro exitoso</h5>
            <strong>Dado</strong> que un propietario desea registrar su espacio en AlquilaFácil.
            <strong>Cuando</strong> el propietario completa el formulario de registro con la información requerida.
            <strong>Entonces</strong> el propietario recibe una confirmación de registro y puede acceder a su cuenta.
            <!-- ---------- -->
            <h5>Escenario 02: Validación de datos</h5>
            <strong>Dado</strong> que un propietario completa el formulario de registro en AlquilaFácil.
            <strong>Cuando</strong> el propietario envía el formulario.
            <strong>Entonces</strong> los datos proporcionados se validan para garantizar la precisión y la autenticidad.
            </td>
            <td>EPIC-001</td>
        </tr>
        <tr style="text-aling:center">
            <td>UH03</td>
            <td>Búsqueda y Filtrado de Espacios</td>
            <!-- Descripción -->
            <td> 
            <strong>Como</strong> organizador de eventos, 
            <strong>quiero</strong> poder buscar y filtrar fácilmente espacios disponibles en AlquilaFácil 
            <strong>para</strong> encontrar el lugar perfecto para mi evento, según mis criterios específicos.
            </td>
            <!-- ---------- -->
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: Búsqueda por ubicación</h5>
            <strong>Dado</strong> que un organizador busca un espacio para eventos en una ubicación específica.
            <strong>Cuando</strong> el organizador ingresa la ubicación deseada en el campo de búsqueda.
            <strong>Entonces</strong> se muestran los espacios disponibles en esa ubicación.
            <!-- ---------- -->
            <h5>Escenario 02: Filtrado por capacidad</h5>
            <strong>Dado</strong> que un organizador desea un espacio con capacidad para un número específico de personas.
            <strong>Cuando</strong> el organizador aplica un filtro de capacidad en la búsqueda.
            <strong>Entonces</strong> se muestran solo los espacios que cumplen con ese criterio.
            </td>
            <td>EPIC-002</td>
        </tr>
        <tr style="text-aling:center">
            <td>UH04</td>
            <td>Reservas de Espacios</td>
            <!-- Descripción -->
            <td> 
            <strong>Como</strong> organizador de eventos, 
            <strong>quiero</strong> poder reservar un espacio para mi evento en AlquilaFácil 
            <strong>para</strong> garantizar su disponibilidad en la fecha deseada.
            </td>
            <!-- ---------- -->
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: Proceso de Reserva</h5>
            <strong>Dado</strong> que un organizador ha encontrado el espacio ideal en AlquilaFácil.
            <strong>Cuando</strong> el organizador selecciona el espacio y la fecha deseada.
            <strong>Entonces</strong> se muestra un formulario de reserva para completar los detalles del evento.
            <!-- ---------- -->
            <h5>Escenario 02: Confirmación de Reserva</h5>
            <strong>Dado</strong> que un organizador ha completado el formulario de reserva en AlquilaFácil.
            <strong>Cuando</strong> el organizador envía la solicitud de reserva.
            <strong>Entonces</strong> recibe una confirmación de reserva y los detalles se actualizan en su cuenta.
            </td>
            <td>EPIC-002</td>
        </tr>
        <tr style="text-aling:center">
            <td>UH05</td>
            <td>Calificaciones y Comentarios sobre Espacios</td>
            <!-- Descripción -->
            <td> 
            <strong>Como</strong> organizador de eventos, 
            <strong>quiero</strong> poder ver las calificaciones y comentarios de otros usuarios sobre los espacios en AlquilaFácil 
            <strong>para</strong> tomar una decisión informada al seleccionar un espacio para mi evento.
            </td>
            <!-- ---------- -->
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: Visualización de Calificaciones</h5>
            <strong>Dado</strong> que un organizador está revisando las opciones de espacios en AlquilaFácil.
            <strong>Cuando</strong> el organizador selecciona un espacio en particular.
            <strong>Entonces</strong> se muestran las calificaciones y comentarios de otros usuarios sobre ese espacio.
            <!-- ---------- -->
            <h5>Escenario 02: Aporte de Comentarios</h5>
            <strong>Dado</strong> que un organizador ha utilizado un espacio reservado a través de AlquilaFácil.
            <strong>Cuando</strong> el evento ha concluido.
            <strong>Entonces</strong> el organizador puede dejar un comentario y una calificación sobre su experiencia en ese espacio.
            </td>
            <td>EPIC-005</td>
        </tr>
        <tr style="text-aling:center">
            <td>UH06</td>
            <td>Notificaciones de Disponibilidad</td>
            <!-- Descripción -->
            <td> 
            <strong>Como</strong> propietario de un espacio para eventos en AlquilaFácil, 
            <strong>quiero</strong> recibir notificaciones cuando mi espacio esté disponible para reservar 
            <strong>para</strong> estar al tanto de las solicitudes de reserva y gestionarlas eficientemente.
            </td>
            <!-- ---------- -->
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: Notificación de Nueva Solicitud</h5>
            <strong>Dado</strong> que un propietario tiene su espacio registrado en AlquilaFácil.
            <strong>Cuando</strong> un organizador realiza una nueva solicitud de reserva para ese espacio.
            <strong>Entonces</strong> el propietario recibe una notificación por correo electrónico o en la plataforma.
            <!-- ---------- -->
            <h5>Escenario 02: Recordatorio de Reservas Pendientes</h5>
            <strong>Dado</strong> que un propietario tiene reservas pendientes en AlquilaFácil.
            <strong>Cuando</strong> se acerca la fecha del evento.
            <strong>Entonces</strong> el propietario recibe recordatorios automáticos para gestionar las reservas.
            </td>
            <td>EPIC-005</td>
        </tr>
        <tr style="text-aling:center">
            <td>UH07</td>
            <td>Soporte al Cliente</td>
            <!-- Descripción -->
            <td> 
            <strong>Como</strong> usuario de AlquilaFácil, 
            <strong>quiero</strong> tener acceso a un servicio de soporte eficiente y amigable 
            <strong>para</strong> resolver cualquier consulta o problema que pueda surgir durante el uso de la plataforma.
            </td>
            <!-- ---------- -->
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: Chat en Vivo</h5>
            <strong>Dado</strong> que un usuario necesita ayuda mientras utiliza AlquilaFácil.
            <strong>Cuando</strong> el usuario accede al servicio de soporte.
            <strong>Entonces</strong> puede comunicarse con un representante a través de un chat en vivo para obtener asistencia inmediata.
            <!-- ---------- -->
            <h5>Escenario 02: Centro de Ayuda</h5>
            <strong>Dado</strong> que un usuario tiene una consulta común sobre el uso de la plataforma.
            <strong>Cuando</strong> el usuario visita el Centro de Ayuda en AlquilaFácil.
            <strong>Entonces</strong> encuentra respuestas claras y detalladas a sus preguntas frecuentes.
            </td>
            <td>EPIC-006</td>
        </tr>
        <tr style="text-aling:center">
            <td>UH08</td>
            <td>Calendario de Disponibilidad</td>
            <!-- Descripción -->
            <td> 
            <strong>Como</strong> propietario de un espacio en AlquilaFácil, 
            <strong>quiero</strong> poder gestionar fácilmente mi calendario de disponibilidad 
            <strong>para</strong> evitar conflictos de reservas y mantener mi agenda organizada.
            </td>
            <!-- ---------- -->
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: Actualización de Disponibilidad</h5>
            <strong>Dado</strong> que un propietario desea marcar fechas específicas como no disponibles en AlquilaFácil.
            <strong>Cuando</strong> el propietario accede a su calendario de disponibilidad.
            <strong>Entonces</strong> puede agregar y eliminar fechas según sea necesario.
            <!-- ---------- -->
            <h5>Escenario 02: Sincronización con Calendarios Externos</h5>
            <strong>Dado</strong> que un propietario utiliza un calendario externo para gestionar su agenda.
            <strong>Cuando</strong> realiza cambios en su calendario externo.
            <strong>Entonces</strong> esos cambios se reflejan automáticamente en su calendario de disponibilidad en AlquilaFácil.
            </td>
            <td>EPIC-005</td>
        </tr>
        <tr style="text-aling:center">
            <td>UH09</td>
            <td>Promoción de Espacios Destacados</td>
            <!-- Descripción -->
            <td> 
            <strong>Como</strong> propietario de un espacio en AlquilaFácil, 
            <strong>quiero</strong> poder destacar mi espacio para aumentar su visibilidad y atraer más clientes 
            <strong>para</strong> aumentar las posibilidades de reserva.
            </td>
            <!-- ---------- -->
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: Opción de Destacar Espacio</h5>
            <strong>Dado</strong> que un propietario desea destacar su espacio en AlquilaFácil.
            <strong>Cuando</strong> accede a las opciones de promoción en su panel de control.
            <strong>Entonces</strong> puede seleccionar un plan de promoción y realizar el pago correspondiente.
            <!-- ---------- -->
            <h5>Escenario 02: Espacio Destacado en Búsquedas</h5>
            <strong>Dado</strong> que un usuario busca espacios para eventos en AlquilaFácil.
            <strong>Cuando</strong> realiza una búsqueda.
            <strong>Entonces</strong> los espacios destacados aparecen en los primeros resultados de búsqueda, aumentando su visibilidad.
            </td>   
            <td>EPIC-002</td>
        </tr>
        <tr style="text-aling:center">
            <td>UH10</td>
            <td>Reseñas Recompensadas</td>
            <!-- Descripción -->
            <td> 
            <strong>Como</strong> usuario de AlquilaFácil, 
            <strong>quiero</strong> poder dejar reseñas sobre los espacios que he utilizado 
            <strong>para</strong> compartir mi experiencia con otros usuarios y ganar recompensas por mi participación.
            </td>
            <!-- ---------- -->
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: Dejar Reseña</h5>
            <strong>Dado</strong> que un usuario ha utilizado un espacio reservado a través de AlquilaFácil.
            <strong>Cuando</strong> el evento ha concluido.
            <strong>Entonces</strong> el usuario puede dejar una reseña y calificación sobre su experiencia en ese espacio.
            <!-- ---------- -->
            <h5>Escenario 02: Recompensas por Reseñas</h5>
            <strong>Dado</strong> que un usuario ha dejado una reseña en AlquilaFácil.
            <strong>Cuando</strong> su reseña es validada por el sistema.
            <strong>Entonces</strong> el usuario recibe una recompensa, como descuentos en futuras reservas o puntos de fidelidad.
            </td>
            <td>EPIC-004</td>
        </tr>
        <tr style="text-aling:center">
            <td>UH11</td>
            <td>Calidad de Servicio Garantizada</td>
            <!-- Descripción -->
            <td> 
            <strong>Como</strong> organizador de eventos en AlquilaFácil, 
            <strong>quiero</strong> tener la certeza de que los espacios disponibles cumplen con altos estándares de calidad y seguridad 
            <strong>para</strong> garantizar una experiencia positiva para mis invitados.
            </td>
            <!-- ---------- -->
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: Verificación de Espacios</h5>
            <strong>Dado</strong> que un organizador está buscando un espacio para su evento en AlquilaFácil.
            <strong>Cuando</strong> revisa los detalles y características de los espacios disponibles.
            <strong>Entonces</strong> encuentra información detallada sobre las medidas de seguridad, comodidades y servicios ofrecidos.
            <!-- ---------- -->
            <h5>Escenario 02: Garantía de Satisfacción</h5>
            <strong>Dado</strong> que un organizador ha reservado un espacio a través de AlquilaFácil.
            <strong>Cuando</strong> concluye el evento.
            <strong>Entonces</strong> tiene la opción de dejar una reseña y calificación sobre la calidad del servicio recibido.
            </td>
            <td>EPIC-006</td>
        </tr>
        <tr style="text-aling:center">
            <td>UH12</td>
            <td>Acceso a Espacios Exclusivos</td>
            <!-- Descripción -->
            <td> 
            <strong>Como</strong> organizador de eventos en AlquilaFácil, 
            <strong>quiero</strong> poder acceder a espacios exclusivos y populares 
            <strong>para</strong> destacar mi evento y ofrecer una experiencia única a mis invitados.
            </td>
            <!-- ---------- -->
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: Búsqueda de Espacios Exclusivos</h5>
            <strong>Dado</strong> que un organizador está planeando un evento especial en AlquilaFácil.
            <strong>Cuando</strong> utiliza la función de búsqueda avanzada.
            <strong>Entonces</strong> encuentra opciones de espacios exclusivos que se ajustan a sus necesidades y preferencias.
            <!-- ---------- -->
            <h5>Escenario 02: Reserva de Espacios Populares</h5>
            <strong>Dado</strong> que un organizador desea reservar un espacio popular para su evento en AlquilaFácil.
            <strong>Cuando</strong> realiza la reserva.
            <strong>Entonces</strong> recibe confirmación inmediata y acceso prioritario al espacio seleccionado.
            </td>
            <td>EPIC-002</td>
        </tr>
        <tr style="text-aling:center">
            <td>UH13</td>
            <td>Flexibilidad en Reservas</td>
            <!-- Descripción -->
            <td> 
            <strong>Como</strong> organizador de eventos en AlquilaFácil, 
            <strong>quiero</strong> tener opciones flexibles de reserva 
            <strong>para</strong> adaptarme a cambios de última hora en la planificación de mi evento.
            </td>
            <!-- ---------- -->
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: Modificación de Reservas</h5>
            <strong>Dado</strong> que un organizador ha reservado un espacio a través de AlquilaFácil.
            <strong>Cuando</strong> necesita realizar cambios en la fecha, hora o detalles de su evento.
            <strong>Entonces</strong> puede modificar la reserva según sea necesario, sujeto a disponibilidad y políticas de cancelación.
            <!-- ---------- -->
            <h5>Escenario 02: Cancelación de Reservas</h5>
            <strong>Dado</strong> que un organizador enfrenta circunstancias imprevistas que requieren la cancelación de su evento.
            <strong>Cuando</strong> solicita cancelar la reserva.
            <strong>Entonces</strong> recibe orientación sobre el proceso de cancelación y cualquier reembolso aplicable.
            </td>
            <td>EPIC-002</td>
        </tr>
        <tr style="text-aling:center">
            <td>UH14</td>
            <td>Experiencia de Reserva Transparente</td>
            <!-- Descripción -->
            <td> 
            <strong>Como</strong> organizador de eventos en AlquilaFácil, 
            <strong>quiero</strong> tener acceso a información transparente sobre tarifas, políticas y términos de reserva 
            <strong>para</strong> tomar decisiones informadas y evitar sorpresas desagradables.
            </td>
            <!-- ---------- -->
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: Visualización de Tarifas y Condiciones</h5>
            <strong>Dado</strong> que un organizador está explorando opciones de reserva en AlquilaFácil.
            <strong>Cuando</strong> revisa los detalles de un espacio y los términos de reserva.
            <strong>Entonces</strong> encuentra información clara y detallada sobre tarifas, políticas de cancelación y cualquier cargo adicional.
            <!-- ---------- -->
            <h5>Escenario 02: Transparencia en Costos Adicionales</h5>
            <strong>Dado</strong> que un organizador está a punto de confirmar una reserva en AlquilaFácil.
            <strong>Cuando</strong> revisa el resumen de costos antes de finalizar la reserva.
            <strong>Entonces</strong> no hay sorpresas, y todos los costos adicionales, como tarifas de servicio o impuestos, están claramente indicados.
            </td>
            <td>EPIC-002</td>
        </tr>
        <tr style="text-aling:center">
            <td>UH15</td>
            <td>Comunicación Directa con Propietarios</td>
            <!-- Descripción -->
            <td> 
            <strong>Como</strong> organizador de eventos en AlquilaFácil, 
            <strong>quiero</strong> poder comunicarme directamente con los propietarios de los espacios 
            <strong>para</strong> aclarar dudas, coordinar detalles y resolver cualquier problema de manera rápida y efectiva.
            </td>
            <!-- ---------- -->
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: Mensajería Instantánea</h5>
            <strong>Dado</strong> que un organizador ha reservado un espacio en AlquilaFácil.
            <strong>Cuando</strong> necesita comunicarse con el propietario del espacio.
            <strong>Entonces</strong> puede enviar mensajes directos a través de la plataforma para obtener respuestas rápidas y resolver cualquier problema.
            <!-- ---------- -->
            <h5>Escenario 02: Gestión de Consultas</h5>
            <strong>Dado</strong> que un organizador tiene preguntas o solicitudes específicas sobre un espacio en AlquilaFácil.
            <strong>Cuando</strong> envía un mensaje al propietario.
            <strong>Entonces</strong> recibe una respuesta oportuna y personalizada para abordar sus inquietudes.
            </td>
            <td>EPIC-003</td>
        </tr>
        <tr style="text-aling:center">
            <td>UH16</td>
            <td>Registro de Espacio Sencillo</td>
            <!-- Descripción -->
            <td> 
            <strong>Como</strong> propietario de un espacio para eventos en AlquilaFácil, 
            <strong>quiero</strong> poder registrar mi espacio de manera rápida y sencilla 
            <strong>para</strong> comenzar a recibir solicitudes de reserva lo antes posible.
            </td>
            <!-- ---------- -->
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: Registro de Datos Básicos</h5>
            <strong>Dado</strong> que un propietario desea registrar su espacio en AlquilaFácil.
            <strong>Cuando</strong> completa un formulario básico con información sobre el espacio, como ubicación, tamaño y tipos de eventos permitidos.
            <strong>Entonces</strong> puede enviar el registro con éxito y recibir confirmación de su inclusión en la plataforma.
            <!-- ---------- -->
            <h5>Escenario 02: Subida de Fotos</h5>
            <strong>Dado</strong> que un propietario está completando el registro de su espacio en AlquilaFácil.
            <strong>Cuando</strong> carga imágenes de alta calidad que muestren el espacio y sus características.
            <strong>Entonces</strong> las fotos se muestran correctamente en el perfil del espacio, ayudando a atraer a posibles organizadores de eventos.
            </td>
            <td>EPIC-001</td>
        </tr>
        <tr style="text-aling:center">
            <td>UH17</td>
            <td>Gestión Flexible de Disponibilidad</td>
            <!-- Descripción -->
            <td> 
            <strong>Como</strong> propietario de un espacio para eventos en AlquilaFácil, 
            <strong>quiero</strong> tener la capacidad de gestionar la disponibilidad de mi espacio de manera flexible 
            <strong>para</strong> adaptarme a cambios de horarios y necesidades de reserva.
            </td>
            <!-- ---------- -->
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: Actualización de Calendario</h5>
            <strong>Dado</strong> que un propietario necesita ajustar la disponibilidad de su espacio en AlquilaFácil.
            <strong>Cuando</strong> realiza cambios en el calendario, bloquea fechas o actualiza horarios disponibles.
            <strong>Entonces</strong> los cambios se reflejan instantáneamente en la plataforma, evitando conflictos de reserva.
            <!-- ---------- -->
            <h5>Escenario 02: Administración de Reservas Pendientes</h5>
            <strong>Dado</strong> que un propietario ha recibido una solicitud de reserva en AlquilaFácil.
            <strong>Cuando</strong> revisa la solicitud y necesita ajustar la disponibilidad del espacio.
            <strong>Entonces</strong> puede hacer cambios rápidos y comunicarse con el organizador del evento según sea necesario.
            </td>
            <td>EPIC-001</td>
        </tr>
        <tr style="text-aling:center">
            <td>UH18</td>
            <td>Comunicación Directa con Organizadores</td>
            <!-- Descripción -->
            <td> 
            <strong>Como</strong> propietario de un espacio para eventos en AlquilaFácil, 
            <strong>quiero</strong> poder comunicarme directamente con los organizadores de eventos interesados 
            <strong>para</strong> aclarar dudas, discutir detalles y confirmar reservas de manera efectiva.
            </td>
            <!-- ---------- -->
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: Interacción Inmediata</h5>
            <strong>Dado</strong> que un propietario ha recibido una solicitud de reserva en AlquilaFácil.
            <strong>Cuando</strong> revisa la solicitud y necesita aclarar detalles con el organizador.
            <strong>Entonces</strong> puede enviar mensajes directos a través de la plataforma para una comunicación rápida y eficiente.
            <!-- ---------- -->
            <h5>Escenario 02: Confirmación de Reservas</h5>
            <strong>Dado</strong> que un propietario y un organizador han llegado a un acuerdo sobre una reserva en AlquilaFácil.
            <strong>Cuando</strong> necesitan confirmar los detalles finales y asegurar la reserva.
            <strong>Entonces</strong> pueden comunicarse directamente para coordinar y confirmar la reserva de manera efectiva.
            </td>
            <td>EPIC-003</td>
        </tr>
        <tr style="text-aling:center">
            <td>UH19</td>
            <td>Perfil Personalizado de Espacio</td>
            <!-- Descripción -->
            <td> 
            <strong>Como</strong> propietario de un espacio para eventos en AlquilaFácil, 
            <strong>quiero</strong> tener un perfil personalizado para mi espacio 
            <strong>para</strong> destacar sus características únicas y atraer a posibles organizadores de eventos.
            </td>
            <!-- ---------- -->
            <!-- Criterios de Aceptación -->
            <td> 
            <h5>Escenario 01: Personalización de Perfil</h5>
            <strong>Dado</strong> que un propietario está completando el registro de su espacio en AlquilaFácil.
            <strong>Cuando</strong> agrega detalles personalizados, como descripciones detalladas, servicios adicionales ofrecidos y reglas de uso del espacio.
            <strong>Entonces</strong> el perfil se destaca entre otros y brinda a los organizadores una visión clara de lo que ofrece el espacio.
            <!-- ---------- -->
            <h5>Escenario 02: Actualización de Información</h5>
            <strong>Dado</strong> que un propietario necesita realizar cambios en la información de su espacio en AlquilaFácil.
            <strong>Cuando</strong> actualiza la descripción, agrega nuevas fotos o modifica los servicios disponibles.
            <strong>Entonces</strong> los cambios se reflejan instantáneamente en el perfil del espacio, manteniendo la información actualizada y precisa.
            </td>
            <td>EPIC-001</td>
        </tr>
        <tr style="text-aling:center">
            <td>UH20</td>
        <td>Recibir Notificaciones de Reservas</td>
        <!-- Descripción -->
        <td> 
        <strong>Como</strong> propietario de un espacio para eventos en AlquilaFácil, 
        <strong>quiero</strong> recibir notificaciones instantáneas sobre nuevas solicitudes de reserva y actualizaciones en el estado de mis reservas 
        <strong>para</strong> estar al tanto de las actividades relacionadas con mi espacio en todo momento.
        </td>
        <!-- ---------- -->
        <!-- Criterios de Aceptación -->
        <td> 
        <h5>Escenario 01: Notificación de Nueva Reserva</h5>
        <strong>Dado</strong> que un propietario tiene su espacio registrado en AlquilaFácil.
        <strong>Cuando</strong> un organizador envía una nueva solicitud de reserva para el espacio.
        <strong>Entonces</strong> el propietario recibe una notificación instantánea por correo electrónico o en la aplicación.
        <!-- ---------- -->
        <h5>Escenario 02: Actualización de Estado de Reserva</h5>
        <strong>Dado</strong> que un propietario tiene reservas confirmadas en AlquilaFácil.
        <strong>Cuando</strong> hay cambios en el estado de una reserva, como confirmación o cancelación.
        <strong>Entonces</strong> el propietario recibe notificaciones automáticas para mantenerlo informado sobre el estado actual de sus reservas.
        </td>
        <td>EPIC-001</td>
        </tr>        
    </body>

</table>

## 3.3. Impact Mapping

**Propietario de Espacio para Eventos**
![ImpactMapPropietario](/assets/img/Impact_map_propietario.png)

**Usuario para Búsqueda de Espacio para Eventos**
![ImpactMapUsuario](/assets/img/Impact_map_usuario.png)


## 3.4. Product Backlog

Utilizamos la escala de Fibonacci para la estimación de los Story Points 

<table>
        <thead>
            <tr>
                <th>Orden</th>
                <th>User Story Id</th>
                <th>Título</th>
                <th>Descripción</th>
                <th>Story Points (1/2/3/5/8)</th>
            </tr>
        </thead>
        <tbody>
        <tr>
            <td>1</td>
            <td>UH18</td>
            <td>Comunicación Directa con Organizadores</td>
            <td>Como propietario de un espacio para eventos en AlquilaFácil, quiero poder comunicarme directamente con los organizadores de eventos interesados para aclarar dudas, discutir detalles y confirmar reservas de manera efectiva.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>2</td>
            <td>UH12</td>
            <td>Acceso a Espacios Exclusivos</td>
            <td>Como organizador de eventos en AlquilaFácil, quiero poder acceder a espacios exclusivos y populares para destacar mi evento y ofrecer una experiencia única a mis invitados.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>3</td>
            <td>UH15</td>
            <td>Comunicación Directa con Propietarios</td>
            <td>Como organizador de eventos en AlquilaFácil, quiero poder comunicarme directamente con los propietarios de los espacios para aclarar dudas, coordinar detalles y resolver cualquier problema de manera rápida y efectiva.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>4</td>
            <td>UH10</td>
            <td>Reseñas Recompensadas</td>
            <td>Como usuario de AlquilaFácil, quiero poder dejar reseñas sobre los espacios que he utilizado para compartir mi experiencia con otros usuarios y ganar recompensas por mi participación.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>5</td>
            <td>UH05</td>
            <td>Calificaciones y Comentarios sobre Espacios</td>
            <td>Como organizador de eventos, quiero poder ver las calificaciones y comentarios de otros usuarios sobre los espacios en AlquilaFácil para tomar una decisión informada al seleccionar un espacio para mi evento.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>6</td>
            <td>UH17</td>
            <td>Gestión Flexible de Disponibilidad</td>
            <td>Como propietario de un espacio para eventos en AlquilaFácil, quiero tener la capacidad de gestionar la disponibilidad de mi espacio de manera flexible para adaptarme a cambios de horarios y necesidades de reserva.</td>
            <td>8</td>
        </tr>
        <tr>
            <td>7</td>
            <td>UH03</td>
            <td>Búsqueda y Filtrado de Espacios</td>
            <td>Como organizador de eventos, quiero poder buscar y filtrar fácilmente espacios disponibles en AlquilaFácil para encontrar el lugar perfecto para mi evento, según mis criterios específicos.</td>
            <td>2</td>
        </tr>
        <tr>
            <td>8</td>
            <td>UH01</td>
            <td>Hipervínculos en el Encabezado</td>
            <td>Como visitante de la plataforma AlquilaFácil, quiero que las opciones del menú de navegación me dirijan a las diferentes secciones de la plataforma para poder acceder rápidamente a la información que necesito.</td>
            <td>1</td>
        </tr>
        </tbody>
</table>