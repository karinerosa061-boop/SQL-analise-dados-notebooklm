# 📖 Miniguia de Estudos — SQL Básico

## 🎯 Objetivo

Este miniguia reúne os principais conceitos estudados durante o projeto de SQL utilizando o NotebookLM.

O objetivo é servir como material de consulta rápida para revisar os fundamentos de SQL e sua aplicação na análise de dados administrativos.

---

# 1. O que é SQL?

SQL significa **Structured Query Language**.

É uma linguagem utilizada para consultar e manipular dados armazenados em bancos de dados relacionais.

Na prática, podemos utilizar SQL para fazer perguntas aos dados.

Exemplo:

> Quais funcionários recebem mais de R$ 4.000?

```sql
SELECT Nome, Salario
FROM Funcionarios
WHERE Salario > 4000;
