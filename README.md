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
│   │   ├── app/
│   │   │   ├── components
│   │   │   │   ├── default-login-layout/
│   │   │   │   │   ├── default-login-layout.component.html
│   │   │   │   │   ├── default-login-layout.component.scss
│   │   │   │   │   ├── default-login-layout.component.spec.ts
│   │   │   │   │   └── default-login-layout.component.ts
│   │   │   │   └── primary-input/
│   │   │   │       ├── primary-input.component.html
│   │   │   │       ├── primary-input.component.scss
│   │   │   │       ├── primary-input.component.spec.ts
│   │   │   │       └── primary-input.component.ts
│   │   │   ├── pages
│   │   │   │   ├── login/
│   │   │   │   │   ├── login.component.html
│   │   │   │   │   ├── login.component.scss
│   │   │   │   │   ├── login.component.spec.ts
│   │   │   │   │   └── login.component.ts
│   │   │   │   ├── signup/
│   │   │   │   │   ├── signup.component.html
│   │   │   │   │   ├── signup.component.scss
│   │   │   │   │   ├── signup.component.spec.ts
│   │   │   │   │   └── signup.component.ts
│   │   │   │   └── user/
│   │   │   │       ├── user.component.html
│   │   │   │       ├── user.component.scss
│   │   │   │       ├── user.component.spec.ts
│   │   │   │       └── user.component.ts
│   │   │   ├── services
│   │   │   │   ├── auth-guard.service.spec.ts
│   │   │   │   ├── auth-guard.service.ts
│   │   │   │   ├── login.service.spec.ts
│   │   │   │   └── login.service.ts
│   │   │   ├── types
│   │   │   │   └── login-response.type.ts
│   │   │   ├── app.component.html
│   │   │   ├── app.component.scss
│   │   │   ├── app.component.spect.ts
│   │   │   ├── app.component.ts
│   │   │   ├── app.config.ts
│   │   │   └── app.routes..ts
│   │   ├── assets/
│   │   │   ├── svg/
│   │   │   │   ├── email-icon.svg
│   │   │   │   ├── logo.svg
│   │   │   │   ├── main-ilustration.svg
│   │   │   │   └── password-icon.svg
│   │   │   └── .gitkeep
│   │   ├── styles/
│   │   ├── favicon.ico
│   │   ├── index.html
│   │   ├── main.ts
│   │   └── styles.scss
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
