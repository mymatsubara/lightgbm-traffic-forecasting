# Previsão de tráfego usando LightGBM

Jupyter notebook com o fluxo de treinamento e otimização de modelos LightGBM e Random Forests para previsão de tráfego.

## Código fonte

O código fonte do projeto inteiro está no arquivo [main.ipynb](/main.ipynb). Uma versão já renderizada do código está [aqui](/main.html).

## Dados utilizados

Os dados utilizados para o treinamento dos modelos não estão disponíveis publicamente. Os dados foram disponibilizados generosamente pela equipe da CET-SP para realização deste estudo.

## Ferramentas usadas

| Ferramenta                                                                                       | Descrição                                                                                                                                   |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------- |
| [Jupyter Notebooks in VS Code](https://code.visualstudio.com/docs/datascience/jupyter-notebooks) | Ambiente de desenvolvimento                                                                                                                 |
| [LightGBM](https://lightgbm.readthedocs.io/en/latest/)                                           | Framework com implementação do LightGBM                                                                                                     |
| [scikit-learn](https://scikit-learn.org/stable/)                                                 | Biblioteca com implementação de diversos algoritmos de Machine Learning e funções que facilitam o treinamento, validação e teste de modelos |
| [optuna](https://optuna.org/)                                                                    | Framework para encontrar parâmetros ótimos de modelos de Machine Learning                                                                   |
| [numpy](https://numpy.org/)                                                                      | Biblioteca com implementação de vetores/arrays com operações eficientes                                                                     |
| [pandas](https://pandas.pydata.org/)                                                             | Biblioteca para lidar com dados em forma de tabelas (DataFrame) de forma eficiente                                                          |
| [matplotlib](https://matplotlib.org/)                                                            | Biblioteca para plotagem de gráficos                                                                                                        |

## Resultados

### Resultados dos modelos

Algumas imagens com os resultados dos modelos estão disponíveis na pasta [img](/img/)

### Resultados de otimização de hiperparâmetros

Alguns imagens e arquivos `.csv` com resultados do processo de otimização de hiperparâmetros estão disponíveis na pasta [hyperparameters](/hyperparameters/).
