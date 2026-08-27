# Projeto Fase 1 — Massa de Dados Financeiros

## Objetivo

Esta pasta contém uma massa de dados propositalmente "imperfeita" para praticar:

- inspeção de dados;
- identificação de problemas de qualidade;
- padronização;
- tratamento de valores ausentes;
- tratamento de duplicidades;
- validação de tipos;
- padronização de textos;
- validação de chaves;
- validação de datas;
- validação de valores numéricos;
- criação de regras de negócio;
- preparação dos dados para análise financeira.

## Arquivos

- clientes.csv
- fornecedores.csv
- produtos.csv
- vendas.csv
- contas_receber.csv
- contas_pagar.csv
- movimentacoes_bancarias.csv

## Desafio

Não corrija os dados manualmente antes da análise.

Primeiro:

1. Faça um diagnóstico de cada arquivo.
2. Identifique os problemas.
3. Classifique cada problema.
4. Defina uma regra de tratamento.
5. Execute a transformação.
6. Valide o resultado.
7. Gere uma versão `processed` dos dados.

## Atenção

Existem problemas intencionais de diferentes naturezas, incluindo inconsistências que
 exigem mais do que uma simples alteração de formato.

A ideia é que você descubra os problemas por meio de análise exploratória e regras de qualidade.

## Regra importante

Preserve os arquivos desta pasta como `raw`.

Não sobrescreva os dados originais.

Estrutura sugerida:

raw/
processed/
scripts/
notebooks/
docs/
