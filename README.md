<h1 align="center">Rodrigo Lutfy</h1>

<p align="center">
  <strong>Backend Developer</strong><br />
  JAVA · SPRING BOOT · POSTGRESQL · REST · SEGURANÇA
</p>

<p align="center">
  Transformando regra de negócio em APIs que resistem ao uso real.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/rodrigo-lutfy">LinkedIn</a>
  ·
  <a href="https://github.com/rodrigolutfydev">GitHub</a>
  ·
  <a href="mailto:[seu e-mail]">E-mail</a>
</p>

<br />

## O que construo

Desenvolvo aplicações de retaguarda em Java, com foco nas decisões estruturais que determinam se um sistema resiste ao uso real. Não só nas rotas que respondem, mas no que sustenta cada uma delas: o modelo de dados, o controle de acesso, a integridade da transação.

Meu ponto de partida é simples: uma regra de negócio que existe apenas no código da aplicação não existe de verdade. Por isso trabalho com restrições declarativas no banco, esquema versionado por migrações e controle de concorrência delegado a quem já o garante — sem perder de vista a clareza da interface que está sendo exposta.

<br />

## Painel técnico

| Camada | Stack e práticas |
| :--- | :--- |
| Aplicação | Java 17, Spring Boot, APIs REST, organização de pacotes por domínio |
| Segurança | Spring Security, JWT, BCrypt, autorização por papel e por propriedade |
| Persistência | PostgreSQL, Spring Data JPA, Hibernate, Flyway, modelagem relacional |
| Interface | DTOs por operação, paginação, tratamento centralizado de erro, Swagger |
| Ferramentas | Maven, Git, Docker, Insomnia, Linux |

<br />

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white" alt="Spring Security" />
  <img src="https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white" alt="Flyway" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</p>

<br />

## Projetos em destaque

### 01 / Ticketfy API

Sistema de venda de ingressos para eventos · projeto pessoal em desenvolvimento

- Modelei o domínio de eventos e lotes de ingresso com esquema versionado em Flyway, restrições de integridade declarativas e exclusão lógica para preservar histórico.
- Implementei autenticação JWT com dois regimes de autorização: por papel, na borda HTTP, e por propriedade do recurso, na camada de serviço.
- Resolvi a venda concorrente com atualização condicional no banco, garantindo que dois compradores simultâneos nunca levem o mesmo ingresso.
- Centralizei o tratamento de erro, mapeando cada condição de falha ao código de situação HTTP correspondente.
- Documentei as decisões de arquitetura e as alternativas descartadas, incluindo o comparativo entre as estratégias de controle de concorrência avaliadas.

<br />

## Em evolução

Testes automatizados · Testcontainers · Docker e Docker Compose · Integração com gateway de pagamento · Processamento assíncrono · Idempotência

<br />

---

<p align="center">
  Aberto a conversar sobre backend, arquitetura de APIs e modelagem de dados.<br />
  <a href="https://www.linkedin.com/in/rodrigo-lutfy">Vamos nos conectar.</a>
</p>
