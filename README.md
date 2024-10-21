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

```js
let nome = "Bill";
let mensagem = "Olá, " + nome + "!";
console.log(mensagem); // Saída: Olá, Bill!
```
Interpolação de strings:

Usando crase, você pode inserir variáveis diretamente dentro de strings:
```js
let idade = 25;
let apresentacao = `Eu tenho ${idade} anos.`;
console.log(apresentacao); // Saída: Eu tenho 25 anos.
```

## Estruturas de Controle: if e else em JavaScript
### As estruturas if e else em JavaScript são fundamentais para a tomada de decisões em seu código. Elas permitem que você execute diferentes blocos de código com base em condições específicas.

```js
if (condição) {
    // Código a ser executado se a condição for verdadeira
} else {
    // Código a ser executado se a condição for falsa
}
```
```js
let idade = 18;

if (idade >= 18) {
    console.log("Você é maior de idade.");
} else {
    console.log("Você é menor de idade.");
}
```
```js
let nota = 75;

if (nota >= 90) {
    console.log("Aprovado com distinção");
} else if (nota >= 70) {
    console.log("Aprovado");
} else {
    console.log("Reprovado");
}
```

## Array

### Um Array é uma estrutura de dados usada para armazenar vários valores em uma única variável. Em JavaScript, arrays são dinâmicos, ou seja, podem crescer ou diminuir em tamanho e podem armazenar diferentes tipos de dados (números, strings, objetos, etc.).

```js
let frutas = ["Maçã", "Banana", "Laranja"];
```

### Acessando elementos de um Array
Os elementos de um array são indexados começando do número 0. Para acessar o primeiro elemento, por exemplo, usamos:

```js
let primeiraFruta = frutas[0]; // "Maçã"
```
## Propriedades e Métodos Comuns
length: Retorna o número de elementos do array.

```js
console.log(frutas.length); // 3
```

push(): Adiciona um elemento ao final do array.

```js
frutas.push("Uva");
```
pop(): Remove o último elemento do array.

```js
frutas.pop(); // Remove "Uva"
```
shift(): Remove o primeiro elemento do array.

```js
frutas.shift(); // Remove "Maçã"
```
unshift(): Adiciona um elemento no início do array.

```js
frutas.unshift("Manga");
```

## Atividades Feitas
```js
https://codepen.io/Tylapio/pen/LYKeMmo
```
```js
https://codepen.io/Tylapio/pen/LYKeMmo
```
```js
https://codepen.io/Tylapio/pen/GRVpaem
```
```js 
https://codepen.io/Tylapio/pen/ExBMgzd
```



