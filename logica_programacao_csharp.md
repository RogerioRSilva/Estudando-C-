# Lógica de Programação em C#

## Introdução
Lógica de programação é a base para o desenvolvimento de qualquer software. Ela envolve o uso de raciocínio lógico para resolver problemas e criar algoritmos. Neste documento, exploraremos os principais conceitos de lógica de programação utilizando a linguagem C#.

---

## 1. Variáveis e Tipos de Dados
### O que são variáveis?
Variáveis são espaços na memória do computador usados para armazenar dados.

### Exemplos em C#:
```csharp
int idade = 25; // Inteiro
double altura = 1.75; // Decimal
char inicial = 'A'; // Caractere
string nome = "João"; // Texto
bool ativo = true; // Booleano
```

---

## 2. Estruturas Condicionais
### O que são?
Permitem executar diferentes blocos de código dependendo de uma condição.

### Exemplos em C#:
```csharp
int idade = 18;

if (idade >= 18)
{
    Console.WriteLine("Você é maior de idade.");
}
else
{
    Console.WriteLine("Você é menor de idade.");
}
```

---

## 3. Estruturas de Repetição
### O que são?
Permitem executar um bloco de código várias vezes.

### Exemplos em C#:
#### `for`:
```csharp
for (int i = 0; i < 5; i++)
{
    Console.WriteLine($"Contagem: {i}");
}
```

#### `while`:
```csharp
int contador = 0;

while (contador < 5)
{
    Console.WriteLine($"Contagem: {contador}");
    contador++;
}
```

#### `do-while`:
```csharp
int contador = 0;

do
{
    Console.WriteLine($"Contagem: {contador}");
    contador++;
} while (contador < 5);
```

---

## 4. Arrays e Coleções
### O que são?
Estruturas que armazenam múltiplos valores.

### Exemplos em C#:
#### Arrays:
```csharp
int[] numeros = { 1, 2, 3, 4, 5 };
Console.WriteLine(numeros[0]); // Saída: 1
```

#### Listas:
```csharp
List<string> nomes = new List<string> { "Ana", "João", "Maria" };
nomes.Add("Carlos");
Console.WriteLine(nomes[3]); // Saída: Carlos
```

---

## 5. Funções e Métodos
### O que são?
Blocos de código reutilizáveis que realizam uma tarefa específica.

### Exemplos em C#:
```csharp
int Somar(int a, int b)
{
    return a + b;
}

int resultado = Somar(5, 3);
Console.WriteLine(resultado); // Saída: 8
```

---

## 6. Estruturas de Dados
### Exemplos:
#### Dicionários:
```csharp
Dictionary<string, int> estoque = new Dictionary<string, int>
{
    { "Maçã", 10 },
    { "Banana", 20 }
};
Console.WriteLine(estoque["Maçã"]); // Saída: 10
```

---

## 7. Orientação a Objetos (OOP)
### Conceitos:
- **Classe**: Define um tipo de objeto.
- **Objeto**: Instância de uma classe.
- **Encapsulamento**: Controle de acesso aos dados.
- **Herança**: Reutilização de código.
- **Polimorfismo**: Comportamentos diferentes para o mesmo método.

### Exemplo em C#:
```csharp
class Pessoa
{
    public string Nome { get; set; }
    public int Idade { get; set; }

    public void Apresentar()
    {
        Console.WriteLine($"Olá, meu nome é {Nome} e tenho {Idade} anos.");
    }
}

Pessoa pessoa = new Pessoa { Nome = "João", Idade = 30 };
pessoa.Apresentar(); // Saída: Olá, meu nome é João e tenho 30 anos.
```

---

## 8. Tratamento de Exceções
### O que é?
Permite lidar com erros de forma controlada.

### Exemplo em C#:
```csharp
try
{
    int numero = int.Parse("abc");
}
catch (FormatException)
{
    Console.WriteLine("Erro: Formato inválido.");
}
finally
{
    Console.WriteLine("Finalizando operação.");
}
```

---

## 9. Recursividade
### O que é?
Uma função que chama a si mesma.

### Exemplo em C#:
```csharp
int Fatorial(int n)
{
    if (n == 0) return 1;
    return n * Fatorial(n - 1);
}

Console.WriteLine(Fatorial(5)); // Saída: 120
```

---

## Conclusão
A lógica de programação é essencial para o desenvolvimento de software. Com os conceitos apresentados, você pode começar a criar soluções eficientes utilizando C#. Pratique bastante para consolidar o aprendizado!