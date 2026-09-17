<h1 align="center">Rodrigo Lutfy</h1>

<p align="center">
  <strong>Dev Backend</strong><br/>
  JAVA · SPRING BOOT · SPRING SECURITY · REST APIs · SQL · DOCKER
</p>

<p align="center">
  Cursando Engenharia de Software.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/rodrigo-lutfy">LinkedIn</a>
  ·
  <a href="mailto:[seu e-mail]">E-mail</a>
</p>

## O que construo

Desenvolvo aplicações de retaguarda em Java, com foco nas decisões estruturais que determinam se um sistema resiste ao uso real. Não só nas rotas que respondem, mas no que sustenta cada uma delas: o modelo de dados, o controle de acesso, a integridade da transação.

Meu ponto de partida é simples: uma regra de negócio que existe apenas no código da aplicação não existe de verdade. Por isso trabalho com restrições declarativas no banco, esquema versionado por migrações e controle de concorrência delegado a quem já o garante — sem perder de vista a clareza da interface que está sendo exposta.


## Painel técnico

| Camada | Stack e práticas |
| :--- | :--- |
| Aplicação | Java 17, Spring Boot, APIs REST, organização de pacotes por domínio |
| Segurança | Spring Security, JWT, BCrypt, autorização por papel e por propriedade |
| Persistência | PostgreSQL, Spring Data JPA, Hibernate, Flyway, modelagem relacional |
| Interface | DTOs por operação, paginação, tratamento centralizado de erro, Swagger |
| Ferramentas | Maven, Git, Docker, Insomnia, Linux |

## Projetos em destaque

### 01 / Ticketfy API

Sistema de venda de ingressos para eventos · projeto pessoal em desenvolvimento

- Modelei o domínio de eventos e lotes de ingresso com esquema versionado em Flyway, restrições de integridade declarativas e exclusão lógica para preservar histórico.
- Implementei autenticação JWT com dois regimes de autorização: por papel, na borda HTTP, e por propriedade do recurso, na camada de serviço.
- Resolvi a venda concorrente com atualização condicional no banco, garantindo que dois compradores simultâneos nunca levem o mesmo ingresso.
- Centralizei o tratamento de erro, mapeando cada condição de falha ao código de situação HTTP correspondente.
- Documentei as decisões de arquitetura e as alternativas descartadas, incluindo o comparativo entre as estratégias de controle de concorrência avaliadas.


## Em evolução

Testes automatizados · Testcontainers · Docker e Docker Compose · Integração com gateway de pagamento · Processamento assíncrono · Idempotência


---

<p align="center">
  Aberto a conversar sobre backend, arquitetura de APIs e modelagem de dados.<br />
  <a href="https://www.linkedin.com/in/rodrigo-lutfy">Vamos nos conectar.</a>
</p>
