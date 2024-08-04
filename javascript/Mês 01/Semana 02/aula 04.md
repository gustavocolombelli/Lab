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
* 2.2\. Crie uma função chamada isBissexto que receberá um ano como parâmetro e retornará o valor booleano true se for bissexto e falso caso contrário [Método para determinar se um ano é bissexto](https://learn.microsoft.com/pt-br/office/troubleshoot/excel/determine-a-leap-year "Ano bissexto").
* 2.3\. Crie uma função chamada isPar que receberá um numero como parâmetro e retornará true se for par, e false caso impar.
* 2.4\. Crie uma função que receba dois números e retorne o maior dentre eles

#### 3. Switch
>https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/switch

* 3.1\. Escreva uma função que receba um número de 1 a 7 e retorne o dia da semana correspondente (1 para Domingo, 2 para Segunda, etc.).
* 3.2\. Escreva uma função diasNoMes(ano, mes) e retorne a quantidade de dias para o mês informado, considere ano bissexto na atribuição de dias.  [Método para determinar quantidade de dias em fevereiro caso seja bissexto](https://www.brasildefato.com.br/2024/02/29/ano-bissexto-por-que-fevereiro-tem-29-dias-em-2024#:~:text=O%20calend%C3%A1rio%20deste%20ano%20possui%20366%20dias&text=Isso%20ocorre%20por%20conta%20do,civil%20e%20o%20ano%20tr%C3%B3pico. "Fevereiro - Ano bissexto").

#### 4. Operador de coalescência nula
> https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Operators/Nullish_coalescing

* 4.1\. Crie uma função imprimirNumeros(num1, num2) e utilizando coalescência nula, verifique se algum dos dois números são nulos ou undefined e imprima o número ou "Num1 não fornecido" ou "Num2 não fornecido"
* 4.2\. Chame a função imprimirNumeros 5 vezes, alternando sua parametrização entre num1 e num2 com os parâmetros null, undefined, 1, 2, 3... E verifique os resultados obtidos 


### Desafio

Neste desafio, desenvolva três funções que lidam com a verificação de anos bissextos e a contagem de dias nos meses. Crie uma função para determinar se um ano é bissexto. 

Crie uma função que retorna a quantidade de dias em um mês específico, utilizando um switch para lidar com cada mês do ano e ajustando o número de dias em fevereiro conforme o ano bissexto ou não.

Combine essas funções em uma função principal que, dado um ano, imprime a quantidade de dias para cada mês daquele ano.

Função para Verificar Ano Bissexto

A função deve receber um ano como parâmetro.
Deve retornar true se o ano for bissexto e false caso contrário.
Um ano é bissexto se for divisível por 4 e não divisível por 100, exceto se for divisível por 400.

Função para Retornar a Quantidade de Dias no Mês
A função deve receber um ano e um mês como parâmetros.
Deve usar um switch para retornar a quantidade de dias no mês.
Fevereiro deve considerar se o ano é bissexto para retornar 28 ou 29 dias.
Os outros meses devem retornar a quantidade de dias correta (31 ou 30 dias).

Função Final que Imprime a Quantidade de Dias por Mês para um Ano Específico
A função deve receber um ano como parâmetro.
Deve usar as funções anteriores para determinar e imprimir a quantidade de dias em cada mês do ano fornecido.
A saída deve ser clara, indicando o nome do mês e a quantidade de dias.
