# 🏠 House Prices - Advanced Regression Techniques

## 📋 Descrição
Este projeto tem como objetivo prever o preço final de venda de casas residenciais na cidade de Ames, Iowa, com base em um conjunto abrangente de variáveis que descrevem as suas características físicas, localização e estado geral.

O dataset, disponibilizado pela competição House Prices - Advanced Regression Techniques
, contém 79 variáveis explicativas que descrevem diferentes aspetos das propriedades, como área, número de quartos, qualidade dos materiais, idade da construção, entre outros.

Através da aplicação de técnicas de análise exploratória de dados (EDA), pré-processamento, engenharia de atributos e modelos de regressão avançados, o projeto visa construir um modelo preditivo capaz de estimar com elevada precisão o valor de venda das casas.

---

## 🎯 Objetivos da Análise
1. **Compreensão do Dataset:**Analisar as variáveis disponíveis, identificar tipos de dados, valores ausentes e possíveis outliers.
2. **Análise Exploratória de Dados (EDA):**Explorar relações entre as variáveis e o preço de venda, identificar correlações e padrões relevantes. 
3. **Pré-processamento dos Dados:**Tratar valores ausentes, normalizar e codificar variáveis categóricas, e preparar o conjunto de dados para modelagem. 
4. **Engenharia de Atributos:**Criar novas variáveis relevantes (features) a partir das existentes, otimizando o desempenho do modelo.
5. **Modelagem Preditiva:**Testar e comparar diferentes algoritmos de regressão (ex.: Linear Regression, Random Forest, XGBoost, Gradient Boosting, entre outros).
6. **Avaliação do Modelo:**Avaliar o desempenho dos modelos com métricas apropriadas (ex.: RMSE, MAE, R²) e selecionar o melhor.
7. **Otimização e Submissão:**Realizar ajustes de hiperparâmetros para maximizar a precisão das previsões e preparar o modelo final para submissão no Kaggle.

---

## 🏗️ Estrutura do Projeto

```
SCORE/
│
├── data/
│ ├── dta_description.txt
│ ├── header.png
│ ├── sample_submission.csv
│ ├── test.csv
│ └── train.csv
│
├── venv/ # Ambiente virtual
├── main.ipynb # Notebook principal de análise
└── requirements.txt
```

## 🚀 Como Executar

### 1. Configuração do Ambiente

```bash
# Entrar no repositório
cd HOUSE

# Criar ambiente virtual
sudo apt update
sudo apt install python3 python3-pip
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
pip install --upgrade pip
pip3 install notebook

# ou
.venv\Scripts\activate     # Windows
# Instalar dependências
pip install -r requirements.txt

```

### 1️⃣ Configuração do Ambiente
1. Crie e ative um ambiente virtual:
```bash
python -m venv venv
source venv/bin/activate  # Linux / Mac
venv\Scripts\activate     # Windows

### 2. Preparação dos Dados

⚠️ **Importante**: Os dados CSV não estão incluídos no repositório por questões de privacidade e tamanho.

Você precisa colocar os arquivos de dados na pasta `data/raw_data/`:
- `data_description.txt`
- `test.csv`  
- `train.csv`
- `sample_submission.csv`

### 3. Executar a Análise

**Linux / Mac:**
```Abra o Jupyter Notebook:
jupyter notebook main.ipynb
```

#### 🚀 Execução Automatizada (Recomendado)

**Linux / Mac:**
```bash
source venv/bin/activate
streamlit run app2.py
```

**Linux / Mac:**
```bash
source venv/bin/activate
streamlit run app.py
```

**Windows PowerShell:**
```powershell
venv\Scripts\Activate.ps1
streamlit run app.py
```

**Windows CMD:**
```cmd
venv\Scripts\activate.bat
streamlit run app.py
```

Os scripts automaticamente:
- ✅ Verificam Python
- ✅ Criam ambiente virtual
- ✅ Instalam dependências
- ✅ Iniciam aplicação Streamlit

📖 **Para mais detalhes, veja:** [SCRIPTS_README.md](SCRIPTS_README.md)

#### 📓 Execução Manual

**Jupyter Notebook:**
```bash
jupyter notebook main.ipynb
```

**Aplicação Streamlit:**
```bash
streamlit run app.py
```

## 📊 Funcionalidades

### Jupyter Notebook
- ✅ Análise exploratória completa
- ✅ Visualizações estáticas e interativas
- ✅ Testes estatísticos
- ✅ Insights automáticos

### Aplicação Streamlit
- ✅ Interface web interativa
- ✅ Upload dos dataset .csv
- ✅ Dashboards interativos

## 📈 Principais Descobertas

### A clusterização não mostrou-se um caminho bom para esta prova.
- **Método AHP mostrou ser um caminho eficiente para a construção do Score**


## 🛠️ Tecnologias Utilizadas

- **Python 3.8+**
- **Pandas** - Manipulação de dados
- **NumPy** - Computação numérica
- **Matplotlib/Seaborn** - Visualizações estáticas
- **Plotly** - Visualizações interativas
- **Streamlit** - Interface web
- **Jupyter** - Notebooks interativos
- **Scipy** - Análises estatísticas

## 📝 Metodologia

1. **Carregamento**: Dados obtidos pelos Dataset .csv e .json
2. **Limpeza**: Tratamento de valores ausentes e duplicatas
3. **Exploração**: Análise descritiva e visual
6. **Visualização**: Dashboards interativos

## 👥 Autores

- **Mariano António Vunge- Vungel **

## 📞 Contato

- GitHub: [@marianovungel](https://github.com/marianovungel)
- Portfólio: [Marinao_Portfólio](https://vungel.vercel.app/)

---
