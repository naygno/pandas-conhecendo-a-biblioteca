# Treinamento em Pandas - Introdução

Este repositório contém exemplos e exercícios para aprender os conceitos básicos da biblioteca **Pandas** em Python, utilizando uma base de dados de imóveis para aluguel.

## 📂 Estrutura do Projeto

1. **Conhecendo a base de dados**
   - Importação dos dados com `pandas.read_csv()`
   - Verificação de:
     - Quantidade de linhas e colunas (`.shape`)
     - Nomes das colunas (`.columns`)
     - Tipos de dados (`.info()`)
     - Visualização inicial (`.head()` e `.tail()`)

2. **Análise exploratória**
   - Valor médio de aluguel por tipo de imóvel
   - Percentual de cada tipo de imóvel
   - Seleção de imóveis do tipo apartamento
   - Remoção de imóveis comerciais

3. **Tratamento e filtragem dos dados**
   - Lidando com valores nulos
   - Removendo registros incompletos
   - Aplicando filtros:
     - Apartamentos com 1 quarto e aluguel < 1200
     - Apartamentos com ≥ 2 quartos, aluguel < 3000 e área > 70

4. **Manipulação dos dados**
   - Criação de colunas numéricas
   - Criação de colunas categóricas
   - Salvando os dados tratados

## 📊 Base de Dados

Os dados utilizados estão disponíveis em:  
[Aluguel.csv](https://raw.githubusercontent.com/alura-cursos/pandas-conhecendo-a-biblioteca/main/base-de-dados/aluguel.csv)

Exemplo de importação:

```python
import pandas as pd

url = 'https://raw.githubusercontent.com/alura-cursos/pandas-conhecendo-a-biblioteca/main/base-de-dados/aluguel.csv'
dados = pd.read_csv(url, sep=';')
```

## 🚀 Objetivo

O objetivo deste repositório é servir como guia introdutório para:
- Explorar bases de dados com Pandas
- Realizar análises exploratórias
- Tratar e manipular dados
- Preparar datasets para análises mais avançadas
