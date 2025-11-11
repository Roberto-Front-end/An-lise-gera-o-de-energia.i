# ⚡ Análise de Geração de Energia no Brasil: Comparação Histórica e Evolução da Matriz
Fonte: https://dados.ons.org.br/

## 💡 Sobre o Projeto

Este projeto tem como objetivo principal analisar e visualizar a **evolução da matriz e da carga de energia elétrica no Brasil**, com foco na comparação de dados de balanço energético entre períodos distintos: **o ano 2000 ao ano 2025** (projeção ou dados recentes).

A análise busca identificar as principais transformações no Sistema Interligado Nacional (SIN), como:
1.  O aumento da Carga Total e seu crescimento ao longo do tempo.
2.  A participação e o crescimento das novas fontes de energia renovável (eólica e solar).
3.  A alteração na dependência da geração hidráulica e térmica.
4.  O comportamento da geração e do intercâmbio de energia nos diferentes subsistemas (Norte, Nordeste, Sudeste/Centro-Oeste e Sul).

## 📊 Fonte de Dados

Todos os dados utilizados neste projeto são públicos e foram obtidos diretamente do **ONS (Operador Nacional do Sistema Elétrico)**.

* **Conjunto de Dados:** Carga e balanço de Energia por Subsistema (Dados Horários).
* **Períodos Analisados:** Dados consolidados do ano 2000 ao ano 2025.

## ⚙️ Metodologia e Tecnologias

O projeto foi desenvolvido inteiramente em **Python**, utilizando o ambiente de notebooks do Google Colab para processamento e visualização de dados.

**Tecnologias Utilizadas:**
* **`Pandas`:** Para importação, limpeza, concatenação vertical (`pd.concat()`) e manipulação dos dados de séries temporais.
* **`Matplotlib` / `Seaborn`:** Para criação de gráficos e visualizações das tendências de geração e carga.

A etapa inicial incluiu a **concatenação** dos dois DataFrames de anos diferentes (2000 e 2025) e o tratamento da coluna de data e hora (`din_instante`) para permitir uma análise temporal eficiente.

## 🚀 Como Executar a Análise

Você pode visualizar e rodar o projeto completo diretamente no Google Colab, seguindo este link:

🔗 **[Acessar o Notebook do Google Colab](https://colab.research.google.com/drive/1cE-7zfNAZgo16a3k3df4FBOJsfpuTnVe)**
