<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Políticas internas de una organización
    .row
      .col-md-4.mb-md-0.mb-4
        figure
          img(src="@/assets/curso/tema3/1.png" data-aos="fade-right")
      .col-md-8
        p(data-aos="fade-up") Aquellas organizaciones donde la seguridad cuenta con el soporte de la alta gerencia, generalmente desarrollarán y adquirirán aplicaciones que cumplen con principios básicos de seguridad. En cambio, es muy poco probable que organizaciones que no cuentan con el soporte de la gerencia, o que simplemente no se preocupan por la seguridad, desarrollen aplicaciones seguras. Cada organización segura documenta su apetito por el riesgo en su Política de Seguridad de la información, haciendo de esa manera que sea fácil determinar que riesgos serán aceptados, mitigados o asignados.
        p.mt-4(data-aos="fade-up") Las organizaciones inseguras simplemente no conocen donde se encuentra este límite, por lo tanto es probable que cuando se van a ejecutar proyectos dirigidos por este tipo de organizaciones y seleccionan los controles a implementar, estos terminan siendo inadecuados o insuficientes. La mayoría de las organizaciones produce políticas de Seguridad de la información derivadas de la ISO 17799 o del marco de trabajo COBIT, u ocasionalmente los dos o uno de los estándares. No hay una regla infalible o rápida que dicte cómo crear políticas de seguridad de la información, pero en general se debe tener en cuenta los siguientes aspectos:

    br
    br
    .row.mt-5.col-md-10.m-auto
      .col-lg-6.mb-5.mb-lg-0
        div(style="height:100%")
          .pb-4.ps-5.pe-5.text-center(style="background-color:#6ACEAE;border-top-left-radius:5px;border-top-right-radius:5px;")
            img(src="@/assets/curso/tema3/2.png" data-aos="zoom-in-up" style="position:relative;display:inline;max-width:200px;margin-top:-75px;")
          .p-5(style="background-color:#C7EDE0;")             
            p(data-aos="fade-up") Si la organización cotiza en bolsa en la mayoría de los países, debe tener una política de seguridad de la información.
      .col-lg-6.mb-5.mb-lg-0
        div(style="height:100%")
          .pb-4.ps-5.pe-5.text-center(style="background-color:#294DDC;border-top-left-radius:5px;border-top-right-radius:5px;")
            img(src="@/assets/curso/tema3/3.png" data-aos="zoom-in-up" style="position:relative;display:inline;max-width:200px;margin-top:-75px;")
          .p-5(style="background-color:#E5EAFF;")             
            p(data-aos="fade-up") Si la organización es propia pero posee cierto número de empleados y desarrolladores, probablemente necesite una política.

    .row.mt-5.cont_tema3_1.p-4(style="position:relative;")
      .col-md-1.mb-4.mb-md-0(style="place-self:center;position:relative")
        figure.text-center
          img(src="@/assets/curso/tema3/4.png" data-aos="fade-right" style="display:inline;max-width:90px;")
      .col-md-11(style="place-self:center;position:relative")
        p.mb-0(data-aos="fade-up") Es perfectamente correcto mezclar y combinar controles de COBIT y de ISO 17799 y casi cualquier otro estándar de seguridad de la información; rara vez se encuentran en desacuerdo en los detalles. El método de producción puede ser a veces difícil – #[strong en el caso de requerir una política certificada, se necesitara involucrar a firmas calificadas para que ayuden a la organización.]



</template>

<script>
export default {
  name: 'Tema3',
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
.cont_tema3_1:before
  content: ''
  position: absolute
  width: 115%
  left: -7%
  height: 100%
  top: 0
  background-color: #FFF5DE
</style>
