// 1. Criando uma variável nome e exibindo seu valor
let nome = "thayanne";
console.log(nome);

// 2. Criando variáveis idade e altura e exibindo os valores
let idade = 25;
let altura = 1.75;
console.log(`Idade: ${idade}, Altura: ${altura}`);

// 3. Calculando o preço com desconto
let preco = 50;
let desconto = 0.2;
let precoFinal = preco - (preco * desconto);
console.log(`Preço com desconto: ${precoFinal}`);

// 4. Verificando a temperatura
let temperatura = 30;
if (temperatura > 25) {
    console.log("Está calor!");
} else {
    console.log("Está fresco!");
}

// 5. Verificando se a pessoa é maior de idade
if (idade >= 18) {
    console.log("Você é maior de idade");
} else {
    console.log("Você é menor de idade");
}

// 6. Verificando a nota do aluno
let nota = 8;
if (nota >= 7) {
    console.log("Aprovado");
} else if (nota >= 5) {
    console.log("Recuperação");
} else {
    console.log("Reprovado");
}

// 7. Verificando se dois números são iguais
let numero1 = 10;
let numero2 = 15;
if (numero1 === numero2) {
    console.log("Os números são iguais");
} else {
    console.log("Os números são diferentes");
}

// 8. Exibindo nome e idade com concatenação
console.log(`Olá, meu nome é ${nome} e eu tenho ${idade} anos`);

// 9. Loop imprimindo números de 1 a 10
for (let i = 1; i <= 10; i++) {
    console.log(i);
}

// Simulando entradas do usuário com um array
let entradas = [3, 8, 2, 5]; // O usuário "digitaria" esses números
let index = 0;
let numeroDigitado;

do {
    numeroDigitado = entradas[index]; // Pegando o próximo número do array
    console.log("Número digitado:", numeroDigitado);
    index++;
} while (numeroDigitado != 5);

console.log("Você digitou 5. O loop foi encerrado.");

let valorDigitado;

do {
    numeroDigitado = Math.floor(Math.random() * 10); // Gera um número de 0 a 9
    console.log("Número gerado:", numeroDigitado);
} while (numeroDigitado != 5);

console.log("O número 5 foi gerado. Loop encerrado.");


// 11. Imprimindo a tabuada do número 7
let numeroTabuada = 7;
for (let i = 1; i <= 10; i++) {
    console.log(`${numeroTabuada} x ${i} = ${numeroTabuada * i}`);
}

// 12. Exibindo números pares de 0 a 20
for (let i = 0; i <= 20; i += 2) {
    console.log(i);
}

// 13. Função para calcular a área de um círculo
function calcularAreaCirculo(raio) {
    return Math.PI * Math.pow(raio, 2);
}
console.log(`Área do círculo: ${calcularAreaCirculo(5)}`);

// 14. Comentários e soma de dois números
// Criando um programa que soma dois números
function somarNumeros(a, b) {
    return a + b;
}
console.log(`A soma de 5 e 10 é: ${somarNumeros(5, 10)}`);

// 15. Refatoração do código para boas práticas
function somarValores(valor1, valor2) {
    return valor1 + valor2;
}
let resultado = somarValores(10, 20);
console.log(`Resultado da soma: ${resultado}`);