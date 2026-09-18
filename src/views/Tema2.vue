<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido(data-aos="flip-up")
        .titulo-principal__numero
          span 2
        h1 Controles para proteger la información personal
      .row.align-items-center.mb-5
        .col-xl
          .box___style_1.color___1(data-aos="flip-up").mb-3
            p.mb-0 Los #[b controles para proteger la información personal] son medidas que permiten reducir riesgos durante la recolección, almacenamiento, uso, circulación, consulta, conservación y eliminación de datos personales. Estos controles contribuyen a prevenir accesos no autorizados, pérdida de información, uso indebido, divulgación no permitida, modificación incorrecta o conservación de datos sin justificación.
          p.mb-0 La protección de datos personales no depende de una sola acción. Requiere combinar #[b controles administrativos, técnicos y físicos], de acuerdo con el tipo de información tratada, el nivel de riesgo, la finalidad del tratamiento y las áreas que intervienen en su manejo. Por ejemplo, una base de datos comercial requiere medidas diferentes de las aplicadas a una historia laboral, un registro médico, una hoja de vida o una base con información de menores de edad. Los tres tipos de controles cumplen funciones complementarias:
        .col-xl-auto.d-none.d-xl-block(data-aos="zoom-in")
          figure
            img(src='@/assets/curso/temas/t2/img1.png', alt='' style="width: 400px").m-auto
      .row.justify-content-center.mb-5
        .col-xl-4.col-md-9.mb-4.mb-lg-0(data-aos="fade-right")
          .box___card_sinbordes.h-100
            .row.justify-content-center.mb-3
              .col-12
                figure.mb-4
                  img(src='@/assets/curso/temas/t2/img2.png', alt="" ).m-auto
              h4.text-center Controles administrativos
              .box___card_sinbordes_p
                p.mb-0.text-center Organizan la gestión interna mediante políticas, procedimientos, responsabilidades, capacitación y mecanismos de seguimiento. Permiten establecer reglas para que el personal conozca cómo debe actuar durante el tratamiento de datos personales.
        .col-xl-4.col-md-9.mb-4.mb-lg-0(data-aos="zoom-in")
          .box___card_sinbordes.h-100
            .row.justify-content-center.mb-3
              .col-12
                figure.mb-4
                  img(src='@/assets/curso/temas/t2/img3.png', alt="" ).m-auto
              h4.text-center Controles técnicos
              .box___card_sinbordes_p
                p.mb-0.text-center Protegen la información almacenada o tratada en sistemas, equipos, aplicaciones y servicios digitales. Incluyen medidas relacionadas con autenticación, copias de seguridad, cifrado y control de accesos.
        .col-xl-4.col-md-9(data-aos="fade-left")
          .box___card_sinbordes.h-100
            .row.justify-content-center.mb-3
              .col-12
                figure.mb-4
                  img(src='@/assets/curso/temas/t2/img4.png', alt="" ).m-auto
              h4.text-center Controles físicos
              .box___card_sinbordes_p
                p.mb-0.text-center Protegen documentos, equipos, soportes y espacios donde se conserva información personal. Su aplicación busca prevenir pérdidas, sustracciones, consultas indebidas o exposición de información a personas no autorizadas.
      p.mb-0 La aplicación articulada de estos controles permite establecer quién accede a los datos, qué uso se les da, dónde se almacenan, cómo se conservan y qué acciones se adoptan cuando se presenta un incidente.
      Separador
      #t_2_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
        h2 2.1 Controles administrativos
      p.mb-5 Los #[b controles administrativos] son medidas relacionadas con la organización interna, la asignación de responsabilidades, la definición de políticas, la documentación de procedimientos y la formación del personal. Su propósito es establecer reglas claras para el manejo adecuado de los datos personales. Estos controles permiten que las personas que intervienen en el tratamiento de información conozcan qué acciones pueden realizar, cuáles deben evitar, a quién deben reportar una novedad y qué procedimiento deben seguir ante una solicitud o incidente. Sin controles administrativos, la protección de datos puede quedar sujeta a decisiones improvisadas o criterios individuales. Los principales controles administrativos pueden organizarse de la siguiente manera:
      .row.align-items-center.mb-5
        .col-xl-auto(data-aos="fade-right")
          figure.d-none.d-xl-block
            img(src="@/assets/curso/temas/t2/img5.png", alt="" style="width: 400px").m-auto
        .col-xl
          AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")(data-aos="fade-left")
            .row(titulo="Responsables de las bases de datos").ajuste-cajaAcordion.ajuste-vineta
              p.mb-3 Cada base de datos debe contar con responsables definidos para su administración, custodia y actualización. Esta asignación facilita el seguimiento y evita que la información quede bajo responsabilidades imprecisas.
            .row(titulo="Políticas y procedimientos").ajuste-cajaAcordion.ajuste-vineta
              p.mb-3 La organización debe establecer orientaciones para la recolección, uso, conservación y protección de los datos personales. Los procedimientos permiten trasladar estas orientaciones a las actividades cotidianas de cada área.
            .row(titulo="Capacitación y confidencialidad").ajuste-cajaAcordion.ajuste-vineta
              p.mb-3 El personal que maneja información personal debe conocer sus responsabilidades y las prácticas aplicables a sus funciones. Los acuerdos de confidencialidad complementan este control cuando, por las características del proceso, resulten necesarios.
            .row(titulo="Atención a titulares").ajuste-cajaAcordion.ajuste-vineta
              p.mb-3 Deben existir canales definidos para recibir y gestionar consultas o reclamos relacionados con datos personales. Estos mecanismos permiten organizar la atención y asignar responsables para su trámite.
            .row(titulo="Inventario y conservación").ajuste-cajaAcordion.ajuste-vineta
              p.mb-3 Mantener un inventario de las bases de datos permite identificar la información tratada y establecer tiempos de conservación. También facilita revisar periódicamente las autorizaciones y finalidades asociadas al tratamiento.
      p.mb-5 Estos controles proporcionan una estructura organizacional para gestionar la información personal de manera responsable.
      .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
        .col
          h3 Políticas internas de tratamiento
      .row.align-items-center.mb-5
        .col-xl
          p Las #[b políticas internas de tratamiento] son orientaciones que establecen cómo se deben recolectar, usar, almacenar, proteger y eliminar los datos personales dentro de la organización. Estas políticas deben ser claras, conocidas por el personal y coherentes con los procesos reales en los que se maneja información.
          p.mb-0 Una política interna no debe permanecer únicamente como un documento archivado. Debe servir como guía práctica para las áreas que recolectan datos, atienden solicitudes, administran bases de datos, gestionan contratos, realizan campañas o conservan documentos físicos y digitales. Para facilitar su aplicación, los elementos principales de una política pueden organizarse así:
        .col-xl-auto.d-none.d-xl-block(data-aos="zoom-in")
          figure
            img(src='@/assets/curso/temas/t2/img6.svg', alt='' style="width: 400px").m-auto
      .bg___slider.mb-5
        .px-5
          .ajuste-slider(data-aos="zoom-in")
            SlyderA(tipo="b")
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Datos y finalidades
                  p.mb-0 La política debe precisar qué datos personales trata la organización y cuáles son las finalidades asociadas con su recolección y uso. Esto permite relacionar la información solicitada con una necesidad concreta del proceso.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t2/img7.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Responsables
                  p.mb-0 Debe establecer quiénes tienen responsabilidades relacionadas con el manejo de la información. Esta definición facilita la asignación de funciones y el seguimiento de las actividades de tratamiento.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t2/img8.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Derechos y canales de atención
                  p.mb-0 Debe indicar los derechos de los titulares y los canales disponibles para presentar consultas o reclamos. Esta información facilita el ejercicio de los derechos relacionados con los datos personales.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t2/img9.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Medidas de seguridad
                  p.mb-0 La política debe incluir las medidas generales aplicadas para proteger la información durante su almacenamiento, consulta, uso y conservación, de acuerdo con las condiciones de cada proceso.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t2/img10.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Tratamientos especiales
                  p.mb-0 Cuando se manejen datos sensibles o información de menores de edad, la política debe establecer condiciones de protección acordes con las características de estos datos.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t2/img11.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Gestión de incidentes
                  p.mb-0 Debe establecer las acciones que deben realizarse ante incidentes, accesos indebidos o usos no autorizados de la información, de manera que el personal conozca cómo proceder.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t2/img12.png', alt='' style="max-width: 500px").m-auto
      p.mb-5 La política debe actualizarse cuando cambien los procesos, las finalidades, las bases de datos, los canales de atención o las formas de almacenamiento de la información.
      .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
        .col
          h3 Asignación de roles y responsabilidades
      p La #[b asignación de roles y responsabilidades] permite definir quiénes intervienen en el tratamiento de datos personales y cuáles son las funciones de cada área o persona. Esto evita confusiones y facilita el control del acceso, uso y conservación de la información.
      .row.align-items-center.mb-5
        .col-xl
          p.mb-0 En una organización pueden intervenir diferentes áreas. Por ejemplo, talento humano puede custodiar hojas de vida, contratos e incapacidades; el área comercial puede administrar datos de clientes; sistemas puede controlar accesos y respaldos; el área jurídica puede revisar autorizaciones y políticas; y atención al usuario puede recibir consultas o reclamos de los titulares. La distribución de responsabilidades puede estructurarse de acuerdo con las principales actividades del tratamiento:
        .col-xl-auto.d-none.d-xl-block(data-aos="zoom-in")
          figure
            img(src='@/assets/curso/temas/t2/img13.svg', alt='' style="width: 400px").m-auto
      .bg___carrusel
        .px-5
          .row.align-items-center.mb-5
            .col-xl-4(data-aos="fade-right")
              figure.d-none.d-xl-block
                img(src='@/assets/curso/temas/t2/img14.png', alt='' style="max-width: 400px").m-auto
            .col-xl-8(data-aos="fade-left")
              SlyderF(columnas="col-lg-6 col-xl-6")
                .tarjeta.color-acento-botones.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/temas/t2/img15.svg' style="max-width: 90px").m-auto
                  h4.mb-3.estilo-text Administración de bases de datos
                  p.mb-0.text-center Requiere definir quién es responsable de cada base y quiénes están autorizados para consultar o gestionar su información. Esto permite relacionar el acceso con las funciones asignadas.
                .tarjeta.color-acento-botones.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/temas/t2/img16.svg' style="max-width: 90px").m-auto
                  h4.mb-3.estilo-text Conservación de autorizaciones
                  p.mb-0.text-center Debe establecerse el área encargada de custodiar las evidencias físicas o digitales mediante las cuales se respalda la autorización del titular.
                .tarjeta.color-acento-botones.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/temas/t2/img17.svg' style="max-width: 90px").m-auto
                  h4.mb-3.estilo-text Atención de solicitudes
                  p.mb-0.text-center Una persona o equipo debe asumir la gestión de las solicitudes presentadas por los titulares y conservar los soportes correspondientes a la atención realizada.
                .tarjeta.color-acento-botones.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/temas/t2/img18.svg' style="max-width: 90px").m-auto
                  h4.mb-3.estilo-text Reporte de incidentes
                  p.mb-0.text-center Debe existir un responsable o canal definido para recibir y gestionar los reportes relacionados con pérdida, acceso indebido, divulgación u otras situaciones que comprometan información personal.
                .tarjeta.color-acento-botones.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/temas/t2/img19.svg' style="max-width: 90px").m-auto
                  h4.mb-3.estilo-text Actualización y depuración
                  p.mb-0.text-center Es necesario establecer quiénes pueden actualizar, corregir o depurar las bases de datos, de manera que estas actividades se realicen bajo responsabilidades previamente asignadas.
                .tarjeta.color-acento-botones.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/temas/t2/img20.svg' style="max-width: 90px").m-auto
                  h4.mb-3.estilo-text Entrega de información a terceros
                  p.mb-0.text-center El acceso o intercambio de datos con terceros debe quedar limitado al personal autorizado y responder a una necesidad relacionada con el tratamiento de la información.
          p.mb-5 Cuando los roles no están definidos, aumenta el riesgo de acceso indebido, duplicidad de información, pérdida de soportes, demoras en la atención de solicitudes o uso de datos para finalidades no autorizadas.
          .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
            .col-lg-auto
              figure
                img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
            .col
              h3 Acuerdos de confidencialidad
          p Los #[b acuerdos de confidencialidad] son compromisos mediante los cuales una persona reconoce su deber de proteger la información a la que tiene acceso durante el desarrollo de sus funciones. Estos acuerdos pueden aplicarse a trabajadores, contratistas, proveedores, practicantes o terceros que manejen datos personales.
          p.mb-5 La confidencialidad no implica únicamente abstenerse de divulgar información. También comprende evitar el uso indebido de los datos, no copiarlos sin autorización, no compartirlos mediante canales inseguros, no almacenarlos en dispositivos personales sin permiso y no consultarlos cuando no exista una necesidad relacionada con la función asignada. Los principales compromisos pueden organizarse de la siguiente manera:
      .bg___slider.mb-5
        .px-5
          .ajuste-slider(data-aos="zoom-in")
            SlyderA(tipo="b")
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Uso autorizado
                  p.mb-0 La información debe utilizarse exclusivamente para las finalidades relacionadas con las funciones o actividades autorizadas. El acceso a los datos no habilita su utilización para propósitos personales o diferentes de los establecidos.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t2/img21.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Reserva de la información
                  p.mb-0 Los datos no deben compartirse con personas no autorizadas. Este compromiso comprende tanto la comunicación directa como la entrega de documentos, archivos o accesos a terceros.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t2/img22.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Protección de documentos y archivos
                  p.mb-0 La persona debe proteger los documentos físicos y digitales a los que tenga acceso y evitar prácticas que puedan facilitar su pérdida, copia o divulgación indebida.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t2/img23.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Reporte de incidentes
                  p.mb-0 Las pérdidas, accesos indebidos o incidentes relacionados con información personal deben reportarse mediante los mecanismos definidos por la organización.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t2/img24.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Finalización de la relación
                  p.mb-0 Cuando termine una relación laboral o contractual, la información debe devolverse o eliminarse según corresponda, manteniendo la reserva incluso después de finalizar las funciones.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t2/img25.png', alt='' style="max-width: 500px").m-auto
      p.mb-0 Este tipo de control fortalece la responsabilidad individual y reduce los riesgos asociados con el manejo informal de datos personales.
      Separador
      #t_2_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
        h2 2.2 Controles técnicos
      .bg___color_1
        .px-5
          p Los #[b controles técnicos] son medidas apoyadas en herramientas, configuraciones, sistemas o recursos tecnológicos que permiten proteger la información personal en ambientes digitales. Su propósito es prevenir accesos no autorizados, pérdida de datos, alteraciones, filtraciones o usos indebidos de los sistemas en los que se almacena información.
          p Estos controles son especialmente importantes cuando los datos se encuentran en plataformas, computadores, correos electrónicos, aplicaciones, servidores, sistemas de información, hojas de cálculo compartidas, formularios web o servicios en la nube.
          p.mb-5 Los controles técnicos deben ajustarse al nivel de riesgo. Una base con datos de contacto puede requerir controles básicos, mientras que una base con información laboral, datos sensibles o datos de menores de edad requiere medidas más estrictas.
          .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
            .col-lg-auto
              figure
                img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
            .col
              h3 Contraseñas y autenticación
          p.mb-5 Las #[b contraseñas] constituyen una primera barrera para prevenir accesos no autorizados a sistemas, equipos o archivos que contienen datos personales. Sin embargo, una contraseña débil, compartida o repetida puede convertirse en un riesgo para la organización.
          .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
            .bloque-texto-g__img(
              :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/t2/img26.jpg')})` }")
            .bloque-texto-g__texto.p-4
              p Una buena práctica consiste en utilizar contraseñas robustas, cambiarlas cuando sea necesario y evitar compartirlas mediante mensajes, correos electrónicos o documentos expuestos. También se recomienda asignar usuarios individuales, debido a que esta medida permite identificar quién accede a la información y qué acciones realiza. Las prácticas relacionadas con contraseñas y autenticación pueden organizarse así:
          .bg___slider.mb-5
            .px-5
              .ajuste-slider(data-aos="zoom-in")
                SlyderA(tipo="b")
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Contraseñas diferenciadas
                      p.mb-0 Utilizar contraseñas diferentes para cada sistema disminuye el riesgo de que el acceso comprometido a una herramienta facilite el ingreso a otros recursos de la organización.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t2/img27.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Claves seguras
                      p.mb-0 Deben evitarse claves simples basadas en fechas, nombres o números consecutivos. Las contraseñas deben contribuir a reducir la posibilidad de accesos no autorizados.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t2/img28.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Usuarios individuales
                      p.mb-0 Los usuarios y contraseñas no deben compartirse. La asignación individual permite relacionar los accesos y las acciones realizadas con una persona determinada.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t2/img29.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Doble factor de autenticación
                      p.mb-0 Cuando sea posible, este mecanismo complementa la contraseña con una segunda forma de autenticación y fortalece el control de ingreso a los sistemas.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t2/img30.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Gestión de accesos
                      p.mb-0 Las contraseñas deben cambiarse ante sospechas de acceso indebido y los permisos deben retirarse cuando una persona deje de participar en el proceso correspondiente.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t2/img31.png', alt='' style="max-width: 500px").m-auto
      p.mb-5 La #[b autenticación] permite confirmar la identidad de quien ingresa a un sistema. Cuanto más sensible sea la información, mayor debe ser el nivel de control aplicado para acceder a ella.
      .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
        .col
          h3 Copias de seguridad y cifrado
      p Las #[b copias de seguridad] permiten recuperar información en caso de pérdida, daño, eliminación accidental, falla tecnológica o incidente de seguridad. Son necesarias para garantizar la continuidad de los procesos y evitar que la organización dependa de un único archivo o dispositivo.
      .row.align-items-center.mb-5
        .col-xl
          p Una copia de seguridad debe realizarse de forma periódica, almacenarse en un lugar seguro y someterse a pruebas de recuperación cuando sea necesario. No basta con crear respaldos si estos no pueden recuperarse o quedan disponibles para personas no autorizadas.
          .box___style_1.fit___box_2(data-aos="flip-up")
            p.mb-0 El #[b cifrado] es una medida técnica que protege la información al impedir que pueda ser interpretada fácilmente por personas no autorizadas. Puede aplicarse a archivos, dispositivos, bases de datos, correos electrónicos o comunicaciones. Resulta especialmente útil cuando se manejan datos sensibles, información laboral, bases de clientes o documentos que requieren reserva. Las principales prácticas asociadas con estos controles son:
        .col-xl-auto.d-none.d-xl-block(data-aos="zoom-in")
          figure
            img(src='@/assets/curso/temas/t2/img32.svg', alt='' style="width: 400px").m-auto
      .bg___carrusel
        .px-5
          SlyderF(columnas="col-lg-6 col-xl-4")(data-aos="zoom-in").mb-5
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t2/img33.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Periodicidad de los respaldos
              p.mb-0.text-center La organización debe definir con qué frecuencia realizará las copias de seguridad, teniendo en cuenta la información almacenada y la necesidad de recuperarla ante una pérdida o falla.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t2/img34.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Almacenamiento seguro
              p.mb-0.text-center Las copias deben conservarse en ubicaciones protegidas y con acceso restringido. Guardar un respaldo sin controles puede generar nuevos riesgos para la información.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t2/img35.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Pruebas de recuperación
              p.mb-0.text-center Los respaldos deben someterse a pruebas que permitan determinar si la información puede recuperarse cuando sea requerida. La existencia de una copia no garantiza por sí sola su utilidad.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t2/img36.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Cifrado de información
              p.mb-0.text-center Los archivos con datos sensibles o información que requiere reserva pueden protegerse mediante cifrado para reducir el riesgo de interpretación por personas no autorizadas.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t2/img37.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Gestión de respaldos obsoletos
              p.mb-0.text-center Las copias que ya no sean necesarias deben eliminarse de forma controlada. También debe evitarse su almacenamiento en dispositivos personales sin autorización.
          p.mb-5 Estas medidas permiten fortalecer la disponibilidad y confidencialidad de la información ante fallas, pérdidas o accesos no autorizados.
          .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
            .col-lg-auto
              figure
                img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
            .col
              h3 Control de accesos por perfiles
          p.mb-5 El #[b control de accesos por perfiles] consiste en permitir que cada persona consulte o modifique únicamente la información necesaria para cumplir sus funciones. Este control evita que todos los usuarios tengan acceso general a las bases de datos.
          .row.align-items-center.mb-5
            .col-xl
              .box___style_1.color___2.fit___box_2(data-aos="flip-up")
                p.mb-0 Por ejemplo, una persona del área comercial puede requerir datos de contacto de clientes, pero no debería acceder a incapacidades de trabajadores. El área de talento humano puede consultar información laboral, pero no necesariamente debe acceder a todas las bases comerciales. Asimismo, el área de sistemas puede administrar plataformas, pero sus accesos también deben estar controlados y justificados. Para aplicar este control, se deben considerar los siguientes componentes:
            .col-xl-auto.d-none.d-xl-block(data-aos="zoom-in")
              figure
                img(src='@/assets/curso/temas/t2/img38.png', alt='' style="width: 400px").m-auto
      .row.align-items-center.mb-5
        .col-xl-auto(data-aos="fade-right")
          figure.d-none.d-xl-block
            img(src="@/assets/curso/temas/t2/img5.png", alt="" style="width: 400px").m-auto
        .col-xl
          AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")(data-aos="fade-left")
            .row(titulo="Perfiles según funciones").ajuste-cajaAcordion.ajuste-vineta
              p.mb-3 Los permisos deben asignarse de acuerdo con las responsabilidades de cada persona. De esta manera, el acceso se relaciona directamente con las necesidades propias del cargo o proceso.
            .row(titulo="Permisos diferenciados").ajuste-cajaAcordion.ajuste-vineta
              p.mb-3 Los perfiles pueden limitar las posibilidades de consulta, edición y descarga. No todas las personas que consultan información necesitan modificarla o conservar copias.
            .row(titulo="Revisión de accesos").ajuste-cajaAcordion.ajuste-vineta
              p.mb-3 Los permisos deben revisarse periódicamente para retirar usuarios inactivos o accesos que hayan dejado de ser necesarios debido a cambios de funciones.
            .row(titulo="Registro de accesos").ajuste-cajaAcordion.ajuste-vineta
              p.mb-3 En bases de datos críticas, el registro de accesos permite identificar quién ingresó a la información y facilita el seguimiento ante situaciones que requieran análisis.
            .row(titulo="Protección reforzada").ajuste-cajaAcordion.ajuste-vineta
              p.mb-3 Los datos sensibles pueden requerir permisos especiales y mayores restricciones para su consulta, modificación o descarga.
      p.mb-0 El principio básico consiste en que cada persona acceda únicamente a la información indispensable para realizar su labor.
      .bg___color_1
        .px-5
          Separador
          #t_2_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
            h2 2.3 Controles físicos
          p Los #[b controles físicos] son medidas destinadas a proteger documentos, equipos, archivos, espacios y soportes en los que se almacena información personal. Aunque muchas organizaciones concentran sus medidas de seguridad en los entornos digitales, una parte importante de los datos personales continúa almacenada en carpetas, formatos impresos, contratos, hojas de vida, archivos físicos, listados, cuadernos de registro o dispositivos externos.
          .row.align-items-center.mb-5
            .col-xl
              p.mb-0 Estos controles contribuyen a prevenir la pérdida, deterioro, consulta indebida, sustracción o divulgación de información. Son necesarios en oficinas, archivos, puntos de atención, instituciones educativas, consultorios, bodegas documentales, áreas administrativas y cualquier espacio donde se manejen datos personales.
            .col-xl-auto.d-none.d-xl-block(data-aos="zoom-in")
              figure
                img(src='@/assets/curso/temas/t2/img40.svg', alt='' style="width: 190px").m-auto
          .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
            .col-lg-auto
              figure
                img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
            .col
              h3 Archivo seguro de documentos
          p.mb-5 El #[b archivo seguro de documentos] permite conservar información física de manera organizada y protegida. Los documentos que contienen datos personales no deben permanecer expuestos en escritorios, zonas de atención, pasillos, impresoras, archivadores abiertos o espacios de acceso general. Las medidas para proteger los archivos físicos pueden organizarse de la siguiente manera:
          .bg___carrusel
            .px-5
              SlyderF(columnas="col-lg-6 col-xl-4")(data-aos="zoom-in").mb-5
                .tarjeta.color-acento-botones.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/temas/t2/img41.svg' style="max-width: 90px").m-auto
                  h4.mb-3.estilo-text Almacenamiento protegido
                  p.mb-0.text-center Los documentos deben conservarse en archivadores cerrados y en espacios que reduzcan la posibilidad de consulta por personas no autorizadas.
                .tarjeta.color-acento-botones.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/temas/t2/img42.svg' style="max-width: 90px").m-auto
                  h4.mb-3.estilo-text Separación de información sensible
                  p.mb-0.text-center La información sensible debe mantenerse separada de los documentos generales cuando sus características requieran mayores condiciones de reserva y protección.
                .tarjeta.color-acento-botones.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/temas/t2/img43.svg' style="max-width: 90px").m-auto
                  h4.mb-3.estilo-text Custodia y préstamo
                  p.mb-0.text-center Deben definirse responsables de custodia y controles para el préstamo de expedientes. Esto permite identificar quién tiene los documentos y reducir el riesgo de pérdida.
                .tarjeta.color-acento-botones.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/temas/t2/img44.svg' style="max-width: 90px").m-auto
                  h4.mb-3.estilo-text Organización documental
                  p.mb-0.text-center Mantener los documentos ordenados por proceso, fecha o titular facilita su ubicación y evita la generación de copias innecesarias.
                .tarjeta.color-acento-botones.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/temas/t2/img45.svg' style="max-width: 90px").m-auto
                  h4.mb-3.estilo-text Eliminación de documentos
                  p.mb-0.text-center Los documentos que ya no deban conservarse deben destruirse de manera controlada para evitar que la información permanezca disponible después de finalizar su periodo de conservación.
              p.mb-5 El archivo seguro también facilita la atención de solicitudes de los titulares y permite sustentar el cumplimiento cuando se requiere ubicar una autorización, contrato, soporte o comunicación.
              .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
                .col-lg-auto
                  figure
                    img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
                .col
                  h3 Restricción de acceso a espacios físicos
              p La #[b restricción de acceso a espacios físicos] permite controlar quién puede ingresar a los lugares donde se conserva información personal. No todas las áreas deben estar disponibles para cualquier trabajador, visitante, proveedor o usuario externo.
              .row.align-items-center.mb-5
                .col-xl
                  p.mb-0 Algunos espacios que pueden requerir control son los archivos, oficinas de talento humano, áreas jurídicas, salas de sistemas, bodegas documentales, zonas de atención, centros de correspondencia o lugares donde se imprimen documentos con datos personales. Las medidas de restricción pueden organizarse así:
                .col-xl-auto.d-none.d-xl-block(data-aos="zoom-in")
                  figure
                    img(src='@/assets/curso/temas/t2/img46.svg', alt='' style="width: 190px").m-auto
      .bg___slider.mb-5
        .px-5
          .ajuste-slider(data-aos="zoom-in")
            SlyderA(tipo="b")
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Áreas restringidas
                  p.mb-0 Los espacios que contienen información personal pueden permanecer cerrados y limitar su ingreso de acuerdo con las necesidades de cada proceso.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t2/img47.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Control de llaves
                  p.mb-0 Las llaves u otros mecanismos de ingreso deben asignarse únicamente al personal autorizado, con el fin de limitar el acceso a los espacios protegidos.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t2/img48.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Registro de visitantes
                  p.mb-0 El ingreso de visitantes o terceros puede registrarse para mantener control sobre las personas que acceden temporalmente a áreas donde existe información personal.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t2/img49.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Acompañamiento a terceros
                  p.mb-0 Cuando un tercero requiera ingresar a un área restringida, el acompañamiento permite reducir el riesgo de acceso a documentos, equipos o información que no corresponda a su actividad.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t2/img50.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Ubicación segura de archivos
                  p.mb-0 Los archivadores y demás soportes deben situarse en espacios protegidos, de manera que el acceso a la información responda a una necesidad real del proceso.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t2/img51.png', alt='' style="max-width: 500px").m-auto
      p.mb-5 Estas medidas permiten limitar el acceso físico a la información y relacionarlo con las funciones o necesidades previamente autorizadas.
      .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
        .col
          h3 Protección de equipos y soportes
      p Los #[b equipos y soportes físicos] también pueden contener datos personales. Computadores, memorias USB, discos externos, celulares institucionales, impresoras, carpetas, cámaras y dispositivos de respaldo deben protegerse para prevenir su pérdida o uso indebido.
      p.mb-5 Entre las prácticas que pueden generar riesgos se encuentran guardar bases de datos en memorias personales, dejar equipos desbloqueados, abandonar documentos en las bandejas de las impresoras, compartir computadores sin controles o transportar información sin medidas de seguridad. Las principales medidas de protección pueden organizarse así:
      .row.align-items-center.mb-5
        .col-xl-auto(data-aos="fade-right")
          figure.d-none.d-xl-block
            img(src="@/assets/curso/temas/t2/img14.png", alt="" style="width: 500px").m-auto
        .col-xl
          AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")(data-aos="fade-left")
            .row(titulo="Bloqueo de equipos").ajuste-cajaAcordion.ajuste-vineta
              p.mb-3 Los computadores y demás equipos deben bloquearse cuando no estén en uso para reducir el riesgo de acceso a información por parte de personas no autorizadas.
            .row(titulo="Dispositivos de almacenamiento").ajuste-cajaAcordion.ajuste-vineta
              p.mb-3 Debe evitarse almacenar bases de datos en dispositivos personales. Las memorias USB y los discos externos utilizados en procesos autorizados requieren medidas de protección acordes con la información que contienen.
            .row(titulo="Control de impresiones").ajuste-cajaAcordion.ajuste-vineta
              p.mb-3 Los documentos con datos personales no deben permanecer abandonados en impresoras o espacios compartidos. Su impresión y manejo requieren medidas que reduzcan la exposición de la información.
            .row(titulo="Custodia y reporte").ajuste-cajaAcordion.ajuste-vineta
              p.mb-3 Los dispositivos deben conservarse en lugares seguros. La pérdida o el robo de un equipo que contenga información personal debe reportarse para gestionar el riesgo asociado.
            .row(titulo="Eliminación de información").ajuste-cajaAcordion.ajuste-vineta
              p.mb-3 Antes de desechar o retirar un dispositivo, la información almacenada debe eliminarse de manera controlada para evitar su recuperación o uso posterior.
            .row(titulo="Uso de equipos institucionales").ajuste-cajaAcordion.ajuste-vineta
              p.mb-3 Los procesos autorizados deben desarrollarse mediante los equipos definidos por la organización, evitando el almacenamiento o traslado informal de información en recursos personales.
      p.mb-0 La protección física complementa los #[b controles administrativos y técnicos]. La aplicación articulada de estos tres tipos de controles permite reducir riesgos y fortalecer la capacidad de la organización para proteger los datos personales.

</template>

<script>
export default {
  name: 'Tema2',
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
