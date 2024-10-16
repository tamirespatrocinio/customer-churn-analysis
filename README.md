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
  <a href="#framed_picture-photos">Photos</a> &#xa0; | &#xa0;
  <a href="#chart_with_upwards_trend-results">Results</a> &#xa0; | &#xa0;
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
| age                         | float64      | Customer's age.                                      |
| gender                          | object       | Customer's gender (Male/Female).                         |
| customer_time           | float64      | Length of time the customer has been with the company (in months).    |
| frequency_use               | float64      | Frequency of service use by the customer.             |
| callcenter_calls          | float64      | Number of calls made to the call center.              |
| delay_days                  | float64      | Number of days of late payments.               |
| signature                     | object       | Type of customer subscription (Basic, Standard, Premium). |
| contract_duration              | object       | Contract duration (Monthly, Quarterly, Annual).      |
| total_expense                  | float64      | Total spent by the client to date.                |
| last_interaction_months       | float64      | Months since last customer interaction.          |
| canceled                      | float64      | Indicates whether the customer has canceled (0.0 = Not Canceled, 1.0 = Canceled). |

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
