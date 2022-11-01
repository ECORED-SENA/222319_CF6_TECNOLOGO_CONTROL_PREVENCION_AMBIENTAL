<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1  Factores que influyen en la representatividad

    p.mb-4 De acuerdo con la Comisión Europea, los factores que relacionan e influyen en la representatividad son los siguientes:

    .tarjeta.tarjeta-verde.p-4.mb-5
      SlyderA(tipo="b")
        .row.align-items-center
          .col-md-4.mb-4.mb-md-0
            h4 Estado físico del lote de muestra
            p En general los materiales sólidos son heterogéneos, y más cuanto mayor es su extensión, pero no es posible generalizar para un determinado analito, ya que pueden en ocasiones presentar homogeneidad. En lo que se refiere a líquidos y gases, se tiene una idea generalizada de que presentan un mayor grado de homogeneidad, pero en un análisis del agua de un lago, se encuentran grandes diferencias entre las muestras de superficie, las de media altura y las de fondo, así como entre las obtenidas en el centro o las próximas a la orilla o a una zona donde llegan aportes.  
        
          .col-md-8
            figure
              img(src='@/assets/curso/tema3/slyder1.png', alt='Texto que describa la imagen')
    
        .row.align-items-center
          .col-md-4.mb-4.mb-md-0
            h4 Número y tamaño de las porciones
            p Para cada población, se determina estadísticamente el número mínimo de porciones y su tamaño para que la muestra resulte representativa sin disparar el coste económico y de personal. 

          .col-md-8
            figure
              img(src='@/assets/curso/tema3/slyder2.png', alt='Texto que describa la imagen')

        .row.align-items-center
          .col-md-4.mb-4.mb-md-0
            h4 Fluctuaciones estacionales o temporales
            p El momento de la toma de muestra puede verse influido por variaciones espacio-temporales producidas por aspectos climatológicos o temporales, temperatura, humedad, presencia de contaminantes o componentes que fluctúen con la hora del día, la época del año, etc.
        
          .col-md-8
            figure
              img(src='@/assets/curso/tema3/slyder3.png', alt='Texto que describa la imagen')
    
        .row.align-items-center
          .col-md-4.mb-4.mb-md-0
            h4 Manipulación, almacenamiento y transporte de las muestras 
            p Durante las operaciones de toma, cuarteo, reducción del tamaño de partícula por molienda, tamizado o envasado de la muestra, o en el posterior transporte y almacenamiento, debe prevenirse que los analitos sufran alteraciones o pérdidas (oxidación, aumento o disminución de la humedad, intercambio de componentes con el recipiente, etc.).
            p (Comisión Europea, 2021) Seguidamente, con base en la precisión, exactitud, reproducibilidad y límites de detección necesarios, se establecerán los métodos analíticos a emplear. Es necesario prestar mucha atención a la información que se presenta a continuación.

          .col-md-8
            figure
              img(src='@/assets/curso/tema3/slyder4.png', alt='Texto que describa la imagen')
    .row.mb-4
      .col-lg-6
        .sub.p-2
          h4.mb-0.text-center.text-white Precisión, exactitud, reproducibilidad y límites de detección

    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema3/1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Una vez fijados los métodos analíticos, con base en la incertidumbre de sus resultados, en las fases tercera y cuarta, empleando métodos estadísticos, se establecerá el número y masa de las muestras, así como el espaciado con que se deben tomar. Se determinará el método de toma de muestras, incluyendo la descripción detallada del procedimiento de obtención, equipo necesario, contenedores a emplear para conservarlas, indicando si se deberán mantener las muestras individuales, o la forma de proceder para preparar la muestra compuesta. También se harán constar los cuidados especiales para preservar las muestras, tales como refrigeración, aditivos, etc., y se establecerán las primeras etapas de tratamiento, especialmente las que contemplan la reducción de la muestra primaria hasta la de laboratorio.
    p.mb-0 (Comisión Europea, 2021)
    p.mb-0 Los códigos a usar en el etiquetado y en el cuaderno de seguimiento de las muestras, así como los aspectos legales y de seguridad del personal que sean de aplicación.
    p.mb-4 Por fin, en la última fase, se redacta el protocolo completo y se recogen todos los aspectos mencionados hasta ahora, y nunca se toma como definitivo, ya que debe estar sometido a revisión continua en función de la experiencia, por si resulta necesario mejorarlo o actualizarlo.
    p.mb-4 En consecuencia con lo anterior, <b> <FONT COLOR="#0540B7"> ¿cuánta muestra se debería llevar para realizar el análisis químico, físico y microbiológico? </FONT> </b>
    p.mb-4 El plan de toma de muestra debe incluir la estimación del tamaño de muestra necesario para minimizar los errores aleatorios.

    .tarjeta.color-celeste.p-4.mb-4
      .row.mb-3 
        .col-lg-12
          b Va a depender de:
      .row.align-items-center
        .col-lg-3
          figure
            img(src='@/assets/curso/tema3/2.jpg', alt='Texto que describa la imagen')
        .col-lg-9
          ul.lista-ul--color.mb-0
            li 
              i.fas.fa-check
              p.mb-0 La matriz de la muestra.
            li 
              i.fas.fa-check
              p.mb-0 De la distribución del analito.
            li 
              i.fas.fa-check
              p.mb-0 Del grado de homogeneidad.
            li 
              i.fas.fa-check
              p.mb-0 De la magnitud del error exigido.
            li 
              i.fas.fa-check
              p.mb-0 Para muestras homogéneas en el espacio y el tiempo, dependerá fundamentalmente de la etapa de determinación final y de la concentración del analito, ya que en la muestra final esta deberá superar el límite de cuantificación del método.
            li 
              i.fas.fa-check
              p.mb-0 Para muestras heterogéneas, como lo menciona la Comisión Europea (2018), es necesario aplicar la estadística. En muchos casos, la complejidad de las muestras hace que un tratamiento estadístico riguroso resulte desproporcionado respecto de los objetivos, por lo que se decide el tamaño de muestra de acuerdo con la experiencia.
            li 
              i.fas.fa-check
              p.mb-0 En otros casos, como ocurre en la minería, son pocos los analitos que pueden interesar y el estudio estadístico está justificado económicamente por la necesidad de caracterizar un depósito.
            li 
              i.fas.fa-check
              p.mb-0 En la mayoría de las ocasiones, suelen emplearse métodos estadísticos aproximados con base en la experiencia, así ocurre con el método del coeficiente de variación.
    .tarjeta.colorama3.p-4.mb-4
      .row.align-items-center
        .col-lg-7
          p.mb-4 En esta misma línea, se requiere establecer el <b>tamaño de la muestra en función del coeficiente de variación.</b>
          p.mb-0 El valor del coeficiente de variación V para una serie de muestras viene dado por el cociente entre la desviación estándar (σ) y el valor medio de las muestras, multiplicado por 100. 
        .col-lg-5
          figure
            img(src='@/assets/curso/tema3/icon1.svg', alt='Texto que describa la imagen')

    .tarjeta.colorverd1.p-4.mb-4
      .row.justify-content-center.align-items-center
        .col-lg-1
          figure
            img(src='@/assets/curso/tema3/3.jpg', alt='Texto que describa la imagen')
        .col-lg-10
          .bloque-texto-b.p-2
            .bloque-texto-b__texto
              i.fas.fa-quote-left
              p.mb-0 <b>Como lo mencionan García-García et al. (2013),</b> una vez obtenido dicho valor, el tamaño de muestra mínimo se obtiene de la tabla 1, en la que, como se puede observar, al aumentar la irregularidad en la distribución del analito, aumenta el valor de V y también la masa de muestra necesaria.
              i.fas.fa-quote-right

    p.mb-4 Finalmente, y sin olvidar que una muestra de calidad representa un excelente análisis en campo y en el laboratorio, de esto depende el 60% del éxito en los análisis fisicoquímicos. Siendo así, es necesario tener en cuenta dos elementos más para un proceso exitoso: 

    TabsB.color-acento-contenido.mb-5
      .py-4.py-md-5(titulo="Espaciado entre muestras" :icono="require('@/assets/curso/tema3/icon2.svg')")
        .row.mb-4
          .col-md-12
            h4 Espaciado entre muestras
        .row.align-items-center.mb-4
          .col-lg-7
            p.mb-2 Empleando los variogramas, se puede establecer una correlación espacial de la variación de la concentración del analito que interesa y, en función de esa correlación, establecer una representación gráfica (semivariograma experimental), como lo menciona Canchaya-Moya (2005). Con base en ella, se puede determinar la distancia a partir de la que empieza la dispersión de los valores de la concentración, desapareciendo la relación espacial que existía y de esta forma establecer la distancia mínima y máxima entre puntos de muestra en cada dirección, con un ahorro en número de puntos de muestreo considerable respecto de otros métodos; pero, a su vez, el método es muy complejo y requiere un gran número de muestras previas para aplicarlo, por lo que sólo se justifica en caso de evaluaciones de grandes explotaciones. En la mayoría de los casos suele bastar con aplicar el método del coeficiente de variación.
          .col-lg-5
            figure
              img(src='@/assets/curso/tema3/4.jpg', alt='Texto que describa la imagen')
        p.mb-4 Según la Universidad Politécnica de Cartagena (2017), en función de la anisotropía de la distribución del analito, aumenta el coeficiente de variación y, por consiguiente, se hace necesario disminuir la distancia entre puntos de toma de muestras. Si el espaciado aumenta sobre los valores de la tabla 1, se encuentran muestras no correlacionadas, y, por el contrario, si se emplean unas distancias menores, se ocasiona una sobredensidad de muestreo que conllevará un gasto innecesario en sondeos.
        p.mb-0 En algunas ocasiones, el método, dada su sencillez, puede llevar a unos espacios excesivamente estrechos, aquí es donde la experiencia puede corregir ligeramente el problema en algunas zonas cuando se advierta el sobredimensionado.

      .py-4.py-md-5(titulo="Número de muestras" :icono="require('@/assets/curso/tema3/icon2.svg')")
        .row.mb-4
          .col-md-12
            h4 Número de muestras
        .row.align-items-center.mb-4
          .col-lg-7
            p.mb-2 A la hora de abordar el planteamiento de la toma de muestras, los métodos estadísticos ayudan a determinar el número de muestras individuales que es necesario tomar para minimizar la variabilidad de los resultados finales, teniendo en cuenta la homogeneidad o heterogeneidad de la población objeto de la toma de muestras y el error máximo admisible, lo que ayudará a que la operación se realice dentro de un óptimo económico. 
          .col-lg-5
            figure
              img(src='@/assets/curso/tema3/5.jpg', alt='Texto que describa la imagen')

    .tarjeta.colorama3.p-4.mb-4
      .row.align-items-center
        .col-lg-7
          p.mb-4 Para una distribución normal del analito, si conocemos σ, el número de muestras mínimo N para un intervalo de confianza dado y un error máximo E viene dado por la expresión:
        .col-lg-5
          figure
            img(src='@/assets/curso/tema3/icon3.svg', alt='Texto que describa la imagen')

    .tarjeta.color-celeste.p-4.mb-1
      .row 
        .col-lg-12
          b.mb-2 Dónde: 
          p.mb-0 <b> <FONT COLOR="#80CAB6"> σ - </FONT> </b> desviación estándar
          p.mb-0 <b> <FONT COLOR="#80CAB6"> Z – </FONT> </b> parámetro de población, que se obtiene de tablas para un nivel de probabilidad dado.
          p.mb-4 <b> <FONT COLOR="#80CAB6"> E – </FONT> </b> error máximo aceptado.
          p.mb-4 Para una distribución irregular del analito y un bajo número de muestras previas (<20), la expresión del número de muestras mínimo N para un intervalo de confianza dado y un error máximo E se transforma en la expresión:
          .row.align-items-center
            .col-lg-3
              figure
                img(src='@/assets/curso/tema3/icon4.svg', alt='Texto que describa la imagen')
            .col-lg-9
              b.mb-2 Dónde:
              p.mb-0 <b> <FONT COLOR="#80CAB6"> Sm2 – </FONT> </b> varianza de la muestra
              p.mb-0 <b> <FONT COLOR="#80CAB6"> t – </FONT> </b> parámetro t de Student para (n -1) grados de libertad o muestras y un nivel de confianza dado. Se obtiene de tablas.
              p.mb-4 <b> <FONT COLOR="#80CAB6"> E – </FONT> </b> error máximo aceptado.
    figcaption.mb-4 (Universidad Politécnica de Cartagena, 2017)   
              
    .row.justify-content-center 
      .col-lg-10
        .tarjeta.color-primario.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema3/icon5.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h5.mb-1 Para poder completar y profundizar en el estudio de los factores que influyen en la representatividad, se invita a hacer lectura consciente y atenta 
                  p.mb-0 Anexo 1_OtrosFactoresInfluyenEnRepresentatividad
                .col-sm-auto
                  a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download

</template>

<script>
export default {
  name: 'Tema3',
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
