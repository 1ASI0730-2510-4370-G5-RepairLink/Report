# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores.
### 2.1.1. Análisis competitivo.

| **Competitive Analysis Landscape**                                                                 |
|----------------------------------------------------------------------------------------------------|
| **¿Por qué llevar a cabo este análisis?**                                                          |
| **¿Qué aspecto le falta a las alternativas en el mercado que podamos cubrir en nuestra aplicación?** |

|           | **Nuestra Startup**                                                                 | **MaintainX**                          | **OpenRMA**                          | **Repero**                          |
|-----------|-------------------------------------------------------------------------------------|----------------------------------------|--------------------------------------|-------------------------------------|
| **Perfil**    | Plataforma impulsada por IA para empresas de reparación informática/electrónica. Diseñada para talleres, autónomos y empresas, especializada en nichos como IoT y electrónica antigua. | Aplicación para seguimiento de mantenimiento reactivo y preventivo. | Tracking para negocios en reparación de computadoras, con notificaciones por email/SMS. | Aplicación usada por pequeñas tiendas de reparación con soluciones IT y plan gratuito. |
| **Ventaja Competitiva** | Herramientas a medida para flujos de trabajo, plazos predictivos, seguimiento de componentes, gestión de garantías. | Automatización simplificada del flujo de trabajo. | Gestión de talleres de reparación con actualizaciones en tiempo real. | Seguimiento simplificado de reparaciones e inventario. |
| **Mercado objetivo** | Talleres de reparación informática, autónomos de electrónica, empresas tecnológicas especializadas. | Pequeños y medianos talleres de reparación informática y autónomos. | Pequeños talleres de reparación de informática/electrónica. | Pequeños y medianos talleres de reparación (bicicletas, electrónica, automoción). |
| **Estrategias de marketing** | Modelo freemium, sistema de referidos, colaboraciones con proveedores de hardware. | Modelo freemium, marketing de contenidos (guías técnicas). | Actualizaciones frecuentes del producto. | Modelo freemium, testimonios de clientes, boletines de noticias. |
| **Productos & Servicios** | Flujos de trabajo específicos por dispositivo, gestión de inventario con escaneo de códigos de barras, portal del cliente. | Gestión de tickets de reparación, diseño móvil. | Gestión de órdenes de reparación, herramientas de TPV. | Seguimiento de reparaciones, carga de fotos, facturas personalizadas. |
| **Precios & Costos** | Modelo freemium (hasta $30/mes). | Modelo freemium (hasta €50/mes). | Modelo freemium (hasta €60/mes). | Modelo freemium (hasta €60/mes). |
| **Canales de distribución** | Web y móvil. | Web y móvil. | Escritorio (Windows) y móvil. | Web y móvil. |

#### Análisis SWOT

| **Fortalezas**               | **Debilidades**               | **Oportunidades**               | **Amenazas**               |
|------------------------------|--------------------------------|----------------------------------|----------------------------|
| Interfaz ágil y gamificación | Falta de plantillas específicas | Integración de IA predictiva    | Competidores establecidos  |
| Precios escalables           | Integración limitada de IA     | Expansión global multilingüe    | Amenazas de ciberseguridad |
| Diseño remoto                | Presupuesto bajo para marketing| Asociaciones con freelancers    | Herramientas SaaS "todo en uno" |

---

### 2.1.2. Estrategias y tácticas frente a competidores.

- **Enfoque Local**: Atender principalmente el mercado peruano de pequeños emprendimientos.
- **UX Dinámica y gamificación**: Priorizar una experiencia visualmente atractiva.
- **Dinámica Cliente-Negocio**: Plataforma dual (gestión + marketplace).
- **Networking**: Conectar servicios de IT y reparación automovilística con marketplaces.

---

## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.

#### Cuestionario de Gestión de Reparaciones

- ¿En qué tipo de reparaciones está especializado?  
- ¿Cuántos trabajos realiza al mes?  
- ¿Qué herramientas/software utiliza actualmente para gestionar las reparaciones, la comunicación con los clientes y el inventario?  
- ¿Cómo controla el progreso de las reparaciones en la actualidad?  
- ¿Qué funciona bien y qué es frustrante?  
- ¿Qué es lo que más tiempo le lleva de la gestión de los trabajos de reparación?  
- ¿Cómo se comunican las actualizaciones a los clientes (por ejemplo, retrasos, finalización)?  
  - ¿Qué dificultades surgen?  
- ¿Qué funciones le gustaría que tuviera el software de gestión de reparaciones?  
- ¿Cómo resolvería esto los problemas a los que se enfrenta actualmente?  
- ¿Qué le haría dudar a la hora de cambiar sus herramientas actuales?  
- ¿Qué modelo de precios (suscripción, tarifa por trabajo) le hace sentido?  
- ¿En qué se equivocan los competidores con respecto a sus necesidades?  
- ¿Puedo ponerme en contacto con usted para una prueba beta?  

---

#### Cuestionario de Experiencia como Cliente

- ¿Cuándo fue la última vez que utilizó un servicio de reparación (coche, informática, etc.)?  
  - ¿Cómo encontró al proveedor?  
- ¿Recibió actualizaciones sobre el progreso de la reparación?  
  - En caso afirmativo, ¿cómo (mensaje de texto, correo electrónico, aplicación)?  
- ¿Está satisfecho con la comunicación?  
  - ¿Qué le frustró?  
- ¿Le haría esto más propenso a elegir un servicio de reparación?  
  - ¿Por qué sí o por qué no?  
- ¿Cómo preferiría recibir las actualizaciones?  
  - (notificaciones en la aplicación, SMS, correo electrónico)  
- ¿Pagaría más por la transparencia?  
- ¿Cuál es el mayor quebradero de cabeza al que se ha enfrentado con los servicios de reparación?  
- ¿Puedo ponerme en contacto con usted?  


### 2.2.2. Registro de entrevistas.

#### **Sección 1: Dueños de Negocio**  
| Pregunta                                                                 | Respuesta | Notas |  
|--------------------------------------------------------------------------|-----------|-------|  
| ¿En qué tipo de reparaciones está especializado?                        | Generalista pero se especializa en televisores     | ...   |  
| ¿Cuántos trabajos realiza al mes?                                       | Realiza 5 trabajos al mes       | ...   |  
| ¿Qué herramientas/software utiliza actualmente para gestionar las reparaciones, la comunicación con los clientes y el inventario?                                       | Excel para la gestión de inventario y Whatsapp para la comunicación con los clientes       | ...   |  
| ¿Cómo controla el progreso de las reparaciones en la actualidad?                                       | Se utiliza excel para mapear los procesos     | La aplicación debe ser capaz de simular funcionalidades importantes de Excel  |  
| ¿Qué funciona bien y qué es frustrante?                                     |  Lo frustrante es llevar el control de lo que se avanzó y lo que no     | ...   |  
| ¿Qué es lo que más tiempo le lleva de la gestión de los trabajos de reparación?                                       | Revisar el estado de cada reparación y actualizar las hojas de excel      | La aplicación debe evitar que el negocio tenga que mantenerse al tanto de estos procesos repetitivos   |  
| ¿Cómo se comunican las actualizaciones a los clientes (por ejemplo, retrasos, finalización)? ¿Qué dificultades surgen?                                       |    Por Whatsapp, se comunica con el cliente cuando hay algún retraso y cuando la reparación está culminada    | ...   |  
| ¿Qué funciones le gustaría que tuviera el software de gestión de reparaciones?                                     |  Registrar las reparaciones con datos como las fechas, fotos, partes utilizadas y que se manden mensajes automáticos y que además se pueda indicar el tiempo de demora de las reparaciones     | Priorizar esas características en el software   |   
| ¿Qué le haría dudar a la hora de cambiar sus herramientas actuales?                                     | Que la aplicación sea muy complicada de usar y que sea dificil adaptarse      | Priorizar la UX   |  
| ¿Qué modelo de precios (suscripción, tarifa por trabajo) le hace sentido?                                       |   Modelo de suscripción mensual mientras sea accesible     | ...   |  
| ¿En qué se equivocan los competidores con respecto a sus necesidades?                                     | Lor procesos pueden ser muy complicados y están diseñados para talleres grandes      | ...   |  
| ¿Puedo ponerme en contacto con usted para una prueba beta?                               |   Sí     | ...   |  


#### **Sección 2: Clientes Regulares**  

| **ID Entrevista** | Fecha       | Tipo de Entrevistado | Duración | Entrevistador |  
|--------------------|-------------|----------------------|----------|---------------|  
| R-001              | 22/04/2025     | [Negocio]    | 4:57 | Josue Arrunategui    |  



| Pregunta                                                                 | Respuesta | Notas |  
|--------------------------------------------------------------------------|-----------|-------|  
| ¿Cuándo usó por última vez un servicio de reparación?                   | Hace 2 meses cuando se rompió la pantalla de su celular      | ...   |  
| ¿Cómo encontró al proveedor?                            | Lo encontró buscando en Google "Reparación de celulares Lima", eligió el servicio basándose en las reseñas y cercanía a su hogar     | Darle importancia al SEO local   |  
| ¿Recibió actualizaciones sobre el progreso? En caso afirmativo, ¿cómo (mensaje de texto, correo electrónico, aplicación)?                            | Sí recibió actualizaciones via Whatsapp       | ...   |  
| ¿Está satisfecho con la comunicación? ¿Qué le frustró?                              |   Sí pero le frustró el tiempo de espera y no saber si ya habían siquiera comenzado a conseguir las piezas necesarias    | El usuario está desconectado del proceso de reparación   |  
| ¿Le haría esto más propenso a elegir un servicio de reparación? ¿Por qué sí o por qué no?                           | Sí, por la transparencia del proceso y la tranquilidad que implica saber el estado de su celular     | ...   |  
| ¿Cómo preferiría recibir las actualizaciones? (notificaciones en la aplicación, SMS, correo electrónico)                           | Notificaciones en una aplicación para evitar revisar constantemente mensajes       | Ponerle importancia al diseño de las notificaciones   |  
| ¿Pagaría más por la transparencia?                            | Sí       | ...   |  
| ¿Cuál es el mayor quebradero de cabeza al que se ha enfrentado con los servicios de reparación?                            | Su mayor problema ha sido la falta de información e incertidumbre      | ...   |  
| ¿Puedo ponerme en contacto con usted?                             | Sí     | ...   |  

--------------------------------------------------------------------------
--------------------------------------------------------------------------

| **ID Entrevista** | Fecha       | Tipo de Entrevistado | Duración | Entrevistador |  
|--------------------|-------------|----------------------|----------|---------------|  
| 002              | 22/04/2025     | [Cliente]    |   4:57  | Eduardo André Chero

| Pregunta                                                                 | Respuesta | Notas |  
|--------------------------------------------------------------------------|-----------|-------|  
| ¿Cuándo usó por última vez un servicio de reparación?                   | Hace 6 meses      | ...   |  
| ¿Cómo encontró al proveedor?                            | Centro de cómputo en miraflores      | Tener en cuenta a los potenciales clientes que se basan principalmente en la ubicación del local  |  
| ¿Recibió actualizaciones sobre el progreso? En caso afirmativo, ¿cómo (mensaje de texto, correo electrónico, aplicación)?                            | No, únicamente le informaron cuando la reparación ya estaba lista     | ...   |  
| ¿Está satisfecho con la comunicación?  ¿Qué le frustró?                           | Preferiría haber recibido comunicación más seguido       | ...   |  
| ¿Le haría esto más propenso a elegir un servicio de reparación?  ¿Por qué sí o por qué no?                          | Sí, para saber acerca de los problemas del producto a reparar       | ...   |  
| ¿Cómo preferiría recibir las actualizaciones? (notificaciones en la aplicación, SMS, correo electrónico)                           | Por Whatsapp o correo       | Tener medios externos en los que el negocio pueda comunicarse con el cliente   |  
| ¿Pagaría más por la transparencia?                            | Depende de lo que necesite la reparación y la calidad del técnico      | ...   |  
| ¿Cuál es el mayor quebradero de cabeza al que se ha enfrentado con los servicios de reparación?                            | Que no le brindan un informe continuo, menciona que tuvo percances en el pasado en el que el producto no había sido arreglado correctamente y lo descubrió hasta 1 semana después      | Tener en cuenta las reseñas y precedentes de los usuarios   |  
| ¿Puedo ponerme en contacto con usted?                             | Sí       | ...   |  

--------------------------------------------------------------------------
--------------------------------------------------------------------------


### 2.2.3. Análisis de entrevistas.

#### Síntesis por Categorías

Categoría    | Hallazgos Clave	 | Recomendaciones |  
|--------------------------------------------------------------------------|-----------|-------|  
| **Comunicación** | Los negocios principalmente se comunican con sus clientes mediante Whatsapp     | Implementar notificaciones automáticas multi-canal (app + WhatsApp) y plantillas de mensajes.   |
| **Transparencia** | -Los clientes prefieren seguimiento en tiempo real     | Crear un panel que permita a los técnicos publicar el progreso y a los usuarios visualizarlo y recibir notificaciones al respecto   |
| **Precios** |  Técnicos prefieren suscripción mensual accesible.Clientes pagarían más por transparencia (condicional).  | Ofrecer plan freemium para técnicos y niveles premium con garantías verificadas. |


#### Pain Points Prioritizados

Pain Point	    | Impacto |  
|--------------------------------------------------------------------------|-----------|  
| **Herramientas fragmentadas** | Alto |
| **Falta de transparencia en procesos** | Alto |
| **Comunicación reactiva (no proactiva)** | Medio   |

#### Oportunidades de Producto

Oportunidad   | Potencial | Alcance |  
| --------------------------------------------------------------------------|-----------|-------|  
| **Panel unificado de reparaciones** | Alto      | Técnicos/Clientes	   |
| **Notificaciones automáticas** | Alto      | Clientes   |
| **Certificaciones técnicas visibles** |  Medio  | Clientes | 

## 2.3. Needfinding.


### 2.3.1. User Personas.

#### **User Persona: Freelancer / Dueño de negocio pequeño de Reparaciones IT**

- **Objetivos**:  
  1. Agilizar reparaciones in situ.  
  2. Minimizar trabajo administrativo.  

- **Puntos débiles**:  
  1. Canales de comunicación dispersos.  
  2. Falta de software asequible.  

#### **User Persona: Cliente Regular**

- **Objetivos**:  
  1. Encontrar técnicos calificados.  
  2. Seguimiento en tiempo real.  

- **Puntos débiles**:  
  1. Desconfianza en técnicos nuevos.  
  2. Comunicación lenta.  


### 2.3.2. User Task Matrix.


| Persona               | Tareas                               | Features                                  | Prioridad | Notas                          |
|-----------------------|--------------------------------------|-------------------------------------------|-----------|--------------------------------|
| **Freelancer**        | Actualizar estado de trabajos        | Interfaz móvil, facturación automatizada  | Alta      | Priorizar UX móvil            |
| **Usuario Regular**   | Encontrar técnicos calificados       | Búsqueda con filtros, notificaciones SMS  | Alta      | Integración con proveedores   |

---
### 2.3.3. User Journey Mapping.

#### Técnico IT

| **Stage**       | **Touchpoints**               | **Actions**                     | **Emotions**                | **Pain Points**           | **Opportunities**               |
|-----------------|-------------------------------|---------------------------------|-----------------------------|---------------------------|----------------------------------|
| **Awareness**   | Grupos de freelancers         | Buscar herramientas de gestión  | Molestia por alternativas   | Funcionalidades limitadas | Anuncios en redes sociales      |
| **Sign-Up**     | Descargar aplicación          | Elegir plan gratuito            | Optimismo por ahorrar tiempo| Miedo a costos ocultos    | Claridad en costos               |


#### Cliente Regular

| **Stage**           | **Touchpoints**               | **Actions**                     | **Emotions**                | **Pain Points**           | **Opportunities**               |
|---------------------|-------------------------------|---------------------------------|-----------------------------|---------------------------|----------------------------------|
| **Need Identification** | Portátil roto              | Buscar en Google               | Estrés por urgencia         | Plazos poco claros        | Guías DIY en la app              |

---


### 2.3.4. Empathy Mapping.

#### Técnico IT

| **Say**                          | **Thinks**                     | **Feels**                      | **Does**                     |
|----------------------------------|--------------------------------|--------------------------------|------------------------------|
| "Los clientes no confían"        | "Necesito demostrar confiabilidad" | Frustrado por la competencia   | Envía actualizaciones vía WhatsApp |

#### Usuario

| **Say**                          | **Thinks**                     | **Feels**                      | **Does**                     |
|----------------------------------|--------------------------------|--------------------------------|------------------------------|
| "No sé si este técnico es confiable" | "¿Me cobrarán de más?"        | Ansiedad por perder tiempo     | Busca reseñas en Google      |

---

### 2.3.5. As-is Scenario Mapping.

#### Técnico IT

| **Stages**          | **Actions**               | **Tools Used**       | **Pain Points**       | **Opportunities**          |
|---------------------|---------------------------|----------------------|-----------------------|----------------------------|
| **Consulta de clientes** | Llamadas telefónicas   | Excel, WhatsApp      | Llamadas perdidas     | Integración de reservas online |
| **Gestión de inventario** | Hojas de cálculo      | Registros en papel   | Exceso de existencias | Escaneado de códigos de barras |

#### Usuario

| **Stages**          | **Actions**               | **Tools Used**       | **Pain Points**       | **Opportunities**          |
|---------------------|---------------------------|----------------------|-----------------------|----------------------------|
| **Búsqueda de técnicos** | Busca en Google       | Google Maps          | Reseñas falsas        | Filtros inteligentes       |

## 2.4. Ubiquitous Language.