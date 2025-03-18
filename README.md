# Workshop 
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" />

# Sobre o projeto

Este Workshop é uma aplicação back end construída durante o curso de Java Completo, organizado pelo professor Nelio Alves.

A aplicação consiste em um modelo de **Web service**, com programação orientada a objetos e mapeamento objeto-relacional. Neste projeto podemos criar e preencher um banco de dados com tabelas e colunas de Clientes, Produtos, Categorias, Pedidos, Itens de pedido, Pagamento e Status de Pedido. 

## Objetivos 
* Criar projeto Spring Boot Java 
* Implementar modelo de domínio 
* Estruturar camadas lógicas: resource, service, repository 
* Configurar banco de dados de teste (H2) 
* Povoar o banco de dados 
* CRUD - Create, Retrieve, Update, Delete 
* Tratamento de exceções
  

## Layout 
![Layout 1](https://github.com/user-attachments/assets/b03389b7-a784-4e0c-91bf-2cc352644ed4) 


![image](https://github.com/user-attachments/assets/c3fd4ee4-fc87-4681-9cf5-e5efad639971)





## Modelo conceitual
![Modelo Conceitual](https://github.com/user-attachments/assets/6f09fe0d-f208-48a9-8931-56568bd267d4)


![Modelo Conceitual](https://github.com/user-attachments/assets/3a15607f-4514-46b5-9c54-8ac43cf479ac)





# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven

## Implantação em produção
- Back end: Heroku
- API teste: Postman
- Banco de dados: H2, e Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 17

```bash
# clonar repositório
git clone https://github.com/Delfalas/workshop-springboot3-jpa

# entrar na pasta do projeto back end

# executar o projeto
./mvnw spring-boot:run
```


## Como povoar o banco de dados

**No arquivo TestConfig.java**


![image](https://github.com/user-attachments/assets/87fbc09c-39d3-468a-b1a1-d3614fe9f234)

**User insert no Postman:**


![image](https://github.com/user-attachments/assets/c616af16-44ad-49aa-a1f0-ce38f06b3e4a)

**User update no Postman:**


![image](https://github.com/user-attachments/assets/c728af74-f2e0-4608-861d-7c53f6a23046)



# Autor

Vinicius Dantas Alverte Ferreira

https://www.linkedin.com/in/vinicius-dantas-alverte-ferreira/
