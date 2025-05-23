# Orientação a Objetos em C#

A orientação a objetos (OO) é um paradigma de programação que organiza o código em torno de objetos, que são instâncias de classes. Em C#, a OO é amplamente utilizada para criar sistemas modulares, reutilizáveis e fáceis de manter.

## 1. Classes e Objetos

### O que são Classes?
Classes são modelos ou "blueprints" que definem as propriedades e comportamentos de um objeto.

```csharp
public class Pessoa
{
    public string Nome { get; set; }
    public int Idade { get; set; }

    public void Apresentar()
    {
        Console.WriteLine($"Olá, meu nome é {Nome} e tenho {Idade} anos.");
    }
}
```

### O que são Objetos?
Objetos são instâncias de uma classe.

```csharp
Pessoa pessoa = new Pessoa();
pessoa.Nome = "João";
pessoa.Idade = 30;
pessoa.Apresentar();
```

## 2. Encapsulamento

Encapsulamento é o princípio de esconder os detalhes internos de uma classe e expor apenas o necessário.

```csharp
public class ContaBancaria
{
    private decimal saldo;

    public void Depositar(decimal valor)
    {
        if (valor > 0)
            saldo += valor;
    }

    public decimal ObterSaldo()
    {
        return saldo;
    }
}
```

### Exemplo de Uso:
```csharp
ContaBancaria conta = new ContaBancaria();
conta.Depositar(100);
Console.WriteLine($"Saldo: {conta.ObterSaldo()}");
```

## 3. Herança

Herança permite que uma classe herde membros de outra classe.

```csharp
public class Animal
{
    public void Comer()
    {
        Console.WriteLine("O animal está comendo.");
    }
}

public class Cachorro : Animal
{
    public void Latir()
    {
        Console.WriteLine("O cachorro está latindo.");
    }
}
```

### Exemplo de Uso:
```csharp
Cachorro cachorro = new Cachorro();
cachorro.Comer();
cachorro.Latir();
```

## 4. Polimorfismo

Polimorfismo permite que métodos tenham comportamentos diferentes dependendo do contexto.

### Exemplo com Sobrescrita:
```csharp
public class Forma
{
    public virtual void Desenhar()
    {
        Console.WriteLine("Desenhando uma forma.");
    }
}

public class Circulo : Forma
{
    public override void Desenhar()
    {
        Console.WriteLine("Desenhando um círculo.");
    }
}
```

### Exemplo de Uso:
```csharp
Forma forma = new Circulo();
forma.Desenhar();
```

## 5. Abstração

Abstração é o processo de expor apenas os detalhes essenciais de um objeto.

```csharp
public abstract class Veiculo
{
    public abstract void Mover();
}

public class Carro : Veiculo
{
    public override void Mover()
    {
        Console.WriteLine("O carro está se movendo.");
    }
}
```

### Exemplo de Uso:
```csharp
Veiculo veiculo = new Carro();
veiculo.Mover();
```

## Conclusão

A orientação a objetos em C# é uma poderosa ferramenta para criar sistemas robustos e escaláveis. Compreender conceitos como classes, encapsulamento, herança, polimorfismo e abstração é essencial para desenvolver aplicações modernas e bem estruturadas.