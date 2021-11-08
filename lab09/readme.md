# Aluno
* 176622: José Henrique Dioz Récio


Optei por enriquecer o banco de dados do meu projeto utilizando a base de dados de
conhecimento “Geonames”. Essa base é aberta e apresenta mais de 27 milhões de nomes
geográficos, também hierarquiza e exibe localidades e aspectos geográficos conforme
requisitado.

Link: https://www.geonames.org/3447799/sergipe.html

Como o projeto CSVac irá analisar o estado de Sergipe, podemos enriquecer nosso banco
com informações geográficas disponibilizadas pelo Geonames. A localização de postos de
saúde e fatores que influenciam na mobilidade urbana são mostrados aqui neste grafo de
conhecimento geográfico sobre Sergipe, e essas informações enriqueceriam nossa base e
auxiliaria na resposta de algumas perguntas de análises que fizemos, como:

* Se o local de vacinação que mais disponibilizou doses de vacina de COVID-19 não
existisse, onde essas vacinas seriam oferecidas?
   * Aqui, conseguimos dizer qual o local de vacinação mais próximo deste que
foi “apagado” e também levar em consideração não só a distância, mas
fatores geográficos como proximidade ao centro, a zona rural, etc.
* A escolaridade influencia na adesão da vacinação?
   * Essa pergunta é feita para análise no modelo de tabelas, entretanto com a
agregação do grafo de conhecimentos do Geonames podemos verificar a
quantidade de escolas e universidades próximas às cidades, e assim usar
essas informações para responder a essa pergunta.
* Quais postos de saúde devem receber mais recursos?
   * Analisando a quantidade de vacinas aplicadas pelo grafo podemos dizer qual
posto deve receber mais insumos, além disso, com o grafo de conhecimento
podemos ver hierarquicamente a “quem” cada posto de saúde responde:
município, estado ou federação, possibilitando aqui melhor gestão e
cobrança da autoridade correta.
