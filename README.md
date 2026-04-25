# Bloco 2 - Generation

Repositório reorganizado com os exercícios antigos do Bloco 2 da Generation.
O objetivo desta estrutura é deixar claro o que foi desenvolvido, onde está cada entrega e como retomar os projetos.

## Estrutura

```text
Bloco2-GEN-main/
├── 01-spring-boot/      # APIs e exercícios Java com Spring Boot
├── 02-banco-de-dados/   # Exercícios SQL/MySQL
├── 03-modelagem-der/    # DER, scripts e diagramas do banco
└── 04-evidencias/       # Prints e registros de execução/deploy
```

## Projetos principais

| Pasta | Descrição | Tecnologias |
| --- | --- | --- |
| `01-spring-boot/helloworld` | Primeiro endpoint REST com Spring Boot | Java 17, Spring Web |
| `01-spring-boot/farmacia` | API CRUD para produtos e categorias de farmácia | Java 17, Spring Boot, JPA, MySQL |
| `01-spring-boot/blogpessoal` | API de blog pessoal com usuários, temas e postagens | Java 17, Spring Boot, JPA, Security, MySQL/PostgreSQL |
| `01-spring-boot/loja-games` | API de loja de games com autenticação, produtos e categorias | Java 17, Spring Boot, JPA, Security, MySQL |

## Como navegar

- Para rodar as APIs, veja [`01-spring-boot/README.md`](01-spring-boot/README.md).
- Para revisar os scripts SQL, veja [`02-banco-de-dados/README.md`](02-banco-de-dados/README.md).
- Para consultar DER e modelagem, veja [`03-modelagem-der/README.md`](03-modelagem-der/README.md).
- Para conferir prints antigos, veja [`04-evidencias/README.md`](04-evidencias/README.md).

## Observações

- As pastas `bin/` dentro dos projetos parecem ser cópias geradas pela IDE na época. O código principal está em `src/`.
- Os projetos usam versões antigas do Spring Boot da época dos exercícios (`2.6.x`).
- Algumas configurações usam banco local com usuário e senha `root/root`; ajuste conforme o seu MySQL atual antes de executar.
