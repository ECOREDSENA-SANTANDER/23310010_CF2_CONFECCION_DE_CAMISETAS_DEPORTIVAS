<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Seguridad y salud en el trabajo

    .bloque-texto-g.bloque-texto-g--inverso.bg6.p-3.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require_src('@/assets/curso/temas/t4/img01.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 La seguridad y salud en el trabajo constituye un eje transversal de la actividad productiva en el sector de la confección. Su incorporación en los procesos no responde únicamente a obligaciones normativas, sino también a la necesidad de garantizar condiciones laborales que protejan la integridad física y mental de quienes participan en la cadena de producción. El conocimiento de los factores de riesgo presentes en el entorno de confección, así como la aplicación de medidas preventivas y protocolos de actuación ante eventos adversos, forma parte de las competencias esenciales de quienes se desempeñan en este campo.
          br

    .row.justify-content-start.mb-4(data-aos="zoom-in-left")
      .col-sm-12.col-lg-12
        .d-flex.align-items-center
          img.w-card-icon(src="@/assets/curso/temas/t1/camisa.svg")
          h3.bg2.py-2.w-card-text Tipos de riesgos laborales

    p Los riesgos laborales presentes en el entorno de confección se clasifican según su naturaleza y el mecanismo mediante el cual pueden afectar la salud. Su identificación sistemática constituye el punto de partida para la implementación de estrategias de prevención dentro del Sistema de Gestión de la Seguridad y Salud en el Trabajo (SG-SST).

    .row.justify-content-start.mb-3(data-aos="zoom-in-left")
        .col-12.col-lg-7
          h4.bg8.py-2.w-card-text2 Riesgos físicos

    p Los riesgos físicos se originan en las condiciones ambientales del lugar de trabajo y actúan sobre el organismo sin necesidad de contacto directo con la fuente. En los puestos de confección, los de mayor prevalencia son los siguientes:
    
    AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul").mb-4(data-aos="zoom-in-left")
      .row.justify-content-center(titulo="Ruido")
        .col-lg-6.mb-3.col-10
          p Las máquinas de coser industriales generan niveles sonoros que, ante exposición prolongada sin protección auditiva adecuada, producen deterioro auditivo de carácter progresivo e irreversible. La normativa colombiana establece un límite de 85 dBA (decibelios ponderados) para exposición continua durante una jornada de ocho horas, tal como lo dispone la Resolución 8321 de 1983 del Ministerio de Salud.
        .col-lg-5.col-11
          figure
            img(src='@/assets/curso/temas/t4/img02.png', alt='')
      
      .row.justify-content-center(titulo="Iluminación deficiente")
        .col-lg-6.mb-3.col-10
          p La iluminación insuficiente en el puesto de trabajo dificulta la identificación de detalles durante las operaciones de costura, aumenta la probabilidad de errores, genera fatiga visual y puede favorecer la ocurrencia de accidentes.
          p El puesto debe contar con iluminación general y con una fuente localizada sobre el área de costura. Esta debe permitir reconocer con claridad las piezas, las puntadas, las agujas y los demás elementos utilizados, sin producir reflejos, sombras excesivas o deslumbramiento.
        .col-lg-5.col-11
          figure
            img(src='@/assets/curso/temas/t4/img03.png', alt='')
      
      .row.justify-content-center(titulo="Temperatura")
        .col-lg-6.mb-3.col-10
          p Las condiciones térmicas inadecuadas, tanto por exposición a calor excesivo como por corrientes de aire frío, pueden afectar la concentración, generar incomodidad y favorecer la aparición de molestias musculares durante la jornada.
          p Para controlar este riesgo, el área de trabajo debe disponer de ventilación adecuada, circulación de aire y condiciones de temperatura acordes con la actividad realizada. También es importante mantener una hidratación adecuada y organizar pausas cuando las condiciones térmicas generen fatiga o malestar.
        .col-lg-5.col-11
          figure
            img(src='@/assets/curso/temas/t4/img04.png', alt='')
      
      .row.justify-content-center(titulo="Atrapamiento en partes móviles")
        .col-lg-6.mb-3.col-10
          p El atrapamiento puede presentarse cuando las extremidades, el cabello, los accesorios o las prendas de vestir entran en contacto con las partes móviles de la maquinaria.
          p Como medida preventiva, se recomienda utilizar ropa ajustada, recoger el cabello, evitar accesorios colgantes y comprobar que las guardas y los dispositivos de seguridad se encuentren instalados y en funcionamiento.
        .col-lg-5.col-11
          figure
            img(src='@/assets/curso/temas/t4/img05.png', alt='')
      
      .row.justify-content-center(titulo="Cortes con herramientas")
        .col-lg-6.mb-3.col-10
          p Las tijeras, los cortadores rotativos y las cuchillas utilizadas en la mesa de corte pueden causar lesiones cuando se manipulan de manera inadecuada o se almacenan sin protección.
          p Estas herramientas deben utilizarse exclusivamente para la función asignada, conservarse en buen estado y guardarse en un lugar seguro después de cada operación. El corte debe realizarse en dirección contraria al cuerpo y sobre una superficie estable.

        .col-lg-5.col-11
          figure
            img(src='@/assets/curso/temas/t4/img06.png', alt='')
      
      .row.justify-content-center(titulo="Golpes y caída de objetos")
        .col-lg-6.mb-3.col-10
          p Los rollos de tejido, las cajas de insumos y los equipos almacenados incorrectamente pueden caer y ocasionar golpes o lesiones.
          p Para reducir este riesgo, los materiales deben ubicarse en superficies estables, respetar la capacidad de almacenamiento y mantenerse alejados de las zonas de circulación. Los objetos pesados deben colocarse en los niveles inferiores para facilitar su manipulación segura.
        .col-lg-5.col-11
          figure
            img(src='@/assets/curso/temas/t4/img07.png', alt='')
      
    .row.justify-content-start.mb-4(data-aos="zoom-in-left")
      .col-sm-12.col-lg-12
        .d-flex.align-items-center
          img.w-card-icon(src="@/assets/curso/temas/t1/camisa.svg")
          h3.bg2.py-2.w-card-text Riesgos ergonómicos en el puesto de confección
    p Los riesgos ergonómicos se originan en la interacción entre las características físicas de la persona, las condiciones del puesto de trabajo y las exigencias de la tarea. Sus efectos suelen manifestarse gradualmente y pueden afectar principalmente el cuello, los hombros, la espalda, las muñecas, los antebrazos y los codos.

    .tarjeta.fondo03.p-4(data-aos="zoom-in-left").mb-4
        SlyderA(tipo="b")
          .row.justify-content-center.align-items-center
            .col-lg-5.mb-4.mb-md-0
              h4 Posturas estáticas prolongadas
              p Mantener una misma posición corporal durante periodos extensos y sin interrupciones genera tensión muscular acumulada, especialmente en el cuello, los hombros y la región lumbar.
              p Para reducir este riesgo, se recomienda alternar posturas, realizar pausas periódicas y ajustar la silla y la máquina de acuerdo con las dimensiones corporales de la persona.
            .col-lg-7.col-md-10
              img(src='@/assets/curso/temas/t4/img08.png', alt='')
          
          .row.justify-content-center.align-items-center
            .col-lg-5.mb-4.mb-md-0
              h4 Posturas forzadas
              p La inclinación sostenida del tronco hacia adelante y la flexión o rotación prolongada del cuello sobrecargan la columna vertebral y la musculatura cervical.
              p La prevención requiere mantener la espalda apoyada, ubicar el área de costura a una altura adecuada y conservar los materiales y controles dentro de una zona de alcance cómoda.
            .col-lg-7.col-md-10
              img(src='@/assets/curso/temas/t4/img09.png', alt='')
          
          .row.justify-content-center.align-items-center
            .col-lg-5.mb-4.mb-md-0
              h4 Movimientos repetitivos
              p Acciones como guiar el material, accionar el pedal, cortar hilos y manipular piezas de manera continua pueden producir lesiones por sobreuso en las muñecas, los antebrazos y los codos.
              p Para disminuir este riesgo, se deben realizar pausas activas, alternar las tareas cuando sea posible y evitar movimientos bruscos o la aplicación innecesaria de fuerza.
            .col-lg-7.col-md-10
              img(src='@/assets/curso/temas/t4/img10.png', alt='')

          .row.justify-content-center.align-items-center
            .col-lg-5.mb-4.mb-md-0
              h4 Aplicación de fuerza excesiva
              p La manipulación de cargas pesadas, como rollos de tejido, cajas de insumos o equipos, sin aplicar una técnica adecuada genera una carga elevada sobre la columna lumbar, los hombros y los miembros superiores.
              p Para prevenir lesiones, la carga debe mantenerse cerca del cuerpo, el levantamiento debe realizarse mediante la flexión y extensión de las piernas, y los cambios de dirección deben efectuarse desplazando los pies, sin girar el tronco mientras se sostiene el objeto.
            .col-lg-7.col-md-10
              img(src='@/assets/curso/temas/t4/img11.png', alt='')

    .row.justify-content-start.mb-4(data-aos="zoom-in-left")
      .col-sm-12.col-lg-12
        .d-flex.align-items-center
          img.w-card-icon(src="@/assets/curso/temas/t1/camisa.svg")
          h3.bg2.py-2.w-card-text Riesgos psicosociales en el entorno de confección

    p Los riesgos psicosociales se relacionan con las condiciones de organización y ejecución del trabajo. La exposición a ritmos de producción intensivos, la presión asociada con el cumplimiento de metas y la ausencia de pausas regulares puede generar fatiga mental, reducir la capacidad de atención y aumentar la probabilidad de errores o accidentes.
    p La prevención de estos riesgos requiere una adecuada organización de las tareas, distribución equilibrada de las cargas laborales, establecimiento de pausas durante la jornada y comunicación oportuna de las situaciones que puedan afectar el bienestar y el desempeño.

    .row.justify-content-start.mb-4(data-aos="zoom-in-left")
      .col-sm-12.col-lg-12
        .d-flex.align-items-center
          img.w-card-icon(src="@/assets/curso/temas/t1/camisa.svg")
          h3.bg2.py-2.w-card-text Lesiones y afecciones frecuentes en el entorno de confección
    p Las posturas prolongadas, los movimientos repetitivos, el esfuerzo muscular y las condiciones inadecuadas del puesto de trabajo pueden favorecer la aparición de diferentes lesiones y afecciones. A continuación, se presentan las más frecuentes.

























</template>

<script>
export default {
  name: 'Tema3',
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
