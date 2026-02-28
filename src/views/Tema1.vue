<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 Montaje audiovisual
    
    .bg-full-width.bg-color-3
      .px-4.px-md-5.py-4
        .row.justify-content-center.align-items-center.mb-5
          .col-lg-3.mb-3.order-lg-2
            figure
              img(src="@/assets/curso/tema1/1.png", data-aos="zoom-in")
          .col-lg-9.order-lg-1
            p El concepto de composición gráfica se refiere a la organización de elementos dentro del espacio visual con el propósito de construir una imagen que transmita una idea de manera sencilla y directa a un público objetivo. Esta premisa mantiene su validez en la creación y edición de imágenes fijas; sin embargo, adquiere un sentido distinto cuando se trata de imágenes en movimiento, donde intervienen factores narrativos y temporales.
            .bg-color-1.px-5.py-4
              p.mb-0 En el ámbito audiovisual, suele emplearse indistintamente los términos edición y montaje. No obstante, desde la teoría del lenguaje audiovisual se establece una diferencia conceptual relevante. La palabra montage, de origen francés, alude a montar o superponer elementos; sin embargo, el montaje se vincula con el proceso narrativo de articulación de significados, mientras que la edición corresponde principalmente a un procedimiento técnico.

        p.mb-5 El montaje audiovisual constituye, por tanto, la fase técnica y narrativa final del producto audiovisual. Aunque se concreta en la etapa de posproducción, su sentido queda previamente definido desde la elaboración del guion, ya que responde a las intenciones del emisor y a las capacidades interpretativas del receptor.

        .row.justify-content-center
          .col-lg-10
            .bg-color-2.mb-5(data-aos="fade-up")
              .row.justify-content-center.align-items-center
                .col-lg-auto
                  figure
                    img(src='@/assets/curso/tema1/2.png', alt='')
                .col-lg
                  .p-4
                    p.mb-0(data-aos="fade-up") En el tratamiento de imágenes fijas, lo habitual es hablar de edición de imágenes; en cambio, el montaje fotográfico o fotomontaje se entiende como un resultado derivado del proceso de edición. Por ello, resulta pertinente considerar ambas definiciones para comprender sus alcances y diferencias.
        
        p.mb-5 A continuación, se presentan las definiciones fundamentales que orientan este apartado:

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-lg-5
        SlyderA(tipo="b").bg-color-white.p-4.tarjeta
          .row.justify-content-center.align-items-center.p-3.p-lg-4
            .col-lg-5.mb-3.mb-lg-0.order-lg-2
              figure
                img(src='@/assets/curso/tema1/3.png', alt='Imagen de acompañamiento')
            .col-lg-7.mb-4.mb-md-0.order-lg-1
              h4 Montaje
              p.mb-0 Conjunto de relaciones espacio-temporales creadas mediante la combinación y duración de fragmentos, que permiten articular un mensaje audiovisual con fluidez, ritmo, coherencia y expresión propia, en función de las intenciones del emisor y las expectativas del receptor.
          .row.justify-content-center.align-items-center.p-3.p-lg-4
            .col-lg-5.mb-3.mb-lg-0.order-lg-2
              figure
                img(src='@/assets/curso/tema1/4.png', alt='Imagen de acompañamiento')
            .col-lg-7.mb-4.mb-md-0.order-lg-1
              h4 Edición
              p.mb-0 Proceso técnico que permite manipular la imagen capturada o creada para mejorarla, adaptarla o ajustarla según necesidades específicas de producción.
    
    p.mb-5 En síntesis, mientras la edición se centra en la manipulación técnica del material audiovisual, el montaje implica una construcción narrativa que organiza los fragmentos en una estructura significativa. Ambos procesos son complementarios y esenciales en la producción audiovisual.

    separador
    
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="flip-up")
      h2 1.1 Edición de imagen
    
    .bg-full-width.bg-color-3
      .px-4.px-md-5.py-4
        .row.justify-content-center.align-items-center.mb-5
          .col-lg-4.mb-3.order-lg-2
            figure
              img(src="@/assets/curso/tema1/5.png", data-aos="zoom-in")
          .col-lg-8.order-lg-1
            .bg-color-4.px-5.py-4.mb-3
              p.mb-0 Cuando se aborda la edición digital de imágenes, intervienen tres componentes fundamentales: una imagen, un terminal computarizado (equipo de escritorio, portátil, tablet, celular u otro dispositivo móvil) y un software especializado. Este proceso permite transformar, optimizar o adaptar la imagen según las necesidades comunicativas, técnicas o estéticas del proyecto.
            p Antes de profundizar en el proceso de edición, es necesario comprender qué es una imagen digital, cuáles son sus características y qué tipos existen, pues de esta clasificación dependerá su tratamiento técnico. Entre los elementos vinculados al proceso de captura y digitalización de la imagen se encuentran:

            .row.justify-content-center.mb-3
              .col-lg-3.text-center
                .bg-color-5.p-4.h-100
                  h5.mb-0 Imagen
              .col-lg-3.text-center
                .bg-color-5.p-4.h-100
                  h5.mb-0 Objetivo
              .col-lg-3.text-center
                .bg-color-5.p-4.h-100
                  h5.mb-0 Filtro infrarrojo
              .col-lg-3.text-center
                .bg-color-5.p-4.h-100
                  h5.mb-0 Filtro RGB
            
            .row.justify-content-center
              .col-lg-3.text-center
                .bg-color-5.p-4.h-100
                  h5.mb-0 Matriz CCD
              .col-lg-3.text-center
                .bg-color-5.p-4.h-100
                  h5.mb-0 Conversor ADC
              .col-lg-3.text-center
                .bg-color-5.p-4.h-100
                  h5.mb-0 Dígitos del sistema binario

        p.mb-5 Estos componentes participan en la conversión de la información lumínica en datos numéricos que posteriormente pueden ser procesados digitalmente.

        .titulo-con-imagen.mb-5(data-aos="fade-right")
          .titulo-con-imagen__fondo
            img.titulo-con-imagen__imagen(src="@/assets/componentes/1.png")
            h3.titulo-con-imagen__texto La imagen digital
        
        p Según la <b>Real Academia Española</b> (s. f.), una imagen es toda forma o figura percibida por el sentido de la vista.
        p.mb-5 Desde el ámbito tecnológico, una <b>imagen digital o gráfico digital</b> se define como una representación bidimensional construida a partir de una matriz numérica, generalmente expresada en sistema binario (unos y ceros). Esta información se almacena en la memoria de un sistema informático y posteriormente es interpretada por el dispositivo para su representación en pantalla o su impresión mediante periféricos de salida.

        div.bg-color-6.p-3.d-inline-flex.tarjeta.mb-3
          h4.mb-0 Tipos de imágenes digitales
        
        p.mb-5 Por su estructura, las imágenes digitales se clasifican principalmente en dos tipos: 
    
    .tarjeta--container.row.mb-5
      //- .tarjeta debe ir acompañado de una de una de estas clases => 
      //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
      //- estas clases tambien tienen un modificador --borde
      .col-md.tarjeta.color-primario.bg-color-7.p-5
        .row.justify-content-center.mb-5
          .col-10
            figure
              img(src='@/assets/curso/tema1/6.png', alt='Texto que describa la imagen')
          
        h2.mb-5 Imagen en mapa de bits (<em>raster</em>)
        p Representa una rejilla rectangular de píxeles o puntos de color. Se obtiene mediante dispositivos como cámaras digitales o escáneres. Cada píxel (<em>picture element</em>) constituye la unidad mínima de la imagen digital. Su calidad depende de la resolución.

      //- .tarjeta debe ir acompañado de una de una de estas clases => 
      //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
      //- estas clases tambien tienen un modificador --borde
      .col-md.tarjeta.color-acento-botones.bg-color-8.p-5
        .row.justify-content-center.mb-5
          .col-10
            figure
              img(src='@/assets/curso/tema1/7.svg', alt='Texto que describa la imagen')
          
        h2.mb-5 Imagen vectorial
        p Está compuesta por fórmulas matemáticas que definen líneas, curvas y formas geométricas. Puede ampliarse sin pérdida de calidad. Es frecuente en logotipos, tipografías y gráficos técnicos.

    p.mb-5 De acuerdo con Ordóñez (2005), una imagen en mapa de bits es una estructura de datos que representa una rejilla rectangular de píxeles. Cada píxel es una unidad mínima sin dimensión física concreta y constituye la base de fotografías, fotogramas de video y gráficos digitales.

    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/1.png")
        h3.titulo-con-imagen__texto Elementos de la imagen digital
    
    p.mb-5 Una vez comprendidos los tipos de imagen, es pertinente abordar los elementos que determinan su construcción y posterior edición.

    div.bg-color-6.p-3.d-inline-flex.tarjeta.mb-3
      h4.mb-0 Formatos
    
    p Los formatos corresponden a la forma codificada que adquiere la imagen al almacenarse digitalmente. Definen la manera en que se guardan los píxeles y determinan aspectos como calidad, peso del archivo y compatibilidad.

    p.mb-5 Antes de la tabla, se sintetizan algunos formatos frecuentes para imágenes en mapa de bits:

    .row.mb-5.justify-content-center
      .col-sm-6.col-lg-4.mb-4.mb-lg-0(data-aos="fade-up")
        //- .tarjeta--boton debe ir acompañado de una de una de estas clases => 
        //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
        //- estas clases tambien tienen un modificador --borde
        .tarjeta--boton.bg-color-9.h-100.p-4
          .row.justify-content-center.mb-3
            .col-4
              figure
                img(src='@/assets/curso/tema1/8.svg', alt='Texto que describa la imagen')

          h3.mb-4.text-center BMP
          p.text-center Desarrollado para sistemas operativos Microsoft. Soporta hasta 24 <em>bits</em> por píxel. Genera archivos de gran tamaño, por lo que no es adecuado para páginas web.

      .col-sm-6.col-lg-4.mb-4.mb-lg-0(data-aos="fade-down")
        //- .tarjeta--boton debe ir acompañado de una de una de estas clases => 
        //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
        //- estas clases tambien tienen un modificador --borde
        .tarjeta--boton.bg-color-9.h-100.p-4
          .row.justify-content-center.mb-3
            .col-4
              figure
                img(src='@/assets/curso/tema1/9.svg', alt='Texto que describa la imagen')

          h3.mb-4.text-center TIFF
          p.text-center Utilizado para impresión y alta resolución. Soporta modelo de color CMYK y hasta 16 bits de profundidad de color. Prioriza calidad sobre tamaño. Es empleado por editoriales y medios impresos.
    
    p.mb-5 En consecuencia, la elección del formato depende del uso final del archivo, la calidad requerida y el medio de distribución.

    div.bg-color-6.p-3.d-inline-flex.tarjeta.mb-3
      h4.mb-0 Resolución de la imagen
    
    p.mb-5 La resolución se relaciona con el tamaño y la densidad de píxeles que conforman la imagen. Este concepto involucra tres dimensiones:
        
    .row.mb-5.justify-content-center
      .col-sm-6.col-lg-4.mb-4.mb-lg-0(data-aos="fade-up")
        //- .tarjeta--boton debe ir acompañado de una de una de estas clases => 
        //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
        //- estas clases tambien tienen un modificador --borde
        .tarjeta--boton.bg-color-2.h-100.p-4
          .row.justify-content-center.mb-3
            .col-10
              figure
                img(src='@/assets/curso/tema1/10.png', alt='Texto que describa la imagen')

          h3.mb-4.text-center Tamaño en píxeles
          p.text-center Número de filas y columnas que conforman la imagen. Determina el total de píxeles.

      .col-sm-6.col-lg-4.mb-4.mb-lg-0(data-aos="fade-down")
        //- .tarjeta--boton debe ir acompañado de una de una de estas clases => 
        //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
        //- estas clases tambien tienen un modificador --borde
        .tarjeta--boton.bg-color-2.h-100.p-4
          .row.justify-content-center.mb-3
            .col-10
              figure
                img(src='@/assets/curso/tema1/11.png', alt='Texto que describa la imagen')

          h3.mb-4.text-center Tamaño informático
          p.text-center Expresado en <em>bytes, kilobytes</em> o <em>megabytes</em>. Depende del número de píxeles y de la cantidad de información asignada a cada uno.
      .col-sm-6.col-lg-4.mb-4.mb-lg-0(data-aos="fade-up")
        //- .tarjeta--boton debe ir acompañado de una de una de estas clases => 
        //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
        //- estas clases tambien tienen un modificador --borde
        .tarjeta--boton.bg-color-2.h-100.p-4
          .row.justify-content-center.mb-3
            .col-10
              figure
                img(src='@/assets/curso/tema1/12.png', alt='Texto que describa la imagen')

          h3.mb-4.text-center Tamaño de salida
          p.text-center Dimensión física que ocupará la imagen al imprimirse. El editor define cuántos píxeles se reproducen por centímetro o pulgada.
          
    p.mb-5 Según Fernández (2005), la resolución de una imagen digital se expresa multiplicando su anchura por su altura en píxeles. Por ejemplo, una imagen de 1200 × 1200 píxeles equivale a 1.440.000 píxeles, es decir, aproximadamente 1,4 megapíxeles (Mp). Conviene recordar que 1 megapíxel equivale a 1024 × 1024 píxeles.

    div.bg-color-6.p-3.d-inline-flex.tarjeta.mb-3
      h4.mb-0 Modos de color
    
    p.mb-5 Además del formato y la resolución, el color constituye un elemento esencial en la imagen digital. Técnicamente, se relaciona con la profundidad de color, es decir, la cantidad de bits necesarios para representar el color de cada píxel. En términos generales, se asocia al modelo de color utilizado. A continuación, se sintetizan los principales modos de color empleados en multimedia:

    .bg-full-width.bg-fondo-1
      .px-4.px-md-5.py-4
        SlyderF.mb-5(columnas="col-lg-6 col-xl-4")
          .tarjeta.bg-color-white.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src='@/assets/curso/tema1/13.png' alt='AvatarTop')
            h2.text-center RGB (<em>Red, Green, Blue</em>)
            p.text-center Modelo aditivo utilizado en pantallas y dispositivos electrónicos. Combina luz roja, verde y azul.

          .tarjeta.bg-color-white.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src='@/assets/curso/tema1/14.png' alt='AvatarTop')
            h2.text-center CMYK (<em>Cian, Magenta, Yellow, Black</em>)
            p.text-center Modelo sustractivo empleado en impresión.

          .tarjeta.bg-color-white.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src='@/assets/curso/tema1/15.png' alt='AvatarTop')
            h2.text-center HSB (<em>Hue, Saturation, Brightness</em>)
            p.text-center Define el color según tono, saturación y brillo.
          
          .tarjeta.bg-color-white.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src='@/assets/curso/tema1/16.png' alt='AvatarTop')
            h2.text-center Escala de grises
            p.text-center Imagen monocromática con hasta 256 niveles de negro.

          .tarjeta.bg-color-white.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src='@/assets/curso/tema1/17.png' alt='AvatarTop')
            h2.text-center <em>Lab</em>
            p.text-center Compuesto por un canal de luminosidad (L) y dos canales cromáticos: A (verde–rojo) y B (azul–amarillo) (M., 2014).

          .tarjeta.bg-color-white.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src='@/assets/curso/tema1/18.png' alt='AvatarTop')
            h2.text-center Mapa de <em>bits</em> (modo monocromático)
            p.text-center Utiliza únicamente blanco o negro para representar los píxeles.
          
          .tarjeta.bg-color-white.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src='@/assets/curso/tema1/19.png' alt='AvatarTop')
            h2.text-center Color indexado
            p.text-center Limita la imagen a un máximo de 256 colores (M., 2014).

        p.mb-5 La edición de imagen implica comprender la naturaleza digital del archivo, su estructura, resolución, formato y modelo de color. Estos elementos determinan tanto la calidad final como las posibilidades de manipulación técnica en entornos digitales e impresos.

    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/1.png")
        h3.titulo-con-imagen__texto Edición de la imagen
    
    p.mb-5 La edición de la imagen se define como:

    .row.justify-content-center
      .col-lg-10
        .bg-color-1.mb-5(data-aos="fade-up")
          .row.justify-content-center.align-items-center
            .col-lg-auto
              figure
                img(src='@/assets/curso/tema1/20.png', alt='')
            .col-lg

                .bloque-texto-c.p-4
                  i.fas.fa-quote-right
                  p.mb-2 Es la manipulación, a través de programas de edición gráfica, de imágenes capturadas o previamente diseñadas, con la intención de reforzar conceptos o mensajes mediante la modificación del color, formas, composición, contrastes, estilo, etcétera. La edición para hacer collages o mejorar la calidad de la imagen es también un recurso de gran valor en publicidad; gracias a ello, se pueden exagerar o disminuir rasgos o elementos de todo tipo
                  span <b>(Viveros, 2005).</b>
    
    p.mb-5 El tratamiento se realiza mediante un editor de imágenes, es decir, un software especializado que proporciona herramientas, efectos, opciones de ajuste y posibilidades de modificación del formato al momento de guardar el archivo.

    div.bg-color-6.p-3.d-inline-flex.tarjeta.mb-3
      h4.mb-0 Aspectos de la edición de imágenes
    
    p.mb-5 La edición digital integra dimensiones creativas y técnicas que se complementan en la construcción del mensaje visual.

    .tarjeta--container.row.mb-5
      //- .tarjeta debe ir acompañado de una de una de estas clases => 
      //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
      //- estas clases tambien tienen un modificador --borde
      .col-md.tarjeta.color-primario.bg-color-7.p-5
        .row.justify-content-center.mb-5
          .col-10
            figure
              img(src='@/assets/curso/tema1/21.png', alt='Texto que describa la imagen')
          
        h2.mb-5 Aspectos creativos
        p Se relacionan con la intención conceptual y semiótica del producto. Determinan el sentido-significación que se desea transmitir, la función de la imagen (principal o complementaria), su carácter ilustrativo o descriptivo y el estilo (realismo, figuración, entre otros).

      //- .tarjeta debe ir acompañado de una de una de estas clases => 
      //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
      //- estas clases tambien tienen un modificador --borde
      .col-md.tarjeta.color-acento-botones.bg-color-8.p-5
        .row.justify-content-center.mb-5
          .col-10
            figure
              img(src='@/assets/curso/tema1/22.png', alt='Texto que describa la imagen')
          
        h2.mb-5 Aspectos técnicos
        p Comprenden el manejo de herramientas del software, ajustes de color, iluminación, contraste, composición, formato y exportación del archivo final.
    
    p.mb-5 Según Viveros (2005), lo conceptual incide directamente en la significación del producto. Estos aspectos fueron desarrollados en el Componente Formativo Diseño para contenidos digitales, en el apartado de Diseño, y se aplican tanto en la creación como en la captura o edición de imágenes digitales. Dentro de este marco se destacan dos procesos fundamentales: la composición digital y el retoque digital.

    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-lg-5
        SlyderA(tipo="b").bg-color-white.p-4.tarjeta
          .row.justify-content-center.align-items-center.p-3.p-lg-4
            .col-lg-5.mb-3.mb-lg-0.order-lg-2
              figure
                img(src='@/assets/curso/tema1/23.png', alt='Imagen de acompañamiento')
            .col-lg-7.mb-4.mb-md-0.order-lg-1
              h4 Composición digital
              p.mb-0 También denominada composición de efectos visuales, consiste en la creación de imágenes digitales mediante la manipulación y combinación de elementos provenientes de diferentes fuentes o herramientas digitales. Su objetivo es generar piezas homogéneas que conserven unidad formal y conceptual, independientemente de que los elementos integrados sean reales o construidos digitalmente.
          .row.justify-content-center.align-items-center.p-3.p-lg-4
            .col-lg-5.mb-3.mb-lg-0.order-lg-2
              figure
                img(src='@/assets/curso/tema1/24.png', alt='Imagen de acompañamiento')
            .col-lg-7.mb-4.mb-md-0.order-lg-1
              h4 Retoque digital
              p.mb-0 Aunque implica conocimiento técnico de las herramientas del software, el retoque digital posee igualmente una dimensión creativa. Permite modificar escenarios, iluminación, color y percepción para construir una nueva imagen o reforzar significados específicos. De esta manera, el retoque no solo optimiza la calidad técnica, sino que también potencia la intención comunicativa.

    div.bg-color-6.p-3.d-inline-flex.tarjeta.mb-3
      h4.mb-0 Herramientas para la edición
    
    p.mb-5 Las herramientas de edición corresponden a los diferentes programas de tratamiento de imagen disponibles en el mercado. Estas aplicaciones se clasifican según el entorno en el que operan: computador, dispositivos móviles o plataformas en línea.

    .row.mb-5.justify-content-center
      .col-sm-6.col-lg-4.mb-4.mb-lg-0(data-aos="fade-up")
        //- .tarjeta--boton debe ir acompañado de una de una de estas clases => 
        //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
        //- estas clases tambien tienen un modificador --borde
        .tarjeta--boton.bg-color-2.h-100.p-4
          .row.justify-content-center.mb-3
            .col-10
              figure
                img(src='@/assets/curso/tema1/25.png', alt='Texto que describa la imagen')

          h3.mb-4.text-center Para computador
          p.text-center Mayor cantidad de funcionalidades y control avanzado. Requieren instalación y ocupan más espacio en disco. Exigen conocimientos técnicos y experiencia en diseño.

      .col-sm-6.col-lg-4.mb-4.mb-lg-0(data-aos="fade-down")
        //- .tarjeta--boton debe ir acompañado de una de una de estas clases => 
        //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
        //- estas clases tambien tienen un modificador --borde
        .tarjeta--boton.bg-color-2.h-100.p-4
          .row.justify-content-center.mb-3
            .col-10
              figure
                img(src='@/assets/curso/tema1/26.png', alt='Texto que describa la imagen')

          h3.mb-4.text-center Para celulares
          p.text-center Diseñadas para sistemas operativos como Android e iOS. Ocupan menos memoria y permiten edición inmediata, aunque con funciones más limitadas.
      .col-sm-6.col-lg-4.mb-4.mb-lg-0(data-aos="fade-up")
        //- .tarjeta--boton debe ir acompañado de una de una de estas clases => 
        //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
        //- estas clases tambien tienen un modificador --borde
        .tarjeta--boton.bg-color-2.h-100.p-4
          .row.justify-content-center.mb-3
            .col-10
              figure
                img(src='@/assets/curso/tema1/27.png', alt='Texto que describa la imagen')

          h3.mb-4.text-center Editores en línea
          p.text-center Funcionan desde el navegador sin descarga previa. Muchos ofrecen versiones gratuitas con funciones restringidas.
          
    .bg-full-width.bg-color-3
      .px-4.px-md-5.py-4
        p.mb-5 A continuación, se relacionan algunos ejemplos representativos:
 
</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    mostrarIndicadorTarjetaAudio: true,
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
