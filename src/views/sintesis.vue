<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p Este componente formativo aborda el uso de herramientas para la evaluación, intervención y seguimiento psicosocial en contextos de movilidad humana, orientadas a la atención de población migrante, personas retornadas y comunidades de acogida, fortaleciendo la identificación de necesidades emocionales, familiares y comunitarias, el desarrollo de estrategias de apoyo individual, familiar y colectivo, la aplicación de orientaciones metodológicas para una intervención ética y culturalmente pertinente, y la implementación de procesos operativos que garantizan el registro, la activación de rutas de atención, la remisión y el monitoreo, con el fin de promover el bienestar mental, la integración social y la protección de derechos en los territorios.
    .row.justify-content-center
      .col-12.mb-5.bgs.p-4.brad
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="En la síntesis se describen las herramientas de evaluación, intervención y seguimiento psicosocial en contextos de movilidad humana, destacando los procesos de valoración individual, familiar y comunitaria, las estrategias de apoyo emocional y fortalecimiento de redes, así como las orientaciones metodológicas y los procedimientos de registro, remisión y monitoreo, que garantizan una atención integral, oportuna y humanizada.")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/bullets/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
