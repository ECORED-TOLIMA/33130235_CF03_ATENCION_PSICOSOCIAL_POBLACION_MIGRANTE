<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
      #Actividad                
        <Actividad :cuestionario="cuestionario"/>
  
  </template>

<script>
export default {
  name: 'ActividadDidactica',
  data: () => ({
    cuestionario: {
      tema: 'tema_actividad_didactica',
      titulo: 'Cuestionario',
      introduccion:
        '<b>Objetivo</b>: evaluar la comprensión de los aprendices sobre los fundamentos, herramientas y orientaciones del acompañamiento psicosocial en contextos de movilidad humana, así como su capacidad para identificar estrategias de evaluación, intervención y seguimiento dirigidas a población migrante, retornada y comunidades de acogida.',
      barajarPreguntas: true,
      preguntas: [
        {
          id: 1,
          texto:
            'Las técnicas individuales de apoyo emocional permiten acompañar a las personas migrantes, retornadas y a las comunidades de acogida.',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: true },
            { id: 'b', texto: 'Falso', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia comprensión de los conceptos y herramientas del acompañamiento psicosocial, así como la capacidad de analizar situaciones de movilidad humana y aplicar estrategias de intervención éticas y articuladas.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 2,
          texto:
            'Las estrategias familiares buscan promover la cohesión, mejorar la comunicación y fortalecer las capacidades colectivas para afrontar el estrés.',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: true },
            { id: 'b', texto: 'Falso', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia comprensión de los conceptos y herramientas del acompañamiento psicosocial, así como la capacidad de analizar situaciones de movilidad humana y aplicar estrategias de intervención éticas y articuladas.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 3,
          texto:
            'Las herramientas comunitarias solo se aplican en intervenciones individuales.',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: false },
            { id: 'b', texto: 'Falso', esCorrecta: true },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia comprensión de los conceptos y herramientas del acompañamiento psicosocial, así como la capacidad de analizar situaciones de movilidad humana y aplicar estrategias de intervención éticas y articuladas.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 4,
          texto:
            'El registro inicial constituye el primer paso para documentar de manera sistemática la situación de la persona migrante, retornada o perteneciente a la comunidad de acogida.',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: true },
            { id: 'b', texto: 'Falso', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia comprensión de los conceptos y herramientas del acompañamiento psicosocial, así como la capacidad de analizar situaciones de movilidad humana y aplicar estrategias de intervención éticas y articuladas.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 5,
          texto:
            'La activación de rutas se realiza sin considerar el nivel de riesgo psicosocial.',
          imagen: require('@/assets/actividad/imagen5.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: false },
            { id: 'b', texto: 'Falso', esCorrecta: true },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia comprensión de los conceptos y herramientas del acompañamiento psicosocial, así como la capacidad de analizar situaciones de movilidad humana y aplicar estrategias de intervención éticas y articuladas.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },

        {
          id: 6,
          texto:
            'La consejería psicosocial inicia con un proceso de acercamiento y reconocimiento.',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: true },
            { id: 'b', texto: 'Falso', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia comprensión de los conceptos y herramientas del acompañamiento psicosocial, así como la capacidad de analizar situaciones de movilidad humana y aplicar estrategias de intervención éticas y articuladas.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 7,
          texto:
            'La validación de la experiencia migratoria no hace parte de los Primeros Auxilios Psicológicos (PAP).',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: false },
            { id: 'b', texto: 'Falso', esCorrecta: true },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia comprensión de los conceptos y herramientas del acompañamiento psicosocial, así como la capacidad de analizar situaciones de movilidad humana y aplicar estrategias de intervención éticas y articuladas.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 8,
          texto:
            'Las habilidades comunicativas en la intervención psicosocial incluyen la apertura mental y la adaptación cultural.',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: true },
            { id: 'b', texto: 'Falso', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia comprensión de los conceptos y herramientas del acompañamiento psicosocial, así como la capacidad de analizar situaciones de movilidad humana y aplicar estrategias de intervención éticas y articuladas.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 9,
          texto:
            'El acompañamiento psicosocial debe considerar el contexto y las trayectorias de movilidad.',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: true },
            { id: 'b', texto: 'Falso', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia comprensión de los conceptos y herramientas del acompañamiento psicosocial, así como la capacidad de analizar situaciones de movilidad humana y aplicar estrategias de intervención éticas y articuladas.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
        {
          id: 10,
          texto:
            'El modelo “Estar, Escuchar, Conectar” orienta las acciones inmediatas de los Primeros Auxilios Psicológicos.',
          imagen: require('@/assets/actividad/imagen5.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Verdadero', esCorrecta: true },
            { id: 'b', texto: 'Falso', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia comprensión de los conceptos y herramientas del acompañamiento psicosocial, así como la capacidad de analizar situaciones de movilidad humana y aplicar estrategias de intervención éticas y articuladas.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },

        {
          id: 11,
          texto:
            'Técnicas de respiración y ______: empleadas para regular la activación fisiológica producida por el estrés y la ansiedad.',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Anclaje', esCorrecta: true },
            { id: 'b', texto: 'Trayectoria', esCorrecta: false },
            { id: 'c', texto: 'Vulnerabilidad', esCorrecta: false },
            { id: 'd', texto: 'Diversión', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia comprensión de los conceptos y herramientas del acompañamiento psicosocial, así como la capacidad de analizar situaciones de movilidad humana y aplicar estrategias de intervención éticas y articuladas.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },

        {
          id: 12,
          texto:
            'El mapeo de redes de apoyo identifica la relación de la ______ con instituciones y redes comunitarias.',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Jefe', esCorrecta: false },
            { id: 'b', texto: 'Familia', esCorrecta: true },
            { id: 'c', texto: 'Escuela', esCorrecta: false },
            { id: 'd', texto: 'Amistad', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia comprensión de los conceptos y herramientas del acompañamiento psicosocial, así como la capacidad de analizar situaciones de movilidad humana y aplicar estrategias de intervención éticas y articuladas.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },

        {
          id: 13,
          texto:
            'Las herramientas grupales y comunitarias constituyen un componente esencial del _______ psicosocial.',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Perspectiva', esCorrecta: false },
            { id: 'b', texto: 'Estado', esCorrecta: false },
            { id: 'c', texto: 'Acompañamiento', esCorrecta: true },
            { id: 'd', texto: 'Camino', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia comprensión de los conceptos y herramientas del acompañamiento psicosocial, así como la capacidad de analizar situaciones de movilidad humana y aplicar estrategias de intervención éticas y articuladas.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },

        {
          id: 14,
          texto:
            'Las prácticas ________ constituyen un componente fundamental del acompañamiento psicosocial.',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Deportivas', esCorrecta: false },
            { id: 'b', texto: 'Psicoeducativas', esCorrecta: true },
            { id: 'c', texto: 'Musicales', esCorrecta: false },
            { id: 'd', texto: 'Religiosas', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia comprensión de los conceptos y herramientas del acompañamiento psicosocial, así como la capacidad de analizar situaciones de movilidad humana y aplicar estrategias de intervención éticas y articuladas.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },

        {
          id: 15,
          texto:
            'La combinación de psicoeducación y fortalecimiento del afrontamiento permite comprender la experiencia ________.',
          imagen: require('@/assets/actividad/imagen5.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'Laboral', esCorrecta: false },
            { id: 'b', texto: 'Docente', esCorrecta: false },
            { id: 'c', texto: 'Informática', esCorrecta: false },
            { id: 'd', texto: 'Migratoria', esCorrecta: true },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia comprensión de los conceptos y herramientas del acompañamiento psicosocial, así como la capacidad de analizar situaciones de movilidad humana y aplicar estrategias de intervención éticas y articuladas.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },

        {
          id: 16,
          texto:
            '¿Cuál es el propósito principal de las técnicas individuales en el acompañamiento psicosocial?',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Impulsar la participación comunitaria.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Brindar apoyo emocional personalizado.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Fortalecer procesos institucionales.',
              esCorrecta: false,
            },
            { id: 'd', texto: 'Gestionar redes sociales.', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia comprensión de los conceptos y herramientas del acompañamiento psicosocial, así como la capacidad de analizar situaciones de movilidad humana y aplicar estrategias de intervención éticas y articuladas.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },

        {
          id: 17,
          texto:
            'Los procesos de movilidad humana generan transformaciones en:',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: true,
          opciones: [
            { id: 'a', texto: 'La dinámica familiar.', esCorrecta: true },
            { id: 'b', texto: 'El grupo de trabajo.', esCorrecta: false },
            { id: 'c', texto: 'El trabajo exclusivo.', esCorrecta: false },
            { id: 'd', texto: 'El trabajo en el aula.', esCorrecta: false },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia comprensión de los conceptos y herramientas del acompañamiento psicosocial, así como la capacidad de analizar situaciones de movilidad humana y aplicar estrategias de intervención éticas y articuladas.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },

        {
          id: 18,
          texto:
            '¿Cuál es la finalidad principal de las herramientas grupales y comunitarias?',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Garantizar atención clínica especializada.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto:
                'Abordar los efectos colectivos de la movilidad humana y fortalecer la convivencia.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Realizar evaluaciones diagnósticas individuales.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Coordinar remisiones médicas directas.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia comprensión de los conceptos y herramientas del acompañamiento psicosocial, así como la capacidad de analizar situaciones de movilidad humana y aplicar estrategias de intervención éticas y articuladas.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },

        {
          id: 19,
          texto: '¿Qué significa PAP?',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Participación Actual Psicológica.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Primeros Actores Protectores.',
              esCorrecta: false,
            },
            {
              id: 'c',
              texto: 'Primeros Auxilios Psicológicos.',
              esCorrecta: true,
            },
            {
              id: 'd',
              texto: 'Principal Ayuda Productiva.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia comprensión de los conceptos y herramientas del acompañamiento psicosocial, así como la capacidad de analizar situaciones de movilidad humana y aplicar estrategias de intervención éticas y articuladas.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },

        {
          id: 20,
          texto: '¿Cuál es la función principal del seguimiento psicosocial?',
          imagen: require('@/assets/actividad/imagen5.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Controlar asistencia institucional.',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Evaluar avances y ajustar apoyos.',
              esCorrecta: true,
            },
            {
              id: 'c',
              texto: 'Sustituir rutas de atención.',
              esCorrecta: false,
            },
            {
              id: 'd',
              texto: 'Definir únicamente riesgos clínicos.',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            '¡Excelente trabajo! Se evidencia comprensión de los conceptos y herramientas del acompañamiento psicosocial, así como la capacidad de analizar situaciones de movilidad humana y aplicar estrategias de intervención éticas y articuladas.',
          mensaje_incorrecto:
            'Revise nuevamente el contenido del componente formativo.',
        },
      ],
      mensaje_final_aprobado:
        'Ha superado la actividad y demuestra sólidos conocimientos sobre el componente formativo.',
      mensaje_final_reprobado:
        'No ha superado la actividad. Le recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica.',
    },
  }),
}
</script>
