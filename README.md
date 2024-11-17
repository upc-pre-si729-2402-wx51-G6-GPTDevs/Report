# <center>COURSE PROJECT</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software - 2024-2</strong><br>
    <strong>Desarrollo de Aplicaciones Open Source - WX51</strong><br>
    <strong>Profesor: Alberto Wilmer Sanchez Seña</strong><br>
    <br><strong>Informe del Trabajo Final</strong>
</p>

</p>

<p align="center">
    <strong>Startup: GPTDevs</strong><br>
    <strong>Producto: TaskLinker </strong>
</p>

<div style="text-align:center;">
    <h3>Team Members:</h3>
    <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Ramos Najar, Tony Alexander</td>
            <td>U20211A153</td>
        </tr>
        <tr>
            <td>Sanchez Rios, Camila Cristina</td>
            <td>U202210973</td>
        </tr>
        <tr>
            <td>Durand Vera, Gianfranco Angel</td>
            <td>U20201F640</td>
        </tr>
        <tr>
            <td>Chávarri Zarzosa, Daniel Jhared</td>
            <td>U202211108</td>
        </tr>
    </table>
</div>

<p align="center">
    <strong>Agosto, 2024</strong>
</p>
<br>

<h1 align="center">Registro de versiones del Informe</h1>
</br>
<table>
        <thead>
            <tr>
                <th>Versión</th>
                <th>Fecha</th>
                <th>Autor</th>
                <th>Descripción de modificaciones</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <th>TB1</th>
                <td>20/08/2024</td>
                <td>
                    <ul>
          <li>Tony Ramos</li>
          <li>Camila Sanchez</li>
          <li>Gianfranco Durand</li>
          <li>Daniel Chávarri</li>
                    <ul>
           </td>
      <td>            
             <ul>
          <li>Capítulo I: Introducción</li>
          <li>Capítulo II: Requirements Elicitation & Analysis</li>
          <li>Capítulo III: Requirements Specification</li>
          <li>Capítulo IV: Product Design</li>
          <li>Avance del Capítulo V: Product Implementation, Validation & Deployment hasta el punto 5.2.1.8</li>
          <li>Avance de Conclusiones, Bibliografía y Anexos</li>
        </ul>
      </td>
  </tr>
</tbody>
</table>

# Project Report Collaboration Insights

# Contenido
[Student Outcome](#student-outcome)

[Capítulo I: Introducción](#capítulo-i-introducción)
- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2 Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

[Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
- [2.1. Competidores](#21-competidores)
  - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
  - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
  - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
  - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
  - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
  - [2.3.1. User Personas](#231-user-personas)
  - [2.3.2. User Task Matrix](#232-user-task-matrix)
  - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
  - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [2.4. Ubiquitous Language](#24-ubiquitous-language)

[Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

[Capítulo IV: Product Design](#capítulo-iv-product-design)
- [4.1. Style Guidelines](#41-style-guidelines)
  - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
  - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
- [4.2. Information Architecture](#42-information-architecture)
  - [4.2.1. Organization Systems](#421-organization-systems)
  - [4.2.2. Labeling Systems](#422-labeling-systems)
  - [4.2.3. SEO Tags and Meta Tag](#423-seo-tags-and-meta-tag)
  - [4.2.4. Searching Systems](#424-searching-systems)
  - [4.2.5. Navigation Systems](#425-navigation-systems)
- [4.3. Landing Page UI Design](#43-landing-page-ui-design)
  - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
  - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
  - [4.4.1. Web Applications Wireframes](#411-general-style-guidelines)
  - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
  - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
  - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
- [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
- [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
  - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
  - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
  - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
- [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
  - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.7.2. Class Dictionary](#472-class-dictionary)
- [4.8. Database Design](#48-database-design)
  - [4.8.1. Database Diagram](#481-database-diagram)

[Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
- [5.1. Software Configuration Management](#51-software-configuration-management)
  - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
  - [5.1.2. Source Code Management](#512-source-code-management)
  - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
  - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
  - [5.2.X. Sprint ](#52x-sprint)
    - [5.2.X.1. Sprint Planning n](#52x1-sprint-planning-n)
    - [5.2.X.2. Sprint Backlog n](#52x2-sprint-backlog-n)
    - [5.2.X.3. Development Evidence for Sprint Review](#52x3-development-evidence-for-sprint-review)
    - [5.2.X.4. Testing Suite Evidence for Sprint Review](#52x4-testing-suite-evidence-for-sprint-review)
    - [5.2.X.5. Execution Evidence for Sprint Review](#52x5-execution-evidence-for-sprint-review)
    - [5.2.X.6. Services Documentation Evidence for Sprint Review](#52x6-services-documentation-evidence-for-sprint-review)
    - [5.2.X.7. Software Deployment Evidence for Sprint Review](#52x7-software-deployment-evidence-for-sprint-review)
    - [5.2.X.8. Team Collaboration Insights during Sprint](#52x8-team-collaboration-insights-during-sprint)
- [5.3. Validation Interviews](#53-validation-interviews)
  - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
  - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
  - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
- [5.4. Video About-the-Product](#54-video-about-the-product)

[Conclusiones](#conclusiones)
- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)

[Bibliografía](#bibliografía)

[Anexos](#anexos)

# Student Outcome
ABET – EAC - Student Outcome 3

Criterio: Capacidad de comunicarse efectivamente con un rango de audiencias

Criterio: Capacidad de comunicarse efectivamente con un rango de audiencias

<table>
  <tr>
    <td><b>Criterio específico</b></td>
    <td><b>Acciones realizadas</b></td>
    <td><b>Conclusiones</b></td>
  </tr>
    </thead>
  <tbody>
    <tr>
      <td><b>Comunica oralmente con
efectividad a diferentes rangos
de audiencia.</b></td>
      <td>
        <p><b>Ramos Najar, Tony Alexander  </b></p>
        <p><b>TB1:</b></p>
        <p>Capítulo II: Requirements Elicitation & Analysis y User Stories<br> Realicé un optimo trabajo en equipo, para crear, visualizar y corregir detalles importantes, además fui flexible con el tiempo de entrega de los capítulos</p>
        <p><b>TP1:</b></p>
        <p>Para esta entrega, realice correciones al documento general, además de implementar el product backlog en Trello con las historias de usuario correspondientes al sprint 2.</p>
        <p><b>TB2:</b></p>
        <p>Para esta entrega, se trabajó el Sprint 3 que consta de la implementación de los Web Services o Backend, en mi caso me enfoqúe en el Vounded Context Profiles.</p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Sanchez Rios, Camila Cristina</b></p>
       <p><b>TB1:</b></p>
        <p>Realicé el Capítulo III: Product Design y User Stories; también realicé lo sieguiente del Capítulo IV: 4.1. Style Guidelines, General Style Guidelines, Web Style Guidelines, Information Architecture, Organization Systems, Labeling Systems, SEO Tags and Meta Tags, Searching Systems, Navigation Systems, Landing Page UI Design, Landing Page Wireframe, Landing Page Mock-up, Web Applications UX/UI Design, Web Applications Wireframes, Web Applications Wireflow Diagrams, Web Applications Mock-ups, Web Applications User Flow Diagrams, Web Applications Prototyping.</p>
        <p><b>TP1:</b></p>
        <p>Correcciones al reporte los agregué a los User Stories los Technical Stories y trabajé en el desarrollo del frontend Toolbar y Traduccion. Colaboración en el proyecto cumpliendo con las indicaciones realizadas por el equipo para lograr lo esperado.</p>
        <p><b>TB2:</b></p>
        <p>Para esta entrega colabore con la parte del web Services Job Post BC y la parte del Capitulo 5 - 5.3. Validation Interviews con algunas correciones.</p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Durand Vera, Gianfranco Angel</b></p>
        <p><b>TB1:</b></p>
        <p>Capítulo IV: Product Design y User Stories <br>Coordiné y realicé la reunión inicial del proyecto, explicando claramente los objetivos y el plan de trabajo. Cree diferentes reuniones para clarificar los roles de cada integrante del equipo.      
        </p>
        <p><b>TP1:</b></p>
        <p>Realicé commits para la web application siguendo las convenciones para una comunicación escrita, realice el deployment de la aplicación de modo que los interesados puedan ver el avance del proyecto y tener un producto en desarrollo que demuestre nuestro avance durante el sprint.</p>
        <p><b>TB2:</b></p>
        <p>En esta tercera entrega, se desarrolló el Sprint 3 del proyecto. Para ello, realizamos los avances correspondientes en Frontend y Backend.</p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Chávarri Zarzosa, Daniel Jhared</b></p>
       <p><b>TB1:</b></p>
        <p>Capítulo III: Requirements Specification</p>
        <p><b>TP1:</b></p>
        <p>En resumen, para el Front-end hice el feature/work-done y feature/task, correjí el impact mapping y implementé la presentación del canva.</p>
        <p><b>TB2:</b></p>
        <p>En esta parte, realicé la parte del back-end, el context NotificationsBC y algunas mejoras con respecto a nuestro proyecto.</p>
        <p><b>TF:</b></p>
        <p>Continué mejorando el back-end de mi context Notifications-BC, agregando lo que había implementado el profesor, también hice recordatorios a mis compañeros de hacer las actividades pendientes, con el fin de acabar el proyecto de manera satisfactoria.</p>
      </td>
      <td>
        <p><strong>TB1:</strong></p>
        <p>En conclusión, en esta primera entrega se logró una buena comunicación entre los miembros del equipo. Cada participante estuvo activo y presento sus ideas de manera que todos pudieran entenderse entre sí. Concluimos que aún hay pequeñas dificultades para expresarnos con todos, pero que se puede solucionar con tiempo.</p>
        <p><strong>TP1:</strong></p>
        <p>En resumen, durante esta etapa del proyecto, implementamos las mejoras sugeridas por el profesor, las cuales incluyeron la mejora de user storires. Además, todos los integrantes del equipo completaron con éxito todas las actividades asignadas en el segundo sprint.</p>
        <p><strong>TB2:</strong></p>
        <p>En conclusión, para esta entrega se comunicó con los segmentos objetivo para obtener retroalimentación de nuestro avance con los productos de software. Asimismo, se desarrollaron los videos About-The-Product y About-The-Team que muestran como hemos desarrollado nuestra propuesta.</p>
        <p><strong>TF:</strong></p>
        <p>En conclusión, para esta entrega final nos mantenimos comunicados de forma activa mediante mensajes y la documentación de nuestros avances tanto de los back-ends, landing page, el reporte y la validación de dichos productos.</p>
      </td>
    </tr>
    <tr>
      <td>Comunica por escrito con
efectividad a diferentes rangos
de audiencia.</td>
      <td>
        <p><b>Ramos Najar, Tony Alexander  </b></p>
        <p><b>TB1:</b></p>
        <p>Capítulo II: Requirements Elicitation & Analysis y User Stories<br> Realicé correctamente lo establecido para esta entrega, además apoyé en otras definiciones a mi team Collab</p>
        <p><b>TP1:</b></p>
        <p>Para esta entrega, realice correciones al documento general, además de implementar el product backlog en Trello con las historias de usuario correspondientes al sprint 2.</p>
        <p><b>TB2:</b></p>
        <p>Para esta entrega, se trabajó el Sprint 3 que consta de la implementación de los Web Services o Backend, en mi caso me enfoqúe en el Vounded Context Profiles.</p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Sanchez Rios, Camila Cristina</b></p>
       <p><b>TB1:</b></p>
        <p>Realicé el Capítulo III: Product Design y User Stories; también realicé lo sieguiente del Capítulo IV: 4.1. Style Guidelines, General Style Guidelines, Web Style Guidelines, Information Architecture, Organization Systems, Labeling Systems, SEO Tags and Meta Tags, Searching Systems, Navigation Systems, Landing Page UI Design, Landing Page Wireframe, Landing Page Mock-up, Web Applications UX/UI Design, Web Applications Wireframes, Web Applications Wireflow Diagrams, Web Applications Mock-ups, Web Applications User Flow Diagrams, Web Applications Prototyping.</p>
        <p><b>TP1:</b></p>
        <p>Correcciones al reporte los agregué a los User Stories los Technical Stories y trabajé en el desarrollo del frontend Toolbar y Traduccion. Colaboración en el proyecto cumpliendo con las indicaciones realizadas por el equipo para lograr lo esperado.</p>
        <p><b>TB2:</b></p>
        <p>Para esta entrega colabore con la parte del web Services Job Post BC y la parte del Capitulo 5 - 5.3. Validation Interviews con algunas correciones.</p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Durand Vera, Gianfranco Angel</b></p>
        <p><b>TB1:</b></p>
        <p>Capítulo IV: Product Design y User Stories <br>Cree repositorios para almacenar nuestro informe con un registro de versiones constante, además de comenzar un registro de los puntos que nos falta completar.
        </p>
        <p><b>TP1:</b></p>
        <p>Realicé commits para la web application siguendo las convenciones para una comunicación escrita, realice el deployment de la aplicación de modo que los interesados puedan ver el avance del proyecto y tener un producto en desarrollo que demuestre nuestro avance durante el sprint.</p>
        <p><b>TB2:</b></p>
        <p>En esta tercera entrega, se desarrolló el Sprint 3 del proyecto. Para ello, realizamos los avances correspondientes en Frontend y Backend.</p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Chávarri Zarzosa, Daniel Jhared</b></p>
       <p><b>TB1:</b></p>
        <p>Capítulo III: Requirements Specification</p>
        <p><b>TP1:</b></p>
        <p>En resumen, para el Front-end hice el feature/work-done y feature/task, correjí el impact mapping y implementé la presentación del canva.</p>
        <p><b>TB2:</b></p>
        <p>En esta parte, realicé la parte del back-end, el context NotificationsBC y algunas mejoras con respecto a nuestro proyecto.</p>
        <p><b>TF:</b></p>
        <p>Continué mejorando el back-end de mi context Notifications-BC, agregando lo que había implementado el profesor, también hice recordatorios a mis compañeros de hacer las actividades pendientes, con el fin de acabar el proyecto de manera satisfactoria.</p>
      </td>
       <td>
        <p><strong>TB1:</strong></p>
        <p>Se participó equitativamente el informe. En conclusión, estamos en camino para desempeñarnos de manera equitativa en el trabajo.</p>
        <p><strong>TP1:</strong></p>
        <p>En resumen, durante esta etapa del proyecto, implementamos las mejoras sugeridas por el profesor, las cuales incluyeron la mejora de user storires. Además, todos los integrantes del equipo completaron con éxito todas las actividades asignadas en el segundo sprint.</p>
        <p><strong>TB2:</strong></p>
        <p>En conclusión, para esta entrega se comunicó con los segmentos objetivo para obtener retroalimentación de nuestro avance con los productos de software. Asimismo, se desarrollaron los videos About-The-Product y About-The-Team que muestran como hemos desarrollado nuestra propuesta.</p>
        <p><strong>TF:</strong></p>
        <p>En conclusión, para esta entrega final nos mantenimos comunicados de forma activa mediante mensajes y la documentación de nuestros avances tanto de los back-ends, landing page, el reporte y la validación de dichos productos.</p>
      </td>
    </tr>
  </tbody>
</table>

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
"TaskLinker" es una innovadora plataforma web que facilita la conexión entre personas que buscan ingresos adicionales laborando por horas y quienes requieren contratar servicios temporales o para tareas específicas. Dirigida a estudiantes, amas de casa, jubilados y cualquier persona interesada en trabajos por horas, TaskLinker actúa como un puente efectivo y confiable entre la oferta y la demanda en el mercado laboral peruano. A través de nuestra plataforma, tanto individuos como organizaciones pueden encontrar soluciones rápidas y eficientes para sus necesidades, optimizando el uso de la fuerza laboral disponible y promoviendo la flexibilidad en el empleo.

La misión de TaskLinker es empoderar a las personas con oportunidades de trabajo flexible, permitiéndoles generar ingresos adicionales en sus propios términos. Al mismo tiempo, buscamos proporcionar a las organizaciones e individuos una herramienta eficiente para encontrar y contratar rápidamente talento adecuado para sus necesidades temporales o específicas.

Nuestra visión es convertirnos en la plataforma líder en Perú para la contratación de trabajos por horas y servicios temporales, siendo reconocidos por nuestra capacidad para conectar de manera efectiva a las personas con oportunidades de ingresos adicionales. Aspiramos a expandir nuestro impacto, promoviendo un mercado laboral más dinámico, inclusivo y flexible, donde cada persona pueda acceder fácilmente a oportunidades laborales que se ajusten a su estilo de vida y necesidades, mientras que las organizaciones logran satisfacer sus demandas con rapidez y precisión.

### 1.1.2. Perfiles de integrantes del equipo
<table>
  <tr>
    <th>
      <img src="assets/TonyRamos.png" alt="Foto de perfil de Tony" width="800px">
    </th>
    <td valign="top">
      <p><b>Ramos Najar, Tony Alexander</b></p>
      <p>
        Mi nombre es Tony Ramos, estoy cursando el 8vo ciclo de la carrera de Ingeniería de Software. Me considero hábil en el ámbito de la programación en los lenguajes, Python, Javascript, y últimamente estoy aprendiendo Angular. Con respeto a mi, me considero una persona responsable, con ganas de aprender y superarme a mí mismo
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="assets/fotocam.png" alt="Foto de perfil de Camila" width="800px">
    </th>
    <td valign="top">
      <p><b>Sánchez Ríos, Camila Cristina</b></p>
      <p>
        Soy estudiante de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas, actualmente me encuentro en el cuarto ciclo. Me gusta escuchar música y leer en los ratos libres y aprender más sobre la carrera.
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="assets/franco.jpg" alt="Foto de perfil de Gianfranco" width="800px">
    </th>
    <td valign="top">
      <p><b>Durand Vera, Gianfranco Ángel</b></p>
      <p>
        Soy estudiante de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas, actualmente me encuentro en el sexto ciclo, escogí esta carrera porque me gusta mucho la programación. Tengo experiencia en lenguajes de programación como C++, C#, Python, Kotlin y JavaScript.
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="assets/daniel.jpeg" alt="Foto de perfil de Daniel" width="800px">
    </th>
    <td valign="top">
      <p><b>Chávarri Zarzosa, Daniel Jhared</b></p>
      <p>
       Soy estudiante de la UPC, tengo 19 años. Estoy en la carrera de Ingeniería de Software, ya que, siempre me gustó la tecnología, los videojuegos, las páginas web, pero sobre todo cómo crearlos. Estoy cursando el 5 ciclo de la carrera y mis habilidades son C++, Python, HTML y JavaScript. También soy bueno en ser responsable con cada curso y organizar mi tiempo en ellos.
      </p>
    </td>
  </tr>
</table>
<br>

## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática
En el mercado laboral peruano, existe una creciente demanda de trabajos temporales y por horas, impulsada tanto por trabajadores que buscan flexibilidad como por empleadores que requieren soluciones rápidas para tareas específicas. No obstante, la falta de una plataforma centralizada ha dificultado la conexión eficiente entre ambas partes, lo que resulta en una subutilización del talento disponible y en procesos de contratación ineficaces.

**5W y 2H**

- **Who (Quién):** 

Los trabajadores objetivo de TaskLinker incluyen estudiantes, amas de casa, jubilados y personas con empleo parcial que buscan ingresos adicionales sin comprometer sus horarios. Por otro lado, los empleadores incluyen pequeñas y medianas empresas (PyMEs), particulares, organizadores de eventos, y startups que necesitan contratar personal temporal de manera rápida y eficiente.

- **What (Qué):**

TaskLinker es una plataforma web que facilita la conexión entre personas que buscan trabajo temporal por horas y empleadores que necesitan contratar servicios específicos. La plataforma ofrece una solución centralizada que permite a ambas partes encontrar rápidamente lo que necesitan, ya sea una oportunidad de trabajo flexible o personal temporal calificado.

- **Where (Dónde):**

La plataforma opera principalmente en el mercado laboral peruano, donde existe una alta demanda de trabajos temporales y por horas. TaskLinker está diseñada para ser accesible desde cualquier dispositivo con conexión a internet, lo que la hace disponible en cualquier lugar dentro del ámbito nacional.

- **When (Cuándo):**

La necesidad de TaskLinker surge en un contexto donde la economía y el mercado laboral están en constante cambio, con un aumento en la demanda de flexibilidad tanto por parte de trabajadores como de empleadores. Esta plataforma es especialmente útil en momentos de alta demanda laboral temporal, como durante eventos especiales o picos estacionales de trabajo.

- **Why (Por qué):**

La falta de una plataforma centralizada que conecte de manera efectiva a trabajadores temporales con empleadores ha llevado a una subutilización de la fuerza laboral disponible y a ineficiencias en el proceso de contratación. TaskLinker responde a esta problemática proporcionando una solución que simplifica y agiliza la búsqueda de trabajo temporal y la contratación de personal por horas, beneficiando a ambos lados del mercado.

-  **How (Cómo):**

TaskLinker funciona a través de una plataforma en línea intuitiva donde los trabajadores pueden crear perfiles, buscar y postularse a trabajos que se ajusten a sus habilidades y disponibilidad. Los empleadores pueden publicar tareas o proyectos específicos y acceder a una base de trabajadores calificados de manera rápida. La plataforma integra un sistema de evaluaciones y reputación para garantizar la confianza y transparencia en las interacciones. El modelo de negocio se sustenta en dos esquemas principales: una comisión por transacción, que se cobra cuando un trabajador es contratado y completa un trabajo, y un plan de suscripción premium, que elimina las comisiones y ofrece beneficios adicionales como priorización en los listados y acceso a tareas exclusivas.

- **How Much (Cuánto):**

En el esquema de comisión por transacción, TaskLinkera cobra una pequeña comisión proporcional al valor del trabajo, la cual se descuenta automáticamente una vez que el trabajo es completado y pagado. Por otro lado, el plan de suscripción premium tiene un costo fijo que elimina estas comisiones por transacción y brinda acceso a funcionalidades avanzadas, como la priorización en los listados, acceso a tareas exclusivas, y herramientas de gestión mejoradas. Este modelo de negocio está diseñado para ser accesible y rentable, permitiendo a los usuarios elegir la opción que mejor se adapte a sus necesidades y volumen de trabajo.

### 1.2.2 Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements

En el mercado laboral peruano, existe una desconexión significativa entre la oferta y la demanda de trabajos temporales y por horas. Por un lado, los trabajadores buscan flexibilidad para encontrar oportunidades que se ajusten a su disponibilidad. Por otro, los empleadores necesitan contratar personal de manera rápida y eficiente para tareas puntuales o picos de trabajo. Sin embargo, la falta de una plataforma centralizada que facilite esta conexión genera ineficiencias en ambos lados, creando barreras para la optimización del talento disponible y el acceso a oportunidades laborales.

Estudiantes, amas de casa, jubilados y personas con empleo parcial en Perú se enfrentan a un desafío constante: ¿cómo encontrar trabajos temporales o por horas que se ajusten a sus horarios y necesidades específicas? Actualmente, la falta de una plataforma centralizada y eficiente para acceder a estas oportunidades laborales limita su capacidad para generar ingresos adicionales, lo que lleva a una subutilización de su tiempo y potencial.  ¿Qué solución podría ofrecerse para permitirles encontrar trabajos de manera rápida y eficiente, maximizando su tiempo disponible?

La falta de un sistema eficiente que centralice estas oportunidades también deja en desventaja a los trabajadores que desean postularse a trabajos en los que tienen experiencia o competencias específicas. ¿Qué características debe tener una plataforma para asegurar que los trabajadores puedan filtrar y postularse solo a las oportunidades que realmente les interesan, sin comprometer su tiempo ni su disponibilidad para otras responsabilidades personales?

Pequeñas y medianas empresas (PyMEs), startups, organizadores de eventos y particulares en Perú se enfrentan a una necesidad urgente: ¿cómo contratar personal temporal para tareas específicas o picos de trabajo de manera rápida y efectiva? 

La falta de una solución adecuada provoca retrasos operativos, un aumento en los costos de contratación y una menor eficiencia en la gestión de recursos humanos. ¿Qué plataforma puede facilitar este proceso, reduciendo el tiempo de contratación y mejorando la eficiencia en la búsqueda de talento calificado? Además, ¿cómo se puede asegurar que los empleadores puedan acceder a una base confiable de trabajadores con las habilidades necesarias para sus tareas específicas sin incurrir en largos procesos de selección?

#### 1.2.2.2. Lean UX Assumptions
**Business Outcomes:**

1. Si ofrecemos una plataforma fácil de usar con un proceso de registro rápido y accesible, más trabajadores potenciales (estudiantes, amas de casa, jubilados) se inscribirán y utilizarán la plataforma para obtener ingresos adicionales.
2.  Si proporcionamos un sistema eficiente para la contratación rápida y confiable de trabajadores temporales, los empleadores recurrirán a la plataforma para cubrir tareas específicas de manera recurrente.
3.  Si simplificamos el proceso de contratación y comunicación entre empleadores y trabajadores, el número de trabajos realizados a través de la plataforma aumentará.
4.  Si mejoramos las herramientas de búsqueda y filtrado, los empleadores podrán encontrar candidatos adecuados de manera más eficiente.
5.  Si ofrecemos características premium valiosas como eliminación de comisiones, acceso a tareas exclusivas y visibilidad prioritaria, más usuarios optarán por suscribirse al plan premium.
6.  Si implementamos un sistema de evaluación transparente y confiable, tanto trabajadores como empleadores tendrán más confianza al usar la plataforma, lo que aumentará la satisfacción general.
7.  Si notificamos a los trabajadores de nuevas oportunidades relevantes para sus habilidades, aumentaremos su participación activa en la plataforma.
8.  Si lanzamos campañas de marketing dirigidas a nuevas regiones, podemos atraer a trabajadores y empleadores de otras ciudades, ampliando nuestro alcance geográfico.
9.  Si mejoramos la facilidad y seguridad en los métodos de pago, aumentará la confianza y la velocidad en las transacciones entre empleadores y trabajadores.
10. Si facilitamos la interacción entre los usuarios (trabajadores y empleadores) a través de herramientas de mensajería y soporte, mejoraremos la percepción de confianza y colaboración en la plataforma.

#### 1.2.2.3. Lean UX Hypothesis Statements

**Hipótesis 1:**

Creemos que si proporcionamos un proceso de registro rápido y fácil para los trabajadores, aumentará la tasa de inscripción en la plataforma. Sabremos que esto es verdad cuando veamos un  aumento del 25% en las inscripciones de nuevos usuarios dentro de los primeros 3 meses de optimizar el proceso de registro.

**Hipótesis 2:**

Creemos que las personas en Perú (estudiantes, amas de casa, jubilados, etc.) tienen dificultades para encontrar trabajos flexibles y por horas que se ajusten a sus necesidades y horarios. Si ofrecemos una plataforma que centraliza la oferta y demanda de trabajos por horas, las personas podrán encontrar oportunidades laborales de forma rápida y fácil. Observaremos un aumento en el número de personas registradas y en la frecuencia con la que encuentran trabajo a través de la plataforma.

**Hipótesis 3:**

Creemos que las pequeñas y medianas empresas (PyMEs) en Perú necesitan contratar servicios temporales de manera eficiente, pero enfrentan dificultades en el proceso de búsqueda y contratación. Si proporcionamos una plataforma donde puedan publicar tareas y contratar trabajadores de forma rápida, las PyMEs podrán cubrir sus necesidades temporales sin problemas. Veremos una alta tasa de satisfacción entre los empleadores y un aumento en el número de tareas publicadas en la plataforma.

**Hipótesis 4:**

Creemos que muchos usuarios en Perú valoran la flexibilidad y desean acceder a una plataforma gratuita para comenzar a trabajar inmediatamente. Si ofrecemos una opción gratuita con comisiones por tarea realizada y un plan premium que elimina esas comisiones, los usuarios podrán empezar a trabajar sin barreras económicas. Tendremos una alta conversión de usuarios del plan gratuito al plan premium a medida que generen más ingresos.

**Hipótesis 5:**

Creemos que un sistema de evaluaciones y reseñas mejorará la confianza entre empleadores y trabajadores, lo que resultará en más transacciones exitosas. Sabremos que esto es verdad cuando veamos un incremento en las evaluaciones en un 30% más de trabajos finalizados con reseñas positivas dentro del primer año de implementación del sistema de evaluaciones.

#### 1.2.2.4. Lean UX Canvas

<img src="assets/canva2.png">
*Imagen (N°1). Elaboración propia. Realizado en Canva*

## 1.3. Segmentos objetivo
**1. Trabajadores que buscan ingresos adicionales y flexibilidad:**
Este segmento incluye a estudiantes que necesitan ingresos para cubrir sus estudios o gastos personales sin afectar sus horarios académicos, amas de casa que desean contribuir económicamente sin comprometer sus responsabilidades en el hogar, jubilados que buscan mantenerse activos y generar ingresos extra, y personas con empleo parcial que desean complementar sus ingresos. Todos ellos valoran la flexibilidad que les ofrece TaskLinker, permitiéndoles encontrar oportunidades laborales que se adapten a su tiempo y necesidades específicas.

**2. Empleadores que requieren soluciones laborales temporales:**

Este segmento abarca a pequeñas y medianas empresas (PyMEs) que necesitan personal temporal para cubrir picos de trabajo o tareas específicas, particulares que requieren servicios domésticos, reparaciones, o tareas puntuales sin compromiso a largo plazo, organizadores de eventos que necesitan personal por horas para diferentes funciones como catering o atención al cliente, y startups que demandan flexibilidad en la contratación para adaptarse al ritmo dinámico de su crecimiento. Estos empleadores buscan soluciones rápidas, confiables y eficientes para satisfacer sus necesidades laborales temporales.


# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores
### 2.1.1. Análisis competitivo
### 2.1.2. Estrategias y tácticas frente a competidores
## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas
## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
### 2.3.5. As-is Scenario Mapping
## 2.4. Ubiquitous Language

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping
## 3.2. User Stories
## 3.3. Impact Mapping
## 3.4. Product Backlog

# Capítulo IV: Product Design
## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines
### 4.1.2. Web Style Guidelines
## 4.2. Information Architecture
### 4.2.1. Organization Systems
### 4.2.2. Labeling Systems
### 4.2.3. SEO Tags and Meta Tag
### 4.2.4. Searching Systems
### 4.2.5. Navigation Systems
## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Mock-up
## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.3. Web Applications Mock-ups
### 4.4.4. Web Applications User Flow Diagrams
## 4.5. Web Applications Prototyping
## 4.6. Domain-Driven Software Architecture
### 4.6.1. Software Architecture Context Diagram
### 4.6.2. Software Architecture Container Diagrams
### 4.6.3. Software Architecture Components Diagrams
## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
### 4.7.2. Class Dictionary
## 4.8. Database Design
## 4.8.1. Database Diagram

# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
En la siguiente sección se describe la ruta de referencia de cada uno de los productos de software para
que cualquier miembro del equipo pueda desarrollar cada punto del trabajo.

- **UXPressia:** Plataforma colaborativa que nos permitirá crear user personas e integrados con los
múltiples mapas para evaluar sus prioridades.
- **Figma:** Herramienta colaborativa que nos permitirá desarrollar wireframes y mockups.
- **Vertabelo:** Plataforma colaborativa que nos permitirá crear nuestro diagrama de base de datos.
- **LucidChart:** Aplicación web destinada a la elaboración de Wireflows, Users Flows y diagramas
de clases.
- **WebStorm:** IDE que utilizaremos para trabajar con javascript y desarrollar la landing page y web
application.

### 5.1.2. Source Code Management
El proyecto seguirá las convenciones de flujo de trabajo establecidas por el modelo GitFlow para el control de versiones, utilizando GitHub como plataforma y sistema de control de versiones. A continuación, se detallará cómo se implementará GitFlow como Workflow de control de versiones, además de proporcionar los URL de los repositorios de GitHub para cada producto: Landing Page, Web Services y Frontend Web Applications.

-  [**Repositorio Landing Page:**](https://github.com/upc-pre-si729-2402-wx51-G6-GPTDevs/Landing-Page)  https://github.com/upc-pre-si729-2402-wx51-G6-GPTDevs/Landing-Page
-  [**Repositorio Web Services:**](https://github.com/upc-pre-si729-2402-wx51-G6-GPTDevs/Web-Services) https://github.com/upc-pre-si729-2402-wx51-G6-GPTDevs/Web-Services
-  [**Repositorio Frontend Web Applications:**](https://github.com/upc-pre-si729-2402-wx51-G6-GPTDevs/Frontend-Web-Applications) https://github.com/upc-pre-si729-2402-wx51-G6-GPTDevs/Frontend-Web-Applications

**GitFlow**

Estructura de branches (Ramas):

**1. Master branch (Rama principal):** Esta rama será considerada como la principal para la aplicación, y contendrá versiones
estables y finales del desarrollo. Solo se permitirán cambios que hayan sido previamente probados y verificados en otras
ramas de prueba.

**2. Develop branch (Rama de desarrollo):** El propósito de esta rama es llevar a cabo los avances del proyecto en equipo y
de mantener los archivos centrales del desarrollo continuo.

**3. Feature branches (Ramas de funcionalidad):** Cada funcionalidad desarrollada por el equipo o separada del enfoque
actual del desarrollo tendrá su propia rama. Una vez que una funcionalidad esté completamente trabajada, se fusionará
con la rama de desarrollo del proyecto. Las convenciones para nombrar las ramas de funcionalidad seguirán un patrón
descriptivo y único, por ejemplo, "feature/nombre-de-la-funcionalidad".

**4. Release branches (Ramas de lanzamiento):** Estas ramas se utilizarán para mantener una instancia de la rama develop
que esté próxima a ser incluida en la rama principal. Se seguirá el sistema de versionamiento semántico (Semantic
Versioning) para nombrar las Releases.

**5. Hotfix branches (Ramas de corrección):** Se crearán para abordar de manera puntual y eficiente la corrección de errores
identificados en la rama principal que afecten significativamente la experiencia de los usuarios.

**Versionamiento Semántico:** Para nombrar las Releases, se aplicará el sistema de versionamiento semántico (Semantic
Versioning 2.0.0).

**Convenciones de Commits:** Para los mensajes de los commits realizados, se utilizará la especificación Conventional Commits
basada en Angular Commit Guidelines. La estructura a seguir será la siguiente:


```bash
git commit -m "<type>[optional scope]:<title>" -m"<description>"
```

### 5.1.3. Source Code Style Guide & Conventions

**HTML:** Algunas de las prácticas que deben de seguirse para alcanzar un código coherente, sostenible y ordenado son las
siguientes:
1. Cerrar todos los elementos HTML. Por ejemplo:
``` html
<p>Esto es un párrafo.</p>
```

2. A pesar de que HTML permite combinar mayúsculas y minúsculas en los nombrs de los elementos y atributos, se limitará
al uso de minúsculas para mantener el orden y garantizar la legibilidad.

3. Utilizar comillas en caso de que los atributos contengan espacios entre sí.

4. Procurar especificar el texto alt y las dimensiones width y height de las imágenes, ya que de esta manera se facilitará la
disponibilidad del contenido. Por ejemplo:
``` html
 <img src="abc.img" alt="image name"
style="width:128px;height:128px">
```

**CSS:** Entre las prácticas empleadas se mencionan:

1. Los nombres de las clases deben de ser breves y autodescriptivos.

2. Separar los nombres de las clases y ID con un guión. Por ejemplo:
```css
#video-id .hero-shadow
```

3. Evitar especificar la unidad de medida luego de usar el valor 0.

4. Separar las declaraciones y selectores en nuevas líneas para agilizar la legibilidad.

**Gherkin:** Es un lenguaje de dominio específico, el cual busca solucionar un problema concreto, la comunicación entre los
negocios y la parte técnica al trabajar con Behavior Driven Development, abreviado por sus siglas en ingles como BBD. En busca
de una buena práctica, se ocuparon los saltos de línea para mejorar el orden de los diversos tipos de escenarios y diferenciarlos
de forma más óptima. Adicionalmente, se utilizaron las palabras clave "Given", "When", "Then" y "And" para estructurar los
escenarios.

### 5.1.4. Software Deployment Configuration

**Landing Page**

Para poder desplegar la Landing Page resulta necesario contar con una serie de requisitos, entre ellos, es necesario contar con
una cuenta personal, una organización y un repositorio al cual cargar los documentos. A partir de lo anterior, es posible
comenzar el despliegue de la landing page. A continuación se enuncian los pasos a seguir:

1. Crear un repositorio para alojar el Landing Page.

2. Asegurarse de que los archivos sigan las nomenclaturas "index.html", para el contenido de la landing page; "style.css" para los estilos. Se tendra una carpeta "assets" y dentro estaran las carpetas "styles" y "img".

3. Cargar los archivos al repositorio mediante un commit.

4. Dirigirse a Settings > Pages y seleccionar la branch correspondiente dentro de la cual se encuentra el proyecto,
generalmente se trata de "main" o "master".

5. Esperar a que GitHub realice las comprobaciones necesarias. Una vez culminado el proceso, se obtendrá un enlace que
llevará al Landing Page desplegado.

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1

| Sprint # | Sprint 1 |
| -------- | -------- |
|**Sprint Planning Background**|
| Date | 2024-09-02|
| Time | 08:00 PM |
| Location | Discord Virtual Meeting |
| Prepared By | Camila Sanchez, Gianfranco Durand |
|Attendees (to planning meeting) | Camila Sanchez, Gianfranco Durand, Daniel Chávarri , Tony Ramos, Jack Roque
| Sprint n – 1 Review Summary | No hubo sprint anterior |
| Sprint n – 1 Retrospective Summary | No hubo sprint anterior |
| **Sprint Goal & User Stories** | 
| Sprint 1 Goal | Realizar la Landing Page |
| Sprint 1 Velocity | 20 |
| Sum of Story Points | 23 | 

#### 5.2.1.2. Sprint Backlog 1

Durante el primer sprint, el equipo tuvo como meta comenzar y concluir la creación de la página de inicio (Landing Page), utilizando Trello para organizar y distribuir las tareas derivadas de las historias de usuario según las competencias de cada integrante. El objetivo clave del sprint fue desarrollar la landing page de manera integral, garantizando tanto su atractivo visual como su funcionalidad.

<div align="center">
<img src="img/TrelloSprint1TB1.png">
</div>

link: [Enlace de trello](https://trello.com/invite/b/671070698574d50e08c7e230/ATTIfd0448052a444c2b7705646e07635cd028FB6849/sprint-1-tb1) https://trello.com/invite/b/671070698574d50e08c7e230/ATTIfd0448052a444c2b7705646e07635cd028FB6849/sprint-1-tb1

| Sprint 1 |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- |
| User Story |     | WorkItem/ Task |     |     |     |     |     |
| Id  | Title | Id  | Title | Description | Estimation(Hours) | Assigned To | Status(To do/ In Process/ To Review/Done) |
| US24 | Sección: Encontrar un trabajo flexible | EP011 | Interfaz de presentación del sitio web. | Sección en el cual el usuario trabajador podrá buscar un trabajo acorde a lo requerido  | 7 hours | Camila Sanchez | Done |
| US25 | Sección: ¿Por qué escoger TaskLinker? | EP011 | Interfaz de presentación del sitio web. | Sección en la cual se presentan datos por la cual el usuario puede escoger nuestra startup | 5 hours | Franco Durand | Done |
| US26 | Sección: Contrata talento temporal | EP011 | Interfaz de presentación del sitio web. | Sección en la cual el empleador podrá buscar trabajadores que coincidan con lo requerido. | 6 hours | Jack Tello | Done |
| US27 | Sección: Encuentra el trabajo ideal para tus proyectos | EP011 | Interfaz de presentación del sitio web. | Sección en la cual se mostrarán recomendaciones para que usted como trabajador, pueda encontrar lo idónea | 8 hours | Franco Durand | Done |
| US28 | Sección: ¿Qué opinan nuestros usuarios? | EP011 | Interfaz de presentación del sitio web. | Sección en donde se mostrarán testimonios de trabajadores o empleadores con respecto al uso | 8 hours | Tony Ramos | Done |
| US29 | Sección: Contáctanos y Footer | EP011 | Interfaz de presentación del sitio web. |Aquí se mostrará la sección para contacto directo con nosostros, y además del footer de lo mas relevante para contacto o información como nuestras redes sociales | 7 hours | Daniel Chávarri | Done |

#### 5.2.1.3. Development Evidence for Sprint Review

En este Sprint 1, el principal enfoque ha sido el desarrollo e implementación de la Landing Page para nuestra startup, TaskLinker. Este avance representa el primer punto de contacto con nuestros usuarios, diseñado para captar la atención de visitantes potenciales y comunicar de manera efectiva nuestra propuesta de valor. Durante este sprint, se realizaron diversos commits en el repositorio del proyecto, los cuales reflejan las tareas completadas y los ajustes realizados para optimizar la presentación visual, la funcionalidad y la experiencia de usuario de la Landing Page. A continuación, se detalla una tabla que muestra los commits relevantes realizados en este sprint.


| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Dated) |
| --- | --- | --- | --- | --- | --- |
| [https://github.com/upc-pre-202401-si729-ws51-eventwear/LandingPage](https://github.com/upc-pre-si729-2402-wx51-G6-GPTDevs/Landing-Page.git) | develop | cbdbf20f93acf052f14249c04a31a477d409b37d | first commit | first commit | 06/09/2024 |
|     |  develop   | 22da688441ef8fc92da4947d90f127952289871b | feat | add globals | 06/09/2024 |
|     |  develop   | 8421a48f7a22443880b411c5801ac01b9786ad61 | feat | update global css | 06/09/2024 |
|     |  feature/testimonials   | 1bf631b6bb65571f23cde29c30e41eb518195507 | feat | update global | 07/09/2024 |
|     |  feature/header-hero   | 0f3ef5c68d997953be0b20387c4a7bdc14aeecaa | feat | add header, hero | 07/09/2024 |
|     |  feature/header-hero   | cb5e69eb3e36f71118f081d151e2a63a624430ce | feat | add styles | 07/09/2024 |
|     |  feature/header-hero   | 4d5a52c1476f8ecb46e4531d6f38b6a4bf8118c6 | feat | add script | 07/09/2024 |
|     |  feature/testimonials   | af8b0b837b273da9e87baf64fac2919c870a594a | Add files via upload | Add files via upload | 07/09/2024 |
|     |  feature/testimonials   | a7121338708570e17368486a891c211278d2cef9 | add | assets | 07/09/2024 |
|     |  feature/testimonials   | 6cbd0340035eb553f6badef31a7fbec9dc9c6c53 | add | index.html | 07/09/2024 |
|     |  develop   | 1d11caedd9d8479052b833c93fe6b1a07b40b499 | feat | add seg1 | 07/09/2024 |
|     |  feature/segment-1   | 4f647b0fbf3d98d99cb4b04b5ff039cde6608d14 | feat | add style | 07/09/2024 |
|     |  develop  | 89f3fdc67935fbdb28ac087c1b4d381007754115 | Merge Branch | 'feature/header-hero' into develop | 07/09/2024 |
|     |  develop  | a11619091b02385eb70ee9bbfa1b9fd79d473023 | Merge Branch | 'feature/segment-1' into develop | 07/09/2024 |
|     |  develop   | 9ac102a1e0a3095a21aa6914b7ae0c17c2cdf953 | Merge Branch | 'feature/testimonials' into develop | 07/09/2024 |
|     |  feature/contact-footer   | 3f7ceb0fc2c9b1d8deb2ebb57fcdec40581fdd0d | Add files via upload | Add files via upload | 07/09/2024 |
|     |  feature/contact-footer   | 06005b42bf3bb76932a91cb30a94b4067d9b64f7 | Add files via upload | Add files via upload | 07/09/2024 |
|     |  feature/contact-footer   | 03fe5f2404c9f3cd0e116585367ec4d980f60c3f | Update | index.html | 07/09/2024 |
|     |  develop   | c75ee84b7108c30369e1558843a29302a41d6824 | Merge Branch | 'feature/contact-footer' into develop | 07/09/2024 |
|     |  feature/segment-2   | e61c6e73974314fe15df3467a64367ec0b618520 |feat: add segment2 | 08/09/2024 |

#### 5.2.1.4. Testing Suite Evidence for Sprint Review

Para el sprint 1 desarrollamos el acceptance test en gherkin de las user stories más importantes que se implementaron en nuestra Landing Page.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Dated) |
| --- | --- | --- | --- | --- | --- |
| [https://github.com/upc-pre-si729-2402-wx51-G6-GPTDevs/acceptance-testing.git](https://github.com/upc-pre-si729-2402-wx51-G6-GPTDevs/acceptance-testing.git) | main | 9e969b3b514bb37875e823719070902950fb04b4 | add | add:create US24 gherkin | 08/09/2024 |
|     |     | 7005982bf59ee9693cf78743f51afd794da40327 | add | add:create US25 gherkin | 08/09/2024 |
|     |     | 7327f3405904f5fe23e1ea62dba90404d4756268 | add | add:create US26 gherkin | 08/09/2024 |
|     |     | 4ab2d1c3221e0348a6dce9e2e1ddb4755b1606db | add | add:create US27 gherkin | 08/09/2024 |
|     |     | 0f8d88d9f5c23b111062a7073b36a759fe229f10 | add | add:create US28 gherkin | 08/09/2024 |
|     |     | 7015a97b16fe0c643579e953eb2f888be2e0e8c7 | add | add:create US29 gherkin | 08/09/2024 |

#### 5.2.1.5. Execution Evidence for Sprint Review

Durante este Sprint, completamos la implementación de la Landing Page de TaskLinker, enfocándonos en un diseño atractivo y responsivo que mejora la experiencia del usuario. A continuación, se muestran capturas de las principales vistas que ilustra la visualización y navegación logradas.

<div align="center">
<img src="img/landing1.png">
</div>

Sección para usuarios que buscan trabajo

<div align="center">
<img src="img/landing2.png">
</div>

<div align="center">
<img src="img/landing3.png">
</div>

Sección para empleadores que buscan trabajadores

<div align="center">
<img src="img/landing4.png">
</div>

<div align="center">
<img src="img/landing5.png">
</div>

Sección sobre comentarios de nuestros usuarios

<div align="center">
<img src="img/landing6.png">
</div>

Sección para contartar con nosotros 

<div align="center">
<img src="img/landing7.png">
</div>

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

No se implementaron servicios en este sprint 1

#### 5.2.1.7. Software Deployment Evidence for Sprint Review
Para realizar el despliegue de la Landing Page se realizaron lo siguientes pasos:

- 1: Hacer merges de las ramas *feature* en la rama *develop* y finalmente merge en la rama *main*

<img src="img/sprint-1-evidencia-1.png"/>

- 2: Ir a la configuración del repositorio, luego a la seccion *Pages* y seleccionar la rama *main* para el despliegue

<img src="img/sprint-1-evidencia-2.png"/>

[Link Landing Page:](https://upc-pre-si729-2402-wx51-g6-gptdevs.github.io/Landing-Page/) https://upc-pre-si729-2402-wx51-g6-gptdevs.github.io/Landing-Page/

#### 5.2.1.8. Team Collaboration Insights during Sprint

<!-- En esta sección, el equipo presenta un resumen de las actividades de implementación realizadas durante el Sprint, destacando la colaboración y el progreso en GitHub. -->

<img src="img/sprint-1-insights-1.png"/>

<img src="img/sprint-1-insights-2.png"/>

<!-- ## Documentation

<div align="center">
<img src="img/colaboration7.png">
</div>

## Landing Page

<div align="center">
<img src="img/colaboration1.png">
</div>

<div align="center">
<img src="img/colaboration2.png">
</div>

<div align="center">
<img src="img/colaboration3.png">
</div>

<div align="center">
<img src="img/colaboration4.png">
</div>

<div align="center">
<img src="img/colaboration5.png">
</div> -->

### 5.2.2. Sprint 2
#### 5.2.2.1. Sprint Planning 2

| Sprint 2 | Sprint 2 |
| -------- | -------- |
|**Sprint Planning Background**|
| Date | 2024-09-25|
| Time | 06:00 PM |
| Location | Discord Virtual Meeting |
| Prepared By | Camila Sanchez, Gianfranco Durand |
|Attendees (to planning meeting) | Camila Sanchez, Gianfranco Durand, Daniel Chávarri , Tony Ramos, Jack Roque
| Sprint n – 2 Review Summary | Durante el segundo sprint, el equipo se enfocó en finalizar la creación de la página de inicio (Landing Page), utilizando Trello para organizar tareas y basándose en las historias de usuario, asegurando su atractivo visual y funcionalidad. |
| Sprint n – 2 Retrospective Summary | Se identificó la necesidad de mejorar la comunicación para abordar dudas más rápidamente y de aumentar la revisión de pruebas antes del despliegue para asegurar la calidad. |
| **Sprint Goal & User Stories** | 
| Sprint 2 Goal | Realizar El Front End |
| Sprint 2 Velocity | 11 |
| Sum of Story Points | 43 Story points | 

#### 5.2.2.2. Sprint Backlog 2

Durante el segundo sprint, el equipo tuvo como meta implementar el frontend de TaskLinker utilizando Node.js, Angular CLI y JSON Server. El enfoque se centró en desarrollar funcionalidades clave en varias páginas. Además, el equipo se enfocó en las historias de usuario relacionadas con este desarrollo, asegurando que cada nueva característica no solo fuera funcional, sino también alineada con las necesidades de los usuarios. Se utilizó Trello para organizar y distribuir las tareas, permitiendo que cada integrante del equipo se especializara en áreas que se correspondían con sus competencias, lo que facilitó un avance eficiente y coordinado hacia el objetivo del sprint.

<div align="center">
<img src="img/TrelloSprint2TP.png">
</div>

link: [Enlace de trello](https://trello.com/invite/b/66dcba9fa4d344f1d0edba45/ATTI3a1423d1b856e4c0a5d2b247b6610d6f7A7492ED/sprint-2-tp) https://trello.com/invite/b/66dcba9fa4d344f1d0edba45/ATTI3a1423d1b856e4c0a5d2b247b6610d6f7A7492ED/sprint-2-tp

| Sprint 2 |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- |
| User Story |     | WorkItem/ Task |     |     |     |     |     |
| Id  | Title | Epic Id  | Title | Description | Estimation(Hours) | Assigned To | Status(To do/ In Process/ To Review/Done) |
| US04 | Acceso a documentos relevantes | EP003 | Gestión y Clasificación de Tareas | Como empleador, quiero poder acceder fácilmente a documentos relevantes, como contratos y evaluaciones previas de trabajadores, para tomar decisiones informadas antes de contratar a un trabajador a través de TaskLinker. | 8 hours | Diego, Camila | Done |
| US05 | Subir y actualizar documentos | EP003 | Gestión y Clasificación de Tareas | Como trabajador, quiero poder subir y actualizar documentos importantes en mi perfil, como certificados de habilidades y documentos de identidad, para que los empleadores puedan evaluar mi idoneidad para los trabajos disponibles. | 7 hours | Diego, Camila | To do |
| US11 | Ver la reputación de los trabajadores | EP010 | Implementación de un Sistema de Reputación. | Como empleador, quiero poder ver las calificaciones y comentarios previos de otros empleadores sobre un trabajador, para asegurarme de que es confiable y competente. | 8 hours | Tony, Camila | Done |
| US13 | Editar perfil de usuario | EP005 | Panel de Usuario Personalizado | Como usuario registrado, quiero poder editar mi perfil para actualizar mi información personal, habilidades y disponibilidad, para que los empleadores tengan datos precisos sobre mí. | 8 hours | Tony | In process |
| US14 | Visualizar y gestionar mis tareas | EP005 | Panel de Usuario Personalizado | Como usuario registrado, quiero poder ver y gestionar las tareas que he aceptado o completado, para hacer seguimiento de mi trabajo y planificar mejor mis actividades. | 8 hours | Diego | Done |
| US16 | Ver perfil detallados de los trabajadores | EP007 | Gestión de Perfiles y Evaluaciones | Como empleador, quiero poder ver perfiles detallados de los trabajadores, incluyendo experiencia, habilidades y evaluaciones previas, para tomar decisiones informadas antes de contratarlos. | 8 hours | Tony | Done |
| US17 | Actualizar mi perfil como trabajador | EP007 | Gestión de Perfiles y Evaluaciones | Como trabajador, quiero poder actualizar mi perfil con nueva información sobre habilidades, experiencia o certificaciones, para atraer más empleadores y mostrar mi crecimiento profesional. | 8 hours | Franco, Camila | In process |
| US20 | Iniciar sesión con autenticación Multifacor activada | EP009 | Implementadón de Autenticación Multifactor | Como usuario, quiero que al iniciar sesión en mi cuenta se me solicite una verificación adicional a través de la autenticación multifactor, para asegurar que solo yo pueda acceder a mi cuenta. | 6 hours | Franco, Camila | Done |
| US22 | Crear una tarea desde cualquier página | EP007 | Gestión de Perfiles y Evaluaciones | Como empleador, quiero poder crear una nueva tarea desde cualquier página de la plataforma, para no tener que navegar hasta un área específica antes de poder crear contenido. | 8 hours | Franco, Camila | Done |
| US30 | Creación de perfil como trabajador | EP007 | Gestión de Perfiles y Evaluaciones | Como trabajador, quiero crear un perfil en la plataforma para poder ofrecer mis servicios y ser contratado por empleadores. | 8 hours | Tony | To do |
| US31 | Creación de perfil como empleador | EP007 | Gestión de Perfiles y Evaluaciones | Como empleador, quiero crear un perfil en la plataforma para poder publicar ofertas de trabajo y contratar trabajadores para tareas específicas o temporales. | 8 hours | Tony | To do |


#### 5.2.2.3. Development Evidence for Sprint Review
| Branch                     | Commit Id | Commit Message                                    | Committed on (Dated) |
|----------------------------|-----------|---------------------------------------------------|----------------------|
| feature/public              | 628c0cb   | feat: add toolbar                                 | 27/09/24             |
| feature/public              | 33dc778   | feat: add fake api                                | 27/09/24             |
| feature/routes              | 91db854   | feat: add route                                   | 27/09/24             |
| feature/routes              | 1cd2215   | feat: add routes                                  | 27/09/24             |
| feature/task                | 59b155f   | feat: add ngif                                    | 27/09/24             |
| feature/task                | 9dc9b48   | Update styles.css                                 | 27/09/24             |
| feature/task                | 9c9f993   | Update index.html                                 | 27/09/24             |
| feature/task                | e84e811   | Update app.routes.ts                              | 27/09/24             |
| feature/task                | 57c6e45   | Update app.config.ts                              | 27/09/24             |
| feature/task                | 7ddb11b   | Update app.component.ts                           | 27/09/24             |
| feature/task                | 24de688   | Update app.component.html                         | 27/09/24             |
| feature/task                | dcf825    | Create publish-task.component.css                 | 27/09/24             |
| feature/task                | 34afb4e   | Create publish-task.component.html                | 27/09/24             |
| feature/task                | 66b02da   | Create publish-task-component.spec.ts             | 27/09/24             |
| feature/task                | 2d8b8c4   | Create publish-task.component.ts                  | 27/09/24             |
| feature/works-done          | dcd3191   | Update styles.css                                 | 27/09/24             |
| feature/works-done          | d48ba8d   | Update app.component.html                         | 27/09/24             |
| feature/works-done          | d87bb55   | Update app.component.ts                           | 27/09/24             |
| feature/works-done          | 4e4da95   | Update app.config.ts                              | 27/09/24             |
| feature/works-done          | d5f6ea0   | Create app.module.ts                              | 27/09/24             |
| feature/works-done          | 7fc19d6   | Update app.routes.ts                              | 27/09/24             |
| feature/works-done          | 9e1d0b7   | Create work-done.component.css                    | 27/09/24             |
| feature/works-done          | ccc87c0   | Create work-done.component.html                   | 27/09/24             |
| feature/works-done          | 36f50e0   | Create work-done.component.spec.ts                | 27/09/24             |
| feature/works-done          | 711f5ce   | Create work-done.component.ts                     | 27/09/24             |
| feature/profiles-dashboard  | 687a8ed   | add: worker-profile, employer-profile & dashboard | 27/09/24             |
| feature/iam                 | 64d9e66   | feat: add login register functionality            | 27/09/24             |
| feature/iam                 | 8477f02   | feat: add auth service                            | 27/09/24             |
| feature/iam                 | 8331bc2   | feat: update user model                           | 27/09/24             |
| feature/iam                 | a461a37   | feat: add user model                              | 27/09/24             |
| feature/iam                 | 7f487a7   | feat: add register component                      | 27/09/24             |
| feature/iam                 | 7dacd14   | feat: add login component                         | 27/09/24             |
| feature/iam                 | fa8c2e2   | feat: update global styles                        | 27/09/24             |


#### 5.2.2.4. Testing Suite Evidence for Sprint Review


#### 5.2.2.5. Execution Evidence for Sprint Review

- Login y register
<img src="img/front1.png">
<img src="img/front2.png">


- Menu principal
<img src="img/front3.png">

- Perfiles
<img src="img/front4.png">
<img src="img/front6.png">

- Historial de trabajos
<img src="img/front5.png">
<img src="img/front7.png">

- Publicar tarea
<img src="img/front8.png">

#### 5.2.2.6. Services Documentation Evidence for Sprint Review
No se implementaron servicios en este sprint 1

#### 5.2.2.7. Software Deployment Evidence for Sprint Review
Para realizar el despliegue del Frontend se realizaron lo siguientes pasos:

- 1: Hacer merges de las ramas *feature* en la rama *develop* y finalmente merge en la rama *main*

<img src="img/sprint-2-evidencia-4.png"/>

- 2: Ir a Netlify, seleccionar *Add new site*, seguidamente seleccionar *Import an existing project* 

<img src="img/sprint-2-evidencia-1.png"/>

- 3: Seleccionar el repositorio del Frontend

<img src="img/sprint-2-evidencia-2.png"/>

- 4: Ingresar un nombre disponible para la página del frontend y seleccionar la rama *main*

<img src="img/sprint-2-evidencia-3.png"/>

[Link Frontend:](https://tasklinker.netlify.app/) https://tasklinker.netlify.app/


#### 5.2.2.8. Team Collaboration Insights during Sprint
<img src="img/sprint2-insights1.png"/>

<img src="img/sprint2-insights2.png"/>

### 5.2.3. Sprint 3
Para este Sprint nos enfocaremos desarrollar una primera version del Web-Services

#### 5.2.3.1. Sprint Planning 3

| Sprint # | Sprint 3 |
| -------- | -------- |
|**Sprint Planning Background**|
| Date | 2024-10-23|
| Time | 08:00 PM |
| Location | Discord Virtual Meeting |
| Prepared By | Camila Sanchez, Gianfranco Durand |
|Attendees (to planning meeting) | Camila Sanchez, Gianfranco Durand, Daniel Chávarri , Tony Ramos, Jack Roque
| Sprint 2 Review Summary | Durante el segundo sprint, el equipo se enfocó en la creación de la primera versión del frontend, utilizando Trello para organizar tareas y basándose en las historias de usuario, asegurando su atractivo visual y funcionalidad. |
| Sprint 2 Retrospective Summary | Se identificó la necesidad de mejorar la comunicación para abordar dudas más rápidamente y de aumentar la revisión de pruebas antes del despliegue para asegurar la calidad. |
| **Sprint Goal & User Stories** | 
| Sprint 3 Goal | 	Desplegar la primera versión de Web Services. |
| Sprint 3 Velocity | 11 |
| Sum of Story Points | 43 Story points | 

#### 5.2.3.2. Sprint Backlog 3

En este Sprint 3, trabajaremos en los servicios clave del backend, incluyendo la autenticación para el acceso seguro, la creación y edición de perfiles de trabajadores y empleadores, la funcionalidad para que los empleadores puedan publicar ofertas de trabajo, y el sistema de notificaciones que enviará alertas importantes por correo y mensajería interna. Estos elementos asegurarán que la plataforma ofrezca una experiencia fluida y conecte eficazmente a todos los usuarios.

<div align="center">
<img src="img/Sprint 3.png">
</div>

link: [Enlace de trello](https://trello.com/b/b8PH3hVt/sprint-3-tb2) https://trello.com/b/b8PH3hVt/sprint-3-tb2

| Sprint 3 |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- |
| User Story |     | WorkItem/ Task |     |     |     |     |     |
| Id  | Title | Epic Id  | Title | Description | Estimation(Hours) | Assigned To | Status(To do/ In Process/ To Review/Done) |
| US011 | Ver la reputación de los trabajadores | EP010 | Gestión y Clasificación de Tareas | Como empleador, quiero poder ver las calificaciones y comentarios previos de otros empleadores sobre un trabajador antes de contratarlo, para asegurarme de que es confiable y competente. | 8 hours | Diego, Camila | Done |
| US12 | Actualizar la reputación de los trabajadores | EP010 | Gestión y Clasificación de Tareas | Como trabajador, quiero que mi reputación en la plataforma se actualice automáticamente con cada evaluación recibida, para reflejar de manera precisa mi desempeño a lo largo del tiempo | 7 hours | Tony | Done |
| US05 | Subir y actualizar documentos| EP03 | Implementación de un Sistema de Reputación. | Como trabajador, quiero poder subir y actualizar documentos importantes en mi perfil, como certificados de habilidades y documentos de identidad, para que los empleadores puedan evaluar mi idoneidad para los trabajos disponibles. | 8 hours | Tony, Camila | Done |
| US13 | Editar perfil de usuario | EP005 | Panel de Usuario Personalizado | Como usuario registrado, quiero poder editar mi perfil para actualizar mi información personal, habilidades y disponibilidad, para que los empleadores tengan datos precisos sobre mí. | 8 hours | Tony | In process |
| US14 | Visualizar y gestionar mis tareas | EP005 | Panel de Usuario Personalizado	 | Como usuario registrado, quiero poder ver y gestionar las tareas que he aceptado o completado, para hacer seguimiento de mi trabajo y planificar mejor mis actividades. | 8 hours | Camila | In process |
| US15 | Recibir notificaciones de nuevas oportunidades de trabajo | EP006 | Panel de Usuario Personalizado | Como trabajador, quiero recibir notificaciones automáticas cuando se publiquen nuevas oportunidades de trabajo que coincidan con mis preferencias, para poder aplicar rápidamente a tareas relevantes. | 8 hours | Diego | Done |
| US16 | Ver perfil detallados de los trabajadores | EP007 | Gestión de Perfiles y Evaluaciones | Como empleador, quiero poder ver perfiles detallados de los trabajadores, incluyendo experiencia, habilidades y evaluaciones previas, para tomar decisiones informadas antes de contratarlos. | 8 hours | Tony | Done |
| US17 | Actualizar mi perfil como trabajador | EP007 | Gestión de Perfiles y Evaluaciones | Como trabajador, quiero poder actualizar mi perfil con nueva información sobre habilidades, experiencia o certificaciones, para atraer más empleadores y mostrar mi crecimiento profesional. | 8 hours | Franco, Camila | In process |
| US20 | Iniciar sesión con autenticación multifactor activada | EP009 | Implementadón de Autenticación Multifactor		| Como usuario, quiero que al iniciar sesión en mi cuenta, se me solicite una verificación adicional a través de la autenticación multifactor, para asegurar que solo yo pueda acceder a mi cuenta. | 8 hours | Franco | In process |
| US21 | Evaluar a los trabajadores después de un trabajo | EP007 | Gestión de Perfiles y Evaluaciones	| Como empleador, quiero evaluar a los trabajadores una vez que terminen un trabajo, para que pueda contribuir a la reputación y ayudar a otros empleadores a elegir a los mejores candidatos. | 8 hours | Camila | In process |
| US30 | Creación de perfil como trabajador | EP007 | Gestión de Perfiles y Evaluaciones | Como trabajador, quiero crear un perfil en la plataforma para poder ofrecer mis servicios y ser contratado por empleadores. | 8 hours | Franco, Camila | Done |
| US31 | Creación de perfil como empleador | EP007 | Gestión de Perfiles y Evaluaciones | Como empleador, quiero crear un perfil en la plataforma para poder publicar ofertas de trabajo y contratar trabajadores para tareas específicas o temporales. | 8 hours | Franco, Camila | Done |
| US32 | Ver perfil detallado de los empleadores | EP005 | Panel de Usuario Personalizado | Como empleador, quiero poder actualizar mi perfil en la plataforma para reflejar cambios en los datos de la compañía, detalles de contacto, método de pago, rango salarial y número de teléfono, asegurando que la información sea precisa y esté actualizada para atraer a trabajadores potenciales. | 8 hours | Tony | Done |
| US33 | Creación de perfil como empleador | EP005 | Panel de Usuario Personalizado	 | Como empleador, quiero crear un perfil en la plataforma para poder publicar ofertas de trabajo y contratar trabajadores para tareas específicas o temporales. | 8 hours | Tony | Done |

#### 5.2.3.3. Development Evidence for Sprint Review

| Branch | Commit Id | Commit Message                       | Committed on (Dated) |
|--------|-----------|--------------------------------------|-----------------------|
| feature/iam   | 875c43d   | feat: add authentication controller, resources, transforms | 25/10/24             |
| feature/iam   | ed5db1e   | feat: add user command query service and implementatio  | 25/10/24             |
| feature/iam   | e9ebefd   | feat: add user repository                               | 25/10/24             |
| feature/iam   | e48c722   | feat: add getUserByEmail query                          | 25/10/24             |
| feature/iam   | 83ef41a   | feat: add sign in sign up commands                      | 25/10/24             |
| feature/iam   | bafa219   | feat: add user model, paymentcard entity, phonenumber value object | 25/10/24             |
| feature/jobPostBC      | e225f4b   | feat: add infrastructure                | 02/11/24             |
| feature/jobPostBC      | b4e97b5   | feat: add domain model and services     | 02/11/24             |
| feature/jobPostBC      | a222da1   | chore: jobPost                          | 25/10/24             |
| feature/jobPostBC      | 702acf9   | chore: jobpost                          | 25/10/24             |
| feature/notificationBC    | 124383d   | Chore: (TasklinkerApplicationTests.java)     | 18/10/24             |
| feature/notificationBC    | 9632251   | Chore: (application.properties)              | 18/10/24             |
| feature/notificationBC    | 43b6397   | Chore: (TasklinkerApplication.java)          | 18/10/24             |
| feature/notificationBC    | 743e5c6   | Chore: (NotificationService.java)            | 18/10/24             |
| feature/notificationBC    | b48e366   | Chore: (NotificationRepository.java)         | 18/10/24             |
| feature/notificationBC    | 062790a   | Chore: (Notification.java)                   | 18/10/24             |
| feature/notificationBC    | 0c2fd67   | Chore:(NotificationController.java)          | 18/10/24             |
| feature/notificationBC    | dca090e   | Chore: (pom.xml)                             | 18/10/24             |
| feature/profileCreateBC  | 9b5c63e   | chore: profile create bounded context added   | 21/10/24             |
| feature/shared | eba6185   | feat: add snake case naming          | 22/10/24             |
| feature/shared | 3db1b41   | feat: add auditable aggregate, model | 22/10/24             |


#### 5.2.3.4. Testing Suite Evidence for Sprint Review

#### 5.2.3.5. Execution Evidence for Sprint Review
La realización de estas tareas refleja un enfoque estructurado para el desarrollo de la aplicación web. Cada tarea aborda un componente crucial del producto, lo que asegura que se cubran tanto aspectos visuales como funcionales. Este enfoque modular permite no solo mantener un orden en el proceso de desarrollo, sino también garantizar que cada sección cumple con las funcionalidades.  
Para la presente entrega, enfatizamos nuestro enfoque en los Web Services o Back-end de nuestro sitio web, logramos definir y ejecutar satisfactoriamente varios endpoints de nuestros bounded contexts, pero a continucación se proporcionará algunas evidencias de ejecución del servicio de los bounded contexts mas relevantes.

##### Bounded Context Profiles

##### Notifications 

POST
<img src="img/webservicenotification.png"/>

<img src="img/webservicenotification1.png"/>

GET
<img src="img/webservicenotification2.png"/>

##### Worker Profile

POST
<img src="img/webserviceworker.png"/>

<img src="img/webserviceworker2.png"/>

GET
<img src="img/webserviceworker3.png"/>

GET BY ID

<img src="img/webserviceworker4.png"/>

DELETE

<img src="img/webserviceworker5.png"/>


##### Employer Profile

POST
<img src="img/webserviceemployer.png"/>

<img src="img/webserviceemployer2.png"/>

GET
<img src="img/webserviceemployer3.png"/>

#### 5.2.3.6. Service Documentation Evidence for Sprint Review

En esta sección, se destacarán los principales endpoints de los bounded context , detallando sus funcionalidades y cómo respaldan las operaciones esenciales del servicio. Se describirá el propósito y la utilidad de cada endpoint, enfocándose en acciones como la creación, consulta, actualización y eliminación de perfiles de trabajadores y empleadores. Por otra parte, con respecto a la utilidad del bounded context Notifications, la creación y consulta requerida.

##### Notification

| Endpoint Route                 | Action                              | HTTP Verb | Required Parameters                               | Call Example | Response |
|--------------------------------|-------------------------------------|-----------|---------------------------------------------------|--------------|----------|
| `/api/notifications` |  Create a new notification  |     POST      |   `email` string required,  `message` string required                |    `POST /api/notifications` with JSON body        |  `200 OK`     |
| `/api/notifications` |  Get all notifications      |     GET       |                None                    |    `GET /api/notifications`           |     `200 OK`     |


##### Worker

| Endpoint Route               | Action                            | HTTP Verb | Required Parameters                          | Call Example                                                                                                                                       | Response                                                                                                                                                                       |
|------------------------------|-----------------------------------|-----------|----------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `/api/v1/workerProfile`      | Create a new worker profile      | POST      | `CreateWorkerResource` in the request body   | `POST /api/v1/workerProfile` with JSON body                | `201 Created` with `WorkerResource` JSON body if successful                                                                                |
| `/api/v1/workerProfile/{id}` | Get a worker profile by ID       | GET       | `id` as path variable                       | `GET /api/v1/workerProfile/1`                                                                                                                     | `200 OK` with `WorkerResource` JSON body if found                                                                                         |
| `/api/v1/workerProfile`      | Get all worker profiles          | GET       | None                                         | `GET /api/v1/workerProfile`                                                                                                                       | `200 OK` with array of `WorkerResource` JSON objects if profiles exist                                                                    |
| `/api/v1/workerProfile/{id}` | Update a worker profile by ID    | PUT       | `id` as path variable, `UpdateWorkerByIdCommand` in the request body | `PUT /api/v1/workerProfile/1` with JSON body | `200 OK` with updated `Worker` JSON object if successful                                                               |
| `/api/v1/workerProfile/{id}` | Delete a worker profile by ID    | DELETE    | `id` as path variable                       | `DELETE /api/v1/workerProfile/1`                                                                                                                  | `200 OK` if deleted successfully                                                                                  |

##### Employer

| Endpoint Route                 | Action                              | HTTP Verb | Required Parameters                               | Call Example                                                                                                                                                                      | Response                                                                                                                                                                                       |
|--------------------------------|-------------------------------------|-----------|---------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `/api/v1/employerProfile`      | Create a new employer profile       | POST      | `CreateEmployerResource` in the request body      | `POST /api/v1/employerProfile` with JSON body                                                     | `201 Created` with `EmployerResource` JSON body if successful                                                                                           |
| `/api/v1/employerProfile/{id}` | Get an employer profile by ID       | GET       | `id` as path variable                             | `GET /api/v1/employerProfile/1`                                                                                                                                                   | `200 OK` with `EmployerResource` JSON body if found                                                                                                           |
| `/api/v1/employerProfile`      | Get all employer profiles           | GET       | None                                              | `GET /api/v1/employerProfile`                                                                                                                                                     | `200 OK` with an array of `EmployerResource` JSON objects if profiles exist                                                                             |
| `/api/v1/employerProfile/{id}` | Update an employer profile by ID    | PUT       | `id` as path variable, `UpdateEmployerByIdCommand` in the request body | `PUT /api/v1/employerProfile/1` with JSON body                | `200 OK` with updated `Employer` JSON object if successful                                                                            |
| `/api/v1/employerProfile/{id}` | Delete an employer profile by ID    | DELETE    | `id` as path variable                             | `DELETE /api/v1/employerProfile/1`                                                                                                                                                 | `200 OK` if deleted successfully                                                                                                         |


#### 5.2.3.7. Software Deployment Evidence for Sprint Review
Durante este sprint, se utilizó Azure como plataforma de despliegue para la aplicación web.

- 1. Crear un recurso de *Azure App Service*

<img src="img/sprint-3-evidencia-1.png"/>

- 2. Escoger el entorno de **Java 21** y configurar un nombre para el dominio

<img src="img/sprint-3-evidencia-2.png"/>

- 3. Actualizar la conexión a la base de datos

<img src="img/sprint-3-evidencia-3.png"/>

- 4. En el menú del recurso de Azure seleccionar *Deploy to Web App* 

<img src="img/sprint-3-evidencia-4.png"/>

<img src="img/sprint-3-evidencia-5.png"/>

- 4. Verificar el funcionamiento de Swagger en el dominio del App Service

<img src="img/sprint-3-evidencia-6.png"/>

[Link:](https://tasklinker.azurewebsites.net/swagger-ui/index.html) https://tasklinker.azurewebsites.net/swagger-ui/index.html

#### 5.2.3.8. Team Collaboration Insights during Sprint
<img src="./img/sprint3-insights7.png"/>

### 5.2.4. Sprint 4
#### 5.2.4.1. Sprint Planning 4
| Sprint # | Sprint 4 |
| -------- | -------- |
|**Sprint Planning Background**|
| Date | 2024-10-23|
| Time | 08:00 PM |
| Location | Discord Virtual Meeting |
| Prepared By | Camila Sanchez, Gianfranco Durand |
|Attendees (to planning meeting) | Camila Sanchez, Gianfranco Durand, Daniel Chávarri , Tony Ramos, Jack Roque
| Sprint 2 Review Summary | Durante el segundo sprint, el equipo se enfocó en la creación de la primera versión del frontend, utilizando Trello para organizar tareas y basándose en las historias de usuario, asegurando su atractivo visual y funcionalidad. |
| Sprint 2 Retrospective Summary | Se identificó la necesidad de mejorar la comunicación para abordar dudas más rápidamente y de aumentar la revisión de pruebas antes del despliegue para asegurar la calidad. |
| **Sprint Goal & User Stories** | 
| Sprint 3 Goal | 	Desplegar la primera versión de Web Services. |
| Sprint 3 Velocity | 11 |
| Sum of Story Points | 43 Story points | 

#### 5.2.4.2. Sprint Backlog 4

<div align="center">
<img src="img/Sprint 3.png">
</div>

link: [Enlace de trello](https://trello.com/b/b8PH3hVt/sprint-3-tb2) https://trello.com/b/b8PH3hVt/sprint-3-tb2

| Sprint 4 |     |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | --- | --- |
| User Story |     | WorkItem/ Task |     |     |     |     |     |
| Id  | Title | Epic Id  | Title | Description | Estimation(Hours) | Assigned To | Status(To do/ In Process/ To Review/Done) |
| US011 | Ver la reputación de los trabajadores | EP010 | Gestión y Clasificación de Tareas | Como empleador, quiero poder ver las calificaciones y comentarios previos de otros empleadores sobre un trabajador antes de contratarlo, para asegurarme de que es confiable y competente. | 8 hours | Diego, Camila | Done |
| US12 | Actualizar la reputación de los trabajadores | EP010 | Gestión y Clasificación de Tareas | Como trabajador, quiero que mi reputación en la plataforma se actualice automáticamente con cada evaluación recibida, para reflejar de manera precisa mi desempeño a lo largo del tiempo | 7 hours | Tony | Done |
| US05 | Subir y actualizar documentos| EP03 | Implementación de un Sistema de Reputación. | Como trabajador, quiero poder subir y actualizar documentos importantes en mi perfil, como certificados de habilidades y documentos de identidad, para que los empleadores puedan evaluar mi idoneidad para los trabajos disponibles. | 8 hours | Tony, Camila | Done |
| US13 | Editar perfil de usuario | EP005 | Panel de Usuario Personalizado | Como usuario registrado, quiero poder editar mi perfil para actualizar mi información personal, habilidades y disponibilidad, para que los empleadores tengan datos precisos sobre mí. | 8 hours | Tony | In process |
| US14 | Visualizar y gestionar mis tareas | EP005 | Panel de Usuario Personalizado	 | Como usuario registrado, quiero poder ver y gestionar las tareas que he aceptado o completado, para hacer seguimiento de mi trabajo y planificar mejor mis actividades. | 8 hours | Camila | In process |
| US15 | Recibir notificaciones de nuevas oportunidades de trabajo | EP006 | Panel de Usuario Personalizado | Como trabajador, quiero recibir notificaciones automáticas cuando se publiquen nuevas oportunidades de trabajo que coincidan con mis preferencias, para poder aplicar rápidamente a tareas relevantes. | 8 hours | Diego | Done |
| US16 | Ver perfil detallados de los trabajadores | EP007 | Gestión de Perfiles y Evaluaciones | Como empleador, quiero poder ver perfiles detallados de los trabajadores, incluyendo experiencia, habilidades y evaluaciones previas, para tomar decisiones informadas antes de contratarlos. | 8 hours | Tony | Done |
| US17 | Actualizar mi perfil como trabajador | EP007 | Gestión de Perfiles y Evaluaciones | Como trabajador, quiero poder actualizar mi perfil con nueva información sobre habilidades, experiencia o certificaciones, para atraer más empleadores y mostrar mi crecimiento profesional. | 8 hours | Franco, Camila | In process |
| US20 | Iniciar sesión con autenticación multifactor activada | EP009 | Implementadón de Autenticación Multifactor		| Como usuario, quiero que al iniciar sesión en mi cuenta, se me solicite una verificación adicional a través de la autenticación multifactor, para asegurar que solo yo pueda acceder a mi cuenta. | 8 hours | Franco | In process |
| US21 | Evaluar a los trabajadores después de un trabajo | EP007 | Gestión de Perfiles y Evaluaciones	| Como empleador, quiero evaluar a los trabajadores una vez que terminen un trabajo, para que pueda contribuir a la reputación y ayudar a otros empleadores a elegir a los mejores candidatos. | 8 hours | Camila | In process |
| US30 | Creación de perfil como trabajador | EP007 | Gestión de Perfiles y Evaluaciones | Como trabajador, quiero crear un perfil en la plataforma para poder ofrecer mis servicios y ser contratado por empleadores. | 8 hours | Franco, Camila | Done |
| US31 | Creación de perfil como empleador | EP007 | Gestión de Perfiles y Evaluaciones | Como empleador, quiero crear un perfil en la plataforma para poder publicar ofertas de trabajo y contratar trabajadores para tareas específicas o temporales. | 8 hours | Franco, Camila | Done |
| US32 | Ver perfil detallado de los empleadores | EP005 | Panel de Usuario Personalizado | Como empleador, quiero poder actualizar mi perfil en la plataforma para reflejar cambios en los datos de la compañía, detalles de contacto, método de pago, rango salarial y número de teléfono, asegurando que la información sea precisa y esté actualizada para atraer a trabajadores potenciales. | 8 hours | Tony | Done |
| US33 | Creación de perfil como empleador | EP005 | Panel de Usuario Personalizado	 | Como empleador, quiero crear un perfil en la plataforma para poder publicar ofertas de trabajo y contratar trabajadores para tareas específicas o temporales. | 8 hours | Tony | Done |


#### 5.2.4.3. Development Evidence for Sprint Review

#### 5.2.4.4. Testing Suite Evidence for Sprint Review

#### 5.2.4.5. Execution Evidence for Sprint Review

#### 5.2.4.6. Services Documentation Evidence for Sprint Review

#### 5.2.4.7. Software Deployment Evidence for Sprint Review

#### 5.2.4.8. Team Collaboration Insights during Sprint



## 5.3. Validation Interviews
En esta sección de nuestro proyecto, nos enfocamos en detectar cuáles son los puntos de mejora de nuestro sitio web para lograr un mayor compromiso con Tasklinker. Esta fase crucial del proyecto implica un diálogo directo con nuestros principales usuarios para recopilar sus opiniones y sugerencias a través de entrevistas.

### 5.3.1. Diseño de Entrevistas
Se decribe la metodología utilizada para diseñar las entrevistas de validación, incluyendo la selección de participantes, la formulación de preguntas y el enfoque adaptaddo para obtener información relevante y precisa sobre la experiencia del usuario con la aplicación Tasklinker:

**Sitio web**

User Goal: Registrar
User persona: Trabajador o Empleador
Explicación del flujo: El usuario accederá a la aplicación y podrá remitir a la aplicación la información necesaria para crear una cuenta. Luego de crear su cuenta le redirigira para registrar su método de pago. Una vez que el proceso de pago es completado exitosamente, se notifica al usuario con un mensaje confirmando el vinculo de su tarjeta con la plataforma

User Goal: Iniciar sesión
User persona: Trabajador o Empleador
Explicación del flujo: El usuario accederá a la aplicación e introducirá su nombre de usuario y contraseña en el formulario de inicio de sesión. Si las credenciales son correctas, el usuario será dirigido al dashboard. En caso contrario, se le solicitará que reintroduzca sus datos.

User Goal: Perfil
User persona: Trabajador o Empleador
Explicación del flujo: Después de iniciar sesión, el usuario podrá dirigirse a la sección Perfil para editar datos personales o la opción de permitir al usuario cambiar de cuenta a una de empleador y utilizar las herramientas de este por la plataforma. 

User Goal: Navegar por el dashboard
User persona: Trabajador o Empleador
Explicación del flujo: Después de iniciar sesión, el usuario será dirigido al dashboard, donde podrá visualizar las últimas tareas publicadas, el botón para publicar, filtros y un panel de su perfil con la sección "Configuración".

### 5.3.2. Registro de Entrevistas


<!DOCTYPE html>
<html lang="es">
<head>
    <meta name="viewport" content="initial-scale=1.0">
    <style>
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
    </style>
</head>
<body>
<table>
    <thead>
        <tr>
            <th>Sección</th>
            <th>Características del video</th>
            <th>Sobre el contenido</th>
            <th>Integración y entrega</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Validation Interviews</td>
            <td>Formato: mp4
            <br>Duración: 3:31 min</br></td>
            <td>Entrevistado(a) #1: Sebastian Silva 
            <br>Sexo: Hombre
            <br>Edad: 20 años
            <br>Segmento Objetivo: Trabajador  
            <br> Distrito: San Luis </td>
            <td>Screenshot:
            <br> Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210973_upc_edu_pe/Eev7_47SUiZLrBtQ2tE7g3gBOPKTyZ0-0ZzaxTxT4rUDHw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=uEBO4s  </td>
        </tr>
        <tr>
            <td>Validation Interviews</td>
            <td>Formato: mp4
            <br>Duración:  min</br></td>
            <td>Entrevistado(a) #2:
            <br>Sexo:
            <br>Edad: años
            <br>Segmento Objetivo:   
            <br> Distrito: </td>
            <td>Screenshot:
            <br> Link: </td>
        </tr>
        <tr>
            <td>Validation Interviews</td>
            <td>Formato: mp4
            <br>Duración:  min</br></td>
            <td>Entrevistado(a) #3:
            <br>Sexo:
            <br>Edad: años
            <br>Segmento Objetivo:   
            <br> Distrito: </td>
            <td>Screenshot:
            <br> Link: </td>
        </tr>
    </tbody>
</table>

</body>
</html>

### 5.3.3. Evaluaciones según heurísticas
Aquí se explican las evaluaciones realizadas utilizando principios heurísticos de usabilidad. Se analizan los resultados obtenidos y se identifican áreas de mejora en la interfaz y la funcionalidad de la aplicación, con el fin de optimizar la experiencia del usuario y asegurar la eficacia del producto.

Site o App a Evaluar: Tasklinker

Tareas a Evaluar: 

1. Iniciar sesión
2. Crear cuenta
3. Cargar tarjeta
4. Mi perfil
5. Subir Archivos
6. Trabajos realizados
7. Historial de trabajos Publicados
8. Panel de control (Dashboard)
9. Aplicación de Filtro
10. Botón Publicar Tarea
11. Postulantes
12. Finalizar Tarea

**Escala de Severidad:** 

Los errores serán puntiados tomando en cuenta la siguiente escala de severidad.

| Nivel | Descripción |
|-------|-------------|
|   1   | Problema superficial: puede ser fácilmente superado por el usuario ó ocurre con muy poco frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo. |
|   2   | Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja de cara resolverlo al siguiente release. |
|   3   | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta. |
|   4   | Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento. |

**Tabla de Resumen:** 

| # | Problema | Escala de Severidad | Heurística/Principio violada(o) |
|---|----------|---------------------|---------------------|
| 1 |  |  |  |
| 2 |  |  |  |
| 3 |  |  |  |

----
<br>

**Descripción del Problemas:**

- **Problema #1:**
- **Severidad:** 
- **Heurística/Principio violado(a):** 
- **Problema:** 
- **Recomendación:** 

---

- **Problema #2:**
- **Severidad:** 
- **Heurística/Principio violado(a):** 
- **Problema:** 
- **Recomendación:** 

---

- **Problema #3:**
- **Severidad:** 
- **Heurística/Principio violado(a):** 
- **Problema:** 
- **Recomendación:** 
<br>

# 5.4. Video About-the-Product
En esta sección se presenta un video explicatiovo sobre la aplicación Tasklinker. El video destaca las principales características y beneficios del producto, demostrando cómo satisface las necesidad de los clientes. Este recurso visual es esencial para comunicar de manera efectiva el valor de la apliación a potenciales usuarios e inversores.

Enlace al Video About-The-Product: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f640_upc_edu_pe/EfFCppV64GFPupXAacw9P0QBWOfH66q39wxBOzVWZzEUFg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=fzwv4u 

# Conclusiones
## Conclusiones y recomendaciones

Conclusiones

TaskLinker aborda una brecha significativa en el mercado laboral peruano, donde existe una creciente demanda de trabajos temporales y por horas. Actualmente, tanto los trabajadores como los empleadores enfrentan dificultades para conectarse de manera eficiente, lo que resulta en una subutilización de talento y procesos de contratación ineficientes.

La plataforma se adapta a un amplio segmento de la población, como estudiantes, amas de casa, jubilados y personas con empleos parciales, quienes valoran la flexibilidad laboral que ofrece TaskLinker. Esta flexibilidad es clave en un mercado laboral que busca adaptarse a diferentes estilos de vida y necesidades.

TaskLinker resuelve la desconexión existente entre oferta y demanda de empleo temporal mediante una plataforma centralizada, fácil de usar, que permite a los trabajadores encontrar oportunidades laborales y a los empleadores contratar personal de manera rápida y eficiente.

La plataforma tiene el potencial de convertirse en la líder del mercado en Perú para trabajos por horas, mejorando tanto la eficiencia de contratación como la satisfacción de trabajadores y empleadores.

TaskLinker ofrece un modelo de negocio flexible, con una opción gratuita que incluye comisiones por transacción y un plan premium que elimina estas comisiones y ofrece beneficios adicionales. Esto facilita el acceso de usuarios con diferentes necesidades económicas y volúmenes de trabajo.

Recomendaciones

Implementar y promocionar un sistema de evaluaciones y reseñas confiable que genere confianza tanto en empleadores como en trabajadores. Esto mejorará la transparencia y fomentará más transacciones exitosas en la plataforma.

Simplificar aún más el proceso de registro para atraer a más usuarios. Se recomienda medir la tasa de conversión y establecer metas claras para aumentar el número de inscripciones de trabajadores y empleadores.

Considerar la expansión de TaskLinker a nuevas regiones dentro de Perú, particularmente en zonas urbanas donde la demanda de trabajos temporales es alta. Campañas de marketing dirigidas a estas áreas ayudarán a incrementar la base de usuarios.

Para maximizar la eficiencia tanto para empleadores como para trabajadores, se recomienda mejorar las opciones de búsqueda y filtrado en la plataforma, permitiendo que ambos grupos encuentren rápidamente las oportunidades o perfiles adecuados.

Además de enfocarse en PyMEs y particulares, TaskLinker podría explorar alianzas con grandes empresas o instituciones que también puedan necesitar trabajadores temporales para proyectos específicos o eventos.

Es crucial realizar un seguimiento del impacto del modelo de comisiones y el plan premium para asegurar que las tarifas no representen una barrera para la participación. Ajustar el modelo en función del volumen de transacciones y el feedback de los usuarios puede ser clave para optimizar el crecimiento de la plataforma.

Incluir un sistema de notificaciones que informe a los trabajadores sobre oportunidades relevantes para sus habilidades y preferencias, aumentando su participación y el número de trabajos completados.

## Video About-the-Team.
<table>
    <thead>
        <tr>
            <th>Sección</th>
            <th>Características del video</th>
            <th>Sobre el contenido</th>
            <th>Integración y entrega</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>About The Team</td>
            <td>Formato: mp4
            <br>Duración: 7:18 min</br></td>
            <td>Video relacionado acerca de los integrantes del equipo, el desarrollo de cada integrante y sus conclusiones acerca del proyecto realizado. </td>
            <td> Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f640_upc_edu_pe/ESjaBnEaSv9KsApVAYRPQHUBDehk1yp3t77m_GzyR9l2SQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=KhH4LN </td>
        </tr>
    </tbody>
</table>

</body>
</html>

# Bibliografía

MetLife México. (s. f.). Formas de generar ingresos adicionales. MetLife. 
(https://www.metlife.com.mx/blog/bienestar-financiero/formas-de-generar-ingresos-adicionales/)

Universidad San Ignacio de Loyola. (2022, 28 marzo). Formas de contratación de personal de una empresa. Blog USIL Facultad de Ciencias Empresariales. (https://blogs.usil.edu.pe/facultad-ciencias-empresariales/ciencias-empresariales/formas-de-contratacion-de-personal-de-una-empresa)

Shiftbase. (s. f.). Contrato temporal. Shiftbase. (https://www.shiftbase.com/es/glosario/contrato-temporal)

# Anexos

**Anexo 1:**

[Link Frontend:](https://tasklinker.netlify.app/) https://tasklinker.netlify.app/

**Anexo 2:**

[Link Backend:](https://tasklinker.azurewebsites.net/swagger-ui/index.html) https://tasklinker.azurewebsites.net/swagger-ui/index.html

[About The Product:](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f640_upc_edu_pe/EfFCppV64GFPupXAacw9P0QBWOfH66q39wxBOzVWZzEUFg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=fzwv4u) https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f640_upc_edu_pe/EfFCppV64GFPupXAacw9P0QBWOfH66q39wxBOzVWZzEUFg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=fzwv4u

[About The Team:](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f640_upc_edu_pe/ESjaBnEaSv9KsApVAYRPQHUBDehk1yp3t77m_GzyR9l2SQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=KhH4LN) https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f640_upc_edu_pe/ESjaBnEaSv9KsApVAYRPQHUBDehk1yp3t77m_GzyR9l2SQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=KhH4LN