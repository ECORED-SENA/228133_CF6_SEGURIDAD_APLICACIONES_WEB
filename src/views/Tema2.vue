<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Metodologías, normas y estándares

    p.mb-0(data-aos="fade-up") En el mundo de la seguridad en las aplicaciones #[em web], se han implementado metodologías,  normas y estándares importantes para la detección y prevención de riesgos informáticos, a continuación se describirán los más comunes:

    .row.cont_tema2_1.p-3(style="position:relative;")
      .col-md-3.mb-4.mb-md-0(style="place-self:center;position:relative")
        figure.text-center
          img(src="@/assets/curso/tema2/1.png" data-aos="fade-right" style="display:inline;max-width:300px;")
      .col-md-9(style="place-self:center;position:relative")
        h4(data-aos="fade-up") Metodologías
        p.mb-0(data-aos="fade-up") El concepto de metodología en el mundo de la informática, se refiere a la acción de detallar, observar y evaluar las páginas #[em web], cumpliendo con una serie de normas diseñadas para esa área específicamente; la metodología OWASP es la más requerida en la actualidad.

    .row.mt-5
      .col-md-8.mb-4.mb-0
        h5(data-aos="fade-up") Metodologías  OWASP
        p(data-aos="fade-up") Según esta metodología, comprende el OWASP Top 10 que corresponde a un documento de los diez riesgos de seguridad más importantes en aplicaciones #[em web] y por otra parte se deben tratar OWASP con (ASVS).
        p.mt-4(data-aos="fade-up") Dentro del OWASP Top 10 se encuentra el ítem 09 que trata del registro y monitoreo, en donde estos pueden ser desafiantes para ser testeados, implicando la realización de entrevistas o preguntando si los ataques fueron detectados durante las pruebas de penetración. No hay muchos datos de CVE/CVSS para esta categoría, pero realizar detecciones y responder a las brechas es crítico. Aún así, puede tener un gran impacto para la auditabilidad, visibilidad, alertas de incidentes y análisis forense. Esta categoría se expande más allá de CWE-117 Neutralización de salida incorrecta de registros, CWE-223 Omisión de información relevante para la seguridad, y CWE-532 inserción de información sensible en archivo de registro.
        p.mt-4(data-aos="fade-up") En registros y monitoreo, las brechas no pueden ser detectadas. registros, detecciones, monitoreo y respuestas activas insuficientes pueden ocurrir en cualquier momento; por lo tanto se recomienda recoger información sobre los siguientes eventos, que se presentan a continuación: 
      .col-md-4
        figure
          img(src="@/assets/curso/tema2/2.png" data-aos="fade-left")

    .cont_full_1.pt-4(style="position:relative")
      .row.mt-5
        .col-lg-4.mb-lg-0.mb-5
          .tarjeta-avatar-b(style="height:100%;")
            .tarjeta-avatar-b__img
              img(src='@/assets/curso/tema2/3.png' style="position:relative;z-index:1;")
            .tarjeta.tarjeta--azul(style="background-color: #FFF4D6;border: 2px #ECC153 solid;border-radius: 5px;position:relative")
              .p-4.h-100.d-flex.align-items-center
                p.mb-0(data-aos="fade-up") Registros en aplicaciones y API no son monitoreados para detectar actividades sospechosas.
                img.image_mapa(src="@/assets/curso/tema2/4.svg" style="max-width:50px;position:absolute;right:-30px;top:50%;")
        .col-lg-4.mb-lg-0.mb-5
          .tarjeta-avatar-b(style="height:100%;")
            .tarjeta-avatar-b__img
              img(src='@/assets/curso/tema2/5.png' style="position:relative;z-index:1;")
            .tarjeta.tarjeta--azul(style="background-color: #C7EDE0;border: 2px #83CBB0 solid;border-radius: 5px;position:relative")
              .p-4.h-100.d-flex.align-items-center
                p.mb-0(data-aos="fade-up") Advertencias y errores generan registros poco claros, inadecuados y en algunos casos ni se generan. 
                img.image_mapa(src="@/assets/curso/tema2/4.svg" style="max-width:50px;position:absolute;right:-30px;top:50%;")
        .col-lg-4.mb-lg-0.mb-5
          .tarjeta-avatar-b(style="height:100%;")
            .tarjeta-avatar-b__img
              img(src='@/assets/curso/tema2/6.png' style="position:relative;z-index:1;")
            .tarjeta.tarjeta--azul(style="background-color: #FFF4D6;border: 2px #ECC153 solid;border-radius: 5px;position:relative")
              .p-4.h-100.d-flex.align-items-center
                p.mb-0(data-aos="fade-up") Eventos auditables, tales como los inicios de sesión, fallas en el inicio de sesión y transacciones de alto valor no son registradas. 
                img.image_mapa(src="@/assets/curso/tema2/4.svg" style="max-width:50px;position:absolute;right:40%;bottom:-20px;transform:rotate(90deg);")
      .row.mt-lg-5
        .col-lg-4.mb-lg-0.mb-5.order-3.order-lg-0
          .tarjeta-avatar-b(style="height:100%;")
            .tarjeta-avatar-b__img
              img(src='@/assets/curso/tema2/7.png' style="position:relative;z-index:1;")
            .tarjeta.tarjeta--azul(style="background-color: #C7EDE0;border: 2px #83CBB0 solid;border-radius: 5px;position:relative;height:100%;")
              .p-4.h-100.d-flex.align-items-center
                p.mb-0(data-aos="fade-up") Los registros son únicamente almacenados en forma local.
                img.image_mapa(src="@/assets/curso/tema2/4.svg" style="max-width:50px;position:absolute;right:40%;bottom:-20px;transform:rotate(90deg);")
        .col-lg-4.mb-lg-0.mb-5.order-2.order-lg-0
          .tarjeta-avatar-b(style="height:100%;")
            .tarjeta-avatar-b__img
              img(src='@/assets/curso/tema2/8.png' style="position:relative;z-index:1;")
            .tarjeta.tarjeta--azul(style="background-color: #FFF4D6;border: 2px #ECC153 solid;border-radius: 5px;position:relative;height:100%;")
              .p-4.h-100.d-flex.align-items-center
                p.mb-0(data-aos="fade-up") Las pruebas de penetración y los escaneos utilizando herramientas de pruebas dinámicas de seguridad en aplicaciones (como ser OWASP ZAP) no generan alertas.
                img.image_mapa(src="@/assets/curso/tema2/4.svg" style="max-width:50px;position:absolute;left:-90px;top:50%;transform:rotate(180deg);")
        .col-lg-4.mb-lg-0.mb-5.order-1.order-lg-0
          .tarjeta-avatar-b(style="height:100%;")
            .tarjeta-avatar-b__img
              img(src='@/assets/curso/tema2/9.png' style="position:relative;z-index:1;")
            .tarjeta.tarjeta--azul(style="background-color: #C7EDE0;border: 2px #83CBB0 solid;border-radius: 5px;position:relative;height:100%;")
              .p-4.h-100.d-flex.align-items-center
                p.mb-0(data-aos="fade-up") Las aplicaciones no logran detectar, escalar, o alertar sobre ataques activos en tiempo real ni cercanos al tiempo real.
                img.image_mapa(src="@/assets/curso/tema2/4.svg" style="max-width:50px;position:absolute;left:-90px;top:50%;transform:rotate(180deg);")
      .row.mt-lg-5
        .col-lg-4.mb-lg-0.mb-5
          .tarjeta-avatar-b
            .tarjeta-avatar-b__img
              img(src='@/assets/curso/tema2/10.png' style="position:relative;z-index:1;")
            .tarjeta.tarjeta--azul(style="background-color: #FFF4D6;border: 2px #ECC153 solid;border-radius: 5px;position:relative")
              .p-4.h-100.d-flex.align-items-center
                p.mb-0(data-aos="fade-up") Los umbrales de alerta y procesos de escalamiento no están correctamente implementados o no son efectivos.
        .col-lg-8
          figure.text-center
            img(src="@/assets/curso/tema2/11.svg" data-aos="zoom-in-up" style="max-width:600px;display:inline;")

    p.mt-5(data-aos="fade-up") Para prevenir a los desarrolladores, se deberían implementar algunos o todos los siguientes controles, dependiendo del riesgo de la aplicación:

    TabsA.color-acento-botones.mt-5
      .tarjeta.color-acento-botones--borde.p-4(titulo="PASO 1: Identificar errores" style="background-color:#FFFBF0;")
        h4 Identificar errores
        .row.mt-3
          .col-md-5.mb-md-0.mb-4(style="place-self:center;")
            figure
              img(src="@/assets/curso/tema2/12.png")
          .col-md-7(style="place-self:center;")
            p Asegúrese que todos los errores de inicio de sesión, de control de acceso y de validación de entradas de datos del lado del servidor se pueden registrar con suficiente contexto como para identificar cuentas sospechosas o maliciosas y mantenerlo durante el tiempo suficiente para permitir un posterior análisis forense.

      .tarjeta.color-acento-botones--borde.p-4(titulo="PASO 2: Gestión de riesgos" style="background-color:#FFFBF0;")
        h4 Gestión de riesgos
        .row.mt-3
          .col-md-5.mb-md-0.mb-4(style="place-self:center;")
            figure
              img(src="@/assets/curso/tema2/13.png")
          .col-md-7(style="place-self:center;")
            p Verifique que los registros se generan en un formato fácil de procesar por las herramientas de gestión de registros.
      .tarjeta.color-acento-botones--borde.p-4(titulo="PASO 3: Verificación de datos" style="background-color:#FFFBF0;")
        h4 Verificación de datos
        .row.mt-3
          .col-md-5.mb-md-0.mb-4(style="place-self:center;")
            figure
              img(src="@/assets/curso/tema2/14.png")
          .col-md-7(style="place-self:center;")
            p Revise que los datos de registros estén correctamente codificados para prevenir inyecciones o ataques en el sistema de monitoreo o registros. 
      .tarjeta.color-acento-botones--borde.p-4(titulo="PASO 4: Realizar auditoría" style="background-color:#FFFBF0;")
        h4 Realizar auditoría
        .row.mt-3
          .col-md-5.mb-md-0.mb-4(style="place-self:center;")
            figure
              img(src="@/assets/curso/tema2/15.png")
          .col-md-7(style="place-self:center;")
            p Asegúrese que las transacciones de alto valor poseen una traza de auditoría con controles de integridad para evitar la modificación o el borrado, tales como permitir únicamente la inserción en las tablas de base de datos o similares.
      .tarjeta.color-acento-botones--borde.p-4(titulo="PASO 5: Establecer alertas" style="background-color:#FFFBF0;")
        h4 Establecer alertas
        .row.mt-3
          .col-md-5.mb-md-0.mb-4(style="place-self:center;")
            figure
              img(src="@/assets/curso/tema2/16.png")
          .col-md-7(style="place-self:center;")
            p Los equipos de DevSecOps deben establecer alertas y monitoreo efectivo tal, que se detecten actividades sospechosas y responder rápidamente.
      .tarjeta.color-acento-botones--borde.p-4(titulo="PASO 6: Adoptar plan de respuesta y recuperación" style="background-color:#FFFBF0;")
        h4 Adoptar plan de respuesta y recuperación
        .row.mt-3
          .col-md-5.mb-md-0.mb-4(style="place-self:center;")
            figure
              img(src="@/assets/curso/tema2/17.png")
          .col-md-7(style="place-self:center;")
            p Establezca o adopte un plan de respuesta y recuperación, tal como NIST 800-61r2 o posterior.

    .row.cont_tema2_2.p-3(style="position:relative;")
      .col-md-3.mb-4.mb-md-0(style="place-self:center;position:relative")
        figure.text-center
          img(src="@/assets/curso/tema2/18.png" data-aos="fade-right" style="display:inline;max-width:300px;")
      .col-md-9(style="place-self:center;position:relative")
        h4(data-aos="fade-up") Normas
        p.mb-0(data-aos="fade-up") Las normas son documentos que contienen directrices, características o en su defecto requisitos, que se deben tener en cuenta en la elaboración, diseño o utilización de productos, procesos y servicios, de modo que garantice la calidad del mismo. Con relación a esta finalidad, existen las normas ISO, las cuales son estándares internacionales que ayudan a las empresas a establecer criterios de homogeneidad frente a la gestión, prestación de servicios y desarrollo de productos en la industria. #[br] La familia de normas ISO/IEC 27000 hacen parte del conjunto de estándares de seguridad (desarrollados o en fase de desarrollo) que proporcionan un marco para la gestión de la seguridad.

    p.mt-5(data-aos="fade-up") Contiene las mejores prácticas recomendadas en seguridad de la información para desarrollar, implementar y mantener especificaciones para los Sistemas de Gestión de la Seguridad de la Información (SGSI) utilizable por cualquier tipo de organización, pública o privada, grande o pequeña.
    p.mt-4(data-aos="fade-up") La seguridad de la información, según la ISO 27001, se basa en la preservación de los siguientes conceptos:

    br
    .row.mt-5
      .col-lg-4.mb-5.mb-lg-0
        div(style="height:100%")
          .pb-5.ps-5.pe-5.text-center(style="background-color:#294DDC;border-top-left-radius:5px;border-top-right-radius:5px;")
            img(src="@/assets/curso/tema2/19.png" data-aos="zoom-in-up" style="position:relative;display:inline;max-width:200px;margin-top:-75px;")
            div.mt-4(data-aos="fade-up")
              span(style="background-color:#fff;font-weight:bold;font-size:18px;width:auto;border-radius:50px;padding:.6rem 1.4rem;") Confidencialidad 
          .p-5(style="background-color:#E5EAFF;")             
            p.mb-5(data-aos="fade-up") La información no se pone a disposición ni se revela a individuos, entidades o procesos no autorizados.
      .col-lg-4.mb-5.mb-lg-0.mt-5.mt-lg-0
        div(style="height:100%")
          .pb-5.ps-5.pe-5.text-center(style="background-color:#6ACEAE;border-top-left-radius:5px;border-top-right-radius:5px;")
            img(src="@/assets/curso/tema2/20.png" data-aos="zoom-in-up" style="position:relative;display:inline;max-width:200px;margin-top:-75px;")
            div.mt-4(data-aos="fade-up")
              span(style="background-color:#fff;font-weight:bold;font-size:18px;width:auto;border-radius:50px;padding:.6rem 1.4rem;") Integridad 
          .p-5(style="background-color:#C7EDE0;")             
            p.mb-5(data-aos="fade-up") Mantenimiento de la exactitud y completitud de la información y sus métodos de proceso.
      .col-lg-4.mb-5.mb-lg-0.mt-5.mt-lg-0
        div(style="height:100%")
          .pb-5.ps-5.pe-5.text-center(style="background-color:#294DDC;border-top-left-radius:5px;border-top-right-radius:5px;")
            img(src="@/assets/curso/tema2/21.png" data-aos="zoom-in-up" style="position:relative;display:inline;max-width:200px;margin-top:-75px;")
            div.mt-4(data-aos="fade-up")
              span(style="background-color:#fff;font-weight:bold;font-size:18px;width:auto;border-radius:50px;padding:.6rem 1.4rem;") Disponibilidad 
          .p-5(style="background-color:#E5EAFF;")             
            p.mb-4(data-aos="fade-up") Acceso y utilización de la información y los sistemas de tratamiento de la misma por parte de los individuos o procesos autorizados cuando lo requieran.

    p.mt-5(data-aos="fade-up") En la tabla que se presenta a continuación, se encuentra un resumen de las Normas ISO 27000, con su respectiva descripción:

    .titulo-sexto.color-acento-contenido.mt-5
      h5 Tabla 1
      span Resumen de Normas ISO 27000

    .tabla-a.color-acento-botones.mt-4 
      table
        thead(style="border:0")
          tr(style="background-color:#6ACEAE;")
            th.text-center(style="font-size:18px;border:0;width:30%;") Norma
            th.text-center(style="font-size:18px;border:0;") Descripción
        tbody
          tr(style="background-color:#F6F6F6;")
            td.p-4.text-center(style="border:0;border-right:1px #16263D solid;font-weight:bold;") ISO/IEC 27000
            td.p-4(style="border:0;") Vocabulario estándar para el SGSI para todas las normas de la familia. Se encuentra en desarrollo actualmente.
          tr(style="background-color:#FFF;")
            td.p-4.text-center(style="border:0;border-right:1px #16263D solid;font-weight:bold;") ISO/IEC 27001
            td.p-4(style="border:0;") Certificación que deben obtener las organizaciones. Norma que especifica los requisitos para la implantación de SGSI. Es la norma más importante de la familia. Adopta un enfoque de gestión de riesgos y promueve la mejora continua de los procesos. Fue publicada como estándar internacional en octubre de 2005.
          tr(style="background-color:#F6F6F6;")
            td.p-4.text-center(style="border:0;border-right:1px #16263D solid;font-weight:bold;") ISO/IEC 27002
            td.p-4(style="border:0;") #[em Information technology- Security techniques-Code of practice for information security management]. Previamente BS 7799 parte 1 y la norma ISO/IEC 17799. Es un código de buenas prácticas para la gestión de seguridad de la información. Fue publicada en julio de 2005 como ISO 17799:2005 y recibió su nombre oficial ISO/IEC 27002:2002 el 01  de julio de 2007.
          tr(style="background-color:#FFF;")
            td.p-4.text-center(style="border:0;border-right:1px #16263D solid;font-weight:bold;") ISO/IEC 27003
            td.p-4(style="border:0;") Directrices para la implementación de un SGSI, es el soporte de la norma ISO/IEC 27001, publicada el 1 de febrero del 2010, no está certificada actualmente.
          tr(style="background-color:#F6F6F6;")
            td.p-4.text-center(style="border:0;border-right:1px #16263D solid;font-weight:bold;") ISO/IEC 27004
            td.p-4(style="border:0;") Métricas para la gestión de seguridad de la información. Es la que proporciona recomendaciones de quién, cuándo y cómo realizar mediciones de seguridad de la información. Publicada el 7 de diciembre del 2009, no se encuentra traducida al español actualmente.
          tr(style="background-color:#FFF;")
            td.p-4.text-center(style="border:0;border-right:1px #16263D solid;font-weight:bold;") ISO/IEC 27005
            td.p-4(style="border:0;") Normativa dedicada exclusivamente a la gestión de riesgos de seguridad de la información, proporciona recomendaciones y lineamientos de métodos y técnicas de evaluación de riesgos en seguridad de la información, en soporte del proceso de gestión de riesgos de la norma ISO/IEC 27001. Es la más relacionada a la actual British Standar BS 7799 parte 3. Publicada en junio de 2008.
          tr(style="background-color:#F6F6F6;")
            td.p-4.text-center(style="border:0;border-right:1px #16263D solid;font-weight:bold;") ISO/IEC 27006
            td.p-4(style="border:0;") Requisitos para la acreditación de las organizaciones que proporcionan la certificación de los sistemas de gestión de seguridad de la información. Esta norma específica de requisitos para la certificación del SGSI es usada en conjunto con la norma 17021-1, la norma genérica de acreditación.
          tr(style="background-color:#FFF;")
            td.p-4.text-center(style="border:0;border-right:1px #16263D solid;font-weight:bold;") ISO/IEC 27007
            td.p-4(style="border:0;") Guía para auditar al SGSI. Se encuentra en preparación.
          tr(style="background-color:#F6F6F6;")
            td.p-4.text-center(style="border:0;border-right:1px #16263D solid;font-weight:bold;") ISO/IEC 27709:2008
            td.p-4(style="border:0;") Guía para implementar ISO/IEC 27002 en la industria de la salud.

    p.mt-5(data-aos="fade-up") A continuación, podrá ampliar la información sobre la Ley 1581 de 2012, la cual se constituye en el marco general de la norma de protección de los datos personales en Colombia:

    .row.cont_tema2_3.mt-5.p-4(style="position:relative")
      .col-lg-1.mb-4.mb-lg-0(style="place-self:center;position:relative")
        figure.text-center
          img(src="@/assets/curso/tema2/22.png" style="display:inline;max-width:65px" data-aos="fade-right")
      .col-lg-9.mb-4.mb-lg-0(style="place-self:center;position:relative")
        h4.text-white(data-aos="fade-up" style="position:relative") Ley 1581 de 2012
        p.text-white.mb-0(data-aos="fade-up" style="position:relative") En el siguiente enlace de la página #[em web]  de Función Pública, podrá ampliar la información sobre la Ley 1581 de 2012, la cual se constituye en el marco general de la norma de protección de los datos personales en Colombia.
      .col-lg-2.text-center(style="place-self:center;position:relative")
        a.boton.color-acento-botones(href="https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=49981" target="_blank" data-aos="fade-left")
          span Ir al enlace

    .row.cont_tema2_2.p-3(style="position:relative;")
      .col-md-3.mb-4.mb-md-0(style="place-self:center;position:relative")
        figure.text-center
          img(src="@/assets/curso/tema2/23.png" data-aos="fade-right" style="display:inline;max-width:300px;")
      .col-md-9(style="place-self:center;position:relative")
        h4(data-aos="fade-up") Estándares
        p.mb-0(data-aos="fade-up") Continuando con la temática de metodologías, normas y estándares, en este punto se hablará sobre este último, pero haciendo especial énfasis en el estándar OWASP top 10 en conjunto con el estándar (ASVS) de OWASP. El Proyecto del Estándar de Verificación de Seguridad de Aplicaciones (ASVS) de OWASP proporciona una base para probar los controles técnicos de seguridad de las aplicaciones #[em web] y también proporciona a los desarrolladores una lista de requisitos para un desarrollo seguro.

    .row.mt-5
      .col-md-8.mb-md-0
        p(data-aos="fade-up") El objetivo principal del #[strong Proyecto del Estándar de Verificación de Seguridad de Aplicaciones (ASVS)] de OWASP es normalizar el rango en la cobertura y el nivel de rigor disponible en el mercado cuando se trata de realizar la verificación de seguridad de aplicaciones #[em web] utilizando un estándar abierto comercialmente viable. El estándar proporciona una base para probar los controles de seguridad técnica de la aplicación, así como cualquier control de seguridad técnica en el entorno, en los que se confía para proteger contra vulnerabilidades como Cross-Site Scripting (XSS) e inyección de SQL. Este estándar se puede utilizar para establecer un nivel de confianza en la seguridad de las aplicaciones #[em web]. 
        p.mt-4(data-aos="fade-up") La siguiente tabla muestra cuándo es apropiado utilizar el OWASP top 10 unido al  (ASVS) de OWASP.
      .col-md-4
        figure
          img(src="@/assets/curso/tema2/24.png" data-aos="fade-left")

    .col-md-10.m-auto
      .titulo-sexto.color-acento-contenido.mt-5
        h5 Tabla 2
        span Otros estándares COBIT e ISO 17799
      .tabla-a.color-acento-botones.mt-4 
        table
          thead(style="border:0")
            tr(style="background-color:#6ACEAE;")
              th.text-center(style="font-size:18px;border:0;") Norma
              th.text-center(style="font-size:18px;border:0;") Descripción
              th.text-center(style="font-size:18px;border:0;") Descripción
          tbody
            tr(style="background-color:#F6F6F6;")
              td.p-4(style="border:0;border-right:1px #16263D solid;font-weight:bold;") Concientización
              td.p-4.text-center(style="border:0;border-right:1px #16263D solid;") Sí
              td.p-4.text-center(style="border:0;") 
            tr(style="background-color:#FFF;")
              td.p-4(style="border:0;border-right:1px #16263D solid;font-weight:bold;") Capacitación
              td.p-4.text-center(style="border:0;border-right:1px #16263D solid;") Nivel de introductorio
              td.p-4.text-center(style="border:0;") Completo
            tr(style="background-color:#F6F6F6;")
              td.p-4(style="border:0;border-right:1px #16263D solid;font-weight:bold;") Diseño y arquitectura
              td.p-4.text-center(style="border:0;border-right:1px #16263D solid;") Ocasionalmente
              td.p-4.text-center(style="border:0;")  Sí
            tr(style="background-color:#FFF;")
              td.p-4(style="border:0;border-right:1px #16263D solid;font-weight:bold;") Estándar de codificación
              td.p-4.text-center(style="border:0;border-right:1px #16263D solid;") Apenas mínimo
              td.p-4.text-center(style="border:0;") Sí
            tr(style="background-color:#F6F6F6;")
              td.p-4(style="border:0;border-right:1px #16263D solid;font-weight:bold;") Revisión de código seguro
              td.p-4.text-center(style="border:0;border-right:1px #16263D solid;") Apenas mínimo
              td.p-4.text-center(style="border:0;")  Sí
            tr(style="background-color:#FFF;")
              td.p-4(style="border:0;border-right:1px #16263D solid;font-weight:bold;") Lista de verificación para la revisión por pares
              td.p-4.text-center(style="border:0;border-right:1px #16263D solid;") Apenas mínimo
              td.p-4.text-center(style="border:0;") Sí
            tr(style="background-color:#F6F6F6;")
              td.p-4(style="border:0;border-right:1px #16263D solid;font-weight:bold;") Pruebas unitarias
              td.p-4.text-center(style="border:0;border-right:1px #16263D solid;") Ocasionalmente
              td.p-4.text-center(style="border:0;")  Sí
            tr(style="background-color:#FFF;")
              td.p-4(style="border:0;border-right:1px #16263D solid;font-weight:bold;") Pruebas de integración
              td.p-4.text-center(style="border:0;border-right:1px #16263D solid;") Ocasionalmente
              td.p-4.text-center(style="border:0;") Sí
            tr(style="background-color:#F6F6F6;")
              td.p-4(style="border:0;border-right:1px #16263D solid;font-weight:bold;") Pruebas de penetración
              td.p-4.text-center(style="border:0;border-right:1px #16263D solid;") Apenas mínimo
              td.p-4.text-center(style="border:0;")  Sí
            tr(style="background-color:#FFF;")
              td.p-4(style="border:0;border-right:1px #16263D solid;font-weight:bold;") Soporte de herramientas
              td.p-4.text-center(style="border:0;border-right:1px #16263D solid;") Apenas mínimo
              td.p-4.text-center(style="border:0;") Sí
            tr(style="background-color:#F6F6F6;")
              td.p-4(style="border:0;border-right:1px #16263D solid;font-weight:bold;") Cadena de suministro de agua
              td.p-4.text-center(style="border:0;border-right:1px #16263D solid;") Ocasionalmente
              td.p-4.text-center(style="border:0;")  Sí

    p.mt-5(data-aos="fade-up") Finalmente, en la siguiente figura se resume la aplicación de normas y estándares de una organización:

    .p-5.mt-5(style="background-color:#FFF5DE;border-radius:15px;")
      .titulo-sexto.color-acento-contenido
        h5 Figura 2.
        span Aplicación de normas y estándares de una organización
      figure.mt-4
        img(src="@/assets/curso/tema2/25.svg" data-aos="zoom-in-up")



</template>

<script>
export default {
  name: 'Tema2',
  components: {},
  data: () => ({
    indicadorTarjetaSlide: true,
    indicadorTarjetaFlip: true,
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>
<style lang="sass">
.cont_tema2_1:before
  content: ''
  position: absolute
  width: 115%
  left: -7%
  height: 70%
  top: 25%
  background-color: #E5FDF3
@media screen and (max-width: 991px)
  .image_mapa
    right: 40% !important
    bottom: -20px !important
    transform: rotate(90deg) !important
    left: unset !important
    top: unset !important
.tabs-a__tab
  background-color: #E8E8E8
.tabs-a.color-acento-botones .tabs-a__tab__selected
  background-color: #6ACEAE
.tabs-a.color-acento-botones .tabs-a__tab__selected:before
  background-color: #6ACEAE
.tabs-a.color-acento-botones .tabs-a__tab:hover, .tabs-a.color-acento-botones .tabs-a__tab:active, .tabs-a.color-acento-botones .tabs-a__tab:focus
  background-color: 6ACEAE
.tabs-a.color-acento-botones .tabs-a__tab:hover, .tabs-a.color-acento-botones .tabs-a__tab:active, .tabs-a.color-acento-botones .tabs-a__tab:focus
  background-color: #6ACEAE
.cont_tema2_2:before
  content: ''
  position: absolute
  width: 115%
  left: -7%
  height: 70%
  top: 17%
  background-color: #E5FDF3
.cont_tema2_3:before
  content: ''
  position: absolute
  width: 115%
  left: -7%
  height: 100%
  top: 0
  background: rgb(17,31,79)
  background: linear-gradient(0deg, rgba(17,31,79,1) 0%, rgba(46,82,212,1) 100%)
.cont_full_1:before
  content: ''
  position: absolute
  width: 115%
  left: -7%
  height: 80%
  top: 0
  background-color: #FAFBFF
@media screen and (max-width: 1200px)
  .cont_tema2_1:before, .cont_tema2_2:before
    height: 100%
    top: 0%
  .cont_tema2_1, .cont_tema2_2
    margin-top: 1.5rem
</style>
