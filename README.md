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
