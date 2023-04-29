# Exercício Network Analysis

### 1. Definições:
(a) Subgrafo <br>
```
Um grafo G pode ser chamado de subgrafo G¹ quando ele tem um subconjunto de vértices e arestas de G.
```
(b) Grafo Bipartido <br>
 ```
Grafos bipartidos são aqueles que podem ser divididos em dois conjuntos disjuntos, por exemplo, conjunto A e conjunto B,
de tal forma que cada aresta conecte um nó do conjunto A a um nó do conjunto B.
```
(c) Grafo Hamiltoniano <br>
```
É um grafo que contém o circuito Hamiltoniano, um circuito Hamiltoniano é aquele onde as vértices iniciais são iguais às finais.
```
(d) Grafo Euleriano <br>
```
É um grafo cujos nós têm uma quantidade par de arestas.
```

### 2. Describe how a breadth-first search algorithm works.
```Esse algoritmo inicia a busca pelo no raiz e percorre os nós adjacentes, o algoritimo explorar os nós vizinhos
que ainda não visitou e assim por diante até que encontre o objetivo.
```
	
### 3. How many edges does a complete graph with n vertices have? What about a complete directed graph with n vertices?
```
Um grafo completo com n vértices tem n(n-1)/2 arestas em um grafo não direcionado, e n(n-1) arestas em um grafo direcionado.
```

### 4. What are isomorphic graphs? Draw an example.
[isomorphic graphs](https://drive.google.com/file/d/1nbDOmO4mCDUkBeXbv21HdZ893YR7aCLq/view?usp=sharing)
```
São grafos que contém a mesma estrutura, mesmo grau, mesma quantidade de vertices e arestas, grafos isomorfos
tem matrizes de adjacência com as mesmas propriedades.
```

	
### 5. Calculate the degree of the nodes for both node types in the bipartite adjacency matrix from the figure below. Find the isolated node(s).
![adjacency matrix](https://raw.githubusercontent.com/terrematte/network_analysis/main/exercises/img/matrix01.png)

### 6. Given the digraph `G = (V, E)` where `V = {M, N, O, P, Q, R, S}` and 

`E ={(M, S), (N, O), (P, R), (N, S), (O, M),
	 (N, Q), (O, M), (P, P), (S, M), (O, N), 
	 (S, M), (N, R), (P, M), (M, S)}`

	(a) Specify, if any, a simple path from vertex M to vertex S.

	(b) Specify, if any, a simple cycle, involving at least 4 nodes.

	(c) Is the digraph connected or not connected?

	(d) What is the degree of vertices N and R.

	(e) Represent the digraph using adjacency list representation.

	(f) Represent the digraph using adjacency matrix representation.

### 7. Draw the undirected and directed versions of the graph G(V, E), where V = {1, 2, 3, 4, 5, 6} and E = {(2, 5), (6, 1), (5, 3), (2, 3)}.
[Grafo](https://colab.research.google.com/drive/1nbDOmO4mCDUkBeXbv21HdZ893YR7aCLq#scrollTo=L9dBDP-4NhYN)

### 8. How many edges does a graph have 3 vertices of degree 3 and one vertex of degree 5?
```
Isso significa que temos 3 vertices com 3 aresta cada e 1 vertice com 5 arestas.
3 * 3 = 9
9 + 5 = 14 (total de arestas nesse grafo) 
```
### 9. Mr. A is friend with Mrs. B, but she doesn't like him back. She has a reciprocal friendship with both C and D, but only C considers D a friend. D has also sent friend requests to E, F, G, and H but, so far, only G replied. G also has a reciprocal relationship with A. Draw the corresponding directed graph.
[Grafo](https://colab.research.google.com/drive/1nbDOmO4mCDUkBeXbv21HdZ893YR7aCLq#scrollTo=L9dBDP-4NhYN)

### 10. Draw the graph from the previous exercise as undirected and weighted, with the weight being 2 if the connection is reciprocal, 1 otherwise.
<a href="https://colab.research.google.com/drive/1nbDOmO4mCDUkBeXbv21HdZ893YR7aCLq#scrollTo=L9dBDP-4NhYN" onclick="window.open(this.href,'_blank');return false;">Grafo</a>
