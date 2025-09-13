# 🩺 Predição de Diabetes com Random Forest

Este projeto foi desenvolvido como forma de praticar minhas habilidades em **Ciência de Dados**, envolvendo análise exploratória, tratamento de dados e aplicação de um modelo preditivo de classificação.

---

## 📌 Objetivo
Construir um modelo capaz de prever a presença de diabetes em pacientes, utilizando dados clínicos e métricas de avaliação adequadas.

---

## 📊 Etapas do Projeto

1. **Importação dos Dados**
   - Dataset: `diabetes.csv`.

2. **Análise Exploratória**
   - Estatísticas descritivas.
   - Identificação de valores ausentes e inconsistentes.

3. **Tratamento dos Dados**
   - Substituição de valores inválidos (zeros) por `NaN`.
   - Preenchimento de valores ausentes com **medianas**.

4. **Seleção de Variáveis**
   - Principais variáveis utilizadas: `Glucose`, `BMI`, `Age`.

5. **Modelagem**
   - Algoritmo: **Random Forest Classifier**.
   - Divisão dos dados: **70% treino / 30% validação**.

6. **Avaliação**
   - Métricas utilizadas:
     - AUC ROC.
     - Acurácia.
     - Precisão.
     - Recall.

---

## 📈 Resultados
O modelo apresentou resultados consistentes com as variáveis escolhidas, destacando:
- **AUC ROC** como métrica principal de desempenho.
- Boas taxas de acurácia, precisão e recall.

---

## 🛠️ Tecnologias Utilizadas
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 🚀 Aprendizados
- Importância do **pré-processamento** de dados.
- Uso correto do **AUC ROC** com probabilidades.
- Relevância da escolha de variáveis e métricas em datasets desbalanceados.

---

📌 *Este projeto faz parte da minha jornada em Ciência de Dados. Qualquer feedback é bem-vindo!*

