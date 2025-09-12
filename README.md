<div align="center">

<h1>Informe del Trabajo Final</h1>
<h2>Universidad Peruana de Ciencias Aplicadas</h2>
<img src="./assets/Logo-UPC.png" alt="Logo UPC" width="200">
<h4>Ingeniería de Software</h4>
<h4>Desarrollo de Aplicaciones Open Source</h4>
<h4>1ASI0729-2520-7394</h4>
<h4>Docente: Hugo Allan Mori Paiva</h4>
<h4>Startup: InventaTech</h4>
<h4>Producto: InventaTrack</h4>

## Team memebers:

|                Nombre                |   Código   |
| :----------------------------------: | :--------: |
| Gonzalo Alonso Carhuancote Dominguez | U202210720 |
|   Juan Carlos Alvarado de la Cruz    | U202216150 |
|    Joan Fernando Teves Samaniego     | U202117303 |
|      Antonio Rodrigo Duran Díaz      | U202215721 |
|     Daiki Oscar Oshiro Yamashita     | U20201f846 |

<h4>Ciclo 2025-02</h4>
</div>

<div>
  
## Registro de Versiones del Informe

| Versión | Fecha      | Autor                                                                                                                                                                                      | Descripción de modificación                                                                                                                  |
| ------- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------- |
| **TB1** | 15/09/2025 | Gonzalo Alonso Carhuancote Dominguez <br><br> Juan Carlos Alvarado de la Cruz <br><br> Joan Fernando Teves Samaniego<br><br>Antonio Rodrigo Duran Díaz<br><br>Daiki Oscar Oshiro Yamashita | Para esta primera entrega, realizamos los primeros 5 capítulos del informe y desarrollamos la primera versión del landing page del Producto. |

</div>

## Project Report Collaboration Insights

<div>
<p>Para este informe se ha dividido de la siguiente forma para cada integrante del grupo:</p>
</div>
  
  ## 
  
  |  Integrantes   | Tarea asignada |
  |:--------------:|:--------------:|
  | Gonzalo Carhuancote | U202210720   |
# Contenido

## Índice

- [Capítulo I: Introducción]()
    - [1.1. StartUp Profile](#11-startup-profile)
        - [1.1.1. Descripción de la StartUp](#111-descripción-de-la-startup)
        - [1.1.2. Perfiles de Integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2. Solution Profile](#12-solution-profile)
        - [1.2.1. Antecedentes y Problemática](#121-antecedentes-y-problemática)
        - [1.2.2. Lean UX Process](#122-lean-ux-process)
            - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
            - [1.2.2.3. Lean UX Hyphotesis Statements](#1223-lean-ux-hyphotesis-statements)
            - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis]()
    - [2.1. Competidores](#21-competidores)
        - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
        - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
    - [2.2. Entrevistas](#22-entrevistas)
        - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
        - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
        - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
    - [2.3. Needfinding](#23-needfinding)
        - [2.3.1. User Persona](#231-user-persona)
        - [2.3.2. User Task Matrix](#232-user-task-matrix)
        - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
        - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.4 Big Picture Event Storming](#24-big-picture-event-storming)
    - [2.5 Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification]()
    - [3.1. User Stories](#31-user-stories)
    - [3.2. Impact Mapping](#32-impact-mapping)
    - [3.3. Product Backlog](#33-product-backlog)
- [Capítulo IV: Product Design]()
    - [4.1. Style Guidelines](#41-style-guidelines)
        - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
        - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
    - [4.2. Information Architecture](#42-information-architecture)
        - [4.2.1. Organization Systems](#421-organization-systems)
        - [4.2.2. Labeling Systems](#422-labeling-systems)
        - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
        - [4.2.4. Searching Systems](#424-searching-systems)
        - [4.2.5. Navigation Systems](#425-navigation-systems)
    - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
        - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
        - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
    - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
        - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
        - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
        - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
        - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
    - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
    - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
        - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)
        - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
        - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
        - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
    - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
        - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.8. Database Design](#48-database-design)
        - [4.8.1. Database Diagram](#481-database-diagram)
- [Capítulo V: Product Implementation, Validation & Deployment]()
    - [5.1. Software Configuration Management](#51-software-configuration-management)
        - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
        - [5.1.2. Source Code Management](#512-source-code-management)
        - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
        - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
    - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
        - [5.2.1. Sprint 1](#521-sprint-1)
            - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
            - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
            - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
            - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
            - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
            - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
            - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
    - [5.3. Validation Interviews]()
        - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
        - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
        - [5.3.3. Evaluaciones según heuristicas](#533-evaluaciones-segun-heuristicas)
    - [5.4. Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
    - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

## Student Outcome

<table>
  <tr>
     <th colspan="2">Criterio Específico</th>
     <th colspan="10">Acciones Realizadas</th>
     <th colspan="2">Conclusiones</th>
  </tr>
  <tr>
     <td colspan="2">Comunica oralmente con efectividad a diferentes rangos de audiencia.</td>
     <td colspan="10">
        <b>Nombre: Gonzalo Alonso Carhuancote Dominguez</b><br><br>
        TB1:<br><br>
        TP:<br><br>
        TB2:<br><br>
        TF:<br><br>
        <b>Nombre:</b><br><br>
        TB1:<br><br>
        TP:<br><br>
        TB2:<br><br>
        TF:<br><br>
        <b>Nombre:</b><br><br>
        TB1:<br><br>
        TP:<br><br>
        TB2:<br><br>
        TF:<br><br>
        <b>Nombre:</b><br><br>
        TB1:<br><br>
        TP:<br><br>
        TB2:<br><br>
        TF:<br><br>
        <b>Nombre:</b><br><br>
        TB1:<br><br>
        TP:<br><br>
        TB2:<br><br>
        TF:<br><br>
     </td>
     <td colspan="2"></td>
  </tr>
  <tr>
     <td colspan="2">Comunica por escrito con efectividad a diferentes rangos de audiencia.</td>
     <td colspan="10">
        <b>Nombre: Gonzalo Alonso Carhuancote Dominguez</b><br><br>
        TB1:<br><br>
        TP:<br><br>
        TB2:<br><br>
        TF:<br><br>
        <b>Nombre:</b><br><br>
        TB1:<br><br>
        TP:<br><br>
        TB2:<br><br>
        TF:<br><br>
        <b>Nombre:</b><br><br>
        TB1:<br><br>
        TP:<br><br>
        TB2:<br><br>
        TF:<br><br>
        <b>Nombre:</b><br><br>
        TB1:<br><br>
        TP:<br><br>
        TB2:<br><br>
        TF:<br><br>
        <b>Nombre:</b><br><br>
        TB1:<br><br>
        TP:<br><br>
        TB2:<br><br>
        TF:<br><br>
     </td>
     <td colspan="2"></td>
  </tr>
</table>