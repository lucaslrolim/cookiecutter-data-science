{{cookiecutter.project_name}}
==============================

{{cookiecutter.description}}

Organização do projeto
------------

├── LICENSE
├── Makefile           <- Arquivo para armazenar comandos bash necessários para setup
├── README.md          <- Descrição geral com objetivos e contexto do projeto
├── data
│   ├── processed       <- Datasets finais, utilizados pelos modelos.
│   └── raw             <- Dump original extraído das bases de dado (imutável)
|   └── queries         <- Consultas utilizadas para extração de informações das bases de
│
├── models             <- Modelos treinados, predições geradas e sumário descritivo dos modelos e parâmetros utilizados
│
├── notebooks          <- Jupyter notebooks. A conversão para nomes é a versão (para ordenar), as iniciais do criador e uma descrição. Tudo separado por "-", e.x.
│                         `1.0-lr-initial-data-exploration`.
│
├── references         <- Artigos, links e outras referências para entendimento dos modelos.
│
├── outputs            <- Análises geradas em HTML, PDF, LaTeX, etc.
│   └── figures        <- Gráficos e figuras geradas e utilizadas nos relatórios.
│
├── requirements.txt   <- Requerimentos de ambiente para execução do projeto. e.x:
│                         generated with `pip freeze > requirements.txt`
│
├── src                <- Classes funções do projeto
│   ├── __init__.py    <- Makes src a Python module
│   │
│   ├── data           <- Scripts para baixar e/ou gerar os datasets
│   │   └── make_dataset.py
│   │
│   ├── features       <- Scrpits para criar features ou datasets nos quais serão aplicados os modelos
│   │   └── build_features.py
│   │
│   ├── models         <- Modelos
│   │   ├── predict_model.py
│   │   └── train_model.py
│   │
│   └── visualization  <- Visualizações
│       └── visualize.py

--------

<p><small>Project based on the <a target="_blank" href="https://github.com/lucaslrolim/cookiecutter-data-science">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
