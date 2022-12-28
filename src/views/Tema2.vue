<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Proceso de caracterización y diagnóstico del programa Mi familia
    .row.mb-5.justify-content-center.align-items-center(data-aos="fade-right")
      .col-lg-4.mb-4.mb-lg-0
        figure
          img.img-t(src='@/assets/curso/tema2/img1.png').m-auto
      .col-lg-8(data-aos="fade-left")
        p El programa Mi familia contempla la caracterización y el diagnóstico como parte fundamental del acompañamiento familiar psicosocial. Este proceso propone un plan de acompañamiento pertinente para cada una de las familias beneficiarias, promueve el reconocimiento de su propia realidad e historia como condición necesaria para la apropiación de su proceso de transformación y hace posible una estimación de los resultados del acompañamiento en cada familia, sumándole además el monitoreo y el seguimiento a un programa que se enmarca en la política pública social. Ver figura.
    .bg8 
      .row.mb-5.justify-content-center
        .col-lg-6.col-xl-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 1
            span Ciclo de atención del programa
          figure
            img(src='@/assets/curso/tema2/img2.png').mb-3
            figcaption Nota. Tomado de ICBF (2021).
    .bg9.p-2.mb-5
      .row.align-items-center.p-3
        .col-lg-auto
          figure
            img.mb-3(src='@/assets/curso/tema2/img3.svg', style="width: 80px").m-auto
        .col-lg.mb-4.mb-lg-0
          p.mb-0 Para el desarrollo del diagnóstico de las familias, los profesionales de acompañamiento familiar cuentan con una batería de instrumentos que les permite abordar diferentes perspectivas de las familias, tal como se aprecia a continuación:
    .row.mb-5.justify-content-center
      .col-lg-10
        figure
          img(src='@/assets/curso/tema2/img4.svg').mb-3
    p.mb-5 Todos estos instrumentos permiten, por un lado, que el profesional de acompañamiento familiar comprenda mejor las realidades de las familias y proponga cursos de acción adecuados y, por otro lado, que la familia reconozca su propia realidad e historia, condición necesaria para la apropiación de su proceso de transformación. En los siguientes subtemas se explica con más detalle cada uno de los instrumentos disponibles para el diagnóstico.
    Separador
    #t_2_1
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.1 ¿Cuál es el sentido del proceso de caracterización y diagnóstico del programa Mi familia?
    .row.mb-5.justify-content-center.align-items-center(data-aos="fade-right")
      .col-lg-4.mb-4.mb-lg-0
        figure
          img.img-t(src='@/assets/curso/tema2/img5.png').m-auto
      .col-lg-8(data-aos="fade-left")
        p Una de las características principales del proceso de caracterización y diagnóstico del programa Mi familia y que guarda armonía con lo expuesto en el apartado anterior es que este no es realizado por un actor externo especializado con total autonomía, sino que promueve la participación de las familias y sus integrantes. En este proceso el profesional realiza la lectura de la realidad y del contexto de manera conjunta con la familia, asumiéndolo como un ejercicio de transformación y motivación al cambio. Esto es posible dado que las preguntas que plantea el profesional, orientadas por los distintos instrumentos, implican un proceso reflexivo por parte de las familias. En el siguiente video se presenta con mayor claridad el proceso de caracterización y diagnóstico del programa:
    figure(data-aos="zoom-in").mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/erZl9TpBowM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
        
    Separador
    #t_2_2
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.2 Ficha de caracterización sociofamiliar (FCSF) 
    .row.mb-5.justify-content-center.align-items-center(data-aos="fade-right")
      .col-lg-4.mb-4.mb-lg-0
        figure
          img.img-t(src='@/assets/curso/tema2/img6.svg').m-auto
      .col-lg-8(data-aos="fade-left")
        p Permite el registro de todas las personas que pertenecen al grupo familiar beneficiario de Mi familia, recogiendo información individual relacionada con nombres, apellidos, edad, sexo, nivel educativo, afiliación a salud y principal actividad que realiza cada integrante del grupo familiar, así como el registro de información grupal, por ejemplo, acceso a servicios públicos, condición y tenencia de la vivienda, entre otros.
        p Esta ficha tiene cuatro apartados: 1. Información de la entidad contratista; 2. Información de la ubicación de la vivienda familiar; 3. Información del jefe del grupo familiar; 4. Integrantes del grupo, tal y como lo expone el siguiente recurso:
    .row.justify-content-center.align-items-center.mb-5          
      .col-lg-6.py-4
        .tarjeta--azul1.p-4.p-md-5
          SlyderA(tipo="b").color_slyder-a_botones
            .row.justify-content-center.align-items-center        
              .col-lg-9.mb-4.mb-md-0
                h4.mb-4 Entidad del contratista
                ul.lista-ul
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 Nombre del contratista.
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 Tipo de documento de la entidad (NIT-RUT).
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 Número de identificación.
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 Número de contrato.
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 Nombre y apellido del profesional de acompañamiento familiar.
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 Tipo de documento de identidad del profesional.
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 Número de documento de identificación del profesional.
              .col-lg-3.d-flex.align-items-start 
                img.img-t(src='@/assets/curso/tema2/img7.svg', alt='')   
            .row.justify-content-center.align-items-center              
              .col-lg-9.mb-4.mb-md-0
                h4.mb-4 Ubicación de la vivienda familiar
                ul.lista-ul
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 Tipo de vivienda.
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 País, departamento, municipio o ranchería.
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 Ubicación de la vivienda.
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 Tenencia de la vivienda.
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 Acceso a servicios públicos.
              .col-lg-3
                img.img-t(src='@/assets/curso/tema2/img8.svg', alt='')
            .row.justify-content-center.align-items-center             
              .col-lg-9.mb-4.mb-md-0
                h4.mb-4 Nivel individual: jefe del grupo familiar
                ul.lista-ul
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 Información básica de identificación.
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 De autorreconocimiento étnico.
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 Tipo de beneficiario y educación.
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 Ocupación y de acceso a salud.
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 Género y diversidad sexual.
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 Discapacidad.
              .col-lg-3.pe-2
                img.img-t(src='@/assets/curso/tema2/img9.svg', alt='')
            .row.justify-content-center.align-items-center             
              .col-lg-9.mb-4.mb-md-0
                h4.mb-4 Nivel individual: integrantes del grupo
                ul.lista-ul
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 Información básica de identificación.
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 De autorreconocimiento étnico.
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 Tipo de beneficiario y educación.
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 Ocupación y de acceso a salud.
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 Género y diversidad sexual.
                  li 
                    i.fas.fa-caret-right(style="color:#F46464")
                    p.mb-0 Discapacidad.
              .col-lg-3
                img.img-t(src='@/assets/curso/tema2/img10.svg', alt='')  
      .col-lg-6
        img.img-t(src='@/assets/curso/tema2/img11.svg', alt='')
    .row
      .col-12.p-5.tambloqimg.tambloqtxt        
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema2/img12.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 En la indagación que permite diligenciar la FCSF se recomienda tener especial cuidado con el diligenciamiento de la información sobre el nivel educativo de los padres, las madres y los cuidadores, las condiciones de la vivienda, la situación laboral de los adultos del hogar, la asistencia escolar y la afiliación a salud de los niños, las niñas y los adolescentes, así como la información que tiene que ver con las características diferenciales de las personas como género y diversidad sexual, discapacidad y pertenencia étnica. <br><br> Esto con el objetivo de identificar las necesidades esenciales por satisfacer o derechos inobservados y orientar acciones específicas, articuladas con los entes territoriales y las entidades respectivas, para promover el acceso a bienes y servicios, mejoras en las condiciones de vida de las familias y la garantía del goce efectivo de sus derechos. 
    .row.justify-content-center.ps-3.mb-5
      .col-lg-12
        .tarjeta.color-primario.p-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema2/img13.svg")
            .col
              .row.align-items-center
                .col.mb-3.mb-sm-0.pt-2
                  h4 Información ubicación de la vivienda
                  p A continuación se presentan las preguntas y las opciones de respuesta del apartado Información ubicación de la vivienda. 
                .col-sm-auto
                  a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('/downloads/anexo1.pdf')" target="_blank")
                    .anexo__iconomb-0                    
                    span Descargar
                    i.fas.fa-download
    .row.mb-5.justify-content-center
      .col-lg-10            
        figure
          img(src='@/assets/curso/tema2/img14.png').mb-3
          figcaption Nota. Tomado del ICBF (2021).
    .bg1.p-2
      .row.align-items-center.p-3
        .col-lg-auto
          figure
            img.mb-3(src='@/assets/curso/tema2/img15.svg', style="width: 80px").m-auto
        .col-lg.mb-4.mb-lg-0
          p.mb-0 Para este apartado se identifican campos con opciones de respuesta como se presenta en la ficha. La persona que responde este apartado será el jefe del grupo familiar, su cónyuge o cualquier otro integrante de 18 años o más. Es importante tener en cuenta que en una vivienda puede haber más de un grupo familiar y que se debe atender y diligenciar esta información para el grupo familiar al que pertenezca el niño, la niña o el adolescente que generó los criterios de selección. Para el caso de Mi familia si está o estuvo en una modalidad priorizada de protección o de primera infancia, entre otros, de acuerdo con la Guía de focalización de la modalidad.
    p.mb-5 La mayor parte de los campos relacionados con la ubicación de la vivienda pueden ser diligenciados previamente de acuerdo con las indicaciones suministradas por la gerencia de operaciones, a partir del análisis de la base de vinculación y de los municipios o ciudades a atender. A continuación se presenta la orientación para el diligenciamiento del campo específico “Zona de ubicación”: 
    .row.justify-content-center.align-items-center
      .col-lg-8
        ImagenInfografica.color-acento-botones.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/tema2/img16.svg', alt='Texto que describa la imagen')(data-aos="fade-right")
          .tarjeta.color-cuarto.p-3(x="71.5%" y="30.6%" numero="a")
            p <b>Cabecera Municipal (CM)</b> 
            p.mb-0 Es el área geográfica que está definida por un perímetro urbano. Corresponde al lugar en donde se ubica la sede administrativa de un municipio. 
          .tarjeta.color-cuarto.p-3(x="86.7%" y="31%" numero="b")
            p <b>Centro Poblado (CP):</b> 
            p.mb-3 Es un concepto creado por el DANE para la identificación de núcleos de población. Se define como una concentración de mínimo veinte viviendas contiguas, vecinas o adosadas entre sí, ubicada en el área rural de un municipio o de un corregimiento departamental. Dicha concentración presenta características urbanas, tales como la delimitación de vías vehiculares y peatonales. Dentro de los centros poblados se encuentran los caseríos, inspección de policía o los corregimientos.  
          .tarjeta.color-cuarto.p-3(x="41.1%" y="46%" numero="c")
            p <b>Resto</b> 
            p.mb-0 Se debe marcar Resto cuando la vivienda esté ubicada en el área rural o resto municipal, que de acuerdo con el DANE se caracteriza por la disposición dispersa de viviendas y explotaciones agropecuarias existentes en ella. No cuenta con un trazado o nomenclatura de calles, carreteras, avenidas y demás; ni tampoco dispone, por lo general, de servicios públicos y de otro tipo de facilidades propias de las áreas urbanas.
    .row.justify-content-center.ps-3.mb-5
      .col-lg-12
        .tarjeta.color-primario.p-4
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/tema2/img17.svg")
            .col
              .row.align-items-center
                .col.mb-3.mb-sm-0.pt-2
                  p <b>Guía para el diligenciamiento de la Ficha de caracterización sociofamiliar</b>
                  p Estimado aprendiz, se sugiere la consulta de este documento para la profundización de la temática. Este recurso también se encuentra como material complementario.
                .col-sm-auto
                  a.boton.color-acento-botones.texto-blanco(href="https://www.icbf.gov.co/system/files/procesos/g4.mo18.pp_guia_para_diligenciamiento_ficha_caracterizacion_socio_familiar_v2.pdf" target="_blank")
                    .anexo__iconomb-0                    
                    span Ir a página
                    i.fas.fa-link 
    .row.justify-content-center
      .col-12.col-lg-8.p-5
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema2/img53.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Finalmente, la información de caracterización le permite a la Dirección de familias y comunidades hacer los análisis agregados de las familias de acuerdo con sus características socioeconómicas y de esta manera, identificar fortalezas u oportunidades de mejora para la modalidad.
    Separador
    #t_2_3
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.3 Genograma
    .row.mb-5.justify-content-center(data-aos="fade-right")
      .col-lg-7.mb-4.mb-lg-0(data-aos="fade-left")
        p.mb-5 Para el abordaje con este instrumento es fundamental tener a disposición un mapa completo de los integrantes de la familia y sus allegados significativos, así como de las cualidades de sus relaciones y aspectos estructurales como el parentesco, los roles que desempeñan, los acuerdos y las prácticas del sistema familiar y la forma como afrontan situaciones estresantes. 
        
        .bloque-texto-f.color-secundario.pt-4.px-5.mb-5
          .bloque-texto-f__comillas
            i.fas.fa-quote-left
            i.fas.fa-quote-right
          h4.text-regular.bloque-texto-f__texto El genograma se usa como instrumento gráfico que permite conocer, recoger, registrar y exponer algunos datos de la familia, información de sus integrantes y las relaciones a lo largo de diferentes generaciones 
          .bloque-texto-f__autor.mb-3.d-flex.align-self-end
            p.text-bold Fernández, Escalante & Palmero, 2011).   
      .col-lg-5
        figure
          img.img-t(src='@/assets/curso/tema2/img18.png').m-auto
    .row.justify-content-center.align-items-center          
      .col-lg-10
        .bg10
          .tarjeta.position-relative.rounded-0.p-4(data-aos="flip-down")
            .row.justify-content-center.align-items-center
              .col-lg-4
                .imagen-absolute1
                  img.img-t.mx-auto(data-aos="zoom-in")(src='@/assets/curso/tema2/img19.svg', alt='')
              .col-lg-8.my-3
                p(data-aos="fade-down") Esta herramienta permite entender cómo, cuándo y de qué manera sucede una situación y quiénes son los integrantes de la familia que participan en esta. Así, el genograma puede ayudar a los integrantes de “la familia a verse como parte de un todo y a reconocer que la familia en su conjunto tiene un papel activo en el proceso que puede afectar a cada uno de sus integrantes” (Fernández, Escalante & Palmero, 2011, p. 19).
    .row.justify-content-center.align-items-center.mb-5.py-5           
      .col-lg-10
        .bg11
          .tarjeta.position-relative.rounded-0.p-4(data-aos="flip-down")
            .row.justify-content-center.align-items-center
              .col-lg-8.my-3
                p(data-aos="fade-down") En una lectura ecosistémica de la familia es útil explicitar el mapa completo de sus miembros a lo largo de al menos tres generaciones, en el cual se referencian los allegados significativos de cada integrante y las características de las relaciones entre ellos. En estos mapas también se desglosan los acuerdos y las prácticas del sistema familiar, y la forma cómo dan manejo a situaciones desafiantes. 
                p Para construir un genograma es necesario tener en cuenta tres fases, de acuerdo con Feixas, Muñoz & Montesano (2012):
              .col-lg-4
                .imagen-absolute2
                  img.img-t.mx-auto(data-aos="zoom-in")(src='@/assets/curso/tema2/img20.svg', alt='')
    .row.justify-content-center.g-2.mb-5
      .col-lg-4.col-md-8.mb-4
        .tarjeta.tarjeta-flip.color-secundario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img24.png')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5.flex-center-text
              .row.justify-content-center
                .col-lg-12.mb-4
                  .bg6.p-2
                    h4.text-center.m-0 Trazado de la estructura familiar
                p Es la descripción gráfica de los integrantes de la familia y de las uniones biológicas y legales entre las generaciones. Pueden usarse cuadrados, círculos o triángulos, dependiendo del género de la persona, y las líneas simbolizan las relaciones. 
      .col-lg-4.col-md-8.mb-4
        .tarjeta.tarjeta-flip.color-secundario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img22.svg')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5.flex-center-text
              .row.justify-content-center
                .col-lg-12.mb-4
                  .bg6.p-2
                    h4.text-center.m-0 Registro de información familiar
                p Inclusión de otros datos de la familia como fechas de nacimiento, fallecimiento, matrimonio, separación, divorcio, entre otros, además incorpora datos sobre cambios de relaciones, migraciones u otros que den cuenta de sucesos familiares significativos. 
      .col-lg-4.col-md-8.mb-4
        .tarjeta.tarjeta-flip.color-secundario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img23.svg')})`}")
            .tarjeta-flip__contenido.p-4.p-xl-5.flex-center-text
              .row.justify-content-center
                .col-lg-12.mb-4
                  .bg6.p-2
                    h4.text-center.m-0 Registro de las relaciones familiares
                p Parte de la información suministrada por la familia, así como de la observación del profesional. Es representado a partir de diferentes tipos de líneas para evidenciar el carácter de las relaciones entre los miembros de la familia.
    
    .row.mb-4.justify-content-center(data-aos="fade-right")
      .col-lg-4
        figure
          img.img-t.mb-3(src='@/assets/curso/tema2/img54.svg').m-auto
      .col-lg-8.mb-4.mb-lg-0(data-aos="fade-left")
        p.mb-5 Esta herramienta brinda una vista sencilla de la familia sobre contenidos con carga emocional como nacimientos, muertes o conflictos que pueden ser identificados por el profesional en una conversación. Es de gran ayuda en el trabajo con familias, pues se puede volver a eventos pasados que marcaron la trayectoria tanto familiar como de cada integrante, así como conversar sobre aspectos familiares que permiten una mejor comprensión de sus procesos. Al profesional también le da un mejor entendimiento de la familia y de las posibilidades del acompañamiento.
        .row.justify-content-center
          .col-lg-11.tambl1
            .bloque-texto-f.color-secundario.pt-4.px-5.mb-5
              .bloque-texto-f__comillas
                i.fas.fa-quote-left
                i.fas.fa-quote-right
              h4.text-regular.bloque-texto-f__texto La lectura de esta herramienta tiene distintos niveles de interpretación. Una se focaliza en la composición familiar, mientras otras pueden centrarse en la repetición de pautas a través de las generaciones de la familia, así como en la manera como los sucesos de la vida están interconectados con los cambios en el funcionamiento familiar, también puede hacerse una mirada que evidencie las transiciones y pérdidas, su significado, y con relación a las formas de afrontamiento en la familia.
              .bloque-texto-f__autor.mb-3.d-flex.align-self-end
                p.text-bold (Cibanal, 2002).
        
      p.mb-5 Las principales convenciones para la realización y comprensión del genograma en cuanto a las personas que conforman la familia son:
      .row.justify-content-center
        .col-lg-8.col-xl-8
          .titulo-sexto.color-acento-contenido
            h5 Figura 2
            span Convenciones de las personas de la familia
          figure
            img(src='@/assets/curso/tema2/img25.svg').mb-3
            figcaption Nota. Adaptado de Feixas, Muñoz y Montesano (2012).
    .bg9.p-2.mb-5
      .row.align-items-center.p-3
        .col-lg-auto
          figure
            img.mb-3(src='@/assets/curso/tema2/img26.svg', style="width: 80px").m-auto
        .col-lg.mb-4.mb-lg-0
          p.mb-0 Por su parte, la siguiente figura presenta las convenciones correspondientes a los tipos de relaciones y vínculos que hay entre las personas de las familias como se muestra a continuación: 
    .row.justify-content-center.mb-5
      .col-lg-8.col-xl-8
        .titulo-sexto.color-acento-contenido
          h5 Figura 3
          span Convenciones de relaciones o vínculos al interior de la familia
        figure
          img(src='@/assets/curso/tema2/img27.svg').mb-3
          figcaption Nota. Adaptado de Feixas, Muñoz y Montesano (2012).
    p.mb-5 A manera de ejemplo se realiza el genograma de una familia que actualmente está conformada por una pareja de dos hombres, uno de ellos, Camilo, tiene un hermano menor, Julián y tras el fallecimiento de su madre, María, Camilo queda como tutor legal de Julián y es llevado a vivir con su pareja:
    .row.justify-content-center.mb-5
      .col-lg-8.col-xl-8
        figure
          img(src='@/assets/curso/tema2/img28.svg').mb-3
    p.mb-5 A continuación se explica la conformación familiar: 
    figure(data-aos="zoom-in").mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/ew81C_EJ1Hk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
        
    Separador
    #t_2_4 
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.4 Ecomapa
    .row.justify-content-center.align-items-center.mb-5          
      .col-lg-10
        .bg10
          .tarjeta.position-relative.rounded-0.p-4(data-aos="flip-down")
            .row.justify-content-center.align-items-center
              .col-lg-4
                .imagen-absolute3
                  img.img-t.mx-auto(data-aos="zoom-in")(src='@/assets/curso/tema2/img29.svg', alt='')
              .col-lg-8.my-3
                p(data-aos="fade-down") Teniendo en cuenta a Clemente (2003), para cada individuo o familia la red es la suma de todas las relaciones que perciben como significativas, así como el conjunto finito de actores y de relaciones que se autodefinen dentro de la misma. El mapa de red o ecomapa es una representación gráfica de la relación o del sistema de vinculación más significativo de una persona o de la familia con su contexto primario con instituciones y con actores sociales. Se constituye en una herramienta complementaria al genograma con el objetivo de aproximarse a la realidad familiar. Ver figura.
    .row.justify-content-center.mb-5
      .col-lg-8.col-xl-8
        .titulo-sexto.color-acento-contenido
          h5 Figura 4
          span Ecomapa
        figure
          img(src='@/assets/curso/tema2/img30.png').mb-3
          figcaption Nota. Tomado del ICBF (2020).
    .row.mb-5.justify-content-center.align-items-center(data-aos="fade-right")
      .col-lg-7(data-aos="fade-left")
        p El ecomapa le permite a cada integrante y a la familia en general identificar su grado de satisfacción, de cercanía y vinculación con una red, así como establecer potencialidades o situaciones problemáticas. Con ese nivel de satisfacción o de insatisfacción, la persona, la familia y los profesionales pueden identificar acciones posibles para ampliarla, modificar vínculos y resolver las situaciones problemáticas en cada área.
        p Para conocer las redes de las familias beneficiarias de la oferta Mi familia se propone el uso del ecomapa. Este instrumento permite identificar de forma rápida el estado en términos relacionales de la familia, tanto al interior (relaciones filiales y afectivas) como con actores externos, ya sean formales o informales, tales como el deporte, el colegio, los amigos o el empleo. 
      .col-lg-5.mb-4.mb-lg-0
        figure
          img.img-t(src='@/assets/curso/tema2/img31.png').m-auto
    .bg9.p-2.mb-5
      .row.align-items-center.p-3
        .col-lg-auto
          figure
            img.mb-3(src='@/assets/curso/tema2/img32.svg', style="width: 80px").m-auto
        .col-lg.mb-4.mb-lg-0
          p.mb-0 Debido a que es la extensión o complemento del genograma, también muestra las relaciones de la familia, lo que permite al profesional de acompañamiento trazar una ruta de acción más cercana a las realidades de la familia, de acuerdo con su propio desarrollo y la relación o construcción con su territorio. En este sentido, el concepto de territorio no solo obedece a la idea de un área física delimitada, habitada y usada, sino que es producto de las relaciones sociales entre lo que se considera personas en cada una de las sociedades, y entre estas y su entorno (Ardila, 2006).
    .row.mb-5.justify-content-center.align-items-center(data-aos="fade-right")
      .col-lg-4.mb-4.mb-lg-0
        figure
          img.img-t(src='@/assets/curso/tema2/img33.png').m-auto
      .col-lg-8(data-aos="fade-left")
        p El ecomapa puede ser construido por cada integrante de manera autónoma o en conjunto con el PAF en una conversación en la cual, además, se construya el sentido de cada relación y la posibilidad de enriquecerla en el futuro inmediato. Se solicita a la persona o a la familia que represente en el gráfico a las personas de su red social en un momento concreto, según se defina por parte del profesional para el desarrollo de la intervención.
        p En la construcción del ecomapa se hace necesario registrar todos los actores con los que la familia tiene relación, incluyendo los que de alguna forma generen procesos de estrés o malestar (grupos armados, venta de sustancias psicoactivas, vertederos de aguas negras, entre otros), con el fin de identificar estos actores y buscar formas de protección de la familia con estrategias individuales o comunitarias que minimicen los riesgos que estos pueden generar para las familias y las comunidades.
    .bg13
      .row.mb-5.justify-content-center.align-items-center(data-aos="fade-right")
        .col-lg-11(data-aos="fade-left")
          p Teniendo en cuenta lo anterior, cobra relevancia el papel del gestor de oferta y del profesional de acompañamiento familiar, ya que son los encargados de realizar el análisis de las redes a las que pertenece la familia y su relación con estas, así como de identificar que otras redes existen en el territorio, además de ayudar a gestionar situaciones que estén presentes en la familia que no sean generativas.
        .col-lg-1.mb-4.mb-lg-0
          figure
            img.img-t(src='@/assets/curso/tema2/img34.svg').mx-auto
    .row.mb-5
      .col-12.p-5
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema2/img35.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Es importante que estos dos profesionales estén en constante comunicación y tengan claridad que no todas las familias deben estar en las mismas redes, ya que su aporte o no, depende de las dinámicas familiares y comunitarias. Ahora bien, para valorar, identificar acciones de intervención y realizar seguimiento es necesario que tanto el profesional de acompañamiento como el gestor de oferta registren la información en los formatos y sistemas de información que disponga el ICBF para tal fin. <br><br> Por lo anterior, en el aplicativo Mi familia se definieron las siguientes variables que se deben recoger en conversación con la familia y, como resultado de la elaboración del ecomapa lo siguiente:
    .row.justify-content-center.mb-5
      .col-lg-10.col-xl-8
        figure
          img(src='@/assets/curso/tema2/img36.svg').mb-3
    p.mb-5 Es importante tener presente que estos elementos deberán ser de especial atención por parte del profesional y del gestor para movilizar el componente de convergencia de oferta, gestión de redes y realizar los reportes en el seguimiento al componente. 
    Separador
    #t_2_5 
    .titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 2.5 Instrumentos de medición de habilidades
    .row.mb-5.justify-content-center.align-items-center(data-aos="fade-right")
      .col-lg-4.mb-4.mb-lg-0
        figure
          img.img-t(src='@/assets/curso/tema2/img37.png').m-auto
      .col-lg-8(data-aos="fade-left")
        p Para complementar la información que se recoge a través de la ficha sociofamiliar, el genograma y el ecomapa, el programa Mi familia incorpora cuatro instrumentos que permiten medir habilidades relevantes en la vida familiar y que se relacionan con los objetivos que busca el programa. Estos instrumentos son la autoeficacia parental, la disciplina positiva, la regulación emocional y la vinculación.
        p Estos instrumentos se seleccionaron luego de una amplia revisión y tienen en común que han sido validados a través de estudios e investigación. A continuación se presenta el valor que tienen estos:
    .row.justify-content-center.align-items-center.mb-5          
      .col-lg-12.py-4
        .tarjeta--azul1.p-4.p-md-5
          SlyderA(tipo="b").color_slyder-a_botones
            .row.justify-content-center.align-items-center        
              .col-lg-6.mb-4.mb-md-0
                h4.mb-4 Perfiles o patrones
                p Proporcionan información adicional al PAF y a la familia, dado que proveen algunos perfiles o patrones en relación con las habilidades de interés, que permitirán realizar una conversación acerca de las razones por las cuales la familia obtuvo un determinado resultado, lo que piensa de esa información y las posibles transformaciones.
              .col-lg-6
                img.img-t(src='@/assets/curso/tema2/img38.png', alt='') 
            .row.justify-content-center.align-items-center              
              .col-lg-6.mb-4.mb-md-0
                h4.mb-4 Hipótesis de trabajo
                p Dicha información le permite al PAF y a la familia conocer el estado inicial en relación con estos temas para generar hipótesis de trabajo e identificar énfasis para las sesiones del ciclo básico y seleccionar las temáticas para las sesiones de profundización. Al PAF, en particular, le ayuda a orientar el acompañamiento psicosocial y a guiar el abordaje general de la atención.
              .col-lg-6
                img.img-t(src='@/assets/curso/tema2/img39.png', alt='')
            .row.justify-content-center.align-items-center             
              .col-lg-6.mb-4.mb-md-0
                h4.mb-4 Avances
                p Estos instrumentos se aplican al inicio y al final del acompañamiento como aproximación a los resultados del mismo, igualmente, establecen los avances de las familias y la autopercepción sobre sus avances, de tal manera que puedan visualizarlos de manera complementaria a través de la información que arrojan este tipo de instrumentos.
              .col-lg-6
                img.img-t(src='@/assets/curso/tema2/img40.png', alt='')
    .bg9.p-2.mb-5
      .row.align-items-center.p-3
        .col-lg-auto
          figure
            img.mb-3(src='@/assets/curso/tema2/img41.svg', style="width: 80px").m-auto
        .col-lg.mb-4.mb-lg-0
          p.mb-0 Ahora, se presenta para cada instrumento la definición de la habilidad o aspecto que pretende medir, por qué es importante para el fortalecimiento familiar, a quiénes se aplica y una descripción general del mismo:
    .row.justify-content-center.align-items-center.mb-5     
      .col-lg-12(data-aos="fade-right")
        AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--azul4")
          .row.align-items-center(titulo="Autoeficacia parental")   
            .col-lg-9.my-3.mb-4.mb-md-0
              p Se refiere a la percepción que tienen las personas sobre su propia capacidad para desempeñarse como buenos padres o madres, y se ve afectada por distintos factores como el conocimiento que tenga el padre o la madre sobre prácticas de crianza, el acceso a información que le ayude a entender las necesidades de su hijo o hija en cada momento de su desarrollo, entre otros.
              p <b>Es necesario tener en cuenta que el instrumento de eficacia parental tiene 17 preguntas y se compone de dos subescalas: la de autoeficacia y la de satisfacción.</b> La primera corresponde a una dimensión instrumental que refleja la competencia, la capacidad de resolución de problemas y la capacidad en el papel de los padres y las madres, mientras que la segunda es una dimensión afectiva que refleja la frustración, la ansiedad y la motivación de los padres. Dentro de las 17 preguntas, 8 se dirigen a medir la satisfacción y 9 la autoeficacia, y en todas ellas la persona tiene 6 opciones de respuesta que son: totalmente en desacuerdo, bastante en desacuerdo, en desacuerdo, de acuerdo, bastante de acuerdo y totalmente de acuerdo.
            .col-lg-3.my-3 
              img.img-a.img-t(src='@/assets/curso/tema2/img42.png', alt='')  
            p <b>Este instrumento es de autoreporte, está dirigido a los padres y las madres de los NNA del grupo familiar. Esta relación de parentesco puede ser biológica, jurídica o de crianza. </b>
          .row.align-items-center(titulo="Disciplina positiva ")   
            .col-lg-9.my-3.mb-4.mb-md-0
              p La disciplina positiva o crianza respetuosa se puede considerar como una forma no violenta y respetuosa de interactuar con los niños, las niñas y los adolescentes. Es una manera de aproximación que le permite a los padres y las madres ayudar, enseñar, orientar y relacionarse con los NNA de forma que puedan tener el apoyo y la información necesaria para su desarrollo (Durrant, 2011). Estas formas de aproximarse se pueden analizar a través de las prácticas que los padres aplican para interactuar en la crianza de sus hijos. 
              p En palabras simples, “disciplina” significa “enseñar”. La disciplina positiva es la forma más amorosa de enseñanza. Involucra la crianza, confianza, conexión, habilidades para compartir, y crear un ambiente donde los niños puedan desarrollar sus capacidades y confianza. La disciplina positiva está soportada sobre la enseñanza, entendimiento, motivación y comunicación, no en el castigo. El castigo busca que los niños y las niñas “paguen” por lo que han hecho. La disciplina está diseñada para ayudar a los niños y las niñas a aprender de lo que han hecho (Nelsen, Erwin y Duffy, 2015). 
            .col-lg-3.my-3 
              img.img-a.img-t(src='@/assets/curso/tema2/img43.png', alt='')  
            p <b>El instrumento cuenta con 29 afirmaciones que miden 5 prácticas específicas: parentalidad positiva (6 afirmaciones); involucramiento parental (10 afirmaciones); bajo monitoreo o supervisión (10 afirmaciones); y castigo físico (3 afirmaciones). Este instrumento de autoreporte es multifuente, es decir, está dirigido a los padres, las madres o a quien ejerza este rol y a los adolescentes entre los 12 y los 17 años, con el objetivo de obtener una perspectiva bidimensional de las prácticas parentales.</b>
          .row.align-items-center(titulo="Regulación emocional")     
            .col-lg-9.my-3.mb-4.mb-md-0
              p Para entender el concepto de regulación emocional es necesario partir de la noción de emoción que, de acuerdo con Gómez y Calleja (2016), se puede entender como “una respuesta del individuo ante los estímulos del entorno que coordina diferentes sistemas y tiene como objetivo proporcionar información para influir en él según sus necesidades” (p. 97). Además, son ‘respuestas inteligentes’ que se construyen racionalmente (Naussbaum, 2001) y, por esa razón, “independientemente de la perspectiva desde la que se aborde el concepto, es considerada como una de las variables psicológicas de más impacto en la vida de los individuos, ya que determina el comportamiento en gran medida” (Gómez y Calleja, 2016, p. 98).
              p El reconocimiento de las emociones y la regulación emocional se ha considerado un aspecto fundamental del desarrollo individual y familiar dada su relación con la autoestima y la satisfacción con la vida, la inteligencia emocional, la competencia social, la personalidad, el temperamento, los procesos de aprendizaje, el desempeño académico, el desempeño laboral, entre otros.
            .col-lg-3.my-3 
              img.img-a.img-t(src='@/assets/curso/tema2/img44.png', alt='') 
            p <b>Este instrumento se aplica a quienes en la familia cumplan el rol de padres, madres o a los cuidadores (cuando no estén presentes el padre o la madre), a los niños, las niñas y los adolescentes entre 12 y 17 años.</b>
          .row.align-items-center(titulo="Vinculación")     
            .col-lg-9.my-3.mb-4.mb-md-0
              p El vínculo supone la sensibilidad con las capacidades del otro y no solo con sus necesidades. Supone conocimiento y respeto por las aspiraciones del otro. Implica la comprensión de las dificultades del otro según como este las vive y no según como se perciben desde fuera. De esta manera, los vínculos afectivos permiten que las personas que los desarrollan se sientan parte significativa del colectivo (ICBF y MEN, 2009).
              p Por tanto, la vinculación es un proceso psicoemocional donde interactúan las madres y los padres con sus hijas e hijos, que permite que reconozcan su entorno e influye en las áreas psicológicas, física, cognitiva, social y emocional, así como en el mejoramiento de su confianza y resiliencia contribuyendo a un desarrollo cerebral sano (Pérez-Abarca, Lucchini-Raies, & Márquez-Doren, 2020). 
            .col-lg-3.my-3 
              img.img-a.img-t(src='@/assets/curso/tema2/img45.png', alt='') 
            p <b>El instrumento de vinculación del programa Mi familia contempla dos subescalas, cariño y hostilidad. La primera hace referencia al relacionamiento con el otro mediante acciones y muestras de simpatía, apego, amistad y amor; mientras que la subescala de hostilidad da cuenta de las acciones agresivas o adversas entre las personas. Este instrumento incluye en total doce ítems y se aplica a los niños, las niñas y los adolescentes entre 12 y 17 años que hagan parte de la familia que recibe el acompañamiento.</b>
    .row.mb-5.justify-content-center.align-items-center(data-aos="fade-right")
      .col-lg-4.mb-4.mb-lg-0
        figure
          img.img-t(src='@/assets/curso/tema2/img46.svg').m-auto
      .col-lg-8(data-aos="fade-left")
        p Cabe decir de manera adicional que en la autoeficacia parental la confianza de los padres y las madres en sus propias capacidades los hacen sentir más satisfechos, motivados y tener mayor tolerancia frente a la frustración (Farkas-Klein, 2008). Lo anterior, se relaciona con la actitud con la que las madres y los padres afrontan las responsabilidades de cuidado y crianza de sus hijos e hijas y en su capacidad para ofrecerles un entorno físico y psicológico de calidad.
        p También en la disciplina positiva, según Kuppens & Ceulemans (2018) las prácticas parentales juegan un rol importante en el desarrollo de la capacidad de autorregulación emocional de los niños, las niñas y los adolescentes, es decir, con la habilidad para entender sus emociones y la de los demás y adaptar su comportamiento a la demanda del entorno (p. 168).
    p De hecho, Dennis (2006) y Forst, Worthman y Reifel (2008) muestran que la calidad de las emociones que se involucran en la relación padres e hijos influye en la capacidad de los NNA de regular sus emociones, mostrando efectos negativos entre la exposición de reacciones adversas con ansiedad, depresión, tristeza, nerviosismo y rabia (Clark & Watson, 1991). Esto quiere decir que entre mayor involucramiento tengan los padres y las madres con los hijos e hijas, los NNA tendrán un manejo más asertivo de sus emociones y las formas en que expresan estas a las demás personas, brindándoles la posibilidad de aumentar sus habilidades sociales.
    p Para medir prácticas parentales Mi familia utiliza la adaptación en español de la escala de Alabama Parenting Questionnaire (Orpinas, Rico & Martínez-Cox, 2012).
    .row.mb-5
      .col-12.p-5
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema2/img47.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 La emoción (en la regulación emocional), entonces, es considerada como una de las variables psicológicas de más impacto en la vida de los individuos, ya que determina el comportamiento en gran medida. En relación con lo anterior, la regulación emocional se describe como el proceso a través del cual los individuos toman decisiones sobre sus emociones, influenciándolas para experimentar aquellas que les permitan alcanzar metas tanto personales como sociales. Los mecanismos de influencia a través de los cuales se modifican las emociones son denominados estrategias de regulación emocional.
    .row.mb-5.justify-content-center.align-items-center(data-aos="fade-right")
      .col-lg-7(data-aos="fade-left")
        p Finalmente, el vínculo es una “relación, conexión, red de solidaridad y afectos” (ICBF, MEN, 2009, p. 44) que se puede desarrollar con personas, uno mismo, un grupo de individuos, como la familia o la comunidad, el lugar donde se vive o el tiempo en el que se vive (historia). Específicamente, los vínculos se entienden como aquellas relaciones que existen entre las personas, van más allá de los lazos de parentesco que se tengan, ya que representan la unión indispensable que le da soporte y equilibrio a las decisiones y situaciones que se presentan en el curso de la vida de un individuo (ICBF, 2017).
        p Los niños y las niñas requieren un modelo materno y paterno para formar su yo, para consolidar su identidad, para desarrollar sus ideales y aspiraciones (Romero, 2007). Por tanto, lograr la vinculación del padre y la madre toma mayor relevancia para promover el desarrollo integral de los NNA. Cuando los niños, las niñas y los adolescentes se sienten reconocidos, queridos y valorados por sus padres, son capaces de integrar normas y seguridad en proyectos personales coherentes. 
      .col-lg-5.mb-4.mb-lg-0
        figure
          img.img-t(src='@/assets/curso/tema2/img48.png').m-auto
    .row.justify-content-center.align-items-center.mb-5          
      .col-lg-10
        .bg12
          .tarjeta.position-relative.rounded-0.p-4(data-aos="flip-down")
            .row.justify-content-center.align-items-center
              .col-lg-4
                .imagen-absolute4
                  img.img-t.mx-auto(data-aos="zoom-in")(src='@/assets/curso/tema2/img49.svg', alt='')
              .col-lg-8.my-3
                p(data-aos="fade-down") Por otra parte, los vínculos entre padres, madres, niños, niñas y adolescentes son fundamentales en la medida en que permiten “consolidar relaciones protectoras y de cuidado para contribuir al desarrollo afectivo, social y cognitivo de aquellos que están en proceso de formación desde sus primeras etapas de vida, además, los vínculos afectivos serán la base para el establecimiento de relaciones futuras” (ICBF, 2017, p. 9).
    .bg13
      .row.mb-5.justify-content-center.align-items-center(data-aos="fade-right")
        .col-lg-11(data-aos="fade-left")
          p En conclusión, estos instrumentos le permiten a los PAF identificar cuáles son las principales fortalezas con las que cuenta la familia para afrontar situaciones de crisis, constituirse en sistemas resilientes y habilidades que requieren fortalecimiento, en especial aquellas que pueden suponer riesgos para el desarrollo familiar y personal de cada uno de los miembros de la familia, en especial de los niños, las niñas y los adolescentes.
        .col-lg-1.mb-4.mb-lg-0
          figure
            img.img-t(src='@/assets/curso/tema2/img50.svg').mx-auto
    .row.mb-5.justify-content-center.align-items-center(data-aos="fade-right")
      .col-lg-4.mb-4.mb-lg-0
        figure
          img.img-t(src='@/assets/curso/tema2/img51.png').m-auto
      .col-lg-8(data-aos="fade-left")
        p Con el análisis de los instrumentos de medición de habilidades y una lectura integrada con los resultados de los otros instrumentos de diagnóstico se pueden generar, en comunicación con las familias, hipótesis de trabajo y cursos de acción que permitan orientar el acompañamiento familiar psicosocial y brindar una atención diseñada a la medida de sus necesidades y realidades. 
        p La forma como se realice el levantamiento de esta información es vital para el adecuado análisis e interpretación de los resultados. Por esto, es importante no cambiar el orden de las preguntas, mantener el fraseo propuesto en los formularios y sobre todo, no interferir en la respuesta de las familias. Para una adecuada recolección de información a través de estos instrumentos, idealmente deberá generarse un espacio para que cada integrante pueda responder de manera autónoma las preguntas y en caso de dudas, frente a palabras o significado de alguna frase y brindar el acompañamiento requerido. 
    p En casos en los que no sea posible el diligenciamiento autónomo, ya sea por razones de bioseguridad o nivel de comprensión de la persona, será el profesional quien realice en voz alta cada una de las preguntas y las opciones de respuesta, en estos casos y sin interferir con la respuesta, puede hacer lectura del lenguaje corporal para incluirlo entre los componentes del diagnóstico. 
    .bg9.p-2.mb-5
      .row.align-items-center.p-3
        .col-lg-auto
          figure
            img.mb-3(src='@/assets/curso/tema2/img52.svg', style="width: 80px").m-auto
        .col-lg.mb-4.mb-lg-0
          p.mb-0 La siguiente tabla incluye un resumen de los cuatro instrumentos de habilidades del programa Mi familia, sus subescalas, la población a la que van dirigidos, la cantidad de preguntas o ítems y las opciones de respuesta. 
    .row.justify-content-center
      .col-lg-8.col-xl-8
        .titulo-sexto.color-acento-contenido
          h5 Tabla 1 
          span Instrumentos de habilidades del programa Mi familia
        .tabla-a.color-acento-contenido.mb-5 
          table
            thead
              tr
                th Instrumento
                th Subescala o componente
                th ¿A quién se aplica?
                th Cantidad de preguntas o ítems
                th Escala
            tbody
              tr
                th(rowspan="2") Autoeficacia parental
                td Autoeficacia  
                td(rowspan="2") Padres y madres
                td.text-center 7
                td(rowspan="2") 
                  p.mb-0 1-Totalmente en desacuerdo 
                  p.mb-0 2-Bastante en desacuerdo
                  p.mb-0 3-En desacuerdo
                  p.mb-0 4-De acuerdo
                  p.mb-0 5-Bastante de acuerdo
                  p.mb-0 6-Totalmente de acuerdo
              tr
                td Satisfacción 
                td.text-center 10
             
              tr(style="background-color: #F6F6F6")
                th(rowspan="4") Disciplina positiva
                td Parentalidad positiva
                td(rowspan="4") Padres, madres y, niños, niñas y adolescentes entre 12 y 18 años.
                td.text-center 6
                td(rowspan="4") 
                  p.mb-0 1-Nunca
                  p.mb-0 2-Casi nunca
                  p.mb-0 3-A veces
                  p.mb-0 4-A menudo
                  p.mb-0 5-Siempre 

              tr(style="background-color: #F6F6F6")
                td Involucramiento parental 
                td.text-center 10
              tr(style="background-color: #F6F6F6")
                td Bajo monitoreo o supervisión 
                td.text-center 10
              tr(style="background-color: #F6F6F6")
                td Castigo físico
                td.text-center 3
                tr(style="background-color: #F6F6F6")                       
              tr
                th(rowspan="3") Regulación emocional
                td Atención
                td(rowspan="3")
                  p Padres, madres y, niños, niñas y adolescentes entre 12 y 18 años.
                  p * Cuidador principal cuando no esté presente el padre o la madre.
                td.text-center 8
                td(rowspan="3") 
                  p.mb-0 1-Nada de acuerdo
                  p.mb-0 2-Algo de acuerdo
                  p.mb-0 3-Bastante de acuerdo
                  p.mb-0 4-Muy de acuerdo
                  p.mb-0 5-Totalmente de acuerdo
              tr
                td Claridad
                td.text-center 8
              tr
                td Reparación
                td.text-center 8
              tr(style="background-color: #F6F6F6")
                th(rowspan="3") Vinculación
                td Cariño
                td(rowspan="3")
                  p Niños, niñas y adolescentes entre 12 y 18 años.
                td.text-center 5
                td(rowspan="3") 
                  p.mb-0 1-Nunca
                  p.mb-0 2-Casi nunca
                  p.mb-0 3-Muchas veces
                  p.mb-0 4-Siempre
              tr(style="background-color: #F6F6F6")
                td Hostilidad
                td.text-center 7
              tr(style="background-color: #F6F6F6")
                td Hostilidad
                td.text-center 7
              
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
