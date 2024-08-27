# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico

JAVASCRIPT

String
conceito de string

```js
javascript
let saudacao = "Olá, mundo!";
Aqui, saudacao é uma variável que armazena a string "Olá, mundo!".
````
Concatenar strings:

Você pode juntar duas ou mais strings usando o operador de adição (+):

javascript
let nome = "Maria";
let mensagem = "Olá, " + nome + "!";
console.log(mensagem); // Saída: Olá, Maria!
Interpolação de strings:

Usando crase, você pode inserir variáveis diretamente dentro de strings:

javascript
let idade = 25;
let apresentacao = `Eu tenho ${idade} anos.`;
console.log(apresentacao); // Saída: Eu tenho 25 anos.
Métodos de strings:

Strings têm muitos métodos úteis. Por exemplo:

length: Retorna o comprimento da string.

javascript
let texto = "JavaScript";
console.log(texto.length); // Saída: 10
toUpperCase(): Converte todos os caracteres para maiúsculas.

javascript
let grito = "estou empolgado!";
console.log(grito.toUpperCase()); // Saída: ESTOU EMPOLGADO!
indexOf(): Encontra a posição de uma substring.

javascript
let frase = "Eu adoro programação";
console.log(frase.indexOf("adoro")); // Saída: 3
