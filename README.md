## Swagger Implementation
al seguir el tutorial de la documentacion de SpringBoot https://www.baeldung.com/swagger-2-documentation-for-spring-rest-api
encontramos que al poner @EnableSwagger2 en la clase Config de SwaggerFox tenemos el siguinete error Springfox Type javax.servlet.http.HttpServletRequest not present
y consultando en StackOverflow encontramos lo siguinete:

![](.README_images/1bfcf89d.png)

una vez puesta las dependencias
![](.README_images/f12876ac.png)
accedemos al endpoint de la documentacion de swagger en:
``http://localhost:8080/swagger-ui/index.html``

![](.README_images/079bb28b.png)