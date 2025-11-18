# 📊 Projeto de Limpeza e Tratamento de Dados --- Telecom Clientes

Notebook: **Limpeza_Tramento_Projeto.ipynb**\
Base de dados original: **dataset-telecon.json**

------------------------------------------------------------------------

## 📌 Descrição do Projeto

Este projeto tem como objetivo realizar **limpeza, tratamento e
preparação de dados** de um conjunto de clientes de uma empresa de
telecomunicações.
Os dados originais estavam em formato **JSON aninhado**, contendo
informações de:

-   Dados pessoais do cliente
-   Serviços de telefone
-   Serviços de internet
-   Informações de cobrança
-   Status de churn

O foco principal é transformar os dados crus em um **dataset limpo,
estruturado e pronto para análises e modelos de Machine Learning**.

------------------------------------------------------------------------

## 🛠️ Etapas Realizadas

### **1️⃣ Importação e Leitura dos Dados**

Uso das bibliotecas: - Pandas
- NumPy
- JSON + json_normalize

### **2️⃣ Transformação do JSON em DataFrame**

Expansão das estruturas aninhadas com:

``` python
pd.json_normalize()
```

### **3️⃣ Tratamento de Duplicados e Valores Nulos**

-   Remoção de duplicatas
-   Identificação e correção de valores ausentes
-   Preenchimento ou exclusão conforme o contexto

### **4️⃣ Tratamento de Outliers**

Identificação e remoção/substituição de valores extremos que prejudicam
análises e modelos de ML.

### **5️⃣ Dataset Final Pronto para Modelagem**

Após a limpeza, o dataset está preparado para: - Análise exploratória\
- Visualizações
- Modelos de classificação (churn)
- Pipelines de ciência de dados

------------------------------------------------------------------------

## 📂 Estrutura Sugerida do Repositório

    📁 Projeto-Telecom-Churn
    │── README.md
    │── Limpeza_Tramento_Projeto.ipynb
    │── dataset-telecon.json

------------------------------------------------------------------------

## 📈 Tecnologias Utilizadas

-   Python
-   Pandas
-   NumPy
-   Jupyter Notebook

------------------------------------------------------------------------

## 🧠 Próximos Passos

-   Criar visualizações (Seaborn/Matplotlib)
-   Explorar padrões de churn
-   Aplicar modelos como:
    -   Regressão Logística
    -   Random Forest
    -   XGBoost
-   Avaliar métricas (AUC, Recall, Precision)
-   Construir um app de previsão (Streamlit)

------------------------------------------------------------------------

## ✨ Autor

Projeto desenvolvido por *Fernando Tobace*.
