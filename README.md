# 📊 Análise de Crédito e Inadimplência

**Autor:** Felipe Passos de Albuquerque  
**Arquivos principais:**  
- `analise_credito.ipynb` → Notebook com o processamento, análise e modelo preditivo  
- `credit_data.csv` → Base de dados utilizada  

---

## 📌 Descrição do Projeto
Este projeto tem como objetivo analisar dados de crédito e prever o risco de inadimplência de clientes.  
Utilizando uma base de dados contendo informações financeiras e pessoais, foram realizadas:  
- **Análise exploratória dos dados (EDA)**  
- **Visualizações gráficas para identificar padrões**  
- **Balanceamento de classes usando SMOTE**  
- **Treinamento e avaliação de um modelo Random Forest**  

---

## 🔍 Etapas do Projeto
1. **Carregamento e inspeção da base de dados**  
2. **Análise estatística e verificação de valores ausentes**  
3. **Visualizações da variável alvo (`kredit`)**  
4. **Pré-processamento e balanceamento das classes**  
5. **Treinamento do modelo**  
6. **Avaliação com métricas (Matriz de Confusão, Precisão, Recall, F1-score)**  

---

## 🤖 Modelo Utilizado
- **Algoritmo:** Random Forest Classifier  
- **Técnicas aplicadas:**  
  - SMOTE para balanceamento das classes  
  - Divisão treino/teste com `train_test_split`  
  - Avaliação por métricas de desempenho  

**Resultados principais:**
- **Acurácia:** 76%  
- **Recall (bons pagadores):** 92%  
- **Recall (inadimplentes):** 38%  

---

## 🚀 Tecnologias Utilizadas
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Imbalanced-learn  

---

## 🎯 Objetivo Profissional
Este projeto foi desenvolvido para consolidar conhecimentos em **ciência de dados** e **machine learning**, além de compor meu portfólio visando oportunidades de estágio na área de tecnologia.

---
