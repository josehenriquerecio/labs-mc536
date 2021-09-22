# Aluno
* José Henrique Dioz Récio - 176622

## Tarefa de Cypher sobre Marcadores e Taxonomia

## Tarefa 1

Escreva em Cypher uma consulta que retorne os marcadores da categoria `Serviços`, sem considerar as categorias subordinadas.

### Resolução
~~~cypher
MATCH (M:Marcador)-[Pertence]->(C:Categoria{id:"Serviços"}) return M,C
~~~

## Tarefa 2

Escreva em Cypher uma consulta que retorne os marcadores da categoria `Serviços`, considerando as categorias subordinadas.

### Resolução
~~~cypher
match(m:Marcador)-[*]->(C:Categoria{id:"Serviços"}) return m
~~~
