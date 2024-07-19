# NPS
Aplicação de Machine Learning no estudo da fórmula do NPS de um RH Analytics, a métrica para desenvolvimento foi o NPS, sendo:

| Parâmetro   | Fórmula      | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `NPS` | (R.POSITIVAS-R.NEGATIVAS)/TOTAL DE REPOSTAS | Avalia a qualidade da satisfação do seu grupo de pesquisa (no caso os funcionários da própria empresa) |

o conjunto de dados por se apresentar como não-supervisionado, foi testado com:
  - KMEANS
  - DBSCAN
  - GAUSSIAN
sendo DBSCAN tido como melhor modelo comprando a silhueta, cotovelo e métrica de calinski harabasz.
