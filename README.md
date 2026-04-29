# Análise de Perfis de Consumo - TCD

Este repositório contém os dados e arquivos utilizados na análise exploratória de consumo de energia elétrica no Ambiente de Contratação Livre (ACL), no contexto de um Trabalho de Conclusão de Disciplina (TCD) em Aprendizado de Máquina.

## Estrutura dos Dados

A base de dados original da CCEE, referente ao mês de fevereiro de 2026, foi previamente tratada e organizada em três arquivos CSV para facilitar a análise.

## Tratamento e Filtragem

A base utilizada corresponde à:

**Base CCEE fevereiro de 2026 tratada**

Foram aplicados os seguintes filtros:

- Estado: Bahia (BA)
- Tipo de consumidor:
  - Consumidor Livre
  - Consumidor Especial

## Processamento dos Dados

Após a filtragem, foi realizado o seguinte cálculo:

- **Cálculo da média mensal de consumo por período de comercialização (0 a 23 horas)**

Esse processamento permitiu a construção de perfis médios de consumo ao longo do dia, utilizados na análise exploratória e como base para etapas futuras de modelagem com aprendizado de máquina.

## Conteúdo do Repositório

- `data/`: arquivos CSV com os dados tratados
- `powerbi/`: arquivo Power BI (.pbix) com a análise exploratória
- `docs/`: materiais auxiliares (workflow, relatórios, etc.)

## Objetivo

A análise tem como objetivo identificar padrões de consumo de energia elétrica, visando aplicações futuras em técnicas de aprendizado de máquina e estratégias de gerenciamento da demanda, como load shifting, com potencial aplicação em sistemas de armazenamento de energia (BESS).

## Observação

A base completa não foi disponibilizada devido ao seu grande volume.
