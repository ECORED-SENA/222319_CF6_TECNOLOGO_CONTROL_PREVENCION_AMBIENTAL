<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 11
      h1 Medios de cultivo

    .row.align-items-center.mb-4
      .col-lg-6
        figure
          img(src='@/assets/curso/tema11/1.png', alt='Texto que describa la imagen') 
      .col-lg-6
        .tarjeta.colorama.p-5
          p.mb-0 El medio de cultivo constituye el aporte de nutrientes indispensables para el crecimiento de los microorganismos. La composición precisa dependerá de la especie que se quiera cultivar, porque las necesidades nutricionales varían considerablemente. Hay microorganismos muy poco exigentes, que crecen bien en medio de laboratorios normales, y microorganismos muy exigentes, que necesitan determinadas sustancias, como vitaminas, suero o sangre, para crecer.

    AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
      .row(titulo="Existen medios cuya composición permite el crecimiento de")
        .col-lg-2
          figure
            img(src='@/assets/curso/tema11/icon1.svg', alt='Texto que describa la imagen')
        .col-lg-10
          p.mb-4 Un gran número de especies (agar nutritivo, caldo ordinario, agar de Sabouraud).
          p.mb-4 Determinados microorganismos (impidiendo el desarrollo de otros), son los denominados medios selectivos.
          p.mb-0 Otros, en cambio, se desarrollan para el estudio de determinadas pruebas fisiológicas o test bioquímicos (utilización de citratos, acidificación a partir de azúcares, etc.).

      .row(titulo="Los medios de cultivo poseen una serie de componentes")
        .col-lg-2
          figure
            img(src='@/assets/curso/tema11/icon2.svg', alt='Texto que describa la imagen')
        .col-lg-10
          p.mb-4 Indispensables: se incluye el agua, nutrientes orgánicos (hidratos de carbono, aminoácidos, vitaminas, etc.) y nutrientes inorgánicos (P, Fe, N, Mg, S, etc.).
          p.mb-0 Alternativos: sustancias isosmotizantes (NaCl), agente solidificante (agar-agar), tampones, indicador de pH, etc.
      
      .row(titulo="Durante las prácticas se van a manejar medios de cultivo de composición muy variada y de tres tipos diferentes en cuanto a consistencia: medios sólidos, semisólidos y líquidos")
        .col-lg-2
          figure
            img(src='@/assets/curso/tema11/icon3.svg', alt='Texto que describa la imagen')
        .col-lg-10
          p.mb-0 Este último aspecto es importante a la hora de la preparación de estos. Aunque los medios artificiales o sintéticos se pueden preparar a partir de sus componentes individuales, se pueden adquirir comercialmente como medios deshidratados a los que solamente hay que añadir la cantidad de agua necesaria. 

      .row(titulo="El fabricante indica la composición, la caducidad y la cantidad que debe pesarse por cada litro a preparar, e incluso cómo debe esterilizarse")
        .col-lg-2
          figure
            img(src='@/assets/curso/tema11/icon4.svg', alt='Texto que describa la imagen')
        .col-lg-10
          p.mb-4 Objetivos concretos de la práctica.
          p.mb-4 Preparar medios de cultivo como soporte y fuente de nutrientes para el desarrollo de los microorganismos in vitro.
          p.mb-4 Manejar los instrumentos de uso rutinario, a la vez que imprescindibles, en el laboratorio de microbiología.
          p.mb-0 Hacer un primer acercamiento a la manipulación de microorganismos. Adquirir la idea de la importancia del trabajo en condiciones de esterilidad y las técnicas más comunes para realizarlo.



</template>

<script>
export default {
  name: 'Tema11',
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
