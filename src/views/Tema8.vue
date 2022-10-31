<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 8
      h1 Sistema internacional de medidas y notación científica 

    #t_8_1.titulo-segundo.color-acento-contenido
      .h2 8.1 Unidades de medición

    #t_8_2.titulo-segundo.color-acento-contenido
      .h2 8.2 El sistema internacional de unidades y notación científica

    #t_8_3.titulo-segundo.color-acento-contenido
      .h2 8.3 Sistema de unidades: CGS, MKS, SI, inglés

    #t_8_4.titulo-segundo.color-acento-contenido
      .h2 8.4 Conversiones de unidades

</template>

<script>
export default {
  name: 'Tema8',
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
