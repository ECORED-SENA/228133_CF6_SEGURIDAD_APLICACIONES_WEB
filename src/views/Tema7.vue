<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 7
      h1 Informe de monitoreo

    p(data-aos="fade-up") Con base en las métricas antes descritas, se deben generar los formatos de indicadores para generar el informe de resultados; a continuación se ilustra un formato de presentación de indicador unido a los reportes generados desde las herramientas de software.

    .titulo-sexto.color-acento-contenido.mt-5
      h5 Figura 2
      span Ejemplo de informe de monitoreo

    figure.mt-4
      img(src="@/assets/curso/tema7/1.svg" data-aos="zoom-in-up")




</template>

<script>
export default {
  name: 'Tema7',
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
<style lang="sass"></style>
