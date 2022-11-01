<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Equipos de laboratorio

    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema4/1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p Todo análisis químico, físico o microbiológico de una muestra requiere la manipulación de diversos equipos o instrumentos de laboratorio. La química analítica es la rama de la química que estudia, desarrolla y mejora los métodos e instrumentos, con el fin de estudiar la composición química de la materia.
        br
        br
        p.mb-0 Se divide en química analítica cuantitativa, que se centra en desarrollar métodos para determinar la concentración de cada una de las sustancias que están presentes en una muestra, y la química analítica cualitativa, que se encarga de identificar cada una de las sustancias que forman una muestra.

    .row.mb-5
      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema4/avatar1.svg' alt='AvatarTop')
          .tarjeta.color-avatar
            .p-4
              h4.text-center Instrumento
              p.text-center Cuando se realiza un muestreo, este debe ser llevado a un instrumento para su análisis. No es un paso directo, al contrario, requiere una serie de pasos de alistamiento de la muestra para su posterior valoración instrumental.

      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema4/avatar2.svg' alt='AvatarTop')
          .tarjeta.color-avatar
            .p-4
              h4.text-center Análisis químico
              p.text-center Dentro de la química analítica, se incluye el análisis químico, que es la parte práctica que utiliza los métodos de análisis para solucionar los problemas relacionados con la composición química de la materia. Esta parte práctica se emplea en muchos ámbitos, pudiendo destacarse el papel que juega en la industria, donde se emplea en los controles de calidad, ya sea de materias primas o de productos.

      .col-md-6.col-lg.mb-5.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/tema4/avatar3.svg' alt='AvatarTop')
          .tarjeta.color-avatar
            .p-4
              h4.text-center Términos utilizados en la química analítica
              p.mb-0 Muestra: es la parte de la materia que nos interesa analizar.
              p.mb-0 Analito: sustancia química que se analiza.
              p.mb-0 Técnica: forma de obtener información sobre el analito.
              p.mb-0 Método: grupo de técnicas aplicadas al análisis de una muestra.

    .row.justify-content-center.mb-5
      .col-lg-12
        h5 Figura 3
        span Tipos de herramientas para la comunicación interpretativa

    .row.justify-content-center.mb-4
      .col-lg-10
        figure.mb-2
          img(src='@/assets/curso/tema4/fig1.svg', alt='Texto que describa la imagen')
        figcaption Nota. Tomada de https://es.calameo.com/read/002446339add36a3f7d24  
    separador 

    #t_4_1.titulo-segundo.color-acento-contenido
      .h2 4.1	Métodos clásicos

    p.mb-4 Los métodos clásicos se basan en las propiedades químicas de la sustancia que se analiza, es decir, del analito. Algunos de estos métodos son:

    .row.justify-content-center.mb-4
      .col-lg-10
        .tarjeta.colorama3
          .row.align-items-center.px-5.py-1
            .col-lg-6
              figure
                img(src='@/assets/curso/tema4/fig2.svg', alt='Texto que describa la imagen')
            .col-lg-1
              span
            .col-lg-5
              ul.lista-ul--color.mb-0
                li 
                  i.fas.fa-check
                  p.mb-0 Marchas analíticas
                li 
                  i.fas.fa-check
                  p.mb-0 Gravimetría
                li 
                  i.fas.fa-check
                  p.mb-0 Volumetría
    separador 

    #t_4_2.titulo-segundo.color-acento-contenido
      .h2 4.2	Métodos instrumentales

    p.mb-4 También llamados métodos químicos, se basan en las propiedades químico-físicas de la materia y son:

    .row.justify-content-center.mb-4
      .col-lg-10
        .tarjeta.colorcian.py-2.px-4
          .row.align-items-center
            .col-lg-1
              span
            .col-lg-4
              ul.lista-ul--color.mb-0
                li 
                  i.fas.fa-check
                  p.mb-0 Ópticos – espectroscópicos
                li 
                  i.fas.fa-check
                  p.mb-0 Separación 
                li 
                  i.fas.fa-check
                  p.mb-0 Electroquímicos
                li 
                  i.fas.fa-check
                  p.mb-0 Radioquímicos
                li 
                  i.fas.fa-check
                  p.mb-0 Térmicos
            .col-lg-1
              span
            .col-lg-4
              figure.top1
                img(src='@/assets/curso/tema4/vec1.svg', alt='Texto que describa la imagen')
    
    p.mb-4 A continuación, se pueden encontrar gráficas e imágenes que ilustran más y mejor sobre las técnicas espectroscópicas y no espectroscópicas, nuevos conceptos y nuevos elementos técnicos, referentes a los métodos instrumentales y clásicos en el análisis químico.
    h5.text-center.mb-4 Sobre los métodos de análisis químicos clásicos e instrumentales
    p.mb-4 Observe y analice, atentamente, cada una de las gráficas que le serán mostradas. Intente asimilar la información que en ellas se le presenta. Recuerde tomar nota de todo ello. 

    TabsB.color-acento-contenido.mb-5
      .py-4.py-md-5(titulo="Técnicas espectroscópicas")
        .row 
          .col-lg-8
            h5.mb-5 Técnicas espectroscópicas
            .row 
              .col-lg-6
                h5.mb-4 Moleculares:
                b.mb-0 Absorción   
                p.mb-0 Espectrofotometría ultravioleta visible
                p.mb-0 Espectrofotometría de infrarrojo
                p.mb-4 Espectrofotometría de microondas
                b.mb-0 Emisión
                p.mb-0 Espectrofotometría de fluorescencia
                p.mb-0 Espectrofotometría de fosforescencia
              .col-lg-6
                h5.mb-4 Atómicas:
                b.mb-0 Absorción   
                p.mb-0 Espectrofotometría de absorción atómica
                p.mb-4 Espestroscopía de absorción de rayos X.
                b.mb-1 Emisión
                p.mb-0 Espestroscopía de emisión atómica (llama, arco, chispa, plasma)
                p.mb-0 Espestroscopía de fluorescencia atómica
                p.mb-0 Espestroscopía de fluorescencia de rayos X
                p.mb-0 Espestroscopía de rayos gamma
          .col-lg-4 
            figure
              img(src='@/assets/curso/tema4/2.jpg', alt='Texto que describa la imagen')
      .py-4.py-md-5(titulo="Técnicas NO espectroscópicas")
        .row 
          .col-lg-8
            h5.mb-5 Técnicas espectroscópicas
            .row 
              .col-lg-6
                h5.mb-4 Basadas en la dispersión de la radiación: 
                p.mb-0 Turbidimetría
                p.mb-0 Nefelometría
                p.mb-0 Espectroscopía
                p.mb-4 Raman
                h5.mb-4 Basadas en la difracción:
                p.mb-0 Difracción de rayos X
                p.mb-0 Difracción de neutrones
                p.mb-0 Difracción de electrones
              .col-lg-6
                h5.mb-4 Basadas en la medida del índice de refracción: 
                p.mb-0 Refractometría 
                p.mb-5 Interferometría
                h5.mb-0 Basadas en la medida de la actividad óptica:
                p.mb-0 Polarimetría
                p.mb-0 Espectropolarimetría
                p.mb-0 Espectrometría de dicroísmo circular.
          .col-lg-4 
            figure
              img(src='@/assets/curso/tema4/3.jpg', alt='Texto que describa la imagen')
        
      .py-4.py-md-5(titulo="Técnicas electroanalíticas")
        .row 
          .col-lg-8
            h5.mb-5 Técnicas electroanalíticas
            .row 
              .col-lg-6
                p.mb-4 <b>a. Potenciometría</b> 
                p.mb-0 <b>b. Técnicas Voltamperométricas</b>
                p.mb-0 i. Voltamperometría de barrido lineal
                p.mb-0 ii. Voltamperometría de redisolución
                p.mb-4 iii. Voltamperometría ciclica
              .col-lg-6
                h5.mb-4 a. Culombiametría 
                p.mb-0 i. Culombimetria a potencial constante
                p.mb-0 ii. Culombimetria a intensidad constante
                p.mb-0 iii. Electrogravimetría
          .col-lg-4 
            figure
              img(src='@/assets/curso/tema4/4.jpg', alt='Texto que describa la imagen')
      .py-4.py-md-5(titulo="Algunos conceptos claros")  
        .row 
          .col-lg-8
            h5.mb-5 Algunos conceptos claros
            .row 
              .col-lg-6
                h5.mb-4 Sensibilidad:
                p.mb-0 Cantidad o concentración mínima que se puede determinar.
                h5.mb-4 Selectividad:
                p.mb-0 Interferencia de unas especies químicas en la determinación de otras.
              .col-lg-6
                h5.mb-4 Exactitud:
                p.mb-0 Proximidad de una medida a su valor real.
                h5.mb-4 Selectividad:
                p.mb-0 Concordancia entre dos o más valores numéricos de resultados obtenidos de forma idéntica.
          .col-lg-4 
            figure
              img(src='@/assets/curso/tema4/5.jpg', alt='Texto que describa la imagen')
      .py-4.py-md-5(titulo="Ejemplos de conceptos")
        .row 
          .col-lg-8
            h5.mb-5 Ejemplos de conceptos
            .row 
              .col-lg-6
                h5.mb-4 Errores Sistemáticos (Determinados)
                p.mb-0 Tienen calor definido
                p.mb-0 Tiene causa asignable
                p.mb-0 Tiene igual signo y magnitud
                p.mb-4 Afectan a la EXACTITUD 
                p.mb-0 Errores de instrumento
                p.mb-0 Errores del método
                p.mb-0 Errores personales
              .col-lg-6
                h5.mb-4 Errores Aleatorios (Indeterminados)
                p.mb-0 No tienen signo concreto  
                p.mb-0 No pueden corregirse
                p.mb-4 Afectan a la Precisión
                p.mb-0 Variables no controladas:
                p.mb-0 Parte inevitable de toda medición física o química.
          .col-lg-4 
            figure
              img(src='@/assets/curso/tema4/6.jpg', alt='Texto que describa la imagen')

</template>

<script>
export default {
  name: 'Tema4',
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
