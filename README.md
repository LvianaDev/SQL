# SQL

- Cursor:
Um cursor servirá à necessidade de iterar linha a linha em cima de uma query já executada
Obs: Normalmente utilizado em procedures. 

Nas versões mais atuais do SQL é visto como uma má prática em alguns cenários, pois pode inteferir diretamente na perfomance da aplicação.
O que foi utilizado: 
CURSOR FAST_FORWARD FOR -- Um cursor que só vai para frente!

- Tabela Temporária:
Às vezes facilitamos um “batch” com o uso de tabelas temporárias, seja física ou em memória, veremos as diferenças e como utilizá-las
Obs: Ao criar uma tabela temporária não esquecer de adicionar um # a frente do nome. Exemplo:  #TempUm

- XML:
É possível transformer uma query em uma representação XML e vice-versa.
