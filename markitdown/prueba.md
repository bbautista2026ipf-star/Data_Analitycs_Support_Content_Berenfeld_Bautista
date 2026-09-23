Diseño Web Responsive con Framework Bootstrap

1. IntroducciónaBootstrapysufuncióneneldiseñowebresponsivo
    ¿QuéesBootstrap?
   Bootstrapes un framework de diseño web de código abierto que se utiliza para crear sitios web y aplicaciones
   web responsivas y móviles. Fue creado por Mark Otto y Jacob Thornton en Twitter como un conjunto de
   herramientas internas para mejorar la consistencia y la eficiencia en el desarrollo de aplicaciones web. La
   primera versión, Bootstrap 2, se lanzó en agosto de 2011, seguida por Bootstrap 3 en 2013 y Bootstrap 4 en
2. Cada versión ha introducido nuevas características, mejoras de rendimiento y soporte para tecnologías
   web modernas. Bootstrap utiliza HTML, CSS y JavaScript para diseñar interfaces de usuario elegantes y
   adaptablesadiferentesdispositivos,tamañosdepantallayresoluciones.
    ¿PorquéusarBootstrapparadiseñarsitioswebresponsivos?
   Bootstrap es una herramienta muy útil para diseñar sitios web responsivos porque simplifica el proceso de
   diseño y desarrollo. Con Bootstrap, los desarrolladores pueden utilizar un conjunto de componentes
   predefinidos y plantillas para crear diseños rápidos y consistentes sin tener que escribir código desde cero.
   Además, Bootstrap ofrece una amplia gama de características que facilitan la creación de sitios web
   responsivos, como la capacidad de ajustar automáticamente el tamaño de las imágenes y los videos según el
   tamañodelapantalla.
    ¿CuálessonlasventajasdeusarBootstrapeneldiseñoweb?
   Bootstrapofrecevariasventajasparaeldiseñoweb,entreellas:
3. Ahorro de tiempo: Con Bootstrap, los desarrolladores pueden ahorrar tiempo en el procesode diseño
   ydesarrollo,yaquenotienenqueescribircódigodesdecero.
4. Consistencia: Bootstrap ofrece un conjunto de componentes y plantillas predefinidos que facilitan la
   creacióndediseñoscoherentesyconsistentesentodoelsitioweb.
5. Responsividad: Bootstrap está diseñado para ser responsivo y adaptable a diferentes tamaños de
   pantalla y dispositivos, lo que permite a los sitios web funcionar de manera efectiva en cualquier
   dispositivo.
6. Flexibilidad: Bootstrap es altamente personalizable y los desarrolladores pueden personalizar los
   componentesyestilosparaadaptarlosalasnecesidadesespecíficasdesusitioweb.
7. Compatibilidad: Bootstrap es compatible con los navegadores más populares y funciona bien en una
   variedaddeplataformasydispositivos.
   Por ejemplo, si se desea agregar una barra de navegación al sitio web, se puede utilizar el componente
   predefinidodebarradenavegacióndeBootstrapypersonalizarlasegúnlasnecesidadesespecíficas.Estopuede
   ahorrartiempoyesfuerzoeneldiseñoydesarrollodeunabarradenavegacióndesdecero.Además,labarrade
   navegación de Bootstrap es responsiva y se ajusta automáticamente a diferentes tamaños de pantalla, lo que
   aseguraqueelsitiowebseveayfuncionebienencualquierdispositivo.
   2.PrimerospasosconBootstrap
    Descargaeinstalación:
   Para comenzar a utilizar Bootstrap, se puede descargar la versión más reciente desde el sitio web oficial
   (https://getbootstrap.com/) o utilizar la versión alojada en la CDN (Content Delivery Network) de
   Bootstrap. Si se prefiere la opción de descarga, simplemente descarga los archivos CSS y JavaScript de
   Bootstrap y agrégalos a tu proyecto. Si optas por la CDN, simplemente agrega los enlaces a los archivos
   CSS y JavaScript en la sección `<head>` de tu documento HTML.
    IntegraciónconHTML:
   Unavezquehayas descargadoo agregadolos archivos deBootstrapatuproyecto, puedes comenzar autilizar
   lasclasesycomponentesdeBootstrapentucódigoHTML.Paraello,simplementeañade las clases CSS de
   Bootstrap a los elementos HTML según sea necesario para aplicarestilos y funcionalidades específicas.

|    | UsodelaCDN | (ContentDeliveryNetwork): |     |     |
| --- | ---------- | ------------------------- | --- | --- |

La CDN de Bootstrap es una forma conveniente de utilizar Bootstrap en tu proyecto sin necesidad de
descargar los archivos directamente. Simplemente agrega los enlaces a los archivos CSS y JavaScript de
Bootstrap en la sección `<head>` de tu documento HTML, y estarás listo para empezar a utilizar
| Bootstrap | en tu proyecto | sin necesidad | de configuración | adicional. |
| --------- | -------------- | ------------- | ---------------- | ---------- |
|  | ¿Cómoseusa? | | | |
-UnaveztengamosvinculadoelCDNdeBootstrap:
-PodemosempezarautilizarlasclasesdeBootstrapdelasiguientemanera:
-Resultado:

-TambienpodemosingresaralapaginadeBootstrapyutilizaralgúncomponentecopiandoelcódigo
| que nos proporciona | y lo pegamos | en nuestro | codigo: |
| ------------------- | ------------ | ---------- | ------- |
-Resultado

3. UsodelacuadrículadeBootstrapparacreardiseñosresponsivos
    ¿QuéeslacuadrículadeBootstrap?
   La cuadrícula de Bootstrapes un sistema de diseño de columnas que permite a los desarrolladores crear
   diseñosde sitiowebresponsivos yadaptablesa diferentestamaños depantalla. Lacuadrícula sebasaen
   un sistema de 12 columnas y utiliza clases CSS predefinidas para definir cómo se deben distribuir los
   elementosenunapágina.
    ¿CómofuncionalacuadrículadeBootstrap?
   La cuadrícula de Bootstrap funciona dividiendola página en filas y columnas. Cada fila puede contener
   hasta 12 columnas, y los elementos se distribuyen en las columnas utilizando clases CSS predefinidas.
   LasclasesCSSutilizadasparalacuadrículadeBootstrapincluyen"col-xs-","col-sm-","col-md-","col-lg-"
   y "col-xl-", las cuales especifican cuántas columnas debe ocupar un elemento en diferentes tamaños de
   pantalla.
   Porejemplo:
   "col-xs-12" significa que un elemento ocupará todas las 12 columnas en pantallas muy pequeñas
   (<576px).
   "col-sm-10"significaqueunelementoocupará10columnasenpantallaspequeñas(≥576px).
   "col-md-6"significaqueunelementoocupará6columnasenpantallasmedianas(≥768px).
   "col-lg-4"significaqueunelementoocupará4columnasenpantallasgrandes(≥992px).
   "col-xl-2"significaqueunelementoocupará2columnasenpantallasmuygrandes(≥1200px).
    EjemplosprácticosdecómousarlacuadrículadeBootstrap
   Aca se presenta unejemplo prácticode cómo utilizar la cuadrícula de Bootstrappara crear undiseño de
   doscolumnasenunapáginaweb:
   En este ejemplo, se utiliza la clase "container" para crear un contenedor de ancho fijo para el contenido
   de nuestra página. Dentro del contenedor, se crea una fila utilizando la clase "row", y hemos dividido la
   fila en dos columnas utilizando la clase "col-md-6". Esto significa que en pantallas medianas, cada
   columnaocupará6delas12columnasdisponibles,creandoundiseñodedoscolumnasenlapágina.
   Además,la cuadrícula de Bootstraptambiénofreceotras características útiles para el diseñoresponsivo,
   como la capacidad de ocultar o mostrar elementos en diferentes tamaños de pantalla utilizando clases
   como:
   "hidden-xs" queutilizaparaocultarunelementoenpantallasextrapequeñas(<576px).Estosignificaque
   siunelementotienelaclase"hidden-xs",noserávisibleenpantallasmáspequeñasque576px.
   "visible-lg-block"se utiliza para hacer visible un elemento solo en pantallas grandes (≥992px). Esto
   significa que si un elemento tiene la clase "visible-lg-block", solo será visible en pantallas mayores o
   igualesa992px,peroestaráocultoenpantallasmáspequeñas.
   Con estas herramientas, los desarrolladores pueden crear diseños web adaptables y atractivos que
   funcionenbienencualquierdispositivo.

4. ComponentesdeBootstrap
    ComponentesdeBootstrap:
   Bootstrapincluye una gran variedadde componentes que permitenagregar funcionalidades y elementos
   visualescomunesenunapáginaweb.Algunosdeloscomponentesmásutilizadosson:
   -Botones: Se utilizan para activar acciones en la página web, como enviar formularios, abrir
   ventanasemergentesoredirigiraotrapágina.Bootstrapofrecediferentesestilosytamañosdebotones.
   -Formularios: Bootstrap ofrece una amplia variedad de estilos para los formularios, lo que
   permite crear formularios atractivos y funcionales sin la necesidad de personalizar los estilos de los
   elementosdelformularioindividualmente.
   -Menús de Navegación: Bootstrap ofrece diferentes estilos de menús de navegación,
   incluyendo menús de navegación fijos en la parte superior de la página, menús de navegación
   responsivos para dispositivos móviles, menús de navegación con pestañas y menús de navegación con
   acordeón.
   -Carruseles: Los carruseles de Bootstrap permiten mostrar contenido de forma dinámica y
   atractiva,conlaposibilidaddemostrarimágenes,textoyotroselementosmultimedia.
   -Alertas: Las alertas de Bootstrap se utilizan para mostrar información importante o mensajes
   deerrorenlapáginaweb,ysepuedenpersonalizarendiferentesestilosycolores.
    ¿CómoagregarcomponentesdeBootstrapaunapáginaweb?
   Para agregar componentes de Bootstrap a una página web, se deben incluir los archivos de CSS y
   JavaScript de Bootstrap en el HTML. Esto se puede hacer descargando los archivos de Bootstrap desde
   lapáginaoficialdeBootstrapoutilizandounCDN(ContentDeliveryNetwork)paracargar losarchivos
   deformamásrápidayeficiente.
   Una vez que se han incluido los archivos de Bootstrap, se pueden agregar los diferentes componentes a
   la página utilizando las clases CSS y los elementos HTML definidos por Bootstrap. Por ejemplo, para
   agregarunbotón,sepuedeutilizarelelementoHTML<button>conlaclaseCSS"btn"deBootstrap.

 EjemplosprácticosdecómousarloscomponentesdeBootstrap:
Enesteejemplo,estamosusandolaclasenavbar paracrearunmenúdenavegación,laclasenavbar-expand-
lg parahacer queelmenúse expandaenpantallasgrandesylaclasebg-light paraestablecerunfondode
colorclaroenelmenú.
Dentro de la etiqueta nav, tenemos una etiqueta a con la clase navbar-brand que nos permite agregar un
logotipooelnombredelsitiowebenelmenúdenavegación.
Elbotóndemenúsecreausandolaetiquetabuttonconlaclasenavbar-toggler.Alhacerclicenelbotón,se
activaráunaanimaciónparamostrarelmenúenpantallaspequeñas.
Dentro del div con la clase collapse navbar-collapse, se encuentra una lista ul con la clase navbar-nav, que
contienelosdiferenteselementosdelmenúdenavegación.
Paraagregar unmenúdesplegable,se puedeusarla clasedropdown enunelementoli dela lista,yagregar
unelementodivconlaclasedropdown-menuquecontendrálasopcionesdelmenúdesplegable.
Por último,también podemos usarclasescomo active paraindicar lapágina actualysr-only paraagregar
textoaccesiblesoloparalectoresdepantalla.
