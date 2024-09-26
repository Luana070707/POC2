# Arrays em JS 

<p align="center">Este repositório contém exemplos simples que demonstram o uso de métodos comuns de arrays em JavaScript :bulb:</p>

## Métodos Abordados: :memo:

- **`sort`**: Ordena os elementos de um array.
- **`map`**: Cria um novo array com os resultados da chamada de uma função para cada elemento.
- **`reduce`**: Aplica uma função "reducer" a cada elemento do array para reduzir a um único valor.
- **`filter`**: Cria um novo array com todos os elementos que passam em um teste especificado.
- **`Spread`**: Exapande os elementos de um array ou objeto.

## Aqui vamos ver alguns exemplos de códigos do métodos abordados: :technologist:

1. **`sort`**

O método sort oderna os elementos de um array, alterando o array origianal. Por padrão, ele converte os elementos em strings e os ordena alfabética: 

```
const numbers = [10, 5, 20, 3];
const sortedNumbers = numbers.sort((a, b) => a - b);  // Ordena de forma crescente

console.log(sortedNumbers);  // [3, 5, 10, 20]
```

2. **`map`**

O método map cria um novo array com os resultados da aplicação de uma função em cada elemento do array original: 

```
const numbers = [1, 2, 3, 4];
const doubled = numbers.map(num => num * 2);

console.log(doubled);  // [2, 4, 6, 8]
```

3. **`reduce`**

O método reduce executa uma funcão "reducer" em cada elemento do array, resultando em um único valor. Pode ser usado, por exemplo, para somar os valores de um array: 

```
const numbers = [1, 2, 3, 4];
const sum = numbers.reduce((acc, current) => acc + current, 0);

console.log(sum);  // 10
```

4. **`filter`**

O método filter cria um novo array com todos os elementos que passam em um teste implementado pela função fornecida: 

```
const numbers = [1, 2, 3, 4, 5, 6];
const evenNumbers = numbers.filter(num => num % 2 === 0);

console.log(evenNumbers);  // [2, 4, 6]
```

5. **`spread`**

O spread permite que elementos de um array ou objeto sejam expandidos onde múltiplos argumentos ou elementos são esperados: 

```
const arr1 = [1, 2, 3];
const arr2 = [4, 5, 6];
const combined = [...arr1, ...arr2];

console.log(combined);  // [1, 2, 3, 4, 5, 6]
```





