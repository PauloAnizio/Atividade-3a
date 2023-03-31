# Atividade 3
 Morumbi

  JUSTIFICATIVA
  
O código apresentado implementa um projeto que consiste em inserir números em uma lista, remover os dados da lista e colocá-los em uma pilha e, em seguida, remover os dados da pilha e colocá-los em uma fila. Em seguida, novos números são inseridos na lista e o processo é repetido.

A implementação do projeto utiliza três classes: Pilha, Fila e o código principal. A classe Pilha implementa uma estrutura de dados que permite inserir e remover elementos na ordem LIFO (Last In First Out). A classe Fila implementa uma estrutura de dados que permite inserir e remover elementos na ordem FIFO (First In First Out). Ambas as classes possuem métodos para verificar se a estrutura está vazia ou cheia, e para inserir e remover elementos.

O código principal cria uma lista com os números [1, 2, 3, 4 e 5] e insere-os em uma pilha, removendo-os da lista sempre da célula inicial. Em seguida, os números são removidos da pilha e inseridos em uma fila. Depois, os números [6, 7, 8, 9 e 10] são inseridos na lista e o processo de inserir na pilha e remover na fila é repetido.

Ao final, o código exibe todos os números que foram inseridos na fila. A ordem dos números exibidos na fila é a mesma em que foram inseridos, pois a implementação da pilha e da fila garantem que os elementos sejam inseridos e removidos respeitando a ordem LIFO e FIFO, respectivamente.

Em relação à implementação do código, nota-se que a estrutura de dados escolhida (Pilha e Fila) é adequada para o problema apresentado, pois permite a manipulação dos elementos em ordem LIFO e FIFO, que são requisitos do projeto. Além disso, o código está bem organizado e utiliza boas práticas de programação, como a criação de classes e métodos para realizar operações específicas.

No entanto, uma possível melhoria seria adicionar mais comentários ao código, explicando em detalhes o que cada trecho de código faz e a lógica por trás das operações realizadas. Isso tornaria o código mais fácil de entender e manter.