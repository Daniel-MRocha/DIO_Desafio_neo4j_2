# DIO_Desafio_neo4j_2
---
## Desafio de uma base de dados, que indique músicas aos usuários
---

## Desenvolvimento

Foi usada uma base de dados como seed do kaggle, de músicas, artistas e gêneros
<ul>
### Criei alguns users com relacionamentos fictícios, apenas para os testes
 Após a criação do database, desenvolvi 3 querys a principio:
- Uma que indica musica com base nos gêneros, ou seja, a query pega os 3 gêneros mais escutados do user, depois busca musícas do database e retorna como sugestão, 15 músicas que contenham os 3 gêneros mais escutados.
- Uma que indica artistas baseado no rating de música escutada pelo user, se o rating for maior que 7, ela indica o artista.
- Uma com uso do APOC, que lista as 3 músicas mais escutadas do database.
---
