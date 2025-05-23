# Exercícios de Programação em C#

## Exercício 1: Concatenação de Strings  
**Descrição:** Crie um programa que solicite ao usuário seu primeiro nome e sobrenome, e exiba o nome completo concatenado.  
**Exemplo de saída:**  
```
Digite seu primeiro nome: João  
Digite seu sobrenome: Silva  
Seu nome completo é: João Silva  
```  
**Explicação:** O programa deve juntar as duas strings e exibir o resultado.

---

## Exercício 2: Interpolação de Strings  
**Descrição:** Desenvolva um programa que solicite o nome e a idade do usuário, e exiba uma mensagem utilizando interpolação de strings.  
**Exemplo de saída:**  
```
Digite seu nome: Ana  
Digite sua idade: 30  
Olá, Ana! Você tem 30 anos.  
```  
**Explicação:** O programa deve usar interpolação para formatar a mensagem.

---

## Exercício 3: Operadores Aritméticos - Soma  
**Descrição:** Crie um programa que solicite dois números inteiros e exiba a soma deles.  
**Exemplo de saída:**  
```
Digite o primeiro número: 10  
Digite o segundo número: 20  
A soma dos números é: 30  
```  
**Explicação:** O programa deve somar os dois números e exibir o resultado.

---

## Exercício 4: Operadores Aritméticos - Divisão  
**Descrição:** Desenvolva um programa que peça dois números e exiba o resultado da divisão do primeiro pelo segundo.  
**Exemplo de saída:**  
```
Digite o primeiro número: 50  
Digite o segundo número: 5  
O resultado da divisão é: 10  
```  
**Explicação:** O programa deve dividir os números e exibir o resultado.

---

## Exercício 5: Estrutura de Decisão - Verificação de Maioridade  
**Descrição:** Crie um programa que solicite a idade do usuário e informe se ele é maior de idade ou não.  
**Exemplo de saída:**  
```
Digite sua idade: 18  
Você é maior de idade.  
```  
**Explicação:** O programa deve usar uma estrutura `if-else` para verificar a idade.

---

## Exercício 6: Estrutura de Decisão - Classificação de Nota  
**Descrição:** Desenvolva um programa que peça uma nota de 0 a 10 e exiba uma mensagem com base na classificação:  
- Nota >= 7: "Aprovado"  
- Nota >= 5 e < 7: "Recuperação"  
- Nota < 5: "Reprovado"  
**Exemplo de saída:**  
```
Digite sua nota: 6  
Você está em recuperação.  
```  
**Explicação:** O programa deve usar `if-else` para classificar a nota.

---

## Exercício 7: Estrutura de Decisão - Verificação de Dia da Semana  
**Descrição:** Crie um programa que solicite um número de 1 a 7 e exiba o dia da semana correspondente usando `switch`.  
**Exemplo de saída:**  
```
Digite um número de 1 a 7: 3  
O dia da semana é: Quarta-feira.  
```  
**Explicação:** O programa deve usar `switch` para mapear o número ao dia.

---

## Exercício 8: Contagem de Caracteres em uma String  
**Descrição:** Desenvolva um programa que receba uma frase e exiba a quantidade de caracteres que ela contém.  
**Exemplo de saída:**  
```
Digite uma frase: Olá, mundo!  
A frase contém 12 caracteres.  
```  
**Explicação:** O programa deve contar os caracteres da string. Não é necessário utilizar uma estrutura de repetição, pois a contagem pode ser feita diretamente utilizando métodos disponíveis na linguagem, como `Length` em C#.

---

## Exercício 9: Verificação de Substring  
**Descrição:** Crie um programa que solicite uma frase e uma palavra, e verifique se a palavra está contida na frase.  
**Exemplo de saída:**  
```
Digite uma frase: Eu gosto de programação.  
Digite uma palavra: programação  
A palavra "programação" está na frase.  
```  
**Explicação:** Não é necessário utilizar uma estrutura de repetição, pois a verificação pode ser feita diretamente utilizando métodos disponíveis na linguagem, como `Contains` em C#.

---

## Exercício 10: Operadores Aritméticos e Decisão  
**Descrição:** Desenvolva um programa que peça dois números e uma operação (soma, subtração, multiplicação ou divisão) e exiba o resultado.  
**Exemplo de saída:**  
```
Digite o primeiro número: 8  
Digite o segundo número: 2  
Escolha uma operação (soma, subtração, multiplicação, divisão): multiplicação  
O resultado da multiplicação é: 16  
```  
**Explicação:** O programa deve usar `switch` para realizar a operação escolhida.


## Exercício 11: Estrutura de Repetição - Tabuada com `for`  
**Descrição:** Crie um programa que exiba a tabuada de um número informado pelo usuário utilizando a estrutura `for`.  
**Exemplo de saída:**  
```
Digite um número: 5  
5 x 1 = 5  
5 x 2 = 10  
...  
5 x 10 = 50  
```  
**Explicação:** O programa deve usar um laço `for` para calcular e exibir a tabuada.

---

## Exercício 12: Estrutura de Repetição - Soma de Números com `while`  
**Descrição:** Desenvolva um programa que solicite números ao usuário até que ele digite 0. O programa deve exibir a soma de todos os números digitados.  
**Exemplo de saída:**  
```
Digite um número (0 para sair): 10  
Digite um número (0 para sair): 20  
Digite um número (0 para sair): 0  
A soma dos números é: 30  
```  
**Explicação:** O programa deve usar um laço `while` para somar os números.

---

## Exercício 13: Estrutura de Repetição - Validação de Entrada com `do-while`  
**Descrição:** Crie um programa que solicite ao usuário um número entre 1 e 10. Caso o número esteja fora do intervalo, solicite novamente até que um número válido seja informado.  
**Exemplo de saída:**  
```
Digite um número entre 1 e 10: 15  
Número inválido. Tente novamente.  
Digite um número entre 1 e 10: 7  
Número válido: 7  
```  
**Explicação:** O programa deve usar um laço `do-while` para validar a entrada.

---

## Exercício 14: Estrutura de Repetição - Contagem Regressiva com `for`  
**Descrição:** Desenvolva um programa que exiba uma contagem regressiva de 10 a 0 utilizando a estrutura `for`.  
**Exemplo de saída:**  
```
10  
9  
8  
...  
0  
```  
**Explicação:** O programa deve usar um laço `for` para exibir a contagem.

---

## Exercício 15: Estrutura de Repetição - Fatorial com `while`  
**Descrição:** Crie um programa que calcule o fatorial de um número informado pelo usuário utilizando a estrutura `while`.  
**Exemplo de saída:**  
```
Digite um número: 5  
O fatorial de 5 é: 120  
```  
**Explicação:** O programa deve usar um laço `while` para calcular o fatorial.

---

## Exercício 16: Estrutura de Repetição - Números Ímpares com `for`  
**Descrição:** Desenvolva um programa que exiba todos os números ímpares de 1 a 20 utilizando a estrutura `for`.  
**Exemplo de saída:**  
```
1  
3  
5  
...  
19  
```  
**Explicação:** O programa deve usar um laço `for` para exibir os números ímpares.

---

## Exercício 17: Estrutura de Repetição - Média de Números com `do-while`  
**Descrição:** Crie um programa que solicite números ao usuário até que ele digite -1. O programa deve calcular e exibir a média dos números digitados.  
**Exemplo de saída:**  
```
Digite um número (-1 para sair): 10  
Digite um número (-1 para sair): 20  
Digite um número (-1 para sair): -1  
A média dos números é: 15  
```  
**Explicação:** O programa deve usar um laço `do-while` para calcular a média.

---

## Exercício 18: Estrutura de Repetição - Sequência de Fibonacci com `for`  
**Descrição:** Desenvolva um programa que exiba os primeiros N números da sequência de Fibonacci, onde N é informado pelo usuário.  
**Exemplo de saída:**  
```
Digite a quantidade de números da sequência: 5  
0  
1  
1  
2  
3  
```  
**Explicação:** O programa deve usar um laço `for` para calcular a sequência.

---

## Exercício 19: Estrutura de Repetição - Números Pares com `while`  
**Descrição:** Crie um programa que exiba todos os números pares de 1 a 50 utilizando a estrutura `while`.  
**Exemplo de saída:**  
```
2  
4  
6  
...  
50  
```  
**Explicação:** O programa deve usar um laço `while` para exibir os números pares.

---

## Exercício 20: Estrutura de Repetição - Soma de Dígitos com `do-while`  
**Descrição:** Desenvolva um programa que solicite um número inteiro positivo e calcule a soma de seus dígitos utilizando a estrutura `do-while`.  
**Exemplo de saída:**  
```
Digite um número: 123  
A soma dos dígitos é: 6  
```  
**Explicação:** O programa deve usar um laço `do-while` para somar os dígitos do número.

---

## Exercício 21: Soma de Elementos de um Array  
**Descrição:** Crie um programa que solicite 5 números ao usuário, armazene-os em um array e exiba a soma de todos os elementos.  
**Exemplo de saída:**  
```
Digite o número 1: 10  
Digite o número 2: 20  
Digite o número 3: 30  
Digite o número 4: 40  
Digite o número 5: 50  
A soma dos números é: 150  
```  
**Explicação:** O programa deve somar os elementos do array e exibir o resultado.

---

## Exercício 22: Maior e Menor Elemento de um Array  
**Descrição:** Desenvolva um programa que solicite 5 números ao usuário, armazene-os em um array e exiba o maior e o menor número.  
**Exemplo de saída:**  
```
Digite o número 1: 5  
Digite o número 2: 10  
Digite o número 3: 3  
Digite o número 4: 8  
Digite o número 5: 1  
O maior número é: 10  
O menor número é: 1  
```  
**Explicação:** O programa deve encontrar o maior e o menor número no array.

---

## Exercício 23: Média dos Elementos de um Array  
**Descrição:** Crie um programa que solicite 5 números ao usuário, armazene-os em um array e exiba a média dos números.  
**Exemplo de saída:**  
```
Digite o número 1: 10  
Digite o número 2: 20  
Digite o número 3: 30  
Digite o número 4: 40  
Digite o número 5: 50  
A média dos números é: 30  
```  
**Explicação:** O programa deve calcular a média dos elementos do array.

---

## Exercício 24: Contagem de Elementos em uma Lista  
**Descrição:** Desenvolva um programa que solicite ao usuário uma lista de palavras separadas por vírgulas e exiba a quantidade de palavras na lista.  
**Exemplo de saída:**  
```
Digite palavras separadas por vírgulas: maçã, banana, laranja  
A lista contém 3 palavras.  
```  
**Explicação:** O programa deve contar os elementos da lista.

---

## Exercício 25: Verificação de Elemento em uma Lista  
**Descrição:** Crie um programa que solicite ao usuário uma lista de números separados por vírgulas e um número. Verifique se o número está na lista.  
**Exemplo de saída:**  
```
Digite números separados por vírgulas: 1,2,3,4,5  
Digite um número: 3  
O número 3 está na lista.  
```  
**Explicação:** O programa deve verificar se o número informado está na lista.

---

## Exercício 26: Ordenação de um Array  
**Descrição:** Desenvolva um programa que solicite 5 números ao usuário, armazene-os em um array e exiba os números em ordem crescente.  
**Exemplo de saída:**  
```
Digite o número 1: 5  
Digite o número 2: 2  
Digite o número 3: 8  
Digite o número 4: 1  
Digite o número 5: 4  
Os números em ordem crescente são: 1, 2, 4, 5, 8  
```  
**Explicação:** O programa deve ordenar os elementos do array.

---

## Exercício 27: Reversão de um Array  
**Descrição:** Crie um programa que solicite 5 números ao usuário, armazene-os em um array e exiba os números na ordem inversa.  
**Exemplo de saída:**  
```
Digite o número 1: 10  
Digite o número 2: 20  
Digite o número 3: 30  
Digite o número 4: 40  
Digite o número 5: 50  
Os números na ordem inversa são: 50, 40, 30, 20, 10  
```  
**Explicação:** O programa deve inverter a ordem dos elementos do array.

---

## Exercício 28: Números Pares em um Array  
**Descrição:** Desenvolva um programa que solicite 10 números ao usuário, armazene-os em um array e exiba apenas os números pares.  
**Exemplo de saída:**  
```
Digite o número 1: 1  
Digite o número 2: 2  
Digite o número 3: 3  
Digite o número 4: 4  
Digite o número 5: 5  
Digite o número 6: 6  
Digite o número 7: 7  
Digite o número 8: 8  
Digite o número 9: 9  
Digite o número 10: 10  
Os números pares são: 2, 4, 6, 8, 10  
```  
**Explicação:** O programa deve filtrar os números pares do array.

---

## Exercício 29: Concatenar Listas  
**Descrição:** Crie um programa que solicite duas listas de números separados por vírgulas e exiba a concatenação das duas listas.  
**Exemplo de saída:**  
```
Digite a primeira lista: 1,2,3  
Digite a segunda lista: 4,5,6  
A lista concatenada é: 1,2,3,4,5,6  
```  
**Explicação:** O programa deve unir as duas listas em uma única lista.

---

## Exercício 30: Remoção de Duplicados em uma Lista  
**Descrição:** Desenvolva um programa que solicite ao usuário uma lista de números separados por vírgulas e exiba a lista sem números duplicados.  
**Exemplo de saída:**  
```
Digite números separados por vírgulas: 1,2,2,3,4,4,5  
A lista sem duplicados é: 1,2,3,4,5  
```  
**Explicação:** O programa deve remover os números duplicados da lista.

---

## Exercício 31: Método para Calcular a Soma  
**Descrição:** Crie um método que receba dois números como parâmetros e retorne a soma deles.  
**Exemplo de saída:**  
```
A soma de 10 e 20 é: 30  
```  
**Explicação:** O método deve realizar a soma e retornar o resultado.

---

## Exercício 32: Método para Verificar Número Par  
**Descrição:** Desenvolva um método que receba um número como parâmetro e retorne `true` se o número for par, ou `false` caso contrário.  
**Exemplo de saída:**  
```
O número 4 é par: True  
```  
**Explicação:** O método deve verificar se o número é divisível por 2.

---

## Exercício 33: Método para Calcular Fatorial  
**Descrição:** Crie um método que receba um número como parâmetro e retorne o fatorial desse número.  
**Exemplo de saída:**  
```
O fatorial de 5 é: 120  
```  
**Explicação:** O método deve calcular o fatorial utilizando um laço de repetição.

---

## Exercício 34: Método para Inverter uma String  
**Descrição:** Desenvolva um método que receba uma string como parâmetro e retorne a string invertida.  
**Exemplo de saída:**  
```
A string invertida de "casa" é: "asac"  
```  
**Explicação:** O método deve inverter a ordem dos caracteres da string.

---

## Exercício 35: Método para Calcular a Média de um Array  
**Descrição:** Crie um método que receba um array de números como parâmetro e retorne a média dos números.  
**Exemplo de saída:**  
```
A média dos números [10, 20, 30] é: 20  
```  
**Explicação:** O método deve somar os elementos do array e dividir pelo total de elementos.

---

## Exercício 36: Método para Verificar Palíndromo  
**Descrição:** Desenvolva um método que receba uma string como parâmetro e retorne `true` se a string for um palíndromo, ou `false` caso contrário.  
**Exemplo de saída:**  
```
A palavra "arara" é um palíndromo: True  
```  
**Explicação:** O método deve verificar se a string é igual à sua versão invertida.

---

## Exercício 37: Método para Contar Vogais  
**Descrição:** Crie um método que receba uma string como parâmetro e retorne a quantidade de vogais na string.  
**Exemplo de saída:**  
```
A string "programação" contém 5 vogais.  
```  
**Explicação:** O método deve contar as letras `a`, `e`, `i`, `o`, `u` na string.

---

## Exercício 38: Método para Encontrar o Maior Número  
**Descrição:** Desenvolva um método que receba um array de números como parâmetro e retorne o maior número.  
**Exemplo de saída:**  
```
O maior número no array [5, 10, 3] é: 10  
```  
**Explicação:** O método deve percorrer o array e encontrar o maior valor.

---

## Exercício 39: Método para Ordenar um Array  
**Descrição:** Crie um método que receba um array de números como parâmetro e retorne o array ordenado em ordem crescente.  
**Exemplo de saída:**  
```
O array [5, 2, 8, 1] ordenado é: [1, 2, 5, 8]  
```  
**Explicação:** O método deve ordenar os elementos do array.

---

## Exercício 40: Método para Contar Palavras em uma Frase  
**Descrição:** Desenvolva um método que receba uma frase como parâmetro e retorne a quantidade de palavras na frase.  
**Exemplo de saída:**  
```
A frase "Eu gosto de C#" contém 4 palavras.  
```  
**Explicação:** O método deve dividir a frase em palavras e contar o total.

---

## Exercício 41: Classe para Representar um Retângulo  
**Descrição:** Crie uma classe `Retangulo` com propriedades `Largura` e `Altura`. Adicione um método para calcular a área do retângulo.  
**Exemplo de saída:**  
```
A área do retângulo com largura 5 e altura 10 é: 50  
```  

---

## Exercício 42: Classe para Representar um Círculo  
**Descrição:** Desenvolva uma classe `Circulo` com a propriedade `Raio`. Adicione um método para calcular a área do círculo.  
**Exemplo de saída:**  
```
A área do círculo com raio 7 é: 153.94  
```  

---

## Exercício 43: Classe para Representar um Funcionário  
**Descrição:** Crie uma classe `Funcionario` com propriedades `Nome`, `Cargo` e `Salario`. Adicione um método para exibir as informações do funcionário.  
**Exemplo de saída:**  
```
Funcionário: João  
Cargo: Desenvolvedor  
Salário: 5000  
```  

---

## Exercício 44: Classe para Representar um Carro  
**Descrição:** Desenvolva uma classe `Carro` com propriedades `Marca`, `Modelo` e `Ano`. Adicione um método para exibir os detalhes do carro.  
**Exemplo de saída:**  
```
Carro: Toyota Corolla, Ano: 2020  
```  

---

## Exercício 45: Classe para Representar um Aluno  
**Descrição:** Crie uma classe `Aluno` com propriedades `Nome` e `Notas` (array de notas). Adicione um método para calcular a média das notas.  
**Exemplo de saída:**  
```
Aluno: Ana  
Média das notas: 8.5  
```  

---

## Exercício 46: Classe para Representar uma Conta Bancária  
**Descrição:** Desenvolva uma classe `ContaBancaria` com propriedades `Numero`, `Titular` e `Saldo`. Adicione métodos para `Depositar` e `Sacar`.  
**Exemplo de saída:**  
```
Saldo inicial: 1000  
Depósito: 500  
Saque: 300  
Saldo final: 1200  
```  

---

## Exercício 47: Classe para Representar um Produto  
**Descrição:** Crie uma classe `Produto` com propriedades `Nome`, `Preco` e `Quantidade`. Adicione um método para calcular o valor total em estoque.  
**Exemplo de saída:**  
```
Produto: Notebook  
Preço: 3000  
Quantidade: 5  
Valor total em estoque: 15000  
```  

---

## Exercício 48: Classe para Representar um Livro  
**Descrição:** Desenvolva uma classe `Livro` com propriedades `Titulo`, `Autor` e `Ano`. Adicione um método para exibir os detalhes do livro.  
**Exemplo de saída:**  
```
Livro: O Senhor dos Anéis  
Autor: J.R.R. Tolkien  
Ano: 1954  
```  

---

## Exercício 49: Classe para Representar um Pedido  
**Descrição:** Crie uma classe `Pedido` com propriedades `Numero`, `Cliente` e `Itens` (lista de produtos). Adicione um método para calcular o valor total do pedido.  
**Exemplo de saída:**  
```
Pedido: 123  
Cliente: Maria  
Valor total: 250.50  
```  

---

## Exercício 50: Classe para Representar um Animal  
**Descrição:** Desenvolva uma classe `Animal` com propriedades `Nome` e `Especie`. Adicione um método para exibir as informações do animal.  
**Exemplo de saída:**  
```
Animal: Rex  
Espécie: Cachorro  
```  
