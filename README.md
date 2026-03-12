# 📊 Dashboard de Salários na Área de Dados

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.2.3-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-1.44.1-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-5.24.1-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)

> Dashboard interativo para explorar e analisar salários na área de dados ao redor do mundo, com filtros dinâmicos e visualizações em tempo real.

🔗 **[Acesse o app aqui](https://imersao-dados-compython.streamlit.app/)**

---

## 📋 Sobre o Projeto

Este dashboard permite analisar dados salariais da área de dados (Data Science, Data Engineering, etc.) de diferentes países, anos e perfis profissionais. A aplicação foi construída com **Streamlit** para a interface, **Pandas** para manipulação dos dados e **Plotly** para os gráficos interativos.

---

## 🖥️ Funcionalidades

- **KPIs** com salário médio, salário máximo, total de registros e cargo mais frequente
- **Top 10 cargos** com maior salário médio (gráfico de barras)
- **Distribuição salarial** por faixas (histograma)
- **Proporção dos tipos de trabalho** — remoto, presencial e híbrido (gráfico de rosca)
- **Mapa mundial** com salário médio de Cientista de Dados por país
- **Tabela detalhada** com todos os registros filtrados
- **Filtros dinâmicos** por ano, senioridade, tipo de contrato e tamanho da empresa

---

## 🛠️ Tecnologias

| Tecnologia | Versão |
|---|---|
| Python | 3.10+ |
| Pandas | 2.2.3 |
| Streamlit | 1.44.1 |
| Plotly | 5.24.1 |

---

## ⚙️ Como Executar Localmente

```bash
# 1. Clone o repositório
git clone https://github.com/ViniciusCavalcantiap/Imersao-dados-python.git
cd Imersao-dados-python

# 2. Crie e ative um ambiente virtual
python -m venv .venv

# Windows:
.venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate

# 3. Instale as dependências
pip install -r requirements.txt

# 4. Execute a aplicação
streamlit run app.py
```

Acesse em `http://localhost:8501`.

---

## 📁 Estrutura do Projeto

```
Imersao-dados-python/
├── app.py                      # Aplicação principal (Streamlit)
├── dados_imersao_final.csv     # Base de dados local
├── requirements.txt            # Dependências
└── README.md
```
