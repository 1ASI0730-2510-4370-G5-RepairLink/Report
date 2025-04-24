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

### 2.2.3. Análisis de entrevistas.

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