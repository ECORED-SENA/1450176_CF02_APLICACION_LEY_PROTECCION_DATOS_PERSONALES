<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido(data-aos="flip-up")
        .titulo-principal__numero
          span 5
        h1 Plan de mejora para la protección de datos personales
      .bg___color_1
        .px-5
          .row.align-items-center.mb-3
            .col-xl
              .box___style_1.color___1(data-aos="flip-up").mb-3
                p.mb-0 El #[b plan de mejora para la protección de datos personales] es una herramienta que permite organizar las acciones necesarias para corregir debilidades, reducir riesgos y fortalecer el cumplimiento en el tratamiento de la información. Este plan se construye a partir del diagnóstico realizado, los hallazgos identificados, los controles existentes y las necesidades detectadas en cada proceso de la organización.
              p.mb-0 Un plan de mejora no debe convertirse en un documento extenso sin aplicación práctica. Debe ser claro, realista y útil para orientar la toma de decisiones. Su propósito es definir qué se debe mejorar, quién será responsable, qué acciones se implementarán, qué evidencias se conservarán y cómo se realizará el seguimiento.
            .col-xl-auto.d-none.d-xl-block(data-aos="zoom-in")
              figure
                img(src='@/assets/curso/temas/t5/img1.png', alt='' style="width: 400px").m-auto
          p.mb-0 La elaboración de este plan contribuye a que la organización actúe de manera preventiva frente a posibles incumplimientos. También permite fortalecer la cultura de protección de datos personales, mejorar los procedimientos internos, actualizar documentos, proteger las bases de datos y responder de manera adecuada a los derechos de los titulares.
          Separador
          #t_5_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
            h2 5.1 Elaboración del diagnóstico final
          p El #[b diagnóstico final] reúne los resultados obtenidos durante la revisión de bases de datos, formularios, autorizaciones, políticas, controles, solicitudes, incidentes y riesgos. Su finalidad es presentar una perspectiva clara del estado de la organización frente al tratamiento de datos personales.
          p.mb-5 Este diagnóstico debe incluir los aspectos que funcionan adecuadamente y aquellos que requieren mejora. No se trata únicamente de señalar errores, sino de identificar oportunidades para fortalecer la gestión de la información personal. Los elementos del diagnóstico pueden organizarse así:
          .bg___slider.mb-5
            .px-5
              .ajuste-slider(data-aos="zoom-in")
                SlyderA(tipo="b")
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Bases de datos y tipos de información
                      p.mb-0 Se deben identificar las bases existentes y los tipos de datos tratados para determinar qué información administra la organización y en qué procesos se utiliza.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t5/img2.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Finalidades y autorizaciones
                      p.mb-0 Es necesario relacionar cada tratamiento con su finalidad y establecer si existen los soportes de autorización correspondientes cuando sean requeridos.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t5/img3.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Políticas y responsables
                      p.mb-0 La revisión debe establecer si existen políticas vigentes y si las responsabilidades internas frente al tratamiento están claramente asignadas.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t5/img4.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Controles implementados
                      p.mb-0 Se deben considerar los controles administrativos, técnicos y físicos aplicados para proteger la información durante su ciclo de tratamiento.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t5/img5.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Solicitudes e incidentes
                      p.mb-0 El diagnóstico debe integrar las solicitudes de titulares y los incidentes registrados, con el fin de identificar dificultades recurrentes o necesidades de mejora.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t5/img6.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Riesgos y evidencias
                      p.mb-0 Se deben consolidar los riesgos identificados y los soportes disponibles para demostrar las acciones realizadas por la organización.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t5/img7.png', alt='' style="max-width: 500px").m-auto
      p.mb-5 La revisión integral de estos elementos permite consolidar los resultados del diagnóstico y establecer las prioridades que orientarán el plan de mejora.
      .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
        .col
          h3 Matriz de hallazgos
      p La #[b matriz de hallazgos] permite organizar las situaciones identificadas durante el diagnóstico. Cada hallazgo debe describirse de manera clara e indicar el área afectada, el riesgo asociado y la acción de mejora recomendada.
      p.mb-5 Un hallazgo puede corresponder a una debilidad documental, un riesgo operativo, una ausencia de control, una autorización incompleta, una política desactualizada o una práctica que requiera ajuste. Lo importante es que su identificación permita tomar decisiones concretas. La matriz puede estructurarse a partir de los siguientes elementos:
      .bg___carrusel
        .px-5
          SlyderF(columnas="col-lg-6 col-xl-4")(data-aos="zoom-in").mb-5
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t5/img8.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Hallazgo
              p.mb-0.text-center Describe de manera concreta la situación identificada durante el diagnóstico y permite precisar la debilidad, ausencia de control o práctica que requiere ajuste.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t5/img9.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Área afectada
              p.mb-0.text-center Identifica el área, proceso o dependencia relacionada con el hallazgo y facilita la asignación posterior de responsabilidades.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t5/img10.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Riesgo asociado
              p.mb-0.text-center Precisa la posible consecuencia derivada del hallazgo, especialmente cuando puede comprometer el tratamiento adecuado o la protección de los datos personales.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t5/img11.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Acción de mejora
              p.mb-0.text-center Define la medida recomendada para corregir la situación, fortalecer el control existente o reducir el riesgo identificado durante el diagnóstico.
          p.mb-5 Esta organización facilita la relación entre los hallazgos identificados y las acciones que deben incorporarse al plan de mejora.
          .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
            .col-lg-auto
              figure
                img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
            .col
              h3 Priorización de riesgos
          p.mb-5 La #[b priorización de riesgos] permite definir cuáles situaciones deben atenderse primero. No todos los hallazgos tienen el mismo impacto ni requieren el mismo nivel de urgencia. Algunos pueden resolverse mediante ajustes simples, mientras que otros requieren intervención inmediata por el tipo de datos comprometidos o por la posibilidad de afectar los derechos de los titulares. Para establecer la prioridad, se deben considerar tres elementos principales:
          .row.justify-content-center.mb-5
            .col-xl-4.col-md-9.mb-4.mb-lg-0(data-aos="fade-right")
              .box___card_sinbordes.h-100
                .row.justify-content-center.mb-3
                  .col-12
                    figure.mb-4
                      img(src='@/assets/curso/temas/t5/img12.png', alt="" ).m-auto
                  h4.text-center Probabilidad
                  .box___card_sinbordes_p
                    p.mb-0.text-center Permite establecer la posibilidad de que el riesgo identificado llegue a materializarse durante el tratamiento de los datos personales.
            .col-xl-4.col-md-9.mb-4.mb-lg-0(data-aos="zoom-in")
              .box___card_sinbordes.h-100
                .row.justify-content-center.mb-3
                  .col-12
                    figure.mb-4
                      img(src='@/assets/curso/temas/t5/img13.png', alt="" ).m-auto
                  h4.text-center Impacto
                  .box___card_sinbordes_p
                    p.mb-0.text-center Permite determinar las consecuencias que podría generar la materialización del riesgo para los titulares, los procesos o la organización.
            .col-xl-4.col-md-9(data-aos="fade-left")
              .box___card_sinbordes.h-100
                .row.justify-content-center.mb-3
                  .col-12
                    figure.mb-4
                      img(src='@/assets/curso/temas/t5/img14.png', alt="" ).m-auto
                  h4.text-center Tipo de datos involucrados
                  .box___card_sinbordes_p
                    p.mb-0.text-center Permite considerar la naturaleza de la información comprometida. Los riesgos relacionados con datos sensibles, menores de edad, divulgación indebida o falta de autorización requieren mayor atención.
      p.mb-5 La priorización permite organizar las acciones de mejora en el corto, mediano y largo plazo. De esta manera, se evita que el plan se convierta en una lista general de actividades sin un orden de atención ni responsables definidos.
      .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
        .col
          h3 Evidencias de cumplimiento
      p.mb-5 Las #[b evidencias de cumplimiento] son los soportes que permiten demostrar que la organización ha realizado acciones para proteger los datos personales. Estas evidencias pueden ser físicas o digitales y deben conservarse de manera organizada. Para facilitar su gestión, pueden agruparse de acuerdo con la acción que respaldan:
      .bg___slider.mb-5
        .px-5
          .ajuste-slider(data-aos="zoom-in")
            SlyderA(tipo="b")
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Autorizaciones y políticas
                  p.mb-0 Incluyen autorizaciones de tratamiento y políticas publicadas o socializadas que permiten sustentar las condiciones definidas para el manejo de la información.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img15.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Gestión de bases de datos
                  p.mb-0 El inventario de bases de datos permite identificar la información tratada, los procesos relacionados y las condiciones de administración.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img16.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Atención de derechos
                  p.mb-0 Los registros de consultas y reclamos, así como los formatos de actualización, rectificación o supresión, permiten documentar la atención brindada a los titulares.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img17.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Capacitación y confidencialidad
                  p.mb-0 Las actas, listados de capacitación y acuerdos de confidencialidad permiten sustentar las acciones desarrolladas con el personal que maneja información personal.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img18.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Gestión de incidentes y riesgos
                  p.mb-0 Los registros de incidentes, matrices de riesgos y soportes de acciones correctivas permiten documentar situaciones identificadas y las respuestas implementadas.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img19.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Controles y comunicaciones
                  p.mb-0 Las evidencias de controles de acceso y las comunicaciones remitidas a los titulares respaldan las actuaciones desarrolladas durante la gestión de la información.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img20.png', alt='' style="max-width: 500px").m-auto
      p.mb-0 Contar con evidencias no significa acumular documentos sin control. La organización debe conservar soportes útiles, actualizados y relacionados directamente con las acciones implementadas.
      Separador
      #t_5_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
        h2 5.2 Diseño de acciones de mejora
      p.mb-5 El #[b diseño de acciones de mejora] consiste en definir actividades concretas para corregir los hallazgos identificados. Estas acciones deben ser realizables, medibles y coherentes con los riesgos encontrados. Para formular una acción de mejora, deben considerarse los siguientes elementos:
      .row.justify-content-center.mb-5
        .col-xl-10
          .box___style_2(data-aos="zoom-in")
            .row.align-items-center
              .col-xl-auto
                figure
                  img(src='@/assets/curso/temas/t5/img21.jpg', alt='' style="width: 400px").m-auto
              .col-xl.fit___box_container
                ul.fa-ul.estilo___ul.mb-0
                  li.mb-2
                    span.fa-li
                      i.fas.fa-check-circle
                    | #[b Situación que requiere corrección:] permite precisar qué hallazgo, debilidad o riesgo será intervenido mediante la acción propuesta.
                  li.mb-2
                    span.fa-li
                      i.fas.fa-check-circle
                    | #[b Justificación:] explica por qué es necesario realizar la acción y qué riesgo o necesidad pretende atender.
                  li.mb-2
                    span.fa-li
                      i.fas.fa-check-circle
                    | #[b Responsable:] define la persona, área o proceso encargado de ejecutar y realizar seguimiento a la actividad.
                  li.mb-2
                    span.fa-li
                      i.fas.fa-check-circle
                    | #[b Recursos:] identifica los recursos humanos, tecnológicos, documentales o administrativos necesarios para implementar la acción.
                  li.mb-2
                    span.fa-li
                      i.fas.fa-check-circle
                    | #[b Plazo:] establece el periodo en el que debe ejecutarse la actividad y facilita el seguimiento a su cumplimiento.
                  li.mb-2
                    span.fa-li
                      i.fas.fa-check-circle
                    | #[b Evidencia:] define el soporte que permitirá demostrar que la acción fue realizada.
                  li.mb-0
                    span.fa-li
                      i.fas.fa-check-circle
                    | #[b Efectividad:] permite determinar cómo se establecerá si la medida implementada contribuyó a corregir el hallazgo o reducir el riesgo.
      p.mb-5 Las acciones de mejora pueden ser #[b administrativas, técnicas o de capacitación]. Su aplicación articulada permite integrar documentos, controles tecnológicos, responsables definidos y personal capacitado para fortalecer la protección de datos personales.
      .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
        .col
          h3 Acciones administrativas
      p.mb-5 Las #[b acciones administrativas] están relacionadas con políticas, procedimientos, formatos, responsables, controles internos y documentación. Permiten organizar la gestión de los datos personales y definir reglas claras para las diferentes áreas de la organización. Las principales acciones administrativas pueden organizarse de esta manera:
      .bg___slider.mb-5
        .px-5
          .ajuste-slider(data-aos="zoom-in")
            SlyderA(tipo="b")
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Políticas y autorizaciones
                  p.mb-0 Incluyen la actualización de la política de tratamiento y la creación o ajuste de formatos de autorización para mantenerlos acordes con las finalidades aplicadas.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img22.png', alt='' style="max-width: 500px").m-auto 
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Inventario y responsables
                  p.mb-0 Comprenden la elaboración del inventario de bases de datos y la asignación de responsables para facilitar su administración y seguimiento.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img23.png', alt='' style="max-width: 500px").m-auto 
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Atención e incidentes
                  p.mb-0 Incluyen procedimientos para consultas y reclamos, así como formatos que permitan registrar y gestionar incidentes relacionados con información personal.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img24.png', alt='' style="max-width: 500px").m-auto 
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Conservación y eliminación
                  p.mb-0 Permiten definir tiempos de conservación documental y procedimientos para eliminar información de manera segura cuando ya no deba mantenerse.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img25.png', alt='' style="max-width: 500px").m-auto 
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Terceros y confidencialidad
                  p.mb-0 Comprenden la revisión de contratos con encargados del tratamiento y la formalización de acuerdos de confidencialidad cuando corresponda.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img26.png', alt='' style="max-width: 500px").m-auto 
      p.mb-5 Estas acciones fortalecen la organización documental y permiten establecer responsabilidades y procedimientos claros para el tratamiento de datos personales.
      .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
        .col
          h3 Acciones técnicas
      p.mb-5 Las #[b acciones técnicas] están relacionadas con herramientas, sistemas, accesos, seguridad digital y protección de archivos electrónicos. Son necesarias para prevenir accesos no autorizados, pérdidas, modificaciones o divulgación indebida de información. Las principales acciones pueden agruparse así:
      .bg___slider.mb-5
        .px-5
          .ajuste-slider(data-aos="zoom-in")
            SlyderA(tipo="b")
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Gestión de accesos
                  p.mb-0 Incluye la creación de perfiles según funciones, el retiro de usuarios inactivos y la revisión periódica de permisos en plataformas institucionales.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img27.png', alt='' style="max-width: 500px").m-auto 
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Autenticación
                  p.mb-0 La activación del doble factor de autenticación, cuando sea posible, fortalece el control de ingreso a sistemas que contienen información personal.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img28.png', alt='' style="max-width: 500px").m-auto 
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Copias y cifrado
                  p.mb-0 Las copias de seguridad periódicas y el cifrado de archivos con datos sensibles permiten fortalecer la disponibilidad y confidencialidad de la información.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img29.png', alt='' style="max-width: 500px").m-auto 
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Descargas y dispositivos
                  p.mb-0 Restringir descargas y controlar el uso de dispositivos externos reduce el riesgo de copias, pérdidas o traslados no autorizados de bases de datos.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img30.png', alt='' style="max-width: 500px").m-auto 
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Carpetas y registros de acceso
                  p.mb-0 Las carpetas compartidas deben protegerse mediante permisos, y los accesos a bases críticas pueden registrarse para facilitar el seguimiento.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img31.png', alt='' style="max-width: 500px").m-auto 
      p.mb-5 Estas medidas complementan las acciones administrativas y permiten fortalecer la seguridad de la información almacenada o tratada mediante recursos tecnológicos.
      .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
        .col
          h3 Acciones de capacitación
      p Las #[b acciones de capacitación] buscan fortalecer el conocimiento y la responsabilidad del personal que maneja datos personales. Muchas fallas pueden producirse por desconocimiento, descuido o uso inadecuado de la información.
      p.mb-5 La capacitación debe ser práctica y estar relacionada con las funciones de cada área. No basta con explicar la norma; también es necesario presentar casos, riesgos y buenas prácticas aplicables al trabajo diario. Los contenidos pueden agruparse en los siguientes ejes:
      .bg___carrusel
        .px-5
          SlyderF(columnas="col-lg-6 col-xl-4")(data-aos="zoom-in").mb-5
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t5/img32.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Principios y derechos
              p.mb-0.text-center Incluye los principios de protección de datos personales y los derechos de los titulares para que el personal comprenda las bases del tratamiento responsable.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t5/img33.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Autorizaciones y finalidades
              p.mb-0.text-center Permite fortalecer la comprensión sobre la relación entre la autorización otorgada, la finalidad informada y el uso permitido de los datos.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t5/img34.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Datos sensibles y menores de edad
              p.mb-0.text-center Aborda las condiciones especiales de manejo de información que requiere mayores medidas de protección y confidencialidad.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t5/img35.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Seguridad y confidencialidad
              p.mb-0.text-center Incluye buenas prácticas para el uso de bases de datos, manejo de información reservada y protección de archivos, formularios y correos electrónicos.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t5/img36.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Solicitudes e incidentes
              p.mb-0.text-center Permite orientar al personal sobre la atención de consultas y reclamos, así como sobre el reporte oportuno de incidentes relacionados con datos personales.
          p.mb-0 La capacitación periódica contribuye a que las medidas establecidas por la organización se incorporen a las actividades cotidianas del personal encargado del tratamiento de datos.
          Separador
          #t_5_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
            h2 5.3 Presentación del plan de protección de datos
          p.mb-5 La #[b presentación del plan de protección de datos] permite comunicar los resultados del diagnóstico y las acciones de mejora propuestas. Esta presentación debe ser clara, organizada y comprensible para las personas responsables de tomar decisiones dentro de la organización.
          .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
            .bloque-texto-g__img(
              :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/t5/img37.jpg')})` }")
            .bloque-texto-g__texto.p-4
              p El plan debe incluir los hallazgos principales, los riesgos identificados, las acciones priorizadas, los responsables, los tiempos de ejecución y las evidencias esperadas. También debe explicar por qué las acciones propuestas contribuyen a prevenir sanciones, proteger los derechos de los titulares y mejorar la gestión interna.
      p.mb-5 Una presentación organizada del plan facilita la aprobación de recursos, la asignación de responsabilidades y el seguimiento de las acciones. Además, permite que las diferentes áreas comprendan su papel en la protección de datos personales.
      .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
        .col
          h3 Estructura del plan de mejora
      p.mb-5 El #[b plan de mejora] debe tener una estructura sencilla y funcional que permita comprender el diagnóstico, las acciones propuestas y el seguimiento correspondiente. La estructura básica puede incluir los siguientes componentes:
      .bg___slider.mb-5
        .px-5
          .ajuste-slider(data-aos="zoom-in")
            SlyderA(tipo="b")
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Objetivo del plan
                  p.mb-0 Define qué se busca mejorar mediante la implementación del plan y orienta las acciones relacionadas con la protección de datos personales.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img38.png', alt='' style="max-width: 500px").m-auto 
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Alcance del plan
                  p.mb-0 Precisa las áreas, procesos o bases de datos que serán intervenidos y delimita el campo de aplicación de las acciones propuestas.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img39.png', alt='' style="max-width: 500px").m-auto 
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Resumen del diagnóstico
                  p.mb-0 Integra los principales resultados obtenidos durante la revisión de bases de datos, autorizaciones, políticas, controles, solicitudes, incidentes y riesgos.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img40.png', alt='' style="max-width: 500px").m-auto 
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Hallazgos principales
                  p.mb-0 Reúne las situaciones que requieren atención y que sirven como punto de partida para establecer las acciones de mejora.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img41.png', alt='' style="max-width: 500px").m-auto 
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Riesgos identificados
                  p.mb-0 Contiene los riesgos asociados con los hallazgos y permite establecer su nivel de atención de acuerdo con la probabilidad, el impacto y el tipo de datos involucrados.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img42.png', alt='' style="max-width: 500px").m-auto 
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Acciones de mejora
                  p.mb-0 Define las actividades concretas que se implementarán para corregir debilidades, reducir riesgos y fortalecer los controles existentes.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img43.png', alt='' style="max-width: 500px").m-auto 
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Responsables
                  p.mb-0 Identifica las áreas o personas encargadas de ejecutar, coordinar o realizar seguimiento a cada acción definida.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img44.png', alt='' style="max-width: 500px").m-auto 
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Plazos
                  p.mb-0 Establece los tiempos previstos para desarrollar las acciones y permite organizar su ejecución en el corto, mediano o largo plazo.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img45.png', alt='' style="max-width: 500px").m-auto 
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Evidencias esperadas
                  p.mb-0 Precisa los soportes físicos o digitales que permitirán demostrar la implementación y cumplimiento de las acciones propuestas.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img46.png', alt='' style="max-width: 500px").m-auto 
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Indicadores de seguimiento
                  p.mb-0 Permite medir el avance de las acciones y determinar si las medidas implementadas contribuyen a reducir los riesgos identificados.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img47.png', alt='' style="max-width: 500px").m-auto 
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Recomendaciones finales
                  p.mb-0 Integra orientaciones para mantener las acciones implementadas y fortalecer de manera continua la protección de datos personales.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t5/img48.png', alt='' style="max-width: 500px").m-auto 
      p.mb-5 Esta estructura permite relacionar el diagnóstico con las acciones, responsables, plazos y evidencias necesarias para facilitar la ejecución y el seguimiento del plan.
      .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
        .col
          h3 Recomendaciones organizacionales
      p.mb-5 Las #[b recomendaciones organizacionales] son orientaciones que ayudan a mantener y fortalecer la protección de datos personales. Estas deben ser realistas y adaptarse al contexto de la entidad. Las recomendaciones pueden agruparse por su propósito:
      .bg___carrusel
        .px-5
          SlyderF(columnas="col-lg-6 col-xl-4")(data-aos="zoom-in").mb-5
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t5/img49.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Actualización de información y documentos
              p.mb-0.text-center Mantener actualizado el inventario de bases de datos y revisar periódicamente las autorizaciones, finalidades y documentos asociados con el tratamiento.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t5/img50.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Formación del personal
              p.mb-0.text-center Capacitar de manera periódica a las personas que manejan información personal para fortalecer el conocimiento de sus responsabilidades.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t5/img51.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Control de accesos
              p.mb-0.text-center Restringir los accesos físicos y digitales de acuerdo con las funciones y revisar periódicamente los permisos otorgados.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t5/img52.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Evidencias y atención de titulares
              p.mb-0.text-center Conservar soportes de cumplimiento y atender oportunamente las solicitudes presentadas por los titulares.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t5/img53.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Incidentes y depuración
              p.mb-0.text-center Registrar los incidentes, aplicar acciones correctivas y depurar la información que haya dejado de ser necesaria.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t5/img54.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Terceros y evaluación de controles
              p.mb-0.text-center Revisar los contratos con terceros que traten datos y evaluar periódicamente la efectividad de los controles implementados.
          p.mb-5 Estas recomendaciones deben integrarse a la gestión diaria de la organización. La protección de datos personales no debe asumirse como una actividad aislada, sino como parte de los procesos administrativos, tecnológicos, jurídicos y operativos.
          .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
            .col-lg-auto
              figure
                img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
            .col
              h3 Seguimiento y mejora continua
          p.mb-5 El #[b seguimiento y la mejora continua] permiten determinar si las acciones definidas fueron implementadas y si contribuyeron a reducir los riesgos identificados. Sin un seguimiento periódico, el plan puede convertirse en un documento sin aplicación práctica. Para realizar el seguimiento, pueden utilizarse indicadores asociados con diferentes aspectos de la gestión:
          .bg___slider.mb-5
            .px-5
              .ajuste-slider(data-aos="zoom-in")
                SlyderA(tipo="b")
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Autorizaciones
                      p.mb-0 El número de autorizaciones actualizadas permite establecer el avance en la revisión y ajuste de los soportes relacionados con el tratamiento de datos.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t5/img55.png', alt='' style="max-width: 500px").m-auto 
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Capacitación
                      p.mb-0 La cantidad de personas capacitadas permite realizar seguimiento a la cobertura de las actividades dirigidas al personal.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t5/img56.png', alt='' style="max-width: 500px").m-auto 
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Inventario de bases de datos
                      p.mb-0 El porcentaje de bases inventariadas permite determinar el nivel de avance en la identificación y organización de la información tratada.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t5/img57.png', alt='' style="max-width: 500px").m-auto 
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Control de accesos
                      p.mb-0 El número de accesos revisados permite realizar seguimiento a la actualización de permisos y perfiles asignados.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t5/img58.png', alt='' style="max-width: 500px").m-auto 
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Solicitudes de titulares
                      p.mb-0 La cantidad de solicitudes atendidas permite controlar la gestión de consultas, actualizaciones, supresiones u otras peticiones relacionadas con datos personales.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t5/img59.png', alt='' style="max-width: 500px").m-auto 
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Incidentes
                      p.mb-0 El número de incidentes registrados y cerrados permite identificar situaciones reportadas y determinar su nivel de gestión.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t5/img60.png', alt='' style="max-width: 500px").m-auto 
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Actualización documental
                      p.mb-0 La cantidad de políticas o formatos actualizados permite realizar seguimiento a las acciones administrativas definidas en el plan.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t5/img61.png', alt='' style="max-width: 500px").m-auto 
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Cumplimiento del plan
                      p.mb-0 El número de acciones de mejora cumplidas permite determinar el avance general de las actividades programadas.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t5/img62.png', alt='' style="max-width: 500px").m-auto
      p.mb-0 La #[b mejora continua] implica revisar periódicamente el plan, ajustar las acciones, actualizar los controles y responder a nuevos riesgos. Cada vez que cambien los procesos, las herramientas, las finalidades o las bases de datos, el plan debe actualizarse para mantener su pertinencia y fortalecer de manera permanente la protección de la información personal.

</template>

<script>
export default {
  name: 'Tema5',
  data: () => ({
    // variables de vue
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

<style lang="sass"></style>
