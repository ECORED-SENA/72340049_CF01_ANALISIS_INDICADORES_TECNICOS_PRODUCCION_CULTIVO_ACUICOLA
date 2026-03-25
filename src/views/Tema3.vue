<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Identificación de desviaciones técnicas 
    .bloque-texto-g.bloque-texto-g--inverso.color-secundario.p-3.p-sm-4.p-md-5.mb-5(data-aos="zoom-in")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema3/img1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 El comportamiento de los indicadores técnicos en acuicultura está influenciado por factores ambientales, nutricionales, sanitarios y administrativos que interactúan entre sí. Comprender estos factores permite garantizar la sostenibilidad del cultivo, el cumplimiento normativo y la rentabilidad del sistema productivo.
    p.mb-5 Se invita al aprendiz a explorar los principales factores ambientales, nutricionales, sanitarios, de manejo productivo, administrativos y de gestión técnica que intervienen en la producción acuícola, con el fin de comprender cómo influyen en el comportamiento del cultivo y en la toma de decisiones técnicas.
    .row.align-items-center.mb-5
      .col-xl-auto
        figure(data-aos="fade-right").d-none.d-xl-block
          img(src="@/assets/curso/tema3/img2.png", alt="" ).m-auto
      .col-xl
        AcordionA(tipo="a" clase-tarjeta="tarjeta acordeonA")(data-aos="fade-left")
          .row(titulo="A.	Factores ambientales").ajuste-cajaAcordion
            p Las condiciones del agua determinan el desempeño productivo del cultivo.
            h5 Temperatura:
            ul.fa-ul.mb-3
              li.mb-1
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Regula crecimiento y metabolismo.
              li.mb-0
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Valores extremos generan estrés y menor consumo.
            h5 Oxígeno disuelto:
            ul.fa-ul.mb-3
              li.mb-1
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Esencial para la respiración.
              li.mb-0
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Niveles bajos reducen crecimiento y supervivencia.
            h5 Amonio y nitritos: 
            ul.fa-ul.mb-3
              li.mb-1
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Provienen de desechos orgánicos.
              li.mb-0
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Altas concentraciones son tóxicas y afectan la producción.
          .row(titulo="B.	Factores nutricionales").ajuste-cajaAcordion
            p La alimentación es el mayor costo operativo y afecta directamente los indicadores productivos.
            h5 Calidad del alimento:
            ul.fa-ul.mb-3
              li.mb-1
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Balance nutricional y digestibilidad adecuados.
              li.mb-0
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Baja calidad aumenta el FCA y reduce el crecimiento.
            h5 Cantidad de alimento:
            ul.fa-ul.mb-3
              li.mb-1
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Sobrealimentación → desperdicio y mala calidad del agua.
              li.mb-0
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Subalimentación → menor crecimiento y biomasa.
            h5 Frecuencia de alimentación:
            ul.fa-ul.mb-3
              li.mb-1
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Debe ajustarse a tamaño, edad y biomasa.
              li.mb-0
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Una frecuencia inadecuada reduce la eficiencia productiva.
          .row(titulo="C.	Factores sanitarios").ajuste-cajaAcordion
            p La sanidad acuícola es prioritaria para la prevención y control de enfermedades.
            h5 Presencia de patógenos:
            p.mb-0 Virus, bacterias, hongos y parásitos afectan:
            ul.fa-ul.mb-3
              li.mb-1
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Supervivencia.
              li.mb-1
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Crecimiento.
              li.mb-0
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Conversión alimenticia y biomasa.
            h5 Estrés:
            ul.fa-ul.mb-3
              li.mb-1
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Causado por manipulación, cambios de temperatura, transporte y alta densidad.
              li.mb-0
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Reduce la inmunidad y el desempeño productivo.
            h5 Manejo inadecuado:
            ul.fa-ul.mb-3
              li.mb-1
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Procedimientos incorrectos generan lesiones, mortalidad y pérdida de apetito.
              li.mb-0
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | El uso de protocolos técnicos reduce riesgos.
    .row.align-items-center.mb-5
      .col-xl
        AcordionA(tipo="a" clase-tarjeta="tarjeta acordeonA")(data-aos="fade-right")
          .row(titulo="D.	Factores de manejo productivo").ajuste-cajaAcordion
            p La gestión operativa influye directamente en el desempeño de los indicadores.
            h5 Densidad de siembra:
            p.mb-0 Altas densidades generan:
            ul.fa-ul.mb-3
              li.mb-1
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Competencia por alimento.
              li.mb-1
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Menor oxígeno.
              li.mb-0
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Acumulación de desechos.
            h5 Clasificación de tallas:
            p.mb-0 Falta de uniformidad provoca:
            ul.fa-ul.mb-3
              li.mb-1
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Competencia desigual.
              li.mb-1
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Canibalismo.
              li.mb-0
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Crecimiento irregular.
            h5 Renovación de agua
            ul.fa-ul.mb-3
              li.mb-1
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Mantiene estabilidad de oxígeno, pH y compuestos nitrogenados.
              li.mb-0
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Favorece el equilibrio del sistema productivo.
          .row(titulo="E.	Factores administrativos y de gestión técnica").ajuste-cajaAcordion
            p Un sistema productivo puede fallar por debilidades administrativas y no solo biológicas.
            h5 Registros incompletos:
            ul.fa-ul.mb-3
              li.mb-1
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Dificultan la interpretación de indicadores.
              li.mb-0
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Impiden detectar desviaciones y cumplir la normativa.
            h5 Errores en medición:
            ul.fa-ul.mb-3
              li.mb-0
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Equipos descalibrados o muestreos incorrectos generan decisiones equivocadas.
            h5 Falta de seguimiento técnico:
            ul.fa-ul.mb-3
              li.mb-0
                span.fa-li
                  i.fas.fa-arrow-alt-circle-right
                | Produce manejo empírico, decisiones sin soporte técnico y pérdidas económicas.
      .col-xl-auto
        figure(data-aos="fade-left").d-none.d-xl-block
          img(src="@/assets/curso/tema3/img3.png", alt="" ).m-auto
    p.mb-0 El enfoque integral en acuicultura reconoce que los factores productivos están interrelacionados, donde un manejo inadecuado puede afectar la calidad del agua, el crecimiento y la rentabilidad. Por ello, la gestión debe integrar control ambiental, bioseguridad, nutrición, manejo técnico, administración y cumplimiento normativo. 
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
