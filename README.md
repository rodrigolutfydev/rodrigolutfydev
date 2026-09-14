<h1 align="center">Rodrigo Lutfy</h1>

<p align="center">
  <strong>Backend Developer</strong><br />
  Java &nbsp;·&nbsp; Spring Boot &nbsp;·&nbsp; PostgreSQL
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/rodrigo-lutfy">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://www.instagram.com/rodrigo_lutfy">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
</p>

<br />

---

<h2 align="center">Sobre</h2>

<p align="center">
  Estudante de Engenharia de Software, dedicado ao desenvolvimento de aplicações<br />
  de retaguarda em Java. Construo APIs REST com Spring Boot, com atenção às<br />
  decisões estruturais que determinam se um sistema resiste ao uso real:<br />
  modelagem de dados, controle de acesso, integridade transacional<br />
  e comportamento sob requisições concorrentes.
</p>

<p align="center">
  Documento as decisões de arquitetura que tomo e as alternativas que descarto,<br />
  porque escolha registrada pode ser revista — escolha implícita, não.
</p>

<br />

---

<h2 align="center">O que desenvolvo</h2>

<br />

<p align="center">
  <strong>APIs REST</strong><br />
  Interfaces organizadas por domínio, com objetos de transferência específicos<br />
  por operação, respostas paginadas e tratamento de erro centralizado,<br />
  mapeando cada condição de falha ao código de situação HTTP correspondente.
</p>

<br />

<p align="center">
  <strong>Modelagem e persistência</strong><br />
  Esquema versionado por migrações, restrições declarativas no banco,<br />
  exclusão lógica em entidades que sustentam histórico<br />
  e representação monetária em tipo decimal exato.
</p>

<br />

<p align="center">
  <strong>Segurança</strong><br />
  Autenticação por token assinado e dois regimes de autorização:<br />
  por papel, para definir quem pode executar uma operação,<br />
  e por propriedade, para definir sobre quais recursos ela pode agir.
</p>

<br />

<p align="center">
  <strong>Concorrência</strong><br />
  Controle de estoque finito sob requisições simultâneas,<br />
  delegando a decisão de disponibilidade ao banco de dados<br />
  em operação atômica, sem bloqueio explícito.
</p>

<br />

---

<h2 align="center">Stack</h2>

<div align="center">

| Camada | Tecnologias |
| :--- | :--- |
| Linguagem | Java 17 |
| Framework | Spring Boot, Spring Data JPA, Spring Security |
| Persistência | PostgreSQL, Hibernate, Flyway |
| Autenticação | JWT |
| Infraestrutura | Docker |
| Ferramentas | Maven, Git, Insomnia, Swagger |

</div>

<br />

---

<h2 align="center">Projeto em destaque</h2>

<p align="center">
  <strong><a href="https://github.com/rodrigolutfydev/Ticketfy-API">Ticketfy API</a></strong><br />
  Sistema de venda de ingressos para eventos
</p>

<p align="center">
  A venda de ingressos é um domínio enganosamente simples. A operação visível<br />
  esconde restrições que só aparecem sob carga: o estoque é finito e indivisível,<br />
  a demanda se concentra em janelas curtas, o pagamento é confirmado por um<br />
  terceiro e o registro financeiro precisa permanecer imutável depois de emitido.
</p>

<br />

<div align="center">

| Aspecto | Decisão |
| :--- | :--- |
| Arquitetura | Camadas com organização de pacotes por domínio |
| Venda concorrente | Atualização condicional no banco, sem bloqueio |
| Valores monetários | Tipo decimal exato, nunca ponto flutuante |
| Histórico financeiro | Preço congelado no pedido, não referenciado |
| Autorização | Por papel na borda, por propriedade no serviço |
| Esquema | Migrações versionadas e validadas na inicialização |

</div>

<br />

<p align="center">
  O projeto acompanha documento de arquitetura com o registro formal<br />
  das decisões, o modelo de dados, a matriz de controle de acesso<br />
  e a análise das estratégias de concorrência avaliadas.
</p>

<br />

---

<h2 align="center">Como trabalho</h2>

<p align="center">
  Prefiro o mecanismo mais simples que ofereça a garantia necessária.<br />
  Uma solução sofisticada sem o problema que a justifique é custo sem retorno.
</p>

<p align="center">
  Commits seguem convenção semântica, código e documentação em inglês,<br />
  e cada domínio concentra em um pacote tudo que o realiza.
</p>

<br />

---

<p align="center">
  <a href="https://www.linkedin.com/in/rodrigo-lutfy">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/rodrigolutfydev">GitHub</a>
</p>
