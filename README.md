# FuncoesJS
Em JavaScript, podemos destacar três tipos de funçôes:Declaration Function, Expression Function,Arrow Function.

----------------------------------------------
(1).Declaration function: Ela permite definir uma função e que pode ser chamada antes ou depois da sua definição.


  ex: 
```js
function Somar(A, B) {
    return A + B;
}

console.log(Somar(3, 4)); // Saída: 7

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

Aqui estamos criando uma função chamada mensagem,ela recebe um parâmetro, chamado nome e esse parâmetro nome funciona como uma caixinha que vai guardar qualquer valor que você passar para a função.
Olá, " + nome + "!" é uma mensagem que junta texto com o valor do parâmetro.
Por exemplo, eu digitei meu nome "Luiz", o resultado é "Olá, Luiz!".

obs:Console.log é pra deixar/mostrar para o usuário o que acontece na função ou código visível, ele é o print do python no Javascript.

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
Diferença principal em relação à Declaration Function:Uma Declaration Function pode ser chamada antes de ser definida no código ja uma Expression Function não pode ser usada antes da linha em que é definida.
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
Aqui sim usamos {} para permitir mais linhas de código dentro da função e também nesse caso, é necessário usar return explicitamente.

