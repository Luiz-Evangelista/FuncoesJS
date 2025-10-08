# FuncoesJS
Em JavaScript, podemos destacar três tipos de funçôes:Declaration Function, Expression Function,Arrow Function.

----------------------------------------------
(1).Declaration function: Ela permite definir uma função e que pode ser chamada antes ou depois da sua definição.


  ex: 
```js
  function Somar (A,B){
    return A + B;
  }

```
"Somar" é o identificador 
"A,B" são os parâmetros
"Return" é o retorno da função

Outro exemplo desse tipo de função:
```js
function mensagem(nome) {
  console.log("Olá, " + nome + "!");
}

mensagem ("Luiz");
```


----------------------------------------------
(2).Expression Function:Diferente da Declaration ela precisa ser declarada antes de ser usada.

  ex: 
```js
let Somar = function(A, B) {
  return A + B;
}
```                  
Nela o indentificador vem antes do nome função.

"Somar =function"

Pois a função está dentro de uma variável.

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



