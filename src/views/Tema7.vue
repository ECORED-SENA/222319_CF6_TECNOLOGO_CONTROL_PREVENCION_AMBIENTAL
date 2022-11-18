<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 7
      h1 Recepción de muestras 

    figure.mb-4
      img(src='@/assets/curso/tema7/1.jpg', alt='Texto que describa la imagen')
    p.mb-4 La recepción de las muestras es uno de los pasos más importantes en el análisis de las mismas, ya que constituye un pilar fundamental para la trazabilidad de la información que ello conlleva.
    separador

    #t_7_1.titulo-segundo.color-acento-contenido
      .h2 7.1 Recepción de la muestra al laboratorio (agua)

    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema7/2.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 El laboratorio donde se practican los análisis fisicoquímicos y microbiológicos de las muestras para la vigilancia, generalmente, cuenta con instalaciones y equipos propios de la autoridad sanitaria y son operados por especialistas en técnicas de análisis de agua. Los laboratorios donde se practican los análisis fisicoquímicos y microbiológicos de las muestras para el control cuentan con instalaciones, equipos y personal propios de la persona prestadora o son laboratorios particulares autorizados por el Ministerio de la Protección Social, según resolución expedida por el Ministerio de la Protección Social, porque cumplen con los requisitos mínimos previstos en el Artículo 27 del Decreto 1575 de 2007. 
    .row.mb-4
      .col-lg-3
        .sub.p-2
          h4.mb-0.text-center.text-white Algunas recomendaciones
    p.mb-4 El personal de estos laboratorios, encargados de la recepción de las muestras, así como los encargados de la recolección y transporte de las muestras, debe seguir algunas recomendaciones, especialmente en aquellos laboratorios donde por la complejidad y tamaño de los sistemas de distribución, se procesan muestras recogidas por varios equipos de recolección o procedentes de varios clientes, como es el caso de los laboratorios particulares.

    .row.mb-4
      .col-lg-4
        .sub.p-2
          h4.mb-0.text-center.text-white Procedimiento de entrada y registro
    p.mb-4 Las muestras deben registrarse en cuanto lleguen al laboratorio. El procedimiento de entrada y registro de la muestra es importante para los propósitos de la cadena de custodia. Y se requiere la siguiente información en el procedimiento de entrada y registro:
    .row.justify-content-center.mb-4
      .col-lg-10
        .tarjeta.tarjeta-verde2.p-4
          .row 
            .col-lg-2
              figure
                img(src='@/assets/curso/tema7/icon1.svg', alt='Texto que describa la imagen')
            .col-lg-10
              p.mb-0 a. Número de código de la muestra. 
              p.mb-0 b. Nombre de la persona prestadora, para el caso de los laboratorios de vigilancia o los laboratorios particulares que atienden varios clientes. 
              p.mb-0 c. Nombre del (o los) tomador(es) de muestras. 
              p.mb-0 d. Número del método de muestreo.
              p.mb-0 e. Localización de almacenamiento de la muestra. 
    .row.mb-4
      .col-lg-2
        .sub.p-2
          h4.mb-0.text-center.text-white Inspección

    .row.align-items-center.mb-4
      .col-lg-6
        p.mb-0 El recepcionista del laboratorio debe inspeccionar el etiquetado de las muestras y compararlo con la información del registro de campo o acta de toma de muestra de agua, si se trata de muestras para vigilancia. Si hay conformidad en esta inspección, el recepcionista del laboratorio firma este documento de vigilancia o control, incluyendo la fecha y hora de llegada. Si no hay conformidad, el recolector anota en la parte del formato correspondiente las observaciones o las inconformidades encontradas en la inspección de las muestras y firma el acta, incluyendo la fecha y hora de llegada. Para cualquiera que sea el caso anteriormente descrito, le asigna un número o código para su entrada, la registra en el libro del laboratorio y guarda las muestras en el cuarto frío, bajo llave, hasta que sea asignada a un analista. Una vez la muestra está en el laboratorio, el encargado del cuarto frío y los analistas son responsables de su cuidado y vigilancia.
      .col-lg-6
        figure
          img(src='@/assets/curso/tema7/1.png', alt='Texto que describa la imagen')

    .tarjeta.color1.mb-4
      .row.align-items-end.px-4
        .col-lg-6
          figure
            img(src='@/assets/curso/tema7/fig1.svg', alt='Texto que describa la imagen')
        .col-lg-6
          .row.align-items-center.py-4
            h5.mb-4 ¿Agilidad o preservación?
            p.mb-4 Las muestras se deben entregar en el laboratorio lo más pronto posible. Como máximo en un término de seis (6) horas desde el momento en que se inició el proceso de recolección. Si no es posible cumplir con este tiempo, se deben prever procedimientos de almacenamiento y preservación para asegurar su entrega en las horas previstas por el laboratorio. Es importante coordinar el envío de las muestras al laboratorio en horas convenientes, con el propósito de realizar los análisis en el horario normal de trabajo y el mismo día, si es posible.
            p.mb-0 A su llegada al laboratorio, si es imposible analizar las muestras de inmediato. Estás se deben preservar en condiciones tales que eviten cualquier contaminación procedente del exterior del recipiente y que impidan cualquier cambio de su contenido. Para este propósito se recomienda usar gabinetes refrigerados o fríos y lugares oscuros. Después de su llegada al laboratorio, las muestras se deben manejar refrigeradas y el análisis debe iniciarse de inmediato o máximo a las dos horas siguientes de su llegada.  
    separador 

    #t_7_2.titulo-segundo.color-acento-contenido
      .h2 7.2 Recepción de la muestra al laboratorio (suelo)
    
    p.mb-4 En el proceso de recepción de la muestra (de suelo) en el laboratorio, se tiene un mecanismo muy similar al descrito en el proceso de recepción de muestras de agua.

    AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
      .row(titulo="El laboratorio")
        .col-lg-12
          p El laboratorio donde se practican los análisis fisicoquímicos y microbiológicos de las muestras son operados por especialistas en técnicas de análisis de suelo. Los laboratorios donde se practican los análisis fisicoquímicos y microbiológicos de las muestras para el control cuentan con instalaciones, equipos y personal propios de la persona prestadora o son laboratorios particulares autorizados. El personal de estos laboratorios encargados de la recepción de las muestras, así como los encargados de la recolección y transporte de las muestras, debe seguir las siguientes recomendaciones, especialmente en aquellos laboratorios donde, por la complejidad y tamaño de los sistemas de distribución, se procesan muestras recogidas por varios equipos de recolección o procedentes de varios clientes, como es el caso de los laboratorios particulares.

      .row(titulo="Registro inmediato")
        .col-lg-12
          p.mb-4 Las muestras deben registrarse en cuanto lleguen al laboratorio. El procedimiento de entrada y registro de la muestra es importante para los propósitos de la cadena de custodia. 
          p.mb-4 La siguiente información debe requerirse en el procedimiento de entrada y registro: 
          p.mb-0 a. Número de código de la muestra. 
          p.mb-0 b. Nombre de la persona prestadora, para el caso de los laboratorios de vigilancia o los laboratorios particulares que atienden varios clientes. 
          p.mb-0 c. Nombre del (o los) tomador(es) de muestras. 
          p.mb-0 d. Número del método de muestreo.
          p.mb-0 e. Localización de almacenamiento de la muestra. 
      
      .row(titulo="Inspección y etiquetado")
        .col-lg-12
          p.mb-4 El recepcionista del laboratorio debe inspeccionar el etiquetado de las muestras y compararlo con la información del registro de campo o acta de toma de muestra de suelo. Si hay conformidad en esta inspección, el recepcionista del laboratorio firma este documento de vigilancia o control, incluyendo la fecha y hora de llegada. Si no hay conformidad, el recolector anota en la parte del formato correspondiente las observaciones o las inconformidades encontradas en la inspección de las muestras y firma el acta incluyendo la fecha y hora de llegada. Para cualquiera que sea el caso anteriormente descrito, a la muestra se le asigna un número o código para su entrada, se registra en el libro del laboratorio y se guarda en el cuarto frío, bajo llave, hasta que sea asignada a un analista. Una vez la muestra está en el laboratorio, el encargado del cuarto frío y los analistas son responsables de su cuidado y vigilancia.

      .row(titulo="Prontitud en la entrega")
        .col-lg-12
          p.mb-0 Las muestras se deben entregar en el laboratorio lo más pronto posible. Es importante coordinar el envío de las muestras al laboratorio en horas convenientes, con el propósito de realizar los análisis en el horario normal de trabajo y el mismo día, si es posible.
          p.mb-0 A su llegada al laboratorio, si es imposible analizar las muestras de inmediato, estas se deben preservar en condiciones tales que eviten cualquier contaminación procedente del exterior del recipiente, su deterioro y que impidan cualquier cambio de su contenido.
          p.mb-0 Para este propósito se recomienda usar gabinetes refrigerados o fríos y lugares oscuros. Se deben manejar las muestras refrigeradas después de su llegada al laboratorio.
    separador 

    #t_7_3.titulo-segundo.color-acento-contenido
      .h2 7.3 Recepción de la muestra al laboratorio (olores)

    .bloque-texto-g.color-bloque.p-3.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema7/3.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 En la última fase de la recolección de muestras, se requiere supervisión y control constante; su importancia radica en organizar las actividades de transporte, preservación, almacenamiento y recepción de las muestras de tal forma que estas no sean alteradas, modificadas o que generen un riesgo que se materialice en resultados no verídicos al procesar las muestras.

    .row.mb-4
      .col-lg-2
        .sub.p-2
          h4.mb-0.text-center.text-white Cadena de custodia

    p.mb-4 De acuerdo con el Instituto Colombiano de Normas Técnicas y Certificación [ICONTEC] (2004), en la guía técnica colombiana [GTC] 100, la cadena de custodia se define como el procedimiento que se da cuando una muestra está bajo custodia (posesión o control físico) de alguien, de modo que se debe evitar la manipulación indebida o alteración de sus características, desde la toma de la muestra hasta que se desecha (p.3).

    .row.mb-4
      .col-lg-3
        .sub.p-2
          h4.mb-0.text-center.text-white Control y seguimiento

    p.mb-4 Como se puede evidenciar en el siguiente esquema, la cadena de custodia es un proceso de control y seguimiento que se inicia antes de la toma de la muestra, ya que debe ser la base para la programación de esta desde el plan de muestreo.

    .row.justify-content-center.mb-4
      .col-lg-10
        p.mb-0 <b>Figura 5</b>
        p.mb-4 Programa de muestreo de agua
      .col-lg-10
        .tarjeta.color-celeste.p-4
          .row.align-items-center
            .col-lg-8
              figure
                img(src='@/assets/curso/tema7/fig2.svg', alt='Texto que describa la imagen')
            .col-lg-4
              figure
                img(src='@/assets/curso/tema7/fig3.svg', alt='Texto que describa la imagen')

    .row.mb-4
      .col-lg-2
        .sub.p-2
          h4.mb-0.text-center.text-white Criterios
    p.mb-4 De acuerdo con el Instituto Nacional de Salud [INS], en su manual de instrucciones para la toma, preservación y transporte de muestras de agua de consumo humano para análisis de laboratorio, a manera general, se podría definir que la cadena de custodia involucra las definiciones de criterios para las siguientes actividades:  
    .row.justify-content-center.mb-4
      .col-lg-10
        .row.justify-content-center.mb-4
          .col-lg-10
            .tarjeta.colorama3
              .row.align-items-end.px-5.py-1
                .col-lg-6
                  figure
                    img(src='@/assets/curso/tema7/icon2.svg', alt='Texto que describa la imagen')
                .col-lg-1
                  span
                .col-lg-5
                  ul.lista-ul--color.m-2
                    li 
                      i.fas.fa-check
                      p.mb-0 La toma de la muestra
                    li 
                      i.fas.fa-check
                      p.mb-0 El uso del recipiente para la misma
                    li 
                      i.fas.fa-check
                      p.mb-0 El almacenamiento temporal
                    li 
                      i.fas.fa-check
                      p.mb-0 El transporte al laboratorio
                    li 
                      i.fas.fa-check
                      p.mb-0 Almacenamiento en el laboratorio
                    li 
                      i.fas.fa-check
                      p.mb-0 El desarrollo de los análisis
                    li 
                      i.fas.fa-check
                      p.mb-0 El desechado de la muestra (p.51)
    .row.mb-4
      .col-lg-4
        .sub.p-2
          h4.mb-0.text-center.text-white Garantía de datos y conclusiones
    p.mb-4 Por lo tanto, la importancia de la cadena de custodia es garantizar el soporte de los datos y conclusiones a los que se llegue con el estudio o ensayo de muestreo de forma adecuada en una situación legal o reglamentaria, que busca mantener registros que certifiquen que los procedimientos fueron desarrollados según condiciones técnicas y que los resultados son verídicos y fiables (ICONTEC, 2004, p.3).
    separador 

    #t_7_4.titulo-segundo.color-acento-contenido
      .h2 7.4 La entrega al laboratorio

    p.mb-4 Las muestras de olores deben registrarse en cuanto lleguen al laboratorio. El procedimiento de entrada y registro de la muestra es importante para los propósitos de la cadena de custodia. 
    .row.justify-content-center.mb-4
      .col-lg-10
        p.mb-4 La siguiente información debe requerirse en el procedimiento de entrada y registro: 
      .col-lg-10
        .tarjeta.color-fondo.py-4.px-5
          .row.justify-content-star
            .col-lg-6
              p.mb-1 <b>a.</b> Número de código de la muestra. 
              p.mb-1 <b>b.</b> Nombre de la persona prestadora, para el caso de los laboratorios de vigilancia o los laboratorios particulares que atienden varios clientes. 
              p.mb-1 <b>c.</b> Nombre del (o los) tomador(es) de muestras. 
              p.mb-1 <b>d.</b> Número del método de muestreo.
              p.mb-1 <b>e.</b> Localización de almacenamiento de la muestra.
    p.mb-4 Al finalizar la entrega se debe realizar el respectivo seguimiento y la respectiva trazabilidad de la documentación y muestras.

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
