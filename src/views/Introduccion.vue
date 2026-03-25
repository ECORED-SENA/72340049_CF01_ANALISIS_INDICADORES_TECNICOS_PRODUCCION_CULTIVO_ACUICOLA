<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .bloque-texto-g.bloque-texto-g--inverso.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-0(data-aos="zoom-in")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/intro/img1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 El análisis de indicadores técnicos es un pilar de la acuicultura moderna, pues permite evaluar con objetividad el desempeño productivo, sanitario y ambiental. Mediante el seguimiento de variables clave como el crecimiento, la conversión alimenticia y la calidad del agua, es posible sustentar decisiones técnicas en datos precisos. 
        br
        p.mb-0 Ante la expansión del sector acuícola colombiano y su impacto en la seguridad alimentaria, dominar estos indicadores es vital para asegurar la eficiencia y la sostenibilidad. Este curso ofrece las herramientas conceptuales, matemáticas y ofimáticas necesarias para gestionar información técnica y formular acciones que fortalezcan la competitividad del sector.
</template>

<script>
export default {
  name: 'Introduccion',
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
