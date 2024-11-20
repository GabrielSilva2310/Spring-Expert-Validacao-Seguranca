# Java Spring Expert Desafio: Validação e Segurança 


# Sobre o projeto
Este projeto é o desafio do capítulo sobre Validação e Segurança do Curso Java Spring Expert da [DevSuperior](https://devsuperior.com.br "Site da DevSuperior").
O desafio consiste em implementar as funcionalidades necessárias para que os testes passem.


## Especificações e Modelo Conceitual
Este é um sistema de funcionários e departamentos com uma relação N-1 entre eles:
![Modelo Conceitual](https://github.com/GabrielSilva2310/Assets/blob/main/Images%20Java%20Spring%20Expert/Valida%C3%A7%C3%A3o%20e%20Seguran%C3%A7a/Modelo%20Conceitual%20Desafio.png)


Regras de controle de acesso:

-Somente rotas de leitura (GET) de eventos e cidades são públicas (não requer login).

-Usuários CLIENT e/ou ADMIN podem inserir novos eventos (POST).

-Os demais acessos são permitidos apenas a usuários ADMIN.

Regras de validação de City:

-Nome não pode ser vazio

-Regras de validação de Event:

-Nome não pode ser vazio

-Data não pode ser passada

-Cidade não pode ser nula



# Tecnologias utilizadas
- Java 17
- Spring Boot 3
- Maven
- JPA / Hibernate
- H2 Database
- JUnit 5
- Postman

# Postman Collection
  Para testar a API, você pode usar a coleção do Postman disponível no link abaixo:
  
  [Download](https://github.com/GabrielSilva2310/Assets/blob/main/Postman%20Collections%20and%20Enviroments/Spring%20Expert/Desafio%20Valida%C3%A7%C3%A3o%20e%20Seguran%C3%A7a/Desafio%20Valida%C3%A7%C3%A3o%20e%20Seguran%C3%A7a.postman_collection%20(1).json)

# Como executar o projeto

Pré-requisitos: Java 17

```bash
# clonar repositório
git clone https://github.com/GabrielSilva2310/Spring-Expert-Validacao-Seguranca.git
```
Importar Projeto para uma IDE de sua escolha , e executar o JUnit nas classes CityControllerIT.java e EvetnControllerIT.java.

Use o Postman para fazer as requisições e verificar se os resultados correspondem aos testes.

# Competências avaliadas no desafio
- Desenvolvimento TDD de API Rest com Java e Spring Boot
- Implementação de segurança com Spring Security e OAuth2
- Controle de acesso por rotas e perfis de usuário
- Validação de dados com Bean Validation

# Autor

Gabriel Da Silva 

www.linkedin.com/in/gabriel-da-silva-457039193
