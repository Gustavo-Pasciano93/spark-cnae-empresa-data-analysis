# Análise de Empresas e Atividades Econômicas com PySpark

Este repositório contém um **projeto de análise de dados** de empresas e suas atividades econômicas, utilizando **Apache Spark** e **consultas SQL**. O objetivo é explorar e manipular dados de empresas, realizando diversas consultas e insights sobre o porte, a localização e o setor de atuação das empresas.

## Tecnologias Utilizadas

- **Apache Spark**: Framework de processamento de dados distribuído utilizado para manipulação e análise de grandes volumes de dados.
- **PySpark**: Interface Python para o Apache Spark, que permite escrever códigos Spark em Python.
- **Google Colab**: Ambiente de desenvolvimento utilizado para executar o projeto.
- **SQL**: Linguagem de consulta utilizada para manipulação e extração de dados do Spark.

## Descrição do Projeto

Neste projeto, trabalhamos com dois conjuntos de dados:

1. **Empresas**: Contém informações como **CNPJ**, **nome fantasia**, **porte**, **município** e **CNAE**.
2. **Atividades Econômicas (CNAE)**: Contém descrições detalhadas das atividades econômicas relacionadas aos códigos **CNAE**.

O principal objetivo foi realizar a **junção desses dois datasets**, utilizando o código **CNAE**, para gerar insights e responder a perguntas como:

- Quais são as atividades econômicas mais representativas por município?
- Qual o porte das empresas em diferentes regiões do Brasil?
- Quais são as principais atividades econômicas de empresas com diferentes portes?

Além disso, foram aplicadas várias transformações e consultas SQL para refinar os dados, como:

- **Limpeza e estruturação dos dados**.
- **Junção entre os datasets de empresas e atividades econômicas**.
- **Consultas SQL** para análise de dados agregados.

## Como Executar

Este projeto foi desenvolvido no **Google Colab** e pode ser executado diretamente em um ambiente de notebook Jupyter. Para executar o projeto localmente, você precisará instalar o **Apache Spark** e o **PySpark**.

### Requisitos

- **Apache Spark** 3.x
- **PySpark**
- **Google Colab** (se preferir rodar no Colab)

### Passos para Execução

1. Clone este repositório:
    ```bash
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    ```

2. Carregue os arquivos de dados (no formato CSV e JSON).

3. Execute os notebooks ou scripts `.py` para carregar, limpar e analisar os dados.

4. Utilize as **consultas SQL** para explorar os dados de empresas e atividades econômicas.

## Consultas SQL Realizadas

- **Empresas por Município e Porte**: Consultas que agrupam as empresas por município e porte.
- **Distribuição de CNAE por Estado**: Identificação de como as atividades econômicas estão distribuídas geograficamente.
- **Empresas de Diferentes Setores**: Exploração de quais setores têm o maior número de empresas.

## Conclusão

Este projeto foi o meu **primeiro utilizando Apache Spark** e **PySpark**, e foi uma ótima oportunidade para aprender sobre como realizar análises utilizando Spark.
---

