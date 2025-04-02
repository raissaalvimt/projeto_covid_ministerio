# Análise Estatística da COVID-19 com Dados do Ministério da Saúde (Brasil)

Este projeto foi desenvolvido como uma atividade técnica durante a pandemia da COVID-19, utilizando dados oficiais do [Ministério da Saúde do Brasil](https://covid.saude.gov.br/) para explorar padrões estatísticos e avaliar indicadores epidemiológicos em diferentes estados brasileiros.

## Objetivo

Realizar uma análise descritiva e estatística da evolução dos casos de COVID-19 no Brasil, utilizando dados abertos, com foco em:
- Identificação de padrões de contágio e mortalidade
- Avaliação da dispersão da doença entre regiões
- Criação de visualizações estatísticas e sumarização de indicadores-chave

## Ferramentas e Tecnologias

- **Linguagem:** R
- **Pacotes utilizados:**
  - `readr`, `dplyr`, `tidyr`, `ggplot2`, `zip`, `corrr`
- **Fonte de dados:** https://covid.saude.gov.br/
- **Tipo de arquivo:** `.csv` compactado (.zip) com encoding Latin-1

## Qualidade e Limpeza de Dados

Durante o projeto foram implementadas diversas estratégias de controle e validação da qualidade dos dados:

- Leitura segura com `read_delim()` e tratamento de encoding
- Exclusão e tratamento de `NA`s e dados ausentes
- Padronização de colunas e formatos de data
- Agrupamentos e filtros para análises por estado, região e data

## Análises Realizadas

- **Correlação** entre número de casos confirmados e óbitos
- **Comparação entre estados com maiores taxas de letalidade**
- **Visualizações temporais** e distribuição geográfica da pandemia
- Cálculo de estatísticas como média, mediana e desvio padrão




