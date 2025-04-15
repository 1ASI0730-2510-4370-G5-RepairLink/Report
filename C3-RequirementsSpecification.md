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

### US-001: Landing Page - Home

Como usuario cliente, quiero encontrar una página atractiva donde pueda ver una  descripción sobre qué ofrece la plataforma desde la sección inicial de la página

```gherkin
Escenario 1: Visualización de la descripción
Dado que el visitante accede a la landing page
Cuando visualiza la sección “Home”
Entonces ve una descripción clara con el beneficio principal de la plataforma y un botón de acción ingresar.
```
### US-002: Sección - Reparaciones

Como usuario cliente, quiero ver los tipos de dispositivos o problemas que se pueden reparar, para saber si me pueden ayudar

```gherkin
Escenario 1: Explorar tipos de reparaciones
Dado que el visitante baja hasta la sección “Reparaciones”
Cuando lee la informacion y ve las imágenes
Entonces comprende que dispositivos o fallas están cubiertas por la website
```


### US-003: Sección - Reseñas

Como usuario cliente, quiero ver reseñas de otros usuarios para generar confianza en el servicio

```gherkin
Escenario 1: Testimonios y reseñas
Dado que el visitante accede a la sección de “Reseñas”
Cuando visualiza los testimonios
Entonces puede leer los comentarios de otros usuarios con sus calificaciones
```


### US-004: Sección - Se un Técnico

Como usuario técnico interesado, quiero ver una sección que me explique como puedo unirme a la website

```gherkin
Escenario 1: Información para técnicos
Dado que el visitante accede a la sección de “Se un técnico”
Cuando lee el contenido
Entonces entiende los beneficios, pasos a registrarse y encuentra un botón para comenzar
```


### US-005: Sección - Contacto

Como usuario cliente, quiero tener un formulario de contacto simple para enviar dudas o comentarios

```gherkin
Escenario 1: Formulario de Contacto
Dado que el visitante llega a la sección “Contacto”
Cuando completa nombre, email y mensaje
Entonces puede enviar el formulario y ver un mensaje de confirmación
```


### US-006: Registro rápido de usuario

Como usuario cliente, quiero crear una cuenta fácilmente para acceder a los servicios de reparación

```gherkin
Escenario 1: Registro exitoso con correo electrónico
Dado que el usuario accede a la pantalla de registro
Cuando completa los campos obligatorios y presiona "Crear cuenta"
Entonces el sistema crea la cuenta y envía un correo de confirmación

Escenario 2: Registro con cuenta de Google o redes sociales
Dado que el usuario elige registrarse con Google
Cuando autoriza el acceso
Entonces el sistema crea la cuenta y lo redirige al panel principal

Escenario 3: Registro con campos incompletos
Dado que el usuario intenta registrarse sin completar los campos requeridos
Cuando presiona "Crear cuenta"
Entonces el sistema muestra un mensaje de error solicitando completar los campos
```


### US-007: Registro de técnico

Como usuario técnico, quiero registrarme y crear un perfil profesional para recibir solicitudes de reparación

```gherkin
Escenario 1: Registro exitoso
Dado que el técnico accede al formulario de registro
Cuando completa todos los campos y acepta los términos
Entonces el sistema crea el perfil y lo pone en revisión
Escenario 2: Activación del perfil
Dado que el técnico completó el perfil
Cuando el equipo lo verifica
Entonces el perfil queda activo y visible para los usuarios
```


### US-008: Subir información del dispositivo

Como usuario cliente, quiero subir fotos y una descripción de mi dispositivo dañado para recibir un diagnóstico

```gherkin
Escenario 1: Envío de fotos y descripción completo
Dado que el usuario ya inició sesión
Cuando selecciona fotos y escribe una descripción
Entonces el sistema confirma el envío exitoso

Escenario 2: Omisión de descripción o fotos
Dado que el usuario intenta enviar solo fotos o solo descripción
Cuando presiona "Enviar"
Entonces el sistema le solicita que complete ambos campos
```


### US-009: Recibir presupuestos

Como usuario cliente, quiero recibir varios presupuestos de técnicos para comparar diferentes opciones y elegir la mejor

```gherkin
Escenario 1: Recepción de múltiples cotizaciones
Dado que el usuario ha enviado información del dispositivo
Cuando los técnicos responden con propuestas
Entonces el sistema le muestra al menos tres cotizaciones

Escenario 2: Comparación de cotizaciones
Dado que el usuario recibe varias cotizaciones
Cuando accede al detalle de cada una
Entonces puede ver precio, tiempo estimado y reputación del técnico
```


### US-0010: Ver reputacion de técnicos

Como usuario cliente, quiero ver la reputación de los técnicos para tomar una decisión concreta

```gherkin
Escenario 1: Visualización de calificaciones
Dado que el usuario explora técnicos disponibles
Cuando abre el perfil de uno
Entonces ve su puntuación promedio y comentarios de clientes anteriores
```


### US-011: Chat con técnicos

Como usuario cliente, quiero poder chatear con los técnicos antes de confirmar una reparación para aclarar dudas

```gherkin
Escenario 1: Inicio de chat
Dado que el usuario recibe cotizaciones
Cuando presiona “Chatear” en alguna de ellas
Entonces accede a una ventana de conversación con ese técnico

Escenario 2: Recibir respuesta del técnico
Dado que el usuario envió una consulta
Cuando el técnico responde
Entonces el usuario recibe una notificación y puede ver el mensaje
```


### US-012: Agendar Cita

Como usuario cliente, quiero agendar una cita directamente desde la plataforma para que sea más cómodo

```gherkin
Escenario 1: Selección de cita
Dado que el usuario ha aceptado una cotización
Cuando elige día y hora disponibles
Entonces el sistema confirma la cita y la agrega a su calendario en la app
```


### US-013: Garantía del servicio

Como usuario cliente, quiero recibir una garantía del servicio realizado para sentirme más seguro

```gherkin
Escenario 1: Visualizar condiciones de garantía
Dado que el usuario acepta una reparación
Cuando revisa el detalle del servicio
Entonces puede ver claramente la duración y condiciones de garantía
```


### US-014: Recompensas por uso

Como usuario cliente, quiero ganar recompensas por usar la plataforma para motivarme a reparar más

```gherkin
Escenario 1: Acumulación de puntos
Dado que el usuario ha completado una reparación
Cuando esta es finalizada y calificada
Entonces recibe puntos en su perfil
```


### US-015: Notificaciones de casos

Como usuario técnico, quiero recibir notificaciones de nuevos casos en mi especialidad para no perder oportunidades

```gherkin
Escenario 1: Notificación de caso nuevo
Dado que un usuario publica un nuevo dispositivo dañado
Cuando este coincide con la especialidad del técnico
Entonces el técnico recibe una notificación inmediata
```


### US-016: Enviar presupuestos

Como usuario técnico, quiero enviar presupuestos personalizados para competir con otros técnicos

```gherkin
Escenario 1: Envío de presupuesto
Dado que el técnico recibe una solicitud
Cuando presiona "Enviar presupuesto" y completa los campos
Entonces el usuario ve su propuesta junto a las demás
```


### US-017: Gestión de citas y clientes

Como usuario técnico, quiero gestionar mis citas y clientes desde la plataforma para organizar mi trabajo

```gherkin
Escenario 1: Ver próximas citas
Dado que el técnico tiene citas confirmadas
Cuando accede a su calendario
Entonces puede ver el día, hora y cliente asociado
```


### US-018: Facturación

Como usuario técnico, quiero acceder a herramientas de facturación para llevar control de mis servicios

```gherkin
Escenario 1: Generar factura automáticamente
Dado que el servicio ha sido finalizado y pagado
Cuando el técnico accede a su historial
Entonces podrá ver las boletas del servicio
```


### US-019: Calificaciones y comentarios

Como usuario técnico, quiero recibir calificaciones y comentarios para mejorar mi perfil y reputación

```gherkin
Escenario 1: Visualización de calificaciones
Dado que el técnico ha completado varios servicios
Cuando accede a su perfil
Entonces puede ver un promedio de calificación y leer comentarios de los clientes
```


### US-020: Comunidad de técnicos

Como usuario  técnico, quiero participar en foros con otros reparadores para compartir conocimientos y aprender

```gherkin
Escenario 1: Participar en un foro
Dado que el técnico accede a la sección de comunidad
Cuando publica una pregunta o responde a otra
Entonces el mensaje aparece disponible para otros técnicos registrados
```

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

