<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Alistamiento de pedidos
    p.mb-5 La preparación de pedidos es la actividad que acondiciona las mercancías y objetos postales, de acuerdo con características, clasificación de los productos y requerimientos de los clientes, para que sean organizados en forma de pedidos. Estos pueden ser enviados al cliente final, al centro de distribución o a otros puntos de despacho.
      br
      br
      |En general, en el proceso de preparación de pedidos se desarrollan las siguientes tareas:
    .row.mb-5.justify-content-center
      .col-lg-3
        img(src='@/assets/curso/1.svg', alt='Texto que describa la imagen' style='width: 190px').mb-3.m-auto.hoverScale
        .text-center: p Identificación del pedido (Nota de salida), con todos los datos puntuales del pedido, cliente y destino.
      .col-lg-3
        img(src='@/assets/curso/2.svg', alt='Texto que describa la imagen' style='width: 190px').mb-3.m-auto.hoverScale
        .text-center: p Condiciones logísticas para la entrega, incluyendo el tipo de vehículo requerido.
      .col-lg-3
        img(src='@/assets/curso/3.svg', alt='Texto que describa la imagen' style='width: 190px').mb-3.m-auto.hoverScale
        .text-center: p Información sobre la ruta y condiciones relevantes de acceso al lugar.
      .col-lg-3
        img(src='@/assets/curso/4.svg', alt='Texto que describa la imagen' style='width: 190px').mb-3.m-auto.hoverScale
        .text-center: p Asignación de identificación (consecutivo) para hacer seguimiento de la ubicación e informar así al cliente.
    p.mb-5 Tenga en cuenta los siguientes aspectos clave, en el inicio del proceso de alistamiento de pedidos:
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8
        LineaTiempoD.color-acento-contenido
          .row(numero="1" titulo="Tipo de producto").align-items-center
            .col-md-6
              figure
                img(src='@/assets/curso/5.png', alt='Texto que describa la imagen')
            .col-md-6.mb-4.mb-md-0
              p Para dar inicio al alistamiento de pedidos, es necesario tener conocimiento (por escrito) del tipo de producto que se requiere; lo cual se realiza teniendo en mano la orden de pedido.
          .row(numero="2" titulo="Líneas de pedido").align-items-center
            .col-md-6
              figure
                img(src='@/assets/curso/6.png', alt='Texto que describa la imagen')
            .col-md-6.mb-4.mb-md-0
              p Regularmente, se preparan diferentes líneas de pedido, dependiendo de condiciones como: a) Requisitos del cliente, b) Fechas de entrega, c) Destino, d) Características de la mercancía y volumen, e) <em>Picking</em> f) Tipo de consolidación de pedidos.
          .row(numero="3" titulo="Objetivos de cumplimiento y calidad").align-items-center
            .col-md-6
              figure
                img(src='@/assets/curso/7.png', alt='Texto que describa la imagen')
            .col-md-6.mb-4.mb-md-0
              p Lo anterior, con el fin de que los objetos postales o mercancías salgan del almacén y lleguen en perfecto estado y condiciones de entrega y transporte, acordadas con el cliente.
    #t_1_1.titulo-segundo.color-acento-contenido
      h2 1.1 Productos     
    .row.justify-content-center.mb-5
      .col-lg-10
        .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image':`url(${require('@/assets/curso/8.jpg')})`}"
          )
          .bloque-texto-g__texto.p-5
            p.mb-0 Un producto es el <b>“resultado de un conjunto de actividades mutuamente relacionadas o que interactúan, las cuales transforman elementos de entrada en resultados”</b> (ICONTEC, 2005).  Se puede definir que, para el sector de servicios postales, las entradas son aquellas mercancías y objetos encomendados para enviar o recibir en el territorio nacional o en el exterior, momento en el cual se convierte en un producto.
    p.mb-3 Dicho producto debe recorrer una serie de actividades como: recepción, clasificación, consolidación, embalaje, transporte y entrega, siempre sujeto a verificación o reporte de inconsistencias.
    p.mb-5 Algunas generalidades, de suma importancia, que se deben tener en cuenta, son:
    ImagenInfografica.color-acento-contenido.dots-1.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/9.svg', alt='Texto que describa la imagen')
      .tarjeta.color-primario.p-3(x="38%" y="19%" numero="1")
        p De una adecuada clasificación de productos depende el éxito en la cadena logística, para saber qué productos requieren almacenamiento y la forma de distribución.
      .tarjeta.color-primario.p-3(x="61%" y="20%" numero="2")
        p Así mismo, el ciclo de vida del producto influye en la toma de decisiones dentro de la cadena logística, pues el producto está compuesto por una parte física y otra intangible…
      .tarjeta.color-primario.p-3(x="76%" y="30%" numero="3")
        p El tema físico hace referencia a las variables: peso, volumen, forma y durabilidad, mientras que lo intangible respecta a información y comunicación para cubrir las expectativas del cliente.
      .tarjeta.color-primario.p-3(x="66%" y="55%" numero="4")
        p Las características de los productos permiten gestionar de una forma más efectiva los inventarios, almacenamiento y el alistamiento de pedidos.
      .tarjeta.color-primario.p-3(x="72%" y="74%" numero="5")
        p <b>Peso–volumen:</b> son medidas directamente proporcionales a los costos de almacenamiento y transporte.  Necesidades de equipos de manipulación y transporte.  Cálculo de la densidad del producto.
      .tarjeta.color-primario.p-3(x="56%" y="73%" numero="6")
        p <b>Valor-peso:</b> utilizada cuando el valor del producto se expresa en relación con el peso; diferente de los objetos valiosos como joyas, electrodomésticos, etc.
      .tarjeta.color-primario.p-3(x="27%" y="69%" numero="7")
        p <b>Sustituible:</b> cuando el cliente está dispuesto a tomar el servicio de otra marca, porque la primera no está disponible
      .tarjeta.color-primario.p-3(x="24%" y="35%" numero="8")
        p <b>Riesgos:</b> características del producto como perecederos, inflamables, de valor o con facilidad de robo.  Por tanto, son de especial cuidado durante el manejo y transporte.
    h4.titulo-cuarto Normativa
    .row.justify-content-center.align-items-center.mb-5.mt-5
      .col-lg-4
          img(src='@/assets/curso/10.png', alt='Texto que describa la imagen')
      .col-lg-7
        p En el 2006 se elaboró el <b>PIDEP</b> (Plan Integral de Reforma y Desarrollo Postal), buscando apoyar la reforma del sector postal colombiano, en el cual se establecieron cuatro componentes fundamentales: el Servicio Postal Universal (SPU), la política sectorial, la reforma legal y la transformación del operador postal. 
    p.mb-5 El desarrollo de este plan trajo consigo, eventualidades importantes tales como:
    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta acordion__normal")
      .row(titulo="Estructuración y aprobaciones de leyes")
        .col-md-6.mb-4.mb-md-0.ps-5.ms-3
          p Estructuración y aprobación de la Ley 1369 de 2009, la cual estableció el régimen legal de los servicios postales y los determinó como servicios públicos. 
        .col-md-5
          figure.img-rounded
            img(src='@/assets/curso/11.jpg', alt='Texto que describa la imagen')
      .row(titulo="Establecimiento de condiciones generales")
        .col-md-6.mb-4.mb-md-0.ps-5.ms-3
          p Expedición del Decreto 223 de 2014, que estableció las condiciones de prestación de los servicios comprendidos en el SPU y, a su vez, a los diferentes Decretos reglamentarios de la Ley 1369 de 2009; hoy en día compilados en el Decreto único reglamentario del sector TIC (Decreto 1078 de 2015). 
        .col-md-5
          figure.img-rounded
            img(src='@/assets/curso/12.jpg', alt='Texto que describa la imagen')
      .row(titulo="Marco normativo general").justify-content-center
        .col-md-12.mb-4.mb-md-4.ps-5.ms-3
          p Estas normas se constituyen en el actual marco normativo general para la prestación de los servicios postales, bajo los principios de calidad, eficiencia y universalidad en todo el territorio nacional.
          br
          br
          | Ejemplo codificación producto ESCOBAS según guía Colombia Compra eficiente:
        .col-md-8
          figure
            img(src='@/assets/curso/13.svg', alt='Texto que describa la imagen')
      .row(titulo="Normativa para productos").justify-content-center
        .col-md-12.mb-4.mb-md-4.ps-5.ms-3
          p En el año 2011, por medio del Decreto Ley 4170 el Gobierno Nacional creó el Sistema Colombia Compra eficiente, a través de la Agencia Nacional de Contratación Pública; uno de los propósitos es implementar normas en busca de la efectividad entre la oferta y la demanda en el mercado y criterios de racionalización normativa.  
          br
          br
          | Estructura lógica por segmentos específicos
        .col-md-6
          figure
            img(src='@/assets/curso/14.svg', alt='Texto que describa la imagen').mb-3
            p Nota: tomado de Guía para la codificación de bienes y servicios de acuerdo con el código estándar de productos y servicios de Naciones Unidas, V.14.080.  – Colombia Compra Eficiente
      .row(titulo="Unificación de criterios").justify-content-center
        .col-md-12.mb-4.mb-md-4.ps-5.ms-3
          p Con el ánimo de unificar criterios, se publica la Guía para la codificación de bienes y servicios de acuerdo con el código estándar de productos y servicios de Naciones Unidas, V.14.080. –UNSPSC; el cual estandariza la codificación de bienes y servicios, para fines comerciales de compras y adquisiciones.
        .col-md-10
          figure
            img(src='@/assets/curso/15.svg', alt='Texto que describa la imagen')
    .row.mb-5.justify-content-center
      .col-md-8.mb-5.mb-lg-0
        .tarjeta-avatar.w-100(style='width: 100px')
          img(src='@/assets/curso/16.svg' alt='AvatarTop' style='width: 130px')
          
          .tarjeta.color-acento-botones.w-100.rounded-0
            .text-white.p-4
              p.text-center Si se desea ahondar en los aspectos más relevantes sobre la normativa asociada, se le recomienda explorar la Guía para codificación de bienes y servicios.
    h4.titulo-cuarto.mb-5 Clasificación
      .row.justify-content-center.align-items-center.mb-5.mt-5
        .col-lg-4
            img(src='@/assets/curso/17.png', alt='Texto que describa la imagen')
        .col-lg-7
          p Clasificar los productos es una pieza importante en la gestión de pedidos; requiere de atención y claridad en la información para no cometer errores. Una correcta clasificación beneficia la gestión de pedidos porque ayuda a conocer y controlar la mercancía postal del almacén, permite implementar procesos automatizados que generen información precisa y en tiempo real, para la toma de decisiones, mejora del control de los inventarios y la clasificación de los pedidos.
    p.mb-5 Todo producto debe cumplir un ciclo de vida, cuyas etapas están enmarcadas desde el punto de vista comercial, inicia con el lanzamiento del producto al mercado hasta la adquisición por parte de los consumidores, en este caso clientes.
    .row.mb-5
      .col-lg-4
        .tarjeta.rounded-0.bg--a-1.p-4.d-flex.flex-column.justify-content-center.h-100.hoverScale2
          img(src='@/assets/curso/18.svg' style='width: 131px').mx-auto
          h4.text-center ¡Atención!
          p.text-center Conocer que los productos y servicios cumplen un ciclo de vida, permite identificar puntos de control requeridos para entregar lo acordado, en el tiempo establecido y bajo las condiciones pactadas.
      .col-lg-4
        .tarjeta.rounded-0.bg--a-1.p-4.d-flex.flex-column.justify-content-center.h-100.hoverScale2
          img(src='@/assets/curso/19.svg' style='width: 131px').mx-auto
          h4.text-center ¡Importante!
          p.text-center En el sector logística es muy difícil encontrar bodegas o centros de distribución que almacenen todos los tipos de producto existentes en el mercado; unas empresas se dedican a fabricar y otras al almacenamiento y/o comercialización.
      .col-lg-4
        .tarjeta.rounded-0.bg--a-1.p-4.d-flex.flex-column.justify-content-center.h-100.hoverScale2
          img(src='@/assets/curso/20.svg' style='width: 131px').mx-auto
          h4.text-center ¡Recuerde!
          p.text-center Entre las empresas dedicadas al almacenamiento y/o comercialización hay algunas que se dedican sólo a una gama de productos, mientras otras comercializan gran variedad de artículos.
    p.mb-5 La clasificación de productos se puede establecer de acuerdo a los siguientes criterios:
    .titulo-sexto.color-primario
      h5 Tabla 6
      span Clasificación de los productos (mercancías) de acuerdo a sus características
    .tabla-a.color-secundario.mb-5
      table
        thead.text-white
          tr.bg-blue
            th CRITERIO (según)
            th CLASIFICACIÓN
            th EJEMPLO
        tbody
          tr
            td(rowspan='3') Estado Físico: permite conocer cómo manipular la mercancía, dónde almacenarlas o cómo transportarlas; según la forma de envasado.
            td Sólidos: se subdividen en gráneles, productos compactados y animales vivos.
            td Minerales, muebles, Agricola (trigo, arroz, azucar)
          tr
            td Líquido: se considera un producto a granel cuando no está envasado.
            td Estables: destinados a la alimentación (refrescos, leche, zumos...)
              br
              |Inestables: aquellos que por su composición química
              br
              |cambian su estado físico (nitroglicerina)
          tr
            td Gaseosos: productos que se utilizan generalmente en la industria y tienen requisitos específicos para el almacenamiento.
            td Gas para neveras<br>Extintores
          tr
            td(rowspan='2') Propiedades:  influyen directamente en las necesidades de conservación y mantenimiento de los productos.
            td Duraderos: son aquellos que no tienen fecha de caducidad y se almacenan sin tener un orden prioritario.  Esta propiedad es importante al momento de escoger el transporte adecuado para la carga.
            td Ropa de vestir, zapatos, textil para
              br
              |el hogar, artículos de limpieza.
              br
              |El almacenaje de estos productos
              br
              |es por gamas, familias, modelos, tallas, etcétera, no mezclando unas con otras.
          tr
            td Perecederos: son aquellos productos cuya durabilidad están limitados por la fecha de caducidad o consumo. Necesitan condiciones especiales de almacenamiento.
            td Productos congelados, productos frescos, productos que se conservan a temperatura ambiente.
          tr
            td Grado de peligrosidad: clasificación establecida por la ONU o SGA (Sistema Globalmente Armonizado).
            td Materiales y Objetos explosivos.
              br
              |Gases comprimidos, licuados o disueltos bajo presión.
              br
              |Líquidos y sólidos inflamables.
              br
              |Comburentes, Tóxicos, Radioactivas, Corrosivas.
            td Ejemplo: oxígeno, Nitrógeno.  Estos productos necesitan cuidados especiales de manipulación, transporte y almacenamiento.
          tr
            td(rowspan='4') Unidad de Medida: aquellos productos medibles atendiendo la capacidad como litros, longitud, superficie, peso. Y de esta forma calcular el espacio que van a ocupar y establecer el número de envases, cajas, el volumen, unidad de carga, etc.
            td Longitud
            td Listones de madera (metros)
          tr
            td Superficie
            td Lamina de triplex conglomerado (metros cuadrados)
          tr
            td Peso
            td Un kilogramo de tierra
          tr
            td Capacidad
            td Liquidos en metros cúbicos
          tr
            td(rowspan='3') Rotación de Salida:  en función de la rotación, ésta mercancía debe ubicarse en un lugar MAS o Menos accesible en el almacenamiento.  La alta rotación tienen un ritmo elevado y baja, apenas tienen movimiento.
            td Alta rotación
            td Productos de consumo
          tr
            td Media rotación
            td Juguetería
          tr
            td Baja rotación
            td Productos de lujo
    #t_1_2.titulo-segundo.color-acento-contenido
      h2 1.2 Planificación de pedidos 
    p.mb-5 En los centros de distribución, la fase de preparación es una de las más relevantes; aquí se asegura que el producto sea el correcto, que su preparación y embalaje sean los adecuados para llegar en perfectas condiciones a su destino final.
    br
    br
    .row.justify-content-center.mb-5
      .col-lg-10
        .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.position-relative
          .bloque-texto-g__img(
            :style="{'background-image':`url(${require('@/assets/curso/21.jpg')})`}"
          )
            .imagen-superior.position-absolute(style='bottom:0 ; left: -7%'): img(src='@/assets/curso/22.png')
          .bloque-texto-g__texto.p-5
            p.mb-0 La preparación de pedidos es también llamada <em>picking</em>, y se define como el proceso mediante el cual se seleccionan y recogen los productos desde las estanterías, pasillos, y demás espacios de la bodega o almacén; con el objetivo de organizar y preparar la mercancía y objetos postales para ser embalados (<em>packing</em>) y enviados a sus respectivos clientes finales.
    p.mb-5 Los principales objetivos en la preparación de pedidos son reducir recorridos, disminuir tiempos y operaciones, y mantener una rotación de stock precisa; para lograr eficiencia en este proceso es importante el desarrollo de las siguientes fases:
    figure.mb-5
      img(src='@/assets/curso/23.svg', alt='Texto que describa la imagen')
    p.mb-5 Dentro de la preparación de pedidos existen tres factores importantes: número de personas, sistema de extracción del producto, recorrido y movimiento de las personas, como se describen en las tablas que se muestran a continuación: 
    .titulo-sexto.color-primario
      h5 Tabla 2
      span Número de personas y la extracción del producto(s) / Relación de factores en la preparación de pedidos
    .row.justify-content-center
      .col-lg-8
        .tabla-a.color-acento-botones.mb-5
          table
            thead
              tr.bg-blue
                th(colspan='2')
            tbody
              tr
                td.p-4.fw-bold Extracción INDIVIDUAL
                td.p-4 UN pedido preparado por UNA persona
              tr
                td.p-4.fw-bold Extracción INDIVIDUAL DIVIDIDA
                td.p-4 Un pedido preparado por VARIAS personas
              tr
                td.p-4.fw-bold Extracción CONJUNTA
                td.p-4 VARIOS pedidos preparados por UNA persona
              tr
                td.p-4.fw-bold Extracción CONJUNTA DIVIDIDA
                td.p-4 VARIOS pedidos preparados por VARIAS personas
    .titulo-sexto.color-primario
      h5 Tabla 3
      span Recorrido y movimiento de las personas / Relación de factores en la preparación de pedidos.
    .row.justify-content-center
      .col-lg-8
        .tabla-a.color-acento-botones.mb-5
          table
            thead
              tr.bg-blue
                th(colspan='2')
            tbody
              tr
                td.p-4.fw-bold(rowspan='2' ) Persona al producto
                td.p-4 La persona se desplaza a pie hasta el producto.
              tr
                td.p-4 <b>Requisito:</b> cantidad de pedidos baja, almacén pequeño, distancias cortas, uso de equipos manuales.
              tr
                td.p-4.fw-bold(rowspan='2') Producto a la persona
                td.p-4 Desplazamiento de los pedidos hasta las personas en forma manual o automática.
              tr
                td.p-4 <b>Requisito:</b> cantidad de pedidos medio-alto, salida del producto en unidades o cajas, distancias medio-largas, abastecimiento con palé, utilización de sistemas de gestión informáticos (SGA) en la preparación de pedidos.
              tr
                td.p-4.fw-bold(rowspan='2') Una persona – <br> varios pedidos
                td.p-4 La persona se desplaza hasta el producto; aunque conlleva a una doble planificación y gestión.
              tr
                td.p-4 <b>Requisito:</b> cantidad de pedidos media-alta, cantidad de líneas de pedido medio, los medios para movilizar utilizados normalmente son carretillas de dos niveles, y aplicación de recursos informáticos como el código de barras.
              tr
                td.p-4.fw-bold(rowspan='2') Varias personas –<br> varios pedidos
                td.p-4 Las personas se desplazan hasta los productos para prepararlos cuando lo requieran por sus características y a la vez en el mismo pedido se debe aplicar un sistema de producto a la persona.
              tr
                td.p-4 <b>Requisito:</b>  desfragmentar el pedido y separar los productos; por ejemplo: tornillos de 5 cm y tuercas de 5 cm; un producto fresco de uno congelado, etc. Posterior se consolida el pedido para realizar un solo envío.
    #t_1_3.titulo-segundo.color-acento-contenido
      h2 1.3 Documentos asociados al alistamiento y almacenaje
    .row.justify-content-center.align-items-center.mb-5.mt-5
        .col-lg-4
            img(src='@/assets/curso/24.png', alt='Texto que describa la imagen')
        .col-lg-7
          p El objetivo de los documentos (registros) asociados al alistamiento y almacenaje es saber dónde está ubicada la mercancía, quiénes son los responsables de la gestión y el control de la misma dentro de la cadena logística.  Existen categorías generales de los documentos como: Comerciales, Operativos, Administrativos, de Transporte, Seguro y Financieros.
    p.mb-5 En el recurso, que se muestra a continuación, se presentan los aspectos más importantes que se deben tener en cuenta en lo que respecta a los documentos asociados al alistamiento y almacenaje:
    figure.mb-5 
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    #t_1_4.titulo-segundo.color-acento-contenido
      h2 1.4 Zonas del almacén
    p.mb-5 El desarrollo del proceso logístico requiere de un conjunto de medios y métodos para desarrollar la actividad o servicio específico; por tanto, requiere de la optimización de los recursos para conseguir los mejores resultados.  Uno de los principales recursos es el almacén, el cual sirve de elemento regulador en el flujo de las mercancías en la red logística.
    br
    br
    
    .row.justify-content-center.mb-5
      .col-lg-9
        .bloque-texto-g.color-acento-contenido.p-4.p-sm-4.p-md-5.position-relative
          .bloque-texto-g__img(
            :style="{'background-image':`url(${require('@/assets/curso/25.jpg')})`}"
          )
            .imagen-superior.position-absolute(style='bottom:0 ; left: 20%'): img(src='@/assets/curso/26.png')
          .bloque-texto-g__texto.p-5
            p.mb-0 El almacén podría definirse como aquella locación donde se realizan funciones de recepción, manipulación, conservación, protección y posterior despacho de productos.

    //todo PENDIENTE AGREGAR EL DOCUMENTO ENLACE
    .tarjeta.color-primario.p-3.mb-5
      .row.justify-content-around.align-items-center.px-5
        .col-3.col-sm-2.col-lg-1
          img(src="@/assets/curso/26.svg")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              p.text-small.mb-0 El almacén desempeña varias funciones, dependiendo de la clasificación de productos. <b>Explore el Anexo_1_PrincipalesFuncionesDelAlmacen</b> y amplíe sus conocimientos en este punto. 
            .col-sm-auto
              a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('/downloads/documento0.pdf')" target="_blank")
                span Ver más 
                i.fas.fa-file-download
    //todo PENDIENTE AGREGAR EL DOCUMENTO ENLACE
    p.mb-5  Explore las distintas zonas del almacén e identifique las particularidades que, de cada una, son importantes por su aporte a la cadena logística:
    ImagenInfograficaB.color-secundario.mb-5
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/27.svg', alt='Texto que describa la imagen')
      .row(x="71.3%" y="57%" tooltip="Zona de recepción" numero="").align-items-center
        .col-lg-8
          h4 Zona de recepción
          p Zona de entrada de la mercancía, donde se realiza un control cuantitativo (unidades correctas con el registro) y cualitativo de la mercancía (calidad y estado).  Posteriormente será clasificada y distribuida en la bodega.
        .col-lg-4: img(src='@/assets/curso/28.jpg')
      .row(x="64%" y="53%" tooltip="Zona de carga y descarga" numero="").align-items-center
        .col-lg-8
          h4 Zona de carga y descarga
          p Área donde se desarrollan actividades de descarga de los vehículos que traen la mercancía, procedente de los proveedores y las devoluciones que realizan los clientes; esta zona cuenta con muelles de carga y descarga.  Aquí se realiza el primer punto de control.
        .col-lg-4: img(src='@/assets/curso/29.jpg')
      .row(x="70%" y="34%" tooltip="Zona de cuarentena" numero="").align-items-center
        .col-lg-8
          h4 Zona de cuarentena
          p Esta zona aplica más para aquellas bodegas que almacenan productos farmacéuticos o agro-alimentos, los cuales, por normativa, exige unos análisis previos al almacenamiento para saber si están en buen estado o no.  Por tanto, hasta no saber el estado no podrán almacenar.
        .col-lg-4: img(src='@/assets/curso/30.jpg')
      .row(x="39%" y="27%" tooltip="Almacenaje" numero="").align-items-center
        .col-lg-12
          h4 Zona de Almacenamiento
          p Lugar donde se depositan mercancías hasta registrar la expedición; aquí se diferencian dos áreas: A) Stock, destinada a reserva de productos, que se trasladan a otras áreas donde se prepararán para consolidación. El almacenamiento se realiza en estanterías industriales para aprovechamiento de la superficie horizontal y altura, dependiendo de las características del producto almacenado.  B) <em>Picking</em>, donde se preparan pedidos para embalaje.  Los tiempos y recorrido de la mercancía son cortos; aquí son necesarios equipos de manipulación de mercancía específicos y soluciones de almacenamiento como cartón flow o estantería para cargas livianas.
      .row(x="57%" y="27%" tooltip="Zona de espera" numero="").align-items-center
        .col-lg-8
          h4 Zona de espera
          p Esta zona es utilizada, por lo general, para atender imprevistos que se puedan presentar como: rapidez o lentitud en la preparación de los pedidos y que lleguen a generar adelantos o retrasos al momento de hacer entrega al transportador.
        .col-lg-4: img(src='@/assets/curso/31.jpg')
      .row(x="29%" y="27%" tooltip="Zona envasado" numero="").align-items-center
        .col-lg-8
          h4 Zona de Envasado
          p Envasado o re-envasado, esta zona se encuentra en aquellas bodegas o almacenes donde es necesario volver a envasar o repaletizar (estibar) y conformar nuevas unidades de carga, por razones de almacenamiento, sanidad e higiene.
        .col-lg-4: img(src='@/assets/curso/32.jpg')
      .row(x="63%" y="34%" tooltip="Embalaje y etiquetado" numero="").align-items-center
        .col-lg-8
          h4 Zona de embalaje y etiquetado
          p Aquí se realiza todo el proceso de acondicionamiento de productos para protegerlos, temporalmente, para posterior manipulación y transporte; el embalaje puede ser manual o a través de equipos automatizados. Esta zona debe ubicarse cerca de mecanismos de envasado, en caso de ser necesario, y edición de etiquetas para registrar en medios informáticos.
        .col-lg-4: img(src='@/assets/curso/33.jpg')
      .row(x="44%" y="65%" tooltip="Consolidación" numero="").align-items-center
        .col-lg-8
          h4 Zona de consolidación
          p Aquí se agrupa una variedad de productos que correspondan a un mismo pedido, incluso de diferentes proveedores y así realizar un envío de mayor volumen a menor costo. En algunas ocasiones esta actividad la realiza, directamente, la empresa de transporte.
        .col-lg-4: img(src='@/assets/curso/34.jpg')
      .row(x="44%" y="53%" tooltip="Zona técnica" numero="").align-items-center
        .col-lg-8
          h4 Zona técnica
          p Aquí se desarrollan actividades, principalmente, de mantenimiento de equipos técnicos y mecánicos que utilice el área operativa; en ocasiones es compartido el espacio con elementos que han sido dados de baja o son deficientes para la operación. Se sugiere que esta zona se encuentre retirada del resto de las áreas por seguridad del personal y la propia mercancía.
        .col-lg-4: img(src='@/assets/curso/35.jpg')
      .row(x="49%" y="80%" tooltip="Administrativa" numero="").align-items-center
        .col-lg-8
          h4 Zona Administrativa
          p Área destinada para oficinas, atención al cliente o para transportadores, salas de reunión, casino, vestieres; o, como se denomina en calidad, para gestión organizacional del almacén.
        .col-lg-4: img(src='@/assets/curso/36.jpg')
      .row(x="17%" y="70%" tooltip="Despacho" numero="").align-items-center
        .col-lg-8
          h4 Zona de control de salida o despacho
          p Aquí se verifica que las mercancías relacionadas en el pedido correspondan con los registros documentales de preparación del pedido o solicitud del cliente.  Por lo regular, en esta área, se acumulan las mercancías que serán cargadas en los vehículos.
        .col-lg-4: img(src='@/assets/curso/37.jpg')





    .tarjeta.color-primario.p-3.mb-5
      .row.justify-content-around.align-items-center.px-5
        .col-3.col-sm-2.col-lg-1
          img(src="@/assets/curso/26.svg")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0
              p.text-small.mb-0 Profundice en los aspectos más importantes, relativos a las zonas del almacén, estudiando conscientemente el documento: <b>guía del Almacén en la cadena logística.</b>
            .col-sm-auto
              a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('/downloads/documento4.pdf')" target="_blank")
                span Ver más 
                i.fas.fa-file-download





</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema1',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
  },
  data: () => ({
    mostrarIndicador: true,
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

<style lang="sass" ;scoped>
.dots-1
  .img-infografica__item__dot
    background-color: #f5f5f5
    height: 69px
    height: 40px
    background-color: $color-acento-contenido
    border-radius: 10px

    &:before, &:after
      display: none
      opacity: 1
.acordion__activo
  background-color: #ffcec9 !important
.acordion__normal
  background-color: #ffe7e4
.bg-blue
  background-color: #5263e2
.tabla-a thead
  border-top: 0
.imagen-superior
  @media (max-width: $bp-min-lg)
    display: none !important

.img-infografica-b.color-secundario .img-infografica-b__item__numero
  color: $white
.img-infografica-b__item__tooltip
  border-radius: 10px
  background-color: $color-primario
  font-weight: bold
.img-infografica-b__modal
  position: absolute
  background-color: #dce0f9
  border-radius: 10px
  min-height: 30% !important
  top: 30%
  left: 10%
  width: 80%
  h4, p
    color: $color-sistema-texto !important
.img-infografica-b__img
  position: relative !important
</style>
