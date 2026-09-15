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
│   ├── club_games.csv
│   └── competitions.csv
└── Transferencias_futebol.ipynb
```

As cinco tabelas foram extraídas do snapshot do dataset baixado em 15/09/2026.
`competitions.csv` foi incluída porque o notebook usa a tabela para confirmar os
IDs das cinco grandes ligas antes de filtrar os jogos. As demais tabelas do pacote
original não foram incluídas nesta versão inicial.

## Como começar

Abra `Transferencias_futebol.ipynb` na raiz do projeto e execute as células em
ordem. O notebook carrega o snapshot local (e usa o Kaggle como fallback), valida
dimensões, valores ausentes, duplicatas e tipos, monta a base clube × temporada e
responde às três perguntas estatísticas do projeto.

Para executar localmente, instale Python 3 com as dependências e abra o notebook
com Jupyter:

```bash
pip install pandas numpy scipy matplotlib kagglehub jupyter
jupyter notebook Transferencias_futebol.ipynb
```
