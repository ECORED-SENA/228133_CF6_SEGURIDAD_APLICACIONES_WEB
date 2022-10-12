<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 6
      h1 Herramientas de #[em software]

    .row
      .col-md-4.mb-md-0.mb-4(style="place-self:center;")
        figure
          img(src="@/assets/curso/tema6/1.png" data-aos="fade-right")
      .col-md-8(style="place-self:center;")
        p(data-aos="fade-up") Las herramientas de #[em software] tienen el objetivo de facilitar, optimizar y mejorar el desempeño del trabajo realizado; estas herramientas ofrecen soluciones, las cuales se aplica en diferentes áreas de una empresa y por tanto ayudan en el desarrollo de tareas desde las más complejas hasta las más simples.
        p.mt-4(data-aos="fade-up") El video a continuación habla de algunas herramientas, que le serán de utilidad en la implementación de aplicaciones #[em web]:

    .row.mt-5
      .col-lg-4.mb-4.mb-lg-0
        .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.p-5(:style="{'background-image': `url(${require('@/assets/curso/tema6/5.png')})`}")
              .text-center
                span(style="background-color:#fff;padding:.5rem 2rem;font-weight:bold;font-size:17px;color:#12263F;border-radius:50px;") Elasticsearch
              p.mt-5(style="color:#12263F;") Es un #[strong(style="color:#12263F;") motor de búsqueda que se basa en Lucene], el cual permite realizar búsquedas de texto, autocompletado, soporte de geolocalización entre otros.
              p.mt-4(style="color:#12263F;") Se puede definir a #[strong(style="color:#12263F;") Elasticsearch] como un base de datos NoSQL orientada a documentos JSON, los cuales pueden ser consultados, creados, actualizados o borrados mediante un sencillo API Rest.
            .tarjeta-flip__contenido.p-5.p-xl-5.mt-5(style="background-color:#FFF4D6;")
              figure
                img(src="@/assets/curso/tema6/2.png")
              .text-center.mt-5
                span(style="background-color:#6ACEAE;padding:.5rem 2rem;font-weight:bold;font-size:17px;color:#12263F;border-radius:50px;") Elasticsearch
      .col-lg-4.mb-4.mb-lg-0
        .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.p-5(:style="{'background-image': `url(${require('@/assets/curso/tema6/6.png')})`}")
              .text-center
                span(style="background-color:#fff;padding:.5rem 2rem;font-weight:bold;font-size:17px;color:#12263F;border-radius:50px;") Logstash
              p.mt-5(style="color:#12263F;") Es una herramienta desarrollada por #[strong(style="color:#12263F;") Elastic] y que funciona bajo la #[strong(style="color:#12263F;") JVM de Java], la cual permite administrar los #[em(style="color:#12263F;") logs] de nuestras aplicaciones, de manera que se puede usar  para recolectar, parsear y guardar los #[em(style="color:#12263F;") logs] para búsquedas posteriores.
            .tarjeta-flip__contenido.p-5.p-xl-5.mt-5(style="background-color:#E5FDF3;")
              figure
                img(src="@/assets/curso/tema6/3.png")
              .text-center.mt-5
                span(style="background-color:#F3C035;padding:.5rem 2rem;font-weight:bold;font-size:17px;color:#12263F;border-radius:50px;") Logstash
      .col-lg-4.mb-4.mb-lg-0
        .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img.p-5(:style="{'background-image': `url(${require('@/assets/curso/tema6/5.png')})`}")
              .text-center
                span(style="background-color:#fff;padding:.5rem 2rem;font-weight:bold;font-size:17px;color:#12263F;border-radius:50px;") Kibana
              p.mt-5(style="color:#12263F;") Es un #[strong(style="color:#12263F;font-style:italic;") dashboard] de recopilación de gráficos, grafos, métricas, búsquedas y mapas que se recopilaron en un solo panel. Los #[em(style="color:#12263F;") dashboards] permiten obtener información de un vistazo sobre datos desde varias perspectivas y permiten a los usuarios explorar los detalles.
            .tarjeta-flip__contenido.p-5.p-xl-5.mt-5(style="background-color:#FFF4D6;")
              figure
                img(src="@/assets/curso/tema6/4.png")
              .text-center.mt-5
                span(style="background-color:#6ACEAE;padding:.5rem 2rem;font-weight:bold;font-size:17px;color:#12263F;border-radius:50px;") Kibana

    div.mt-5


</template>

<script>
export default {
  name: 'Tema6',
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
.tarjeta-flip__img
  border-radius: 0px !important
</style>
