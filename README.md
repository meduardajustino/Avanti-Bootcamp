<h1 align="center">📊 Análise Exploratória e Modelagem de Dados <br><small>Bootcamp de Ciência de Dados AVANTI</small></h1> 
<p align="center"><em>Descobrindo padrões, extraindo insights e construindo modelos preditivos com dados reais 💡</em></p>

---

## 🧠 Sobre o Projeto

Este repositório documenta nosso projeto de **<span style="color:#ff8800">Análise Exploratória de Dados (AED)</span>** e **modelagem preditiva**, desenvolvido durante o **Bootcamp de Ciência de Dados da AVANTI**, utilizando o dataset *Cars Data From 1970 to 2024*.

Nosso foco inicial foi compreender profundamente o conjunto de dados — explorando **padrões**, **tendências** e **anomalias** — para então construir modelos de machine learning capazes de prever o preço de veículos com base em suas características técnicas e estruturais.

---

## 📌 Objetivos

- Realizar uma Análise Exploratória completa do conjunto de dados.
- Identificar as variáveis mais relevantes para previsão de preços.
- Aplicar e comparar modelos de regressão, com foco em desempenho preditivo.
- Utilizar validação cruzada para garantir robustez dos resultados.
- Interpretar e comunicar os insights obtidos de forma clara e visual.

---

## 🛠️ Etapas do Projeto

As análises e modelagens foram conduzidas no notebook `Bootcamp_Avanti.ipynb`, divididas em:

### 🔍 1. Inspeção e Preparação dos Dados
- Carregamento, limpeza e tratamento de valores ausentes.
- Engenharia de features com categorização e transformação de variáveis.

### 📈 2. Análise Descritiva
- Resumo estatístico das variáveis numéricas e categóricas.
- Verificação de distribuição, dispersão e possíveis distorções nos dados.

### 📊 3. Visualização de Dados
- Gráficos de dispersão, histogramas, boxplots, heatmaps e pares de variáveis.
- Análises visuais para facilitar insights e entendimento das correlações.

### 🚨 4. Detecção de Outliers e Correlações
- Aplicação de IQR e Z-score para remoção de valores atípicos.
- Estudo da correlação entre variáveis para evitar multicolinearidade.

### 🤖 5. Modelagem Preditiva
- Aplicação dos modelos:
  - Regressão Linear (LRG)
  - K-Nearest Neighbors (KNN)
  - Decision Tree Regressor (DTR)
  - Support Vector Regressor (SVR)
- Ajuste de hiperparâmetros com RandomizedSearchCV.
- Validação cruzada com Monte Carlo (ShuffleSplit).
- Métricas utilizadas: MAE, MSE, MAPE e R².

### 🏆 6. Resultados e Conclusões
- O modelo K-Nearest Neighbors (KNN) destacou-se com o melhor desempenho geral:
  - MAE = 1918.79
  - MSE = 1.285.973
  - R² = 0.8688
- Avaliação de tempo de execução, precisão e estabilidade.
- Análise de importância das features: *year*, *mileage* e *engineSize* foram os fatores mais relevantes para a precificação.

---

## 🧰 Tecnologias Utilizadas

- 🐍 Python 3.x  
- 📒 Jupyter Notebook  
- 📦 Bibliotecas: pandas, numpy, matplotlib, seaborn, scikit-learn

---

## ▶️ Como Executar

### ✅ Execute Online  
👉 [**Abrir no Google Colab**](https://colab.research.google.com/drive/12l4xJ4qjSdDmx2UmUJ9unQDMjGMz0YnP)

### 💻 Execute Localmente
```bash
# Clone o repositório
git clone https://github.com/SAGIEV007/Bootcamp-Avanti.git
cd Bootcamp-Avanti

# (Opcional) Crie um ambiente virtual
python -m venv venv
source venv\Scripts\activate

# Instale as dependências
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# Inicie o notebook
jupyter notebook Bootcamp_Avanti.ipynb

---

## 📌 Próximos Passos

- Explorar modelos mais escaláveis (ex: XGBoost, LightGBM) para grandes volumes de dados.
- Aplicar técnicas de ensemble learning para melhoria de performance.
- Realizar uma engenharia de atributos ainda mais refinada.
- Coletar dados complementares como histórico de manutenção ou condições de mercado.

---

## 👥 Autores

Projeto colaborativo desenvolvido por estudantes da AVANTI, sob orientação do prof. Madson Luiz Dantas Dias:

- 👨‍💻 Fernando da Conceição Cordeiro Filho  
- 👨‍💻 David William A. Oliveira  
- 👨‍💻 José Vitor Paulino Delmiro  
- 👩‍💻 Maria Eduarda Justino

---

## 📄 Licença

Distribuído sob a licença MIT. Veja o arquivo LICENSE para mais informações.

