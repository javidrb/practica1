# practica1
# Ejercicio 1

1.- Realizar en el siguiente HTML 5 declaraciones de estilo CSS para realizarla página tal y como se muestra en la imagen utilizando display GRID.

# Ejercicio 2

# EJERCICIO 1.2.1

En el archivo facilitado al alumno "la primera página Web con imagen",emplear estilos CSS para cambiar el color del fondo de la página, el color de lafuente, la familia tipográfica y el tamaño.

# EJERCICIO 1.2.2.

Realiza un esquema sencillo de este documento HTML a su estructura tipoárbol, que resuma brevemente las relaciones directas entre elementos de lapágina, clarificando la jerarquía del árbol.

# EJERCICIO 1.2.3 OBLIGATORIO

Construir una página HTML titulada: Secciones y líneas generales de undocumento HTML5.Deben emplearse las marcas básicas de HTML y estilos según los contenidosdel módulo 1 de este curso.Utilice el texto que aparece a continuación:

Secciones y líneas generales de un documento HTML5La especificación HTML5 trae muchos nuevos elementos a los desarrolladores web,permitiéndoles describir la estructura de un documento web con semánticaestandarizada. Este documento describe estos elementos y cómo usarlos para definirel perfil de cualquier documento.Problemas resueltos por HTML5La definición de la estructura de un documento en HTML 4 y su algoritmo de perfiladoes muy tosco y genera numerosos problemas:1. HTML5 quita la necesidad de elementos

para definir seccionessemánticas sin definir valores específicos para los atributos class, introduciendoun nuevo elemento,
, el elemento de sección HTML.2. Mezclar varios documentos es difícil: la inclusión de un sub-documento en undocumento principal. Esto se resuelve en HTML5 con los elementos deseccionado (,
, y ) son siempre subsecciones desu sección ancestra más cercana.3. HTML5 introduce el elemento que oculta todos los elementos decabecera excepto el primero de más alto rango (por ejemplo,
Justine

# Les Malheurs de la Vertu

creael perfil 1. Justine).4. Un documento puede tener secciones especiales conteniendo informaciónrelacionado que no es parte del flujo principal. HTML5 introduce el elemento permitiendo a dichas secciones no ser parte del perfil principal.5. Hay información relacionada no al documento, pero si al sitio entero, comologos, menús, tablas de contenidos, o información de derechos de autor ynotas legales. Para ese propósito, HTML5 introduce tres elementos de secciónespecíficos: para colecciones de enlaces, como una tabla de contenidos, y información relacionada con el sitio. De manera más general, HTML5 trae precisión a las características de seccionado ycabecera, permitiendo a los perfiles de documento ser predecibles y usados por elnavegador para mejorar la experiencia de usuario.El algoritmo de perfilado de HTML5Definiendo secciones en HTML5Todo el contenido incluido dentro del elemento es parte de una sección. Lassecciones en HTML5 pueden ser anidadas. Además de la sección principal, definida porel elemento , los límites de la sección son definidos explícita o implícitamente.Las secciones definidas explícitamente son el contenido definido en las etiquetas,
, , , , , y . Nota: Cada secciónpuede tener su propia jerarquía de cabeceras. Por lo tanto, incluso una secciónanidada puede tener un elemento
. Consulte también Definiendo cabeceras enHTML5.Ejemplo:
Forest elephants
Introduction
In this section, we discuss the lesser known forest elephants.

Habitat
Forest elephants do not live in trees but among them.

advertising block

(c) 2010 The Example company

------------------------------------------------------------
