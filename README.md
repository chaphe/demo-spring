# demo-spring
Application demo usando Spring boot y maven como herramienta de build

__Para compilar:__
_mvn compile_

__Para ejecutar Tests:__
_mvn test_

__Para crear artefacto de despliegue (.jar)__
_mvn package_

__Para ejecutar usando spring pluging__ _mvn spring-boot:run_ 

__Para ejecutar usando el artefacto generado__ _java -jar target/demo-spring-0.0.1-SNAPSHOT.jar_ 

__Para probar__

- GET en [http://localhost:8090/demo/greeting](http://localhost:8090/demo/greeting) 

- GET en [http://localhost:8090/demo/greeting](http://localhost:8090/demo/greeting) parametro name

- POST en [http://localhost:8090/demo/register](http://localhost:8090/demo/registar) parametros: name y lang (valores posibles EN, ES o FR)




