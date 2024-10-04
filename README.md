## Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.

Claro! Vamos explorar cada um desses conceitos em JavaScript:

### 1. **String**

##### Strings são sequências de caracteres, escritas entre aspas simples ou duplas.

```javascript
let str1 = 'Texto simples'
let str2 = "Outro texto"
let str3 = `Texto com interpolação: ${str1}`
```

### 2. **Variável**

##### As variáveis ​​podem ser usadas para armazenar dados em um programa, como strings, números, objetos JSON ou valores booleanos. Em JavaScript, existem três tipos de variáveis ​​diferentes: var , let , e const .

**var: Declara variáveis com escopo de função ou global.**
  ```javascript
  var idade = 30
  ```

**let: Declara variáveis com escopo de bloco.**
  ```javascript
  let nome = "Maria"
  ```

**const: Declara variáveis com escopo de bloco que não podem ser reatribuídas.**
  ```javascript
  const pi = 3.14
  ```

### 3. **Number**

No JavaScript, o conceito de Number refere-se ao tipo de dado utilizado para representar números. Ele é um dos tipos primitivos da linguagem e pode ser utilizado para lidar com operações matemáticas e aritméticas.

```javascript
let inteiro = 42
let decimal = 3.14
```

### 4. **Switch Case**

O switch é uma estrutura de controle em JavaScript usada para executar um bloco de código entre várias alternativas baseadas no valor de uma expressão.

```javascript
let cor = 'verde'

switch (cor) {
  case 'vermelho':
    console.log('A cor é vermelha.')
    break;
  case 'verde':
    console.log('A cor é verde.')
    break;
  case 'azul':
    console.log('A cor é azul.')
    break;
  default:
    console.log('Cor desconhecida.')
}
```

### 5. **If e Else**

O if e o else são estruturas de controle fundamentais em JavaScript usadas para executar diferentes blocos de código com base em condições.

```javascript
let idade = 18

if (idade >= 18) {
  console.log('Você é adulto.')
} else {
  console.log('Você é menor de idade.')
}
```


```javascript
let nota = 85

if (nota >= 90) {
  console.log('Nota A')
} else if (nota >= 80) {
  console.log('Nota B')
} else if (nota >= 70) {
  console.log('Nota C')
} else {
  console.log('Nota abaixo de C')
}
```

### 6. **Prompt**


O prompt é uma função integrada em JavaScript que exibe uma caixa de diálogo ao usuário, permitindo que ele insira dados

```javascript
let nome = prompt('Qual é o seu nome?')
console.log('Olá, ${nome}!`)
```

### 7. **Concatenação**

Em JavaScript, a concatenação é o processo de unir dois ou mais valores para formar um único valor. O mais comum é concatenar strings, mas também é possível concatenar arrays.

  ```javascript
  let primeiroNome = 'John'
  let sobrenome = 'Doe'
  let nomeCompleto = primeiroNome + ' ' + sobrenome
  console.log(nomeCompleto)
  ```

  ```javascript
  let primeiroNome = 'John'
  let sobrenome = 'Doe';
  let nomeCompleto = `${primeiroNome} ${sobrenome}`
  console.log(nomeCompleto)
  ```

### 8. **Array**

Um array é uma estrutura de dados que armazena uma coleção de elementos (como números, strings, objetos, etc.) em uma única variável.

```js
let numeros = [10, 20, 30, 40, 50]
```

### 9. **Elementos de array**

#### **1. push()**

Adiciona um ou mais elementos ao final do array.

```js
let frutas = ['maçã', 'banana']
frutas.push('laranja')
```

#### **2. pop()**

Remove o último elemento do array e o retorna.

```js
let numeros = [1, 2, 3, 4]
let ultimo = numeros.pop()
```

#### **3. shift()**

Remove o primeiro elemento do array e o retorna.

```js
let animais = ['gato', 'cachorro', 'coelho']
let primeiro = animais.shift()
```

#### **4. unshift()**

Adiciona um ou mais elementos ao início do array.

```js
let carros = ['Fusca', 'Civic']
carros.unshift('Gol')
```




## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 
