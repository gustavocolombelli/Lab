## Estruturas de repetição: For, While, do while, recursão e forEach
### Exercícios de fixação

#### 1. For 
>

* 1.1\. Crie uma variável x, atribua um valor a ela e imprima todos os múltiplos dela até 20.
* 1.2\. Crie um vetor de tamanho 20 e atribua os valores do exercício anterior a ela. Imprima o vetor.
* 1.3\. Crie um vetor de tamanho 10 e atribua, para cada posição, o dobro do valor anterior. Escolha um número para iniciar e imprima o vetor.
* 1.4\. Crie uma matriz 5x5 e preencha-a com a multiplicação da linha pela coluna.
* 1.5\. Crie uma matriz 10x10 e, utilizando dois _for_ preencha-a com 1 quando a linha e a coluna tiverem o mesmo valor (linha 1 e coluna 1, linha 2 e coluna 2, ...), ou zero quando forem diferentes. 

#### 2. While e do While
>

* 2.1\. Escreva um programa que use um loop while para imprimir os números de 1 a 10.
* 2.2\. Escreva um programa que use um loop while para somar números até que a soma atinja ou ultrapasse 100.
* 2.3\. Escreva um programa que use um loop while para fazer uma contagem regressiva de 10 a 1.
* 2.4\. Inicialize um vetor com 10 números. Use um loop while para calcular a soma dos elementos do vetor.

#### 3. Recursão
>

* 3.1\. Escreva uma função recursiva que calcula o fatorial de um número.

### Desafios
* Validador de CPF:
O Cadastro de Pessoa Física (ou CPF) é um número composto por nove dígitos básicos e mais dois dígitos denominados verificadores. A partir dos nove dígitos básicos, é possível calcular o valor dos dígitos verificadores.

O cálculo se dá a partir da seguinte lógica:

- Para o primeiro dígito verificador, multiplica-se o primeiro dígito básico por 10, o segundo por 9, o terceiro por 8, e assim consecutivamente até o nono dígito, multiplicado por 2. Em seguida, soma-se todos os resultados. Esta soma é multiplicada por 10 e então dividida por 11, onde o resto deste cálculo origina o primeiro dígito verificador.

- Para o segundo dígito verificador, o processo é o mesmo, porém iniciando a multiplicação do primeiro dígito por 11 e encerrando a multiplicação do último dígito por 3. Então, o primeiro dígito verificador é multiplicado por 2 e adicionado à soma. Esta soma é multiplicada por 10 e dividida, onde o resto deste cálculo origina o segundo dígito verificador.

Caso o resultado de um dígito verificador seja 10, o valor real dele é de zero.

Para fins de teste, o CPF 123.456.789 tem os dígitos verificadores 0 e 9.
