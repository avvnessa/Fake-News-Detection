# Detecção de Fake News com Naive Bayes

Este projeto tem como objetivo a detecção de Fake News usando o algoritmo Naive Bayes e uma base de dados retirada do Kaggle. A implementação foi feita em Python utilizando o ambiente Colab.

## Sobre o Naive Bayes

O algoritmo Naive Bayes é um algoritmo de classificação probabilística baseado no Teorema de Bayes. É considerado um dos algoritmos mais simples e eficientes para classificação de texto.

## Requisitos

> Python 3.x

> Jupyter Notebook ou Google Colab

# Base de dados

A base de dados utilizada foi obtida no Kaggle, disponível [aqui](https://www.kaggle.com/hassanamin/textdb3). Ela contém notícias reais e falsas de diversas fontes, além de informações como título, texto e data de publicação.


## Como executar

* Clone ou faça o download do repositório.
* Acesse o [Google Colab](https://colab.research.google.com/).
* Faça o upload do arquivo fake_or_real_news.csv que foram obtidos no Kaggle, utilizando o comando uploaded = files.upload().
* Abra o arquivo detecção_de_fake_news.ipynb e execute as células sequencialmente.
* Pronto! O notebook irá treinar e testar o modelo Naive Bayes para detectar fake news.

## Implementação do Naive Bayes

O algoritmo Naive Bayes foi implementado utilizando a biblioteca scikit-learn do Python. Foi criado um modelo que recebe como entrada o título e o texto da notícia e classifica como real ou falsa.

## Resultados

O modelo obteve uma acurácia de 84% na classificação de notícias como real ou falsa

## Créditos 

Os créditos para a realização desse trabalho vão para o [RODRIGO CARDOSO DURGIEWICZ](http://repositorio.utfpr.edu.br/jspui/handle/1/28048), que desenvolveu um trabalho de detecção de Fake News em seu TCC, e disponibilizou o código no seu repositório

### Contribuições

Contribuições são sempre bem-vindas! Se você tiver sugestões de melhoria ou encontrar algum erro, sinta-se à vontade para abrir uma issue ou enviar um pull request.

