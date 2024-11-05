MedConnect é nosso sistema de recomendação de produtos farmaceuticos.

Ele utiliza a biblioteca "SURPRISE" que é especializada em sistemas de recomendações para rodar nosso programa.

Dentre os sistemas de recomendação que foram escolhidos para esse projeto escolhemos o sistema de recomendação hibrido
que é um junção em o sistema de RECOMENDAÇÃO COLABORATIVO e sistema de RECOMENDAÇÃO BASEADO EM CONTEUDO.

Recomendação colaborativo: baseia-se em produtos comprados por clientes de gostos semelhantes para realizar uma recomendações

Recomendação baseado em conteudo: baseia-se nas semelhança dos atributos de um produto para realizar recomendaçõs

No caso, nosso sistema de recomendação hibrido ira utilizar o sistema de recomendação colaborativo para criar uma lista de possiveis 
produtos baseados em clientes com gostos semelhantes e com cada produto dessa lista o sistema hibrido irá utilizar o sistema de recomendação 
baseada em conteudo para recomendar um produto semelhante com a maior nota possivel.
Ai final o sistemas deverá perguntar ao usuario se ele não gostaria de realizar novas compras e sugerir 5 produtos com as especificações
de nome, cor e marca que possivelmente poderão atiçar sua vontade de realizar novas compras




Obs: Vale notar que estamos utilizando um dataset de uma loja de roupas. Escolhemos esse tipo de dataset pois assim como remedios, roupas não deverão ser recomendadas pra clientes que não condizem com sertas carcteristicas fisicas.
ex: Nosso sistema não deve recomendar uma camisa "p" para um cliente tamanho "g", do mesmo jeito que ele não deverá recomendar um remedio de colicas menstruais para um homem


