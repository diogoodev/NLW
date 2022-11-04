#  O que é programação?
### Ensinar o computador
- Algoritimos: Sequencia de passos e conjuntos de regras
- Logica de Programação: 
 Maneira de pensar
 - Sintaxe: Maneira correta de escrever
 ### Javascript
 - Linguagem de programação: Interpretada e executada pelo navegador.
 - A inteligência da triade: HTML é a estrutura, CSS é a beleza, JS é a inteligência
 #### Porque a prender JavaScript ?
 - Aplicativos: Para web, desktop e mobile
 - Empresas famosas estão usando
 - Moderna e Viva: Comunidade e linguagem que cresce cada vez mais.

 #### Instruções e sintaxe
 > Toda linguagem é escrita com esses 2 principios
 - Instruções (declarações): Ordens ao computador
 - Sintaxe: Maneira correta de escrever
 ``` javascript
 alert("Fala, Dev" ) // Fala, Dev!
 alert((10*100) + "abraços") //  1000 abraços
``` 
> Existem palavras resevedas em cada linguagem de programação, elas dão sinificados a diversas instruções
###  Variáveis
>Basicamente são caixinhas/espaços onde armazenamos um tipo de dado para ser usado posteriormente
### Tipos de dados
> Informações podem ser em textos, numeros , booleanos( valores que são logicos: Verdadeiro ou Falso) e dados mais estruturados

```javascript
//declarar e atrubir valor
let boasVindas ="Fala, Dev"
boasVindas = "Fala, Dev Beleza?!"

// constante não pode mudar o valor
const serHumano =  true;
serHumano = false // erro

//string
""
''
``
//Number
1
1.2
//Boolean
true
false

```
---
## Funções
  Rei do javascript

- Agrupamento de código
- Reuso de código
- Miniprogrmas dentro do progrma maior
- Toda linguagem oferece muitas opções
``` javascript
// usando uma função
alert("fala, Dev!")

// criando uma função
function alert (text){
  return text
}
```
## Objetos
Em javascript tudo é opbjeto
- Atributos: são as propriedades de um objeto
- Metodos: São as funcionalidades de um objeto

```javascript
// criando um objeto
const person = {
  age: 18,
  drive: function(){}
}

// usando um objeto
person.drive()

```