# Trabalho_Optimization
Trabalho de Grupo da Unidade Curricular de Optimization - ISAG - Data Science and Business Intelligence

O Problema da Mochila (Knapsack Problem) é um problema clássico de otimização em ciência da computação e matemática. Trata-se de um problema de otimização combinatória em que o objetivo é selecionar um subconjunto de itens com pesos e valores dados, sujeitos a uma restrição no peso total. O objetivo é maximizar o valor total dos itens selecionados. O problema é frequentemente descrito no contexto de uma mochila com capacidade fixa. Cada item tem um peso específico e um valor correspondente. O desafio é determinar a combinação de itens a incluir na mochila, garantindo que o peso total não ultrapasse a capacidade, ao mesmo tempo que se maximiza o valor total. O problema pode ser formalmente definido da seguinte forma: 

• Dado um conjunto de itens, cada um com um peso wi e um valor vi, onde i representa o índice do item.

• Dada uma mochila com capacidade W. 

• Encontrar um subconjunto de itens que maximize o valor total ∑ivi, mantendo o peso total ∑iwi abaixo ou igual à capacidade da mochila. Existem diferentes variações do Problema da Mochila, incluindo o Problema da Mochila 0/1 (onde cada item pode ser incluído ou excluído). 

É esta variação que iremos usar neste trabalho. 

O Problema da Mochila é conhecido por ser NP-difícil, o que significa que não existe um algoritmo conhecido de tempo polinomial para resolvê-lo exatamente para todas as instâncias. No entanto, diversos algoritmos, heurísticas e métodos de aproximação são utilizados para encontrar soluções aproximadas de forma eficiente.

Neste trabalho iremos recorrer ao algoritmo Simulated Annealing, abordando a questão em 3 passos:

1. Codificar um algoritmo capaz de fazer uma procura pelo ótimo global
2. Testar várias combinações de Temperatura Inicial e de método de atualização de Temperatura  e comentar sobre o impacto que esta atualização e valor tem no resultado final do modelo.
3. O que acontece se o item adicionado for aquele que tiver um rácio de utilidade e peso maior em todas as iterações? A solução final com este método é melhor que a solução original?
