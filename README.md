# 🌾 Modelação Preditiva de Produtividade Agrícola com Modelos Ensemble

> Projeto desenvolvido no âmbito da aula/laboratório de **Inteligência Artificial**, focado na análise exploratória de dados e na implementação de modelos de *Machine Learning* baseados em *Ensemble* para prever e analisar o rendimento de culturas agrícolas.

---

## 📋 Sobre o Projeto

Este projeto tem como objetivo principal explorar um conjunto de dados agrícola, realizar o pré-requisito de tratamento e engenharia de variáveis, e treinar modelos de regressão avançados para estimar a produtividade com base em fatores como a variedade da cultura (`variety`), o local de plantação (`site`), entre outras variáveis ambientais ou de gestão.

### Etapas do Pipeline:
1. **Análise Exploratória de Dados (EDA):** Visualização de distribuições, correlações e estatísticas descritivas para compreender o comportamento do rendimento.
2. **Pré-processamento de Dados:** Tratamento de valores omissos e aplicação de *One-Hot Encoding* em variáveis categóricas para adequá-las aos algoritmos.
3. **Modelação *Ensemble*:** Treino e otimização de dois modelos principais:
   * **Bagging Regressor**
   * **Gradient Boosting Regressor**
4. **Avaliação de Desempenho:** Comparação rigorosa dos modelos utilizando métricas de regressão padrão, nomeadamente o Erro Quadrático Médio da Raiz ($RMSE$) e o Coeficiente de Determinação ($R^2$).
5. **Conclusão Visual:** Interpretação da importância das variáveis preditoras e análise gráfica dos resultados obtidos.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido em **Python** utilizando o ambiente Jupyter Notebook e as seguintes bibliotecas principais:
* **Manipulação e Análise de Dados:** `pandas`, `numpy`
* **Visualização de Dados:** `matplotlib`, `seaborn`
* **Machine Learning:** `scikit-learn` (Modelos de Ensemble, Métricas, Pré-processamento)

