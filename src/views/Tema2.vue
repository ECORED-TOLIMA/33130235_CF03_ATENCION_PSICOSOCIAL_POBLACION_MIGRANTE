<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="fade-right")
      .titulo-principal__numero
        span 2
      h1 Herramientas para la intervención psicosocial
    .row.justify-content-center.mb-4
      .col-lg-5.col-8.col-md-7.order-lg-2.order-1.mb-3
        figure
          img(src='@/assets/curso/temas/tema2/img01.png', alt='Imagen decorativa')
      .col-lg-7.col-12.order-lg-1.order-2
        p.mb-4(data-aos="fade-down") La implementación de herramientas y técnicas psicosociales constituye un eje fundamental en los procesos de acompañamiento a la población migrante, retornada y a las comunidades de acogida. Esta fase permite transformar la información obtenida en la evaluación en acciones concretas que favorecen el bienestar emocional, el fortalecimiento de capacidades individuales y colectivas y la integración social. Su adecuada aplicación exige considerar las experiencias vividas por las personas, el contexto territorial y las particularidades culturales que influyen en la forma de afrontar la movilidad humana.
        p(data-aos="fade-down") Estas herramientas posibilitan la intervención en los niveles individual, familiar y comunitario, mediante estrategias orientadas a la expresión emocional, la reconstrucción de vínculos, la activación de redes de apoyo y la promoción de entornos protectores. Entre las principales herramientas de intervención psicosocial se encuentran:
    .BG01.mb-5(data-aos="flip-up")
      .row.justify-content-center.align-items-center(data-aos="fade-down")
        .col-lg-4.d-none.d-lg-block
          figure(data-aos="zoom-in")
            img(src="@/assets/curso/temas/tema2/img02.png", alt="Imagen decorativa")
        .col-lg-8
          SlyderF.custom.color-acento-botones(columnas="col-lg-6 col-xl-4")
            .tarjeta.tarjeta--slyder.p-4
              .row.justify-content-center.mb-3
                .col-6.col-lg-8
                  img(src="@/assets/curso/temas/tema2/img03.svg", alt="alt").img100.m-auto
              p Herramientas grupales y comunitarias.
            .tarjeta.tarjeta--slyder.p-4
              .row.justify-content-center.mb-3
                .col-6.col-lg-8
                  img(src="@/assets/curso/temas/tema2/img04.svg", alt="alt").img100.m-auto
              p Técnicas individuales de apoyo emocional.
            .tarjeta.tarjeta--slyder.p-4
              .row.justify-content-center.mb-3
                .col-6.col-lg-8
                  img(src="@/assets/curso/temas/tema2/img05.svg", alt="alt").img100.m-auto
              p Estrategias familiares y redes de apoyo.
            .tarjeta.tarjeta--slyder.p-4
              .row.justify-content-center.mb-3
                .col-6.col-lg-8
                  img(src="@/assets/curso/temas/tema2/img06.svg", alt="alt").img100.m-auto
              p Practicas psicoeducativas y fortalecimiento del afrontamiento.
    .row.justify-content-center.mb-0
      .col-lg-10.col-12
        .cajon.cajon.C01.color-primario.p-4
          p.mb-0(data-aos="fade-down") La Organización Internacional para las Migraciones (OIM), el Alto Comisionado de las Naciones Unidas para los Refugiados (ACNUR) y el Ministerio de Salud y Protección Social (MSPS) señalan que las intervenciones psicosociales deben desarrollarse con un enfoque sensible al trauma, garantizando condiciones de seguridad, confidencialidad, respeto y participación activa de las personas atendidas. Por ello, su implementación requiere habilidades técnicas, comunicación clara y la capacidad de adaptar cada herramienta a las características y necesidades del territorio.
    separador
    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 2.1 Técnicas individuales de apoyo emocional
    p(data-aos="fade-down") Las técnicas individuales de apoyo emocional permiten acompañar a las personas migrantes, retornadas y a las comunidades de acogida en la gestión de las emociones derivadas de la movilidad humana. Estas técnicas buscan estabilizar la respuesta emocional, favorecer la comprensión de los síntomas asociados al estrés y fortalecer la capacidad de afrontamiento. De acuerdo con los Lineamientos para la Atención Psicosocial del Ministerio de Salud y Protección Social (MSPS), estas intervenciones deben desarrollarse bajo un enfoque sensible al trauma, garantizando condiciones de seguridad, voluntariedad, confidencialidad y respeto por los ritmos de cada persona.
    p.mb-5(data-aos="fade-down") Entre las principales técnicas de apoyo emocional se destacan:
    TabsC.color-acento-botones.mb-5(data-aos="flip-up")
      .py-3.py-md-4(titulo="Contención emocional")
        .row.justify-content-center.p-4
          .col-lg-8.col-10.order-lg-1.order-1.mb-lg-0.mb-4
            figure(data-aos="fade-right")
              img(src='@/assets/curso/temas/tema2/img07.jpg', alt='Imagen decorativa')
          .col-lg-4.order-lg-2.order-2
            p Orientada a disminuir la angustia y favorecer la calma en situaciones de crisis, mediante la escucha activa, la validación emocional y una comunicación clara y empática. La Organización Internacional para las Migraciones (OIM) resalta su importancia en contextos de incertidumbre, duelo y experiencias migratorias dolorosas.
      .py-3.py-md-4(titulo="Psicoeducación emocional")
        .row.justify-content-center.p-4
          .col-lg-8.col-10.order-lg-1.order-1.mb-lg-0.mb-4
            figure(data-aos="fade-right")
              img(src='@/assets/curso/temas/tema2/img08.jpg', alt='Imagen decorativa')
          .col-lg-4.order-lg-2.order-2
            p Dirigida a explicar de forma sencilla las causas y manifestaciones del malestar psicológico, ayudando a normalizar las reacciones emocionales y a reducir el estigma asociado a la salud mental. La Organización Panamericana de la Salud (OPS) señala que este proceso fortalece la comprensión y la autonomía de las personas.
      .py-3.py-md-4(titulo="Técnicas de respiración y anclaje")
        .row.justify-content-center.p-4
          .col-lg-8.col-10.order-lg-1.order-1.mb-lg-0.mb-4
            figure(data-aos="fade-right")
              img(src='@/assets/curso/temas/tema2/img09.jpg', alt='Imagen decorativa')
          .col-lg-4.order-lg-2.order-2
            p Empleadas para regular la activación fisiológica producida por el estrés y la ansiedad, permitiendo recuperar la sensación de control, calma y estabilidad emocional.
      .py-3.py-md-4(titulo="Ejercicios de expresión emocional guiada")
        .row.justify-content-center.p-4
          .col-lg-8.col-10.order-lg-1.order-1.mb-lg-0.mb-4
            figure(data-aos="fade-right")
              img(src='@/assets/curso/temas/tema2/img10.jpg', alt='Imagen decorativa')
          .col-lg-4.order-lg-2.order-2
            p Que incluyen narrativas simbólicas, cuentos, dibujo y escritura, para facilitar la elaboración de experiencias difíciles, fortalecer el sentido de agencia personal y promover procesos de resignificación, evitando siempre la retraumatización.
    p.mb-0(data-aos="fade-down") Estas técnicas contribuyen al fortalecimiento de los recursos internos de las personas y favorecen procesos de adaptación más saludables en contextos de movilidad humana.
    separador
    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 2.2 Estrategias familiares y redes de apoyo
    p(data-aos="fade-down") La intervención familiar y el fortalecimiento de las redes de apoyo son componentes esenciales en el acompañamiento a familias migrantes, retornadas y de acogida. Los procesos de movilidad humana generan transformaciones en la dinámica familiar, separaciones, reasignación de roles y tensiones relacionales que requieren abordajes específicos. De acuerdo con el Ministerio de Salud y Protección Social (MSPS, 2023), estas estrategias buscan promover la cohesión, mejorar la comunicación y fortalecer las capacidades colectivas para afrontar el estrés.
    p.mb-5(data-aos="fade-down") Entre las principales estrategias utilizadas se destacan:
    .tarjeta.tarjeta--BG03.p-4.mb-5
      LineaTiempoC.color-acento-botones(text-small)(data-aos="flip-up")
        .row.py-5.px-4(titulo="1")
          .col-lg-5.mb-4.mb-md-0.order-lg-2.order-2
            h4 Genograma familiar
            p Herramienta que permite identificar la estructura familiar, la historia migratoria, los patrones de relación y los recursos internos, facilitando la comprensión de tensiones, rupturas y fortalezas (OIM).
          .col-lg-7.order-lg-1.order-1.mb-lg-0.mb-4
            figure
              img(src='@/assets/curso/temas/tema2/img11.jpg', alt='Imagen decorativa')
        .row.py-5.px-4(titulo="2")
          .col-lg-5.mb-4.mb-md-0.order-lg-2.order-2
            h4 Mapeo de redes de apoyo
            p Identifica la relación de la familia con instituciones, organizaciones sociales, vecinos y redes comunitarias, permitiendo visualizar apoyos disponibles y necesidades de fortalecimiento (OPS).
          .col-lg-7.order-lg-1.order-1.mb-lg-0.mb-4
            figure
              img(src='@/assets/curso/temas/tema2/img12.jpg', alt='Imagen decorativa')
        .row.py-5.px-4(titul5="3")
          .col-lg-5.mb-4.mb-md-0.order-lg-2.order-2
            h4 Sesiones de fortalecimiento familiar
            p Orientadas al desarrollo de habilidades como la comunicación asertiva, la resolución de conflictos y la adaptación a nuevos contextos culturales (ACNUR).
          .col-lg-7.order-lg-1.order-1.mb-lg-0.mb-4
            figure
              img(src='@/assets/curso/temas/tema2/img13.jpg', alt='Imagen decorativa')
        .row.py-5.px-4(titulo="4")
          .col-lg-5.mb-4.mb-md-0.order-lg-2.order-2
            h4 Activación de redes institucionales y comunitarias
            p Articulación con servicios de salud, educación, protección social, organizaciones comunitarias y grupos de apoyo, con el fin de generar entornos protectores y respuestas integrales (MSPS).
          .col-lg-7.order-lg-1.order-1.mb-lg-0.mb-4
            figure
              img(src='@/assets/curso/temas/tema2/img14.jpg', alt='Imagen decorativa')
    p.mb-0(data-aos="fade-down") La integración de estas estrategias contribuye a disminuir los niveles de tensión, fortalecer los vínculos familiares y consolidar redes de apoyo que favorecen la inclusión social y el bienestar psicosocial.
    separador
    #t_2_3.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 2.3 Herramientas grupales y comunitarias
    p(data-aos="fade-down") Las herramientas grupales y comunitarias constituyen un componente esencial del acompañamiento psicosocial, ya que permiten abordar los efectos colectivos de la movilidad humana y fortalecer la convivencia entre la población migrante, retornada y las comunidades de acogida. Estas herramientas parten del reconocimiento de que la experiencia migratoria impacta no solo a las personas de manera individual, sino también a las dinámicas sociales, las relaciones comunitarias y el sentido de pertenencia territorial. Según la Organización Panamericana de la Salud (OPS), el trabajo grupal favorece la cohesión social, reduce los niveles de estigmatización y contribuye a la construcción de entornos protectores.
    p.mb-5(data-aos="fade-down") Entre las principales herramientas grupales y comunitarias se destacan:
    .row.justify-content-center.align-items-center.mb-5(data-aos="flip-up")
      .col-lg-10.col-12.mb-5.mb-md-0.order-lg-2.order-2.mb-lg-0
        LineaTiempoD.color-acento-botones.especial
          .row(numero="1" titulo="Grupos psicosociales")
            .col-12.mb-4.mb-md-0
              p Espacios estructurados de encuentro que promueven la expresión emocional, la escucha activa y el reconocimiento de experiencias compartidas, fortaleciendo el apoyo mutuo y las capacidades de resiliencia.
              figure
                img(src='@/assets/curso/temas/tema2/img15.jpg', alt='Imagen decorativa')
          .row(numero="2" titulo="Círculos de diálogo y convivencia")
            .col-12.mb-4.mb-md-0
              p Orientados a abordar percepciones, tensiones, expectativas y necesidades relacionadas con la vida comunitaria, facilitando la búsqueda de soluciones colectivas y acuerdos de convivencia (MSPS, 2023).
              figure
                img(src='@/assets/curso/temas/tema2/img16.jpg', alt='Imagen decorativa')
          .row(numero="3" titulo="Cartografía social participativa")
            .col-12.mb-4.mb-md-0
              p Herramienta que permite reconstruir de manera colectiva la relación entre las comunidades y el territorio, identificando riesgos, recursos, barreras de acceso y oportunidades para la integración social.
              figure
                img(src='@/assets/curso/temas/tema2/img17.jpg', alt='Imagen decorativa')
          .row(numero="4" titulo="Jornadas comunitarias y actividades de integración")
            .col-12.mb-4.mb-md-0
              p Incluyen ferias comunitarias, encuentros interculturales, actividades deportivas y artísticas, que fortalecen el sentido de pertenencia, la confianza y la cooperación entre los diferentes grupos poblacionales.
              figure
                img(src='@/assets/curso/temas/tema2/img18.jpg', alt='Imagen decorativa')
          .row(numero="5" titulo="Movilización comunitaria")
            .col-12.mb-4.mb-md-0
              p Acciones orientadas a fortalecer el liderazgo local, la participación ciudadana y la articulación con instituciones y organizaciones sociales para el desarrollo de iniciativas conjuntas de bienestar psicosocial.
              figure
                img(src='@/assets/curso/temas/tema2/img19.jpg', alt='Imagen decorativa')
    p.mb-0(data-aos="fade-down") La implementación de estas herramientas contribuye a la construcción de comunidades más solidarias, inclusivas y resilientes, promoviendo la convivencia pacífica y la integración social en contextos de movilidad humana.
    separador
    #t_2_4.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 2.4 Prácticas psicoeducativas y fortalecimiento del afrontamiento
    figure.mb-5
      img(src='@/assets/curso/temas/tema2/img20.png', alt='Imagen decorativa')
    p(data-aos="fade-down") Las prácticas psicoeducativas constituyen un componente fundamental del acompañamiento psicosocial, ya que brindan información clara, comprensible y culturalmente pertinente sobre las reacciones emocionales que pueden surgir en contextos de movilidad humana. Estas prácticas orientan a las personas migrantes, retornadas y a las comunidades de acogida en la comprensión de sus respuestas psicológicas frente a situaciones de cambio, pérdida e incertidumbre, favoreciendo la identificación de emociones, la disminución del estigma y el fortalecimiento de la capacidad de afrontamiento. De acuerdo con la Organización Panamericana de la Salud (OPS), la psicoeducación contribuye a reducir la sensación de amenaza y a mejorar la percepción de control personal.
    p.mb-5(data-aos="fade-down") Durante este proceso se trabajan, entre otros, los siguientes temas:
    .row.justify-content-center.mb-0
      .col-lg-10.col-12
        .row.justify-content-center.tarjeta.tarjeta--C02.align-items-center.pt-4.mb-5
          .row.justify-content-center.align-items-center
            .col-lg-7.col-12.order-lg-2.order-2
              ol.lista-ol--cuadro.lista-ol.mb-0
                li.mb-2
                  .lista-ol--cuadro__vineta
                    span.text-bold 1
                  | Impacto emocional de la separación familiar.
                li.mb-2
                  .lista-ol--cuadro__vineta
                    span.text-bold 2
                  | Dificultades de adaptación a nuevos contextos culturales y sociales.
                li.mb-2
                  .lista-ol--cuadro__vineta
                    span.text-bold 3
                  | Manejo de la incertidumbre y el estrés.
                li.mb-2
                  .lista-ol--cuadro__vineta
                    span.text-bold 4
                  | Elaboración emocional de las pérdidas asociadas al proceso migratorio.
            .col-lg-5.col-8.col-md-7.order-lg-1.order-1.mb-3
              figure
                img(src='@/assets/curso/temas/tema2/img21.svg', alt='Imagen decorativa')
    p.mb-5(data-aos="fade-down") El fortalecimiento del afrontamiento se orienta a potenciar los recursos personales, familiares y comunitarios, mediante prácticas como:
    .row.mb-5(data-aos="flip-up")
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema2/img22.svg' alt='AvatarTop')
        p.text-center.text-bold(data-aos="fade-down") Reconocimiento de habilidades y experiencias previas.
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema2/img23.svg' alt='AvatarTop')
        p.text-center.text-bold(data-aos="fade-down") Identificación y activación de redes de apoyo.
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema2/img24.svg' alt='AvatarTop')
        p.text-center.text-bold(data-aos="fade-down") Resignificación de experiencias difíciles.
      .col-md-6.col-lg.tarjeta--tabla.p-4
        .row.justify-content-center.mb-3
          .col-4
            img(src='@/assets/curso/temas/tema2/img25.svg' alt='AvatarTop')
        p.text-center.text-bold(data-aos="fade-down") Promoción de estrategias de autocuidado y regulación emocional.
    p.mb-5(data-aos="fade-down") Los Lineamientos de Atención Psicosocial del Ministerio de Salud y Protección Social (MSPS, 2023) recomiendan que estas prácticas se desarrollen desde un enfoque sensible al trauma, garantizando respeto, escucha activa, ambientes seguros y participación voluntaria. El objetivo es que las personas reconozcan y utilicen sus propios recursos para afrontar situaciones difíciles, evitando la revictimización o la exposición innecesaria a recuerdos dolorosos.
    .row.justify-content-center.mb-0
      .col-lg-10.col-12
        .cajon.cajon.C01.color-primario.p-4
          p.mb-0(data-aos="fade-down") La combinación de psicoeducación y fortalecimiento del afrontamiento permite que las personas comprendan su experiencia migratoria, fortalezcan su bienestar emocional y desarrollen herramientas prácticas para enfrentar los desafíos derivados de la movilidad humana.
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
