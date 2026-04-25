# Projetos Spring Boot

Esta pasta concentra as APIs desenvolvidas durante os exercícios. Cada subpasta é um projeto Maven independente.

## Projetos

| Projeto | Objetivo | Principais recursos |
| --- | --- | --- |
| `helloworld` | Primeiro contato com Spring Boot e criação de endpoint REST | Controller simples |
| `farmacia` | CRUD de produtos e categorias | Spring Web, JPA, validação, MySQL |
| `blogpessoal` | API de blog pessoal | Usuários, login, temas, postagens, segurança |
| `loja-games` | API de loja de games | Usuários, login, categorias, produtos, segurança |

## Como executar um projeto

Entre na pasta do projeto escolhido:

```powershell
cd 01-spring-boot\farmacia
.\mvnw.cmd spring-boot:run
```

Em Linux/macOS:

```bash
cd 01-spring-boot/farmacia
./mvnw spring-boot:run
```

## Rotas principais

### helloworld

- `GET /Hello World`

### farmacia

- `/categorias`
- `/produtos`
- Buscas por tipo, nome, laboratório e faixa de preço

### blogpessoal

- `/usuarios`
- `/usuarios/cadastrar`
- `/usuarios/logar`
- `/temas`
- `/postagens`
- Swagger configurado em `/swagger-ui.html`

### loja-games

- `/usuarios`
- `/usuarios/cadastrar`
- `/usuarios/logar`
- `/categorias`
- `/produtos`

## Bancos de dados

Os projetos `farmacia` e `loja-games` apontam para MySQL local em `application.properties`.
O projeto `blogpessoal` usa perfis (`dev`/`prod`) e possui arquivos específicos em `src/main/resources`.

Antes de rodar, confira:

- URL do banco
- Usuário e senha
- Banco MySQL/PostgreSQL instalado e ativo
