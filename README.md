# 📡 Análise de Churn de Clientes – Desafio ETL

Este projeto foi desenvolvido como parte do desafio final da formação em **ETL da Turma G8 do programa ONE (Oracle Next Education)**, em parceria com a Alura. O objetivo é realizar uma análise exploratória de dados (EDA) em um conjunto de dados de uma empresa de telecomunicações para identificar os principais fatores que levam à evasão de clientes (Churn).

-----

## 🎯 Propósito da Análise

A análise visa responder à seguinte pergunta central:

> **Quais são os principais fatores e perfis de clientes que influenciam a taxa de churn?**

Para isso, foram investigados os seguintes pontos:

  - A distribuição geral de churn na base de clientes.
  - A relação entre churn e variáveis categóricas (ex: tipo de contrato, método de pagamento).
  - O impacto de variáveis numéricas (ex: tempo de contrato, faturamento mensal) no churn.
  - A identificação do perfil de cliente com maior risco de evasão.

-----

## 📁 Estrutura do Projeto

O projeto está organizado da seguinte forma:

```
📂 desafio-etl-churn
│
├── 📘 TelecomX.ipynb    # Notebook com todo o código, gráficos e o relatório final
├── 📄 README.md                          # Este arquivo
```

-----

## 📊 Exemplos de Gráficos e Insights

Foram gerados gráficos interativos com a biblioteca **Plotly** para visualizar os padrões nos dados:

1.  **Gráfico de Barras Agrupadas**

      - Compara a ocorrência de churn entre diferentes categorias (ex: tipo de contrato).
      - **Insight:** Clientes com contrato **mensal (Month-to-month)** e pagamento via **boleto eletrônico (Electronic Check)** apresentam taxas de churn drasticamente mais altas.

2.  **Gráfico Box Plot**

      - Exibe a distribuição de variáveis numéricas (ex: tempo de contrato) para clientes que evadiram e os que não evadiram.
      - **Insight:** Clientes que cancelam o serviço possuem um **tempo de contrato (tenure) significativamente menor**, indicando que os primeiros meses são críticos para a retenção.

**Conclusão:** Com base na análise, foi identificado um **perfil de cliente de alto risco**, permitindo a sugestão de ações estratégicas e direcionadas para aumentar a retenção.

-----

## ▶️ Como Executar o Notebook

1.  **Abra o projeto no Google Colab:**

      - Você pode subir o notebook `TelecomX.ipynb` diretamente para o [Colab](https://colab.research.google.com/).

2.  **Instale as bibliotecas necessárias:**

    ```python
    !pip install pandas numpy plotly
    ```

3.  **Execute as células na ordem.**

      - O notebook está estruturado com a importação, tratamento, análise exploratória e o relatório conclusivo.

-----

## 🤝 Contribuições e Créditos

Este projeto foi desenvolvido como o desafio final da formação em **ETL da Turma G8 do programa ONE (Oracle Next Education)**, em parceria com a **Alura**.

Sinta-se à vontade para explorar, modificar e sugerir melhorias\!

-----

Desenvolvido com 🧠 por **Miguel Antônio Barbosa Caetano**
📧 miguelantoniobsk@gmail.com | 💼 www.linkedin.com/in/miguel-antoniobc
