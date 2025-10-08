# FuncoesJS
Em JavaScript, podemos destacar três tipos de funçôes:Declaration Funcion, Expression Funcion,Arrow Funcion.

----------------------------------------------
(1).Declaration Funcion: Ela permite deefinir uma função e que pode ser chamada antes ou depois da sua definição.


  ex: 
```js
  funcion Somar (A,B){
    return A + B;
  } 
```
"Somar" é o identificador 
"A,B" são os parâmetros
"Return" é o retorno da função

----------------------------------------------
(2).Expression Funcion:Diferente da Declaration ela precisa ser declarada antes de ser usada.

  ex: 
```js
let Somar = funcion (A,B){
    return A + B;
  }
```                  
Nela o indentificador vem antes do nome função.
"Somar = funcion"

----------------------------------------------
(3).Arrow Funcion: É uma forma mais simples e curta de escrever uma função, por isso é a mais comumente utilizada hoje em dia.

  ex: 

Ela pode ser utilizada de duas maneiras:

```js
let Somar =  (A,B) => A + B;
```
Forma mais simples, quando o codigo é simples e couber em uma linha assim ja retorna direto,sem precisar usar "{}" e "return".
```js
let Somar =  (A,B) =>{
    let Somar = A + B;
    return result;
    
}
```
Essa forma é um puco mais longa e permite que coloque mais comandos ou dados.



