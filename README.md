# Helen Cristina Batista | Portfólio

Portfólio pessoal desenvolvido para apresentar minha trajetória, projetos, conhecimentos técnicos e experiências na área de desenvolvimento Back-End.

O projeto foi construído com foco em uma interface moderna, responsiva e acessível, reunindo informações sobre minha atuação com **Java, Spring Boot, APIs REST e arquitetura de microsserviços**.

## Sobre o projeto

Este repositório contém meu portfólio profissional, desenvolvido para centralizar:

* Apresentação profissional
* Principais projetos desenvolvidos
* Tecnologias e conhecimentos técnicos
* Estudo de caso de arquitetura de software
* Links para GitHub e LinkedIn
* Informações para contato
* Currículo para visualização/download

O portfólio também possui suporte a **tema claro e escuro** e **idiomas português e inglês**.

## Tecnologias

### Desenvolvimento

* HTML5
* JavaScript
* CSS3
* Digital Canvas Runtime
* React Runtime

### Conceitos e tecnologias apresentados

* Java 17
* Spring Boot
* Spring Security
* Spring Data JPA
* Hibernate
* APIs REST
* Arquitetura em camadas
* Microsserviços
* RabbitMQ
* API Gateway
* Eureka
* JWT
* Redis
* Resilience4j
* Micrometer
* Prometheus
* MapStruct
* JUnit 5
* OpenAPI / Swagger

## Projetos em destaque

### API Gateway

**API Gateway enterprise** desenvolvido utilizando Spring Cloud Gateway, com recursos voltados para roteamento, segurança, observabilidade e tolerância a falhas.

Principais tecnologias:

* Spring Cloud Gateway
* Eureka
* JWT
* Redis
* Resilience4j
* Micrometer
* Prometheus

🔗 [Repositório no GitHub](https://github.com/Helencb/api_gateway)

---

### Api_CRM

API REST para gerenciamento de vendas e relacionamento com clientes.

O projeto utiliza uma **arquitetura em camadas** e possui controle de acesso baseado em papéis, autenticação JWT e um fluxo de vendas baseado em máquina de estados.

Entre os principais recursos estão:

* Autenticação e autorização com JWT
* RBAC para gerentes e vendedores
* Gerenciamento de clientes
* Gerenciamento de produtos
* Fluxo de vendas
* Controle de estoque
* Cancelamento de vendas com estorno de estoque
* Lock de banco de dados na finalização da venda
* Documentação com Swagger/OpenAPI
* Testes automatizados

Principais tecnologias:

* Java
* Spring Boot 3.2
* Spring Security 6
* Spring Data JPA
* MapStruct
* JUnit 5
* OpenAPI

🔗 [Repositório no GitHub](https://github.com/Helencb/Api_CRM)

## Arquitetura

Um dos destaques apresentados no portfólio é o fluxo de vendas do `Api_CRM`.

A aplicação utiliza uma arquitetura em camadas para separar responsabilidades e facilitar manutenção e evolução do sistema.

O fluxo de uma venda é representado por estados:

```text
                    ┌─────────────┐
                    │   PENDENTE  │
                    └──────┬──────┘
                           │
                           ▼
                    ┌─────────────┐
                    │  CONCLUÍDA  │
                    └─────────────┘

                           ou

                    ┌─────────────┐
                    │  CANCELADA  │
                    └──────┬──────┘
                           │
                           ▼
                  Estorno do estoque
```

A finalização da venda utiliza controle de concorrência no banco de dados para evitar que dois vendedores consigam finalizar simultaneamente uma venda envolvendo o mesmo estoque disponível.

## Funcionalidades do portfólio

* 🌙 Tema claro e escuro
* 🌎 Português e inglês
* 📱 Layout responsivo
* ⚡ Animações e transições
* ♿ Recursos de acessibilidade
* 📊 Barra de progresso de navegação
* 🔗 Integração com GitHub
* 💼 Integração com LinkedIn
* 📧 Contato por e-mail
* 📄 Currículo disponível no projeto
* 🧩 Seção dedicada à arquitetura de software

## Estrutura do projeto

```text
meu_portfolio/
│
├── index.html
├── support.js
├── README.md
├── cv-helen-cristina-batista.pdf
│
├── uploads/
│   └── ...
│
└── _ds/
    └── ...
```

### Principais arquivos

| Arquivo                         | Descrição                      |
| ------------------------------- | ------------------------------ |
| `index.html`                    | Página principal do portfólio  |
| `support.js`                    | Runtime utilizado pelo projeto |
| `cv-helen-cristina-batista.pdf` | Currículo profissional         |
| `README.md`                     | Documentação do projeto        |

## Como acessar:

```bash
https://helencb-portfolio.vercel.app/
```


## Objetivo

Este projeto faz parte da minha construção de portfólio profissional e tem como objetivo demonstrar, além dos projetos desenvolvidos, minha evolução na área de desenvolvimento de software.

Meu foco atual está no desenvolvimento **Back-End com Java e Spring Boot**, com estudos e projetos envolvendo APIs REST, segurança, bancos de dados, microsserviços, mensageria, observabilidade e arquitetura de software.

## Contato

**Helen Cristina Batista**

* GitHub: [Helencb](https://github.com/Helencb)
* LinkedIn: [Helen Cristina Batista](https://www.linkedin.com/in/hcbatista/)
* E-mail: [h.c.batista2002@gmail.com](mailto:h.c.batista2002@gmail.com)

---

> Portfólio desenvolvido para apresentar projetos, conhecimentos e evolução profissional na área de desenvolvimento Back-End.
