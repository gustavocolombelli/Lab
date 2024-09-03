## _JavaScript Objects_

### Exercício de Fixação

#### Crie um objeto

Crie um objeto chamado carro que tenha as seguintes propriedades:

- `marca`: Uma string representando a marca do carro.
- `modelo`: Uma string representando o modelo do carro.
- `ano`: Um número representando o ano de fabricação do carro.

#### Adicione uma nova propriedade

Adicione uma nova propriedade chamada `cor` e atribua uma cor ao carro.
Modifique a propriedade `ano` para ser o ano atual.

#### Adicione um método 

Adicione um método ao objeto carro chamado descreverCarro. Esse método deve retornar uma string que descreve o carro usando suas propriedades, por exemplo, "Este carro é um Toyota Corolla de 2021 na cor prata.".

#### Percorrendo as Propriedades de um Objeto

Crie uma função chamada listarPropriedades que receba um objeto como parâmetro e retorne um array com os nomes de todas as propriedades desse objeto.

#### Objetos Aninhados

Crie um objeto chamado pessoa que tenha as seguintes propriedades:

- `nome`: Uma string com o nome da pessoa.
- `idade`: Um número com a idade da pessoa.
- `endereco`: Um objeto com as propriedades `rua`, `cidade`, e `estado`.

#### Iterando sobre um Objeto Aninhado

Utilizando o objeto pessoa criado no exercício anterior, crie uma função chamada `listarEnderecoCompleto` que retorne uma string com o endereço completo no formato "Rua `rua`, `cidade` - `estado`".