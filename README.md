# Aplicação Streamlit para Criação de Modelos de Aprendizado de Máquina

Este repositório contém uma aplicação desenvolvida em Streamlit que permite aos usuários criar um modelo de aprendizado de máquina em um fluxo de trabalho de ponta a ponta. A aplicação abrange desde o upload e pré-processamento da base de dados até o treinamento, construção do modelo de aprendizado de máquina e análise pós-modelo.

## Funcionalidades

- **Upload de Base de Dados**: Carregue sua base de dados no formato CSV.
- **Pré-processamento de Dados**: Realize o tratamento dos dados antes do treinamento.
- **Treinamento de Modelos**: Treine modelos de aprendizado de máquina usando a biblioteca Scikit-Learn.
- **Análise Pós-Modelo**: Avalie e visualize a performance dos modelos.

## Base de Dados

A base de dados usada neste aplicativo é a `new_retail_data.csv`, disponível na plataforma Kaggle. Você pode fazer o download da base de dados [aqui](https://www.kaggle.com/datasets/sahilprajapati143/retail-analysis-large-dataset).

## Bibliotecas Usadas

- **Pandas**: Para leitura e tratamento dos dados.
- **Scikit-learn**: Para construção do modelo de aprendizado de máquina.
- **Streamlit**: Para interface do usuário.
- **Sweetviz**: Para gerar o relatório de análise exploratória de dados.
- **Time**: Para manipular o tempo de execução de processos.
- **Base64**: Para download do relatório.
- **Pycaret**: Para comparação da performance dos modelos de aprendizado de máquina.
- **Plotly**: Para construção de gráficos interativos.

## Amostra
[streamlit-app-2024-07-07-20-07-56.webm](https://github.com/AdiltonCarvalho/previsao_vendas/assets/141254502/5e19285b-7626-4c47-aae7-dda91a7651a8)


## Instalação

Para instalar e executar a aplicação, siga os passos abaixo:

1. Clone o repositório:
    ```bash
    git clone https://github.com/AdiltonCarvalho/previsao_vendas.git
    cd previsao_vendas
    ```

2. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

3. Execute a aplicação:
    ```bash
    streamlit run app.py
    ```

4. Acesse a aplicação em seu navegador na URL `http://localhost:8501`.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para melhorias e correções.
