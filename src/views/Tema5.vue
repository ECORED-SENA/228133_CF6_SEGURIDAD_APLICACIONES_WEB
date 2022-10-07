<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Métricas

    p(data-aos="fade-up") Las métricas se encuentran divididas en seguridad, red, #[em software] y calidad, los cuales se describen a continuación:

    TabsB.color-acento-contenido.mt-5
      .py-4.py-md-5(titulo="Métricas en procesos de seguridad" :icono="require('@/assets/curso/tema5/1.png')")
        .row.p-4
          .col-md-6.mb-4.mb-md-0(style="place-self:center;")
            h4 Métricas en procesos de seguridad
            ul.lista-ul.mt-4
              li 
                i.fas.fa-check-circle(style="color:#6ACEAE;")
                | Medición de los procesos y procedimientos Implica alta utilidad de la seguridad políticas y procesos.
              li 
                i.fas.fa-check-circle(style="color:#6ACEAE;")
                | La relación entre indicadores y nivel de seguridad no está claramente definida.
              li 
                i.fas.fa-check-circle(style="color:#6ACEAE;")
                | Cumplimiento / Gobierno impulsado generalmente apoya una mayor seguridad. 
              li 
                i.fas.fa-check-circle(style="color:#6ACEAE;")
                | Impacto real difícil de definir.
          .col-md-6(style="place-self:center;")
            figure
              img(src='@/assets/curso/tema5/5.png')
      .py-4.py-md-5(titulo="Métricas de red" :icono="require('@/assets/curso/tema5/2.png')")
        .row.p-4
          .col-md-6.mb-4.mb-md-0(style="place-self:center;")
            h4 Métricas de red
            ul.lista-ul.mt-4
              li 
                p #[i.fas.fa-check-circle(style="color:#6ACEAE;")] Impulsado por productos (#[em firewalls], IDS, etc.).
              li 
                p #[i.fas.fa-check-circle(style="color:#6ACEAE;")] Disponible.
              li 
                p #[i.fas.fa-check-circle(style="color:#6ACEAE;")] Ampliamente utilizado. 
              li 
                p #[i.fas.fa-check-circle(style="color:#6ACEAE;")] Brinda una sensación de control.
              li 
                p #[i.fas.fa-check-circle(style="color:#6ACEAE;")] Gráficos agradables.
              li 
                p #[i.fas.fa-check-circle(style="color:#6ACEAE;")] Puede ser engañoso.
          .col-md-6(style="place-self:center;")
            figure
              img(src='@/assets/curso/tema5/6.png')
      .py-4.py-md-5(titulo="Métricas de <em>software</em>" :icono="require('@/assets/curso/tema5/3.png')")
        .row.p-4
          .col-md-6.mb-4.mb-md-0(style="place-self:center;")
            h4 Métricas de #[em software]
            ul.lista-ul.mt-4
              li 
                p #[i.fas.fa-check-circle(style="color:#6ACEAE;")] Medidas de &nbsp;#[em software]&nbsp; están problemáticas (LOC, FPS, Complejidad etc.).
              li 
                p #[i.fas.fa-check-circle(style="color:#6ACEAE;")] Dependen del contexto y son sensibles al entorno. 
              li 
                p #[i.fas.fa-check-circle(style="color:#6ACEAE;")] Dependiente de arquitectura.
          .col-md-6(style="place-self:center;")
            figure
              img(src='@/assets/curso/tema5/7.png')
      .py-4.py-md-5(titulo="Métricas de calidad" :icono="require('@/assets/curso/tema5/4.png')")
        .row.p-4
          .col-md-6.mb-4.mb-md-0(style="place-self:center;")
            h4 Métricas de calidad
            ul.lista-ul.mt-4
              li 
                i.fas.fa-check-circle(style="color:#6ACEAE;")
                | Correctitud (Grado de operación del programa respecto a los requerimientos).
              li 
                i.fas.fa-check-circle(style="color:#6ACEAE;")
                | Mantenibilidad (Grado en el que un programa puede cambiar).
              li 
                i.fas.fa-check-circle(style="color:#6ACEAE;")
                | Integridad (Grado de resistencia ante pérdida de información).
              li 
                i.fas.fa-check-circle(style="color:#6ACEAE;")
                | Usabilidad (Grado de facilidad de uso).
          .col-md-6(style="place-self:center;")
            figure
              img(src='@/assets/curso/tema5/8.png')






</template>

<script>
export default {
  name: 'Tema5',
  components: {},
  data: () => ({
    indicadorTarjetaSlide: true,
    indicadorTarjetaFlip: true,
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
<style lang="sass">
.tabs-b__tab
  border-bottom: 0
.tabs-b.color-acento-contenido .tabs-b__tab--active img
  filter: none
.tabs-b__tab img
  filter: grayscale(1)
</style>
