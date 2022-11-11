# Trabalho sobre Ordenação

### [BubbleSort](https://github.com/jotaquissak/estrutura-de-dados-c-estacio/blob/main/bubbleSort.c)
  O metodo de ordenação citado se basea na ideia de jogar para o final os maiores fazendo uma comparação por vez sendo iniciada apartir do índice 0 e se direcionando até o -1, fazendo a troca se encontra um número menor que o anterior.
	
<div align="center">
<img src="https://user-images.githubusercontent.com/80067222/201231768-41e20129-c0b3-492f-ab96-36e8915ffe0c.gif" width="400px"/>
</div>

### [InsertionSort](https://github.com/jotaquissak/estrutura-de-dados-c-estacio/blob/main/insertionSort.c)
  O metodo de ordenação citado se basea na ideia de ordenar de forma objetiva os numeros, já os colocando desde o principio em ordem crescente. Sendo feito pegando o primeiro número e comparando com o seguinte, se for mais será feita a troca e ele seguirá para fazer a troca, todo número trocado deve fazer comparações com os números anteriores ao trocado, com o objetivo de encontrar um menor, pois se forem maiores devem ser novamente feita a troca.

<div align="center">
<img src="https://user-images.githubusercontent.com/80067222/201231938-bdc2128c-9f68-41ea-9060-f5bfcc1bf56f.gif" width="400px"/>
</div>

### [SelectionSort](https://github.com/jotaquissak/estrutura-de-dados-c-estacio/blob/main/selectSort.c)
  O metodo de ordenação citado se basea na ideia de colocar o menor na frente, até que a sequencia execute o número de passos equivalente a quantidade de elementos dentro do array e o mesmo se encontra ordenado de maneira crescente.
	
<div align="center">
<img src="https://user-images.githubusercontent.com/80067222/201232081-e1e2e08c-3631-437f-84cd-d1adcf3b3541.gif" width="100px" height="300px"/>
</div>

### [MergetSort](https://github.com/jotaquissak/estrutura-de-dados-c-estacio/blob/main/mergeSort.c)
  O metodo de ordenação citado se basea na ideia de "Dividir para conquistar", ou seja, ele divide o vetor inicial em subvetores que continuam a se dividir em vetores subsequentes até que sobre apenas 1 índice dentro do vetor. Isso feito os subvetores volta a se reagrupar formando vetores maiores organizados até voltar ao tamanho do vetor original.

<div align="center">
<img src="https://user-images.githubusercontent.com/80067222/201232281-17996b90-f887-4bf1-bccb-52aaecbe120e.gif" width="400px"/>
</div>

## Comparação de Complexidade
  **O cálculo da complexidade se dá pela formula de recorrência, que é váriavel.**

<div align="center">
<img src="https://user-images.githubusercontent.com/80067222/201243473-3e50912c-56c0-44f5-84fa-9a378f5a866a.png" width="433px" height="78px"/>
</div>

 **Importante**: Olhando apenas os números faz parecer que os mesmo são próximos, mas conforme o gráfico abaixo, pode se perceber diferenças grandes entrem eles.
  
<div align="center">
<img src="https://user-images.githubusercontent.com/80067222/201233624-790e3ea8-d46d-420f-a2be-72611c090278.jpeg" width="700px">
</div>

## Comparação de Estabilidade
  A estabilidade é definida se o metodo de ordenação respeita a ordem lexical do objeto passado.
  
  **BubbleSort:** ✔️
  
  **InsertionSort:** ✔️
  
  **SelectionSort:** ✔️
  
  **MergeSort:** ✔️
  
  **Importante:** Todos os metodos de ordenação usados respeitam a ordem lexicografia, mas alguns outros não o fazem, como o **HeapSort** e o **QuickSort**
  
 ## Considerações
  Cada metodo de ordenação pode e tem seu melhor funcionamento em um cenário ideal para ele, com isso irei dar alguns pontos sobre cada um para que assim você possa saber se é o melhor para a sua necessidade.
  
  **BubbleSort**:
  
  - Suas principais vantagens são sua simplicidade, facilidade de ser criada e não fazer uso de armazenamento temporário.
  - Sua grande desvantagem é o fato de não suportar listas com muitos elementos, por sua complexidade ser elevada.
  
  Portanto, o bubble sort é indicada para o ensino acadêmio, mas não para aplicações na vida real.

  **InsertionSort**:
  
  - As principais vantagens são ser uma ordenação simples, tendo um bom desempenho com listas pequenas, baixo uso de memória.
  - Sua desvantagem com relação a outros metodos de ordenação é sua complexidade extremamente elevada.
  
  No entanto, é particularmente útil com listas de poucos itens.

  **SelectionSort**:
  
  - As principais vantagens é seu bom desempenho em listas pequenas, não necessitar de armazenamento temporário.
  - A principal desvantagem é em listas grandes onde sua complexidade se torna um problema.
  
  Devido a isso, esse tipo seleção é adequado apenas para uma lista em que poucos elementos estejam em ordem aleatória.
  
  **MergeSort**:
  
  - A principai vantagem é sua velocidade mesmo em listas com muitos itens, pois não depende da sequência de entrada.
  - Sua principal desvantagem é a necessidade do uso de um vetor auxiliar, aumentando assim o uso de memória durante a execução.

  Por ser o único que aguenta lista com grande quantidade de elementos, ela é mais recomendada para tal.
