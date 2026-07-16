<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Confección de camiseta deportiva

    .bloque-texto-g.bloque-texto-g--inverso.bg7.p-3.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require_src('@/assets/curso/temas/t3/img01.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 La confección de la camiseta deportiva exige el dominio técnico de una secuencia de operaciones básicas de costura ejecutadas en maquinaria especializada, dado que cada equipo cumple una función específica dentro del proceso de ensamble. La correcta articulación entre máquina, material, tipo de puntada y operación determina la estabilidad de la costura, la funcionalidad de la prenda y la calidad del acabado final. 
          br
          br
          | Por esta razón, el presente apartado introduce las operaciones fundamentales desarrolladas en las principales máquinas empleadas en confección industrial, con el propósito de reconocer su aplicación, su orden de intervención y su aporte dentro de la construcción técnica de la camiseta deportiva.

    separador
    #t_3_1.titulo-segundo.mb-4(data-aos="zoom-in-left")
      h2 3.1  Máquina fileteadora con puntada de seguridad

    p La máquina fileteadora con puntada de seguridad es uno de los equipos más utilizados en la confección de prendas elaboradas en tejido de punto, como las camisetas deportivas. Su función consiste en unir las piezas de la prenda mientras realiza simultáneamente el sobrehilado de los bordes, lo que proporciona resistencia, elasticidad y un acabado adecuado para prendas sometidas a movimiento constante.
    p Antes de iniciar cualquier operación de costura, es indispensable realizar la puesta a punto de la máquina. Este procedimiento permite verificar que el equipo se encuentre limpio, correctamente lubricado, ajustado y enhebrado, garantizando así la formación adecuada de la puntada y el correcto desempeño durante el proceso de confección.

    .row.justify-content-start.mb-4(data-aos="zoom-in-left")
      .col-sm-12.col-lg-12
        .d-flex.align-items-center
          img.w-card-icon(src="@/assets/curso/temas/t1/camisa.svg")
          h3.bg2.py-2.w-card-text Puesta a punto de la máquina fileteadora con puntada de seguridad

    p La puesta a punto de la máquina fileteadora con puntada de seguridad comprende una secuencia de trece pasos que deben ejecutarse de manera ordenada antes de iniciar las operaciones de confección.
    
    .fondosly.p-3.p-md-4.p-lg-5.mb-4
      .tarjeta.tarjeta-blanca.p-4
        LineaTiempoC.color-acento-botones(text-small)
          .row.justify-content-center(titulo="1")
            .col-lg-2.mb-4.mb-md-0.col-7.col-md-4
              img.mb-4(src="@/assets/curso/temas/t3/1.png")
            .col-lg-3
              h4 Alistamiento de herramientas
              p Consulte el video:  
              .col-sm-auto
                a.boton.color-acento-botones.texto-blanco( href="https://www.youtube.com/watch?v=BlsIooZH9gg&list=PLkc5n6npRWkjS1Oni_VR8m2ZJh2pb3E6C&index=13" target="_blank")
                  span Abrir video
                  i.fas.fa-file-video


          .row.justify-content-center(titulo="2")
            .col-lg-2.mb-4.mb-md-0.col-7.col-md-4
              img.mb-4(src="@/assets/curso/temas/t3/2.png")
            .col-lg-4
              h4 Limpieza y orden del puesto de trabajo
              p Consulte el video:
              .col-sm-auto
                a.boton.color-acento-botones.texto-blanco(
                  href="https://www.youtube.com/watch?v=wtHBYpvY2qg&list=PLkc5n6npRWkjS1Oni_VR8m2ZJh2pb3E6C&index=14"
                  target="_blank"
                )
                  span Abrir video
                  i.fas.fa-file-video

          .row.justify-content-center(titulo="3")
            .col-lg-2.mb-4.mb-md-0.col-7.col-md-4
              img.mb-4(src="@/assets/curso/temas/t3/3.png")
            .col-lg-4
              h4 Enhebrado del hilo para looper inferior
              p Consulte el video:
              .col-sm-auto
                a.boton.color-acento-botones.texto-blanco(
                  href="https://www.youtube.com/watch?v=e3VIQuI2CPc&list=PLkc5n6npRWkjS1Oni_VR8m2ZJh2pb3E6C&index=5"
                  target="_blank"
                )
                  span Abrir video
                  i.fas.fa-file-video

          .row.justify-content-center(titulo="4")
            .col-lg-2.mb-4.mb-md-0.col-7.col-md-4
              img.mb-4(src="@/assets/curso/temas/t3/4.png")
            .col-lg-4
              h4 Enhebrado del hilo para looper superior
              p Consulte el video:
              .col-sm-auto
                a.boton.color-acento-botones.texto-blanco(
                  href="https://www.youtube.com/watch?v=C60vi8djPhA&list=PLkc5n6npRWkjS1Oni_VR8m2ZJh2pb3E6C&index=4"
                  target="_blank"
                )
                  span Abrir video
                  i.fas.fa-file-video

          .row.justify-content-center(titulo="5")
            .col-lg-2.mb-4.mb-md-0.col-7.col-md-4
              img.mb-4(src="@/assets/curso/temas/t3/5.png")
            .col-lg-5
              h4 Enhebrado del hilo para aguja de puntada de filete
              p Consulte el video:
              .col-sm-auto
                a.boton.color-acento-botones.texto-blanco(
                  href="https://www.youtube.com/watch?v=7MPnUCYW0Qg&list=PLkc5n6npRWkjS1Oni_VR8m2ZJh2pb3E6C&index=3"
                  target="_blank"
                )
                  span Abrir video
                  i.fas.fa-file-video

          .row.justify-content-center(titulo="6")
            .col-lg-2.mb-4.mb-md-0.col-7.col-md-4
              img.mb-4(src="@/assets/curso/temas/t3/6.png")
            .col-lg-5
              h4 Enhebrado del hilo para aguja de puntada de seguridad
              p Consulte el video:
              .col-sm-auto
                a.boton.color-acento-botones.texto-blanco(
                  href="https://www.youtube.com/watch?v=Y4GHFnR_Hq0&list=PLkc5n6npRWkjS1Oni_VR8m2ZJh2pb3E6C&index=6"
                  target="_blank"
                )
                  span Abrir video
                  i.fas.fa-file-video

          .row.justify-content-center(titulo="7")
            .col-lg-2.mb-4.mb-md-0.col-7.col-md-4
              img.mb-4(src="@/assets/curso/temas/t3/7.png")
            .col-lg-6
              h4 Enhebrado del hilo para looper de puntada de seguridad
              p Consulte el video:
              .col-sm-auto
                a.boton.color-acento-botones.texto-blanco(
                  href="https://www.youtube.com/watch?v=Y_KBM8O2lIY&list=PLkc5n6npRWkjS1Oni_VR8m2ZJh2pb3E6C&index=2"
                  target="_blank"
                )
                  span Abrir video
                  i.fas.fa-file-video

          .row.justify-content-center(titulo="8")
            .col-lg-2.mb-4.mb-md-0.col-7.col-md-4
              img.mb-4(src="@/assets/curso/temas/t3/8.png")
            .col-lg-3
              h4 Prueba de costura
              p Consulte el video:
              .col-sm-auto
                a.boton.color-acento-botones.texto-blanco(
                  href="https://www.youtube.com/watch?v=uv3mjlOymIE&list=PLkc5n6npRWkjS1Oni_VR8m2ZJh2pb3E6C&index=12"
                  target="_blank"
                )
                  span Abrir video
                  i.fas.fa-file-video

          .row.justify-content-center(titulo="9")
            .col-lg-2.mb-4.mb-md-0.col-7.col-md-4
              img.mb-4(src="@/assets/curso/temas/t3/9.png")
            .col-lg-4
              h4 Ajuste de la tensión de la máquina
              p Consulte el video:
              .col-sm-auto
                a.boton.color-acento-botones.texto-blanco(
                  href="https://www.youtube.com/watch?v=PMS6lRthWnQ&list=PLkc5n6npRWkjS1Oni_VR8m2ZJh2pb3E6C&index=10"
                  target="_blank"
                )
                  span Abrir video
                  i.fas.fa-file-video

          .row.justify-content-center(titulo="10")
            .col-lg-2.mb-4.mb-md-0.col-7.col-md-4
              img.mb-4(src="@/assets/curso/temas/t3/10.png")
            .col-lg-3
              h4 Calibración de la puntada
              p Consulte el video:
              .col-sm-auto
                a.boton.color-acento-botones.texto-blanco(
                  href="https://www.youtube.com/watch?v=Cf2gPlXy88s&list=PLkc5n6npRWkjS1Oni_VR8m2ZJh2pb3E6C&index=9"
                  target="_blank"
                )
                  span Abrir video
                  i.fas.fa-file-video

          .row.justify-content-center(titulo="11")
            .col-lg-2.mb-4.mb-md-0.col-7.col-md-4
              img.mb-4(src="@/assets/curso/temas/t3/11.png")
            .col-lg-3
              h4 Ajuste del nivel de arrastre
              p Consulte el video:
              .col-sm-auto
                a.boton.color-acento-botones.texto-blanco(
                  href="https://www.youtube.com/watch?v=Nz1r5rl-xXQ&list=PLkc5n6npRWkjS1Oni_VR8m2ZJh2pb3E6C&index=8"
                  target="_blank"
                )
                  span Abrir video
                  i.fas.fa-file-video

          .row.justify-content-center(titulo="12")
            .col-lg-2.mb-4.mb-md-0.col-7.col-md-4
              img.mb-4(src="@/assets/curso/temas/t3/12.png")
            .col-lg-3
              h4 Verificación del nivel de aceite
              p Consulte el video:
              .col-sm-auto
                a.boton.color-acento-botones.texto-blanco(
                  href="https://www.youtube.com/watch?v=Omjyi5Wbq_8&list=PLkc5n6npRWkjS1Oni_VR8m2ZJh2pb3E6C&index=7"
                  target="_blank"
                )
                  span Abrir video
                  i.fas.fa-file-video

          .row.justify-content-center(titulo="13")
            .col-lg-2.mb-4.mb-md-0.col-7.col-md-4
              img.mb-4(src="@/assets/curso/temas/t3/13.png")
            .col-lg-5
              h4 Verificación de los dispositivos de seguridad
              p Consulte el video:
              .col-sm-auto
                a.boton.color-acento-botones.texto-blanco(
                  href="https://www.youtube.com/watch?v=SqvF1VSJouU&list=PLkc5n6npRWkjS1Oni_VR8m2ZJh2pb3E6C&index=11"
                  target="_blank"
                )
                  span Abrir video
                  i.fas.fa-file-video        
                  
    .row.justify-content-center.align-items-center.mb-4.fondo02(data-aos="zoom-in-left")
        .col-lg-5.d-none.d-lg-block
          img(src='@/assets/curso/temas/t3/img02.png', alt='')
        .col-lg-7
          .p-4
            .d-flex.align-items-start
              .row
                .col-lg-12
                  p La correcta ejecución de esta secuencia permite preparar la máquina para las operaciones de confección, reducir fallas durante la costura, mejorar la calidad de las uniones y garantizar condiciones seguras de trabajo. Antes de iniciar el ensamble de la camiseta deportiva, se recomienda revisar cada uno de los pasos y verificar que la máquina se encuentre en condiciones óptimas de funcionamiento.
                  p Una vez realizada la puesta a punto de la máquina, es posible ejecutar las operaciones básicas de confección que intervienen en el ensamble de la camiseta deportiva. Estas operaciones permiten desarrollar habilidades de manejo, control del material y precisión en la formación de la puntada.

    .row.justify-content-start.mb-4(data-aos="zoom-in-left")
      .col-sm-12.col-lg-12
        .d-flex.align-items-center
          img.w-card-icon(src="@/assets/curso/temas/t1/camisa.svg")
          h3.bg2.py-2.w-card-text Operaciones básicas para el manejo de la máquina fileteadora

    p Los videos dedicados a las operaciones básicas con máquina fileteadora brindan al aprendiz las herramientas necesarias para ejecutar con destreza maniobras fundamentales como unir piezas, realizar filetes rectos y rematar costuras. Este contenido complementario resulta esencial para reforzar la técnica operativa, mejorar la precisión en el acabado de prendas y consolidar la confianza en el manejo de esta maquinaria especializada en el proceso de confección industrial.


















































































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
