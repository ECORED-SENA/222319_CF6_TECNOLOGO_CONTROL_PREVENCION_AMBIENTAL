<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Materiales de laboratorio

    figure.mb-4
      img(src='@/assets/curso/tema5/1.jpg', alt='Texto que describa la imagen')
    p.mb-4 Los materiales de laboratorio se convierten en las principales herramientas de trabajo en el laboratorio. En esta sección, se identifican los conceptos asociados y principales directrices a emplear en este campo. Es necesario que antes de comenzar cualquier trabajo experimental, el aprendiz conozca el material que se utiliza. Cada uno de los materiales tiene una función y su uso debe ser acorde con la tarea por realizar. La utilización inadecuada de este material da lugar a errores en las experiencias realizadas y aumenta el riesgo en el laboratorio.

    .tarjeta.tarjeta-ama4.p-4.mb-5
      SlyderA(tipo="b")
        .row.align-items-center
          .col-md-4.mb-4.mb-md-0
            h4 Volumétrico: 
            p dentro de este grupo se encuentran los materiales de vidrio calibrados a una temperatura dada. Permite medir volúmenes exactos de sustancias (matraces, pipetas, buretas, probetas graduadas). 
        
          .col-md-8
            figure
              img(src='@/assets/curso/tema5/slyder1.png', alt='Texto que describa la imagen')
    
        .row.align-items-center
          .col-md-4.mb-4.mb-md-0
            h4 Calentamiento o sostén
            p son aquellos que sirven para realizar mezclas o reacciones y que además pueden ser sometidos a calentamiento (vaso de precipitado, erlenmeyer, cristalizador, vidrio de reloj, balón, tubo de ensayo).

          .col-md-8
            figure
              img(src='@/assets/curso/tema5/slyder2.png', alt='Texto que describa la imagen')

        .row.align-items-center
          .col-md-4.mb-4.mb-md-0
            h4 Equipos de medición
            p es un instrumento que se usa para comparar magnitudes físicas mediante un proceso de medición. Como unidades de medida se utilizan objetos y sucesos previamente establecidos como estándares o patrones, y de la medición resulta un número que es la relación entre el objeto de estudio y la unidad de referencia. Los instrumentos de medición son el medio por el que se hace esta conversión. Ejemplo: balanza, pHmetro, termómetro.
        
          .col-md-8
            figure
              img(src='@/assets/curso/tema5/slyder3.png', alt='Texto que describa la imagen')
    
        .row.align-items-center
          .col-md-4.mb-4.mb-md-0
            h4 Equipos especiales
            p equipos auxiliares para el trabajo de laboratorio. Ejemplo: centrífuga, estufa, baño termostático, etc.

          .col-md-8
            figure
              img(src='@/assets/curso/tema5/slyder4.png', alt='Texto que describa la imagen')

        .row.align-items-center
          .col-md-4.mb-4.mb-md-0
            h4 Diversos equipos
            p Es importante tener presente que todo análisis químico, físico o microbiológico de una muestra requiere la manipulación de diversos equipos o instrumentos de laboratorio.

          .col-md-8
            figure
              img(src='@/assets/curso/tema5/slyder5.png', alt='Texto que describa la imagen')


</template>

<script>
export default {
  name: 'Tema5',
  data: () => ({
    // variables de vue
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
