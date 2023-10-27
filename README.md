
# Classificação com KNN

Este é um projeto que implementa a base de um algoritmo de classificação [K-Nearest Neighbors (KNN)](https://github.com/lfaferreira/ada-potencia-tech-knn-project/blob/main/001_final_case_module_1.ipynb), lecionado pela Ada Tech.

![Cartão de Visita](https://cdn.discordapp.com/attachments/1167506564526121011/1167506718012481609/Modern_Creative_Business_Card.png?ex=654e605c&is=653beb5c&hm=db5c85d8bea7d945ca9fba81618bcdc5eedb64fd26802d5a944815c42fd598d3&)

## Índice
- [1. Introdução](#1-Introdução)
- [2. Compreensão dos dados](#2-Compreensão-dos-dados)
- [3. Plano de Ação](#3-Plano-de-Ação)
  - [3.1. Objetivo](#31-Objetivo)
  - [3.2. Ferramentas e Frameworks](#32-Ferramentas-e-Frameworks)
- [4. Dificuldades](#4-Dificuldades)
- [5. Contribuições](#5-Contribuições)
- [6. Resultados](#6-Resultados)
  - [Conclusão](#conclusão)
- [7. Autores](#7-Autores)

## 1. Introdução

O projeto final do módulo de Lógica de Programação I foi uma maneira muito interessante de fazermos a conexão dos fundamentos da linguagem de programação que estudamos - o Python - com aplicações práticas em um método de Machine Learning. O problema era contextualizado com a realidade do patrocinador do nosso programa, [Ifood - Potência Tech](https://potenciatech.com.br/), uma plataforma de delivery majoritariamente no ramo de alimentação.

## 2. Compreensão dos dados

O conjunto de dados fornecido contém informações sobre clientes, incluindo um identificador único (CPF), a classificação NPS (Promotor, Neutro ou Detrator) e os valores das últimas compras realizadas pelo cliente (VUCC), representados como uma tupla contendo quatro valores (float): valor 1, valor 2, valor 3 e valor 4.

| Atributo | Definição | Tipo do Dado |
| --- | --- | --- |
| CPF | ID único do cliente | int64 |
| Classificação NPS | Classificador do cliente | String |
| VUCC | Valores das últimas compras feitas pelo cliente | Tupla(float) |

Há um total de 150 dados divididos entre o conjunto de dados classificados que contém 120 entradas e o conjunto de dados não classificados contém 30 entradas.

## 3. Plano de Ação

### 3.1. Objetivo
Criação de um algoritmo capaz de identificar os dados não classificados e definir a qual grupo pertencem através da distância euclidiana entre o dado não classificado e os dados classificados.

### 3.2. Ferramentas e Frameworks
A seguir uma lista de ferramentas e frameworks utilizados no projeto:

- Python 3.11.5
- Jupyter Notebook
- Git & GitHub

## 4. Dificuldades

Precisávamos classificar clientes de acordo com os valores de seus últimos pedidos, utilizando o método de KNN, ou K-nearest neighbours, onde, a partir da classificação de seus K vizinhos, classificaríamos os novos clientes de acordo com seus últimos gastos na plataforma.

A primeira dificuldade encontrada foi entender o problema através dos dados fornecidos e da teoria do algoritmo de Machine Learning. Tivemos divergências interpretativas de como proceder inicialmente, mas as dúvidas foram sanadas com o auxílio da professora e, a partir daí, fomos esboçar o nosso código.

## 5. Contribuições

Todos contribuíram com seus conhecimentos e competências. Observamos os pontos fortes de cada componente do nosso grupo, e assim pudemos otimizar nossa maneira de trabalhar em conjunto. Os participantes com maior experiência lógico-matemática trabalharam em conjunto com os participantes com mais prática de código e programação, tornando um trabalho que poderia ser complexo em algo fluido.

Destacamos as principais competências utilizadas nesse projeto a seguir:

- Trabalho em Equipe
- Liderança 
- Lógica Matemática
- Leitura e Interpretação do Problema
- Domínio do Método KNN

## 6. Resultados

Ficamos satisfeitos e realizados com nossos resultados e nosso código limpo, claro e objetivo. Esperamos que seja o início de uma longa parceria em projetos no nosso curso.

### Conclusão

A classificação dos dados é feita de maneira satisfatória seguindo a base do algoritmo KNN utilizando a distância euclidiana. É possível modificar a métrica k-vizinhos para ajustar o algoritmo, assim como ocorre no original.

## 7. Autores

- [Camila Stavola](https://github.com/camilastavola)
- [Jéssica Moreira](https://github.com/mpjessica)
- [Lavínia Beatriz](https://github.com/laviniacaldas)
- [Lucas Ferreira](https://github.com/lfaferreira)
- [Rodrigo Ventura](https://github.com/rodrigopventura)