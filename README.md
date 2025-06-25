
# Predição de Falhas em Máquinas Industriais

Este projeto aplica técnicas de **aprendizado de máquina** para prever falhas em componentes de máquinas industriais com base em dados operacionais em tempo real.

## 📂 Sobre o Projeto

O objetivo é construir um modelo preditivo capaz de identificar possíveis falhas com antecedência, utilizando variáveis como:

- Temperatura
- Pressão
- Vibração
- Rotação do motor
- Tempo desde a última manutenção

Isso permite **otimizar o plano de manutenção**, reduzir custos e evitar paradas inesperadas.

## 🧠 Técnicas Utilizadas

- Análise Exploratória de Dados (EDA)
- Pré-processamento de dados
- Balanceamento de classes (se necessário)
- Modelos supervisionados (ex: Random Forest, SVM, etc.)
- Avaliação com métricas como Acurácia, F1-Score e Matriz de Confusão

## 📁 Estrutura

```

├── predição de falhas.ipynb      # Notebook com todo o processo de análise e modelagem
├── predictive\_maintenance.csv    # Base de dados com variáveis operacionais e falhas
└── README.md                     # Documentação do projeto

````

## 📊 Base de Dados

A base `predictive_maintenance.csv` contém registros de sensores industriais com atributos como:

- `Temperature`, `Pressure`, `RPM`, `Vibration`, `TimeSinceMaintenance`
- `Failure` (0: sem falha, 1: falha detectada)

## 🚀 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/predictive-maintenance.git
   cd predictive-maintenance
````

2. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

3. Execute o notebook `predição de falhas.ipynb` em um ambiente como Jupyter Notebook, Google Colab ou VSCode.

## ✅ Resultados

* Modelos treinados com boa performance na previsão de falhas
* Visualizações gráficas claras sobre o comportamento dos sensores
* Sugestões de melhoria contínua no monitoramento preditivo

## 📌 Requisitos

* Python 3.x
* Bibliotecas: pandas, numpy, matplotlib, seaborn, scikit-learn

> Você pode gerar um arquivo `requirements.txt` com:
>
> ```bash
> pip freeze > requirements.txt
> ```

## ✍️ Autor

Pedro Victor Gonçalves
[Cientista de Dados em formação](https://github.com/pedrovictorgoncalves)


