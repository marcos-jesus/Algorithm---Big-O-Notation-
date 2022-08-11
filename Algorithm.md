Notação Big O é uma forma simples de classificar a complexidade de um algoritmos.

Se você sabe o Big O de um algortimo podemos saber qual será a performance e eficiencia dele
conforme o volume de entrada de informações aumenta.

Se temos mais de um algoritmo para resolver o mesmo problema podemos usar o Big O para saber qual deles
é o mais eficiente.


Exemplos conceituais

> function meuNumero(numero) { <br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
  console.log(`Seu número é o ${numero}`); <br/>
}

meuNumero(5)

independente de qual é a entrada essa função sempre terá o mesmo custo computacional, seja a entrada o número 1 ou 1000000.

O custo será exatamente o mesmo, o Big O dessa função será o 
> O(1)

No Big O a entrada de dados é representado pela letra (n).

Nesse caso o Big O é uma costante independentemente da entrada.

independente de (n) o (n) não aparece aqui.

> function meuNumero(numero) { <br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  for(let i = 1; i <= numero; i++) { <br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  console.log(``-> ${i})<br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
}<br/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  console.log('Seu número é o '+numero)<br/>
}<br>


O custo dessa função será o 
> O(n)

e não é mais constante, varia conforme a entrada, quanto maior a entrada maior o tempo de execução.

O custo é linearmente proporcional a entrada.
