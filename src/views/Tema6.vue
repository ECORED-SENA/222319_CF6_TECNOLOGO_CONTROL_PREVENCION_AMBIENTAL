<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 6
      h1 Reactivos y soluciones

    #t_6_1.titulo-segundo.color-acento-contenido
      .h2 6.1 Componentes de una disolución

    #t_6_2.titulo-segundo.color-acento-contenido
      .h2 6.2 Importancia de las disoluciones

    #t_6_3.titulo-segundo.color-acento-contenido
      .h2 6.3 Clases de disoluciones

    #t_6_4.titulo-segundo.color-acento-contenido
      .h2 6.4 Solubilidad

    #t_6_5.titulo-segundo.color-acento-contenido
      .h2 6.5 Factores que afectan la solubilidad

    #t_6_6.titulo-segundo.color-acento-contenido
      .h2 6.6 Unidades de la concentración de las disoluciones

</template>

<script>
export default {
  name: 'Tema6',
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
