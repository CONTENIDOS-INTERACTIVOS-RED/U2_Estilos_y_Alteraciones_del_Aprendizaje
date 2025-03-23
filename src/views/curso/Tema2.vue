<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(:subTitulo="'2. Título tema'")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden
  
      .bg-color-1.mb-5(data-aos="fade-up")
        .row.justify-content-center.align-items-center
          .col-lg
            .p-4
              p.mb-0(data-aos="fade-up") Las habilidades comunicativas, desarrolladas en los primeros cinco años de vida y consolidadas en la escolaridad, son esenciales para el desempeño social, académico y laboral. Según Rupérez et al. (2022), estas habilidades no solo impactan la comunicación, sino que también son fundamentales para establecer relaciones interpersonales saludables.
          .col-lg-auto
            figure
              img(src='@/assets/curso/tema2/1.png', alt='')

      h2(data-aos="fade-left").mb-4 Características del trastorno del lenguaje

      p(data-aos="fade-up").mb-4 Este trastorno implica un déficit en la comprensión, producción y uso del lenguaje, lo que representa un reto para la detección y tratamiento, considerando que su prevalencia oscila entre el 10 % y el 15 % en niños menores de seis años. La variabilidad en su etiología, manifestaciones clínicas, pronóstico y tratamiento complica su abordaje.

      .row.align-items-start.mb-5
        .col-lg-4
          figure
            img(src="@/assets/curso/tema2/2.png", alt="").mb-4.mb-lg-0
        .col-lg-8
          AcordionA(tipo="b")
            div(titulo="Habla").px-4.py-2
              p.mb-0 Producción de sonidos expresivos, incluye articulación, fluidez, voz y calidad de resonancia.

            div(titulo="Lenguaje").px-4.py-2
              p Forma, función y uso de símbolos para la comunicación verbal y no verbal.

            div(titulo="Comunicación").px-4.py-2
              p Cualquier conducta verbal o no verbal, intencional o no, que influye en el comportamiento, ideas o actitudes de otra persona.
              
      h2(data-aos="fade-left").mb-4 Componentes del lenguaje

      p(data-aos="fade-up").mb-4 Según Rupérez et al. (2022), el lenguaje se compone de:


      .bg-full-width.bg-color-7.mb-5#bg-full-listaflecha
        .px-4.px-md-5
          .row.justify-content-center.align-items-center
            .col-lg-8
              ul.lista-ul--color
                li.mb-3
                  i.fas.fa-arrow-circle-right
                  | #[strong Forma:] incluye los aspectos motores de la comunicación y las modalidades de expresión (gestos y palabras).
      
                li.mb-3
                  i.fas.fa-arrow-circle-right
                  | #[strong Contenido:] se refiere a qué comunica el individuo, incluyendo la semántica y el léxico.
      
                li.mb-4.mb-lg-0
                  i.fas.fa-arrow-circle-right
                  | #[strong Uso:] examina para qué, dónde, cuándo y con quién se comunica, abordando las funciones del lenguaje y las reglas pragmáticas.
      
            .col-lg-4
              figure
                img(src="@/assets/curso/tema2/3.svg" alt="Ilustración de profesora" style="max-width: 400px;").mx-auto.mb-4.mb-lg-0

      h2(data-aos="fade-left").mb-4 Definición del Trastorno del Lenguaje (TL) según el DSM-5

      p(data-aos="fade-up").mb-4 Este trastorno se caracteriza por dificultades persistentes en la adquisición y uso del lenguaje, debido a déficits en la comprensión o producción de palabras, frases, estructuras o narraciones. Estas dificultades afectan la comunicación hablada, escrita o en lenguaje de signos. Los niños con TL pueden presentar:

      .row.justify-content-center.align-items-stretch.mb-4#iconos-color-1
        .col-lg-4
          .bg-color-2.p-4(data-aos="fade-left").h-100
            .row.align-items-center
              .col-lg-auto
                img(src="@/assets/curso/tema1/icon-tarjeta.svg", style="max-width: 90px").mx-auto
              .col-lg
                h5.mb-2 01
                p.mb-0 Vocabulario reducido

        .col-lg-4
          .bg-color-2.p-4(data-aos="fade-left").h-100
            .row.align-items-center
              .col-lg-auto
                img(src="@/assets/curso/tema1/icon-tarjeta.svg", style="max-width: 90px").mx-auto
              .col-lg
                h5.mb-2 02
                p.mb-0 Estructuras gramaticales simplificadas o incorrectas

        .col-lg-4
          .bg-color-2.p-4(data-aos="fade-left").h-100
            .row.align-items-center
              .col-lg-auto
                img(src="@/assets/curso/tema1/icon-tarjeta.svg", style="max-width: 90px").mx-auto
              .col-lg
                h5.mb-2 03
                p.mb-0 Dificultades en la narración y discurso
      

      h2(data-aos="fade-left").mb-4 Causas de los trastornos del neurodesarrollo
      p(data-aos="fade-up").mb-4 Según Chappotin (2022), las causas pueden agruparse en cuatro categorías principales:

      div.row.justify-content-center.align-items-stretch.mb-5#b2
        div.col-lg-4.mb-4(data-aos="zoom-in-up")
          div.bg-color-white.box-shadow.px-4.py-5.h-100
            img.mx-auto.d-block.mb-4(
              src="@/assets/curso/tema2/4.svg"
              alt="Ícono trastornos expresivos"
              style="width: 90px"
            )
            h4.text-center.mb-3 Trastornos expresivos
            p.mb-0.text-center Dificultad para formular y comunicar pensamientos, ideas o mensajes.
      
        div.col-lg-4.mb-4(data-aos="zoom-in-up")
          div.bg-color-white.box-shadow.px-4.py-5.h-100
            img.mx-auto.d-block.mb-4(
              src="@/assets/curso/tema2/5.svg"
              alt="Ícono trastornos receptivos"
              style="width: 90px"
            )
            h4.text-center.mb-3 Trastornos receptivos
            p.mb-0.text-center Afectan la comprensión y entendimiento de mensajes externos.
      
        div.col-lg-4.mb-4(data-aos="zoom-in-up")
          div.bg-color-white.box-shadow.px-4.py-5.h-100
            img.mx-auto.d-block.mb-4(
              src="@/assets/curso/tema2/6.svg"
              alt="Ícono trastornos mixtos"
              style="width: 90px"
            )
            h4.text-center.mb-3 Trastornos mixtos
            p.mb-0.text-center Combinan dificultades tanto en la expresión como en la comprensión del lenguaje.


      h2(data-aos="fade-left").mb-4 Evaluación y diagnóstico

      .row.mb-5
        .col-lg-8
          .bg-color-7.px-4.py-5(data-aos="fade-left").mb-4
            p.mb-0 Es fundamental evaluar tanto las habilidades expresivas como las receptivas para orientar correctamente el diagnóstico y realizar las exploraciones necesarias. Además, se deben descartar alteraciones sensoriales, cognitivas o motoras que puedan estar afectando la comunicación, como la hipoacusia o el retraso global del desarrollo.
          
          p(data-aos="fade-left") #[b a. Tipos de trastornos del lenguaje, habla y comunicación]

          p(data-aos="fade-left") Los trastornos del lenguaje y la comunicación se pueden clasificar según sus características específicas. Entre ellos se encuentran:

        .col-lg-4.d-none.d-sm-block
          figure
            img(src="@/assets/curso/tema2/7.png", data-aos="zoom-in").mb-4.mb-lg-0
      

      .bg-full-width.bg-fondo-slider
        .p-4.p-md-5
          SlyderA(tipo="b").bg-white
            .row.align-items-center.p-4.p-md-5
              .col-lg-5
                figure
                  img(src="@/assets/curso/tema2/slide-1.png" alt="Niño con tablet y terapeuta")
              .col-lg-7
                h5 Trastornos en los que el niño deja de hablar
                ul.lista-ul--color.color-dark.mb-4
                  li.mb-3
                    i.fas.fa-arrow-circle-right
                    | #[strong Afasia:] se produce por una lesión cerebral y afecta la comunicación. Ejemplo: niño que tras un traumatismo craneoencefálico pierde la capacidad de hablar.
                  li.mb-3
                    i.fas.fa-arrow-circle-right
                    | #[strong Mutismo selectivo:] relacionado con la ansiedad; el niño se niega a hablar en ciertos contextos. Ejemplo: niño que habla en casa, pero permanece en silencio en la escuela.
                  li.mb-0
                    i.fas.fa-arrow-circle-right
                    | #[strong Autismo regresivo:] pérdida de habilidades lingüísticas y sociales previamente adquiridas. Ejemplo: niño que balbuceaba y decía algunas palabras, pero de repente deja de hacerlo y se aísla.

            .row.align-items-center.p-4.p-md-5
              .col-lg-5
                figure
                  img(src="@/assets/curso/tema2/slide-2.png" alt="Niña pensativa")
              .col-lg-7
                h5 Trastornos en los que el niño habla mal o no habla
                ul.lista-ul--color.color-dark.mb-4
                  li.mb-3
                    i.fas.fa-arrow-circle-right
                    | #[strong Tartamudez:] problemas de fluidez y pronunciación. Ejemplo: niño que repite sílabas o palabras ("ca-ca-casa") o se bloquea al hablar.
                  li.mb-3
                    i.fas.fa-arrow-circle-right
                    | #[strong Disartria:] dificultad para articular palabras debido a problemas neuromusculares. Ejemplo: niño con parálisis cerebral que tiene dificultades para controlar los músculos de la boca y la lengua.
                  li.mb-3
                    i.fas.fa-arrow-circle-right
                    | #[strong Dislalia:] problemas en la pronunciación de ciertos sonidos consonantes. Ejemplo: niño que dice "tetota" en vez de "pelota".
                  li.mb-0
                    i.fas.fa-arrow-circle-right
                    | #[strong Trastornos de la prosodia:] Afectan la entonación, el ritmo y la expresión emocional en el habla. Ejemplo: niño con habla monótona sin variaciones de tono.

            .row.align-items-center.p-4.p-md-5
              .col-lg-5
                figure
                  img(src="@/assets/curso/tema2/slide-3.png" alt="Niño con terapeuta")
              .col-lg-7
                h5 Trastorno específico del lenguaje (disfasia)
                ul.lista-ul--color.color-dark.mb-4
                  li.mb-3
                    i.fas.fa-arrow-circle-right
                    | Afecta la expresión y recepción del lenguaje sin pérdida auditiva ni discapacidad intelectual.
                  li.mb-0
                    i.fas.fa-arrow-circle-right
                    | Características: vocabulario reducido, errores en la pronunciación, dificultades en la construcción de frases.

            .row.align-items-center.p-4.p-md-5
              .col-lg-5
                figure
                  img(src="@/assets/curso/tema2/slide-4.png" alt="Niña con terapeuta")
              .col-lg-7
                h5 Retraso en el desarrollo del lenguaje oral
                ul.lista-ul--color.color-dark.mb-4
                  li.mb-3
                    i.fas.fa-arrow-circle-right
                    | Comprensión adecuada, pero dificultades para hablar.
                  li.mb-0
                    i.fas.fa-arrow-circle-right
                    | Puede ser leve o severo.

      .bg-full-width.bg-color-8.mb-5
        .px-4.px-md-5.py-4
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema2/8.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 La detección temprana y el tratamiento adecuado son clave para mejorar la comunicación de los niños con estos trastornos. Si se sospecha de una alteración en el lenguaje, habla o comunicación, es fundamental acudir a un profesional de la salud especializado.
      

      .bg-full-width.PurpleContainer.pt-5
        .px-4.px-md-5
          p #[b b. Tratamientos y estrategias en el aula]
          p(data-aos="fade-up").mb-4 El tratamiento de los problemas del lenguaje es responsabilidad de los fonoaudiólogos, quienes emplean diversas técnicas de intervención. Según Moreno (2013), anteriormente se usaban métodos como la repetición de palabras y ejercicios gramaticales, pero hoy se favorecen estrategias más naturales, como situaciones cotidianas que fomenten la comunicación y la socialización. Las intervención y estrategias efectivas son: 

          .row.align-items-start#aco2
            .col-lg-8
              AcordionA(tipo="b")
                .div(titulo="Interacción entre niños con y sin dificultades lingüísticas")
                  ul.lista-ul--color.color-dark.mb-4
                    li.mb-3
                      i.fas.fa-arrow-circle-right
                      | Facilita la mejora del lenguaje mediante la socialización.
                    li.mb-0
                      i.fas.fa-arrow-circle-right
                      | Beneficia tanto a los niños con trastornos como a sus compañeros.

                .div(titulo="Estrategias en el aula")
                  p.mb-4 Las estrategias educativas pueden facilitar el aprendizaje y la adaptación de los niños con dificultades en el desarrollo intelectual. A continuación, se presentan algunas estrategias con su descripción y ejemplos:
                  ul.lista-ul--color.color-dark.mb-4
                    li.mb-3
                      i.fas.fa-arrow-circle-right
                      | #[strong Uso de esquemas visuales:] Facilita la comprensión y organización de ideas. Un ejemplo es el uso de mapas mentales y diagramas.
                    li.mb-3
                      i.fas.fa-arrow-circle-right
                      | #[strong Adaptación del lenguaje:] Implica utilizar frases cortas y claras para mejorar la comprensión. Por ejemplo, decir "Escribe tu nombre en la hoja" en lugar de "Pon tu identificación en el documento".
                    li.mb-3
                      i.fas.fa-arrow-circle-right
                      | #[strong Ubicación estratégica en el aula:] Consiste en situar a los niños cerca del docente para proporcionar mayor apoyo. Un ejemplo es asignar un asiento en la primera fila a un niño con dificultades.
                    li.mb-0
                      i.fas.fa-arrow-circle-right
                      | #[strong Mantenimiento de rutinas estructuradas:] Ayuda a reducir la ansiedad y mejorar la comprensión mediante un horario diario consistente.

            .col-lg-4
              figure
                img(src="@/assets/curso/tema2/9.png", alt="Imagen ilustrativa de estrategias educativas").mb-4.mb-lg-0
          
      .bg-full-width.SplitContainer2.mb-5.pt-5
        .row.justify-content-center
          .col-lg-9
            .bg-color-white.shadow-soft.py-4.px-lg-5(data-aos="fade-up")
              .row.justify-content-around.align-items-center
                .col-md-auto
                  img(src="@/assets/template/bg-icono-link.svg", style="width: 90px;")
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-3.mb-sm-0
                      h3.mb-1 Dificultades del lenguaje en los trastornos del desarrollo
                      p.mb-0 Para profundizar en estos trastornos y estrategias, se recomienda leer el capítulo  IV.
                    .col-sm-auto
                      a.boton.color-acento-botones.texto-blanco(href="https://elibro.net/es/lc/tecnologicadeloriente/login_usuario/?next=/es/ereader/tecnologicadeloriente/117780/?page=159" target="_blank")
                        span Ir al sitio
                        i.fas.fa-arrow-right
      



      .bg-full-width.border-top.color-primario
        .p-4.p-md-5
          h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
          .row.material-complementario
            .col-12.col-md-6.col-lg-7
              p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.
  
              p.d-flex.my-4
                img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
                a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/274611" target="_blank" rel="noopener noreferrer") De Castro Emilio Cerdá, F. J. A. L. M. (s/f). Las energías renovables en el ámbito internacional. Revistasice.com. 
  
              p.d-flex.my-4
                img.me-3(src='@/assets/template/book.svg' :style="{'max-width':'16px'}")
                span De Janeiro, R. (1992). La declaración del Río sobre el Medio Ambiente y el Desarrollo. Río de Janeiro República Federativa del Brasil., aprobada en Estocolmo el, 16.
  
              p.d-flex.my-4
                img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
                a(href="https://youtu.be/QKLjwCMyv3M?si=uAWhO9tnyghljaJg" target="_blank" rel="noopener noreferrer") Innovación y sostenibilidad.
  
            .col-12.col-md-6.col-lg-3.offset-lg-1
              figure
                img(src='@/assets/componentes/material-complementario.svg', alt='')
  
  </template>

<script>
export default {
  name: 'Tema2',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.PurpleContainer
  background: linear-gradient(180deg, #FFFFFF 0%, #FFFFFF 60%, #EAE9EE 100%)

.SplitContainer2
  background: rgb(85,122,250)
  background: linear-gradient(0deg, rgba(255,255,255,1) 0%, rgba(255,255,255,1) 50%, rgba(235,233,240, 1) 50%)
</style>
