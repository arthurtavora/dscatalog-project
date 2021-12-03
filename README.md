# DSCatalog 

## Sobre o projeto (Em desenvolvimento)

DSCatalog é uma aplicação full stack web que venho desenvolvendo durante o módulo Spring-React da instituição de ensino [DevSuperior](https://devsuperior.com.br/ "Site da DevSuperior").

A aplicação consiste em um catálogo de venda de produtos, onde os dados são cadastrados pelo usuário (admin) e depois são listados no app web.

## Layout mobile
![Mobile 1](https://github.com/arthurtavora/dscatalog-project/blob/main/frontweb/src/assets/images/layout-mobile.png) 

## Layout web
![Web 1](https://github.com/arthurtavora/dscatalog-project/blob/main/frontweb/src/assets/images/layout-web.png)

![Web 2](https://github.com/arthurtavora/dscatalog-project/blob/main/frontweb/src/assets/images/crud-web.png)

## Modelo conceitual
![Modelo Conceitual](https://github.com/arthurtavora/dscatalog-project/blob/main/frontweb/src/assets/images/modelo-conceitual.png)

# Tecnologias utilizadas
## Back end
- Back end desenvolvido em camadas lógicas (Controlador REST, Camada de Serviço e Camada de Acesso a dados (Repository), utilizando o padrão DTO para o tráfego de dados)
- Java
- Spring Boot
- JPA / Hibernate
- Maven
- JPQL
- JUnit
- Mockito & MockBean
- Validação com Bean Validation
- Autenticação e autorização (Spring Security, OAuth 2.0, Token JWT, Autorização de rotas por perfil)
## Front end (Ainda em desenvolvimento)
- HTML / CSS / JS / TypeScript
- ReactJS

## Implantação em produção (Ainda em desenvolvimento)

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/arthurtavora/dscatalog-project.git

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

## Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/arthurtavora/dscatalog-project.git

# entrar na pasta do projeto front end web
cd frontweb

# instalar dependências
yarn install

# executar o projeto
yarn start
