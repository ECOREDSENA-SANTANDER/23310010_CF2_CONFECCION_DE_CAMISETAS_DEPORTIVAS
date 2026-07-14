<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 1
        h1 Puesto de trabajo
    
      .bloque-texto-g.bloque-texto-g--inverso.color-primario.p-3.p-sm-4.p-md-5.mb-4
        .bloque-texto-g__img(
          :style="{'background-image': `url(${require_src('@/assets/curso/temas/t1/img01.png')})`}"
        )
        .bloque-texto-g__texto.p-4
          p.mb-0 La productividad en la industria de la confección se encuentra estrechamente vinculada con la organización técnica del puesto de trabajo, ya que este constituye el punto donde convergen recursos humanos, maquinaria, insumos, métodos operativos y condiciones de seguridad. Su configuración no responde únicamente a criterios de ubicación física, sino también a decisiones relacionadas con la secuencia de operaciones, la accesibilidad de los materiales, la economía del movimiento, la postura de trabajo y la reducción de tiempos improductivos. De esta disposición depende, en buena medida, la estabilidad del proceso, la regularidad en la ejecución de las tareas y la capacidad para mantener estándares consistentes de calidad durante la producción.
            br

      p Un puesto de trabajo diseñado bajo criterios técnicos favorece la continuidad operativa, disminuye los desplazamientos innecesarios, reduce la fatiga derivada de posturas sostenidas o movimientos repetitivos y fortalece el control de los riesgos asociados con la actividad. También incide en la precisión de las operaciones, la adecuada manipulación de herramientas y equipos, y la conservación de ritmos de trabajo compatibles con las metas de producción establecidas. Por esta razón, el puesto de trabajo no debe entenderse como un espacio aislado dentro de la planta, sino como una unidad funcional determinante para el desempeño global del sistema productivo en la confección industrial.

      .row.justify-content-center.align-items-end.mb-4.fondo01
        .col-lg-7
          .titulo-sexto.color-acento-contenido(data-aos='fade-right')
            h5 Figura 1. 
            span Puesto de trabajo en confección
          img(src='@/assets/curso/temas/t1/fig1.png', alt='')







              

  </template>

<script>
export default {
  name: 'Tema1',
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
