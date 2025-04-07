# 🧪 Testes de Python 

## 🎯 Objetivo

Avaliar a familiaridade do desenvolvedor com os principais fundamentos da linguagem Python, incluindo:

- Sintaxe básica
- Manipulação de strings e listas
- Estruturas de decisão (`if/else`)
- Laços de repetição (`for`, `while`)
- Definição de funções
- Lógica de programação

---

## ✅ Instruções

1. Resolva cada exercício criando uma função conforme o enunciado.
2. Use apenas **Python puro** (sem bibliotecas externas).
3. Sinta-se à vontade para testar suas funções com `print()` ou `assert`.
4. Escreva um código claro, legível e bem estruturado.

---

## 🧪 Teste 1 – Verificador de Palíndromos

**Função esperada:** `eh_palindromo(texto)`

**Descrição:**  
Verifica se uma string é um palíndromo, ignorando espaços e diferenças entre maiúsculas/minúsculas.

**Exemplo:**
```python
eh_palindromo("Ame a ema")  # True
eh_palindromo("Python")     # False


## 🧪 Teste 2 – Contador de Vogais

**Função esperada:** `contar_vogais(frase)`

### 📝 Descrição:
Crie uma função que receba uma string e retorne o número de vogais (`a`, `e`, `i`, `o`, `u`) contidas nela, **ignorando maiúsculas e minúsculas**.

### 🔧 Requisitos:
- Ignorar letras maiúsculas.
- Considerar apenas as vogais `a`, `e`, `i`, `o`, `u`.
- Usar laço de repetição e estrutura condicional.

### 💡 Exemplo de uso:
```python
contar_vogais("Brasil é incrível")  # 6
contar_vogais("Python")              # 1

## 🧪 Teste 3 – Soma de Números Pares

**Função esperada:** `soma_pares(lista)`

### 📝 Descrição:
Crie uma função que receba uma **lista de números inteiros** e retorne a **soma apenas dos números pares**.

### 🔧 Requisitos:
- Usar laço de repetição (`for` ou `while`).
- Verificar se o número é par usando a condição: `numero % 2 == 0`.
- Somar apenas os valores pares da lista.
- Retornar o total da soma.

### 💡 Exemplo de uso:
```python
soma_pares([1, 2, 3, 4, 5, 6])   # 12
soma_pares([10, 15, 22, 33])     # 32
soma_pares([])                   # 0
soma_pares([1, 3, 5, 7])         # 0


## 🧪 Teste 4 – FizzBuzz

**Função esperada:** `fizzbuzz()`

### 📝 Descrição:
Implemente a lógica clássica do FizzBuzz, imprimindo os números de 1 a 50 com as seguintes condições:

- Para múltiplos de **3**, imprimir `"Fizz"`.
- Para múltiplos de **5**, imprimir `"Buzz"`.
- Para múltiplos de **3 e 5**, imprimir `"FizzBuzz"`.
- Caso contrário, imprimir o número normalmente.

### 🔧 Requisitos:
- Usar um laço `for` que percorra os números de 1 até 50.
- Utilizar estruturas condicionais (`if`, `elif`, `else`) para tratar os diferentes casos.
- Imprimir os resultados diretamente no terminal com `print()`.

### 💡 Exemplo de saída:
1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 FizzBuzz ...

## 🧪 Teste 5 – Ordenação Manual (Bubble Sort)

**Função esperada:** `ordenar(lista)`

### 📝 Descrição:
Crie uma função que receba uma **lista de números inteiros** e a retorne em **ordem crescente**, **sem utilizar as funções `sort()` ou `sorted()` do Python**.

Este exercício tem como objetivo testar a capacidade de implementar lógica de ordenação manual, utilizando um algoritmo simples como o **Bubble Sort**.

### 🔧 Requisitos:
- Implementar um algoritmo de ordenação (preferencialmente Bubble Sort).
- Não utilizar funções prontas de ordenação.
- Retornar a **lista ordenada**.
- Tratar listas vazias ou com um único elemento.

### 💡 Exemplo de uso:
```python
ordenar([3, 1, 4, 2])        # [1, 2, 3, 4]
ordenar([10, 5, 2, 8, 7])    # [2, 5, 7, 8, 10]
ordenar([])                  # []
ordenar([42])                # [42]


## Entrega:

- Faça um git clone desse repositorio para a realização dos testes
- Os testes devem ser entregues via Push request nesse mesmo repositorio até o dia 14/04
- Organize os diretorios de forma clara
- Utilize todo o seu conhecimento em programacao, clean code, arquitetura, git e logica de programacao
- Sera avaliado seu codigo em python, suas habilidades de git, clean code e arquitetura
- Referencia: https://www.python.org/
