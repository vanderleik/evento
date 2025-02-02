# Desafio Modelo de Domínio e ORM

### Formação Desenvolvedor Moderno
### Módulo: Back end
### Capítulo: Modelo de Domínio e ORM

## DESAFIO: Modelo de domínio e ORM
<p>Este projeto é um desafio de programação do curso Java Spring Profissional, do DevSuperior.
Trata-se de uma aplicação Spring Boot, que utiliza banco de dados em memória H2 e implementa o modelo
conceitual especificado no desafio e construindo um seeding da base de dados conforme diagrama de objetos proposto.</p>

## ESPECIFICAÇÃO - Sistema EVENTO:
<p>O sistema construído gerencia as informações dos participantes das atividades de um evento acadêmico. 
As atividades deste evento podem ser, por exemplo, palestras, cursos, oficinas práticas, etc. Cada atividade que ocorre 
possui nome, descrição, preço, e pode ser dividida em vários blocos de horários (por exemplo: um curso de HTML pode 
ocorrer em dois blocos, sendo necessário armazenar o dia e os horários de início de fim do bloco daquele dia). 
Para cada participante, deseja-se cadastrar seu nome e email.</p>


## Tecnologias Utilizadas
- Java
- Spring Boot
- JPA / Hibernate
- Maven
- H2 Database

### Executando a Aplicação
Para executar a aplicação, utilize o Maven para compilar e rodar o projeto:
```bash
mvn spring-boot:run
```

### Acesso ao Banco de Dados
Para acessar o banco de dados H2, acesse o endereço:
```bash
http://localhost:8080/h2-console
```
- JDBC URL: jdbc:h2:mem:testdb
- User Name: sa
- Password: 

