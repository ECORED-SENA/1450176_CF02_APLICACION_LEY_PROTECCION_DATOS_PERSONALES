<template lang="pug">
  .curso-main-container.introduccion
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido(data-aos="flip-up")
        .titulo-principal__numero
          span
            i.fas.fa-info
        h1 Introducción
      p.mb-5 La #[b protección de datos personales] constituye una responsabilidad fundamental para las organizaciones que recolectan, almacenan, utilizan, consultan, circulan, conservan o eliminan información de personas naturales. Su adecuada gestión requiere reconocer qué datos se tratan, con qué finalidad se utilizan, quiénes pueden acceder a ellos y qué medidas deben implementarse para reducir riesgos. Por esta razón, resulta necesario integrar prácticas que permitan fortalecer el cumplimiento, proteger los derechos de los titulares y prevenir situaciones relacionadas con el uso indebido o la divulgación no autorizada de información.
      .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
        .bloque-texto-g__img(
          :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/intro/img1.jpg')})` }")
        .bloque-texto-g__texto.p-4
          p Este componente formativo aborda la protección de datos desde una perspectiva práctica y organizacional. Para ello, integra el #[b diagnóstico del tratamiento de datos personales], la aplicación de #[b controles administrativos, técnicos y físicos], la gestión de solicitudes e incidentes, el análisis de riesgos y el desarrollo de ejercicios relacionados con empresas comerciales, instituciones educativas y áreas de talento humano. Estos contenidos permiten relacionar las responsabilidades de la organización con situaciones que pueden presentarse durante el manejo cotidiano de la información personal.
      .row.align-items-center.mb-0
        .col-xl
          .box___style_1.fit___box_1(data-aos="flip-up")
            p.mb-0 Finalmente, se plantea la elaboración de un #[b plan de mejora para la protección de datos personales], construido a partir de los hallazgos, riesgos, controles y evidencias identificados durante el proceso. Este plan permite definir acciones administrativas, técnicas y de capacitación, establecer responsables y plazos, conservar evidencias de cumplimiento y realizar seguimiento a las medidas implementadas. De esta manera, el componente promueve una gestión preventiva y de mejora continua orientada a fortalecer la protección de la información y la atención adecuada de los derechos de los titulares.
        .col-xl-auto.d-none.d-xl-block(data-aos="zoom-in")
          figure
            img(src='@/assets/curso/temas/intro/img2.svg', alt='' style="width: 190px").m-auto
      
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
