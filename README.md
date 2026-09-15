# Projeto de Estatística

Projeto de análise estatística de futebol a partir do dataset [Football Data from
Transfermarkt](https://www.kaggle.com/datasets/davidcariboo/player-scores), publicado
por David Cariboo no Kaggle.

## Estrutura

```text
projeto-estatistica/
├── dados/
│   ├── transfers.csv
│   ├── clubs.csv
│   ├── games.csv
│   └── club_games.csv
└── projeto.ipynb
```

As quatro tabelas foram extraídas do snapshot do dataset baixado em 15/09/2026.
As demais tabelas do pacote original não foram incluídas neste primeiro commit.

## Como começar

Abra `projeto.ipynb` na raiz do projeto e execute as células em ordem. O notebook
carrega as tabelas, verifica dimensões e valores ausentes e cria resumos iniciais
de desempenho dos clubes e de transferências.

Para executar localmente, instale Python 3 com `pandas` e `numpy` e abra o notebook
com Jupyter:

```bash
pip install pandas numpy jupyter
jupyter notebook projeto.ipynb
```
