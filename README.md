# Aula de Orientação a Objetos com Python

## Bem-vindos, Alunos da Unisagrado!

Nesta aula, vamos mergulhar no fascinante mundo da Programação Orientada a Objetos (OOP) usando Python. Vamos explorar como OOP pode ser uma ferramenta poderosa para criar programas mais organizados, modulares e reutilizáveis.

---

### O que é Programação Orientada a Objetos?

OOP é um paradigma de programação baseado no conceito de "objetos", que podem conter dados e código: dados na forma de campos (também conhecidos como atributos ou propriedades) e código, na forma de procedimentos (métodos).

---

### Por que Python para OOP?

- **Simplicidade e Legibilidade:** Python é conhecido por sua sintaxe clara e legível.
- **Amplamente Utilizado:** Desde desenvolvimento web até ciência de dados, Python é usado em diversas áreas.
- **Grande Comunidade:** Uma vasta comunidade para suporte e recursos.

---

### Lição 1: Introdução à OOP

**Conceitos Chave:**
- Classes e Objetos
- Métodos e Atributos

**Exemplo Prático:**

```python
class Carro:
    def __init__(self, marca, modelo):
        self.marca = marca
        self.modelo = modelo

    def exibir_informacoes(self):
        print(f"Carro: {self.marca} {self.modelo}")

meu_carro = Carro("Toyota", "Corolla")
meu_carro.exibir_informacoes()
```
### Lição 2: Classes e Objetos

##Aprofunde-se em:

- Definindo Classes
- Criando Objetos
##Exemplo Prático:##

```python
class Pessoa:
    def __init__(self, nome, idade):
        self.nome = nome
        self.idade = idade

    def cumprimentar(self):
        return f"Olá, meu nome é {self.nome} e eu tenho {self.idade} anos."

pessoa1 = Pessoa("João", 30)
print(pessoa1.cumprimentar())
```

### Lição 3: Métodos e Atributos

##Explore:

- Interagindo com Atributos
- Definindo Métodos
##Exemplo Prático:##

```python
class ContaBancaria:
    def __init__(self, titular, saldo_inicial=0):
        self.titular = titular
        self.saldo = saldo_inicial

    def depositar(self, quantia):
        self.saldo += quantia
        return f"Depósito de {quantia} realizado com sucesso!"

    def sacar(self, quantia):
        if quantia > self.saldo:
            return "Saldo insuficiente!"
        self.saldo -= quantia
        return f"Saque de {quantia} realizado com sucesso!"

conta = ContaBancaria("Maria", 1000)
print(conta.depositar(500))
print(conta.sacar(200))
```

## Próximos Passos
### Pratique os conceitos aprendidos e comece a aplicá-los em seus próprios projetos. Lembre-se, a prática leva à perfeição!

- Feliz Aprendizado! 🚀
