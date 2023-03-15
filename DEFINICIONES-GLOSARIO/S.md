**SERVERLESS:**

**SCOPE:** en programación todo el párrafo englobado entre \{ \} **corchetes** 

**SCRIPT:**


**SPRING BOOT PATTERN:** Mirar Libreta 02/03/2023

![[Pasted image 20230302162710.png]]

Controller ----> manage of te REST interface to the business logic  
Service -------> Business logic interpretations  
Repository ---> Storage of the entity beans in the system

![Pasted image 20230302112801.png](app://local/C:/Users/alber/Dropbox/OBSIDIAN%20COPIA%20160123/NOTAS/SOFTWARE/DEVOPS/DEFINICIONES/ANEXOS/Pasted%20image%2020230302112801.png?1677752881750)

Si el código está relacionado con el almacenamiento/recuperación, debe ir al Repositorio. Si se trata de exponer la funcionalidad, va en el Controlador. Todo lo que sea único en la lógica de negocio iría a la capa de servicio.

Al Repositorio no le importa qué componente lo está invocando; ciegamente hace lo que se le pide.

A la capa de Servicio no le importa cómo se accede a ella, simplemente hace su trabajo, usando un Repositorio donde sea necesario.

Y el controlador simplemente pasa el trabajo a la capa de servicio, por lo que puede mantenerse agradable y eficiente.

![Pasted image 20230302115321.png](app://local/C:/Users/alber/Dropbox/OBSIDIAN%20COPIA%20160123/NOTAS/SOFTWARE/DEVOPS/DEFINICIONES/ANEXOS/Pasted%20image%2020230302115321.png?1677754401555)

Fuente: [https://www.linkedin.com/pulse/spring-que-significa-repository-service-controller-adrián-pol-alcalá-/?originalSubdomain=es](https://www.linkedin.com/pulse/spring-que-significa-repository-service-controller-adri%C3%A1n-pol-alcal%C3%A1-/?originalSubdomain=es)

Al tener una separación por capas es más fácil poder modificar, crear, añadir sin que una capa afecte a la otra.

Fuente: [https://tom-collings.medium.com/controller-service-repository-16e29a4684e5](https://tom-collings.medium.com/controller-service-repository-16e29a4684e5)

