*Verifique se um número digitado pelo usuário é positivo ou negativo. Mostre um alerta informando.*
```js
let numero = prompt('digite um numero);
if (numero >= 0) {
    alert('Seu numero é positivo');
} else {
    alert('Seu numero é negativo');
}
```

Esse foi até que **bem simples**, criei uma **variável** e logo após pergunto pro usuário dizer um número qualquer, sendo <u>positivo</u> ou <u>negativo</u>.
Logo após disso, será retornado pra ele, dizendo qual é o **sinal daquele número**.

Se o número for **maior ou igual `(>=)` a zero**, será lido que o número é **positivo**;
caso contrário, se o número não obtiver essas características, ele automaticamente será **negativo**.

Creio que eu **não precise atribuir uma nova característica**, porque assim fica bem mais **simples e limpo o código**.

