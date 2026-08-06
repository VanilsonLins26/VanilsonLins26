<div align="center">

# Vanilson Lins

**Full Stack Developer | .NET & Angular | Clean Architecture & DDD**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vanilson-lins-507597309/)
[![E-mail](https://img.shields.io/badge/E--mail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Vanilson.liins@gmail.com)

</div>

## Sobre Mim

Graduado em Análise e Desenvolvimento de Sistemas pela Universidade de Fortaleza (UNIFOR), com CRA 9.23/10.

Desenvolvo aplicações full stack utilizando **.NET (C#) e Angular**, com foco em arquitetura limpa, testes automatizados e sistemas escaláveis. Meu principal projeto, o **IOrder**, é uma plataforma de delivery com chat em tempo real, pagamentos via Stripe e integração com WhatsApp — aplicando conceitos de **Clean Architecture, DDD, mensageria assíncrona e CI/CD**.

**Disponível para estágio e oportunidades júnior.**

---

## Stack Principal

| Camada | Tecnologias |
|:---|:---|
| **Back-End** | C#, .NET (Core a 10), ASP.NET Core Web API, Entity Framework Core |
| **Front-End** | Angular 20, TypeScript, Signals, RxJS, HTML5/CSS3 |
| **Bancos de Dados** | MySQL, PostgreSQL, Redis |
| **Arquitetura** | Clean Architecture, DDD, SOLID, CQRS |
| **Mensageria** | RabbitMQ, Apache Kafka, SignalR |
| **Qualidade** | xUnit, TestContainers, FluentValidation |
| **DevOps** | Docker, Azure Pipelines, CI/CD |
| **Integrações** | Auth0, Stripe, Cloudinary, WhatsApp (Evolution API) |

---

## Projetos em Destaque

### IOrder - Plataforma de Encomendas & Delivery
> Projeto principal de portfólio. Plataforma SaaS com chat em tempo real, pagamentos e notificações.

![.NET](https://img.shields.io/badge/.NET-10.0-512BD4?style=flat&logo=dotnet)
![Angular](https://img.shields.io/badge/Angular-20-DD0031?style=flat&logo=angular)
![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=flat&logo=mysql)
![Redis](https://img.shields.io/badge/Redis-7.0-DC382D?style=flat&logo=redis)

- Clean Architecture + DDD com segregação read/write
- Chat em tempo real (SignalR + RabbitMQ + dedup via Redis)
- Pagamentos via Stripe (PIX, cartão, boleto)
- Notificações por WhatsApp e E-mail via Domain Events (Kafka)
- Cache distribuído (Cache-Aside com Decorator Pattern)
- CI/CD com Azure Pipelines + TestContainers

**[Ver repositório](https://github.com/VanilsonLins26/IOrder)**

---

### A Nossa Padaria (NPOrder) - Deploy em Produção
> Sistema completo de gestão com e-commerce + dashboard administrativo. **Já em produção.**

![Angular](https://img.shields.io/badge/Angular-19-DD0031?style=flat&logo=angular)
![.NET](https://img.shields.io/badge/.NET-9-512BD4?style=flat&logo=dotnet)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql)

- E-commerce B2C + Backoffice integrados
- Autenticação OIDC via Auth0 (SSO Google)
- Pagamento com Mercado Pago SDK
- Notificações via WhatsApp (Evolution API)
- Deploy automatizado: Vercel (Front) + Render (Back)

**[Demo Online](https://np-order.vercel.app/)** | **[Ver repositório](https://github.com/VanilsonLins26/NPOrder)**

---

### Outros Projetos

| Projeto | Descrição | Stack |
|:---|:---|:---|
| [Sistema de Indicação](https://github.com/VanilsonLins26/SistemaIndicacao) | SPA para gestão de indicações e pontuação (Desafio Vortex) | .NET 9, Angular 17, JWT |
| [API PDV](https://github.com/VanilsonLins26/ApiPDV) | API REST para ponto de vendas com autenticação e paginação | .NET, MySQL, Swagger |
