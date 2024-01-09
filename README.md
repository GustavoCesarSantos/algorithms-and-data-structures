# algorithms-and-data-structures

O que é estrutura de dados ?
- Estrutura de dados é a organização de dados armazenados no computador ou dispotivo de armazenamento. A forma
como organizamos os dados e construimos suas relações podem afetar na performance negativamente ou positivamente.

O que é algoritimo ?
- Algoritimos são instruções passo a passo organizados de forma lógica com o objetivo de executar uma ação.

Complexidade de tempo ?
- Complexidade de tempo é uma das formas que temos de medir a complexidade e performance dos nossos algoritimos.
Nos baseando no número de repetições que um passo executa podemos ver seu tempo de finalização aumentar ou dimi-
nuir e degradar ou melhorar a performance do algoritimo. 
Exemplo escrito:
Cenário: Imagine que temos uma lista com 1000 nomes e precisamos encontrar um nome especifico nela.

Opção 1: Vamos usar um algoritimo que vai receber esse nome especifico e vai procura-lo olhando item a item da lista
Opção 2: Vamos usar um algoritimo que vai receber esse nome especifico e usando a primeira letra do nome vai achar
o espaço na lista onde aquele nome pode estar e vai realizar sua busca alí.

Explicação: Se o nome que queremos for o último da lista, o algoritimo 1 vai verificar 1000x a lista até encontrar e
concluir a ação desejada, em um cenário otimista onde o nome desejado é o primeiro será bem rapido e com apenas 1 re-
petição, porem se a lista aumentar e o nome que queremos achar estiver mais perto do final o número de repetições tam-
irá aumentar junto como o tempo de execução e a performance desse algoritimo vai caindo.
Já no segundo exemplo como não precisamos olhar 1 a 1 e conseguimos ignorar uma parte dos nomes da lista, se a mesma
aumentar não vamos ser tão afetados e vamos conseguir realizar a ação com menos repetições, menos tempo e com uma me-
lhor performance.
