<h1 align="center">Rodrigo Lutfy</h1>

<p align="center">
  <strong>Desenvolvedor Backend</strong><br/>
  Java · Spring Boot · Spring Security · PostgreSQL · Docker
</p>

<p align="center">
  Estudante de Engenharia de Software
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/rodrigo-lutfy">LinkedIn</a>
  ·
  <a href="mailto:rodrigolutfy.dev@gmail.com">E-mail</a>
</p>

## O que construo

Desenvolvo APIs em Java com foco nas decisões que determinam se um sistema resiste ao uso real: o modelo de dados, o controle de acesso e a integridade das transações.

Parto de um princípio simples: uma regra de negócio que existe apenas no código da aplicação não está garantida. Por isso uso restrições no banco, esquema versionado por migrações e controle de concorrência delegado a quem já o garante, sem perder de vista a clareza da API exposta.

## Painel técnico

| Camada | Stack e práticas |
| :--- | :--- |
| Aplicação | Java 17, Spring Boot, APIs REST, Bean Validation |
| Segurança | Spring Security, JWT, BCrypt, autorização por papel e por propriedade |
| Persistência | PostgreSQL, Spring Data JPA, Hibernate, Flyway |
| Testes | JUnit 5, Testcontainers |
| Entrega | Docker, Docker Compose, GitHub Actions, Spring Boot Actuator, Render, Neon |
| Ferramentas | Maven, Git, IntelliJ IDEA, Insomnia, Linux |

## Projeto em destaque

### Ticketfy API

API de venda de ingressos para eventos · em produção

[Repositório](https://github.com/rodrigolutfydev/Ticketfy-API)

- **Fluxo completo de venda:** eventos, lotes, pedidos com reserva temporária e expiração automática, pagamento simulado, emissão de ingressos com código único, check-in na entrada e reembolso.
- **Concorrência tratada no banco:** atualização condicional de estoque, verificada por teste com dez requisições disputando o último ingresso; bloqueio otimista entre pagamento e expiração; índice único parcial contra pagamento duplicado; chave de idempotência contra clique duplo.
- **Segurança:** autenticação JWT, autorização por papel e por propriedade do recurso, limite de tentativas de login, CORS restrito e segredos fora do código.
- **Modelagem:** valores em `BigDecimal` e `NUMERIC`, preço congelado no pedido, instantes em `TIMESTAMPTZ`, exclusão lógica e consultas sem N+1.
- **Entrega:** imagem Docker em dois estágios, testes de integração com Testcontainers, CI no GitHub Actions, health check, encerramento gracioso e deploy no Render com PostgreSQL no Neon.
- **Documentação:** documento de arquitetura com registro de decisões (ADRs), diagramas UML, dicionário de dados e matriz de riscos.

## Em evolução

Envio de ingressos por e-mail com QR code · Recuperação de senha · Pagamento via Pix com webhook · Processamento assíncrono com padrão outbox · Ampliação da cobertura de testes

---

<p align="center">
  Em busca de uma oportunidade como desenvolvedor backend.<br/>
  Aberto a conversar sobre arquitetura de APIs e modelagem de dados.<br/>
  <a href="https://www.linkedin.com/in/rodrigo-lutfy">Vamos nos conectar.</a>
</p>
