<div align="center">
    <img src="./assets/image/SonoZen_Logo.png" alt="Logo SonoZen" width="50%" >
</div>


# Análise da Eficiência e Padrões de Sono: Um Estudo Baseado em Dados sobre Fatores que Afetam a Qualidade do Sono

## Resumo

<p align="justify">
    Esse conjunto de dados <a href="https://www.kaggle.com/datasets/equilibriumm/sleep-efficiency">Sleep Efficience</a>, disponível no site do Kaggle, registra variáveis detalhadas sobre o sono de participantes, incluindo duração total, eficiência (proporção do tempo dormindo), e distribuição entre sono REM, profundo e leve. Ele também monitora fatores comportamentais como consumo de cafeína e álcool, tabagismo e frequência de exercícios, fornecendo uma base para análises sobre a influência desses fatores na qualidade do sono.
</p>


## Gráfico Abstrato

<div align="center">
    <img src="./assets/image/grafico_abstrato_final.png" alt="Graphical Abstract">
</div>

<br>

 - **Curioso para explorar mais sobre o projeto? Descubra todos os detalhes e insights analisando esse [notebook](https://github.com/atlantico-academy/equipe2-2024.3/blob/master/notebooks/01-exploratory_data_analysis.ipynb).**

<br>

## Justificativa do Projeto

<p align="justify">
    A eficiência do sono desempenha um papel fundamental na saúde física e mental dos indivíduos. Compreender os fatores que influenciam a qualidade do sono é essencial para profissionais de saúde, pesquisadores e para o público em geral. A partir da análise dos dados, busca-se identificar correlações entre a eficiência do sono e variáveis como horas de sono, consumo de álcool, tabagismo e níveis de atividade física.
</p>

## Metodologia

O projeto seguirá a metodologia **CRISP-DM** (Cross Industry Standard Process for Data Mining), que inclui as seguintes fases:

1. **Entendimento do Negócio**: Definir a proposta e os objetivos principais do projeto.
2. **Entendimento dos Dados**: Coleta inicial e análise exploratória do conjunto de dados.
3. **Preparação dos Dados**: Limpeza, transformação e criação de novas variáveis, se necessário.

## Desenvolvedores
 - [Lousane Avelar](https://github.com/lousaneavelar)
 - [Halane Moreira](https://github.com/HalaneMoreira)
 - [Maria Isabel Oliveira](https://github.com/isabe1l-t)

### Organização de diretórios
```

├── README.md
├── app.py
├── assets
│   └── image
│       ├── SonoZen_Logo.png
│       └── grafico_abstrato_final.png
├── data
│   ├── external
│   │   └── dictionary.csv
│   ├── processed
│   │   └── data.csv
│   └── raw
│       └── Sleep_Efficiency.csv
├── docs
│   ├── assets
│   │   ├── css
│   │   │   └── tables.css
│   │   └── js
│   │       └── mathjax.js
│   ├── index.md
│   └── notebooks
│       └── 01-exploratory_data_analysis.ipynb
├── mkdocs.yml
├── models
├── notebooks
│   ├── 00-data-dowload.ipynb
│   ├── 01-exploratory_data_analysis.ipynb
│   └── 02-comparative_analysis..ipynb
├── poetry.lock
├── pyproject.toml
├── references
├── requirements.txt
└── src
    ├── __init__.py
    ├── data
    │   └── __init__.py
    ├── deployment
    │   └── __init__.py
    └── model
        └── __init__.py
```

### Referências
- https://seaborn.pydata.org/
- https://matplotlib.org/
- https://pandas.pydata.org/
- https://numpy.org/doc/stable/user/index.html#user
- https://medium.com/@6448119929/exploratory-data-analysis-on-sleep-efficiency-dataset-baeec53edc8d
- https://www.scielo.br/j/rbem/a/CdHSFWD4DZ7VMcGqzSZLMRF/
- https://institutodosono.com/artigos-noticias/fases-de-sono-veja-quais-sao-e-entenda-a-importancia/
- https://github.com/atlantico-academy/equipe1-2024.2/blob/master/notebooks/01-exploratory_data_analysis.ipynb
