<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p La confección de una camiseta deportiva comienza con la preparación del entorno en el que se desarrollará el proceso. La distribución del puesto de trabajo, la ubicación de la maquinaria y la disponibilidad de herramientas y equipos permiten realizar las operaciones con orden, continuidad y seguridad.
    p El proceso continúa con la selección de las telas y los insumos, la revisión de sus características y la ejecución del tendido, el marcado y el corte. Después, las piezas se verifican, agrupan e identifican antes de ingresar al ensamble, evitando faltantes, mezclas de tallas o errores que puedan afectar la calidad de la prenda.
    p Con los materiales preparados, la máquina fileteadora y la máquina plana industrial de una aguja intervienen en las diferentes operaciones de unión y acabado. Su puesta a punto, el manejo técnico y el seguimiento de la secuencia operativa permiten integrar progresivamente las piezas hasta completar la camiseta deportiva tipo polo.
    p A lo largo de todo el proceso, la identificación de los riesgos laborales, la aplicación de técnicas ergonómicas y el reporte oportuno de incidentes y accidentes contribuyen a proteger la salud y a mantener condiciones adecuadas de trabajo. El esquema conceptual Confección de camisetas deportivas reúne estos elementos y representa su articulación dentro del proceso productivo.

    .row.justify-content-center
      .col-lg-102.mb-5.bgs.p-4.brad
        figure
          img(src="@/assets/curso/sintesis.svg", alt="Mapa conceptual sobre la confección de camisetas deportivas, organizado en cuatro ramas principales. La primera presenta el puesto de trabajo, su distribución, maquinaria, herramientas y relación con la productividad, la ergonomía y la seguridad. La segunda aborda la preparación de materiales mediante la selección de telas e insumos, la revisión, el tendido, el marcado, el corte y la organización de las piezas. La tercera reúne la puesta a punto y el manejo de la máquina fileteadora y la máquina plana de una aguja, junto con las operaciones básicas y la secuencia de ensamble. La cuarta integra los riesgos laborales, las medidas ergonómicas, las pausas activas, la manipulación segura de cargas y el reporte de incidentes y accidentes.")
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
