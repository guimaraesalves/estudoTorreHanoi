# Algoritmo Recursivo

**Recursividade** é a definição de uma _*sub-rotina*_ (função o método) que pode invocar a si mesma;

Objetivos:
* Diminuir sucessivamente o problema em um problema menor ou mais simples,até que seja possível resolvê-lo de forma direta, sem recorrer a si mesmo.
* O algoritmo deve ter uma condição de parada, ou seja, um caso primário.
*  **Sem esta Condição o algoritmo não para de chamar a si mesmo.**

> { T(n) = 2.T(n-1) + 1
> { T(1) = 1

**Função T(n)**
* se n=1;
* T=1;
* Senão;
* T=2*T(n-1)+ 1;
* Fim;
* Fim Função;

