<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 5
      h1 Información base  
    p.mb-5 La información base engloba los datos fundamentales y las variables esenciales que se utilizan para evaluar el desempeño del cultivo acuícola. Entre estos parámetros se incluyen aspectos como la densidad de siembra, la biomasa inicial, las condiciones del agua y la calidad del alimento suministrado. Estos datos constituyen la base sobre la cual se construyen los análisis productivos y sanitarios del cultivo.
    .titulo-sexto.color-acento-contenido.mb-2(data-aos="fade-right")
      h5 Figura 1.
      span Información base
    figure(data-aos="zoom-in").mb-5
      img(src='@/assets/curso/tema5/img1.svg', alt='La imagen presenta un esquema conceptual sobre el cálculo de los indicadores técnicos de la producción acuícola, mostrando que este proceso se explica desde tres componentes principales: los indicadores técnicos (conceptos, tipos, importancia, cálculos e interpretación), los registros productivos (conceptos, tipos, formatos y diligenciamiento) y la matemática aplicada como base para el análisis.').m-auto
    p.mb-5 El manejo técnico del cultivo acuícola se fundamenta en la recolección y análisis de variables base que permiten establecer un punto de referencia claro para el seguimiento del sistema productivo. Estas variables constituyen el soporte inicial para interpretar cambios, evaluar resultados y proyectar el comportamiento del cultivo a lo largo del ciclo:
    TabsC.color-acento-contenido.mb-0(data-aos="zoom-in")
      .py-3.py-md-4(titulo="Variables base en acuicultura")
        .row.justify-content-center.align-items-center
          .col-xl-5.order-2.order-lg-1
            figure
              img(src='@/assets/curso/tema5/img2.png', alt="" ).m-auto
          .col-xl-7.order-1.order-lg-2.mb-4.mb-lg-0
            h4.txt--purpura Variables base en acuicultura
            p.mb-0 Las variables base son datos fundamentales del cultivo, como peso inicial, temperatura, oxígeno disuelto y nutrientes, que sirven como referencia para evaluar y monitorear continuamente su desempeño.
      .py-3.py-md-4(titulo="Importancia y empleo de la información base")
        .row.justify-content-center.align-items-center
          .col-xl-5.order-2.order-lg-1
            figure
              img(src='@/assets/curso/tema5/img3.png', alt="" ).m-auto
          .col-xl-7.order-1.order-lg-2.mb-4.mb-lg-0
            h4.txt--purpura Importancia y empleo de la información base
            p.mb-0 La información base permite comparar datos con estándares, identificar desviaciones y ajustar el manejo para optimizar la producción y la salud del cultivo.
</template>

<script>
export default {
  name: 'Tema5',
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
