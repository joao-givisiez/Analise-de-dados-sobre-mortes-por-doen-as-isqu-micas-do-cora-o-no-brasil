# 🩺 Projeto Dashboard - Mortalidade por Doenças Isquêmicas e Fatores Socioeconômicos

Este projeto tem como objetivo analisar a relação entre fatores socioeconômicos e a taxa de mortalidade por doenças isquêmicas do coração nos estados brasileiros, utilizando dados públicos e técnicas de análise exploratória com Python atribuidas na trilha de Ciência e Governança de Dados do Zettalab

---

## 🧠 Objetivo

- Integrar dados públicos de mortalidade, população, PIB, tabagismo, IDHM, Gini e leitos hospitalares.
- Realizar análise exploratória e gerar visualizações com Python.
- Apresentar um dashboard interativo para explorar os dados por ano e estado.

---

## 🗂️ Estrutura do Projeto

```
├── dados/                # 📥 Dados brutos originais
│   ├── mortes_2016.csv
│   ├── mortes_2017.csv
│   ├── mortes_2018.csv
│   ├── populaçao br.csv
│   ├── pib em %.csv
│   ├── tabagismo.csv
│   ├── IDMH.csv
│   ├── gini geral.csv
│   ├── leitos sus.csv
│
├── saida/                # 📊 Dados tratados e unificados
│   ├── scatter_plot_taxa_vs_fumantes
│   ├── scatter_plot_taxa_vs_idhm
│   ├── series_temporais_por_estado
│   ├── dataset_final.csv
│   ├── heatmap_correlacao_mortes_isquemicas
│
├── analise_de_dados.ipynb    # 📓 Notebook principal de análise
├── heatmap_correlacao_mortes_isquemicas.png # 🌐 Visualização de correlação
│
├── README.md                 # 📚 Instruções e explicações do projeto
├── requirements.txt          # 📦 Dependências do projeto
```

---

## ⚙️ Como executar o projeto

### 1. Instalar o Python (>= 3.8)
- [Download Python](https://www.python.org/downloads/)

### 2. (Opcional) Criar um ambiente virtual

```bash
# Windows
python -m venv env
env\Scripts\activate

# macOS/Linux
python3 -m venv env
source env/bin/activate
```

### 3. Instalar as dependências

```bash
pip install -r requirements.txt
```

### 4. Rodar o notebook de análise

```bash
jupyter notebook
```

Depois, abra o arquivo `analise_de_dados.ipynb`.

### 5. (Opcional) Rodar o dashboard interativo

```bash
streamlit run dashboard.py
```

---

## 📊 Visualizações

- Heatmap de correlação entre taxas de mortalidade e fatores socioeconômicos.
- Gráficos de dispersão (scatter plot) para análise de tendências.
- Séries temporais por estado.

---

## 📥 Fontes de Dados

- [DATASUS - Mortalidade](http://tabnet.datasus.gov.br/)
- [IBGE - Indicadores Socioeconômicos](https://www.ibge.gov.br/)
- [Ministério da Saúde](https://datasus.saude.gov.br/)

---

## 📌 Observações

- Os dados de mortalidade abrangem os anos de 2016 a 2018.
- As análises consideram apenas estados brasileiros, excluindo totais nacionais.
- O projeto pode ser executado em qualquer sistema operacional com Python instalado.

---

## 🤝 Contato

Projeto desenvolvido por Joao Vitor Givisiez.

🔗 [LinkedIn](https://linkedin.com/in/joão-vitor-givisiez-lessa)