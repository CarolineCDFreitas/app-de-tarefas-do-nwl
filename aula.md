## Linguagem de programação

Maneira de dar instrução ao computador.
Como um lego, você irá utilizar peças para criar algoritmos, ou seja, para resolver problemas.

> 💡 **Algoritmos**: Sequência de passos lógica e finita para resolução de um problema.

## Peças de uma linguagem

- Comentários
- Declaração de variáveis (const, let)
- Operadores (distribuição, concatenação, matemáticos, lógicos)
- Tipos de dados (primitivos: string, number, bigint, null, undefined, boolean, symbol; referenciais: objects {arrays, function})
- Estrutura de dados (functions, object, array)
- Controle de fluxo (if/else)
- Estrutura de repetição (for, while)

# Fases de resolução de um problema

Coletar os dados
Processar os dados (manipular, alterar ...)
Apresentar os dados

## Escopo e variáveis:

Variáveis globais e locais
Constantes

## Tipos de dados:

Strings (textos): "" '' ``
Number: 2, 3.14
Boolean: true ou false
Function

# Operadores

- Operadores de atribuição de valor (=)
- Operador de concatenação (+)
- Operadores de comparação: == != <= >= < >
- Spread Operator: ...

## Estruturas de dados

### Arrays

Uma lista que contém qualquer tipo de dado
- Métodos de array: push, [find, forEach, filrer, map] : HOF (Higher Order Function)

### Objects

Atributos e métodos
Criação e manipulação de objetos
Acesso a propriedades de objetos

### Functions

 Criar
 Executar
 Arrow Function (const criarMeta = () => {}
) / named function (function criarMeta () {})

# Estrutura de repetição

-  while
- if/else

# Condicionais

- switch

## Módulos em Node.js:

- Importação de módulos (require, Common JS)
Biblioteca 'inquirer' para criar prompts interativos
- FS (file system)

## JSON
 - JavaScript Object Notstio (.json)
 - JSON.parse(): transforma os dados de JSON para JS 
 - JSON.stringify(): transforma os dados de JS para JSON

## Programação assíncrona e Promises:

- Uso de funções assíncronas (async/await)


** AULA 1 **

////variáveis

/*const mensagem = 'Olá, Jaehyun!';

  {
     const mensagem = 'Olá, mundo!';
     console.log(mensagem);
  }

 console.log(mensagem); */


//arrays, objects

/* let metas = ["Caroline", "Professor"];

 console.log(metas[0] + " " + "é demais");

let meta = {
   value: "ler um livro por mês",
   checked: false
}

console.log(meta.value); */


//function

/* const criarMeta = () => {}

function criarMeta () {}

*/

** AULA 2 **

//condicional while

/* const start = () => {
   let count = 1;
    whole (count <= 10) {
      console.log(count)
      count = count + 1;
    }
} */

count = count + 1; === count++


//instalação de uma biblioteca ou módulo no terminal
// npm install inquirer
// importação de um método específico de um módulo
// const { select } = require ('@inquire/prompts');
// spread operator (...) (as reticências) serve para COPIAR os valores de uma variável sem modificá-la.
se existir informações que se sobrepõem, a última escrita prevalecerá.
