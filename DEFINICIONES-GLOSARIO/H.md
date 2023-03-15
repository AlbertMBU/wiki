**HASHMAP:** designa y almacena claves únicas para los valores (en pares clave/valor), que se pueden recuperar, consultar en cualquier punto dado, utilizando la clave del elemento es un estructura de datos similar a Array, Arraylist, etc. ^hashmap

**HTTP:** Protocolo de comunicación entre dos computadoras en red.

Un protocolo es aquel que especifica las reglas de la comunicación, en este caso, entre dos computadoras. El protocolo HTTP (Hyper Text Transfer Protocol) fue creado específicamente para la web.

## Cuáles son los verbos HTTP

Una de las especificaciones de este protocolo son sus verbos, estos nos ayudan a indicar acciones. ^1fac59

-   **GET**. Lo utilizamos para solicitar datos o recursos específicos.
-   **HEAD**. Es similar a una petición GET pero sin contenido, sólo traer los encabezados. En ejemplo de su uso sería cuando vamos a utilizar APIs, para comprobar si lo que vamos a enviar es correcto y puede ser procesado.
-   **POST**. Envía datos a un recurso para su creación.
-   **PUT**. Es utilizado para actualizar un recurso.
-   **PATCH**. Actualiza un sección especifica de un recurso.
-   **DELETE**. Elimina por completo un recurso.

## Solicitudes de verbos HTTP en Postman

Supongamos que necesitas ejecutar estas acciones con una URL base como [https://platzi.com/profesores](https://platzi.com/profesores)

Para realizar este tipo de solicitudes, si es que queremos hacer pruebas podemos usar algunas herramientas como **Postman** que es multiplataforma y también lo puedes instalar como addOn a Google Chrome.

Mira para el caso de **GET** podríamos hacer algo así con Postman:

![https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202017-04-28%20a%20la-s-%2023.26.18-decae19c-0bff-4df1-b4fb-34e9f69c69df.jpg](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202017-04-28%20a%20la-s-%2023.26.18-decae19c-0bff-4df1-b4fb-34e9f69c69df.jpg)

Otro caso **GET** donde queremos obtener los datos de un profesor en particular, en este caso el que tiene identificador 1, podríamos hacerlo así:

![https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202017-05-03%20a%20la-s-%2013.38.45-46ef3a98-f43c-4463-b7ef-d45c108b80da.jpg](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202017-05-03%20a%20la-s-%2013.38.45-46ef3a98-f43c-4463-b7ef-d45c108b80da.jpg)

Para el método **POST**, como haremos una inserción de datos tenemos que enviar el objeto Profesor con los datos clave, Postman tiene un campo llamado Body donde envías el objeto en forma de JSON algo así:

![https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202017-05-03%20a%20la-s-%2013.33.27-f73c264f-a802-475d-bcf0-8bb6c24b28e6.jpg](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202017-05-03%20a%20la-s-%2013.33.27-f73c264f-a802-475d-bcf0-8bb6c24b28e6.jpg)

Para el método **PATCH** es muy similar al caso anterior, recuerda que aquí los datos del objeto serán actualizados.

![https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202017-05-03%20a%20la-s-%2013.50.45-eb0c2324-df46-45f6-9a65-260a0c706b41.jpg](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202017-05-03%20a%20la-s-%2013.50.45-eb0c2324-df46-45f6-9a65-260a0c706b41.jpg)

Por último, el método **DELETE** solo necesita que coloquemos en la url el identificador que corresponde al profesor que queremos eliminar, todas las llamadas deben llevar el header _application/json_ si es que así lo marca el API.

![https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202017-05-03%20a%20la-s-%2017.55.14-4cfe6d66-e5f4-465c-9c2a-e0dd965f04a9.jpg](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%202017-05-03%20a%20la-s-%2017.55.14-4cfe6d66-e5f4-465c-9c2a-e0dd965f04a9.jpg)

