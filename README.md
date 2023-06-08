## Análise de estratégias utilizadas em sistemas de recomendação
---
> [**Pós Graduação Inteligência Artificial e Aprendizado de máquina**](https://www.pucminas.br/PUCVIRTUAL/Pos-Graduacao/Paginas/Inteligencia-Artificial-e-Aprendizado-de-Maquina.aspx?pageID=542&moda=1&polo=1&curso=2975&situ=1)<br/>
> [*PUC - Minas*](https://www.pucminas.br/pucvirtual/Paginas/default.aspx)
---

Neste projeto iremos analisar e construir um mecanismo de recomendação de filmes para os dados de filmes fornecidos pela Netflix. Os conjunto de dados foram extraídos da página do [Kaggle](https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data)

Para realizar as analises foram utilizados os arquivos: 
``` r
movie_titles.csv ("../movie_titles.csv")
combined_data_1.txt("../combined_data_1.txt")
```
### Motivação:
O uso de sistemas e redes sociais para buscar entretenimento e comodidade se tornou cada vez mais comum nos últimos anos. Com a evolução da tecnologia e o aumento da conectividade, os usuários têm acesso a uma ampla variedade de plataformas, como serviços de streaming de vídeo, compras online, aplicativos de entrega de comida e muito mais.
As plataformas de streaming de vídeo tornaram-se extremamente populares entre os consumidores, oferecendo acesso a uma grande variedade de conteúdos, desde filmes e séries até documentários e programas de TV.
Contudo, um dos grandes desafios é realizar a correlação entre o que está sendo recomendado e o relacionamento dos interesses. Por isso, as técnicas de aprendizado de máquina auxiliam na análise e entendimento dos padrões de uso e preferências dos usuários.
O intuito deste trabalho é analisar uma estratégia de recomendação de filmes por meio da técnica de filtragem colaborativa e apresentar os resultados obtidos perante a análise.

### Planejamento da análise de recomendação dos filmes consiste em:
1. Carregar o conjunto de dados;
1. Descrever os dados;
1. Análise exploratória dos dados;
1. Execução do modelo de filtragem colaborativa.

### Visualização do arquivo:
Para visualizar o arquivo do Google Colab que contém os dados de execução em detalhes, basta acessar o arquivo [Analise_Recomendacao_Filmes_Filtragem_Colaborativa.ipynb](https://github.com/gomesevelyn/netflix_data_analysis/blob/main/Analise_Recomendacao_Filmes_Filtragem_Colaborativa.ipynb)