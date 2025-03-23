<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. Trastornos del desarrollo neurológico'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    p.mb-5(data-aos="fade-right") En la primera unidad se estableció qué son los trastornos en términos generales. Ahora se abordarán específicamente los trastornos del neurodesarrollo y motrices, como:

    .row.justify-content-center.align-items-stretch.mb-4#bloque-tarjetas
      .col-lg-4.mb-3
        .bg-color-2.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema1/icon-tarjeta.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Trastornos del lenguaje y la comunicación

      .col-lg-4.mb-3
        .bg-color-2.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema1/icon-tarjeta.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 TDAH

      .col-lg-4.mb-3
        .bg-color-2.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema1/icon-tarjeta.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Trastorno del desarrollo intelectual

      .col-lg-4.mb-3
        .bg-color-2.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema1/icon-tarjeta.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Trastorno del espectro del autismo (TEA)

      .col-lg-8.mb-3
        .bg-color-2.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema1/icon-tarjeta.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 
                | #[strong Trastornos del desarrollo sensorial y motórico:]
                br
                | Discapacidad visual y ceguera, discapacidad auditiva y sordera, discapacidad motórica o motriz.


    h2(data-aos="fade-left").mb-4 Causas y tratamiento

    .row.mb-5
      .col-lg-8
        .bg-color-3.p-4.mb-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema1/1.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Según el Manual Diagnóstico y Estadístico de los Trastornos Mentales DSM-5, los trastornos del desarrollo neurológico comprenden un grupo de condiciones que afectan el desarrollo del sistema nervioso y, en consecuencia, las habilidades cognitivas, motoras, del lenguaje y del comportamiento. Estos pueden manifestarse en la infancia y persistir a lo largo de la vida, impactando el aprendizaje y la socialización.
    
        p(data-aos="fade-left") Para Sulkes (2024), el término "trastornos del desarrollo" debe ser reemplazado por "trastornos del neurodesarrollo", ya que este es más preciso y hace referencia a condiciones con base neurológica que afectan la adquisición, retención o aplicación de habilidades específicas. Estos trastornos pueden implicar dificultades en:
    
      .col-lg-4
        figure
          img(src="@/assets/curso/tema1/2.png", data-aos="zoom-in")


    .row.justify-content-center.align-items-stretch.mb-5
      .col
        .bg-color-1.px-3.py-4.h-100
          h4.mb-2 01
          p.mb-0 Atención

      .col
        .bg-color-1.px-3.py-4.h-100
          h4.mb-2 02
          p.mb-0 Memoria

      .col
        .bg-color-1.px-3.py-4.h-100
          h4.mb-2 03
          p.mb-0 Percepción

      .col
        .bg-color-1.px-3.py-4.h-100
          h4.mb-2 04
          p.mb-0 Lenguaje

      .col
        .bg-color-1.px-3.py-4.h-100
          h4.mb-2 05
          p.mb-0 Resolución de problemas

      .col
        .bg-color-1.px-3.py-4.h-100
          h4.mb-2 06
          p.mb-0 Interacción social
    

    .bg-full-width.bg-color-9
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema1/3.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0.text-white Chappotin (2022) señala que estos trastornos son un conjunto heterogéneo de condiciones con retrasos o alteraciones en la adquisición de habilidades motoras, sociales, lingüísticas y cognitivas. Su severidad varía: algunos individuos pueden llevar una vida independiente con apoyos mínimos, mientras que otros requieren asistencia constante para funciones básicas como caminar o alimentarse.
    

    .bg-full-width.PurpleContainer.pt-5
      .px-4.px-md-5
        h2(data-aos="fade-left").mb-4 Causas de los trastornos del neurodesarrollo
        p Según Chappotin (2022), las causas pueden agruparse en cuatro categorías principales:

        div.row.justify-content-center.align-items-stretch#bloque-tarjetas-botones
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(
                src="@/assets/curso/tema1/4.svg"
                alt="Ícono causas congénitas"
                style="width: 90px"
              )
              h4.text-center.mb-3 Congénitas
              p.mb-0.text-center Mutaciones genéticas, trastornos metabólicos.

          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(
                src="@/assets/curso/tema1/5.svg"
                alt="Ícono causas prenatales"
                style="width: 90px"
              )
              h4.text-center.mb-3 Prenatales
              p.mb-0.text-center Deficiencias nutricionales, infecciones maternas.

          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(
                src="@/assets/curso/tema1/6.svg"
                alt="Ícono causas perinatales"
                style="width: 90px"
              )
              h4.text-center.mb-3 Perinatales
              p.mb-0.text-center Complicaciones en el parto, hipoxia.

          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(
                src="@/assets/curso/tema1/7.svg"
                alt="Ícono causas postnatales"
                style="width: 90px"
              )
              h4.text-center.mb-3 Postnatales
              p.mb-0.text-center Traumatismos craneoencefálicos, infecciones como meningitis, exposición a tóxicos.
    

    .bg-full-width.SplitContainer2.mb-5.pt-5
      .row.justify-content-center
        .col-lg-8
          .bg-color-white.shadow-soft.py-4.px-lg-5(data-aos="fade-up")
            .row.justify-content-around.align-items-center
              .col-md-auto
                img(src="@/assets/template/video.svg", style="width: 90px;")
              .col
                .row.justify-content-between.align-items-center
                  .col.mb-3.mb-sm-0
                    h3.mb-1 Trastornos del neurodesarrollo
                    p.mb-0 Para conocer más sobre estos trastornos, se recomienda ver el siguiente video:
                  .col-sm-auto
                    a.boton.color-primario(href="https://www.youtube.com/watch?v=vyZnvgvgm5c" target="_blank")
                      span Ver video
                      i.fas.fa-arrow-right
    




    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar y enriquecer su aprendizaje en los temas tratados en esta unidad.
            
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/ereader/tecnologicadeloriente/117780?page=159" target="_blank" rel="noopener noreferrer") Aguilar-Mediavilla, E. (Il.) & Igualada, A. (Il.). (2019). Dificultades del lenguaje en los trastornos del desarrollo. Vol. I: pérdida sensorial y daño neurológico: ( ed.). Editorial UOC.
            
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/ereader/tecnologicadeloriente/227877?page=111" target="_blank" rel="noopener noreferrer") Rodríguez-Izquierdo, R. M. (2022). Ciudadanía activa y discapacidad intelectual: (1 ed.). Ediciones Octaedro, S.L.
          
          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({}),

  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.PurpleContainer
  background-color: rgb(235,233,240)

.SplitContainer2
  background: rgb(85,122,250)
  background: linear-gradient(0deg, rgba(255,255,255,1) 0%, rgba(255,255,255,1) 50%, rgba(235,233,240, 1) 50%)
</style>
