# css3

Lista de propiedades CSS estables:
La tabla siguiente resume las propiedades definidas en las recomendaciones de Hojas de Estilo en Cascada (CSS) y admitidas correctamente por los navegadores más utilizados:

    Se incluyen las propiedades CSS 2, excepto las propiedades relacionadas con las hojas de estilo auditivas (aural).
    Las propiedades que han sido eliminadas en la recomendación CSS 2.1 se listan al final.
    Los valores de las propiedades añadidos o eliminados en la recomendación CSS 2.1 se indican con los símbolos (+) o (-).
    Las propiedades o los valores de las propiedades definidas en recomendaciones CSS 3 en elaboración que los navegadores actuales admiten correctamente se indican con el símbolo (3).

Tipos
Propiedad 	Descripción 	Valores
contador 	Contador 	counter(nombre, estilo)
familia-genérica 	Familia genérica de fuente 	cursive | fantasy | monospace | serif | sans-serif
forma 	Forma 	rect(top, right, bottom, left)
tamaño-absoluto 	Tamaño absoluto de fuente 	xx-small | x-small | medium | large | x-large | xx-large
tamaño-relativo 	Tamaño relativo de fuente 	larger | smaller
uri (para imagen de fondo o fuentes web) 	Dirección absoluta o relativa 	url("ruta_y_nombre_de_archivo")
Reglas arroba
Propiedad 	Descripción 	Descriptores / Características
@import 	Importar recurso 	url(...)
@font-face 	Fuente web 	font-family, src, font-style, font-weight, font-stretch, unicode-range, font-variant, font-feature-settings
@media 	Características del dispositivo 	width | height | orientation | aspect-ratio | resolution | etc.
Tipo de letra (fuente)
Propiedad 	Descripción 	Valores
font 	propiedad compuesta 	[ [ font-style || font-variant || font-weight ]? font-size [ / line-height ]? font-family ] | caption | icon | menu | message-box | small-caption | status-bar
font-family 	tipo de letra (fuente) 	[ nombre-fuente | familia-genérica ] [, nombre-fuente | familia-genérica ]*
font-size 	tamaño 	tamaño-absoluto | tamaño-relativo | distancia | porcentaje
font-weight 	grosor del trazo (negrita) 	normal | bold | bolder | lighter | 100 | 200 | 300 | 400 | 500 | 600 | 700 | 800 | 900
font-style 	inclinación (cursiva) 	normal | italic | oblique
font-variant(3) 	variantes tipográficas 	normal | small-caps
font-variant-caps(3) 	versalitas 	normal | small-caps
font-kerning(3) 	kerning 	auto | normal | none
font-variant-ligatures(3) 	ligaduras 	normal | none | common-ligatures | no-common-ligatures | discretionary-ligatures | no-discretionary-ligatures | historical-ligatures | no-historical-ligatures | contextual | no-contextual
font-variant-numeric(3) 	versalitas 	normal | lining-nums | oldstyle-nums | proportional-nums | tabular-nums | diagonal-fractions | stacked-fractions | ordinal | slashed-zeros
font-variant-position(3) 	posición 	normal | sub | super
font-variant-east-asian(3) 	lenguas asiáticas 	normal | jis78 | jis83 | jis90 | jis04 | simplified | traditional | full-width | proportional-width | ruby
font-feature-settings(3) 	características OpenType 	normal | características OpenType
font-synthesis(3) 	síntesis 	none | weight | style
font-size-adjust(3) 	ajuste del tamaño 	número
font-stretch(3) 	anchura 	ultra-condensed, extra-condensed, condensed, semi-condensed, normal, semi-expanded, expanded, extra-expanded, ultra-expanded
Texto
Propiedad 	Descripción 	Valores
color 	color del texto 	color
direction 	dirección del texto 	ltr | rtl
letter-spacing 	espacio entre caracteres 	normal | distancia
line-height 	espaciado entre líneas 	normal | número | distancia | porcentaje
text-align 	alineación del texto 	center | justify | left | right
text-decoration 	decoración del texto 	none | blink | line-through | overline | underline
text-indent 	sangrado de la primera línea 	distancia | porcentaje
text-transform 	mayúsculas / minúsculas 	none | capitalize | lowercase | uppercase
text-shadow(3) 	sombreado 	desplazamiento horizontal, desplazamiento vertical, tamaño desenfoque, color
unicode-bidi 	dirección del texto 	normal | embed | bidi-override
vertical-align 	alineación vertical 	baseline | bottom | middle | sub | super | text-bottom | text-top | top | distancia | porcentaje
white-space 	espacios en blanco, saltos de línea y wrap 	normal | nowrap | pre | pre-line(+) | pre-wrap(+)
word-spacing 	espacio entre palabras 	normal | distancia
Bordes
Propiedad 	Descripción 	Valores
border 	cuatro bordes simultáneamente 	border-color || border-width || border-style
border-top 	borde superior 	border-color || border-width || border-style
border-right 	borde derecho 	border-color || border-width || border-style
border-bottom 	borde inferior 	border-color || border-width || border-style
border-left 	borde izquierdo 	border-color || border-width || border-style
border-radius(3) 	esquinas redondeadas 	[ distancia | porcentaje ] {1, 4}
border-top-right-radius(3) 	esquina superior derecha redondeada 	distancia | porcentaje
border-bottom-right-radius(3) 	esquina inferior derecha redondeada 	distancia | porcentaje
border-bottom-left-radius(3) 	esquina inferior izquierda redondeada 	distancia | porcentaje
border-top-left-radius(3) 	esquina superior izquierda redondeada 	distancia | porcentaje
border-color 	color de los bordes 	[ color | transparent ] {1, 4}
border-width 	grosor de los bordes 	[ medium | thick | thin | distancia ] {1, 4}
border-style 	estilos de los bordes 	[ none | hidden | dashed | dotted | double | groove | inset | outset | ridge | solid ] {1, 4}
border-top-color 	color del borde superior 	[ color | transparent ] {1, 4}
border-top-width 	grosor del borde superior 	[ medium | thick | thin | distancia ] {1, 4}
border-top-style 	estilo del borde superior 	[ none | hidden | dashed | dotted | double | groove | inset | outset | ridge | solid ] {1, 4}
border-right-color 	color del borde derecho 	[ color | transparent ] {1, 4}
border-right-width 	grosor del borde derecho 	[ medium | thick | thin | distancia ] {1, 4}
border-right-style 	estilo del borde derecho 	[ none | hidden | dashed | dotted | double | groove | inset | outset | ridge | solid ] {1, 4}
border-bottom-color 	color del borde inferior 	[ color | transparent ] {1, 4}
border-bottom-width 	grosor del borde inferior 	[ medium | thick | thin | distancia ] {1, 4}
border-bottom-style 	estilo del borde inferior 	[ none | hidden | dashed | dotted | double | groove | inset | outset | ridge | solid ] {1, 4}
border-left-color 	color del borde izquierdo 	[ color | transparent ] {1, 4}
border-left-width 	grosor del borde izquierdo 	[ medium | thick | thin | distancia ] {1, 4}
border-left-style 	estilo del borde izquierdo 	[ none | hidden | dashed | dotted | double | groove | inset | outset | ridge | solid ] {1, 4}
Margen exterior
Propiedad 	Descripción 	Valores
margin 	cuatro márgenes exterior simultáneamente 	[ auto | distancia | porcentaje ] {1, 4}
margin-top 	margen exterior superior 	auto | distancia | porcentaje
margin-right 	margen exterior derecho 	auto | distancia | porcentaje
margin-bottom 	margen exterior inferior 	auto | distancia | porcentaje
margin-left 	margen exterior izquierdo 	auto | distancia | porcentaje
Margen interior
Propiedad 	Descripción 	Valores
padding 	cuatro márgenes interiores simultáneamente 	[ distancia | porcentaje ] {1, 4}
padding-top 	margen interior superior 	distancia | porcentaje
padding-right 	margen interior derecho 	distancia | porcentaje
padding-bottom 	margen interior inferior 	distancia | porcentaje
padding-left 	margen interior izquierdo 	distancia | porcentaje
Fondos
Propiedad 	Descripción 	Valores
background 	propiedad compuesta 	background-attachment || background-color || background-image || background-position || background-repeat
background(3) 	fondos múltiples 	separados por comas
background-attachment 	ligadura de la imagen 	fixed | scroll
background-color 	color de fondo 	transparent | color
background-image 	imagen de fondo 	none | uri
background-position 	posición de la imagen de fondo 	[ [ left | center | right | distancia | porcentaje] [ top | center | bottom | distancia | porcentaje] ]? | [ [ left | center | right ] || [ top | center | bottom ] ]
background-repeat 	repetición de la imagen de fondo 	no-repeat | repeat | repeat-x | repeat-y | space(3) | round(3)
background-clip(3) 	límite de la imagen de fondo 	border-box | padding-box | content-box
background-size(3) 	tamaño de la imagen de fondo 	auto | [ distancia | porcentaje ] {2} | contain | cover
background-origin(3) 	origen de la imagen de fondo 	border-box | padding-box | content-box
Listas
Propiedad 	Descripción 	Valores
list-style 	propiedad compuesta 	list-style-image || list-style-position || list-style-type
list-style-image 	imagen del marcador 	none | uri
list-style-position 	posición del marcador 	inside | outside
list-style-type 	tipo de marcador 	none | circle | disc | square | decimal | decimal-leading-zero | lower-alpha | upper-alpha | lower-greek | lower-latin | upper-latin | lower-roman | upper-roman | armenian | georgian | hebrew(-) | cjk-ideographic(-) | hiragana(-) | katakana(-) | hiragana-iroha(-) | katakana-iroha(-)
Tablas
Propiedad 	Descripción 	Valores
border-collapse 	modo de bordes 	collapse | separate
border-spacing 	separación entre celdas 	distancia distancia?
caption-side 	posición de la leyenda 	top | bottom | left(-) | right(-)
empty-cells 	borde de casillas vacías 	hide | show
table-layout 	algoritmo ancho de tabla 	auto | fixed
Modelo de caja / Tamaño
Propiedad 	Descripción 	Valores
display 	tipo de caja 	none | block | compact(-) | inline | inline-block(+) | inline-table | list-item | marker(-) | run-in | table | table-caption | table-cell | table-column | table-column-group | table-footer-group | table-header-group | table-row | table-row-group | flex(3) | inline-flex(3)
box-sizing(3) 	posición del borde y márgenes 	border-box | content-box
width 	anchura 	auto | distancia | porcentaje
min-width 	anchura mínima 	distancia | porcentaje
max-width 	anchura máxima 	distancia | porcentaje
height 	altura 	auto | distancia | porcentaje
min-height 	altura mínima 	distancia | porcentaje
max-height 	anchura máxima 	distancia | porcentaje
overflow 	si el contenido desborda al elemento 	auto | hidden | scroll | visible
Posicionamiento
Propiedad 	Descripción 	Valores
float 	modo de posicionamiento flotante 	none | left | right
clear 	lado en el que no puede haber elementos flotantes 	none | both | left | right
position 	modo de posicionamiento 	absolute | fixed | relative | static
top 	posición del borde superior del elemento 	auto | distancia | porcentaje
right 	posición del borde derecho del elemento 	auto | distancia | porcentaje
bottom 	posición del borde inferior del elemento 	auto | distancia | porcentaje
left 	posición del borde izquierdo del elemento 	auto | distancia | porcentaje
clip 	recorta el elemento 	auto | forma
visibility 	visibilidad 	hidden | collapse | visible
z-index 	apilamiento 	auto | número-entero
Cajas flexibles
Propiedad 	Descripción 	Valores
display 	tipo de caja 	flex(3) || inline-flex(3)
flex-flow(3) 	propiedad compuesta 	flex-direction || flex-wrap
flex-direction(3) 	dirección 	row || row-reverse || column || column-reverse
flex-wrap(3) 	ajuste de línea 	wrap || no-wrap || wrap-reverse
order(3) 	número de orden 	número
flex(3) 	propiedad compuesta 	[ flex-grow || flex-shrink || flex-basis ] || initial || auto || none || número
flex-grow(3) 	factor de expansión 	número
flex-shrink(3) 	factor de compresión 	número
flex-basis(3) 	tamaño inicial 	distancia || auto || content || width
justify-content(3) 	alineación en la dirección principal 	flex-start || flex-end || center || space-between || space-around
align-items(3) 	alineación en la dirección secundaria (una línea) 	flex-start || flex-end || center || baseline || stretch
align-self(3) 	alineación individual en la dirección secundaria 	auto || flex-start || flex-end || center || baseline || stretch
align-content(3) 	alineación en la dirección secundaria (varias líneas) 	flex-start || flex-end || center || space-between || space-around || stretch
Impresora
Propiedad 	Descripción 	Valores
page-break-after 	salto de página después de 	auto | always | avoid | left | right
page-break-before 	salto de página antes de 	auto | always | avoid | left | right
page-break-inside 	salto de página dentro de 	auto | avoid
orphans 	número de líneas al final de página 	número-entero
widows 	número de líneas al principio de la página 	número-entero
Interface de usuario
Propiedad 	Descripción 	Valores
cursor 	tipo de cursor 	[uri,]* | auto | crosshair | default | help | move | pointer | progress | n-resize | ne-resize | e-resize | se-resize | s-resize | sw-resize | w-resize | nw-resize | text | wait
outline 	cuatro bordes simultáneamente 	outline-color || outline-width || outline-style
outline-color 	color de los bordes 	color
outline-width 	grosor de los bordes 	border-width
outline-style 	estilos de los bordes 	border-style
Pseudo-elementos
Nombre 	Descripción 	Valores
::after 	inserta contenido después del elemento 	content: contenido
::before 	inserta contenido antes del elemento 	content: contenido
::first-letter 	primera letra 	
::first-line 	primera línea de texto 	
content 	contenido generado 	normal(+) | none(+) | [ texto | uri | contador | attr(atributo) | open-quote | close-quote | no-open-quote | no-close-quote ]+
counter-increment 	incremento de contador 	none | [ identificador número-entero? ]+
counter-reset 	puesto a cero de contador 	none | [ identificador número-entero? ]+
quotes 	comillas 	none | [ texto-apertura texto-cierre ]+
Pseudo-clases
Nombre 	Descripción 	Valores
:active 	cuando se hace clic sobre el elemento 	
:first-child 	primer elemento hijo 	
:focus 	cuando el elemento tiene el foco 	
:hover 	cuando el ratón pasa sobre el elemento 	
:lang 	idioma 	:lang(en) | :lang(es) | :lang(fr) etc.
:link 	enlaces no visitados 	
:visited 	enlaces ya visitados 	
Propiedades no incluidas en CSS 2.1 ni en CSS 3
Propiedad 	Descripción 	Valores
marker-offset 	distancia entre marcador y elemento 	distancia
marks 	marcas de corte de papel 	crop | cross

