# train-custom-tensorflow

## Descrição do Projeto
<p align="justify"> Neste projeto veremos uma forma fácil de criar um modelo customizado do Tensorflow para detectar objetos, utilizando Colab. </p>

Criando dados
----------

Teremos quatro classes:
  - Pica-Pau
  - Zeca Urubu
  - Pink
  - Cerebro
  
Para gerar nossa base de dados foram utilizadas imagens disponíveis no google imagens.

Para auxiliar na criação do dataset foi utilizado o programa labelImg.

![Semantic description of image](/imagens/labelImg.gif "labelImg")

As imagens e suas anotações  estão disponivéis no diretório [images/dados/](https://github.com/adlerschilling/train-custom-tensorflow/tree/main/imagens/dados).

Agora que temos as imagens e suas anotações prontas, poderemos gerar os arquivos .rec para o treinamento, usaremos o próprio Google Colab para gerar estes arquivos.

Para facilitar a manipulação dos dados vamos utilizar nosso Google Drive para armazenar os dados do treinamento, para isso deve ser dado a permissão de acesso ao Google Drive, pois é através dele que nossas imagens anotadas serão acessadas.

Então se você quizer gerar seus próprios arquivos .rec, adicione as imagens e suas anotações no seu Google Drive na pasta raiz com a seguinte estrutura:
  
  - train-custom-tensorflow/imagens/dados/train
  - train-custom-tensorflow/imagens/dados/test
