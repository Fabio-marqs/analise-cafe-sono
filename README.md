# Análise de Sono, Estresse e Consumo de Cafeína  
Classificação da Qualidade do Sono com Modelos Preditivos

## Objetivo
O projeto analisa padrões entre consumo de cafeína, horas de sono, níveis de estresse e variáveis demográficas.  
A etapa final constrói modelos de classificação para prever **Sleep_Quality** e usa esses resultados para gerar **insights de negócio** aplicáveis ao setor de bebidas e cafeterias.

## Etapas Principais
1. Limpeza e preparação dos dados.  
2. Criação de *features* derivadas.  
3. Codificação de variáveis categóricas (*One-Hot Encoding* ou *Label Encoding*).  
4. Divisão entre treino e teste.  
5. Treinamento de dois modelos:  
   - Regressão Logística  
   - Random Forest  
6. Comparação via acurácia, matriz de confusão e relatório de classificação.  
7. Salvamento do dataset final processado e do melhor modelo.  

## Estrutura do Projeto


📂 projeto_cafe_sono/
│── dados/
│     ├── dataset_original.csv
│     └── dataset_final.csv
│── models/
│     └── modelo_random_forest.pkl
│── analise_cafe_sono.ipynb
│── README.md


## Principais Bibliotecas Necessárias

```text
pandas
numpy
scikit-learn
matplotlib
seaborn
joblib
```

## Resultados

A Random Forest apresentou o melhor desempenho, maior acurácia e menor dispersão de erro nas classes.
O modelo está salvo para uso posterior em sistemas de recomendação, dashboards ou integrações comerciais.

## Relevância do Projeto

Os padrões identificados permitem criar ações estratégicas para empresas do setor de café.
Os modelos preditivos ajudam a segmentar comportamentos e orientar campanhas informativas, mantendo vendas e reduzindo danos associados ao consumo excessivo de cafeína.

