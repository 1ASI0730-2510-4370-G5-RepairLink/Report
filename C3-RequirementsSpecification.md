## Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

> Describiremos cómo funcionará la plataforma en su estado ideal, desde el punto de vista de los principales actores  

> Segmento Cliente:
> 
> <img src="images/To-Be-Cliente.jpg" alt="Impact Map Client">

> Segmento Técnico:
> 
> <img src="images/To-Be-Tecnico.jpg" alt="Impact Map Tech">

## 3.2. User Stories

<table>
  <thead>
    <tr>
      <th>Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de Aceptación</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US-001</td>
      <td>Landing Page - Home</td>
      <td>Como usuario cliente, quiero encontrar una página atractiva donde pueda ver una descripción sobre qué ofrece la plataforma desde la sección inicial de la página.</td>
      <td>
        Escenario: Visualización de la descripción<br>
        Dado que el visitante accede a la landing page<br>
        Cuando visualiza la sección “Home”<br>
        Entonces ve una descripción clara con el beneficio principal de la plataforma y un botón de acción ingresar.
      </td>
    </tr>
    <tr>
      <td>US-002</td>
      <td>Sección - Reparaciones</td>
      <td>Como usuario cliente, quiero ver los tipos de dispositivos o problemas que se pueden reparar, para saber si me pueden ayudar.</td>
      <td>
        Escenario: Explorar tipos de reparaciones<br>
        Dado que el visitante baja hasta la sección “Reparaciones”<br>
        Cuando lee la información y ve las imágenes<br>
        Entonces comprende que dispositivos o fallas están cubiertas por la website.
      </td>
    </tr>
    <tr>
      <td>US-003</td>
      <td>Sección - Reseñas</td>
      <td>Como usuario cliente, quiero ver reseñas de otros usuarios para generar confianza en el servicio.</td>
      <td>
        Escenario: Testimonios y reseñas<br>
        Dado que el visitante accede a la sección de “Reseñas”<br>
        Cuando visualiza los testimonios<br>
        Entonces puede leer los comentarios de otros usuarios con sus calificaciones.
      </td>
    </tr>
    <tr>
      <td>US-004</td>
      <td>Sección - Sé un Técnico</td>
      <td>Como usuario técnico interesado, quiero ver una sección que me explique cómo puedo unirme a la website.</td>
      <td>
        Escenario: Información para técnicos<br>
        Dado que el visitante accede a la sección de “Sé un técnico”<br>
        Cuando lee el contenido<br>
        Entonces entiende los beneficios, pasos a registrarse y encuentra un botón para comenzar.
      </td>
    </tr>
    <tr>
      <td>US-005</td>
      <td>Sección - Contacto</td>
      <td>Como usuario cliente, quiero tener un formulario de contacto simple para enviar dudas o comentarios.</td>
      <td>
        Escenario: Formulario de Contacto<br>
        Dado que el visitante llega a la sección “Contacto”<br>
        Cuando completa nombre, email y mensaje<br>
        Entonces puede enviar el formulario y ver un mensaje de confirmación.
      </td>
    </tr>
    <tr>
      <td>US-006</td>
      <td>Registro rápido de usuario</td>
      <td>Como usuario cliente, quiero crear una cuenta fácilmente para acceder a los servicios de reparación.</td>
      <td>
        Escenario 1: Registro exitoso con correo electrónico<br>
        Dado que el usuario accede a la pantalla de registro<br>
        Cuando completa los campos obligatorios y presiona "Crear cuenta".<br><br>
        Escenario 2: Registro con cuenta de Google o redes sociales<br>
        Dado que el usuario elige registrarse con Google<br>
        Cuando autoriza el acceso<br>
        Entonces el sistema crea la cuenta y lo redirige al panel principal.<br><br>
        Escenario 3: Registro con campos incompletos<br>
        Dado que el usuario intenta registrarse sin completar los campos requeridos<br>
        Cuando presiona "Crear cuenta"<br>
        Entonces el sistema muestra un mensaje de error solicitando completar los campos.
        </td>
    </tr>
    <tr>
      <td>US-007</td>
      <td>Registro de técnico</td>
      <td>Como usuario técnico, quiero registrarme y crear un perfil profesional para recibir solicitudes de reparación</td>
      <td>
        Escenario 1: Registro exitoso<br>
        Dado que el técnico accede al formulario de registro<br>
        Cuando completa todos los campos y acepta los términos<br>
        Entonces el sistema crea el perfil y lo pone en revisión<br><br>
        Escenario 2: Activación del perfil<br>
        Dado que el técnico completó el perfil<br>
        Cuando el equipo lo verifica<br>
        Entonces el perfil queda activo y visible para los usuarios
      </td>
    </tr>
    <tbody>
  <tr>
    <td>US-008</td>
    <td>Subir información del dispositivo</td>
    <td>Como usuario cliente, quiero subir fotos y una descripción de mi dispositivo dañado para recibir un diagnóstico</td>
    <td>
      Escenario 1: Envío de fotos y descripción completo<br>
      Dado que el usuario ya inició sesión<br>
      Cuando selecciona fotos y escribe una descripción<br>
      Entonces el sistema confirma el envío exitoso<br><br>
      Escenario 2: Omisión de descripción o fotos<br>
      Dado que el usuario intenta enviar solo fotos o solo descripción<br>
      Cuando presiona "Enviar"<br>
      Entonces el sistema le solicita que complete ambos campos
    </td>
  </tr>
  <tr>
    <td>US-009</td>
    <td>Recibir presupuestos</td>
    <td>Como usuario cliente, quiero recibir varios presupuestos de técnicos para comparar diferentes opciones y elegir la mejor</td>
    <td>
      Escenario 1: Recepción de múltiples cotizaciones<br>
      Dado que el usuario ha enviado información del dispositivo<br>
      Cuando los técnicos responden con propuestas<br>
      Entonces el sistema le muestra al menos tres cotizaciones<br><br>
      Escenario 2: Comparación de cotizaciones<br>
      Dado que el usuario recibe varias cotizaciones<br>
      Cuando accede al detalle de cada una<br>
      Entonces puede ver precio, tiempo estimado y reputación del técnico
    </td>
  </tr>
  <tr>
    <td>US-010</td>
    <td>Ver reputación de técnicos</td>
    <td>Como usuario cliente, quiero ver la reputación de los técnicos para tomar una decisión concreta</td>
    <td>
      Escenario 1: Visualización de calificaciones<br>
      Dado que el usuario explora técnicos disponibles<br>
      Cuando abre el perfil de uno<br>
      Entonces ve su puntuación promedio y comentarios de clientes anteriores
    </td>
  </tr>
  <tr>
    <td>US-011</td>
    <td>Chat con técnicos</td>
    <td>Como usuario cliente, quiero poder chatear con los técnicos antes de confirmar una reparación para aclarar dudas</td>
    <td>
      Escenario 1: Inicio de chat<br>
      Dado que el usuario recibe cotizaciones<br>
      Cuando presiona “Chatear” en alguna de ellas<br>
      Entonces accede a una ventana de conversación con ese técnico<br><br>
      Escenario 2: Recibir respuesta del técnico<br>
      Dado que el usuario envió una consulta<br>
      Cuando el técnico responde<br>
      Entonces el usuario recibe una notificación y puede ver el mensaje
    </td>
  </tr>
  <tr>
    <td>US-012</td>
    <td>Agendar Cita</td>
    <td>Como usuario cliente, quiero agendar una cita directamente desde la plataforma para que sea más cómodo</td>
    <td>
      Escenario 1: Selección de cita<br>
      Dado que el usuario ha aceptado una cotización<br>
      Cuando elige día y hora disponibles<br>
      Entonces el sistema confirma la cita y la agrega a su calendario en la app
    </td>
  </tr>
  <tr>
    <td>US-013</td>
    <td>Garantía del servicio</td>
    <td>Como usuario cliente, quiero recibir una garantía del servicio realizado para sentirme más seguro</td>
    <td>
      Escenario 1: Visualizar condiciones de garantía<br>
      Dado que el usuario acepta una reparación<br>
      Cuando revisa el detalle del servicio<br>
      Entonces puede ver claramente la duración y condiciones de garantía
    </td>
  </tr>
  <tr>
    <td>US-014</td>
    <td>Recompensas por uso</td>
    <td>Como usuario cliente, quiero ganar recompensas por usar la plataforma para motivarme a reparar más</td>
    <td>
      Escenario 1: Acumulación de puntos<br>
      Dado que el usuario ha completado una reparación<br>
      Cuando esta es finalizada y calificada<br>
      Entonces recibe puntos en su perfil
    </td>
  </tr>
  <tr>
    <td>US-015</td>
    <td>Notificaciones de casos</td>
    <td>Como usuario técnico, quiero recibir notificaciones de nuevos casos en mi especialidad para no perder oportunidades</td>
    <td>
      Escenario 1: Notificación de caso nuevo<br>
      Dado que un usuario publica un nuevo dispositivo dañado<br>
      Cuando este coincide con la especialidad del técnico<br>
      Entonces el técnico recibe una notificación inmediata
    </td>
  </tr>
  <tr>
    <td>US-016</td>
    <td>Enviar presupuestos</td>
    <td>Como usuario técnico, quiero enviar presupuestos personalizados para competir con otros técnicos</td>
    <td>
      Escenario 1: Envío de presupuesto<br>
      Dado que el técnico recibe una solicitud<br>
      Cuando presiona "Enviar presupuesto" y completa los campos<br>
      Entonces el usuario ve su propuesta junto a las demás
    </td>
  </tr>
  <tr>
    <td>US-017</td>
    <td>Gestión de citas y clientes</td>
    <td>Como usuario técnico, quiero gestionar mis citas y clientes desde la plataforma para organizar mi trabajo</td>
    <td>
      Escenario 1: Ver próximas citas<br>
      Dado que el técnico tiene citas confirmadas<br>
      Cuando accede a su calendario<br>
      Entonces puede ver el día, hora y cliente asociado
    </td>
  </tr>
  <tr>
    <td>US-018</td>
    <td>Facturación</td>
    <td>Como usuario técnico, quiero acceder a herramientas de facturación para llevar control de mis servicios</td>
    <td>
      Escenario 1: Generar factura automáticamente<br>
      Dado que el servicio ha sido finalizado y pagado<br>
      Cuando el técnico accede a su historial<br>
      Entonces podrá ver las boletas del servicio
    </td>
  </tr>
  <tr>
    <td>US-019</td>
    <td>Calificaciones y comentarios</td>
    <td>Como usuario técnico, quiero recibir calificaciones y comentarios para mejorar mi perfil y reputación</td>
    <td>
      Escenario 1: Visualización de calificaciones<br>
      Dado que el técnico ha completado varios servicios<br>
      Cuando accede a su perfil<br>
      Entonces puede ver un promedio de calificación y leer comentarios de los clientes
    </td>
  </tr>
  <tr>
    <td>US-020</td>
    <td>Comunidad de técnicos</td>
    <td>Como usuario técnico, quiero participar en foros con otros reparadores para compartir conocimientos y aprender</td>
    <td>
      Escenario 1: Participar en un foro<br>
      Dado que el técnico accede a la sección de comunidad<br>
      Cuando publica una pregunta o responde a otra<br>
      Entonces el mensaje aparece disponible para otros técnicos registrados
    </td>
  </tr>
 </tbody>
</table>


## 3.3. Impact Mapping

> Segmento Cliente:
> 
> <img src="images/Impact-map-Cliente.png" alt="Impact Map Client">

> Segmento Técnico:
> 
> <img src="images/Impact-Map-Tec.png" alt="Impact Map Tech">

## 3.4. Product Backlog

| ID       | User Story                                                                  | Prioridad | Valor para el Usuario/Negocio      | Sprint |
|----------|-----------------------------------------------------------------------------|-----------|------------------------------------|--------|
| US-006   | Registro rápido de usuario                                                  | Alta      | Acceso básico a plataforma         | 1      |
| US-008   | Subir información del dispositivo                                           | Alta      | Inicia el flujo de diagnóstico     | 1      |
| US-009   | Recibir presupuestos                                                        | Alta      | Permite comparar y elegir técnicos | 2      |
| US-010   | Ver reputación de técnicos                                                  | Media     | Confianza en la elección           | 2      |
| US-011   | Chat con técnicos                                                           | Alta      | Comunicación directa               | 3      |
| US-012   | Agendar cita                                                                | Alta      | Cierre de acuerdo                  | 3      |
| US-013   | Garantía del servicio                                                       | Alta      | Confianza post-reparación          | 4      |
| US-014   | Recompensas por uso                                                         | Media     | Fomenta fidelidad                  | 4      |
| US-007   | Registro de técnico                                                         | Alta      | Permite oferta de servicios        | 1      |
| US-015   | Notificaciones de casos                                                     | Alta      | Mejora tiempos de respuesta        | 2      |
| US-016   | Enviar presupuestos                                                         | Alta      | Competencia y conversión           | 2      |
| US-017   | Gestión de citas y clientes                                                 | Media     | Organización del técnico           | 3      |
| US-018   | Facturación                                                                 | Media     | Control financiero                 | 4      |
| US-019   | Calificaciones y comentarios                                                | Alta      | Reputación y confianza             | 4      |
| US-020   | Comunidad de técnicos                                                       | Baja      | Valor agregado profesional         | 5      |
| US-001   | Landing Page - Home                                                         | Alta      | Primera impresión del usuario      | 1      |
| US-002   | Sección - Reparaciones                                                      | Alta      | Información clara de alcance       | 1      |
| US-003   | Sección - Reseñas                                                           | Media     | Genera confianza inicial           | 1      |
| US-004   | Sección - Sé un Técnico                                                     | Alta      | Convierte visitantes en técnicos   | 1      |
| US-005   | Sección - Contacto                                                          | Media     | Canal de comunicación inicial      | 1      |

