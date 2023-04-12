# PIAT

## Practica 1

<pre>


### Fase1 


En la fase 1 de la practica1 tendremos que realizar 3 documentos xml.
El formato que vamos a utilizar es el siguiente < mision > mis siendo la cabecera.

Para poner una palabra en cursiva y en negrita se hace lo siguiente:
- < cursiva > [ palabra en cursiva ] < /cursiva >
- < negrita > [ palabra en negrita ] < /negrita >
- < negritaYCursiva > [ palabra en negrita y cursiva ] < /negritaYCursiva >

Ejemplo:
<texto>
  Esta es una palabra en <b><i>negrita y cursiva</i></b>.
</texto>


Base 64 binary para convertir fotos a texto y que lo pueda leer el xml

### Fase 2
-

El documento tipoIdentificacion contendrá datos de identificación, los elementos que van a colgar directamente de Schema van a ser complexType o simpleType. Va a colgar un element.

### Fase 3
-

Vamos a implementar key y key ref que tienen un atributo llamado path
Integridad ref el contenido de un elemento tiene que ser único

Ejemplo:
<tns:libros>
  <tns:libro ISBN="21212121" idLibro="Libro01">
    <tns:titulo> hola </tns:titulo>
    </tns:libro>
  <tns:libro ISBN="31313131" idLibro="Libro02">
    <tns:titulo> adios </tns:titulo>
  </tns libro>
</tns:libros>
  <tns:compras>
    <tns:compra idcompra="727">
      <tns:titulo> hola </tns:titulo> //Integridad referencial


En la clase principal, para hacer único un atributo tiene que empezar por "@"

</pre>

## Practica 2 PIAT:
<pre>

Para quedarte con la fecha tienes que añadir un parentesis en la parte correspondiente en la expresión 
regular que corresponde con la fecha

Grupo 0 todo
Grupo 1 Verde en nuestro caso la fecha como ejemplo, primer grupo de parentesis

Expresion regular para cada uno: msgIn, msgSPAM...

Fichero->trabajador->hacemos match-> aumentamos el estadítico.
Estructuras de datos:

*msgIn: mensaje de entrada, tenemos una expresión regular pasada por el patrón.

*msgOut: ...

Le pasamos a los logs un hashmap con todas las expresiones .compile() [Expresiones regulares]



</pre>









