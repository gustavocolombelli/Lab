## Tipos de Condicionais: If, else if, else, switch, operador ternário e coalescência nula
### Exercícios de fixação

#### 1. If, else if e else
>https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else

* 1.1\. Crie uma função que recebe uma nota de um aluno e retorna "Aprovado" se a nota for maior ou igual a 70, e "Reprovado" caso contrário.
* 1.2\. Crie uma função chamada isBissexto que receberá um ano como parâmetro e retornará o valor booleano true se for bissexto e falso caso contrário [Método para determinar se um ano é bissexto](https://learn.microsoft.com/pt-br/office/troubleshoot/excel/determine-a-leap-year "Ano bissexto").
* 1.3\. Crie uma função chamada isPara que receberá um numero como parâmetro e retornará true se for par, e false caso impar.
* 1.4\. Crie uma função para veríficar se um número é positivo, negativo ou zero.
* 1.5\. Crie uma função verificarMariorNumbero, que receberá três números e deverá retornar o maior entre eles.


#### 2. Operador ternário
>https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_operator

* 2.1\. Crie uma função que recebe uma nota de um aluno e retorna "Aprovado" se a nota for maior ou igual a 70, e "Reprovado" caso contrário.
* 2.2\. Crie uma função chamada isBissexto(ano) que receberá um ano como parâmetro e retornará o valor booleano true se for bissexto e falso caso contrário [Método para determinar se um ano é bissexto](https://learn.microsoft.com/pt-br/office/troubleshoot/excel/determine-a-leap-year "Ano bissexto").
* 2.3\. Crie uma função chamada isPar que receberá um numero como parâmetro e retornará true se for par, e false caso impar.
* 2.4\. Crie uma função que receba dois números e retorne o maior dentre eles
* 2.5\. 

#### 3. Switch
>https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/switch

* 3.1\. Escreva uma função que receba um número de 1 a 7 e retorne o dia da semana correspondente (1 para Domingo, 2 para Segunda, etc.).
* 3.2\. Escreva uma função diasNoMes(ano, mes) e retorne a quantidade de dias para o mês informado, considere ano bissexto na atribuição de dias.  [Método para determinar quantidade de dias em fevereiro caso seja bissexto](https://www.brasildefato.com.br/2024/02/29/ano-bissexto-por-que-fevereiro-tem-29-dias-em-2024#:~:text=O%20calend%C3%A1rio%20deste%20ano%20possui%20366%20dias&text=Isso%20ocorre%20por%20conta%20do,civil%20e%20o%20ano%20tr%C3%B3pico. "Fevereiro - Ano bissexto").

#### 4. Operador de coalescência nula
> https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Operators/Nullish_coalescing

* 4.1\. Crie uma função imprimirNumeros(num1, num2) e utilizando coalescência nula, verifique se algum dos dois números são nulos ou undefined e imprima o número ou "Num1 não fornecido" ou "Num2 não fornecido"
* 4.2\. Chame a função imprimirNumeros 5 vezes, alternando sua parametrização entre num1 e num2 com os parâmetros null, undefined, 1, 2, 3... E verifique os resultados obtidos 


### Desafio

Crie uma função imprimirDiasPorMes(ano) que receberá um ano e utilize o console.log para imprimir os dias por mês de um determinado ano.

Saída esperada:

```javascript
imprimirDiasPorMes(2024);
// Saída esperada:
// Janeiro: 31 dias
// Fevereiro: 29 dias
// Março: 31 dias
// Abril: 30 dias
// Maio: 31 dias
// Junho: 30 dias
// Julho: 31 dias
// Agosto: 31 dias
// Setembro: 30 dias
// Outubro: 31 dias
// Novembro: 30 dias
// Dezembro: 31 dias
```

