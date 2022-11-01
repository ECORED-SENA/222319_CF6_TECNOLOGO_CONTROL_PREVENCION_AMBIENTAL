<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 6
      h1 Reactivos y soluciones

    figure.mb-4
      img(src='@/assets/curso/tema6/img1.jpg', alt='Texto que describa la imagen')
    p.mb-4 Las disoluciones, también llamadas soluciones, se definen como la mezcla de dos sustancias o más y que forman una sola fase, es decir, que son mezclas homogéneas de sus componentes.
    separador

    #t_6_1.titulo-segundo.color-acento-contenido
      .h2 6.1 Componentes de una disolución

    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema6/1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Los componentes que forman las disoluciones son nombrados dependiendo de la cantidad en que se encuentren en la mezcla. El componente que se encuentre en mayor cantidad es conocido como solvente, mientras que aquel componente que se encuentre en menor cantidad será el soluto. En las soluciones acuosas o aquellas soluciones donde se encuentra agua como uno de los componentes, el agua será el solvente, aunque se encuentre en menor cantidad que el soluto.
    separador

    #t_6_2.titulo-segundo.color-acento-contenido
      .h2 6.2 Importancia de las disoluciones

    p.mb-4 Se encuentran disoluciones en nuestra vida cotidiana muy comúnmente, es muy difícil encontrar sustancias puras en nuestro ambiente, ya que en la gran mayoría de casos se encuentran como mezclas, y en muchos de ellos, como mezclas homogéneas. A continuación, se dan algunos ejemplos de disoluciones y su importancia.

    .row.mb-4
      .col-lg-12
        TabsA.color-acento-contenido
          .tarjeta.colortabs1.p-4(titulo="En la industria")
            .row.align-items-center
              .col-lg-8
                h4 En la industria
                p para estudiar el petróleo es indispensable disolverlo, es decir, hacer soluciones de petróleo. Este se disuelve en compuestos orgánicos como el hexano. Para hacer cremas, dentífricos, cosméticos, entre otros, es necesario hacer soluciones. Para extraer colorantes o aceites esenciales, es necesario disolver las plantas en diversos compuestos orgánicos. Las cerámicas se hacen a base de soluciones sólidas. Las pinturas son soluciones.
              .col-lg-4
                figure
                  img(src='@/assets/curso/tema6/tab1.jpg', alt='Texto que describa la imagen')

          .tarjeta.colortabs1.p-4(titulo="En la vida diaria")
            .row.align-items-center
              .col-lg-8
                h4 En la vida diaria
                p los refrescos son soluciones, varios compuestos están disueltos, como ácido carbónico y azúcar. Las frutas y verduras contienen agua, la cual disuelve algunos componentes. Como la mandarina o la naranja, que son muy jugosas y su jugo es rico en vitamina C (soluciones de vitamina C). La limonada es ácido cítrico y azúcar disueltos en agua, una solución.
              .col-lg-4
                figure
                  img(src='@/assets/curso/tema6/tab2.jpg', alt='Texto que describa la imagen')

          .tarjeta.colortabs1.p-4(titulo="En el ambiente")
            .row.align-items-center
              .col-lg-8
                h4 En el ambiente
                p existen soluciones que son capaces de atrapar partículas contaminantes, aunque en la actualidad todavía está en desarrollo la investigación de este tipo de soluciones. La lluvia ácida es un tipo de solución con efectos negativos, pues el agua disuelve los óxidos de nitrógeno y de azufre que salen de las chimeneas o escapes. En el área de la química, las soluciones son muy importantes, pues para hacer análisis químico es indispensable el empleo de las soluciones. En el área de síntesis química, la mayoría de las reacciones se llevan a cabo en soluciones. Para sintetizar un nuevo medicamento, se emplean varias soluciones. (Luquez, 2016)
              .col-lg-4
                figure
                  img(src='@/assets/curso/tema6/tab2.jpg', alt='Texto que describa la imagen')
    separador 

    #t_6_3.titulo-segundo.color-acento-contenido
      .h2 6.3 Clases de disoluciones

    p.mb-4 Según la cantidad de soluto disuelto en una cantidad dada de solvente, las disoluciones pueden ser:

    .row.mb-5
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema6/avatar1.svg' alt='AvatarTop')
          .tarjeta.color-avatar2
            .p-4
              h4.text-center Diluida
              p.text-center en estas disoluciones la cantidad de soluto disuelto es muy pequeño en comparación con la cantidad de solvente. Por ejemplo, si se agrega una cucharadita de sal en un litro de agua.

      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema6/avatar2.svg' alt='AvatarTop')
          .tarjeta.color-avatar2
            .p-4
              h4.text-center Concentrada
              p.text-center a pesar de que en estas soluciones hay una cantidad grande de soluto en un solvente determinado, esta no alcanza a ser la máxima cantidad de soluto que puede ser disuelto por el solvente.

      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema6/avatar3.svg' alt='AvatarTop')
          .tarjeta.color-avatar2
            .p-4
              h4.text-center Saturada
              p.mb-0 estas disoluciones contienen disuelta la máxima cantidad de soluto que se puede; si se agrega un poco más de soluto, este ya no podrá disolverse.

      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema6/avatar4.svg' alt='AvatarTop')
          .tarjeta.color-avatar2
            .p-4
              h4.text-center Sobresaturada
              p.mb-0 contiene una cantidad de soluto que no alcanza a ser disuelto por el solvente debido a que este ya alcanzó el punto máximo de soluto disuelto en él.
    separador

    #t_6_4.titulo-segundo.color-acento-contenido
      .h2 6.4 Solubilidad

    .row.align-items-center.mb-4
      .col-lg-6
        figure
          img(src='@/assets/curso/tema6/2.png', alt='Texto que describa la imagen')
      .col-lg-6
        .tarjeta.colorama.p-5
          p.mb-0 La solubilidad se define como la capacidad de un soluto para disolverse en un solvente. Además, es la máxima cantidad de soluto que se puede disolver en una cantidad determinada de un solvente. Esta solubilidad normalmente es expresada en gramos de soluto por cada 100 ml de solvente.
    separador 

    #t_6_5.titulo-segundo.color-acento-contenido
      .h2 6.5 Factores que afectan la solubilidad

    p.mb-4 La solubilidad de un soluto en un solvente se puede ver afectada por diferentes condiciones a las que se someta la disolución. Estas condiciones pueden ser: la temperatura, la agitación, la naturaleza de los componentes de la disolución, la presión y la superficie de contacto del soluto con el solvente.

    .row.align-items-center.mb-4
      .col-lg-6
        .row.mb-4
          .col-lg-6
            .sub.p-2
              h4.mb-0.text-center.text-white Temperatura y agitación
        p.mb-4 al aumentar la temperatura y el grado de agitación en una disolución, aumenta la energía cinética de sus partículas, por lo que se favorece el movimiento de estas y se permite que se difuminen más rápido por todo el solvente.
        p.mb-4 <b>Presión:</b> esta afecta en gran medida la solubilidad de los gases, ya que al aumentar la presión que se ejerce sobre un gas en una disolución, este se solubiliza más en un solvente.
        p.mb-0 <b>Superficie de contacto:</b> mientras más superficie de contacto tenga un soluto, es más soluble. Si se da la trituración, pulverización o fragmentación de un soluto sólido, la superficie de contacto de este será mayor, lo que favorecería la interacción y su disolución en un solvente.
      .col-lg-6
        figure
          img(src='@/assets/curso/tema6/3.png', alt='Texto que describa la imagen')
    separador 

    #t_6_6.titulo-segundo.color-acento-contenido
      .h2 6.6 Unidades de la concentración de las disoluciones

    p.mb-4 La concentración de una disolución es la cantidad de soluto que hay en una determinada cantidad de solvente. Cuando se habla  de concentrado, diluido o saturado, no se alcanza a dimensionar cantidades. Para que este valor sea más exacto, se puede expresar mediante unidades que indiquen las cantidades de soluto y solvente que se puede encontrar en una disolución.

    .row.mb-4
      .col-lg-3
        .sub.p-2
          h4.mb-0.text-center.text-white Unidades físicas y químicas

    p.mb-4 Existen distintas expresiones para referirse a la concentración de una disolución, distintas relaciones cuantitativas entre cantidad de soluto, disolvente y disolución; relaciones de masas, masas y volúmenes, moles y volúmenes, etc.  
    p.mb-4 En el siguiente esquema, se pueden apreciar las unidades de concentración más utilizadas:  

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
