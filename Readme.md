//função Soma

function somar(N1, N2) {
  return N1 + N2;
};



exports.somar = somar

//Modulo Externo Input dados


let readlineSync = require('readline-sync');



let num1 = readlineSync.question('Digite um numero: ');
let num2 = readlineSync.question('Digite um numero: ');
let somar =  require('./somar');
let n1 = Number(num1)
let n2 = Number(num2)

console.log(somar(n1,n2))

// Modulo sendo executado

let soma =  require('./somar');
soma.somar


console.log(soma.somar(8,10));


