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

![image](https://github.com/user-attachments/assets/fd5504d5-70fb-4b4c-8955-78acfde36000)

Jupyter (ajuda na execução e visualização do notebook):

![image-1](https://github.com/user-attachments/assets/23533236-2979-4439-a035-3a3d5ffa9476)

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
### OBS: Caso a pasta dataset não esteja presente, basta cria-la manualmete.

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
Caso o ambiente seja ativado seu terminal ficara assim, com o nome do ambiente na frente do terminal.

![image-2](https://github.com/user-attachments/assets/5633d50b-44d1-420f-941f-5da287893d5f)


4. Instale as bibliotecas 
```bash
pip install -r requirements.txt
```
5. Execute o Jupyter Notebook:

Baixe o dataset  e faça a extração para a pasta dataset.
Link para o dataset: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

A pasta dataset deve ficar assim.

![image-3](https://github.com/user-attachments/assets/668ee486-8bc1-4f84-8297-0453e6bc3503)

Selecione o Kernel, ambiente no qual será executado o notebook, mas antes é necessário ter instalado os plugins que mencionei acima e também ter instalado as dependências para o ambiente usando o pip install -r requirements.txt com o ambiente ativo, isso também foi mostrado acima.

![image-5](https://github.com/user-attachments/assets/6ef7f543-143f-4d14-b990-5758f1a32f6f)

Abra o arquivo `main.ipynb`, feche as secções do notebook e click no play, como a imagem abaixo.( o vscode fica dessa maneira graças ao plugin Jupyter )

![image-4](https://github.com/user-attachments/assets/76eae754-a19e-4c68-8fef-29643496fca0)

Espere o término da execução do código, isso pode demorar um pouco. Após isso, verifique os resultados em cada secção do desafio.

![image-6](https://github.com/user-attachments/assets/28772f95-c79b-449f-813f-57520d3f83fb)

### Caso algum codigo ocorra um erro, execute a fase de prepapação dos dados, em seguida execute novamente a secção do código/desafio que gerou o erro.

## Referências de conteúdo técnico que me ajudou
Mãos à Obra: Aprendizado de Máquina com Scikit-Learn, Keras & TensorFlow: Conceitos, Ferramentas e Técnicas Para a Construção de Sistemas Inteligentes -  Aurélien Géron.

Python para Análise de Dados - 3ª Edição: Tratamento de dados com pandas, NumPy & Jupyter - Wes McKinney.
