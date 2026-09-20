# 📊 Simulador de Investimentos em Excel

## Sobre o projeto

Este projeto consiste em um **simulador de investimentos desenvolvido no Microsoft Excel**, criado para ajudar o utilizador a compreender como aportes mensais e a rentabilidade podem influenciar a formação de patrimônio ao longo do tempo.

O simulador permite alterar diferentes parâmetros e observar projeções para diferentes períodos de investimento.

## 🎯 Objetivo

O objetivo do projeto é criar uma ferramenta simples e interativa para:

* Simular investimentos mensais;
* Projetar o patrimônio acumulado;
* Estimar rendimentos/dividendos mensais;
* Comparar diferentes períodos de investimento;
* Sugerir um valor de investimento com base no salário;
* Distribuir o investimento de acordo com diferentes perfis;
* Demonstrar o efeito dos juros compostos no longo prazo.

## ⚙️ Principais funcionalidades

### 1. Configurações

O utilizador pode informar:

* Salário;
* Rendimento da carteira;
* Valor sugerido para investimento;
* Investimento mensal;
* Prazo do investimento;
* Taxa de rendimento mensal.

O simulador utiliza esses dados para realizar as projeções.

### 2. Investimento mensal

A ferramenta calcula o patrimônio potencialmente acumulado a partir de um aporte mensal durante determinado período.

A projeção utiliza a função financeira `FV` do Excel para calcular o valor futuro.

### 3. Projeção por cenários

O simulador apresenta projeções para:

* 2 anos;
* 5 anos;
* 10 anos;
* 20 anos;
* 30 anos.

Além do patrimônio projetado, também apresenta uma estimativa de dividendos mensais com base na taxa definida para a carteira.

### 4. Perfis de investimento

O projeto possui três perfis:

* Conservador;
* Moderado;
* Agressivo.

Cada perfil possui uma distribuição percentual entre diferentes tipos de ativos.

### 5. Distribuição do investimento

A ferramenta apresenta uma sugestão de distribuição entre:

* Papel;
* Tijolo;
* Híbridos;
* FOFs;
* Desenvolvimento;
* Hotelarias.

O valor financeiro destinado a cada categoria é calculado automaticamente de acordo com o percentual definido para o perfil selecionado.

## 📑 Estrutura do projeto

O arquivo possui duas planilhas principais:

### `Plan1`

Contém a interface principal do simulador, configurações, projeções, dividendos e distribuição do investimento.

### `Plan2`

Contém a base de dados utilizada para definir a distribuição percentual de cada perfil de investimento.

## 🧮 Exemplo

Considerando um investimento mensal de **350** durante **5 anos**, com uma taxa mensal de **1,079%**, o modelo projeta aproximadamente:

**Patrimônio acumulado:** 29.321,92

Considerando uma taxa de rendimento da carteira de **0,6% ao mês**, a estimativa de dividendos seria aproximadamente:

**175,93 por mês.**

> Os valores são projeções matemáticas e não representam garantia de rentabilidade ou de dividendos futuros.

## 🛠️ Tecnologias utilizadas

* Microsoft Excel
* Fórmulas financeiras
* Função `FV`
* `VLOOKUP`
* `SUM`
* Named Ranges
* Tabelas de distribuição percentual

## 📌 Observação

Este simulador possui finalidade **educacional e de planejamento**. As projeções dependem das taxas utilizadas e não devem ser interpretadas como garantia de retorno financeiro.

Antes de tomar decisões reais de investimento, devem ser considerados fatores como risco, inflação, impostos, taxas, liquidez e variação dos ativos.

## 🚀 Possíveis melhorias futuras

Entre as melhorias planejadas estão:

* Criação de gráficos;
* Dashboard interativo;
* Cálculo da rentabilidade anual;
* Inclusão da inflação;
* Comparação entre investimento nominal e investimento real;
* Simulação de aportes crescentes;
* Inclusão de aportes extraordinários;
* Análise de diferentes cenários de rentabilidade;
* Indicador de retorno sobre o capital investido;
* Proteção das células com fórmulas;
* Validação dos dados inseridos pelo utilizador;
* Interface mais moderna e profissional.

---

**Projeto desenvolvido em Excel para fins de aprendizagem, simulação e demonstração de conhecimentos em ferramentas de análise financeira.**
