# Projeto de Análise e Modelagem Preditiva de Filmes do IMDB para PProductions

## Descrição do Projeto

Este projeto foi desenvolvido para a Indicium, a pedido do estúdio de Hollywood PProductions, com o objetivo de analisar um banco de dados cinematográfico e fornecer insights que possam orientar o desenvolvimento de futuros filmes. O projeto busca identificar características de filmes bem-sucedidos e criar um modelo de Machine Learning capaz de prever a nota do IMDB, uma métrica importante para a reputação e potencial de um filme.

As etapas incluíram Análise Exploratória de Dados (EDA), pré-processamento de dados, desenvolvimento e avaliação de modelos preditivos (Regressão Linear e Random Forest), previsão para um filme específico e a criação de uma aplicação web simples para demonstração.

## Estrutura do Repositório

Este repositório contém os seguintes arquivos e diretórios:

*   `desafio_indicium_imdb.csv`: O dataset original utilizado no projeto.
*   `seu_notebook.ipynb`: O notebook Google Colab contendo toda a análise, visualizações, código de pré-processamento, modelagem e a aplicação web Gradio. (Substitua `seu_notebook.ipynb` pelo nome real do seu arquivo .ipynb).
*   `random_forest_imdb_predictor.pkl`: O modelo Random Forest treinado e salvo.
*   `requirements.txt`: Arquivo listando as bibliotecas Python e suas versões necessárias.
*   `README.md`: Este arquivo, explicando o projeto.

## Como Instalar e Executar no Google Colab

Para rodar este projeto no ambiente do Google Colab, siga os passos abaixo:

1.  **Abra o notebook:** Faça o upload ou abra o arquivo `seu_notebook.ipynb` no Google Colab.
2.  **Execute as células:** Execute todas as células do notebook em ordem, de cima para baixo.
    *   As primeiras células carregarão e farão a limpeza inicial dos dados.
    *   As células seguintes realizarão a Análise Exploratória de Dados (EDA) e a análise da coluna 'Overview'.
    *   As células de pré-processamento prepararão os dados para a modelagem.
    *   As células de modelagem treinarão e avaliarão os modelos de Regressão Linear e Random Forest.
    *   A célula de previsão fará a estimativa da nota do IMDB para um filme específico.
    *   A célula que gera o arquivo `requirements.txt` criará a lista de dependências.
    *   A célula que inicia a aplicação Gradio (`L80v2W1_DORr`) irá instalar o Gradio (se necessário) e lançar a interface web.
3.  **Acesse a Aplicação Gradio:** Após a execução da célula Gradio, um link público temporário será fornecido na saída da célula. Clique neste link para interagir com a aplicação e prever a nota do IMDB para novos filmes.

As dependências necessárias serão instaladas automaticamente durante a execução das células no ambiente Colab.

## Contato

Se tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato.
