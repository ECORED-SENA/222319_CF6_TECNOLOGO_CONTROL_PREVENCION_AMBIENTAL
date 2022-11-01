<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 8
      h1 Sistema internacional de medidas y notación científica 

    p.mb-4 Cuando se cuenta al medir, lo que estamos haciendo es comparar dos cantidades.  Por ejemplo, cuando se necesita saber cuál es la longitud de una ventana, lo que se hace es comparar la longitud de una regla o metro.

    .row.align-items-center.mb-4 
      .col-lg-6
        SlyderF(columnas="col-12")
          .tarjeta.color-avatar.py-5.px-5
            p.text-center Medir es seccionar determinada cantidad en partes iguales usando otra cantidad que sirva de referencia para compararla y contarla.  Por ejemplo, en caso de querer saber la cantidad de agua con la que se llena una piscina. Para ello se tiene un balde, o cubeta, y una fuente de agua. Lo que se hace es empezar a llenar cubetas de agua y vaciar su cantidad dentro de la piscina varias veces.

          .tarjeta.color-avatar.py-5.px-5
            p.text-center Al contar el número de veces que se llena y vacía la cubeta dentro de la piscina, también se habrá hecho una medición de cuánta agua necesita la piscina para quedar llena.
      .col-lg-6
        figure
          img(src='@/assets/curso/tema8/1.jpg' alt='AvatarTop')
    separador 

    #t_8_1.titulo-segundo.color-acento-contenido
      .h2 8.1 Unidades de medición

    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema8/2.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p Sería muy complejo que se mida las cantidades, las longitudes, los pesos, entre otros, con lo que nos pareciera, ya que cada uno tendría un parámetro distinto y no habría un acuerdo universal para establecer cálculos precisos sobre algo.
        br
        br
        p Es por ello por lo que se crearon las unidades de medida, con el fin de tener un parámetro de referencia sobre las cantidades, magnitudes y demás en todo el mundo. 
    separador 

    #t_8_2.titulo-segundo.color-acento-contenido
      .h2 8.2 El sistema internacional de unidades y notación científica

    p.mb-4 El Sistema Internacional de Unidades se basa en dos tipos de magnitudes físicas. Las siete que toma como fundamentales son:
    
    .row.justify-content-center.mb-4 
      .col-lg-10
        .tarjeta.color1.p-4
          .row.align-items-center
            .col-lg-8
              .row.justify-content-center
                .col-lg-4
                  figure
                    img(src='@/assets/curso/tema8/icon1.svg' alt='AvatarTop')
                .col-lg-6
                  ul.lista-ul--color.mb-0
                    li 
                      i.fas.fa-check
                      p.mb-0 Longitud
                    li 
                      i.fas.fa-check
                      p.mb-0 Tiempo
                    li 
                      i.fas.fa-check
                      p.mb-0 Masa
                    li 
                      i.fas.fa-check
                      p.mb-0 Intensidad de corriente eléctrica
                    li 
                      i.fas.fa-check
                      p.mb-0 Temperatura
                    li 
                      i.fas.fa-check
                      p.mb-0 Cantidad de sustancia
                    li 
                      i.fas.fa-check
                      p.mb-0 Intensidad luminosa
            .col-lg-4
              figure
                img(src='@/assets/curso/tema8/icon2.svg' alt='AvatarTop')
    p.mb-4 Y por otro lado existen las derivadas, que son las restantes y que pueden ser expresadas con una combinación matemática de las anteriores. Las más frecuentes son: superficie, volumen, velocidad, aceleración, densidad, frecuencia, periodo, fuerza, presión, trabajo, calor, energía, potencia, carga eléctrica, diferencia de potencial, potencial eléctrico, resistencia eléctrica, etcétera. 
    separador

    #t_8_3.titulo-segundo.color-acento-contenido
      .h2 8.3 Sistema de unidades: CGS, MKS, SI, inglés

    p.mb-4 Un sistema de unidades es un conjunto consistente de unidades de medida. Definen un conjunto básico de unidades de medida a partir del cual se derivan el resto. Existen varios sistemas de unidades:

    .row.mb-4
      .col-lg-12
        SlyderF.mb-5(columnas="col-lg-6 col-xl-4")
          .tarjeta-avatar
            img(src='@/assets/curso/tema8/avatar1.svg' alt='AvatarTop')
            .tarjeta.color-avatar2
              .p-4
                h4.text-center Sistema Internacional de Unidades o SI
                p.text-center es el sistema más usado. Sus unidades básicas son: el metro, el kilogramo, el segundo, el ampere, el kelvin, la candela y el mol.

          .tarjeta-avatar
            img(src='@/assets/curso/tema8/avatar1.svg' alt='AvatarTop')
            .tarjeta.color-avatar2
              .p-4
                h4.text-center Sistema Métrico Decimal
                p.text-center primer sistema unificado de medidas.

          .tarjeta-avatar
            img(src='@/assets/curso/tema8/avatar1.svg' alt='AvatarTop')
            .tarjeta.color-avatar2
              .p-4
                h4.text-center Sistema Cegesimal o CGS
                p.text-center denominado así porque sus unidades básicas son el centímetro, el gramo y el segundo.

          .tarjeta-avatar
            img(src='@/assets/curso/tema8/avatar1.svg' alt='AvatarTop')
            .tarjeta.color-avatar2
              .p-4
                h4.text-center Sistema Técnico de Unidades
                p.text-center derivado del sistema métrico con unidades del anterior, actualmente este sistema está en desuso.

          .tarjeta-avatar
            img(src='@/assets/curso/tema8/avatar1.svg' alt='AvatarTop')
            .tarjeta.color-avatar2
              .p-4
                h4.text-center Sistema Inglés
                p.text-center aún utilizado en los países anglosajones, principalmente en Estados Unidos. Muchos de ellos lo están intentando reemplazar por el Sistema Internacional de Unidades.
    p.mb-4 Es así como en Colombia el Instituto Nacional de Metrología ha establecido que en el país se debe utilizar el Sistema Internacional de Unidades (abreviado SI del francés: Le Système International d’Unités), también denominado Sistema Internacional de Medidas; es el nombre que recibe el sistema de unidades que se usa en la mayoría de los países y es la forma actual del sistema métrico decimal.

    .row.justify-content-center.mb-4 
      .col-lg-10
        .tarjeta.color-bloque2.p-5
          ol.lista-ol--cuadro
            li 
              .lista-ol--cuadro__vineta
                span 1
              p <b>El SI también es conocido como sistema métrico,</b> especialmente en las naciones en las que aún no se ha implantado para su uso cotidiano. Fue creado en 1960 por la Conferencia General de Pesos y Medidas, que inicialmente definió seis unidades físicas básicas. En 1971, se añadió la séptima unidad básica, el mol. 
            li 
              .lista-ol--cuadro__vineta
                span 2
              p <b>Una de las principales características, y que constituye la gran ventaja del SI,</b> es que sus unidades están basadas en fenómenos físicos fundamentales. La única excepción es la unidad de la magnitud masa, el kilogramo, que está definida como la masa del prototipo internacional del kilogramo o aquel cilindro de platino e iridio almacenado en una caja fuerte de la Oficina Internacional de Pesos y Medidas.  
            li 
              .lista-ol--cuadro__vineta
                span 3
              p <b>Las unidades del SI son la referencia internacional de las indicaciones de los instrumentos de medida</b> y a las que están referidas a través de una cadena ininterrumpida de calibraciones o comparaciones. Esto permite alcanzar la equivalencia de las medidas realizadas por instrumentos similares, utilizados y calibrados en lugares apartados, y por ende asegurar, sin la necesidad de ensayos y mediciones duplicadas, el cumplimiento de las características de los objetos que circulan en el comercio internacional y su intercambiabilidad.
    separador 

    #t_8_4.titulo-segundo.color-acento-contenido
      .h2 8.4 Conversiones de unidades

    p.mb-4 La conversión de unidades es la transformación de una unidad en otra. Un método para realizar este proceso es el uso de los factores de conversión y las, muy útiles, tablas de conversión. Bastaría multiplicar por una fracción (factor de conversión) y el resultado es otra medida equivalente en la que han cambiado las unidades.
    p.mb-4 Cuando el cambio de unidades implica la transformación de varias unidades se pueden utilizar varios factores de conversión, uno tras otro, de forma que el resultado final será la medida equivalente en las unidades que se busca. Por ejemplo:
    
    .row.justify-content-center.mb-4  
      .col-lg-10
        .tarjeta.color-bloque3.p-3
          p.text-center.mb-0 Si queremos pasar 8 metros a yardas, lo único que tenemos que hacer es multiplicar 8(0.914 yd) = 7.312 yd. 

    .tarjeta.color-celeste.p-4.mb-5
      SlyderA(tipo="b")
        .row.align-items-center
          .col-md-4.mb-4.mb-md-0
            h4 Factor de conversión.
            p El factor de conversión es una fracción en la que el numerador y el denominador son medidas iguales expresadas en unidades distintas, de tal manera que esta fracción equivale a la unidad. Método efectivo para cambio de unidades y resolución de ejercicios sencillos, dejando de utilizar la regla de tres.
        
          .col-md-8
            figure
              img(src='@/assets/curso/tema8/img1.png', alt='Texto que describa la imagen')
    
        .row.align-items-center
          .col-md-4.mb-4.mb-md-0
            h4 Precisión
            p.mb-4 Se denomina precisión a la capacidad de un instrumento de dar el mismo resultado en mediciones diferentes realizadas en las mismas condiciones. Esta cualidad debe evaluarse a corto plazo. No debe confundirse con exactitud ni con reproducibilidad.
            p.mb-0 La precisión es un parámetro relevante, especialmente en la investigación de fenómenos físicos, ámbito en el cual los resultados se expresan como un número más una indicación del error máximo estimado para la magnitud. Es decir, se indica una zona dentro de la cual está comprendido el verdadero valor de la magnitud.

          .col-md-8
            figure
              img(src='@/assets/curso/tema8/img2.png', alt='Texto que describa la imagen')

        .row.align-items-center
          .col-md-12.mb-4.mb-md-0
            h4.mb-5 Cifras significativas
            p.mb-4 Son aquellas que tienen significado real o aportan alguna información. Las cifras no significativas aparecen como resultado de los cálculos y no tienen significado alguno. Las cifras significativas de un número vienen determinadas por su error. Son cifras significativas aquellas que ocupan una posición igual o superior al orden o posición del error.
            p.mb-4 (Facultad de Ingeniería de LUZ, 2018)
            p.mb-4 Por ejemplo, se considera una medida de longitud que arroja un valor de 5432.4764 m con un error de 0.8 m. El error es por tanto del orden de décimas de metro. Es evidente que todas las cifras del número que ocupan una posición menor que las décimas no aportan ninguna información. En efecto, ¿qué sentido tiene dar el número con precisión de diez milésimas si se afirma que el error es de casi 1 metro? Las cifras significativas en el número serán, por tanto, las que ocupan la posición de las décimas, unidades, decenas, etc, pero no las centésimas, milésimas ni diezmilésimas.
            p.mb-0 Cuando se expresa un número debe evitarse siempre la utilización de cifras no significativas, puesto que puede suponer una fuente de confusión. Los números deben redondearse de forma que contengan sólo cifras significativas. Se llama redondeo al proceso de eliminación de cifras no significativas de un número.
    
        .row.align-items-center
          .col-md-12.mb-4.mb-md-0
            h4 Notación científica
            p.mb-0 La notación científica (o notación índice estándar) es un modo conciso de representar un número utilizando potencias de base diez. Los números se escriben como un producto: a × 10k, (siendo a un número mayor o igual que 1 y menor que 10, y k un número entero). Esta notación se utiliza para poder expresar más fácilmente números muy grandes o demasiado pequeños.
            p.mb-4 La notación científica utiliza un sistema llamado coma flotante, o de punto flotante, en países de habla inglesa y en algunos hispanohablantes.
            p.mb-0 100 = 1
            p.mb-0 101 = 10
            p.mb-0 102 = 100
            p.mb-0 103 = 1000
            p.mb-0 104 = 10000
            p.mb-0 105 = 100000
            p.mb-0 106 = 1000000
            p.mb-0 109 = 1000000000
            p.mb-0 1010 = 10000000000
            p.mb-0 1020 = 100000000000000000000
            p.mb-0 1030 = 1000000000000000000000000000000

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
