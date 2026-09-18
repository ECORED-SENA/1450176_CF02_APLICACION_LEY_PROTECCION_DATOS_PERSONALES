<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido(data-aos="flip-up")
        .titulo-principal__numero
          span 4
        h1 Ejercicios prácticos de aplicación organizacional
      .row.align-items-center.mb-5
        .col-xl
          .box___style_1.color___1(data-aos="flip-up").mb-3
            p.mb-0 Los #[b ejercicios prácticos de aplicación organizacional] permiten aplicar los conceptos de protección de datos personales en situaciones cercanas al funcionamiento real de una organización. Su propósito es fortalecer la capacidad para identificar los datos tratados, revisar autorizaciones, reconocer riesgos y proponer acciones de mejora orientadas a proteger la información personal.
          p.mb-0 En este apartado se plantean tres contextos de aplicación: #[b una empresa comercial, una institución educativa y un área de talento humano]. Cada caso permite analizar el tratamiento de datos personales desde procesos diferentes, teniendo en cuenta las finalidades, los titulares, las autorizaciones, los controles y los riesgos asociados. Los contextos de aplicación se organizan de la siguiente manera:
        .col-xl-auto.d-none.d-xl-block(data-aos="zoom-in")
          figure
            img(src='@/assets/curso/temas/t4/img1.png', alt='' style="width: 400px").m-auto
      .row.justify-content-center.mb-5
        .col-xl-4.col-md-9.mb-4.mb-lg-0(data-aos="zoom-in")
          .card___icon.h-100.color___3
            .row.justify-content-center.mb-3
              .col-7
                figure.mb-4(data-aos="fade-right")
                  img(src='@/assets/curso/temas/t4/img2.svg', alt="" style="max-width: 90px").m-auto
              h4.text-center Empresa comercial
              p.mb-0.text-center Permite analizar el tratamiento de datos de clientes, la revisión de autorizaciones para finalidades comerciales y las acciones necesarias para fortalecer campañas y comunicaciones.
        .col-xl-4.col-md-9.mb-4.mb-lg-0(data-aos="zoom-in")
          .card___icon.h-100.color___3
            .row.justify-content-center.mb-3
              .col-7
                figure.mb-4(data-aos="zoom-in")
                  img(src='@/assets/curso/temas/t4/img3.svg', alt="" style="max-width: 90px").m-auto
              h4.text-center Institución educativa
              p.mb-0.text-center Se centra en el tratamiento de información de estudiantes, acudientes y demás integrantes de la comunidad educativa, con especial atención a los datos de niños, niñas y adolescentes.
        .col-xl-4.col-md-9(data-aos="zoom-in")
          .card___icon.h-100.color___3
            .row.justify-content-center.mb-3
              .col-7
                figure.mb-4(data-aos="fade-left")
                  img(src='@/assets/curso/temas/t4/img4.svg', alt="" style="max-width: 90px").m-auto
              h4.text-center Área de talento humano
              p.mb-0.text-center Aborda el manejo de hojas de vida, contratos, datos laborales y sensibles, así como la protección de archivos físicos y digitales relacionados con trabajadores y aspirantes.
      p.mb-0 Estos casos permiten trasladar los conceptos de protección de datos personales a situaciones organizacionales concretas.
      .bg___color_1
        .px-5
          Separador
          #t_4_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
            h2 4.1 Caso práctico: empresa comercial
          p Una empresa comercial recolecta datos personales de clientes para gestionar ventas, enviar información sobre productos, atender garantías, realizar procesos de facturación y responder solicitudes. En este tipo de organización, el tratamiento de datos suele realizarse mediante formularios físicos, plataformas digitales, bases de datos de clientes, correos electrónicos, redes sociales, sistemas de facturación y campañas comerciales.
          p.mb-5 El principal cuidado consiste en determinar que los datos recolectados sean necesarios para la finalidad informada y que exista autorización cuando se utilicen para comunicaciones comerciales, promociones, encuestas o campañas de fidelización. No todos los datos entregados por un cliente pueden utilizarse libremente para cualquier actividad de mercadeo.
          .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
            .col-lg-auto
              figure
                img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
            .col
              h3 Diagnóstico de datos de clientes
          p.mb-5 El #[b diagnóstico de datos de clientes] inicia con la identificación de los datos personales que la empresa conserva sobre sus clientes. Estos pueden incluir nombre, documento de identidad, teléfono, correo electrónico, dirección, historial de compras, preferencias, solicitudes, reclamos o información de pagos. Para desarrollar el ejercicio, la revisión de la base de datos comercial puede organizarse mediante los siguientes criterios:
          .row.align-items-center.mb-5
            .col-xl-auto(data-aos="fade-right")
              figure.d-none.d-xl-block
                img(src="@/assets/curso/temas/t4/img5.png", alt="" style="width: 400px").m-auto
            .col-xl
              AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")(data-aos="fade-left")
                .row(titulo="Datos personales tratados").ajuste-cajaAcordion.ajuste-vineta
                  p.mb-3 Se deben identificar los datos que contiene la base y establecer si corresponden con las necesidades reales del proceso comercial. Esto permite reconocer información innecesaria o excesiva.
                .row(titulo="Finalidad del tratamiento").ajuste-cajaAcordion.ajuste-vineta
                  p.mb-3 Cada dato recolectado debe relacionarse con una finalidad definida, como facturación, atención de garantías, gestión de ventas o comunicaciones comerciales.
                .row(titulo="Autorización").ajuste-cajaAcordion.ajuste-vineta
                  p.mb-3 Se debe determinar si existe soporte para el tratamiento y, cuando corresponda, si la autorización cubre específicamente las finalidades comerciales aplicadas.
                .row(titulo="Actualización de la información").ajuste-cajaAcordion.ajuste-vineta
                  p.mb-3 La revisión debe permitir identificar datos desactualizados, incompletos o que ya no resulten necesarios para el proceso.
                .row(titulo="Acceso a la base").ajuste-cajaAcordion.ajuste-vineta
                  p.mb-3 Es necesario establecer quiénes pueden consultar, modificar o descargar la información y si esos permisos corresponden con las funciones asignadas.
                .row(titulo="Evidencias y conservación").ajuste-cajaAcordion.ajuste-vineta
                  p.mb-3 Se debe determinar si la empresa conserva evidencia de la autorización y si ha definido tiempos de conservación para la información almacenada.
      p.mb-5 Este diagnóstico permite reconocer si la base de clientes responde a una finalidad clara o si existen datos innecesarios, desactualizados o utilizados sin soporte suficiente.
      .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
        .col
          h3 Revisión de autorizaciones comerciales
      p La #[b revisión de autorizaciones comerciales] permite determinar si los clientes aceptaron recibir información publicitaria, promociones, novedades, encuestas o comunicaciones por medios electrónicos. Esta revisión es importante porque una base creada para facturación o entrega de productos no debe utilizarse automáticamente para campañas comerciales.
      .row.align-items-center.mb-5
        .col-xl
          p.mb-0 La autorización debe indicar de forma clara la finalidad comercial. También debe permitir al titular conocer sus derechos y los canales disponibles para solicitar actualización, supresión o revocatoria. Los elementos que deben analizarse pueden organizarse de la siguiente manera:
        .col-xl-auto.d-none.d-xl-block(data-aos="zoom-in")
          figure
            img(src='@/assets/curso/temas/t4/img6.svg', alt='' style="width: 190px").m-auto
      .bg___carrusel
        .px-5
          SlyderF(columnas="col-lg-6 col-xl-4")(data-aos="zoom-in").mb-5
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t4/img7.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Identificación del responsable
              p.mb-0.text-center La autorización debe permitir reconocer qué organización realiza el tratamiento y quién asume la responsabilidad sobre los datos recolectados.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t4/img8.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Finalidad comercial
              p.mb-0.text-center Debe explicar con claridad si la información será utilizada para promociones, campañas, encuestas, comunicaciones u otras actividades de naturaleza comercial.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t4/img9.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Derechos del titular
              p.mb-0.text-center El titular debe recibir información sobre los derechos que puede ejercer respecto de sus datos personales durante el tratamiento.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t4/img10.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Canales de atención
              p.mb-0.text-center La autorización debe señalar los mecanismos disponibles para presentar consultas, solicitar actualizaciones, pedir supresión o revocar autorizaciones cuando corresponda.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t4/img11.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Evidencia de aceptación
              p.mb-0.text-center La organización debe conservar un soporte que permita demostrar que el cliente otorgó la autorización y establecer cuándo se produjo dicha aceptación.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t4/img12.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Separación de finalidades
              p.mb-0.text-center Las finalidades contractuales y publicitarias deben diferenciarse para evitar que la información recolectada con un propósito se utilice automáticamente para otro distinto.
          p.mb-5 Si la autorización no cumple estos elementos, se debe proponer una mejora en el formulario o en el mecanismo de registro.
          .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
            .col-lg-auto
              figure
                img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
            .col
              h3 Propuesta de mejora para campañas
          p.mb-5 Una #[b campaña comercial] debe utilizar únicamente datos autorizados para esa finalidad. Antes de enviar mensajes, correos electrónicos, realizar llamadas o remitir promociones, la empresa debe determinar que la base de datos esté actualizada y que los titulares hayan aceptado recibir comunicaciones comerciales. Las acciones de mejora pueden estructurarse así:
          .bg___slider.mb-5
            .px-5
              .ajuste-slider(data-aos="zoom-in")
                SlyderA(tipo="b")
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Actualización de autorizaciones
                      p.mb-0 Es necesario ajustar los formularios cuando no diferencien las finalidades o no permitan conservar evidencia suficiente de la aceptación del titular.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t4/img13.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Separación de finalidades
                      p.mb-0 La finalidad relacionada con la compra o prestación del servicio debe mantenerse diferenciada de la finalidad publicitaria o promocional.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t4/img14.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Depuración de la base
                      p.mb-0 Deben identificarse clientes inactivos, datos desactualizados y registros que ya no resulten necesarios para las actividades comerciales.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t4/img15.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Gestión de revocatorias
                      p.mb-0 Conviene mantener identificados los titulares que hayan retirado su autorización para comunicaciones comerciales, con el fin de evitar nuevos contactos no autorizados.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t4/img16.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Control de acceso
                      p.mb-0 La base comercial debe quedar disponible únicamente para las personas que requieran utilizarla de acuerdo con sus funciones.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t4/img17.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Evidencias y canales de retiro
                      p.mb-0 La empresa debe conservar soporte de la autorización y de las comunicaciones realizadas, además de informar un canal para dejar de recibir contenidos comerciales.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t4/img18.png', alt='' style="max-width: 500px").m-auto
      p.mb-0 Estas acciones permiten fortalecer el uso responsable de la información de los clientes durante el desarrollo de campañas comerciales.
      .bg___color_1
        .px-5
          Separador
          #t_4_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
            h2 4.2 Caso práctico: institución educativa
          p Una institución educativa maneja datos personales de estudiantes, acudientes, docentes, personal administrativo y proveedores. En este contexto, la protección de datos requiere especial cuidado porque puede incluir información de niños, niñas y adolescentes, registros académicos, datos familiares, fotografías, videos, datos de salud y documentos de identificación.
          p.mb-5 El tratamiento de esta información debe estar relacionado con finalidades educativas, administrativas, académicas, disciplinarias, de bienestar, seguridad o comunicación institucional. Además, cuando se trate de menores de edad, se debe actuar con mayor responsabilidad y respetar el interés superior del menor.
          .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
            .col-lg-auto
              figure
                img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
            .col
              h3 Tratamiento de datos de estudiantes
          p.mb-5 Los #[b datos de estudiantes] pueden encontrarse en matrículas, observadores, boletines, plataformas académicas, listados de asistencia, registros de convivencia, autorizaciones de salida, encuestas, certificados, comunicaciones con acudientes y bases institucionales. Para analizar este caso, se deben considerar los siguientes aspectos:
          .bg___carrusel
            .px-5
              SlyderF(columnas="col-lg-6 col-xl-4")(data-aos="zoom-in").mb-5
                .tarjeta.color-acento-botones.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/temas/t4/img19.svg' style="max-width: 90px").m-auto
                  h4.mb-3.estilo-text Datos recolectados
                  p.mb-0.text-center Se debe identificar qué información se solicita durante la matrícula y cuál se incorpora posteriormente en el desarrollo del proceso académico.
                .tarjeta.color-acento-botones.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/temas/t4/img20.svg' style="max-width: 90px").m-auto
                  h4.mb-3.estilo-text Acceso a la información
                  p.mb-0.text-center Es necesario determinar quiénes pueden consultar los datos de los estudiantes y si ese acceso corresponde con las funciones asignadas.
                .tarjeta.color-acento-botones.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/temas/t4/img21.svg' style="max-width: 90px").m-auto
                  h4.mb-3.estilo-text Almacenamiento
                  p.mb-0.text-center Debe identificarse dónde se conservan los registros académicos y administrativos, tanto en soportes físicos como en plataformas o sistemas institucionales.
                .tarjeta.color-acento-botones.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/temas/t4/img22.svg' style="max-width: 90px").m-auto
                  h4.mb-3.estilo-text Entrega a acudientes o terceros
                  p.mb-0.text-center La institución debe establecer qué información puede compartirse, con quién y bajo qué condiciones, evitando la entrega de datos de otros estudiantes.
                .tarjeta.color-acento-botones.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/temas/t4/img23.svg' style="max-width: 90px").m-auto
                  h4.mb-3.estilo-text Autorizaciones
                  p.mb-0.text-center Se deben identificar los soportes que respaldan los tratamientos realizados, especialmente cuando se utilicen fotografías, videos u otra información que requiera autorización.
                .tarjeta.color-acento-botones.p-4
                  .row.justify-content-center.mb-3
                    .col-8
                      img(src='@/assets/curso/temas/t4/img24.svg' style="max-width: 90px").m-auto
                  h4.mb-3.estilo-text Medidas de protección
                  p.mb-0.text-center Deben aplicarse controles para evitar la exposición de notas, listados, datos familiares o información sensible en espacios de acceso general.
              p.mb-5 La institución también debe proteger las plataformas académicas mediante usuarios, contraseñas y perfiles de acceso.
              .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
                .col-lg-auto
                  figure
                    img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
                .col
                  h3 Protección de datos de menores de edad
              p Los #[b datos de menores de edad] requieren protección reforzada. Su tratamiento debe realizarse con autorización de los representantes legales cuando corresponda y responder a finalidades legítimas relacionadas con el servicio educativo o institucional.
              p.mb-5 Una situación frecuente es el uso de fotografías y videos en redes sociales, páginas web, carteleras, eventos o material promocional. Antes de publicar este tipo de contenido, la institución debe contar con autorización clara, informar la finalidad y evitar exponer información que pueda afectar la seguridad o intimidad del menor. Las buenas prácticas pueden organizarse de la siguiente manera:
              .bg___slider.mb-5
                .px-5
                  .ajuste-slider(data-aos="zoom-in")
                    SlyderA(tipo="b")
                      .row.justify-content-center.align-items-center
                        .col-xl-6.mb-4
                          h4 Recolección necesaria
                          p.mb-0 Deben solicitarse únicamente los datos necesarios para cumplir las finalidades educativas, administrativas o institucionales correspondientes.
                        .col-xl-6
                          figure
                            img(src='@/assets/curso/temas/t4/img25.png', alt='' style="max-width: 500px").m-auto
                      .row.justify-content-center.align-items-center
                        .col-xl-6.mb-4
                          h4 Autorizaciones de acudientes
                          p.mb-0 La institución debe conservar los soportes relacionados con la autorización cuando corresponda, especialmente en tratamientos que impliquen fotografías, videos u otros usos específicos.
                        .col-xl-6
                          figure
                            img(src='@/assets/curso/temas/t4/img26.png', alt='' style="max-width: 500px").m-auto
                      .row.justify-content-center.align-items-center
                        .col-xl-6.mb-4
                          h4 Acceso restringido
                          p.mb-0 La información académica, médica o familiar debe estar disponible únicamente para las personas que requieran consultarla por razón de sus funciones.
                        .col-xl-6
                          figure
                            img(src='@/assets/curso/temas/t4/img27.png', alt='' style="max-width: 500px").m-auto
                      .row.justify-content-center.align-items-center
                        .col-xl-6.mb-4
                          h4 Uso de imágenes
                          p.mb-0 Las fotografías o videos de menores no deben publicarse sin la autorización correspondiente ni utilizarse para finalidades distintas de las informadas.
                        .col-xl-6
                          figure
                            img(src='@/assets/curso/temas/t4/img28.png', alt='' style="max-width: 500px").m-auto
                      .row.justify-content-center.align-items-center
                        .col-xl-6.mb-4
                          h4 Plataformas y comunicaciones
                          p.mb-0 Los permisos en plataformas académicas deben revisarse y las comunicaciones relacionadas con estudiantes deben gestionarse mediante canales institucionales.
                        .col-xl-6
                          figure
                            img(src='@/assets/curso/temas/t4/img29.png', alt='' style="max-width: 500px").m-auto
                      .row.justify-content-center.align-items-center
                        .col-xl-6.mb-4
                          h4 Capacitación del personal
                          p.mb-0 Docentes y personal administrativo deben conocer las medidas aplicables al tratamiento de información de niños, niñas y adolescentes.
                        .col-xl-6
                          figure
                            img(src='@/assets/curso/temas/t4/img30.png', alt='' style="max-width: 500px").m-auto
      p.mb-5 Estas medidas permiten reforzar la protección de la información de menores de edad en los diferentes procesos institucionales.
      .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
        .col
          h3 Control de acceso a información académica
      .bg___color_1
        .px-5
          p El #[b control de acceso a información académica] permite garantizar que únicamente las personas autorizadas consulten los registros de los estudiantes. No todos los docentes, administrativos o terceros deben acceder a toda la información institucional.
          p.mb-5 Por ejemplo, un docente puede consultar información académica de su grupo, pero no necesariamente datos familiares, médicos o financieros. El área administrativa puede gestionar matrículas y pagos, pero no debe divulgar información académica sin autorización. Los acudientes pueden recibir información del estudiante a su cargo, pero no datos de otros estudiantes. Las medidas de control pueden organizarse así:
          .row.justify-content-center.mb-5
            .col-xl-10
              .box___style_2(data-aos="zoom-in")
                .row.align-items-center
                  .col-xl-auto
                    figure
                      img(src='@/assets/curso/temas/t4/img31.jpg', alt='' style="width: 400px").m-auto
                  .col-xl.fit___box_container
                    ul.fa-ul.estilo___ul.mb-0
                      li.mb-2
                        span.fa-li
                          i.fas.fa-check-circle
                        | #[b Usuarios individuales:] cada persona debe contar con un acceso propio a las plataformas institucionales para relacionar las acciones realizadas con un usuario determinado. 
                      li.mb-2
                        span.fa-li
                          i.fas.fa-check-circle
                        | #[b Perfiles según funciones:] los permisos deben asignarse de acuerdo con las responsabilidades de docentes, administrativos y demás personas que intervienen en el proceso. 
                      li.mb-2
                        span.fa-li
                          i.fas.fa-check-circle
                        | #[b Restricción de descargas:] la descarga de reportes debe limitarse cuando no sea necesaria para el desarrollo de las funciones asignadas. 
                      li.mb-2
                        span.fa-li
                          i.fas.fa-check-circle
                        | #[b Revisión de permisos:] los accesos a las plataformas académicas deben revisarse periódicamente para retirar permisos innecesarios o desactualizados. 
                      li.mb-2
                        span.fa-li
                          i.fas.fa-check-circle
                        | #[b Protección de documentos:] los listados y documentos físicos gestionados en secretaría o coordinación deben mantenerse bajo control y evitar su circulación mediante canales informales. 
                      li.mb-0
                        span.fa-li
                          i.fas.fa-check-circle
                        | #[b Entrega de información:] la entrega de certificados o reportes debe registrarse cuando sea necesario para conservar evidencia de quién recibió la información.
      p.mb-0 La definición de permisos según las funciones permite limitar el acceso a la información académica y reducir los riesgos de divulgación indebida.
      Separador
      #t_4_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
        h2 4.3 Caso práctico: área de talento humano
      p El #[b área de talento humano] maneja información personal de aspirantes, empleados, contratistas, practicantes y exempleados. Esta información puede incluir hojas de vida, documentos de identificación, contratos, certificados, datos bancarios, afiliaciones, incapacidades, evaluaciones, registros disciplinarios, información familiar y datos de salud ocupacional.
      p.mb-5 Por la naturaleza de estos datos, talento humano debe aplicar controles administrativos, técnicos y físicos. También debe limitar el acceso a la información, conservar soportes de autorización, definir tiempos de retención documental y garantizar la confidencialidad.
      .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
        .col
          h3 Manejo de hojas de vida y contratos
      p Las #[b hojas de vida] contienen información personal, académica, laboral, familiar y de contacto. Por esta razón, no deben circular libremente dentro de la organización ni conservarse indefinidamente sin una finalidad.
      p.mb-5 Durante los procesos de selección, la organización debe informar al aspirante para qué se recolecta su información, durante cuánto tiempo se conservará y cómo puede ejercer sus derechos. Cuando el proceso finaliza, se debe definir si la hoja de vida será eliminada, archivada temporalmente o conservada para futuras convocatorias con la correspondiente autorización.
      .row.align-items-center.mb-5
        .col-xl
          .box___style_1.color___2(data-aos="flip-up")
            p.mb-0 En el caso de los #[b contratos], se debe proteger la información relacionada con identificación, salario, cargo, funciones, afiliaciones, datos bancarios y documentos de soporte. Estos archivos deben permanecer bajo custodia del área responsable y no deben compartirse con personas que no intervengan en el proceso laboral o contractual. Las principales condiciones de manejo pueden organizarse de esta manera:
        .col-xl-auto.d-none.d-xl-block(data-aos="zoom-in")
          figure
            img(src='@/assets/curso/temas/t4/img32.svg', alt='' style="width: 190px").m-auto
      .bg___slider.mb-5
        .px-5
          .ajuste-slider(data-aos="zoom-in")
            SlyderA(tipo="b")
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Hojas de vida de aspirantes
                  p.mb-0 Deben recolectarse para una finalidad definida y conservarse únicamente durante el tiempo que resulte pertinente. Si se mantienen para futuras convocatorias, debe existir el soporte correspondiente.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t4/img33.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Información contractual
                  p.mb-0 Los contratos y sus documentos asociados pueden contener datos de identificación, salario, afiliaciones y datos bancarios, por lo que requieren medidas de custodia y acceso restringido.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t4/img34.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Circulación interna
                  p.mb-0 Las hojas de vida y los contratos no deben compartirse con personas que no intervengan en el proceso de selección, contratación o gestión laboral.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t4/img35.png', alt='' style="max-width: 500px").m-auto
              .row.justify-content-center.align-items-center
                .col-xl-6.mb-4
                  h4 Conservación
                  p.mb-0 La organización debe establecer qué información se mantiene, durante cuánto tiempo y bajo qué condiciones, evitando la conservación indefinida sin una finalidad.
                .col-xl-6
                  figure
                    img(src='@/assets/curso/temas/t4/img36.png', alt='' style="max-width: 500px").m-auto
      p.mb-5 Estas medidas permiten limitar el uso y circulación de la información laboral a las necesidades reales del proceso.
      .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
        .col-lg-auto
          figure
            img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
        .col
          h3 Protección de datos laborales y sensibles
      p En talento humano pueden tratarse #[b datos sensibles], especialmente aquellos relacionados con salud, incapacidades, restricciones médicas, exámenes ocupacionales, condiciones especiales, biometría o información familiar. Estos datos requieren mayor confidencialidad y acceso restringido.
      p.mb-5 No toda persona dentro de la organización debe conocer esta información. Su tratamiento debe limitarse al cumplimiento de obligaciones laborales, administrativas, legales o relacionadas con la seguridad y salud en el trabajo. Las principales medidas pueden organizarse así:
      .bg___carrusel
        .px-5
          SlyderF(columnas="col-lg-6 col-xl-4")(data-aos="zoom-in").mb-5
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t4/img37.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Separación de información
              p.mb-0.text-center Los expedientes laborales pueden mantenerse diferenciados de la información médica o sensible cuando esta requiera mayores condiciones de reserva.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t4/img38.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Acceso restringido
              p.mb-0.text-center La consulta debe limitarse al personal autorizado y responder a una necesidad relacionada con las funciones asignadas.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t4/img39.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Canales seguros
              p.mb-0.text-center Debe evitarse el envío de incapacidades u otros documentos sensibles mediante canales inseguros o mecanismos no autorizados por la organización.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t4/img40.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Protección documental
              p.mb-0.text-center Los documentos físicos y digitales deben conservarse en carpetas, sistemas o repositorios protegidos frente a accesos no autorizados.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t4/img41.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Uso limitado
              p.mb-0.text-center La información debe utilizarse exclusivamente para las finalidades laborales, administrativas o legales correspondientes, sin divulgar condiciones de salud u otros datos sensibles.
            .tarjeta.color-acento-botones.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/temas/t4/img42.svg' style="max-width: 90px").m-auto
              h4.mb-3.estilo-text Capacitación
              p.mb-0.text-center El personal encargado del proceso debe conocer las responsabilidades aplicables al tratamiento de información laboral y sensible.
          p.mb-5 La aplicación de estas medidas permite fortalecer la confidencialidad y limitar el tratamiento de información laboral y sensible a las finalidades correspondientes.
          .titles___box_tercer_nivel.mb-5(data-aos="fade-right")
            .col-lg-auto
              figure
                img(src="@/assets/curso/temas/t1/img3.png" style="max-width: 70px").m-auto
            .col
              h3 Medidas para archivo físico y digital
          p El #[b archivo físico y digital] en talento humano debe organizarse de forma segura. Los documentos físicos deben permanecer en archivadores cerrados, con responsables de custodia y controles de préstamo. Los archivos digitales deben almacenarse en carpetas protegidas, sistemas institucionales o repositorios con permisos definidos.
          p.mb-5 No es recomendable guardar información laboral en computadores personales, memorias USB sin control, correos electrónicos personales o carpetas compartidas sin restricciones. Tampoco deben dejarse documentos impresos sobre escritorios, impresoras o zonas comunes. Las medidas para ambos tipos de archivo pueden estructurarse de la siguiente manera:
          .bg___slider.mb-5
            .px-5
              .ajuste-slider(data-aos="zoom-in")
                SlyderA(tipo="b")
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Archivo físico
                      p.mb-0 Los documentos deben conservarse en archivadores cerrados, con responsables definidos y controles que permitan gestionar el préstamo de expedientes.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t4/img43.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Archivo digital
                      p.mb-0 La información debe almacenarse en sistemas institucionales, carpetas protegidas o repositorios con permisos asignados según las funciones.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t4/img44.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Dispositivos personales
                      p.mb-0 Debe evitarse guardar información laboral en computadores personales, memorias USB u otros dispositivos que no cuenten con los controles definidos por la organización.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t4/img45.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Carpetas compartidas
                      p.mb-0 Los repositorios compartidos deben contar con restricciones de acceso que impidan la consulta o modificación de información por personas no autorizadas.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t4/img46.png', alt='' style="max-width: 500px").m-auto
                  .row.justify-content-center.align-items-center
                    .col-xl-6.mb-4
                      h4 Documentos impresos
                      p.mb-0 Los documentos con datos personales no deben permanecer expuestos en escritorios, impresoras o espacios de acceso general.
                    .col-xl-6
                      figure
                        img(src='@/assets/curso/temas/t4/img47.png', alt='' style="max-width: 500px").m-auto
      p.mb-0 La organización segura de los archivos físicos y digitales complementa los demás controles aplicados por talento humano y contribuye a proteger la información durante su conservación y uso.

</template>

<script>
export default {
  name: 'Tema4',
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
