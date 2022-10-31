<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 7
      h1 Recepción de muestras 

    #t_7_1.titulo-segundo.color-acento-contenido
      .h2 7.1 Recepción de la muestra al laboratorio (agua)

    #t_7_2.titulo-segundo.color-acento-contenido
      .h2 7.2 Recepción de la muestra al laboratorio (suelo)

    #t_7_3.titulo-segundo.color-acento-contenido
      .h2 7.3 Recepción de la muestra al laboratorio (olores)

    #t_7_4.titulo-segundo.color-acento-contenido
      .h2 7.4 La entrega al laboratorio

</template>

<script>
export default {
  name: 'Tema7',
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
