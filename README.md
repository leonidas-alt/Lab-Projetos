# Lab Projetos — Dicionário Técnico do ZYRON

O **Lab Projetos** é a base de conhecimento do projeto ZYRON. Ele reúne estudo, documentação, comandos, decisões técnicas e preparação para entrevistas em arquivos Markdown separados por assunto.

## Objetivo

Este repositório existe para ajudar você a:

- aprender Python de forma progressiva;
- entender arquitetura de software aplicada ao ZYRON;
- consultar comandos de Git, Docker, Linux, APIs e banco de dados;
- registrar decisões técnicas;
- estudar para entrevistas;
- acompanhar sua evolução sem depender totalmente de inteligência artificial.

## Organização

Cada conceito fica em um arquivo próprio. Não misturamos assuntos diferentes no mesmo documento.

## Índice principal

- [01-python](01-python/README.md) — fundamentos, controle de fluxo, estruturas de dados, funções, POO, testes e bibliotecas.
- [02-git-github](02-git-github/README.md) — conceitos, comandos, branches, commits, pull requests e problemas comuns.
- [03-arquitetura](03-arquitetura/README.md) — POO, SOLID, Clean Architecture, design patterns, DDD e decisões arquiteturais.
- [04-zyron](04-zyron/README.md) — visão geral, IA, voz, memória, comandos, automações, integrações, segurança, banco e arquitetura.
- [05-banco-de-dados](05-banco-de-dados/README.md) — SQL, PostgreSQL, SQLite, modelagem, SQLAlchemy e migrações.
- [06-apis](06-apis/README.md) — conceitos de APIs, REST, FastAPI, autenticação e integrações.
- [07-devops-infra](07-devops-infra/README.md) — Linux, WSL, Docker, Kubernetes, AWS, CI/CD e GitHub Actions.
- [08-qualidade](08-qualidade/README.md) — Clean Code, refatoração, testes, logging, segurança e performance.
- [09-glossario](09-glossario/README.md) — termos gerais, siglas e vocabulário específico do ZYRON.
- [PROGRESSO.md](PROGRESSO.md) — acompanhamento dos estudos.

## Como localizar conteúdos

1. Escolha a área principal pelo índice acima.
2. Abra o `README.md` da área.
3. Acesse o arquivo do conceito desejado.
4. Use os exercícios e perguntas de entrevista para revisar.

## Como adicionar novos conceitos

1. Crie um arquivo Markdown com nome em letras minúsculas, sem acentos, sem espaços e separado por hífen.
2. Coloque apenas um conceito por arquivo.
3. Use a estrutura obrigatória: definição, propósito, sintaxe, funcionamento, exemplos, uso no ZYRON, erros, boas práticas, entrevista e exercícios.
4. Atualize o `README.md` da pasta principal.
5. Atualize o `PROGRESSO.md`.

## Como estudar

Comece por `01-python/fundamentos/python.md`, avance pelos fundamentos, depois controle de fluxo, estruturas de dados, funções e POO. Em seguida, conecte os conceitos com os módulos do ZYRON em `04-zyron/`.

## Relação com o ZYRON

Todo conteúdo deve responder: “como isso ajuda a construir, entender ou manter o ZYRON?”. Mesmo quando o assunto for básico, ele deve mostrar uma ponte para comandos, automações, memória, voz, IA, integrações ou arquitetura do projeto.
