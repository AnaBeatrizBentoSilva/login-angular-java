# Login de Usuários em Angular e Java

Este repositório contém um projeto de uma tela de login e cadastro, com front-end desenvolvido em Angular e back-end utilizando Java com Spring Boot. A aplicação oferece funcionalidades de login e registro de usuários.

## 🚀 Objetivo
Criar uma aplicação de login e cadastro de usuários, implementando:
- Angular: Front-end para a interface de login e cadastro.
- Spring Boot (Java): Lógica e estrutura do back-end.

## 🔒 Conceitos Abordados
- Implementação de um sistema de login e cadastro de usuários.
- Comunicação entre front-end e back-end via API RESTful.

## 📂 Estrutura do Repositório

```plaintext
.
├── login-auth-api/
│   ├── .mvn/wrapper/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/login_auth_api/
│   │   │   │   ├── controllers/
│   │   │   │   │   ├── AuthController.java
│   │   │   │   │   └── UserController.java
│   │   │   │   ├── domain/user/
│   │   │   │   │   └── User.java
│   │   │   │   ├── dto/
│   │   │   │   │   ├── LoginRequestDTO.java
│   │   │   │   │   ├── RegisterRequestDTO.java
│   │   │   │   │   └── ResponseDTO.java
│   │   │   │   ├── infra/
│   │   │   │   │   ├── cors/
│   │   │   │   │   │   └── CorsConfig.java
│   │   │   │   │   └── security/
│   │   │   │   │       ├── CustomUserDetailsService.java
│   │   │   │   │       ├── SecurityConfig.java
│   │   │   │   │       ├── SecurityFilter.java
│   │   │   │   │       └── TokenService.java
│   │   │   │   ├── repositories/
│   │   │   │   │   └── UserRepository.java
│   │   │   │   └── LoginAuthApiApplication.java
│   │   │   └── resources/
│   │   │       └── application.properties
│   │   └── test/java/com/example/login_auth_api/
│   │       └── LoginAuthApiApplicationTests.java
│   ├── .gitignore
│   ├── mvnw
│   ├── mvnw.cmd
│   └── pom.xml
├── login-page/
│   ├── .vscode/
│   ├── src/
│   ├── .editorconfig
│   ├── .gitignore
│   ├── README.md
│   ├── angular.json
│   ├── package-lock.json
│   ├── package.json
│   ├── tsconfig.app.json
│   ├── tsconfig.json
│   └── tsconfig.spec.json
├── .DS_Store
└── README.md
