<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(:subTitulo="'3. Trastorno del Espectro Autista.'")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

      .bg-full-width.bg-color-5
        .px-4.px-md-5.py-3.py-md-4
          p.mb-0 Después de abordar los trastornos del lenguaje, es momento de profundizar en el Trastorno del Espectro Autista (TEA). Para comprender mejor esta condición, analicemos el siguiente caso:

      .bg-full-width.bg-color-6.mb-5
        .px-4.px-md-5.pt-3.pt-md-4
          .row.justify-content-center
            .col-lg-8
              p #[strong Caso de Manuel]
              p Manuel, un niño de 4 años, fue diagnosticado con TEA. Desde pequeño, sus padres notaron que evitaba el contacto visual y no respondía a su nombre. En el jardín de infancia, sus maestros observaron que tenía dificultades para seguir instrucciones y participar en actividades grupales. Su lenguaje verbal era limitado, por lo que utilizaba señas o guiaba a los adultos hacia lo que quería.

              p #[strong Para ayudarlo, se implementaron estrategias como esquemas visuales, frases cortas y un entorno estructurado. También recibió terapia del habla y del lenguaje, logrando mejoras en su capacidad de interacción y expresión. Aunque sigue enfrentando desafíos, el apoyo adecuado ha sido clave para su desarrollo.]
            .col-lg-4
              figure
                img(src="@/assets/curso/tema3/1.svg", alt="Imagen ilustrativa de estrategias educativas").mb-4.mb-lg-0
              
  
      p(data-aos="fade-up").mb-5 El TEA es una condición del neurodesarrollo que afecta la comunicación e interacción social, acompañada de comportamientos repetitivos e intereses restringidos (Del Mar y Soto, 2023).

      .bg-full-width.bg-fondo-slider.mb-5
        .p-4.p-md-5
          figure
            .video
              iframe(width="560" height="315" src="https://www.youtube.com/embed/9cqLwqWDCzs?si=F1b2M6SlLRnGqFf9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)


      h2(data-aos="fade-up").mb-4 a) Tipos o grados del TEA

      p(data-aos="fade-up").mb-5 El TEA no es una enfermedad, sino una condición que afecta a 10-15 personas por cada 10,000 habitantes, siendo más común en hombres (proporción 4:1). Anteriormente, se clasificaba según autores como Asperger y Kanner, pero hoy el DSM-5 lo categoriza en tres niveles de apoyo:

      .bg-full-width.bg-color-info.mb-5
        .px-4.px-md-5.pt-4.pt-md-5
          .row.justify-content-center.align-items-center
            .col-lg-10
              ImagenInfografica.color-secundario
                template(v-slot:imagen)
                  figure
                    img(src='@/assets/curso/tema3/info1.png', alt='', style="max-width: 845px;").mx-auto
      
                .bg-color-white.box-shadow.p-3(x="46%" y="23%" numero="+")
                  h5 Nivel 2
                  p Problemas evidentes en comunicación y adaptación a cambios. Rutinas rígidas e intereses restringidos. Necesidad de apoyo moderado.
                  
      
                .bg-color-white.box-shadow.p-3(x="46%" y="59%" numero="+")
                  h5 Nivel 1
                  p Dificultades leves en comunicación social, problemas para interpretar señales no verbales. Uso de lenguaje estructurado. Necesidad de poco apoyo.
      
                .bg-color-white.box-shadow.p-3(x="59%" y="18%" numero="+")
                  h5 Nivel 3
                  p Dificultades severas en comunicación e interacción. Uso limitado del lenguaje. Alta dependencia. Necesidad de apoyo intenso.

      p(data-aos="fade-up").mb-5 El nivel asignado en el diagnóstico puede cambiar con el tiempo a medida que la persona desarrolla habilidades.

      .bg-full-width.bg-fondo-2
        .p-4.p-md-5
          h2(data-aos="fade-up").mb-4 b) Tratamiento y estrategias en el aula

          p(data-aos="fade-up").mb-5 El TEA es un trastorno de por vida sin cura, pero con intervención adecuada, las personas pueden mejorar sus habilidades sociales, de comunicación y autonomía (Martos et al., 2020).


          div.row.justify-content-center.align-items-stretch
            div.col-lg-3.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(
                  src="@/assets/curso/tema3/2.svg"
                      alt="Ícono Análisis Conductual Aplicado"
                  style="width: 90px"
                )
                h4.text-center.mb-3 Análisis Conductual Aplicado (ABA)
                p.mb-0.text-center Mejora comportamientos mediante refuerzos positivos.
          
            div.col-lg-3.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(
                  src="@/assets/curso/tema3/3.svg"
                      alt="Ícono Terapia ocupacional"
                      style="width: 90px"
                    )
                h4.text-center.mb-3 Terapia ocupacional
                p.mb-0.text-center Fortalece habilidades motoras y sensoriales.

            div.col-lg-3.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(
                  src="@/assets/curso/tema3/4.svg"
                  alt="Ícono Terapia del lenguaje"
                  style="width: 90px"
                )
                h4.text-center.mb-3 Terapia del lenguaje
                p.mb-0.text-center Desarrolla la comunicación verbal y no verbal.

            div.col-lg-3.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(
                  src="@/assets/curso/tema3/5.svg"
                  alt="Ícono Intervenciones educativas"
                  style="width: 90px"
                )
                h4.text-center.mb-3 Intervenciones educativas individualizadas (PiAR)
                p.mb-0.text-center Ajustes razonables en el aula para garantizar inclusión.


      .bg-full-width.bg-color-8.mb-5
        .px-4.px-md-5.py-4
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema3/6.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 El #[strong PIAR (Plan Individual de Ajustes Razonables)], regulado por el Decreto 1421 de 2017, busca garantizar que los estudiantes con TEA reciban un apoyo adecuado. Este plan adapta estrategias a las necesidades del estudiante para su desarrollo académico y social.
      

      h2(data-aos="fade-up").mb-4 c) Estrategias para el aula según el MEN (2006)

      p(data-aos="fade-up").mb-5 El Ministerio de Educación Nacional (MEN) recomienda:

      .bg-full-width.bg-color-7#bt2
        .px-4.px-md-5
          .row.justify-content-center.align-items-center
            .col-lg-4
              figure
                img(src="@/assets/curso/tema3/7.svg" alt="Ilustración de un profesor y estudiantes en el aula" style="max-width: 400px;").mx-auto.mb-4.mb-lg-0
            .col-lg-8
              ul.lista-ul--color
                li.mb-3
                  i.fas.fa-arrow-circle-right
                  | #[strong Rutinas estructuradas:] reducen la ansiedad mediante horarios visuales y organización del espacio.

                li.mb-3
                  i.fas.fa-arrow-circle-right
                  | #[strong Uso de apoyos visuales:] pictogramas y diagramas facilitan la comprensión de instrucciones.

                li.mb-3
                  i.fas.fa-arrow-circle-right
                  | #[strong Instrucciones directas y sencillas:] dividir tareas en pasos pequeños.

                li.mb-3
                  i.fas.fa-arrow-circle-right
                  | #[strong Apoyo en la comunicación:] uso de sistemas aumentativos o alternativos.
                  br
                  | #[strong Regulación sensorial:] minimizar ruidos fuertes y luces brillantes.

                li.mb-0
                  i.fas.fa-arrow-circle-right
                  | #[strong Interacción guiada:] juegos estructurados para fomentar la socialización.

      .bg-full-width.PurpleContainer.pt-5
        .px-4.px-md-5
          p.mb-0.text-center Estas estrategias favorecen la inclusión de los estudiantes con TEA y potencian su desarrollo en el aula.
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
                      p.mb-0 Para conocer más sobre estos trastornos, se recomienda ver el siguiente video.
                    .col-sm-auto
                      a.boton.color-acento-botones.texto-blanco(href="URL del enlace" target="_blank")
                        span Ver video
                        i.fas.fa-arrow-right


      h2(data-aos="fade-up").mb-4 Trastorno por Déficit de Atención con Hiperactividad/Impulsividad (TDAH)

      p(data-aos="fade-up").mb-4 El Trastorno por Déficit de Atención con Hiperactividad/Impulsividad (TDAH) es una condición neurobiológica caracterizada por dificultades en la regulación de la atención, el control de impulsos y la hiperactividad. Se manifiesta en diferentes grados de intensidad y puede afectar el desempeño académico, social y laboral de quienes lo presentan.


      .bg-full-width.bg-color-5.mb-lg-5
        .px-4.p-md-5
          .row.justify-content-center.align-items-center
            .col-lg-5
              figure(data-aos="zoom-in")
                img(src='@/assets/curso/tema3/8.png', alt='')
      
            .col-lg-7
              h2.mb-4(data-aos="flip-up") Trastorno por Déficit de Atención con Hiperactividad/Impulsividad (TDAH)
              p.mb-4(data-aos="fade-right") Se invita a profundizar en el conocimiento sobre el Trastorno por Déficit de Atención con Hiperactividad/Impulsividad (TDAH) , explorando su evolución histórica, características diagnósticas y estrategias de tratamiento. A través de esta revisión, se comprenderán los síntomas principales del TDAH según el DSM-5, su impacto en la vida cotidiana y las intervenciones más efectivas en el ámbito educativo y clínico.
      
              a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_1.pdf')" target="_blank")(data-aos="flip-up")
                .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                  img(src="@/assets/template/icono-pdf.svg")
                .anexo__texto
                  p <strong>Anexo. </strong> Trastorno por Déficit de Atención con Hiperactividad/Impulsividad (TDAH)
      
      
      h2(data-aos="fade-up").mb-4 Trastorno del desarrollo Intelectual (TDI).

      .bg-color-1.mb-5(data-aos="fade-up")
        .row.justify-content-center.align-items-center
          .col-lg
            .p-4
              p.mb-0(data-aos="fade-up") Para comprender este trastorno, es necesario partir de la definición de inteligencia propuesta por Luque Rojas y Luque Parra (2016). Según estos autores, la inteligencia es una capacidad multifacética que abarca aspectos cognitivos, sociales y culturales, manifestándose en la capacidad de aprender, razonar, resolver problemas y adaptarse al entorno. A pesar de la existencia de diversas teorías sobre la inteligencia, todas coinciden en su importancia para el desarrollo humano.
          .col-lg-auto
            figure
              img(src='@/assets/curso/tema3/9.png', alt='')

      h3(data-aos="fade-up").mb-4 Evolución del concepto de TDI

      p(data-aos="fade-up").mb-5 El término retraso mental o discapacidad intelectual ha evolucionado con el tiempo, reflejando una mejor comprensión de esta condición. Originalmente, se consideraba una variante de la demencia, pero en el siglo XIX se empezó a diferenciar como una condición independiente. Hasta finales del siglo XVIII y principios del XIX, las personas con discapacidad intelectual eran vistas como individuos con alteraciones mentales de origen orgánico o innato.

      .row.mb-5
        .col-lg-4
          figure
            img(src="@/assets/curso/tema3/10.png", data-aos="zoom-in")
        .col-lg-8
          p(data-aos="fade-left").mb-4 Sin embargo, el siglo XIX marcó el inicio del reconocimiento de esta discapacidad como una condición distinta, lo que llevó al desarrollo de estudios e intervenciones específicas. Uno de los hitos en este proceso fue el trabajo de Jean Itard con el niño salvaje de Aveyron, que demostró la posibilidad de educar y socializar a personas con discapacidad intelectual. Con el tiempo, estas ideas influyeron en la manera en que la educación y la atención a estas personas se estructuraron.

          p(data-aos="fade-up").mb-4 Con la publicación del DSM-5 (APA, 2013), el término retraso mental fue reemplazado por Trastorno del Desarrollo Intelectual (TDI). La clasificación se reorganizó en cinco categorías:
      
          .bg-color-2.px-5(data-aos="fade-left")
            .row.justify-content-center.align-items-center
              .col-lg-6
                ul.lista-ul--color.color-dark
                  li.mb-0
                    i.fas.fa-arrow-circle-right
                    | TDI Leve
                  li.mb-0
                    i.fas.fa-arrow-circle-right
                    | TDI Moderado
                  li.mb-0
                    i.fas.fa-arrow-circle-right
                    | TDI Severo
                  li.mb-0
                    i.fas.fa-arrow-circle-right
                    | TDI Profundo
                  li.mb-0
                    i.fas.fa-arrow-circle-right
                    | Retraso Global del Desarrollo
              .col-lg-6
                figure
                  img(src="@/assets/curso/tema3/11.svg", alt="")
      
      p(data-aos="fade-up").mb-5 Este cambio terminológico buscó evitar expresiones ofensivas, de manera similar a cómo retraso mental sustituyó términos como morón, imbécil o idiota. Además, los TDI se agrupan dentro de los Trastornos del Neurodesarrollo en el DSM-5.

      h3(data-aos="fade-up").mb-4 Características y síntomas

      p(data-aos="fade-up").mb-5 El TDI se manifiesta cuando hay un retraso en la adquisición de habilidades durante una etapa temprana del desarrollo, como el dominio del lenguaje. Se caracteriza por limitaciones en las funciones cognitivas, el aprendizaje y las habilidades adaptativas. Los niños con este trastorno presentan dificultades en áreas como el razonamiento, la planificación y el pensamiento abstracto. La clasificación de los síntomas:

      div.row.justify-content-center.align-items-stretch.mb-5
        div.col-lg-4.mb-4(data-aos="zoom-in-up")
          div.bg-color-white.box-shadow.px-4.py-5.h-100
            img.mx-auto.d-block.mb-4(
              src="@/assets/curso/tema3/12.svg"
              alt=""
              style="width: 90px"
            )
            h4.text-center.mb-3 Conceptuales
            p.mb-0.text-center Dificultades académicas, retraso escolar, problemas de memoria, resolución de problemas y razonamiento.
      
        div.col-lg-4.mb-4(data-aos="zoom-in-up")
          div.bg-color-white.box-shadow.px-4.py-5.h-100
            img.mx-auto.d-block.mb-4(
              src="@/assets/curso/tema3/13.svg"
              alt=""
              style="width: 90px"
            )
            h4.text-center.mb-3 Sociales
            p.mb-0.text-center Problemas en la comunicación, dificultad para adquirir información nueva, falta de inhibiciones sociales, incapacidad para interpretar señales y dificultades en la formación de amistades.
      
        div.col-lg-4.mb-4(data-aos="zoom-in-up")
          div.bg-color-white.box-shadow.px-4.py-5.h-100
            img.mx-auto.d-block.mb-4(
              src="@/assets/curso/tema3/14.svg"
              alt=""
              style="width: 90px"
            )
            h4.text-center.mb-3 Prácticas
            p.mb-0.text-center Retraso en habilidades motoras (gatear, caminar, hablar), problemas con tareas diarias como el cuidado personal y el manejo del dinero, y dificultades en la organización de tareas.
      

      .bg-full-width.bg-color-8.mb-5
        .px-4.px-md-5.py-4
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema3/15.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 A pesar de su impacto en la vida diaria, el estudio del TDI ha sido poco priorizado en ámbitos jurídicos, sociales y de salud pública, lo que ha generado una escasez de pruebas científicas sobre el trastorno. Además, existe una falta de competencias específicas y profesionalización en el cuidado de estas personas, lo que resalta la necesidad de intervenciones en prevención, rehabilitación, integración e inclusión laboral.


      h3(data-aos="fade-up").mb-4 Causas del TDI

      p(data-aos="fade-up").mb-4 De acuerdo con Saunders (2024), las causas del TDI incluyen:


      .bg-full-width.bg-color-7.mb-5
        .px-4.px-md-5.pt-4
          .row.justify-content-center.align-items-center
            .col-lg-8
              ul.lista-ul--color
                li.mb-1
                  i.fas.fa-arrow-circle-right
                  | Factores genéticos.
                li.mb-1
                  i.fas.fa-arrow-circle-right
                  | Problemas en el crecimiento cerebral durante el embarazo.
                li.mb-1
                  i.fas.fa-arrow-circle-right
                  | Consumo de alcohol o drogas por parte de la madre.
                li.mb-1
                  i.fas.fa-arrow-circle-right
                  | Complicaciones durante el parto.
                li.mb-1
                  i.fas.fa-arrow-circle-right
                  | Lesiones cerebrales graves.
                li.mb-1
                  i.fas.fa-arrow-circle-right
                  | Enfermedades específicas.
                li.mb-1
                  i.fas.fa-arrow-circle-right
                  | Convulsiones.
                li.mb-1
                  i.fas.fa-arrow-circle-right
                  | Falta de cuidados en la infancia.
            .col-lg-4
              figure
                img(src="@/assets/curso/tema3/17.svg" alt="" style="max-width: 400px;").mx-auto.mb-4.mb-lg-0


      p(data-aos="fade-up").mb-5 Para el diagnóstico, el niño debe obtener una puntuación inferior a 70 en una prueba de coeficiente intelectual (CI), lo que indica dificultades en el pensamiento y aprendizaje. Además, debe presentar limitaciones en al menos dos áreas clave:

      .row.justify-content-center.align-items-stretch.mb-4
        .col-lg-4
          .bg-color-2.p-4(data-aos="fade-left").h-100
            .row.align-items-center
              .col-lg-auto
                img(src="@/assets/curso/tema3/18.svg", style="max-width: 90px").mx-auto
              .col-lg
                h5.mb-1 Comunicación
                p.mb-0 Dificultad para dar y recibir información.
      
        .col-lg-4
          .bg-color-2.p-4(data-aos="fade-left").h-100
            .row.align-items-center
              .col-lg-auto
                img(src="@/assets/curso/tema3/18.svg", style="max-width: 90px").mx-auto
              .col-lg
                h5.mb-1 Habilidades interpersonales
                p.mb-0 Problemas para interactuar con los demás.
        
        .col-lg-4
          .bg-color-2.p-4(data-aos="fade-left").h-100
            .row.align-items-center
              .col-lg-auto
                img(src="@/assets/curso/tema3/18.svg", style="max-width: 90px").mx-auto
              .col-lg
                h5.mb-1 Habilidades de la vida diaria
                p.mb-0 Dificultades con actividades básicas como vestirse y usar el baño.

      p(data-aos="fade-up").mb-5 El TDI generalmente se manifiesta antes del nacimiento, aunque también puede ser consecuencia de lesiones o exposición a sustancias tóxicas antes de los 18 años. La identificación y el apoyo temprano son fundamentales para mejorar la calidad de vida de los niños con este trastorno.

      h2(data-aos="fade-up").mb-4 Clasificación del TDI

      p(data-aos="fade-up").mb-5 Según Pérez (2013), la clasificación del TDI se basa en el coeficiente intelectual (CI) y en las habilidades que presenta cada individuo.

      TabsC.color-acento-contenido.mb-5
        .tabs-content.border.px-4.p-md-5.py-3(titulo="Leve CI: 50-70" :icon="require('@/assets/bullets/icon-tab-c-1.svg')")
          .row
            .col-md-6.col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
              h4 Leve CI: 50-70
              p Representa el 85% de los casos. Pueden completar educación primaria con adaptaciones y llevar una vida independiente con apoyo.
            .col-md-6.col-lg-5.col-xl-4.order-1
              figure(data-aos="zoom-in")
                img(src='@/assets/curso/tema3/tab-1.png', alt='Imagen de estudiantes con profesor en aula')

        .tabs-content.border.px-4.p-md-5.py-3(titulo="Moderado CI: 35-50" :icon="require('@/assets/bullets/icon-tab-c-1.svg')")
          .row
            .col-md-6.col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
              h4 Moderado CI: 35-50
              p Constituye el 10% de los casos. Pueden aprender habilidades comunicativas y desarrollar autonomía en ciertas tareas diarias. En la adultez, pueden realizar trabajos no cualificados bajo supervisión.
            .col-md-6.col-lg-5.col-xl-4.order-1
              figure(data-aos="zoom-in")
                img(src='@/assets/curso/tema3/tab-2.png', alt='Imagen de estudiante trabajando con profesor')

        .tabs-content.border.px-4.p-md-5.py-3(titulo="Grave CI: 20-35" :icon="require('@/assets/bullets/icon-tab-c-1.svg')")
          .row
            .col-md-6.col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
              h4 Grave CI: 20-35
              p Representa entre el 3% y 4% de los casos. Requieren supervisión constante y pueden aprender habilidades básicas.
            .col-md-6.col-lg-5.col-xl-4.order-1
              figure(data-aos="zoom-in")
                img(src='@/assets/curso/tema3/tab-3.png', alt='Imagen de estudiante con tutor')

        .tabs-content.border.px-4.p-md-5.py-3(titulo="Profundo CI: Menos de 20" :icon="require('@/assets/bullets/icon-tab-c-1.svg')")
          .row
            .col-md-6.col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
              h4 Profundo CI: Menos de 20
              p Representa entre el 1% y 2% de los casos. Se asocia a problemas neurológicos y requiere un entorno altamente estructurado.
            .col-md-6.col-lg-5.col-xl-4.order-1
              figure(data-aos="zoom-in")
                img(src='@/assets/curso/tema3/tab-4.png', alt='Imagen de estudiante con educador')

      


      h3(data-aos="fade-up").mb-4 Tratamiento y estrategias en el aula
      p(data-aos="fade-up").mb-5 El TDI no tiene cura, pero la educación especial y los programas de rehabilitación pueden mejorar la calidad de vida de los afectados. Según Sanders (2024), los programas de intervención pueden ayudar a desarrollar habilidades esenciales como vestirse, manejar dinero y comunicarse. El objetivo es lograr la mayor autonomía posible para cada persona. Las principales intervenciones son:

      imagen.row.align-items-start.mb-5
        .col-lg-4
          figure
            img(src="@/assets/curso/tema3/19.svg", alt="").mb-4.mb-lg-0
        .col-lg-8

        .div(titulo="Terapia del lenguaje")
          p Busca mejorar la capacidad de comunicación, desarrollando habilidades como la articulación, el vocabulario y la comprensión del lenguaje. Es crucial para niños con dificultades en el habla, ayudándolos a expresarse y socializar de manera efectiva.

        .div(titulo="Terapia ocupacional")
          p Se centra en la adquisición de habilidades para la vida diaria, como vestirse, alimentarse y escribir. Además, fortalece la motricidad fina y la coordinación, promoviendo la independencia del niño en su entorno cotidiano.

        .div(titulo="Terapia física")
          p Desarrolla el control muscular y la movilidad, trabajando en habilidades motoras gruesas como caminar, correr y mantener el equilibrio. Es esencial para niños con trastornos del desarrollo que afectan la coordinación y el tono muscular.

        .div(titulo="Intervenciones psicológicas")
          p Ayudan a regular emociones, mejorar la autoestima y desarrollar estrategias de adaptación. Incluyen terapia cognitivo-conductual para manejar la ansiedad, el estrés y dificultades en la interacción social.


      p(data-aos="fade-up").mb-5 Las estrategias en el aula son:

      .bg-full-width.bg-color-7.mb-5
        .px-4.px-md-5.pt-5
          .row.justify-content-center.align-items-center

            .col-lg-8
              ul.lista-ul--color
                li.mb-2
                  i.fas.fa-arrow-circle-right
                  | Adaptación curricular con metas alcanzables y ajustadas al nivel del estudiante.
                li.mb-2
                  i.fas.fa-arrow-circle-right
                  | Uso de recursos visuales, auditivos y manipulativos.
                li.mb-2
                  i.fas.fa-arrow-circle-right
                  | Implementación de metodologías activas, como el aprendizaje cooperativo.
                li.mb-2
                  i.fas.fa-arrow-circle-right
                  | Incorporación de diversos canales sensoriales para mejorar la comprensión.
                li.mb-2
                  i.fas.fa-arrow-circle-right
                  | Establecimiento de rutinas predecibles para brindar seguridad.
                li.mb-2
                  i.fas.fa-arrow-circle-right
                  | Recompensa de logros y esfuerzos para motivar la participación.
                li.mb-2
                  i.fas.fa-arrow-circle-right
                  | Evaluación formativa y personalizada.
            .col-lg-4
              figure
                img(src="@/assets/curso/tema3/20.svg" alt="" style="max-width: 400px;").mx-auto.mb-4.mb-lg-0


      .bg-full-width.PurpleContainer.pt-5
        .px-4.px-md-5
          p.mb-0.text-center Para que estas estrategias sean efectivas, es fundamental que los docentes reciban formación continua en inclusión y trabajen en colaboración con otros profesionales y familias.
      .bg-full-width.SplitContainer2.mb-5.pt-5
        .row.justify-content-center
          .col-lg-8
            .bg-color-white.shadow-soft.py-4.px-lg-5(data-aos="fade-up")
              .row.justify-content-around.align-items-center
                .col-md-auto
                  img(src="@/assets/template/bg-icono-link.svg", style="width: 90px;")
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-3.mb-sm-0
                      h3.mb-1 Ciudadanía activa y discapacidad intelectual
                      p.mb-0 Si desean conocer más estrategias, los invitamos a leer el capítulo 6, del libro. 
                    .col-sm-auto
                      a.boton.color-acento-botones.texto-blanco(href="https://elibro.net/es/lc/tecnologicadeloriente/login_usuario/?next=/es/ereader/tecnologicadeloriente/227877/?page=111" target="_blank")
                        span Ir al sitio
                        i.fas.fa-arrow-right


      h2(data-aos="fade-up").mb-4 Trastornos del desarrollo sensorial motórico

      p(data-aos="fade-up").mb-5 Los trastornos del desarrollo sensorial motórico afectan la capacidad de una persona para procesar estímulos sensoriales y responder a ellos con movimientos adecuados. Estos trastornos pueden impactar el equilibrio, la coordinación, la percepción del espacio y la integración de la información sensorial con la motricidad.

      .bg-full-width.border-top.color-primario
        .p-4.p-md-5
          h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
          .row.material-complementario
            .col-12.col-md-6.col-lg-7
              p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar y enriquecer su aprendizaje en los temas tratados en esta unidad.
              
              p.d-flex.my-4
                img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
                a(href="https://www.youtube.com/watch?v=vyZnvgvgm5c&t=136s" target="_blank" rel="noopener noreferrer") Fernández, E. N. M. [@elneuropediatra]. (2020, 14 de febrero). Trastornos del NEURODESARROLLO. [Claves para padres, educadores y profesionales sanitarios]. Youtube.
              
              p.d-flex.my-4
                img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
                a(href="https://www.youtube.com/watch?v=gWmCd201IHw&t=85s" target="_blank" rel="noopener noreferrer") Sprouts Español. (2021, 2 de diciembre). TDAH en la escuela: signos, síntomas, ejemplos y soluciones. Youtube.
              
              p.d-flex.my-4
                img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
                a(href="https://www.youtube.com/watch?v=zRM3sVJYqbk" target="_blank" rel="noopener noreferrer") CanalFenascol. (2023, 11 de octubre). La Lengua de Señas es un derecho y en Colombia la Ley 324 de 1996 lo reconoce. Youtube.
            
            .col-12.col-md-6.col-lg-3.offset-lg-1
              figure
                img(src='@/assets/componentes/material-complementario.svg', alt='')
      

      .bg-full-width.border-top.actividad.bg-color-actividad
        .p-4.p-md-5
          #Actividad                
            <Actividad :cuestionario="cuestionario"/>

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
import Actividad from '@/components/actividad/Actividad.vue'
export default {
  name: 'Tema3',
  components: {
    Actividad,
  },
  data() {
    return {
      cuestionario: {
        tema: 'Herramientas colaborativas para la construcción de paz',
        titulo: 'Ponte a prueba',
        introduccion:
          'Demuestra lo que aprendiste en esta unidad y pon a prueba tus conocimientos.',
        barajarPreguntas: true,
        preguntas: [
          {
            id: 1,
            texto:
              '¿Cuál de las siguientes es una característica fundamental de los derechos humanos?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Son temporales y cambiantes',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Son universales y aplican a todas las personas',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Son exclusivos de ciertos grupos',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Son opcionales',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 2,
            texto:
              '¿Cuál de las siguientes afirmaciones sobre la diversidad cultural es correcta?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Fomenta la homogeneización cultural',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Promueve el respeto y la aceptación de las diferencias',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Debilita la identidad cultural de los pueblos',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Limita las oportunidades de interacción',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 3,
            texto:
              'La mediación en un conflicto tiene como objetivo principal:',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Imponer una solución rápida',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Facilitar el diálogo entre las partes',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Determinar la culpabilidad',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Ignorar las preocupaciones de una parte',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 4,
            texto: 'En un foro comunitario, es importante:',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Escuchar solo a las autoridades',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Fomentar la participación de todos los miembros',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Decidir por votación sin consultar a los demás',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Excluir las opiniones de los más jóvenes',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 5,
            texto:
              '¿Qué busca la justicia restaurativa en el contexto de un conflicto?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Aplicar una sanción severa',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Reparar el daño y restablecer las relaciones',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Castigar a las partes involucradas',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Ignorar el contexto del conflicto',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
        ],
        mensaje_final_aprobado:
          '¡Felicidades! Has superado la prueba con éxito.',
        mensaje_final_reprobado:
          'Te recomendamos repasar nuevamente la unidad para reforzar los conceptos clave antes de volver a intentarlo.',
      },
    }
  },
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.bg-color-actividad
  background-color: #EBF1F5

.PurpleContainer
  background: linear-gradient(180deg, #FFFFFF 0%, #EAE9EE 100%)

.SplitContainer2
  background: rgb(85,122,250)
  background: linear-gradient(0deg, rgba(255,255,255,1) 0%, rgba(255,255,255,1) 50%, rgba(235,233,240, 1) 50%)
</style>
