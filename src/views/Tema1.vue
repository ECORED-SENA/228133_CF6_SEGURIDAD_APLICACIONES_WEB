<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Monitorear la seguridad #[em web]

    .row
      .col-md-4.mb-4.mb-md-0(style="place-self:center;")
        figure
          img(src="@/assets/curso/tema1/1.png" data-aos="fade-right")
      .col-md-8(style="place-self:center;")
        p(data-aos="fade-up") Las empresas y organizaciones deben cuidar muy bien sus sistemas y equipos informáticos, dado que en la actualidad existen muchos tipos de ataques que podrían afectar la seguridad de la información y de los datos y no solo basta con tener un antivirus instalado a pesar que sea de pago, este de igual manera está propenso a recibir ataques y a generar bloqueos que afecten todo el sistema operativo, provocando pérdida de la información.
        p.mt-4(data-aos="fade-up") Por tanto, se hace necesario realizar monitoreo activo y permanente de amenazas, donde se lleven a cabo pruebas de verificación del correcto funcionamiento y de la no existencia de brechas de seguridad, amenazas en el sistema o programas obsoletos que se puedan convertir en la entrada de piratas informáticos y finalmente, revisar periódicamente el cumplimiento de las medidas de seguridad, acatando las normas, metodologías y estándares.

    .row.cont_tema1.mt-5.p-4(style="position:relative;")
      .col-md-1.mb-4.mb-md-0(style="place-self:center;position:relative")
        figure.text-center
          img(src="@/assets/curso/tema1/2.png" data-aos="fade-right" style="display:inline;max-width:200px;")
      .col-md-11(style="place-self:center;position:relative")
        p.mb-0(data-aos="fade-up") El monitoreo activo de amenazas es un factor muy importante y que debemos tener muy en cuenta y que se debe aplicar sin importar si somos usuarios domésticos o una gran empresa, porque es esencial detectar lo antes posible las amenazas.



</template>

<script>
export default {
  name: 'Tema1',
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
.cont_tema1:before
  content: ''
  position: absolute
  width: 115%
  left: -7%
  height: 100%
  top: 0%
  background-color: #FFF5DE
</style>
