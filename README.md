[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/swFpIGvM)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=14054185&assignment_repo_type=AssignmentRepo)
# Laboratório: Análise Exploratória de Dados

## Descrição da atividade

Você deve usar os dados de séries do IMDB (_Internet Movie DataBase_) para fazer uma análise exploratória de dados em uma série de sua escolha. A série deve ter no mínimo 4 temporadas. A análise deve ser um relatório em Jupyter Notebook, a partir do arquivo `relatorio.ipynb`. O relatório já possui algumas perguntas a serem respondidas. Use as perguntas como base, mas não fique preso a elas. Você pode fazer novas perguntas e novas análises à vontade.

O relatório deve ser legível e compreensível por alguém que não está na disciplina. Não precisa explicar como ler cada gráfico, mas tente ajudar a ver os resultados que você quer mostrar, e caso você use conceitos como IQR e desvio padrão, dê uma ajuda ao leitor.

## Descrição dos dados

O arquivo usado para avaliação está em `dados/avaliacao_episodios_series_top.csv`. Estes dados foram gerados a partir de [dados disponíveis no IMDB](https://datasets.imdbws.com/). Cada linha do arquivo possui dados de um episódio de uma série. As colunas são as seguintes:

- `id_serie`: identificador da série.
- `nome_serie`: nome da série.
- `id_episodio`: identificador do episódio.
- `num_temporada`: número da temporada.
- `num_episodio`: número do episódio.
- `nome_episodio`: nome do episódio.
- `ano`: ano do episódio.
- `duracao_minutos`: duração do episódio em minutos.
- `generos`: gêneros do episódio.
- `avaliacao_media`: avaliação média do episódio pelos usuários do IMDB.
- `num_votos`: quantidade de votos (avaliações) pelos usuários do IMDB.


## Data source acknowledgement

Information courtesy of IMDb (http://www.imdb.com).
Used with permission.
Non-commercial use only.

Downloaded at: https://datasets.imdbws.com/
