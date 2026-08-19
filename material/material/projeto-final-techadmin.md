# 💼 Projeto Final — Análise de Resultados TechAdmin

## 📌 Descrição

O projeto final tem como objetivo consolidar os conhecimentos básicos de SQL estudados durante o caderno temático.

Foi criada uma empresa fictícia chamada **TechAdmin**, que possui informações sobre departamentos, funcionários e vendas.

O objetivo é utilizar consultas SQL simples para responder perguntas administrativas.

---

# 🏢 Cenário

A TechAdmin deseja analisar informações relacionadas aos seus funcionários e resultados de vendas.

Para isso, foram criadas três tabelas:

- Departamentos
- Funcionarios
- Vendas

---

# 🗂️ Estrutura da Base de Dados

## Tabela: Departamentos

| ID_Depto | Nome_Depto |
|---:|---|
| 10 | Administrativo |
| 20 | Comercial |

---

## Tabela: Funcionarios

| ID_Func | Nome | Salario | ID_Depto |
|---:|---|---:|---:|
| 1 | Alice Souza | R$ 5.000 | 10 |
| 2 | Bruno Lima | R$ 3.500 | 20 |
| 3 | Carla Dias | R$ 4.000 | 20 |

---

## Tabela: Vendas

| ID_Venda | ID_Func | Valor | Data |
|---:|---:|---:|---|
| 101 | 2 | R$ 1.200 | 2024-08-01 |
| 102 | 3 | R$ 800 | 2024-08-02 |
| 103 | 2 | R$ 1.500 | 2024-08-03 |

---

# 🔑 Relacionamentos

### Chave Primária

Cada tabela possui um identificador único.

Exemplo:

```text
Departamentos → ID_Depto
Funcionarios → ID_Func
Vendas → ID_Venda
