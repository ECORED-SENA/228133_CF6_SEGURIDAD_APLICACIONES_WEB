<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Indicadores

    p(data-aos="fade-up") La creación de indicadores de gestión está orientada principalmente en la #[strong medición de efectividad, eficiencia y eficacia de los componentes de implementación y gestión definidos en el modelo de operación del marco de seguridad y privacidad de la información], indicadores que servirán como insumo para el componente de mejora continua permitiendo adoptar decisiones de mejora.

    br
    .row.mt-5.cont_tema4_1(style="position:relative;")
      .col-md-8.mb-4.mb-md-0.p-5(style="position:relative;place-self:center;")
        h4(data-aos="fade-up") Los objetivos de estos procesos de medición en seguridad de la información son:
        ol.lista-ol--cuadro.lista-ol--separador.mt-4
          li(data-aos="fade-up")
            .lista-ol--cuadro__vineta
              span(style="color:initial;font-weight:bold;") 1
            | Evaluar la efectividad de la implementación de los controles de seguridad.
          li(data-aos="fade-up")
            .lista-ol--cuadro__vineta
              span(style="color:initial;font-weight:bold;") 2
            | Evaluar la eficiencia del Modelo de Seguridad y Privacidad de la Información al interior de la entidad. 
          li(data-aos="fade-up")
            .lista-ol--cuadro__vineta
              span(style="color:initial;font-weight:bold;") 3
            | Proveer estados de seguridad que sirvan de guía en las revisiones del Modelo de Seguridad y Privacidad de la Información, facilitando mejoras en seguridad de la información y nuevas entradas a auditar. 
          li(data-aos="fade-up")
            .lista-ol--cuadro__vineta
              span(style="color:initial;font-weight:bold;") 4
            | Comunicar valores de seguridad al interior de la entidad. 
          li(data-aos="fade-up")
            .lista-ol--cuadro__vineta
              span(style="color:initial;font-weight:bold;") 5
            | Servir como insumos al plan de análisis y tratamiento de riesgos.
      .col-md-4.pb-4(style="position:relative;place-self:center;")
        figure
          img(src="@/assets/curso/tema4/1.png" data-aos="zoom-in-left" style="position:relative;margin-top:-70px;")

    p.mt-5(data-aos="fade-up") A continuación se profundizará sobre la temática de indicadores:

    ImagenInfografica.color-acento-botones.mt-5.col-lg-6.m-auto
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/tema4/2.svg' data-aos="zoom-in-up")
      .tarjeta.color-acento-botones.p-3(x="28%" y="40%" numero="1")
        span.text-white(style="background-color:#294DDC;font-weight:bold;padding:.1rem;")  Indicador 01
        h5 Organización de la seguridad de la información
        p.mt-4 Determina y hace seguimiento al compromiso de la dirección, en cuanto a seguridad de la información, en lo relacionado con la asignación de personas y responsabilidades relacionadas a la seguridad de la información al interior de la entidad.
      .tarjeta.color-acento-botones.p-3(x="28%" y="58%" numero="2")
        span(style="background-color:#B9FFE2;font-weight:bold;padding:.1rem;")  Indicador 02
        h5 Cubrimiento del SGSI en activos de información
        p.mt-4 Determina y #[em hace seguimiento] al cubrimiento que se realiza a nivel de activos críticos de información de una #[em entidad] y los #[em controles] aplicados.
      .tarjeta.color-acento-botones.p-3(x="41%" y="70%" numero="3")
        span(style="background-color:#6ACEAE;font-weight:bold;padding:.1rem;")  Indicador 03
        h5 Tratamientos de eventos relacionados en marco de seguridad y privacidad de la información
        p.mt-4 Determina la eficiencia en el tratamiento de eventos relacionados con la seguridad de la información; los eventos serán reportados por los usuarios o determinadas en las auditorías planeadas para el sistema.
      .tarjeta.color-acento-botones.p-3(x="57%" y="71%" numero="4")
        span(style="background-color:#6ACEAE;font-weight:bold;padding:.1rem;")  Indicador 04
        h5 Implementación de los procesos de registro y auditoría
        p.mt-4 Grado de existencia de lineamientos, normas o estándares en cuanto registro y auditoría para la seguridad de la información.
      .tarjeta.color-acento-botones.p-3(x="71%" y="59%" numero="5")
        span(style="background-color:#F3C035;font-weight:bold;padding:.1rem;") Indicador 05
        h5 Prevención de código malicioso
        p.mt-4 Mide el nivel de efectividad del proceso de prevención de código malicioso.




</template>

<script>
export default {
  name: 'Tema4',
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
.cont_tema4_1:before
  content: ''
  position: absolute
  width: 115%
  left: -7%
  height: 100%
  top: 0
  background-color: #E5FDF3
.tarjeta.color-acento-botones
  background-color: #F6F6F6
  border-radius: 0px
</style>
