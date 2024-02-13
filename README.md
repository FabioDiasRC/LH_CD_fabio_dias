<h1 align="center"> LH_CD_FABIO_DIAS - DESENVOLVIMENTO DE UM DESAFIO DE CIENCIA DE DADOS </h1>

Este repositório contém o código para um projeto de ciência de dados que realiza uma análise exploratória de dados (EDA) e previsões de preços de aluguel para apartamentos em uma plataforma de aluguel, salvos no modelo de machine learning 'LH_CD_modelo_fabio_dias.pkl'.

Vale ressaltar que o notebook descrito como 'LH_CD_FABIO_DIAS.ipynb' desse repositório define todo o projeto e descreve tudo o que foi realizado de forma detalhada e explicada.

## Instalação

Para instalar as dependências necessárias para executar este projeto, siga os passos abaixo:

1. **Instale o Python**: Certifique-se de ter o Python instalado na sua máquina. Você pode baixar a versão mais recente do Python em https://www.python.org/downloads/ para sua máquina se ela utilizar windows. Rode o seguinte comando na sua máquina linux:

sudo apt update
sudo apt install python3.13

verifique a ultima versao do python instalado na maquina

bash python --version

2. **copie o repositório**: bash git clone https://github.com/FabioDiasRC/fabio_dias_desafio_indicium.git

2. **Instale as dependencias no seu computador**:

* pip install pandas

* pip install seaborn

* pip install statsmodels

alternativamente voce pode utilizar o comando abaixo, que ele utiliza o arquivo e instala as dependencais necessarias.

pip install -r requirements.txt

2. **Run all**: no toṕo do notebook coloque o comando 'run all' que ele rodara todas as celulas do notebook do projeto.

## Análise Exploratória de Dados (EDA)

Neste projeto, realizei uma análise exploratória de dados (EDA) para entender as características principais das variáveis e identificar possíveis hipóteses de negócio.

## Perguntas Respondidas

Respondi às seguintes perguntas durante a análise:

a. Onde seria mais indicado comprar um imóvel para alugar na plataforma?
b. Como o número mínimo de noites e a disponibilidade ao longo do ano afetam o preço?
c. Existe alguma tendência no texto do nome do local que indica valores mais altos?

## Previsão de Preços

Utilizei aprendizado de máquina para prever os preços dos apartamentos. O problema solucionado é de regressão, pois nosso objetivo é prever um valor numérico contínuo. Escolhemos o modelo que melhor se ajustava aos dados e considerei seus prós e contras. A medida de performance escolhida foi o R-quadrado, que é adequado para modelos de regressão.

## Modelo de Machine Learning

O modelo de machine learning foi treinado e salvo no arquivo `LH_CD_modelo_fabio_dias.pkl`. Este modelo pode ser carregado para fazer previsões sobre novos dados.

## Sugestão de Preço para um Imóvel Específico

Com base nas informações disponíveis, sugeri um preço para um imóvel específico definido pela Incidium. A previsão do valor do imóvel baseado no conjunto de dados é de <b>$235.41.</b><br>
