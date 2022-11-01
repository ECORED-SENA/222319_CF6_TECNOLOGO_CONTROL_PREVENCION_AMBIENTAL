<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Alistamiento general y bases conceptuales

    p.mb-4 Como se muestra en la figura 1, <b>el proceso de alistamiento de una muestra para su posterior análisis es un proceso muy importante en los análisis químicos en campo y laboratorio, puesto que influye en los resultados que se obtienen para, posteriormente, tomar decisiones de orden económico, ambiental, político y social.</b>

    .row.justify-content-center.mb-0
      .col-lg-10
        .titulo-sexto.color-acento-contenido
          h5 Figura 1
          span Tipos de herramientas para la comunicación interpretativa
    .row.justify-content-center.mb-4
      .col-lg-10
        figure.mb-2
          img(src='@/assets/curso/tema1/vec1.svg', alt='')
        figcaption Nota. Tomada de Pineda (2020). Proceso analítico de una muestra.

    p.mb-4 <b>Alistar la muestra es la etapa que más variabilidad introduce en el proceso analítico,</b> es la preparación de la muestra, que puede estar formada por un número variable de operaciones de muy diversa complejidad, por lo que incide en la calidad de los resultados obtenidos. 

    .row.justify-content-center.mb-4
      .col-lg-12
        .tarjeta.colordoble.px-4
          .row.align-items-center.mb-4.py-2
            .col-lg-2
              figure
                img(src='@/assets/curso/tema1/vec2.svg', alt='')
            .col-lg-10
              p.mb-4 Esta unidad temática se centra en la <b>etapa de preparación de la muestra, cuyo objetivo es hacer que el analito (muestra para analizar) sea óptimo para el análisis, a una concentración adecuada y eliminando las posibles interferencias. </b>
              p.mb-0 Por ende, se debe tener mucho cuidado en la preparación de la muestra dentro del proceso analítico general y revisar muy bien las operaciones que forman parte de ella.
    separador

    #t_1_1.titulo-segundo.color-acento-contenido
      .h2 1.1	Alistamiento

    p.mb-4 Alistar una muestra emplea, como lo menciona Palacios (2018), hasta un 60% del tiempo necesario para el proceso analítico, de aquí su gran importancia. <b>Dependiendo de si el analito a determinar es orgánico o inorgánico, se utilizan diferentes procesos.</b>

    .row.align-items-center.mb-4
      .col-lg-7
        p.mb-4 Debido al variable y amplio número de procedimientos existentes dentro de la etapa de preparación de la muestra, durante la formación de la presente competencia, se abordarán los procesos de extracción, envasado, rótula y transporte de la muestra. 
        .cajon.color-acento-contenido(style='background-color: #DFF2ED').p-4.mb-0
          p.mb-0 Frente a la toma de la muestra, existen diversos factores a tener en cuenta a la hora de seleccionar el proceso analítico más adecuado, para lo que habría que dar respuesta a varias preguntas que aparecen en la figura 2, tales como: <b>¿Qué se tiene que analizar y por qué? ¿Quién va a tomar la muestra? ¿Dónde se va a tomar? ¿Cómo van a influir los resultados?</b>
      .col-lg-5
        figure
          img(src='@/assets/curso/tema1/1.jpg', alt='')
    p.mb-4 Así pues, las respuestas a estas preguntas serán posibles si el problema se ha definido de manera clara y minuciosa, y se evitaría una cantidad de trabajo no necesario con el que se obtendrían datos sin importancia.
    p.mb-4 A continuación, se muestran en una gráfica algunos elementos técnicos de suma importancia para el estudio del muestreo y preparación de las muestras.

    .row.justify-content-center
      .col-lg-10
        .tarjeta.color-azul.p-4.mb-2
          .row.justify-content-center
            h4.text-center Muestreo y preparación de la muestra
            p.mb-4 Existen dos conceptos técnicos importantes:
          .row.align-items-center.mb-4
            .tarjeta.colorwhite.p-3
              p.mb-0 <b> <FONT COLOR="#0540B7">Muestreo:</FONT> </b> es la acción de tomar una porción representativa de algo. 
          .row.align-items-center.mb-4
            .tarjeta.colorwhite.p-4
              p.mb-0 <b> <FONT COLOR="#0540B7">Preparación de la muestra:</FONT> </b> es el proceso que se le hace al tarro, envase o recipiente en el cual está contenida la muestra recién tomada o recolectada para su conservación, transporte y análisis químico.
          p.mb-4 En la figura que se presenta en esta pantalla, se encuentran representadas algunas de las operaciones previas a realizar para preparar la muestra, desde que se ha realizado el muestreo hasta obtener la muestra de laboratorio que se lleva al instrumento de medida o equipo de laboratorio. Se recomienda estudiarlas con atención y tomar nota de ellas.
          figure.mb-4
            img(src='@/assets/curso/tema1/fig1.svg', alt='')
          .row.justify-content-center
            .col-lg-10
              .tarjeta.colorama.p-4
                .row.align-items-center
                  .col-lg-2
                    .col-10
                      figure
                        img(src='@/assets/curso/tema1/icon1.svg', alt='')
                  .col-lg-10
                    p.mb-0 Dentro de las posibles operaciones de preparación de muestras, algunos autores, como  Rodríguez, Aguera, Gómez, Martínez y Dolores (2010) diferencian dos fases, la primera de ellas correspondiente a una serie de tratamientos previos de la muestra, y la segunda correspondiente a la propia preparación de la muestra para la medida, según el tipo de analito orgánico o inorgánico
        figcaption Figura 6. Esquema en el que se muestran algunas de las operaciones previas.
    separador

    #t_1_2.titulo-segundo.color-acento-contenido
      .h2 1.2	Bases conceptuales

    p.mb-4 En la presente sección, se establecen las bases conceptuales sobre el muestreo y el alistamiento de la muestra. La toma y preparación de una muestra son un problema complejo que tiene muchas variables; así, antes de plantear el sistema de muestreo, envasado y preparación de la muestra:

    .tarjeta.tarjeta-verde.p-4.mb-5
      SlyderA(tipo="b")
        .row.align-items-center
          .col-md-4.mb-4.mb-md-0
            h4 Recolección de muestras en suelo: 
            p Por ejemplo, se pide determinar el contenido de plomo en agua, suelo, aire y residuos sólidos de cierta empresa o ecosistema. Pues bien, se debería conocer el tipo de agua o suelo o aire en concreto y su procedencia. No es lo mismo que el problema sea agua de lluvia o agua residual, lodo o suelo, aire, entre otros; como tampoco es igual que esta sea urbana o que sea industrial.
        
          .col-md-8
            figure
              img(src='@/assets/curso/tema1/slyder1.png', alt='Texto que describa la imagen')
    
        .row.align-items-center
          .col-md-4.mb-4.mb-md-0
            h4 Recolección de muestras en agua:
            p La imagen muestra distintas personas recolectando una muestra para análisis. De otra parte, la muestra que se quiere analizar puede estar contenida en un pequeño recipiente o en un gran depósito, ser de una corriente subterránea o un agua superficial. También hay que tener en cuenta la distribución del analito, como lo menciona Harris (2010), que puede ser homogénea o depender de la profundidad.

          .col-md-8
            figure
              img(src='@/assets/curso/tema1/slyder2.png', alt='Texto que describa la imagen')

        .row.align-items-center
          .col-md-4.mb-4.mb-md-0
            h4 Recolección de muestras en aire: 
            p La imagen muestra un proceso de recolección. También influirá el muestreador, es decir, la persona que realizará la recolección, esta debe estar fuera de todo peligro. Por otra parte, todo lo dicho anteriormente también influirá en el tipo de contenedor a usar con la muestra y a la forma de conservación de esta.
        
          .col-md-8
            figure
              img(src='@/assets/curso/tema1/slyder3.png', alt='Texto que describa la imagen')
    
        .row.align-items-center
          .col-md-4.mb-4.mb-md-0
            h4 Recolección de muestras en residuos sólidos: 
            p Se visualiza la forma de recolectar productos sólidos. Además, a la hora de establecer una estrategia de muestreo habrá que considerar tanto el tipo de analito y su nivel de concentración, como la exactitud y precisión que se requiera de los resultados. No es igual plantear una toma de muestra para análisis rutinario que una toma de muestras para actuar en caso de una demanda.
          .col-md-8
            figure
              img(src='@/assets/curso/tema1/slyder4.png', alt='Texto que describa la imagen')
    p.mb-4 Continuando con las bases conceptuales sobre el muestreo y el alistamiento de la muestra, es momento de conocer la influencia de las diferentes etapas sobre los resultados. ¡Adelante!
    p.mb-4 Se consideran cinco etapas del protocolo completo: 

    .row.justify-content-center
      .col-lg-10
        .tarjeta.color-azul.p-5.mb-2
          ul.lista-ul--color
            li 
              i.fas.fa-check
              p Los elementos de protección personal 
            li 
              i.fas.fa-check
              p Desmuestre o recolección de la muestra
            li 
              i.fas.fa-check
              p Envasado, conservación y transporte
            li 
              i.fas.fa-check
              p Preparación
            li 
              i.fas.fa-check
              p Aplicación de la técnica analítica
            li 
              i.fas.fa-check
              p En lo que se refiere al aseguramiento de la calidad y la reproducibilidad de todo el proceso, las cinco etapas acabadas de mencionar influyen de forma diferente.
            li 
              i.fas.fa-check
              p También, a veces resulta un reto la conservación y transporte de la muestra en condiciones, ya que debe impedirse que se produzcan alteraciones físicas o químicas, debiendo en algunos casos muy específicos realizarse las medidas in situ.
            li 
              i.fas.fa-check
              p Por todo esto la gran importancia de prestar una especial atención a las técnicas de recolección y preservación de las muestras, por la repercusión que tienen sobre la precisión, exactitud y representatividad de los datos que resulten de los análisis y, sobre todo, en la reproducibilidad del proceso completo. 
  
  
   
  
</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema1',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
  },
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
