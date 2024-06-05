# Salary databased country and race
## Introduction
In this project, we clean a dataset containing various type of variables to predict salary implementing several machine learing algorithms.
## Goals
Clean the dataset to achieve the best performance. <br>
Implement machine learning algorithms. <br>
Observe and determine which algorithm performs best.
## This project's repo includes the following files:
The procces to clean the dataset (1_Data_analysis.ipynb) <br>
Implementation of multiple algorithms (2_Linear_regression.ipynb, 3_Logistic_regression.ipynb, 4_K_neighbors.ipynb, 5_Decision_Trees, 6_Neuronal_networks) <br>
The original data (Salary_Data_Based_Country_and_race.csv) <br>
The clean data (clean_data.csv)
## This project includes the following steps:
1. Null values checkout. <br>
2. Clasification of nominal and ordinal variables. <br>
3. Data visualization and data statistics. <br>
4. Feature selection. <br>
5. Implementation of algorithms and selecting hyperparameters.

## Conclusion
\begin{table}[h!]
\centering
\begin{tabular}{|l|c|c|}
\hline
\textbf{Model} & \textbf{$R^2$} & \textbf{Computation Time (s)} \\ \hline
Linear Regression & 0.79 & 0.1 \\ \hline
Decision Trees & 0.68 & 8.5 \\ \hline
K-Neighbors & 0.93 & 10.4 \\ \hline
Neural Networks & 0.89 & 1296 \\ \hline
\end{tabular}
\caption{Comparison of different models}
\label{table:comparison}
\end{table}
