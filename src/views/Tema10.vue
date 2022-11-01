<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 10
      h1 Sistema internacional de medidas y notación científica 

    p.mb-4 En esta sección se verán los microorganismos y sus principales características, tanto sus morfologías como en sus respectivos análisis.

    .row.justify-content-center.mb-4 
      .col-lg-10
        .tarjeta.colorcian.p-4
          .row.align-items-center
            .col-lg-2
              figure
                img(src='@/assets/curso/tema10/icon1.svg', alt='Texto que describa la imagen') 
            .col-lg-10
              p.mb-0 Los microorganismos son aquellos organismos que, por su tamaño reducido, son imperceptibles a la vista. También denominados “microbios”, estos organismos cuentan con una organización biológica muy básica: una proporción importante de ellos cuenta con apenas una única célula. Además, se caracterizan por existir numerosas variedades, de diferentes formas y tamaños. Los organismos unicelulares procariotas y eucariotas, junto con ciertos hongos y algas, componen el universo de los microbios.
    .row.align-items-center.mb-4
      .col-lg-7
        p.mb-4 Los microorganismos tienen la capacidad de alterar el medio en el cual se encuentran. Los microorganismos tienen una serie de características en común:
        .tarjeta.colorama.p-4
          ul.lista-ul--color.m-2
            li 
              i.fas.fa-check
              p.mb-0 Su tamaño es tan reducido que son imperceptibles a simple vista.
            li 
              i.fas.fa-check
              p.mb-0 Sus reacciones metabólicas son muy veloces.
            li 
              i.fas.fa-check
              p.mb-0 La relación que mantienen con el medio es intensa.
            li 
              i.fas.fa-check
              p.mb-0 Necesitan agua para metabolizar. 
            li 
              i.fas.fa-check
              p.mb-0 Desarrollan mecanismos de dispersión y de resistencia.
            li 
              i.fas.fa-check
              p.mb-0 Tienen la capacidad de alterar el medio en el cual se encuentran.
            li 
              i.fas.fa-check
              p.mb-0 Se reproducen a una gran velocidad.
            li 
              i.fas.fa-check
              p.mb-0 Su actividad es indispensable para la vida en el planeta.
            li 
              i.fas.fa-check
              p.mb-0 Forman parte de los ciclos biogeoquímicos que se llevan a cabo en la naturaleza.
            li 
              i.fas.fa-check
              p.mb-0 Son muy livianos, por lo que se transportan en el aire. 
      .col-lg-5
        figure
          img(src='@/assets/curso/tema10/img1.jpg', alt='Texto que describa la imagen') 
    separador 

    #t_10_1.titulo-segundo.color-acento-contenido
      .h2 10.1 Tipos de microorganismos

    p.mb-4 Dentro de la naturaleza se pueden identificar diferentes tipos de microorganismos. Algunos de ellos son los siguientes:

    .row.justify-content-center.mb-4 
      .col-lg-12
        SlyderF.mb-5(columnas="col-lg-6 col-xl-4")
          .tarjeta-avatar
            img(src='@/assets/curso/tema10/avatar1.svg' alt='AvatarTop')
            .tarjeta.color-avatar2
              .p-4
                h4.text-center Virus
                p.text-center Son los microbios más básicos y solamente se los puede percibir con microscopios electrónicos. Para reproducirse, deben infectar a otros organismos unicelulares, a los que les inoculan su contenido genético (solo pueden reproducirse en una célula huésped).

          .tarjeta-avatar
            img(src='@/assets/curso/tema10/avatar2.svg' alt='AvatarTop')
            .tarjeta.color-avatar2
              .p-4
                h4.text-center Algas cianofíceas
                p.text-center Se trata de bacterias de gran tamaño y se caracterizan por hacer fotosíntesis de manera muy similar a las plantas, es decir, oxigénica (desprenden oxígeno).

          .tarjeta-avatar
            img(src='@/assets/curso/tema10/avatar3.svg' alt='AvatarTop')
            .tarjeta.color-avatar2
              .p-4
                h4.text-center Hongos
                p.text-center Así como la levadura, muchos de los organismos que integran el reino fungi son microscópicos.

          .tarjeta-avatar
            img(src='@/assets/curso/tema10/avatar4.svg' alt='AvatarTop')
            .tarjeta.color-avatar2
              .p-4
                h4.text-center Protistas
                p.text-center Se trata de microbios unicelulares eucariotas de gran volumen. Por lo general, se desarrollan en ambientes acuáticos, que pueden ser de agua dulce o salada, o en lugares muy húmedos. Aunque algunas variedades desarrollan vidas parasitarias, por lo general, estos organismos depredan a otros microorganismos a la hora de alimentarse.

          .tarjeta-avatar
            img(src='@/assets/curso/tema10/avatar5.svg' alt='AvatarTop')
            .tarjeta.color-avatar2
              .p-4
                h4.text-center Arqueas y bacterias
                p.text-center Se trata de dos tipos de organismos procariotas y unicelulares, y son los microbios más simples. Conforman el grupo de microbios con mayor presencia en la tierra, se alimentan del hábitat en el que se encuentran y su reproducción es a partir de la división de su material genético.
    separador 

    #t_10_2.titulo-segundo.color-acento-contenido
      .h2 10.2 Microorganismos perjudiciales y beneficiosos

    p.mb-4 Los virus solo se pueden reproducir dentro de una célula huésped.  

    .row.justify-content-center.mb-4
      .col-lg-2
        .row.mb-4
          .col-lg-12
            .sub.p-2
              h4.mb-0.text-center.text-white Perjudiciales
      .col-lg-10
        p.mb-0 Existen microorganismos que resultan perjudiciales para la salud de las personas porque, al atacar células vitales, pueden causarles enfermedades que, en algunas ocasiones, pueden llevar a la muerte.
    
    .row.align-items-center.mb-4
      .col-lg-5
        figure
          img(src='@/assets/curso/tema10/1.png', alt='Texto que describa la imagen') 
      .col-lg-7
        p.mb-4 <b> <FONT COLOR="#0540B7"> Bacterias. </FONT> </b> Son microorganismos que pertenecen al reino monera, liberan toxinas y pueden sobrevivir dentro o fuera de una célula. Además, son unicelulares y carecen de núcleo. No todas las bacterias son patógenas, algunas pueden ser beneficiosas para la salud o neutrales.
        p.mb-4 <b> <FONT COLOR="#0540B7"> Virus. </FONT> </b> Estos microbios, que tienen forma espiralada o esférica, solo se pueden reproducir dentro de una célula huésped. Estos microbios, que pueden ser infecciosos, cuentan con un único tipo de ácido nucleico y son siempre patógenos. Los virus nunca pueden ser eliminados con antibióticos y solamente se pueden atacar sus síntomas.
        p.mb-4 <b> <FONT COLOR="#0540B7"> Hongos. </FONT> </b> Estos microbios pueden generar enfermedades infecciosas y se desarrollan en el exterior de los cuerpos.(Raffino, 2020) 
    .row.justify-content-center.mb-4
      .col-lg-2
        .row.mb-4
          .col-lg-12
            .sub.p-2
              h4.mb-0.text-center.text-white Beneficiosos
      .col-lg-10
        p.mb-0 Dentro de los microorganismos, también existen variedades que son beneficiosas para la vida, el medio ambiente y la salud del ser humano. A continuación, algunos ejemplos donde los microbios intervienen de forma beneficiosa:
    
    .row.align-items-center.mb-4
      .col-lg-7
        p.mb-4 <b> <FONT COLOR="#0540B7"> Industria alimenticia. </FONT> </b> Los microbios juegan un rol fundamental en la producción de ciertos productos. Por ejemplo, el yogur, el queso o la cerveza son el resultado de alimentos fermentados, gracias al accionar de los microbios. En estos casos, los microbios producen ácido láctico que facilita la conservación de los alimentos.
        p.mb-4 <b> <FONT COLOR="#0540B7"> Cuerpo humano. </FONT> </b> Existen microorganismos que participan de ciertos procesos dentro del cuerpo humano, como en la digestión, y hasta actúan en defensa de otros organismos que sí pueden afectar a la salud.
        p.mb-4 <b> <FONT COLOR="#0540B7"> Basura. </FONT> </b> Por medio de ciertos procesos biológicos, como la estabilización o descomposición, los microbios limpian los residuos. Terminan por convertir los residuos en humus o compost.
        p.mb-4 <b> <FONT COLOR="#0540B7"> Agricultura. </FONT> </b> Muchos de los microorganismos que habitan el suelo facilitan la producción agrícola. Ya sea porque actúan como plaguicidas, o bien porque ayudan al crecimiento de las plantas.
      .col-lg-5
        figure
          img(src='@/assets/curso/tema10/2.png', alt='Texto que describa la imagen') 
    separador 

    #t_10_3.titulo-segundo.color-acento-contenido
      .h2 10.3 Ejemplos de microorganismos

    p.mb-4 Los microbios como el Escherichia coli habitan en los intestinos. Algunos de los microorganismos más conocidos y estudiados que pueden ocasionar enfermedades son los siguientes:

    .row.align-items-center.mb-4
      .col-lg-6
        LineaTiempoD.color-primario
          .row(numero="1" titulo="Escherichia coli")
            .col-md-4.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema10/d1.jpg', alt='Texto que describa la imagen') 
            .col-md-6
              p Son los microbios causantes de enfermedades como diarrea hemorrágica o insuficiencia renal. Habitan en los intestinos.
          
          .row(numero="2" titulo="Salmonella")
            .col-md-4.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema10/d2.jpg', alt='Texto que describa la imagen') 
            .col-md-6
              p Estos microorganismos ocasionan diversas enfermedades. Buena parte de ellas son diarreicas. Se propaga a través de la orina y las heces.

          .row(numero="3" titulo="Streptococcus pneumoniae")
            .col-md-4.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema10/d3.jpg', alt='Texto que describa la imagen') 
            .col-md-6
              p Son los microbios que causan enfermedades como neumonía, sinusitis u otitis, así como también meningitis.

          .row(numero="4" titulo="Mycobacterium tuberculosis.")
            .col-md-4.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema10/d4.jpg', alt='Texto que describa la imagen') 
            .col-md-6
              p En general, afectan el funcionamiento del hígado y del pulmón, pero tienen la capacidad de enfermar a cualquier órgano del cuerpo. Son microbios muy resistentes al frío.
          
          .row(numero="5" titulo="Yersinia pestis")
            .col-md-4.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema10/d5.jpg', alt='Texto que describa la imagen') 
            .col-md-6
              p Este microbio, que puede ocasionar peste, habita en los roedores, aunque se transmite a través de pulgas.
          
          .row(numero="6" titulo="Bacillus cereus.")
            .col-md-4.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema10/d6.jpg', alt='Texto que describa la imagen') 
            .col-md-6
              p Este microorganismo ocasiona intoxicaciones, vómitos, diarrea y náuseas. Habita en alimentos y se caracteriza por reproducirse muy fácilmente.

          .row(numero="7" titulo="Treponema pallidum. ")    
            .col-md-4.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema10/d7.jpg', alt='Texto que describa la imagen') 
            .col-md-6
              p Este microorganismo se combate con penicilina y se caracteriza por no sobrevivir en el exterior del cuerpo. Además, este microbio ocasiona la enfermedad de transmisión sexual llamada sífilis.
      .col-lg-6
        figure
          img(src='@/assets/curso/tema10/3.png', alt='Texto que describa la imagen') 

</template>

<script>
export default {
  name: 'Tema10',
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
