# Análise de Dados de um E-commerce para a resolução do desafio da Triggo ai

Este projeto apresenta a resolução do desafio técnico do Programa Trainee da triggo.ai. O objetivo é analisar dados de um e-commerce utilizando Python.

## Principais Resultados

- Limpeza e tratamento dos dados provenientes de um e-commerce.
- Aplicou-se técnicas de clusterização para segmentação de clientes.
- Foram desenvolvidos modelos de classificação e regressão com Random Forest.
- Utilizou PCA para redução de dimensionalidade, otimizando o desempenho dos modelos.
- Desenvolvimento de dashboards para obter visualizações que revelaram padrões de compra e comportamento do consumidor.

## Requisitos

- Python 3.12.1
- Visual Studio Code
- Alguns plugins do Visual Studio Code

Python:
![alt text](image.png)
Jupyter (ajuda na execução e visualização do notebook):
![alt text](image-1.png)

## Como Executar

1. Clone este repositório.
```bash
git clone https://github.com/will763/desafio-ia.git
```

## A Sua Estrutura do Projeto

```
.
├── main.ipynb           # Notebook com a análise
├── README.md            
├── requirements.txt     # Dependências do projeto
└── dataset/             # Diretório contendo os arquivos CSV usados na análise
```

2. Crie seu ambiente
```
python -m venv trigo-desafio-env
```

agora sua estrutura deve ficar assim

```bash
.
├── main.ipynb           
├── README.md            
├── requirements.txt     
├── dataset/
├── trigo-desafio-env/ # ambiente criado
```

3. Ative o ambiente na raiz do projeto
```bash
.\trigo-desafio-env\Scripts\Activate.ps1
``` 
Caso o ambiente seja ativado seu terminal ficara assim
![alt text](image-2.png)

4. Instale as bibliotecas 
```bash
pip install -r requirements.txt
```
2. Execute o Jupyter Notebook:

Baixe o dataset  e faça a extração para a pasta dataset.
Link para o dataset: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

A pasta dataset deve ficar assim.
![alt text](image-3.png)

Selecione o Kernel, ambiente no qual será executado o notebook, mas antes é necessário ter instalado os plugins que mencionei acima.

![alt text](image-5.png)

Abra o arquivo `main.ipynb`, feche as secções do notebook e click no play, como a imagem abaixo.( o vscode fica dessa maneira graças ao plugin Jupyter )

![alt text](image-4.png)

Espere o término da execução do código, isso pode demorar um pouco. Após isso, verifique os resultados em cada secção do desafio.

![alt text](image-6.png)

#### Caso algum codigo ocorra um erro, execute a fase de prepapação dos dados, em seguida execute novamente a secção do código/desafio que gerou o erro.

## Referências de conteúdo técnico que me ajudou
Mãos à Obra: Aprendizado de Máquina com Scikit-Learn, Keras & TensorFlow: Conceitos, Ferramentas e Técnicas Para a Construção de Sistemas Inteligentes -  Aurélien Géron.

Python para Análise de Dados - 3ª Edição: Tratamento de dados com pandas, NumPy & Jupyter - Wes McKinney.
