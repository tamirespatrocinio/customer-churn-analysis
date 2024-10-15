<h1 align="center">Customer Churn Analysis</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/tamirespatrocinio/customer-churn-analysis?color=56BEB8">
  <img alt="Github language count" src="https://img.shields.io/github/languages/count/tamirespatrocinio/customer-churn-analysis?color=56BEB8">
  <img alt="License" src="https://img.shields.io/github/license/tamirespatrocinio/customer-churn-analysis?color=56BEB8">
</p>

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/tamirespatrocinio" target="_blank">Author</a>
</p>

<br>

## :dart: About  

This project focuses on analyzing customer churn data to identify patterns and factors contributing to service cancellations. The goal is to uncover insights that can help improve customer retention by analyzing historical data and visualizing key trends.

## :sparkles: Features  

:heavy_check_mark: Customer churn analysis;\
:heavy_check_mark: Data visualization to uncover patterns;\
:heavy_check_mark: Identification of factors contributing to churn.

## :rocket: Technologies  

The following tools were used in this project:

- [Pandas](https://pandas.pydata.org/) 
- [NumPy](https://numpy.org/) 
- [OpenPyXL](https://openpyxl.readthedocs.io/en/stable/) 
- [nbformat](https://nbformat.readthedocs.io/en/latest/) 
- [ipykernel](https://ipykernel.readthedocs.io/en/latest/) 
- [Plotly](https://plotly.com/) 

## :white_check_mark: Requirements

- Before starting, you need to have [Python](https://www.python.org/) installed.

- Install Jupyter extension for [VS Code](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) or use [Anaconda](https://www.anaconda.com/download) for managing Python environments and running Jupyter Notebooks.

## :checkered_flag: Starting

```bash
# Clone this project
$ git clone https://github.com/tamirespatrocinio/customer-churn-analysis

# Navigate into the project directory
$ cd customer-churn-analysis

# Install dependencies
$ pip install pandas numpy openpyxl nbformat ipykernel plotly
```

## :bar_chart: Dataset

The data set used in the analysis contains the following columns:

| Column Name               | Type  | Description                                               |
|-------------------------------|--------------|---------------------------------------------------------|
| idade                         | float64      | Idade do cliente.                                      |
| sexo                          | object       | Sexo do cliente (Male/Female).                         |
| tempo_como_cliente           | float64      | Tempo que o cliente está com a empresa (em meses).    |
| frequencia_uso               | float64      | Frequência de uso do serviço pelo cliente.             |
| ligacoes_callcenter           | float64      | Número de ligações feitas ao call center.              |
| dias_atraso                  | float64      | Número de dias em atraso nos pagamentos.               |
| assinatura                    | object       | Tipo de assinatura do cliente (Basic, Standard, Premium). |
| duracao_contrato             | object       | Duração do contrato (Mensal, Trimestral, Anual).      |
| total_gasto                   | float64      | Total gasto pelo cliente até o momento.                |
| meses_ultima_interacao       | float64      | Meses desde a última interação com o cliente.          |
| cancelou                      | float64      | Indica se o cliente cancelou (0.0 = Não Cancelou, 1.0 = Cancelou). |

## :framed_picture: Photos

![newplot](https://github.com/user-attachments/assets/a13ffadf-5ac5-4944-bea7-97e3aade2d34)
*Chart 1: Number of calls to the call center by customers.*
![newplot2](https://github.com/user-attachments/assets/75ade608-2e45-4ecd-a047-4c47ff97c31d)
*Chart 2: Number of days in delay for customer payments.*
![newplot3](https://github.com/user-attachments/assets/1f118f47-b8b7-4498-96c4-7b875dbc5c10)
*Chart 3: Duration of contracts (Monthly, Quarterly, Annual) by customers.*


## :chart_with_upwards_trend: Results
The initial analysis revealed that the proportion of cancellations is as follows:

- Canceled: 56.71%
- Active: 43.29%

After applying retention measures, the cancellation rate fell from 56.71% to 36.27%, which corresponds to a reduction of approximately 20.44 percentage points. This reflects a significant improvement.

&#xa0;

<a href="#top">Back to top</a>
