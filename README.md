# Atividades - Bootcamp Avanti

## Sobre o projeto

Olá! Este repositório contém uma série de exercícios que foram realizados durante o bootcamp, abordando diversos tópicos fundamentais em Data Science. Estes exercícios são projetados para ajudar a consolidar o conhecimento teórico através da prática.
Além disso, algumas anotações realizadas em aula podem ser encontradas no [Notion](https://www.notion.so/a455e5d32e6043d1a59a5fba4c731db8?v=71119f36ea7544acacaf89568eddd8a3&pvs=4).

## Linguagens e Pacotes

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)

## Atividades do Repositório
As atividades estão organizadas da seguinte forma:

- **Criação de Dicionário de Dados**: Exercícios focados na criação e manipulação de dicionários de dados, fundamentais para a organização e descrição dos dados utilizados em análises.

- **Estatística Descritiva**: Conjunto de exercícios que cobrem conceitos de estatística descritiva, incluindo medidas de tendência central e dispersão, para sumarizar e entender a distribuição dos dados.

- **Visualização de Dados**: Exercícios práticos para criar diferentes tipos de visualizações de dados, utilizando bibliotecas como Matplotlib e Seaborn, para explorar e comunicar insights visualmente.

- **Preparação e Limpeza de Dados**: Conjunto de exercícios destinados a ensinar técnicas de preparação e limpeza de dados, incluindo tratamento de valores ausentes, remoção de outliers e normalização de dados.

- **Transformação de Dados**: Exercícios sobre a transformação de dados, incluindo técnicas de feature engineering e scaling, para preparar os dados para modelagem.

## Conjunto de Dados 

O conjunto de dados utilizado para a realização das atividades foi o [Tips](https://github.com/atlantico-academy/datasets/blob/main/tips.csv),que contém informações sobre gorjetas dadas em um restaurante!

## Case em Grupo
Além dos exercícios individuais, o bootcamp também incluiu um case em grupo, onde os participantes puderam aplicar os conhecimentos adquiridos em um projeto prático e colaborativo. O case referente ao grupo "AnalytiQueens" pode ser acessado [aqui](https://github.com/atlantico-academy/equipe3-2024.2).


Aproveite os exercícios e bom aprendizado!

### Organização de diretórios


```
.
├── data/              # Diretório contendo todos os arquivos de dados
│   ├── external/      # Arquivos de dados de fontes externas
│   ├── interim/       # Arquivos de dados intermediários
│   ├── processed/     # Arquivos de dados processados
│   └── raw/           # Arquivos de dados originais, imutáveis
├── docs/              # Documentação gerada através da biblioteca mkdocs
├── models/            # Modelos treinados e serializados, predições ou resumos de modelos
├── notebooks/         # Diretório contendo todos os notebooks utilizados nos passos
├── references/        # Dicionários de dados, manuais e todo o material exploratório
├── src/               # Código fonte utilizado nesse projeto
│   ├── data/          # Classes e funções utilizadas para download e processamento de dados
│   ├── deployment/    # Classes e funções utilizadas para implantação do modelo
│   └── model/         # Classes e funções utilizadas para modelagem
├── app.py             # Arquivo com o código da aplicação do streamlit
├── Procfile           # Arquivo de configuração do heroku
├── pyproject.toml     # Arquivo de dependências para reprodução do projeto
├── poetry.lock        # Arquivo com sub-dependências do projeto principal
├── README.md          # Informações gerais do projeto
└── tasks.py           # Arquivo com funções para criação de tarefas utilizadas pelo invoke

```
