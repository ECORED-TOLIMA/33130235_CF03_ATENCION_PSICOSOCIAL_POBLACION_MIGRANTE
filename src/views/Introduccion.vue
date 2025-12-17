<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-4.col-8.col-md-7.order-lg-1.order-1.mb-3
        figure
          img(src='@/assets/curso/temas/intro/img01.svg', alt='Imagen decorativa')
      .col-lg-8.col-12.order-lg-2.order-2
        p(data-aos="fade-down") El acompañamiento psicosocial a población migrante, personas retornadas y comunidades de acogida requiere el uso de herramientas técnicas que permitan comprender las necesidades emocionales, sociales y comunitarias, así como intervenir de manera oportuna y articulada. La movilidad humana genera desafíos complejos que demandan intervenciones estructuradas, éticas y culturalmente pertinentes, orientadas a la protección de la salud mental, el fortalecimiento del bienestar y la reconstrucción de los vínculos sociales.
        .tarjeta.tarjeta--C01.p-3.mb-3
          p.mb-0(data-aos="fade-down") En este contenido se describen las herramientas para la evaluación e intervención psicosocial, las orientaciones metodológicas para la atención en contextos de movilidad humana y los procesos operativos que garantizan el registro, la activación de rutas, el seguimiento y la aplicación de protocolos técnicos vigentes, con el fin de fortalecer las capacidades de atención integral y humanizada en los territorios.
        p.mb-0(data-aos="fade-down") Para comprender la importancia del contenido y los temas abordados, se recomienda acceder al siguiente video.
    .row.justify-content-center.align-items-center.mb-0        
      .col-lg-12
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/vdPrCjWJSHo?si=X4NxENRo3LLXAua_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

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
