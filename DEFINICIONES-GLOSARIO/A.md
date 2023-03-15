**API**:  Application Programming Interface, (interfaz de programación de aplicaciones), conjunto de estructuras que permiten que los componentes de un SW se comuniquen con otros. Permite el acceso a desarrolladores de otros programas a ciertas partes de su biblioteca para llevar a cabo determinadas acciones. **La capacidad que tiene un software para comunicar**

![[Pasted image 20230302162934.png]]


**API REST:** interfície 

![[Pasted image 20230302162838.png]]

Una API REST es una forma de permitir que diferentes programas de ordenador se comuniquen entre sí a través de Internet. Ya que la comunicación debe darse a través de protocolos y estándares para enviar y recibir datos, estas APIs están diseñadas bajo los principios de **REST** (que significa **Representational State Transfer)** y son útiles para interacciones simples.

En otras palabras, son el puente de comunicación entre frontend y backend.

## Principios de una API REST (API RESTful)

Una API RESTful es una interfaz que utiliza los principios de REST para comunicarse hacia y desde un servidor.

El principio más importante en las APIs RESTful es el uso de los métodos HTTP:

-   GET
-   POST
-   PUT
-   DELETE

Estos métodos son empleados por los clientes para crear, manipular y eliminar datos en los servidores, respectivamente.

### Tabla de métodos sobre API REST

![https://static.platzi.com/media/user_upload/REST-65e4240f-662b-406e-91c9-57d8b0dd56f4-8f3dbe2f-62b7-4991-a5aa-db4a71418204.jpg](https://static.platzi.com/media/user_upload/REST-65e4240f-662b-406e-91c9-57d8b0dd56f4-8f3dbe2f-62b7-4991-a5aa-db4a71418204.jpg)

## Elementos de una API REST o API RESTful

Para que una API sea REST esta debe de funcionar bajo tres conceptos:

-   **Recurso:** todo dentro de una API RESTful debe ser un recurso.
-   **URI:** los recursos en REST siempre se manipulan a partir de la URI, identificadores universales de recursos.
-   **Acción:** todas las peticiones a tu API RESTful deben estar asociadas a uno de los verbos de HTTP: GET para obtener un recurso, POST para escribir un recurso, PUT para modificar un recurso y DELETE para borrarlo.

## ¿Cuál es la diferencia entre API y API REST (RESTful)

Una API ( acrónimo que significa **Interfaz de Programación de Aplicaciones -Application Programming Interface) es una interfaz que permite que diferentes programas de ordenador se comuniquen entre sí, mientras que una API REST es un tipo de API que sigue un conjunto de reglas y estándares que la hacen más fácil de usar y más compatible con otras aplicaciones.

De esta manera, una API REST puede ser una buena opción para permitir que diferentes aplicaciones se integren de manera más sencilla.

> [Conoce más sobre verbos HTTP.](https://platzi.com/clases/1912-intro-elasticsearch/28689-verbos-http/)

## Qué es REST

REST es un estilo de arquitectura de software enfocado en el intercambio de recursos y basado en HTTP. Le agrega una capa muy delgada de complejidad y abstracción a HTTP. Mientras que HTTP es transferencia de archivos, REST se basa en la **transferencia de recursos**.

### **En qué casos sí conviene usar REST:**

Conviene usarlo cuando las interacciones son simples, dónde lo que queremos hacer son las operaciones básicas de crear un recurso, quitar recursos o modificarlos. También cuando los recursos de hardware son limitados, por que como es muy cercano al HTTP no hay más que necesitemos instalar.

### Cúando no conviene usar REST**:

Cuando las interacciones son un poco más complejas, es decir necesitamos que el servidor aporte más lógica, ejemplo: la validación de algún documento.

## Cómo funciona REST

REST es un conjunto de principios que definen la forma en que se deben crear, leer, actualizar y eliminar los datos. Es una arquitectura conocida como **cliente-servidor**, en la que el servidor y el cliente actúan de forma independiente, siempre y cuando la interfaz sea la misma al procesar una solicitud y una respuesta, que son los elementos esenciales.

**El servidor expone la API REST y el cliente hace uso de ella**. El servidor almacena la información y la pone a disposición del usuario, mientras que el cliente toma la información y la muestra al usuario o la utiliza para realizar posteriores peticiones de más información.

![https://static.platzi.com/media/user_upload/Captura-d336ab2e-8e2d-40a4-808a-ee3da1fbdaef-597e9e5e-eae6-4151-b617-7e145404d7ab.jpg](https://static.platzi.com/media/user_upload/Captura-d336ab2e-8e2d-40a4-808a-ee3da1fbdaef-597e9e5e-eae6-4151-b617-7e145404d7ab.jpg)

REST es muy útil cuando:

-   Las interacciones son simples.
-   Los recursos de tu hardware son limitados.