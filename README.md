# Desafio de Python: Calculadora Simples

Neste desafio, você irá criar uma calculadora simples que pode realizar as quatro operações matemáticas básicas: adição, subtração, multiplicação e divisão.

## Objetivo
Criar uma função em Python que pede ao usuário dois números e a operação desejada, então realiza o cálculo e exibe o resultado.

## Passo a passo

### Passo 1: Criando a função
Crie uma função chamada `calculadora()` que vai receber três parâmetros: dois números e a operação matemática.

```python
def calculadora(numero1, numero2, operacao):
    # Aqui você vai implementar a lógica para as operações matemáticas
```

### Passo 2: Receber os valores do usuário
Agora que a função está pronta, precisamos pegar os valores de entrada do usuário. Use a função \`input()\` para isso.

```python
numero1 = float(input("Digite o primeiro número: "))
numero2 = float(input("Digite o segundo número: "))
operacao = input("Digite a operação (+, -, *, /): ")
```

### Passo 3: Chamar a função e exibir o resultado
Agora, com os valores capturados, podemos chamar a função \`calculadora()\` e exibir o resultado.

```python
resultado = calculadora(numero1, numero2, operacao)
print("O resultado é:", resultado)
```

## Dicas:

1. **Validar o Input:** Verifique se o usuário está inserindo números válidos e uma operação válida.
2. **Divisão por Zero:** Certifique-se de que o segundo número não seja zero ao realizar divisões.
3. **Looping:** Para melhorar a calculadora, você pode colocá-la dentro de um loop para que o usuário possa continuar realizando cálculos sem reiniciar o programa.

Boa sorte!

# Desafio de Python 2: Criando uma Classe para Controle de Conta Bancária

Neste desafio, você irá criar uma classe chamada `ContaBancaria` que simula operações básicas de uma conta bancária, como depósito, saque e consulta de saldo.

## Objetivo
Desenvolver uma classe em Python que representa uma conta bancária com métodos para manipular o saldo.

## Passo a passo

### Passo 1: Definir a classe
Crie uma classe chamada `ContaBancaria` com um atributo `saldo`, que será inicializado com zero.

```python
class ContaBancaria:
    def __init__(self):
        # Inicialize o saldo com zero
```

### Passo 2: Criar o método de depósito
Adicione um método \`depositar(self, valor)\` à classe, que deve adicionar o valor passado ao saldo da conta.

```python
    def depositar(self, valor):
        # Lógica para adicionar o valor ao saldo
```

### Passo 3: Criar o método de saque
Crie um método `sacar(self, valor)` que subtraia o valor do saldo, se houver saldo suficiente. Caso contrário, exiba uma mensagem de erro.

```python
    def sacar(self, valor):
        # Lógica para verificar se o saldo é suficiente e subtrair o valor
```

### Passo 4: Método para exibir o saldo
Adicione um método `exibir_saldo(self)` que imprime o saldo atual da conta.

```python
    def exibir_saldo(self):
        # Lógica para exibir o saldo atual
```

## Dicas:

1. **Validação de Entrada:** Certifique-se de que os valores de depósito e saque sejam positivos.
2. **Saque com Saldo Insuficiente:** Verifique se o saldo é suficiente antes de permitir um saque.
3. **Melhorias:** Você pode estender a classe para incluir funcionalidades como taxa de transação ou limites de saque.

Boa sorte!

