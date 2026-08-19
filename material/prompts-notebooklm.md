# 🤖 Engenharia de Prompts — NotebookLM

## 🎯 Objetivo

Este documento registra os prompts utilizados durante o projeto para orientar o NotebookLM no processo de aprendizagem de SQL.

A estratégia utilizada foi dividir o conteúdo em etapas progressivas, começando pelos fundamentos e avançando até um pequeno projeto prático.

---

# Prompt 1 — Fundamentos de SQL

### Objetivo

Compreender os conceitos básicos de SQL e bancos de dados relacionais.

### Prompt utilizado

> Explique os fundamentos de SQL e de bancos de dados relacionais para uma pessoa iniciante, relacionando os conceitos com situações da área administrativa. Explique SQL, tabelas, registros, colunas, relacionamentos, chaves primárias e estrangeiras e a importância desses conceitos para análise de dados. Utilize exemplos simples e finalize com perguntas de revisão.

---

# Prompt 2 — Consultas básicas

### Objetivo

Aprender os principais comandos de consulta e filtragem.

### Prompt utilizado

> Crie uma aula prática e progressiva sobre consultas SQL básicas utilizando uma pequena tabela de funcionários como exemplo. Explique SELECT, FROM, WHERE, AND, OR, BETWEEN, IN, LIKE, ORDER BY e LIMIT/TOP. Para cada conceito, apresente uma pergunta administrativa, a consulta SQL, uma explicação simples e um exercício de fixação.

---

# Prompt 3 — Agregações e GROUP BY

### Objetivo

Aprender a resumir informações utilizando funções de agregação.

### Prompt utilizado

> Crie uma aula simples sobre funções de agregação e GROUP BY utilizando a mesma tabela de funcionários. Explique COUNT, SUM, AVG, MIN e MAX e mostre como utilizar GROUP BY para analisar informações por departamento ou categoria. Utilize exemplos administrativos e exercícios básicos. Não introduza conteúdos avançados.

---

# Prompt 4 — HAVING

### Objetivo

Compreender a diferença entre WHERE e HAVING.

### Prompt utilizado

> Explique de maneira simples o comando HAVING e sua diferença em relação ao WHERE. Utilize exemplos administrativos com GROUP BY, COUNT, SUM e AVG. Mostre a ordem lógica de uma consulta e apresente exercícios básicos. Não introduza recursos avançados.

---

# Prompt 5 — JOIN

### Objetivo

Aprender a relacionar informações de diferentes tabelas.

### Prompt utilizado

> Crie uma aula introdutória sobre JOIN utilizando duas tabelas relacionadas: Funcionarios e Departamentos. Explique PK, FK, INNER JOIN e LEFT JOIN de maneira simples. Mostre como utilizar JOIN com GROUP BY e agregações em situações administrativas. Finalize com exercícios básicos e gabarito.

---

# Prompt 6 — Projeto final

### Objetivo

Consolidar os conhecimentos estudados.

### Prompt utilizado

> Com base nos conhecimentos apresentados nos cinco prompts anteriores, crie um projeto final simples para consolidar meu aprendizado de SQL. Sou iniciante e ainda estou aprendendo SQL, portanto não crie um projeto complexo. Utilize três tabelas relacionadas e apresente perguntas administrativas simples que possam ser respondidas utilizando SELECT, WHERE, COUNT, SUM, GROUP BY, ORDER BY e JOIN. Finalize explicando de forma simples a conexão entre SQL, Excel e Power BI.

---

# 🔧 Ajustes e Troubleshooting

Durante o processo, foi identificado que algumas respostas do NotebookLM estavam muito extensas para o nível de conhecimento inicial.

### Problema

Muitos conceitos eram apresentados em uma única aula, dificultando a assimilação do conteúdo.

### Solução

O projeto foi dividido em seis etapas menores:

1. Fundamentos;
2. Consultas básicas;
3. Agregações e GROUP BY;
4. HAVING;
5. JOIN;
6. Projeto final.

Também foram adicionadas instruções como:

- Utilizar linguagem simples;
- Considerar um estudante iniciante;
- Utilizar exemplos administrativos;
- Evitar conteúdos avançados;
- Incluir exercícios;
- Manter uma evolução gradual de dificuldade.

---

# 🧠 Aprendizado sobre Engenharia de Prompts

A experiência mostrou que um prompt mais específico tende a produzir uma resposta mais adequada ao objetivo.

Alguns elementos que ajudaram a melhorar as respostas foram:

**Contexto:** explicar o objetivo do projeto.

**Público:** informar que o conteúdo era destinado a um iniciante.

**Limitação:** pedir para não introduzir conteúdos avançados.

**Formato:** solicitar exemplos, explicações e exercícios.

**Progressão:** dividir o conteúdo em etapas.

---

# ♻️ Prompts reutilizáveis

## Aprender um conceito

> Explique o conceito de [CONCEITO] para uma pessoa iniciante, utilizando linguagem simples e um exemplo relacionado à área administrativa. Apresente uma consulta SQL básica e explique cada parte do código.

## Criar exercícios

> Crie 5 exercícios de SQL sobre [TEMA], começando pelo nível iniciante e aumentando gradualmente a dificuldade. Não mostre o gabarito até o final.

## Corrigir uma consulta

> Analise a consulta SQL abaixo. Explique se ela está correta, identifique possíveis erros e explique como posso melhorar meu raciocínio. Não apenas forneça a resposta pronta.

## Aplicar à administração

> Crie uma situação administrativa que possa ser resolvida utilizando [COMANDO SQL]. Explique o problema, apresente uma consulta SQL simples e explique como o resultado poderia apoiar uma decisão.

## Revisar o conteúdo

> Faça uma revisão dos principais conceitos de SQL que estudei, utilizando perguntas de múltipla escolha e exercícios práticos. Comece pelo nível básico e não apresente o gabarito até que eu tente responder.
