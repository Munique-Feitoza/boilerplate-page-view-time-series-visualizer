# Page View Time Series Visualizer

Este projeto analisa dados de visualizações de página do fórum do **freeCodeCamp**, utilizando as bibliotecas **Pandas**, **Seaborn** e **Matplotlib** em Python. Ele faz parte do curso de **Análise de Dados com Python** da [freeCodeCamp](https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/page-view-time-series-visualizer).

## 📊 Objetivo

Visualizar padrões de visualizações de página ao longo do tempo, identificando tendências anuais, variações sazonais e remoção de outliers para uma análise mais precisa.

As visualizações geradas incluem:

- **Gráfico de linha** para mostrar a evolução diária das visualizações.
- **Gráfico de barras** para mostrar a média mensal de visualizações agrupadas por ano.
- **Diagramas de caixa (box plots)** para analisar a tendência anual e a sazonalidade mensal nas visualizações.

## 📁 Estrutura do Projeto

```
📦 page-view-time-series-visualizer/
├── time_series_visualizer.py   # Arquivo principal com as funções de visualização
├── main.py                     # Script de teste
├── test_module.py               # Testes unitários
├── fcc-forum-pageviews.csv      # Conjunto de dados de visualizações de página
└── README.md                    # Este arquivo
```

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone <url-do-seu-repositório>
   cd page-view-time-series-visualizer
   ```

2. Instale as dependências (se necessário):
   ```bash
   pip install pandas seaborn matplotlib
   ```

3. Execute o script de teste:
   ```bash
   python main.py
   ```

## ✅ Requisitos

- Python 3.x
- pandas
- seaborn
- matplotlib

## 🧪 Testes

Os testes são executados automaticamente ao rodar o `main.py`, que importa e testa as funções implementadas a partir do `test_module.py`.

## 📚 Fonte dos Dados

Os dados representam o número de visualizações diárias de páginas no fórum do freeCodeCamp entre maio de 2016 e dezembro de 2019.

---

Projeto baseado no curso gratuito da [freeCodeCamp](https://www.freecodecamp.org/).
