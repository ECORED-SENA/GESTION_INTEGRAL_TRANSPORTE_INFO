<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.png')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Gestión Integral del Transporte
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Gestión Integral del Transporte
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 121524
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 3984: etapa lectiva: 3120 + etapa productiva: 864.
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Duración en meses: 
                p.banner-principal__datos__item__texto 27 meses
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual
              

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/DC4LEqH2wVk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p El programa Tecnología en Gestión Integral del Transporte forma talento humano que desee desempeñarse en actividades del transporte que involucren la planeación, supervisión, coordinación de los recursos, el análisis de costos, caracterización de los riesgos, proyección de requerimientos y el análisis de la información. 
    p El egresado de este programa podrá adquirir habilidades y destrezas que lo llevarán a ser competente laboralmente, tener una mejor calidad de vida y a su vez podrá vincularse en empresas del sector público o privado que estén dedicadas a la movilización de objetos, animales y/o personas según su actividad económica.
    p Estimado aprendiz, le damos la bienvenida a la formación profesional integral que ofrece el Sena, mediante el programa tecnólogo en Gestión Integral del Transporte, donde usted podrá adquirir o reforzar sus conocimientos, destrezas y habilidades, con las cuales se espera que usted pueda resolver las situaciones a las que se enfrentará en su vida laboral dentro del sector del transporte. Ánimo, la perseverancia y la constancia le permitirá lograr su proyecto de vida y contribuir al desarrollo del país.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación del programa

    p El SENA a través de la RED LOGÍSTICA Y TRANSPORTE, diseña el programa Tecnología en Gestión Integral del Transporte, respondiendo a las necesidades de profesionalización del talento humano, con el fin de mejorar la calidad de vida, la reducción de los costos de operación, la generación de estrategias de emprendimiento, manejo de herramientas de los sistemas de logística y transporte, administración de flotas y terminales para una mejor prestación del servicio, desarrollo y monitoreo de la programación de rutas, análisis de costos y fijación de precios, desarrollo de sistemas logísticos de suministros y distribución, y el cuidado ambiental. El personal formado en este programa desarrolla habilidades, conocimientos, destrezas y competencias en la coordinación de movimiento físico de mercancías entre diversos sistemas de transporte a nivel nacional e internacional, en beneficio de los usuarios, las empresas y la sociedad en general, buscando un servicio eficiente, seguro, oportuno y económico.
    p Los contenidos del programa de formación, apuntan a que los egresados cuenten con un amplio dominio de saberes relacionados con la gestión, seguimiento y evaluación del transporte en sus diferentes modos y la integración de éste con los demás eslabones de la cadena. Igualmente, pretende que los egresados tengan herramientas de gestión y solucionen problemas que enfrentan las empresas en el mercado nacional e internacional, incluyendo habilidades en el uso eficiente de las TIC (Tecnologías de la Información y Comunicación), como soporte estratégico para la toma de decisiones; con conciencia ambiental, responsabilidad social y empresarial, alcanzando desempeños seguros que generen alta productividad.
    p El programa de formación Tecnología en Gestión Integral del Transporte brinda a los empresarios y al sector productivo a nivel nacional, regional y local, las herramientas para que mejoren su desempeño logístico a través de la capacitación del personal vinculado al sector, que requiere adquirir y/o mejorar competencias para el desarrollo de las operaciones del transporte.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Competencias a desarrollar

    ul.lista-ul--color.mt-2
      li 
        i.fas.fa-circle
        span Coordinar el transporte según rutas y medios.
      li 
        i.fas.fa-circle
        span Proyectar los requerimientos de los clientes según método de compra y pronóstico.
      li 
        i.fas.fa-circle
        span Monitorear el servicio según protocolos y especificaciones del proceso de negocio.
      li 
        i.fas.fa-circle
        span Diseñar el plan de distribución según el canal y normativa de transporte.
      li    
        i.fas.fa-circle
        span Elaborar el plan de transporte según modos y normativa.
      li 
        i.fas.fa-circle
        span Supervisar el flujo de recursos de acuerdo con técnicas de trazabilidad y procedimientos técnicos.
      li 
        i.fas.fa-circle
        span Calcular costos de operación de acuerdo con métodos.
      li 
        i.fas.fa-circle
        span Coordinar el flujo de mercancía según el plan de operación y procedimientos.
      li 
        i.fas.fa-circle
        span Elaborar presupuestos de acuerdo con metodología y guía técnica.
      li 
        i.fas.fa-circle
        span Dirigir el talento humano de acuerdo con normativa.
      li 
        i.fas.fa-circle
        span Procesar los datos de acuerdo con técnica de investigación y tabulación.
      li 
        i.fas.fa-circle
        span Razonar cuantitativamente frente a situaciones susceptibles de ser abordadas de manera matemática en contextos laborales, sociales y personales.
      li 
        i.fas.fa-circle
        span Aplicación de conocimientos de las ciencias naturales de acuerdo con situaciones del contexto productivo y social.
      li 
        i.fas.fa-circle
        span Desarrollar procesos de comunicación eficaces y efectivos, teniendo en cuenta situaciones de orden social, personal y productivo.
      li 
        i.fas.fa-circle
        span Utilizar herramientas informáticas de acuerdo a las necesidades.
      li 
        i.fas.fa-circle
        span Generación de hábitos saludables de vida mediante la aplicación de programas de actividad física en los contextos productivos y sociales.
      li 
        i.fas.fa-circle
        span Gestionar procesos propios de la cultura emprendedora y empresarial de acuerdo con el perfil personal y los requerimientos de los contextos productivo y social.
      li 
        i.fas.fa-circle
        span Interactuar en el contexto productivo y social de acuerdo con principios éticos para la construcción de una cultura de paz.
      li 
        i.fas.fa-circle
        span Aplicar prácticas de protección ambiental, seguridad y salud en el trabajo de acuerdo con las políticas organizacionales y la normatividad vigente.
      li 
        i.fas.fa-circle
        span Investigación.
      li 
        i.fas.fa-circle
        span Derecho fundamental del trabajo.
      li 
        i.fas.fa-circle
        span Bilingüismo.  


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Perfil de ingreso

    p El aspirante debe demostrar terminación de educación básica secundaria, como edad mínima 16 años, aprobar el proceso de selección dentro del SENA y/o empresa.
    ul.lista-ul--color.mt-2
      li 
        i.fas.fa-circle
        strong Nivel de competencias a demostrar en el proceso de ingreso por tipo de certificación: 
        br
        br
        |
        li
          ul
            li 
              i.fas.fa-check
              | Nivel académico: media básica
            li 
              i.fas.fa-check
              | Grado: undécimo
            li 
              i.fas.fa-check
              | Requiere certificación académica:  si 
            li 
              i.fas.fa-check
              | Edad mínima definida en la ley: 16 años 
 
      li 
        i.fas.fa-circle
        strong Requisitos adicionales:
        br
        br
        |
        li
          ul
            li 
              i.fas.fa-check
              | No requiere experiencia laboral.
            li 
              i.fas.fa-check
              | Certificación de estudios de grado 11°
            li 
              i.fas.fa-check
              | Pruebas SABER PRO.
            li 
              i.fas.fa-check
              | Aprobar el proceso de selección del centro de formación o la empresa.
      li 
        i.fas.fa-circle
        p
          strong Restricciones de ingreso soportadas en la legislación vigente:
          br
          br
          | Limitaciones físicas o cognitivas que impiden total o parcialmente el desarrollo de la formación y que estén expresamente descritos y soportados en normas relacionadas con el desempeño ocupacional y profesional.
          br
          br
          | Para el desplazamiento en sitios donde se realicen las operaciones del transporte integral relacionadas con movimientos de carga, traslado, despachos, maniobras de equipo entre otras, no debe tener restricciones de tipo cognitivo ni motriz que impida el buen desarrollo de las actividades operacionales según documento de la OMS - Clasificación Internacional del Funcionamiento, de la Discapacidad y la Salud.
      li 
        i.fas.fa-circle
        p
          strong Aspectos actitudinales, motivacionales y de interés:
          br
          br
          | Buena actitud, presentación personal, proactivo, valores éticos, relaciones interpersonales.



  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Perfil de egreso

    p Este curso se creó para ofrecer a los aspirantes formación en la tecnología de logística y transporte. Con capacidades técnicas para desempeñarse eficientemente como:  Inspector de rutas de transporte urbano,  jefe de rodamiento, jefe transporte terrestre, programador de rutas de transporte terrestre, supervisor operaciones de transporte terrestre, supervisor rodamiento, supervisor sistema de transporte urbano, coordinador de rutas escolares, coordinador transporte escolar, programador de itinerarios, programador de rutas, programador de transporte de carga, programador de transporte de pasajeros, programador de trenes, auxiliar vuelo, coordinador de transporte, administrador de transporte, planificador de transporte.
  
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 6. Estrategia metodológica

    p Se centra en el aprendizaje autónomo, en pro de garantizar la calidad en el marco de la formación tanto por competencias, como por proyectos y el uso de técnicas didácticas activas, que estimulen el pensamiento para la resolución de problemas simulados y reales que estén soportadas en la utilización de las TIC, integradas en ambientes abiertos y pluritecnológicos que, en todo caso, recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias.
    p Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz, sobre el que hacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:
    ul.lista-ul--color.mt-2.mx-lg-4
      li 
        i.fas.fa-circle
        span El instructor - Tutor.
      li 
        i.fas.fa-circle
        span El entorno.
      li 
        i.fas.fa-circle
        span Las TIC.
      li 
        i.fas.fa-circle
        span El Aprendiz.  
  
  
  
  
  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 Créditos

    
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
