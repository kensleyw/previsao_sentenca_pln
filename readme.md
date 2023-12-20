# Modelo CBoW (Continuous Bag of Words) - README

Este repositório contém a implementação de um modelo Continuous Bag of Words (CBoW) em PyTorch para tarefas de processamento de linguagem natural. O modelo CBoW foi projetado para prever uma palavra-alvo com base nas palavras de contexto em uma sentença.

## Pré-requisitos
- Python 3.10.11

## Conteúdo do Repositório

- **previsao_sentenca.ipynb**: Notebook Jupyter contendo a implementação do modelo CBoW, pré-processamento de dados e treinamento.
  
- **requirements.txt**: Arquivo que lista as dependências necessárias para executar o código. Execute `pip install -r requirements.txt` para instalar as bibliotecas necessárias.

## Sumário
- [Introdução](#introdução)
- [Conceitos Básicos de Tensor](#conceitos-básicos-de-tensor)
- [Problema de Negócio](#problema-de-negócio)
- [Pré-processamento](#pré-processamento)
- [Modelo CBoW](#modelo-cbow)
- [Treinamento](#treinamento)
- [Predição](#predição)

## Introdução
O modelo CBoW é uma arquitetura de rede neural utilizada para embeddings de palavras e processamento de linguagem natural. Ele é especialmente eficaz na previsão de uma palavra-alvo com base nas palavras de contexto ao seu redor. Esta implementação é construída usando o PyTorch, uma biblioteca popular de aprendizado profundo.

## Conceitos Básicos de Tensor
As seções iniciais do código demonstram a criação e manipulação de tensores usando o PyTorch. Tensores são estruturas de dados fundamentais no PyTorch, e compreender suas propriedades é crucial para a construção de redes neurais.

## Problema de Negócio
O código aborda um problema legal específico relacionado a uma quebra de contrato para a compra de imóveis. O texto fornecido delineia o contexto legal, e o objetivo é pré-processar o texto e treinar um modelo CBoW para prever palavras dentro desse domínio legal.

## Pré-processamento
A seção de pré-processamento concentra-se na limpeza e organização dos dados textuais legais. Envolve tarefas como remover pontuação, criar um corpus e preparar os dados para o treinamento do modelo CBoW.

## Modelo CBoW
A arquitetura do modelo CBoW é definida no código. Inclui uma camada de incorporação, camadas lineares e funções de ativação. O modelo é projetado para aprender incorporações de palavras e prever palavras-alvo com base no contexto.

## Treinamento
O processo de treinamento envolve a iteração sobre o conjunto de dados, o cálculo da perda e a atualização dos parâmetros do modelo usando descida gradiente estocástica (SGD). O loop de treinamento é executado por um número especificado de épocas, e o modelo melhora gradualmente sua capacidade de prever palavras-alvo.

## Predição
O código inclui funções para fazer previsões com o modelo treinado. Demonstra como obter incorporações de palavras e prever a próxima palavra em um determinado contexto.

Sinta-se à vontade para explorar e modificar o código para se adequar ao seu caso de uso específico ou conjunto de dados. Se tiver dúvidas ou sugestões, não hesite em entrar em contato.

