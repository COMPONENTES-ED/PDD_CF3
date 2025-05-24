<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .row.justify-content-center.mb-4
      .col-lg-8.my-3.order-1
        .brad.p-3.mb-4
          p.mb-0
            | En el ámbito de la estadística aplicada, la comprensión y el uso de medidas estadísticas permiten describir, analizar y entender patrones dentro de los datos. Las medidas de tendencia central, dispersión y posición, junto con el cálculo de probabilidades, son fundamentales para interpretar correctamente la información y realizar inferencias válidas sobre poblaciones a partir de muestras.
        .row.justify-content-center.align-items-center.bg8.mb-4
          .col-lg-4.h-100
            img.img-fluid(src='@/assets/curso/temas/2.png' alt='')
          .col-lg-8.bgi
            .p-4
              p.mb-0
                | &iquest;Cómo se aplican estas herramientas para obtener resultados precisos y representativos en el análisis estadístico? Este componente formativo explora los principios y metodologías de las medidas estadísticas clave, abarcando desde los conceptos de media y varianza hasta las distribuciones de probabilidad y su interpretación en gráficos estadísticos. Además, se proporcionarán enfoques prácticos para seleccionar y presentar datos de manera clara y efectiva en informes estadísticos.
        p
          | A lo largo de este componente, el aprendiz desarrollará habilidades para calcular y aplicar medidas estadísticas, interpretar distribuciones y utilizar gráficos para comunicar hallazgos. Asimismo, se destacarán las mejores prácticas para estructurar datos y elegir el tipo de gráfico adecuado, optimizando la precisión y la claridad en la presentación de resultados.
      .col-lg-4.my-3.order-lg-2
        img.img-a.img-t(src='@/assets/curso/temas/1.png' alt='')
    .row.justify-content-center
      .col-lg-10.my-3
        .row.justify-content-center.align-items-center.bg7.p-4.brad.text-white.mb-5
          .col-lg-auto
            img.img-a.img-t(src='@/assets/curso/temas/3.svg' alt='')
          .col.pt-lg-0.pt-md-4
            p.mb-0
              | Las medidas estadísticas y su interpretación son pilares para cualquier análisis riguroso, ya que &ldquo;la precisión de las conclusiones depende de la correcta aplicación de los principios estadísticos&rdquo;.
    h4.mb-4
      | &iexcl;Bienvenido a este recorrido por el mundo de la estadística y la visualización efectiva de datos para el análisis!
    .row.justify-content-center.align-items-center        
      .col-lg-12
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/qe9HXvi56T0?si=poW0teGuK5v6U3vw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
          figcaption Video. Análisis estadístico de datos y generación de gráficos

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
