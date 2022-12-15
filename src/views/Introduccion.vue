<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-12(data-aos="fade-right")
        p.mb-0 Los profesionales de acompañamiento y de los equipos técnicos que sustentan el acompañamiento psicosocial son la principal herramienta – instrumento de trabajo con las familias y sus integrantes. En el siguiente video se destaca la importancia de su rol y la postura que se espera en estos procesos, información que luego será desarrollada a lo largo del componente.

    figure(data-aos="zoom-in").mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/P-8rwdXAK_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    .bg1
      .row.align-items-center.p-3
        .col-lg-auto
          figure
            img(src='@/assets/curso/temas/img01.svg', style="width: 80px").m-auto
        .col-lg.mb-4.mb-lg-0
          p.mb-0 <b>Objetivo:</b> reconocer los procesos de cambio en las familias y aplicar las herramientas que permiten estructurar, planear y proyectar el acompañamiento psicosocial con las familias beneficiarias del programa Mi familia .
      
          
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
