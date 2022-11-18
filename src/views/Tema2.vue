<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1  Métodos y equipos para la toma de muestras

    .row.align-items-center.mb-4
      .col-lg-6
        .tarjeta.cajon1.p-5
          p.mb-0 En la mayoría de los casos, <b> <FONT COLOR="#0540B7">los protocolos de toma de muestra se encuentran en las normas ASTM, ISO, EPA, UNE o UNE-EN, que son de carácter internacional, y en las que se encontrará protocolizado todo el proceso, desde la etapa de toma de muestra, pasando por reducción, envasado, conservación y método o métodos de aplicación para efectuar la determinación de que se trate, con el fin de asegurar la calidad del proceso.</FONT> </b>  Algunos procedimientos de toma de muestra se dividen en función del estado físico de la matriz; asimismo, de acuerdo con los dos grandes grupos: sólidos y líquidos, se pueden encontrar tablas que resumen los diferentes tipos de recipientes, métodos y tiempos máximos de conservación de las muestras en función del analito a determinar.
      .col-lg-6
        figure
          img(src='@/assets/curso/tema2/1.png', alt='Texto que describa la imagen')
    separador 

    #t_2_1.titulo-segundo.color-acento-contenido
      .h2 2.1	Muestreo y análisis en aguas 

    p.mb-4 A continuación, se presentan las normas y guías técnicas para el alistamiento y valoración de distintas muestras según el protocolo de recolección.
    p.mb-4 <b> <FONT COLOR="#0540B7"> Resolución 631 del 2015. </FONT> </b> Parámetros vertimientos. Por la cual se establecen los parámetros y los valores límites máximos permisibles en los vertimientos puntuales a cuerpos de aguas superficiales y a los sistemas de alcantarillado público y se dictan otras disposiciones.

    .row.mb-4 
      .col-lg-3
        .tarjeta.color-azul.p-4.mb-2
          .row.align-items-center.mb-4 
            .col-lg-3
              figure
                img(src='@/assets/curso/tema2/icon1.svg', alt='Texto que describa la imagen')
            .col-lg-9
              h5.mb-0.text-center NTC-ISO 5667-1 - Calidad del agua 
          p.mb-0.text-center Muestreo. Directrices para el diseño de planes de muestreo. 
      .col-lg-3
        .tarjeta.color-azul.p-4.mb-2
          .row.align-items-center.mb-4 
            .col-lg-3
              figure
                img(src='@/assets/curso/tema2/icon1.svg', alt='Texto que describa la imagen')
            .col-lg-9
              h5.mb-0.text-center NTC-ISO 5667-2 - Calidad del agua 
          p.mb-0.text-center Muestreo. Técnicas generales de muestreo.
      .col-lg-3
        .tarjeta.color-azul.p-4.mb-2
          .row.align-items-center.mb-4 
            .col-lg-3
              figure
                img(src='@/assets/curso/tema2/icon1.svg', alt='Texto que describa la imagen')
            .col-lg-9
              h5.mb-0.text-center NTC-ISO 5667-3 - Calidad del agua
          p.mb-0.text-center Directrices para la preservación y manejo de muestras.
      .col-lg-3
        .tarjeta.color-azul.p-4.mb-2
          .row.align-items-center.mb-4 
            .col-lg-3
              figure
                img(src='@/assets/curso/tema2/icon1.svg', alt='Texto que describa la imagen')
            .col-lg-9
              h5.mb-0.text-center NTC-ISO 5667-10 - Calidad del agua 
          p.mb-0.text-center Muestreo. Muestreo de aguas residuales.
    separador 

    #t_2_2.titulo-segundo.color-acento-contenido
      .h2 2.2	Muestreo y análisis en suelos 

    p.mb-4 Con respecto al muestreo y análisis en suelos, estas son las normas y guías técnicas que regulan los mismos.

    .row.justify-content-center.mb-4
      .col-lg-4
        figure
          img(src='@/assets/curso/tema2/2.png', alt='Texto que describa la imagen')
      .col-lg-7
        SlyderF(columnas="col-lg-6 col-xl-6")
          .tarjeta.colorslyder.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src='@/assets/curso/tema2/icon2.svg' alt='AvatarTop')
            h5.text-center NTC-ISO 4113-1- Calidad del suelo
            p.text-center Muestreo. Directrices para el diseño de planes de muestreo.

          .tarjeta.colorslyder.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src='@/assets/curso/tema2/icon2.svg' alt='AvatarTop')
            h5.text-center NTC-ISO 4113-2- Calidad del suelo
            p.text-center Muestreo. Técnicas generales de muestreo.

          .tarjeta.colorslyder.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src='@/assets/curso/tema2/icon2.svg' alt='AvatarTop')
            h5.text-center NTC-ISO 4113-3- Calidad del suelo
            p.text-center Muestreo. Guía sobre seguridad.

          .tarjeta.colorslyder.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src='@/assets/curso/tema2/icon2.svg' alt='AvatarTop')
            h5.text-center NTC-ISO 4113-4- Calidad del suelo
            p.text-center Muestreo. Sitios cultivados.

          .tarjeta.colorslyder.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src='@/assets/curso/tema2/icon2.svg' alt='AvatarTop')
            h5.text-center NTC-ISO 4113-6- Calidad del suelo
            p.text-center Muestreo. Manejo y almacenamiento del suelo para evaluación de procesos microbianos aeróbicos en el laboratorio.

          .tarjeta.colorslyder.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src='@/assets/curso/tema2/icon2.svg' alt='AvatarTop')
            h5.text-center NTC 3935 - Gestión ambiental
            p.text-center Calidad de suelo. Pretratamiento de muestras para la determinación de contaminantes orgánicos.

          .tarjeta.colorslyder.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src='@/assets/curso/tema2/icon2.svg' alt='AvatarTop')
            h5.text-center NTC-ISO 11464 Gestión ambiental
            p.text-center Calidad del suelo. Pretratamiento de las muestras de suelo para análisis fisicoquímicos.
    separador 

    #t_2_3.titulo-segundo.color-acento-contenido
      .h2 2.3	Muestreo y análisis de olores (aire)

    p.mb-4 Estas son las resoluciones o referentes normativos vigentes para regular el muestreo y análisis de olores. Se recomienda tomar nota de ellas.

    .row.mb-4
      .tarjeta.color-azul2.p-4
        .row.align-items-center
          .col-lg-1
            figure
              img(src='@/assets/curso/tema2/icon3.svg', alt='Texto que describa la imagen')
          .col-lg-11
            p.mb-2 <b> <FONT COLOR="#0540B7"> Resolución 1541 de 2013 </FONT> </b> Por la cual se establecen los niveles permisibles de calidad del aire o de inmisión, el procedimiento para la evaluación de actividades que generan olores ofensivos y se dictan otras disposiciones.
            p.mb-2 <b> <FONT COLOR="#0540B7"> Resolución 2087 de 2014 </FONT> </b> Por la cual se adopta el protocolo para el monitoreo, control y vigilancia de olores ofensivos.
            p.mb-0 <b> <FONT COLOR="#0540B7"> Resolución 1541 de 2013 </FONT> </b> Para la medición de sustancias de olor.

    .row.mb-4
      .tarjeta.colorama2.p-4
        .row.align-items-center
          .col-lg-8
            ul.lista-ul--color
              li 
                i.fas.fa-check
                p.mb-0 <b>NTC 6012-1</b> Efectos y evaluación de los olores. Evaluación psicométrica de las molestias por olores.
              li 
                i.fas.fa-check
                p.mb-0 <b>NTC 4503</b> Análisis sensorial metodología. Iniciación y entrenamiento de evaluadores en la detección y reconocimiento de olores. 
              li 
                i.fas.fa-check
                p.mb-0 <b>NTC 4770</b> Calidad del agua; determinación del olor; método de umbral de olor NTC 838 pinturas; disolventes y diluyentes; identificación y determinación del olor. 
              li 
                i.fas.fa-check
                p.mb-0 <b>NTC 958</b> Agua potable; determinación del olor y del sabor. 
              li 
                i.fas.fa-check
                p.mb-0 <b>NTC 5602</b> Determinación del olor de los adhesivos.
              li 
                i.fas.fa-check
                p.mb-0 <b>NTC 5880</b> Calidad del aire; determinación de la concentración de olor por olfatometría dinámica. 
              li 
                i.fas.fa-check
                p.mb-0 <b>NTC 6012-1</b> Efectos y evaluación de los olores. Evaluación psicométrica de las molestias por olores. Cuestionarios. 
              li 
                i.fas.fa-check
                p.mb-0 <b>NTC 6012-2</b> Efectos y evaluación de olores; determinación de parámetros de molestia mediante preguntas breves repetidas, a panelistas de un vecindario. 
              li 
                i.fas.fa-check
                p.mb-0 <b>NTC 6049-1</b> Medición de impacto de olor mediante inspección en campo; medición de la frecuencia del impacto de olores reconocibles; medición de malla.
              li 
                i.fas.fa-check
                p.mb-0 <b>NTC 6049-2</b> Medición de impacto de olor mediante inspección en campo; medición de la frecuencia del impacto de olores reconocibles. Medición de pluma. 
              li 
                i.fas.fa-check
                p.mb-0 <b>NTC 6049-3</b> Medición de impacto de olor mediante inspección en campo; determinación de intensidad de olor y tono hedónico de olor. 
              li 
                i.fas.fa-check
                p.mb-0 <b>NTC 6049-4</b> Determinación del tono hedónico del olor; perfiles de polaridad.
          .col-lg-4 
            figure
              img(src='@/assets/curso/tema2/3.png', alt='Texto que describa la imagen')
    separador 

    #t_2_4.titulo-segundo.color-acento-contenido
      .h2 2.4	Muestreo y análisis en suelos 

    p.mb-4 En relación con el muestreo de análisis de residuos sólidos, en las siguientes tablas se presentan algunos decretos y otras normativas que se deben tener en cuenta. Se recomienda conocerlas y tomar atenta nota de ellas.

    .row.mb-4
      .col-lg-12
        TabsB.color-acento-contenido.mb-5
          .py-4.py-md-5(titulo="Tabla No.1")
            .row
              .col-lg-2
                figure
                  img(src='@/assets/curso/tema2/icon4.svg', alt='Texto que describa la imagen')
              .col-lg-10
                h5 Tabla No.1 
                p.mb-2 <b> <FONT COLOR="#0540B7"> Decreto 2202 de 1968 </FONT> </b> expedido por la Presidencia de la República. Por el cual se reglamenta la industria y comercio de los abonos o fertilizantes químicos simples, químicos compuestos, orgánicos naturales, orgánicos reforzados, enmiendas y acondicionadores del suelo, y se derogan unas disposiciones.
                p.mb-2 <b> <FONT COLOR="#0540B7"> NTC 2581. 89-06-21 </FONT> </b> Abonos o fertilizantes. Determinación de carbonatos totales y proporciones aproximadas de carbonatos de calcio y magnesio en calizas y calizas dolomíticas. Establece ensayos.
                p.mb-2 <b> <FONT COLOR="#0540B7"> NTC 3795. 95-08-23 </FONT> </b> . Fertilizantes sólidos. Derivación de un plan de muestreo para la evaluación de una entrega grande.
                p.mb-2 <b> <FONT COLOR="#0540B7"> NTC-ISO 8633. 95-08-23 </FONT> </b> Fertilizantes sólidos. Método de muestreo simple para lotes pequeños. Define un plan de muestreo para el control de las cantidades de fertilizante sólido de máximo 250 T y presenta el método a emplear. Se aplica a todos los fertilizantes sólidos a granel o empacados.
                p.mb-2 <b> <FONT COLOR="#0540B7"> NTC-ISO 8634. 95-08-23 </FONT> </b> Fertilizantes sólidos. Plan de muestreo para la evaluación de una entrega grande.
                p.mb-2 <b> <FONT COLOR="#0540B7"> NTC 234. 96-11-27 </FONT> </b> Abonos o fertilizantes. Método de ensayo para la determinación cuantitativa del fósforo. Contiene definiciones, requisitos, métodos de ensayo e informe.
              

          .py-4.py-md-5(titulo="Tabla No. 2")
            .row
              .col-lg-2
                figure
                  img(src='@/assets/curso/tema2/icon4.svg', alt='Texto que describa la imagen')
              .col-lg-10
                h5 Tabla No.2 
                p.mb-2 <b> <FONT COLOR="#0540B7"> NTC 4150. 97-06-25 </FONT> </b> Abonos o fertilizantes. Método cuantitativo para la determinación del nitrógeno amoniacal por titulación previo tratamiento con formaldehído. Establece un método cuantitativo para determinar el contenido de nitrógeno amoniacal en abonos o fertilizantes.
                p.mb-2 <b> <FONT COLOR="#0540B7"> NTC 4173. 97-06-25 </FONT> </b> Fertilizantes sólidos y acondicionadores del suelo. Ensayo de tamizado. Especifica un método para la determinación, mediante ensayos de tamizado, la distribución del tamaño de partículas de los fertilizantes sólidos y los acondicionadores de suelos. 
                p.mb-2 <b> <FONT COLOR="#0540B7"> NTC 4175. 97-06-25 </FONT> </b> Fertilizantes sólidos. Preparación de muestras para análisis químicos y físicos. Especifica los métodos para la preparación de las muestras o porciones de muestras requeridas para los ensayos químicos o físicos de fertilizantes sólidos. Contiene definiciones, aparatos, rotulado y reporte de preparación de muestra. 
                p.mb-2 <b> <FONT COLOR="#0540B7"> NTC 370. 97-08-27 </FONT> </b> Abonos o fertilizantes. Determinación del nitrógeno total. Establece el método para determinar el contenido de nitrógeno total en abonos o fertilizantes. Contiene definiciones y ensayos. 
                p.mb-2 <b> <FONT COLOR="#0540B7"> NTC 35. 98-03-18 </FONT>  </b> Abonos y fertilizantes. Determinación de la humedad. Del agua libre y del agua total. Establece los métodos para determinar el contenido de humedad, agua libre y agua total en abonos o fertilizantes. Contiene definiciones y ensayos. 
                p.mb-2 <b> <FONT COLOR="#0540B7"> NTC 202. 01-08-01 </FONT> </b> Métodos cuantitativos para la determinación de potasio soluble en agua, en abonos o fertilizantes y fuentes de materias para su fabricación. Establece los métodos cuantitativos para la determinación del contenido de potasio soluble en agua, en abonos o fertilizantes y fuentes. De materias primas para su fabricación. 

          .py-4.py-md-5(titulo="Tabla No. 3")
            .row
              .col-lg-2
                figure
                  img(src='@/assets/curso/tema2/icon4.svg', alt='Texto que describa la imagen')
              .col-lg-10
                h5 Tabla No.3
                p.mb-2 <b> <FONT COLOR="#0540B7"> NTC 1927. 01-10-31 </FONT> </b> Fertilizantes y acondicionadores de suelos. Definiciones. Clasificación y fuentes de materias primas. Define los términos relacionados con fertilizantes, acondicionadores del suelo, fuentes de materias primas, y sus clasificaciones. 
                p.mb-2 <b> <FONT COLOR="#0540B7"> Resolución 074 de 2002 </FONT> </b> Elaborada por el Ministerio de Agricultura y Desarrollo Rural. Por la cual se establece el reglamento para la producción primaria, procesamiento, empacado, etiquetado, almacenamiento, certificación, importación y comercialización de productos agropecuarios ecológicos. El prefijo BIO únicamente puede ser utilizado en acondicionadores orgánicos registrados para agricultura ecológica, que involucren microorganismos en su composición. 
                p.mb-2 <b> <FONT COLOR="#0540B7"> Resolución ICA No. 00150 del 21 de enero de 2003 </FONT> </b> Expedida por el Instituto Colombiano Agropecuario. Por el cual se adopta el reglamento técnico de fertilización y acondicionadores de suelos para Colombia. 
                p.mb-2 <b> <FONT COLOR="#0540B7"> NTC 40. 03-03-19 </FONT> </b> Fertilizantes y acondicionadores de suelos. Etiquetado. Establece los requisitos que debe cumplir el etiquetado de los envases y embalajes destinados para fertilizantes y acondicionadores de suelos. 
                p.mb-2 <b> <FONT COLOR="#0540B7"> NTC 5167. 2004-05-31 </FONT>  </b> Productos para la industria agrícola. Materiales orgánicos usados como fertilizantes y acondicionadores del suelo. Establece requisitos que deben cumplir y los ensayos a los cuales deben ser sometidos los productos orgánicos usados como fertilizantes o como acondicionadores del suelo. Reglamenta los limitantes actuales para el uso de materiales orgánicos, los parámetros físicoquímicos de los análisis de las muestras de materia orgánica, los límites máximos de metales y enuncia algunos parámetros para los análisis microbiológicos.
    .row.justify-content-center
      .col-lg-10
        .tarjeta.colorama.p-4
          .row 
            .col-lg-1
              figure
                img(src='@/assets/curso/tema2/icon5.svg', alt='Texto que describa la imagen')
            .col-lg-11
              h5 Importante: una muestra representativa antes de ingresar al laboratorio.
              p.mb-4 ¡Un buen análisis o ensayo para caracterizar y valorar una muestra depende de que la cantidad sea representable del sitio y el lugar de donde se tomó o recolectó!
              p.mb-4 Un plan de toma de muestra debe asegurar que la obtenida refleje adecuadamente las propiedades que interesan del lote del que proviene, es decir, la muestra final debe ser:
              ul.lista-ul--color.mb-4
                li 
                  i.fas.fa-check
                  p.mb-0 Tan similar como sea posible a la población global a analizar
                li 
                  i.fas.fa-check
                  p.mb-0 Poseer sus características esenciales
                li 
                  i.fas.fa-check
                  p.mb-0 Ser reproducible
              p.mb-4 Para conseguir este resultado es necesario seleccionar subáreas y métodos de toma de muestra con base en criterios estadísticos y/o la experiencia previa.
              p.mb-0 Al aumentar el número y volumen de las muestras, aumenta la representatividad, pero las consideraciones económicas y de conveniencia introducirán límites en ambos, ya que no se pueden manejar y transportar toneladas de muestra, y que al final, la técnica analítica a emplear limitará aún más la cantidad de la muestra para análisis.


</template>

<script>
export default {
  name: 'Tema2',
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
