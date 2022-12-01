Oscar Rodrigo Alvarez Urbina

Cuento con 4 años de experiencia 

-------------
|Ejercicio 2|
-------------

1.¿Qué es un servidor HTTP? 
Es un servidor web es un servidor que almacena, procesa y entrega archivos de sitios web a los buscadores.

2.¿Qué son los verbos HTTP? Mencionar los más conocidos
Son metodos que indican qué acción queremos realizar sobre el servidor, POST o GET son los más populares

3.¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers? 
Request: Es la solicitud que hace el usuario hace una al servidor web. 
Response: es la respuesta que brinda el servidor web al usuario

Los headers HTTP permiten al usuario y al servidor enviar información adicional junto a una petición o respuesta

4.¿Qué es un queryString? (En el contexto de una url)
Las Query String permiten acceder a páginas web dinámicas con distintas variables consiguiendo así que las páginas web no estén compuestas de decenas de directorios y permitiendo que su estructura esté basada en URLs amigables

5.¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?
Indican si se ha completado satisfactoriamente una solicitud HTTP específica. Las respuestas se agrupan en cinco clases:

Respuestas informativas (100–199),
Respuestas satisfactorias (200–299),
Redirecciones (300–399),
Errores de los clientes (400–499),
y errores de los servidores (500–599).

6.¿Cómo se envía la data en un Get y cómo en un POST? 
Con el método GET, los datos que se envían al servidor se escriben en la misma dirección URL

El método POST introduce los parámetros en la solicitud HTTP para el servidor. Por ello, no quedan visibles para el usuario.

7.¿Qué verbo http utiliza el navegador cuando accedemos a una página?
GET
8.Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.

XML es un estándar abierto de almacenamiento e intercambio de datos


<pieza tipo="A">
    <nombre>Tornillo</nombre>
    <descripcion>Cilindro mecanico con una cabeza utilizado en la fijación temporal de unas piezas con otras 
    </descripcion>
    <caracateristica>
        <tipo>metal</tipo>
        <tamanyo>10</tamanyo>
    </caracateristica>
    <vacio></vacio>
</pieza>

JSON es un formato de intercambio de datos basado en texto derivado del lenguaje de encriptación de JavaScript.


{
    “pieza”: {
        “tipo”: “A”
        “nombre”: “Tornillo”,
        “descripcion”: “Cilindro mecánico con una cabeza utilizado en la fijación temporal de unas piezas con otras”,
        “caracteristica”: {
            “tipo”: “metal”
            “tamanyo”: 10
        },
        “vacio”: “”
     }
}

9.Explicar brevemente el estándar SOAP
Es un protocolo permite realizar intercambios de información entre aplicaciones que se encuentren implementadas en diferentes lenguajes de programación.

10.Explicar brevemente el estándar REST Full

Es un metodo que utiliza dos sistemas para intercambiar información de manera segura a través de Internet pueden ser aplicaciones internas o de terceros para llevar a cabo varias tareas.

11.¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?
Los headers HTTP permiten al usuario y al servidor enviar información adicional junto a una petición o respuesta

Es un recurso que se utiliza en el header y que le indica al usuario o el buscador qué clase de archivo o medio le está enviando el servidor.

------------
|Ejercicio 3|
------------
1.	Realizar un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json

![P_GET](https://user-images.githubusercontent.com/88816213/204975224-a8337c1b-cde4-48d7-a18b-9ece29ac9325.png)


2.	Realizar un request POST a la URL anterior, y con body:

![P_POST](https://user-images.githubusercontent.com/88816213/204975519-c74ec7ef-90af-4359-9efd-4887518312a5.png)

3.	Realizar nuevamente un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json

![P_GET_2](https://user-images.githubusercontent.com/88816213/204975583-72164929-62ed-4100-a2d0-14df23c30883.png)

¿Qué diferencias se observan entre las llamadas el punto 1 y 3?
visualizamos la inserción del registro

------------
|Ejercicio 4|
-------------

https://trailblazer.me/id/roalvrz12

-------------
|Ejercicio 5|
-------------

