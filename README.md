# SQL-analise-dados-notebooklm

# 📊 SQL para Análise de Dados Administrativos

### Caderno Temático desenvolvido com NotebookLM

> Projeto desenvolvido para o Desafio de Projeto da DIO sobre Inteligência Artificial como ferramenta de aprendizagem ativa.

**Autora:** Karine Rosa  
**Ano:** 2026  
**Tema:** SQL aplicado à análise de dados administrativos

---

## 📌 Sobre o projeto

Este projeto foi desenvolvido como parte do desafio da DIO sobre o uso da **Inteligência Artificial como ferramenta de aprendizagem ativa**, utilizando o NotebookLM para pesquisa, organização e consolidação do conhecimento.

O tema escolhido foi **SQL aplicado à análise de dados administrativos**, devido à importância da análise de dados para profissionais da área administrativa e à possibilidade de integrar conhecimentos de SQL com ferramentas como **Excel, Power Query e Power BI**.

A proposta não foi apenas obter respostas utilizando Inteligência Artificial, mas utilizar o NotebookLM como apoio a um processo estruturado de aprendizagem, baseado em fontes selecionadas, perguntas estratégicas, revisão das respostas e aplicação prática dos conceitos.

---

## 🎯 Pergunta central

> **Como os conhecimentos básicos de SQL podem ser aplicados à análise de dados administrativos e integrados ao Excel e ao Power BI para transformar dados em informações úteis para a tomada de decisão?**

---

## 🎯 Objetivos

### Objetivo geral

Desenvolver conhecimentos básicos de SQL para consultar, organizar e analisar dados administrativos, compreendendo sua relação com ferramentas como Excel e Power BI.

### Objetivos específicos

- Compreender o conceito de bancos de dados relacionais;
- Entender tabelas, registros, colunas e relacionamentos;
- Aprender os principais comandos do SQL básico;
- Utilizar filtros e ordenações em consultas;
- Realizar cálculos e agrupamentos;
- Compreender o relacionamento entre diferentes tabelas;
- Aplicar SQL em situações administrativas;
- Entender a relação entre SQL, Excel e Power BI;
- Desenvolver uma base para estudos futuros em análise de dados.

---

# 📚 Curadoria de fontes

Foram selecionadas fontes abertas relacionadas aos fundamentos de SQL, consultas, relacionamentos entre tabelas e integração com ferramentas de análise.

| Fonte | Utilização no projeto |
|---|---|
| **SQLBolt** | Aprendizado prático de consultas SQL, filtros, agregações e JOINs |
| **PostgreSQL Documentation** | Consulta de conceitos e sintaxe de SELECT, WHERE e GROUP BY |
| **Microsoft Learn — Primary and Foreign Key Constraints** | Compreensão de chaves primárias e estrangeiras |
| **Microsoft Support — Power Query no Excel** | Relação entre Excel, Power Query e fontes de dados |
| **Microsoft Learn — Power Query SQL Server Connector** | Compreensão da conexão entre Power Query, Excel/Power BI e bancos SQL |

### 🔗 Links das fontes

1. [SQLBolt — Learn SQL](https://sqlbolt.com/)
2. [PostgreSQL — SELECT Documentation](https://www.postgresql.org/docs/16/sql-select.html)
3. [Microsoft Learn — Primary and Foreign Key Constraints](https://learn.microsoft.com/ro-ro/SQL/relational-databases/tables/primary-and-foreign-key-constraints?view=sql-server-ver15)
4. [Microsoft Support — Power Query no Excel](https://support.microsoft.com/pt-br/excel/create-load-or-edit-a-query-in-excel-power-query)
5. [Microsoft Learn — Conector do Power Query para SQL Server](https://learn.microsoft.com/pt-br/power-query/connectors/sql-server)

---

# 🤖 Utilização do NotebookLM

O NotebookLM foi utilizado como ferramenta de apoio ao processo de aprendizagem.

As fontes selecionadas foram adicionadas ao notebook e utilizadas como base para a elaboração de prompts progressivos.

A estratégia foi dividir o estudo em etapas, começando pelos conceitos fundamentais e avançando gradualmente até uma aplicação prática.

### 🧭 Trilha de aprendizagem

01. Fundamentos de SQL

        ↓
3. Consultas básicas

       ↓
5. Funções de agregação e GROUP BY

       ↓
7. HAVING

       ↓
9. JOIN

       ↓
11. Projeto prático
---

# 🧪 Engenharia de Prompts

Para conduzir o aprendizado, foram criados prompts progressivos no NotebookLM.

A ideia foi começar pelos conceitos mais simples e aumentar gradualmente a complexidade.

## Prompt 1 — Fundamentos

**Objetivo:** compreender o que é SQL e como funcionam bancos de dados relacionais.

> Explique os fundamentos de SQL e de bancos de dados relacionais para uma pessoa iniciante, relacionando os conceitos com situações da área administrativa. Explique SQL, tabelas, registros, colunas, relacionamentos, chaves primárias e estrangeiras e a importância desses conceitos para análise de dados. Utilize exemplos simples e finalize com perguntas de revisão.

## Prompt 2 — Consultas básicas

**Objetivo:** aprender os principais comandos de consulta e filtragem.

> Crie uma aula prática e progressiva sobre consultas SQL básicas utilizando uma pequena tabela de funcionários como exemplo. Explique SELECT, FROM, WHERE, AND, OR, BETWEEN, IN, LIKE, ORDER BY e LIMIT/TOP. Para cada conceito, apresente uma pergunta administrativa, a consulta SQL, uma explicação simples e um exercício de fixação.

## Prompt 3 — Agregações e GROUP BY

**Objetivo:** aprender a resumir informações utilizando funções de agregação.

> Crie uma aula simples sobre funções de agregação e GROUP BY utilizando a mesma tabela de funcionários. Explique COUNT, SUM, AVG, MIN e MAX e mostre como utilizar GROUP BY para analisar informações por departamento ou categoria. Utilize exemplos administrativos e exercícios básicos. Não introduza conteúdos avançados.

## Prompt 4 — HAVING

**Objetivo:** compreender a diferença entre WHERE e HAVING.

> Explique de maneira simples o comando HAVING e sua diferença em relação ao WHERE. Utilize exemplos administrativos com GROUP BY, COUNT, SUM e AVG. Mostre a ordem lógica de uma consulta e apresente exercícios básicos. Não introduza recursos avançados.

## Prompt 5 — JOIN

**Objetivo:** aprender a relacionar informações de diferentes tabelas.

> Crie uma aula introdutória sobre JOIN utilizando duas tabelas relacionadas: Funcionarios e Departamentos. Explique PK, FK, INNER JOIN e LEFT JOIN de maneira simples. Mostre como utilizar JOIN com GROUP BY e agregações em situações administrativas. Finalize com exercícios básicos e gabarito.

## Prompt 6 — Projeto final

**Objetivo:** consolidar os conhecimentos estudados.

> Com base nos conhecimentos apresentados nos cinco prompts anteriores, crie um projeto final simples para consolidar meu aprendizado de SQL. Sou iniciante e ainda estou aprendendo SQL, portanto não crie um projeto complexo. Utilize três tabelas relacionadas e apresente perguntas administrativas simples que possam ser respondidas utilizando SELECT, WHERE, COUNT, SUM, GROUP BY, ORDER BY e JOIN. Finalize explicando de forma simples a conexão entre SQL, Excel e Power BI.

---

# 🩹 Cicatrizes e ajustes no processo

Durante o desenvolvimento do projeto, algumas respostas do NotebookLM apresentaram uma quantidade de conteúdo maior do que o necessário para um estudante iniciante.

Por esse motivo, a estratégia de estudo foi ajustada.

Inicialmente, a intenção era concentrar o conteúdo em menos prompts. Entretanto, percebeu-se que dividir o aprendizado em etapas menores tornaria o processo mais fácil de acompanhar.

A trilha foi então organizada em seis etapas:

1. Fundamentos de SQL;
2. Consultas básicas;
3. Funções de agregação e GROUP BY;
4. HAVING;
5. JOIN;
6. Projeto final.

Essa mudança permitiu trabalhar cada conceito separadamente, evitando excesso de informações em uma única resposta.

### Principal aprendizado sobre os prompts

Foi possível perceber que prompts mais específicos produziram respostas mais adequadas ao objetivo do projeto.

Algumas instruções que ajudaram foram:

- Informar que o conteúdo era destinado a um iniciante;
- Solicitar linguagem simples;
- Utilizar exemplos administrativos;
- Dividir o conteúdo em aulas;
- Solicitar exercícios de fixação;
- Evitar conteúdos avançados.

---

# 📖 Miniguia de Estudo

O resultado do processo de aprendizagem foi consolidado em um miniguia de SQL básico.

O material reúne os principais conceitos estudados:

- SQL;
- Bancos de dados relacionais;
- Tabelas;
- Registros e colunas;
- Chaves primárias e estrangeiras;
- SELECT;
- FROM;
- WHERE;
- AND e OR;
- BETWEEN;
- IN;
- LIKE;
- ORDER BY;
- COUNT;
- SUM;
- AVG;
- MIN;
- MAX;
- GROUP BY;
- HAVING;
- INNER JOIN;
- LEFT JOIN.

O miniguia completo está disponível na pasta `material` deste repositório.

---

# 📚 Glossário

| Conceito | Definição |
|---|---|
| **SQL** | Linguagem utilizada para trabalhar com bancos de dados relacionais. |
| **Banco de dados** | Estrutura utilizada para armazenar e organizar informações. |
| **Tabela** | Estrutura formada por linhas e colunas que armazena dados. |
| **Registro** | Uma linha de uma tabela. |
| **Coluna** | Campo que representa uma característica dos dados. |
| **PK** | Chave primária que identifica um registro de forma única. |
| **FK** | Chave estrangeira utilizada para relacionar tabelas. |
| **SELECT** | Define quais informações serão exibidas. |
| **FROM** | Define de qual tabela os dados serão obtidos. |
| **WHERE** | Filtra registros de acordo com uma condição. |
| **GROUP BY** | Agrupa registros para realizar análises. |
| **HAVING** | Filtra grupos após uma agregação. |
| **ORDER BY** | Organiza os resultados. |
| **COUNT** | Conta registros. |
| **SUM** | Soma valores. |
| **AVG** | Calcula uma média. |
| **MIN** | Retorna o menor valor. |
| **MAX** | Retorna o maior valor. |
| **JOIN** | Permite combinar informações de diferentes tabelas. |
| **INNER JOIN** | Retorna registros que possuem correspondência nas duas tabelas. |
| **LEFT JOIN** | Mantém todos os registros da tabela da esquerda. |

---

# 💼 Projeto Final — TechAdmin

Para consolidar os conhecimentos adquiridos, foi desenvolvido um pequeno cenário fictício chamado **Análise de Resultados TechAdmin**.

O projeto utiliza três tabelas:

- Departamentos;
- Funcionarios;
- Vendas.

A proposta foi utilizar SQL para responder perguntas administrativas simples relacionadas a funcionários, departamentos e vendas.

Entre as perguntas analisadas estão:

- Quais vendas foram superiores a R$ 1.000?
- Quantos funcionários a empresa possui?
- Qual é o valor total vendido?
- Quanto cada funcionário vendeu?
- Qual é o departamento de cada funcionário?
- Quais são os maiores salários?
- Qual é a média salarial da empresa?

O projeto completo está disponível no arquivo:

`material/projeto-final-techadmin.md`

---

# 🔄 SQL + Excel + Power BI

Um dos objetivos do projeto foi compreender que SQL não precisa ser estudado de forma isolada.

Em um cenário profissional, os conhecimentos podem fazer parte de um fluxo de análise de dados:

```text
Banco de Dados
      ↓
     SQL
      ↓
Power Query / Excel
      ↓
   Power BI
      ↓
   Dashboard
      ↓
Tomada de decisão
  ```

♻️ Prompts reutilizáveis

Os prompts abaixo podem ser utilizados posteriormente para continuar os estudos.

Aprender um novo conceito

Explique o conceito de [CONCEITO] para uma pessoa iniciante em SQL, utilizando linguagem simples e um exemplo relacionado à área administrativa. Apresente uma consulta SQL básica e explique cada parte do código.

Criar exercícios

Crie 5 exercícios de SQL sobre [TEMA], começando pelo nível iniciante e aumentando gradualmente a dificuldade. Não apresente o gabarito até o final.

Corrigir uma consulta

Analise a consulta SQL abaixo. Explique se ela está correta, identifique possíveis erros e explique como posso melhorar meu raciocínio. Não forneça apenas a resposta pronta.

Revisar o conteúdo

Faça uma revisão dos principais conceitos de SQL que estudei. Crie perguntas e exercícios práticos de nível iniciante e não apresente o gabarito antes que eu tente responder.

🎓 Conclusão

O desenvolvimento deste projeto permitiu utilizar a Inteligência Artificial não apenas como ferramenta para obter respostas, mas como apoio a um processo estruturado de aprendizagem.

O NotebookLM foi utilizado para organizar fontes, elaborar explicações, criar exercícios e consolidar os conhecimentos adquiridos.

Ao longo do projeto, foi possível compreender os fundamentos de SQL e perceber como consultas podem ser utilizadas para transformar dados em informações úteis para a área administrativa.

Também foi possível compreender a relação entre SQL, Excel, Power Query e Power BI, criando uma base para estudos futuros em análise de dados.

Principal aprendizado

Antes de pensar no código, é importante entender qual pergunta queremos responder com os dados.

Esse princípio orientou a construção do projeto e representa o principal aprendizado obtido durante o desafio.
