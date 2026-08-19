# Spring Boot Clean Architecture

Projeto desenvolvido para demonstrar a implementação de uma aplicação utilizando **Clean Architecture** com **Spring Boot**.

A aplicação foi estruturada buscando separar as responsabilidades entre as camadas de domínio, casos de uso, infraestrutura e interfaces, facilitando a manutenção, testabilidade e evolução do sistema.

## Tecnologias

- Java
- Spring Boot
- Spring MVC
- Spring Data JDBC
- Maven
- H2 Database

## Arquitetura

O projeto utiliza conceitos de **Clean Architecture**, separando a aplicação em camadas como:

- **Domain** — regras de negócio e entidades.
- **Application** — casos de uso da aplicação.
- **Infrastructure** — persistência, banco de dados e implementações externas.
- **Adapters / Interfaces** — controllers e comunicação com o mundo externo.

O objetivo é reduzir o acoplamento entre as regras de negócio e frameworks ou tecnologias específicas.

## Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/GustavoFontanaa/spring-clean-arch.git
```

```bash
cd spring-boot-cleanarch
```

```bash
.\mvnw clean package
```

```bash
java -jar ./target/spring-boot-cleanarch-0.0.1-SNAPSHOT.jar
```