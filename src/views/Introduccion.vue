<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    p(data-aos="fade-up") La seguridad web está relacionada directamente con la vigilancia en todos los aspectos del diseño y uso de un sitio web, es decir, #[strong es aquella actividad encargada de proteger sitios web del acceso, uso, modificación, destrucción o interrupción, no autorizados.]

    .row.cont_intro.mt-5.p-4(style="position:relative;")
      .col-md-1.mb-4.mb-md-0(style="place-self:center;position:relative")
        figure.text-center
          img(src="@/assets/curso/intro1.png" data-aos="fade-right" style="display:inline;max-width:200px;")
      .col-md-11(style="place-self:center;position:relative")
        p.mb-0(data-aos="fade-up") Es importante tener en cuenta existen muchos riesgos que se pueden presentar, por solo el hecho de que el sistema de información se encuentre desprotegido  y  se presenten situaciones como, robo de información, explotación de datos, redireccionamiento a páginas web maliciosas, mostrar anuncios no deseados, entre otros.
    
    p.mt-5(data-aos="fade-up") Teniendo en cuenta lo anterior, el aprendiz en el presente componente formativo, conocerá sobre las diferentes estrategias para monitorear la seguridad web, para lo cual se invita a observar el siguiente video:
    
    figure.mt-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    


</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>
<style lang="sass">
.cont_intro:before
  content: ''
  position: absolute
  width: 115%
  left: -7%
  height: 100%
  top: 0%
  background-color: #E5FDF3
</style>
