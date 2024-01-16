# Modelagem preditiva para Análise de Crédito

<p align="center">
    <!-- Python -->
    <img alt="python" src="https://img.shields.io/badge/python-FFFFFF?style=flat&labelColor=000000&color=FFFFFF&logo=python&logoColor=1ED760&">
    <!-- Pandas -->
    <img alt="pandas" src="https://img.shields.io/badge/pandas-FFFFFF?style=flat&labelColor=000000&color=FFFFFF&logo=pandas&logoColor=1ED760&">
    <!-- Numpy -->
    <img alt="numpy" src="https://img.shields.io/badge/numpy-FFFFFF?style=flat&labelColor=000000&color=FFFFFF&logo=numpy&logoColor=1ED760&">
    <!-- Plotly -->
    <img alt="plotly" src="https://img.shields.io/badge/plotly-FFFFFF?style=flat&labelColor=000000&color=FFFFFF&logo=plotly&logoColor=1ED760&">
    <!-- Scikit-learn -->
    <img alt="scikit-learn" src="https://img.shields.io/badge/sklearn-FFFFFF?style=flat&labelColor=000000&color=FFFFFF&logo=scikitlearn&logoColor=1ED760&">
    <!-- Status -->
    <img alt="status" src="https://img.shields.io/badge/Status-Em%desenvolvimento-FFFFFF?style=flat&logoColor=1ED760&labelColor=000000">
</p>



# Índice 

* [Descrição do Projeto](#descrição-do-projeto)
* [Funcionalidades](#funcionalidades)
* [Tecnologias utilizadas](#tecnologias-utilizadas)
* [Acesso ao Projeto](#acesso-ao-projeto)
* [Licença](#licença)


# Descrição do projeto

O presente trabalho visa realizar uma modelagem preditiva, baseada nos pilares
da ciência de dados e do aprendizado de máquina. Para a análise, foi utilizada
base de dados
[default of credit card clients](https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients)
da UCI, a qual contém cerca de 30000 contas de etiquetadas de maneira binária,
os quais indicam se o cliente conseguiu (ou não) pagar a fatura mínima de
crédito dentro dos ultimos 6 meses.

# Funcionalidades

# Tecnologias utilizadas
- Linguagem: Python 3.11.5
- Bibliotecas: 
Pandas (2.1.1), Numpy (1.24.3), Plotly (5.9.0), Matplotlib (3.8.0), Scikit-learn (1.3.0)

# Acesso ao Projeto

## Como executar (Windows)

- clone o repositório
- crie um ambiente virtual com o comando:
```shell
python -m venv venv
```

- entre no seu novo ambiente com o comando:
```shell
.\venv\Scripts\activate
```

- instale as dependências:
```shell
pip install requirements.txt
```

pronto, agora basta execurtar o notebook.

### Com Anaconda (Windows)

Crie o environment a partir do arquivo e ative com os seguintes comandos

```shell
conda env create -f environment.yml

conda activate nome_do_ambiente
```

Ou carregue o arquivo `.yml` via *Anaconda Navigator*

# Licença
[MIT License](https://opensource.org/license/mit/)
