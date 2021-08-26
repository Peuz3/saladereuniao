# Sala de Reunião

Construção de uma aplicação de gerenciamento de salas de reunião Java 11 com Spring Boot e Angular

Primeiramente, acessar o String Initialzr: https://start.spring.io/   

Em Project escolher o Maven e Language: Java.

O Spring Boot utilizado no projeto foi o: 2.5.4

As dependências adicionadas foram:
Spring Web;
Spring Data JPA;
H2 Database;
Lombok

A IDE utilizada foi o IntelliJ 2021 1.3

No aplications properties há a configuração do banco de dados H2, banco de memória, cujo nome é testedb
spring datasource.url = jdbc:h2:mem:testedb 
sprig.datasource.driverClassName=org.h2.Driver
spring.datasource.username=sa
spring.datasource.password=password
spring.jpa.database-plataform=org.hibernate.dialect.H2Dialect
server.port=8080
