Análise de Séries Temporais — A1

Este repositório contém o material e o relatório referente ao Trabalho A1 da disciplina de Séries Temporais.

O projeto tem como objetivo realizar uma análise completa de uma série temporal, abordando desde a escolha e justificativa das métricas de avaliação até a comparação de modelos de previsão.

## Relatório

O relatório contém as seguintes seções:

* Discussão sobre métricas e métodos de avaliação
Justificativa do uso de métricas percentuais e absolutas, considerando a escala e distribuição dos dados.

* Discussão sobre a necessidade de transformação de variáveis
Avaliação da aplicação de transformações logarítmicas ou diferenciações para estabilizar variância.

* Discussão sobre decomposição entre tendência e sazonalidade
Separação das componentes estruturais da série e análise de sua influência no modelo.

* Análise de resíduos e ajuste dos modelos
Verificação da adequação dos modelos por meio dos resíduos.

* Modelos Baseline

    Implementação dos métodos:

    * Mean

    * Naive

    * Seasonal Naive

    * Drift

    * Média Móvel

* Modelos de Regressão Linear Múltipla
Utilizando co-variáveis derivadas de week e volume, avaliadas pelas métricas MAE, RMSE e MAPE.


## Execução

Clone o repositório:
```
git clone https://github.com/eduardammag/time-series.gitA1-Series-Temporais.git

cd A1-Series-Temporais
```


Instale as dependências:

pip install -r requirements.txt

## Autores

* Ana Júlia Amaro Pereira Rocha

* Henrique Borges Carvalho

* Maria Eduarda Mesquita Magalhães

* Mariana Fernandes Rocha

* Paula Eduarda de Lima
