
# Sistema de Recomendação de Produtos
Este repositório contém um sistema básico de recomendação de produtos utilizando o algoritmo de Singular Value Decomposition (SVD) da biblioteca Surprise. O objetivo é recomendar produtos a usuários com base em seu histórico de compras.

# Estrutura do Projeto
**O projeto é estruturado da seguinte forma:**

## 1.Dados
**produtos:** *Dados dos produtos, incluindo ID, nome, categoria, preço e descrição.*

**usuarios:** *Dados dos usuários, incluindo ID, idade, localização, histórico de compras e preferências.*

## 2. Processamento de Dados
*Os dados dos produtos e usuários são armazenados em DataFrames do Pandas.
O histórico de compras dos usuários é convertido em um DataFrame para treinamento do modelo de recomendação.|*

## 3. Modelo de Recomendação
*Utiliza o algoritmo SVD da biblioteca Surprise para prever a interação entre usuários e produtos.
O modelo é treinado com um conjunto de dados e avaliado usando a métrica RMSE (Root Mean Square Error).*

## 4. Recomendações
*Função obter_recomendacoes para recomendar produtos a um usuário específico com base em previsões feitas pelo modelo.*

# Estrutura do Código

## Dados
*produtos:* Contém informações sobre produtos.

*usuarios:* Contém informações sobre usuários e seu histórico de compras.

## Processamento
DataFrames são usados para manipulação e processamento dos dados.

O histórico de compras é convertido em um formato adequado para treinamento do modelo.

## Modelo
SVD é utilizado para gerar recomendações.

O desempenho do modelo é avaliado utilizando a métrica RMSE.

# Recomendações
A função obter_recomendacoes gera uma lista de produtos recomendados para um usuário específico.
