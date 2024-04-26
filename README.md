# Projeto de MVP para PUC 

## Objetivo: Utilizar Métodos de Classficação para Determinar se uma Notícia é Falsa

Descrição do Problema: O problema consiste em desenvolver um sistema de classificação capaz de detectar se uma notícia é falsa ou verdadeira com base em seu conteúdo. Isso é crucial devido à disseminação de informações enganosas e falsas, especialmente nas mídias sociais e na internet, que podem influenciar negativamente a opinião pública e até mesmo levar a decisões prejudiciais.

## Premissas ou Hipóteses:

Notícias falsas podem conter linguagem sensacionalista, informações não verificadas, fontes não confiáveis ou discrepâncias com fatos bem estabelecidos. Por tanto, é possivel criar uma classificador que possa ser utilizado para sinalizar se uma nóticia pode ser falsa.

## Descrição do Dataset:

O dataset contém atributos textuais como:

Título
Corpo do texto
Assunto
Data
O dataset está dividido em dois CSVs, um para nóticias falsas e outro para nóticias verdadeiras.

Fonte do Dataset: https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset/data

## Preparação de Dados:

O tratamento dos dados será feito utiliznado tecnicas como remoção da pontuação e stopwords e a tokenização e outras técnicas de pré-processamento de texto para padronizar o formato dos dados.

Em seguida será feita a junção dos dois CSVs e em seguida faremos uma randomização e separação dos dados em um conjunto de treinamento e teste. Tomando cuidado para garantir que as classes de notícias falsas e verdadeiras estejam balanceadas no conjunto de treinamento para evitar viés no modelo.
