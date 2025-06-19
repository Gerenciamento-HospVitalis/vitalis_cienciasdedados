# 🚑 Projeto Final: Ciências de Dados - Hospital Vitalis 🚑

📌 Bem-vindo ao repositório do **Hospital Vitalis**, com foco na **Ciências e Análise de Dados**. Este projeto simula um
cenário
hospitalar por meio de dados gerados artificialmente, permitindo a aplicação prática dos principais conceitos
estatísticos, exploratórios e gráficos com Python.

---

## 🎯 Objetivo

O objetivo do projeto é aplicar **conceitos de Estatística Descritiva, Inferencial e Visualização de Dados** utilizando
a linguagem Python. A análise foi realizada sobre dados simulados de um hospital fictício, com foco em consultas,
prescrições, estoques e especialidades médicas.

## 👥 Integrantes do Grupo

- Juliana Fernandes do Nascimento;
- Milenna Victória Assis Portella.

## 🌟 Tema Escolhido

O tema segue o mesmo do projeto anterior: o **Hospital Vitalis**, um pronto-socorro fictício que funciona 24 horas.
Neste projeto, os dados de consultas, medicamentos, especialidades e prescrições foram simulados para realizar análises
estatísticas reais, com foco em:

- 📦 Estoque de medicamentos;
- 🩺 Padrões de prioridade em atendimentos;
- 💊 Correlação entre consultas e prescrições;
- 🧪 Comparação entre especialidades médicas.

## 🛠️ Requisitos Técnicos

- **Linguagem**: Python 3.11+
- **Bibliotecas utilizadas**:
    - `pandas`
    - `numpy`
    - `matplotlib`
    - `seaborn`
    - `scipy`
- **Ambiente de desenvolvimento**:
    - Jupyter Notebook / Google Colab / VS Code

---

## 🦾 Sobre a Base de Dados

A base de dados utilizada neste projeto foi **simulada artificialmente** com o uso das bibliotecas `numpy` e `pandas`, e
inspirada diretamente na estrutura do banco de dados relacional desenvolvido no projeto **Hospital Vitalis** (dml).

Os dados simulados incluem:

- Consultas com informações como: especialidade, prioridade, status e diagnóstico;
- Estoque de medicamentos por nome e quantidade;
- Prescrições médicas associadas às consultas realizadas.

Essa base foi construída manualmente em Python, tendo como referência os dados originalmente inseridos no script
`dml.sql` do projeto de banco de dados relacional. Nenhuma fonte externa foi usada.

---

## 🧪 Técnicas Estatísticas Aplicadas

O projeto aborda 8 tópicos dos 12 sugeridos pela disciplina:

| Tópico                        | Aplicado?                                 |
|-------------------------------|-------------------------------------------|
| 1. Tipos de Amostragem        | Aleatória simples                         |
| 2. Escalas de Medição         | Nominal, ordinal, intervalar, razão       |
| 3. Tendência Central          | Média, mediana, moda                      |
| 4. Dispersão                  | Amplitude, variância, desvio padrão       |
| 5. Testes de Normalidade      | Shapiro-Wilk                              |
| 6. Correlação entre Variáveis | Pearson                                   |
| 8. Visualizações Estatísticas | Histogramas, boxplots, dispersão          |
| 11. Testes de Hipótese        | Teste Exato de Fisher, Teste de Proporção |

---

## 📊 Visualizações Geradas

Os seguintes gráficos foram desenvolvidos e exportados:

- 📦 Boxplot e histograma do estoque de medicamentos
- 📋 Gráfico de barras para status das consultas
- 📈 Dispersão entre número de consultas e prescrições
- 🔍 Gráfico comparativo entre Cardiologia e Pediatria (proporções)

Todos os gráficos estão salvos na pasta `graficos/`.

---

## 📂 Estrutura do Projeto

```txt
📁 vitalis_cienciasdedados/
├── 📁 documentacao
│ ├── 📄 relatorio_tecnico.pdf
├── 📁 scripts
│ ├── vitalis_cienciasdedados.ipynb
├── 📁 graficos
│ ├── 📊 histograma_normalidade.png
│ ├── 📊 histograma_estoque.png
│ ├── 📊 boxplot_estoque.png
│ ├── 📊 barras_status.png
│ ├── 📊 barras_especialidade.png
│ ├── 📊 dispersao_correlacao.png
│ └── 📊 barras_proporcoes.png
└── 📄 README.md # Este arquivo
```
---

## ▶️ Como Executar o Projeto
Esse projeto pode ser executado no Google Colab ou no Visual Studio Code (VsCode). Abaixo contém explicações de como executá-lo em ambas as plataformas:

## 💻 No VsCode:
### 1. Pré-requisitos

- Ter o **Python 3.11+** instalado no computador!
>https://www.python.org/downloads/
  - Instalar as bibliotecas necessárias:

    - No terminal do VsCode, digite:

>pip install pandas numpy matplotlib seaborn scipy jupyter

-Se `pip` não funcionar, use:

>python -m pip install pandas numpy matplotlib seaborn scipy jupyter

  - Abra o arquivo `.ipynb` e execute os scripts
---

## ☁️ No Google Colab
### 2. Executar o Notebook

1. Acesse [https://colab.research.google.com](https://colab.research.google.com)
2. Clique em “**Carregar notebook**”
3. Envie o arquivo `vitalis_cienciasdedados.ipynb`
4. Clique em “Executar tudo” (`Ambiente de execução > Executar tudo`)

### 3. Resultados Esperados

- Os gráficos são exibidos diretamente no notebook
- Arquivos gerados (como `amostra_consultas.csv` e os gráficos `.png`) são salvos na pasta do projeto

---

## 📒 Relatório Técnico

O relatório técnico foi elaborado com base nas normas da **ABNT**, incluindo:

- Introdução
- Metodologia
- Resultados com gráficos
- Interpretações
- Conclusões

📄 **Caminho sugerido:** `documentacao/relatorio_tecnico.pdf`

---