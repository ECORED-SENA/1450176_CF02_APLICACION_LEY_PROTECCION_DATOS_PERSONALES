<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido(data-aos="flip-up")
        .titulo-principal__numero
          span 3
        h1 Gestión de solicitudes, incidentes y riesgos
      .row.align-items-center.mb-3
        .col-xl
          .box___style_1.color___1(data-aos="flip-up").mb-3
            p.mb-0 La #[b gestión de solicitudes, incidentes y riesgos] permite que la organización responda de manera ordenada ante situaciones relacionadas con los derechos de los titulares, las fallas en la seguridad de la información o los posibles incumplimientos en el tratamiento de datos personales. Este proceso es necesario para demostrar responsabilidad, prevenir sanciones y proteger la información durante todo su ciclo de vida.
          p.mb-0 Una organización no solo debe recolectar y almacenar datos de manera adecuada; también debe contar con procedimientos para atender consultas, corregir información, suprimir datos cuando corresponda, reportar novedades internas y aplicar acciones de mejora.
        .col-xl-auto.d-none.d-xl-block(data-aos="zoom-in")
          figure
            img(src='@/assets/curso/temas/t3/img1.png', alt='' style="width: 400px").m-auto
      .bg___color_1
        .px-5
          p.mb-0 La gestión de solicitudes, incidentes y riesgos debe integrarse con las políticas internas de tratamiento de datos, los controles administrativos, técnicos y físicos, y las responsabilidades asignadas a cada área. De esta manera, se evita actuar de forma improvisada cuando un titular presenta una petición o cuando ocurre una situación que compromete la seguridad de la información.
          Separador
          #t_3_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
            h2 3.1 Atención de derechos de los titulares
          p La #[b atención de derechos de los titulares] consiste en recibir, analizar y responder las solicitudes que realizan las personas sobre sus datos personales. Estos derechos permiten que el titular conozca qué información tiene la organización, solicite su actualización o rectificación, pida la supresión cuando sea procedente o revoque la autorización otorgada para determinadas finalidades.
          p.mb-5 Para atender estos derechos, la organización debe contar con canales claros, responsables definidos, tiempos de respuesta y evidencias de la gestión realizada. No es suficiente recibir la solicitud; también se debe registrar, revisar, responder y conservar el soporte de la atención brindada.
          .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
            .bloque-texto-g__img(
              :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/t3/img2.jpg')})` }")
            .bloque-texto-g__texto.p-4
              p Los canales de atención pueden incluir correo electrónico, formularios web, línea telefónica, oficina de atención, ventanilla física o sistema de gestión de solicitudes. Lo importante es que el titular conozca dónde puede presentar su petición y que la organización disponga de un procedimiento para tramitarla.
          .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
            .col-lg-auto
              figure
                img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
            .col
              h3 Solicitudes de consulta
          p Las #[b solicitudes de consulta] permiten al titular conocer qué datos personales tiene la organización, para qué los utiliza, de dónde provienen, con quién se comparten y bajo qué condiciones se tratan. Este tipo de solicitud es frecuente cuando una persona desea determinar si su información está registrada o si se utiliza para una finalidad determinada.
          .row.align-items-center.mb-5
            .col-xl
              p.mb-0 Para atender una consulta, la organización debe validar la identidad del solicitante, ubicar la información en sus bases de datos, revisar la finalidad del tratamiento y entregar una respuesta clara. La respuesta no debe incluir datos de otras personas ni información que pueda vulnerar los derechos de terceros. Una solicitud de consulta puede relacionarse con preguntas como:
            .col-xl-auto.d-none.d-xl-block(data-aos="zoom-in")
              figure
                img(src='@/assets/curso/temas/t3/img3.svg', alt='' style="width: 190px").m-auto
          .row.justify-content-center.mb-5
            .col-xl-2.col-md-9.mb-4.mb-lg-0(data-aos="zoom-in")
              .style___tarjeta_rob.h-100
                .p-4
                  p.mb-0.text-center ¿Qué datos personales tiene registrados la organización? 
            .col-xl-2.col-md-9.mb-4.mb-lg-0(data-aos="zoom-in")
              .style___tarjeta_rob.h-100
                .p-4
                  p.mb-0.text-center ¿Para qué se utilizan los datos? 
            .col-xl-2.col-md-9.mb-4.mb-lg-0(data-aos="zoom-in")
              .style___tarjeta_rob.h-100
                .p-4
                  p.mb-0.text-center ¿Quién es el responsable del tratamiento? 
            .col-xl-2.col-md-9.mb-4.mb-lg-0(data-aos="zoom-in")
              .style___tarjeta_rob.h-100
                .p-4
                  p.mb-0.text-center ¿La información ha sido compartida con terceros? 
            .col-xl-2.col-md-9.mb-4.mb-lg-0(data-aos="zoom-in")
              .style___tarjeta_rob.h-100
                .p-4
                  p.mb-0.text-center ¿Cuál es la política de tratamiento aplicable? 
            .col-xl-2.col-md-9(data-aos="zoom-in")
              .style___tarjeta_rob.h-100
                .p-4
                  p.mb-0.text-center ¿Qué autorización respalda el tratamiento? 
      p.mb-5 Atender correctamente las consultas fortalece la transparencia y permite que el titular tenga mayor control sobre su información.
      .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
        .col
          h3 Actualización y rectificación de datos
      p La #[b actualización y rectificación de datos] se presenta cuando el titular solicita corregir información incompleta, inexacta, desactualizada o equivocada. Este derecho es importante porque la información incorrecta puede generar errores en comunicaciones, trámites, pagos, certificaciones, reportes, servicios o decisiones administrativas.
      p.mb-5 Por ejemplo, un titular puede solicitar la corrección de su número de identificación, dirección, correo electrónico, teléfono, nombre, estado contractual o información asociada a un registro. La organización debe analizar la solicitud, requerir soportes cuando sea necesario y actualizar la base de datos correspondiente.
      .row.justify-content-center.mb-5
        .col-xl-10
          .box___style_2(data-aos="zoom-in")
            .row.align-items-center
              .col-xl-auto
                figure
                  img(src='@/assets/curso/temas/t3/img4.jpg', alt='' style="width: 400px").m-auto
              .col-xl.fit___box_container
                p Para gestionar este tipo de solicitudes, se recomienda:
                ul.fa-ul.estilo___ul.mb-0
                  li.mb-0
                    span.fa-li
                      i.fas.fa-check-circle
                    | Validar la identidad del titular. 
                  li.mb-0
                    span.fa-li
                      i.fas.fa-check-circle
                    | Identificar la base de datos donde se encuentra el registro. 
                  li.mb-0
                    span.fa-li
                      i.fas.fa-check-circle
                    | Verificar el dato que debe actualizarse o corregirse. 
                  li.mb-0
                    span.fa-li
                      i.fas.fa-check-circle
                    | Solicitar soporte cuando aplique. 
                  li.mb-0
                    span.fa-li
                      i.fas.fa-check-circle
                    | Realizar la modificación en los sistemas o archivos correspondientes. 
                  li.mb-0
                    span.fa-li
                      i.fas.fa-check-circle
                    | Informar al titular sobre la actualización realizada. 
                  li.mb-0
                    span.fa-li
                      i.fas.fa-check-circle
                    | Conservar evidencia de la solicitud y de la respuesta. 
      p.mb-5 La actualización oportuna de la información contribuye a mantener bases de datos confiables y reduce los riesgos derivados del uso de datos erróneos.
      .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
        .col
          h3 Supresión y revocatoria de autorización
      p.mb-5 La #[b supresión] y la #[b revocatoria de autorización] son mecanismos relacionados con el control que ejerce el titular sobre sus datos personales. Aunque pueden estar vinculados dentro de una misma solicitud, responden a situaciones diferentes y requieren un análisis previo por parte de la organización. Las principales diferencias pueden organizarse de la siguiente manera:
      .row.align-items-center.mb-5
        .col-xl-auto(data-aos="fade-right")
          figure.d-none.d-xl-block
            img(src="@/assets/curso/temas/t2/img14.png", alt="" style="width: 400px").m-auto
        .col-xl
          AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")(data-aos="fade-left")
            .row(titulo="Supresión de datos").ajuste-cajaAcordion.ajuste-vineta
              p.mb-3 Consiste en eliminar datos personales cuando ya no son necesarios, se han tratado de forma indebida o el titular solicita su eliminación y no existe una obligación legal o contractual que exija conservarlos.
            .row(titulo="Revocatoria de autorización").ajuste-cajaAcordion.ajuste-vineta
              p.mb-3 Se presenta cuando el titular decide retirar el permiso otorgado para una o varias finalidades de tratamiento. Su aplicación depende de la finalidad involucrada y de las obligaciones que justifiquen la conservación de determinados datos.
            .row(titulo="Conservación justificada").ajuste-cajaAcordion.ajuste-vineta
              p.mb-3 Una solicitud de supresión no implica necesariamente la eliminación inmediata. La organización debe determinar si existen obligaciones legales, contractuales, contables, laborales, administrativas o de defensa jurídica que requieran conservar la información.
            .row(titulo="Revocatoria por finalidad").ajuste-cajaAcordion.ajuste-vineta
              p.mb-3 El titular puede retirar su autorización para una finalidad específica, como recibir comunicaciones comerciales, sin que esto implique necesariamente eliminar información requerida para cumplir obligaciones contractuales o legales.
      p.mb-0 Por lo tanto, antes de atender una solicitud de supresión o revocatoria, la organización debe analizar la finalidad del tratamiento, las obligaciones aplicables y las condiciones que justifican la conservación de la información.
      .bg___color_1
        .px-5
          Separador
          #t_3_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
            h2 3.2 Gestión de incidentes de seguridad
          p.mb-5 Un #[b incidente de seguridad] es cualquier situación que pueda afectar la confidencialidad, integridad o disponibilidad de los datos personales. Puede presentarse por pérdida de documentos, acceso no autorizado, envío equivocado de información, robo de equipos, eliminación accidental, divulgación indebida, errores en sistemas o uso de canales inseguros.
          .row.align-items-center.mb-5
            .col-xl
              p Gestionar incidentes no significa únicamente reaccionar cuando el problema ya ocurrió. También implica identificar señales de alerta, registrar lo sucedido, evaluar el impacto, aplicar acciones correctivas y prevenir que la situación se repita.
              p.mb-0 La gestión de incidentes debe ser conocida por las áreas que manejan información personal. Cuando una persona detecta una novedad, debe saber a quién reportarla, qué información debe suministrar y qué acciones debe evitar para no agravar la situación.
            .col-xl-auto.d-none.d-xl-block(data-aos="zoom-in")
              figure
                img(src='@/assets/curso/temas/t3/img5.svg', alt='' style="width: 190px").m-auto
          .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
            .col-lg-auto
              figure
                img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
            .col
              h3 Identificación de incidentes
          p.mb-5 La #[b identificación de incidentes] consiste en reconocer situaciones que pueden comprometer los datos personales. Algunas son evidentes, como la pérdida de un computador o el envío de una base de datos a un destinatario equivocado. Otras pueden ser menos evidentes, como accesos no autorizados, permisos excesivos o documentos expuestos en zonas comunes. Los incidentes pueden agruparse según la situación que compromete la información:
          .bg___slider.mb-5
            .px-5
              .ajuste-slider(data-aos="zoom-in")
                SlyderA(tipo="b")
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Pérdida o robo de equipos
                      p.mb-0 Se presenta cuando computadores, dispositivos o soportes que contienen información personal quedan fuera del control de la organización, lo que puede facilitar accesos no autorizados.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t3/img6.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Envíos equivocados
                      p.mb-0 Ocurre cuando correos electrónicos, archivos o documentos con datos personales son remitidos a destinatarios incorrectos, generando una posible divulgación de información.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t3/img7.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Acceso no autorizado
                      p.mb-0 Se produce cuando una persona consulta bases de datos, documentos o sistemas sin contar con los permisos correspondientes o sin que exista una necesidad asociada con sus funciones.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t3/img8.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Publicación o exposición indebida
                      p.mb-0 Comprende situaciones en las que listados, contratos, historias laborales u otra información personal quedan disponibles en espacios físicos o digitales sin autorización.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t3/img9.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Eliminación accidental
                      p.mb-0 Se presenta cuando registros o archivos son borrados sin intención y pueden afectar la disponibilidad de la información necesaria para los procesos de la organización.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t3/img10.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Descarga o traslado no autorizado
                      p.mb-0 Incluye la descarga de bases de datos o el uso de memorias personales para transportar información sin los controles definidos por la organización.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t3/img11.png', alt='' style="max-width: 500px").m-auto
      p.mb-5 La identificación temprana permite actuar de manera oportuna y reducir el impacto sobre los titulares y la organización.
      .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
        .col
          h3 Registro y reporte interno
      p Todo incidente debe registrarse, incluso cuando parezca menor. El registro permite establecer qué ocurrió, cuándo sucedió, qué información estuvo comprometida, quién lo detectó, qué áreas participaron y qué acciones se adoptaron.
      p.mb-5 El reporte interno debe dirigirse al área o persona responsable definida por la organización. Esta función puede corresponder al área de sistemas, jurídica, administrativa, talento humano, seguridad de la información o al responsable designado para la protección de datos. Un registro básico de incidentes debe contener información suficiente para facilitar su análisis y seguimiento:
      .bg___carrusel
        .px-5
          SlyderF(columnas="col-lg-6 col-xl-4")(data-aos="zoom-in").mb-5
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t3/img12.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Fecha y hora de detección
              p.mb-0.text-center Permite establecer cuándo fue identificado el incidente y facilita reconstruir la secuencia de los hechos relacionados con la situación.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t3/img13.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Área y persona que reporta
              p.mb-0.text-center Identifica el proceso donde ocurrió el incidente y la persona que informó la situación, lo que facilita la comunicación durante el seguimiento.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t3/img14.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Descripción del incidente
              p.mb-0.text-center Precisa qué sucedió, cómo se detectó y cuáles fueron las circunstancias asociadas con el evento. Debe redactarse de forma clara y objetiva.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t3/img15.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Datos y titulares involucrados
              p.mb-0.text-center Permite identificar el tipo de información comprometida y estimar el número de titulares que podrían resultar afectados.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t3/img16.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Acciones inmediatas
              p.mb-0.text-center Registra las medidas adoptadas para contener la situación, proteger la información y evitar que el incidente continúe generando efectos.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t3/img17.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Responsable y estado del caso
              p.mb-0.text-center Permite asignar el seguimiento a una persona o área y establecer si el incidente se encuentra abierto, en análisis o cerrado.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t3/img18.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Acciones correctivas o preventivas
              p.mb-0.text-center Documenta las medidas definidas para corregir las consecuencias del incidente y reducir la posibilidad de que una situación similar se repita.
          p.mb-5 Registrar los incidentes permite identificar patrones y fortalecer los controles. Si una misma situación se repite, puede ser una señal de falta de capacitación, fallas en los procedimientos, permisos inadecuados o ausencia de controles técnicos.
          .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
            .col-lg-auto
              figure
                img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
            .col
              h3 Acciones correctivas y preventivas
          p.mb-5 Las #[b acciones correctivas] buscan solucionar una situación que ya ocurrió, mientras que las #[b acciones preventivas] están orientadas a reducir la posibilidad de que el incidente se repita. Ambas son necesarias para fortalecer la protección de datos personales. La diferencia entre estos dos tipos de acciones puede comprenderse mediante situaciones concretas:
          .row.justify-content-center.mb-5
            .col-xl-4.col-md-9.mb-4.mb-lg-0(data-aos="fade-right")
              .box___card_sinbordes.h-100
                .row.justify-content-center.mb-3
                  .col-12
                    figure.mb-4
                      img(src='@/assets/curso/temas/t3/img19.png', alt="" ).m-auto
                  h4.text-center Envío de información a un destinatario equivocado
                  .box___card_sinbordes_p
                    p.mb-0.text-center Como acción correctiva, puede solicitarse la eliminación del mensaje, registrar el incidente y realizar el reporte interno. Como acción preventiva, pueden establecerse revisiones previas de destinatarios, restricciones en envíos masivos o actividades de capacitación.
            .col-xl-4.col-md-9.mb-4.mb-lg-0(data-aos="zoom-in")
              .box___card_sinbordes.h-100
                .row.justify-content-center.mb-3
                  .col-12
                    figure.mb-4
                      img(src='@/assets/curso/temas/t3/img20.png', alt="" ).m-auto
                  h4.text-center Pérdida de una carpeta con hojas de vida
                  .box___card_sinbordes_p
                    p.mb-0.text-center La acción correctiva puede orientarse a identificar la información comprometida y procurar su recuperación. Como prevención, pueden aplicarse controles de préstamo, archivadores cerrados y responsables de custodia.
            .col-xl-4.col-md-9(data-aos="fade-left")
              .box___card_sinbordes.h-100
                .row.justify-content-center.mb-3
                  .col-12
                    figure.mb-4
                      img(src='@/assets/curso/temas/t3/img21.png', alt="" ).m-auto
                  h4.text-center Acceso indebido a una base de datos
                  .box___card_sinbordes_p
                    p.mb-0.text-center La acción correctiva puede consistir en retirar el acceso no autorizado y analizar la información comprometida. La acción preventiva puede incluir la revisión de perfiles y permisos asignados.
      p.mb-0 Las acciones deben ser proporcionales al riesgo. Un incidente que involucre datos sensibles, información de menores de edad o un gran volumen de titulares requiere mayor atención que un error menor sin exposición real de información.
      Separador
      #t_3_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
        h2 3.3 Análisis de riesgos legales
      p El #[b análisis de riesgos legales] permite identificar situaciones que pueden generar incumplimientos relacionados con el tratamiento de datos personales. Estos riesgos pueden derivarse de recolectar datos sin autorización, utilizar información para finalidades no informadas, compartir datos con terceros sin soporte, conservar información innecesaria o no atender solicitudes de los titulares.
      p.mb-5 Este análisis ayuda a priorizar acciones de mejora. No todos los riesgos tienen el mismo impacto. Algunos pueden afectar únicamente un proceso interno, mientras que otros pueden comprometer los derechos de los titulares, generar reclamaciones, afectar la reputación institucional o exponer a la organización a sanciones. Para analizar los riesgos, se deben considerar tres elementos básicos:
      .row.justify-content-center.mb-5
        .col-xl-4.col-md-9.mb-4.mb-lg-0(data-aos="zoom-in")
          .card___icon.h-100
            .row.justify-content-center.mb-3
              .col-7
                figure.mb-4(data-aos="fade-right")
                  img(src='@/assets/curso/temas/t3/img22.svg', alt="" style="max-width: 90px").m-auto
              h4.text-center Probabilidad de ocurrencia
              p.mb-0.text-center Permite establecer qué tan posible es que una situación de riesgo llegue a materializarse durante el tratamiento de los datos personales.
        .col-xl-4.col-md-9.mb-4.mb-lg-0(data-aos="zoom-in")
          .card___icon.h-100
            .row.justify-content-center.mb-3
              .col-7
                figure.mb-4(data-aos="zoom-in")
                  img(src='@/assets/curso/temas/t3/img23.svg', alt="" style="max-width: 90px").m-auto
              h4.text-center Impacto
              p.mb-0.text-center Permite determinar las consecuencias que podría generar el riesgo para los titulares, los procesos internos o la organización.
        .col-xl-4.col-md-9(data-aos="zoom-in")
          .card___icon.h-100
            .row.justify-content-center.mb-3
              .col-7
                figure.mb-4(data-aos="fade-left")
                  img(src='@/assets/curso/temas/t3/img24.svg', alt="" style="max-width: 90px").m-auto
              h4.text-center Medidas de control existentes
              p.mb-0.text-center Permite establecer qué controles administrativos, técnicos o físicos se encuentran implementados para prevenir, reducir o atender el riesgo identificado.
      p.mb-5 El análisis conjunto de estos elementos facilita la priorización de los riesgos y la definición de acciones de mejora acordes con su nivel de importancia.
      .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
        .col
          h3 Riesgos por uso no autorizado
      p.mb-5 El #[b uso no autorizado] ocurre cuando los datos personales se utilizan para finalidades diferentes de las informadas o aceptadas por el titular. Este riesgo es frecuente cuando las bases de datos se comparten entre áreas sin revisión previa o cuando se utilizan registros antiguos para campañas, comunicaciones o reportes no autorizados. Las situaciones más frecuentes pueden organizarse de la siguiente manera:
      .bg___slider.mb-5
        .px-5
          .ajuste-slider(data-aos="zoom-in")
            SlyderA(tipo="b")
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Uso para una finalidad diferente
                  p.mb-0 Se presenta cuando datos recolectados para un proceso específico, como una matrícula, se utilizan posteriormente para campañas comerciales u otras actividades que no corresponden a la finalidad inicialmente informada.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t3/img25.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Comunicaciones sin autorización
                  p.mb-0 Ocurre cuando se envía publicidad, promociones u otro tipo de comunicación a titulares que no autorizaron expresamente esa finalidad.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t3/img26.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Entrega de datos a terceros
                  p.mb-0 Se configura cuando información de empleados, clientes u otros titulares se comparte con terceros sin contar con el soporte correspondiente o sin una finalidad justificada.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t3/img27.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Uso de fotografías sin autorización
                  p.mb-0 Se presenta cuando fotografías institucionales se utilizan en publicaciones, campañas u otros medios sin contar con la autorización correspondiente.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t3/img28.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Consulta sin relación funcional
                  p.mb-0 Ocurre cuando una persona accede a información personal que no necesita para desarrollar las funciones que le han sido asignadas.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t3/img29.png', alt='' style="max-width: 500px").m-auto
      p.mb-5 Para reducir este riesgo, se deben revisar las finalidades antes de utilizar una base de datos, separar las autorizaciones según el tipo de tratamiento y restringir los accesos de acuerdo con las funciones del personal.
      .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
        .col
          h3 Riesgos por divulgación indebida
      p.mb-5 A continuación, se presenta un video  que permitirá reconocer las principales situaciones que pueden generar una divulgación indebida de datos personales, así como las medidas de prevención necesarias para proteger la confidencialidad de la información.
      .row.align-items-center.m-0.mb-5
        .col-xl
          .row.align-items-center.justify-content-center.box___podcast(data-aos="zoom-in")
            .col-auto.mb-4.mb-lg-0
              figure(data-aos="fade-right")
                img(src="@/assets/curso/temas/t3/img30.svg" style="max-width: 220px").m-auto
            .col
              h4.mb-4 Pódcast
              TarjetaAudio.color-acento-contenido.mb-4(
                  texto="Riesgos por divulgación indebida"
                  :audio="audio1"
                  @audio-hover="mostrarIndicadorTarjetaAudio = false"
                )
                  .indicador--click(v-if="mostrarIndicadorTarjetaAudio")
        .col-xl-auto.d-none.d-xl-block
          figure(data-aos="fade-left")
            img(src="@/assets/curso/temas/t3/img31.png" style="max-width: 510px").m-auto
      .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
        .col
          h3 Riesgos por falta de evidencias
      p.mb-5 La #[b falta de evidencias] ocurre cuando la organización no puede demostrar que actuó correctamente frente al tratamiento de datos personales. Puede existir autorización, atención de solicitudes o aplicación de controles, pero, si no se cuenta con los soportes correspondientes, se dificulta demostrar el cumplimiento. Las principales evidencias pueden organizarse según su función:
      .bg___slider.mb-5
        .px-5
          .ajuste-slider(data-aos="zoom-in")
            SlyderA(tipo="b")
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Autorizaciones y políticas
                  p.mb-0 Las autorizaciones físicas o digitales y las políticas de tratamiento permiten sustentar las condiciones bajo las cuales la organización recolecta y utiliza los datos personales.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t3/img32.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Atención de derechos
                  p.mb-0 Los registros de consultas y reclamos, junto con los soportes de actualización o supresión, permiten documentar la forma en que la organización atiende las solicitudes de los titulares.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t3/img33.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Gestión de bases de datos
                  p.mb-0 El inventario de bases de datos permite identificar la información tratada, los procesos relacionados y las condiciones establecidas para su administración.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t3/img34.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Formación y confidencialidad
                  p.mb-0 Las actas de capacitación y los acuerdos de confidencialidad permiten sustentar las acciones realizadas para orientar al personal y definir responsabilidades frente al manejo de la información.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t3/img35.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Gestión de incidentes y controles
                  p.mb-0 Los registros de incidentes y las evidencias de controles aplicados permiten documentar las medidas utilizadas para proteger la información y atender situaciones que puedan comprometerla.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t3/img36.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Comunicaciones con titulares
                  p.mb-0 Las comunicaciones enviadas al titular permiten respaldar respuestas, informaciones y actuaciones realizadas durante la gestión de sus datos personales.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t3/img37.png', alt='' style="max-width: 500px").m-auto
      p.mb-0 Las evidencias deben conservarse de manera organizada, protegida y disponible para consulta interna cuando sean requeridas. No se trata de acumular documentos sin control, sino de conservar soportes útiles que permitan sustentar la gestión realizada.

</template>

<script>
import audio1 from '@/assets/curso/temas/t3/audios/audio-ej.mp3'
export default {
  name: 'Tema3',
  data: () => ({
    audio1,
    mostrarIndicadorTarjetaAudio: true,
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
