<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    p La confección de camisetas deportivas exige mucho más que unir piezas mediante operaciones de costura. Para obtener una prenda funcional y con acabados acordes con las especificaciones técnicas, es necesario preparar adecuadamente el puesto de trabajo, seleccionar y organizar los materiales, seguir una secuencia lógica de ensamble y aplicar medidas de seguridad durante todo el proceso. Estos elementos permiten mantener la continuidad de la producción, reducir errores y favorecer el cumplimiento de los criterios de calidad establecidos.
    
    .bloque-texto-g.bg1.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require_src('@/assets/curso/portada/intro.png')})`}"
      )
      .bloque-texto-g__texto1.p-4
        p.mb-0 El componente formativo Confección de camisetas deportivas aborda estos aspectos desde una perspectiva técnica, operativa y preventiva. A lo largo de su desarrollo se analizarán la organización del puesto de trabajo, la preparación de telas e insumos, las operaciones necesarias para confeccionar una camiseta deportiva y las prácticas de seguridad y salud aplicables al entorno productivo. De esta manera, se fortalecen los conocimientos requeridos para ejecutar las actividades de confección con orden, precisión y responsabilidad.
          br

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
