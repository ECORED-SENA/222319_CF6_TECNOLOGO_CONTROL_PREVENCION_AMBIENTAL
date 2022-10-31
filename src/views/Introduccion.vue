<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .row.align-items-center.mb-4
      .col-lg-7
        p.mb-4 Cuando en los muestreos que se desarrollan de un trabajo de campo, se captan las muestras según el parámetro a medir, ya sea de agua, lodos, olores, entre otros, es importante conocer cuáles son los análisis y el alistamiento que se va a llevar a cabo en el laboratorio para poder establecer los pertinentes resultados del estudio.
        .cajon.color-acento-contenido(style='background-color: #DFF2ED').p-4.mb-0
          p.mb-0 La importancia del análisis de las muestras que se llevan al laboratorio radica particularmente en el tratamiento que se le dé a las mismas, desde la toma, el embalaje, el transporte y su respectiva identificación; puesto que, si la muestra laboratorio es alterada en alguno de los procesos, su posterior análisis entra en un margen de baja confiabilidad que se traduce en un resultado de poca fiabilidad.
      .col-lg-5
        figure
          img(src='@/assets/curso/introduccion/1.jpg')
    p.mb-3 Por esta razón, en esta unidad temática, se profundizará en el proceso de valoración de muestras, desde el alistamiento hasta el análisis que se lleva a cabo en un laboratorio.
    p.mb-0 Para la elaboración de este componente, se abordaron varios autores conocidos en alistamiento para el análisis químico de muestras, de quienes se han citado y referenciado conceptos y ejemplos para los fines educativos de esta materia, en el entendido que el conocimiento es social y, por lo tanto, es para usarlo por quienes necesitan adquirirlo. Se espera que este documento sea útil para todos, aprendices y lectores en general, que estén interesados en acercarse a asuntos básicos de prevención y control ambiental.

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
