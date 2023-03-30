# 1 - Descrição do Problema:
Dado um número inteiro positivo n, escreva um algoritmo que desenhe uma escada (staircase) com n degraus usando o caractere '#' (jogo da velha).

# Entrada:
Um número inteiro positivo n, onde 1 ≤ n ≤ 10.

# Saída:
Uma escada (staircase) com n degraus usando o caractere '#'.

# Exemplo de entrada:
```
n = 4
```

# Exemplo de saída:
```
   #
  ##
 ###
####
```
# Explicação:
Para n = 4, a escada tem quatro degraus e é desenhada usando o caractere '#'. A primeira linha tem três espaços em branco e um caractere '#', a segunda linha tem dois espaços em branco e dois caracteres '#' e assim por diante até a última linha, que tem quatro caracteres '#'.

---




# 2 - Descrição do Problema:

Dado um número inteiro positivo n, escreva um algoritmo que determine a soma de todos os números inteiros positivos menores ou iguais a n.

# Entrada:
Um número inteiro positivo n, onde 1 ≤ n ≤ 100.

# Saída:
A soma de todos os números inteiros positivos menores ou iguais a n.

# Exemplo de entrada:
```
n = 5
```

# Exemplo de saída:
```
A soma de todos os números inteiros positivos menores ou iguais a 5 é 15.
```

# Explicação:
A soma dos números inteiros positivos menores ou iguais a 5 é: 1 + 2 + 3 + 4 + 5 = 15.

---


# 3 - Descrição do Problema:

Dado um número inteiro positivo n, escreva um algoritmo que desenhe uma pirâmide (pyramid) com n andares usando o caractere '#' (jogo da velha).

# Entrada:
Um número inteiro positivo n, onde 1 ≤ n ≤ 10.

# Saída:
Uma pirâmide (pyramid) com n andares usando o caractere '#'.

# Exemplo de entrada:
```
n = 3
```

# Exemplo de saída:
```
  #
 ###
#####
```


# Explicação:
Para n = 3, a pirâmide tem três andares e é desenhada usando o caractere '#'. A primeira linha tem um espaço em branco e um caractere '#', a segunda linha tem um espaço em branco, dois caracteres '#' e um espaço em branco, e a terceira linha tem três caracteres '#'. Note que o número de caracteres '#' aumenta de 1 a cada linha e o número de espaços em branco diminui de 1 a cada linha.

---


# 4 - Descrição do Problema:
Dada uma matriz mat de tamanho m x n, escreva um algoritmo que calcule a soma de todos os elementos da matriz.

# Entrada:
Uma matriz mat de tamanho m x n, onde 1 ≤ m, n ≤ 1000 e -1000 ≤ mat[i][j] ≤ 1000.

# Saída:
A soma de todos os elementos da matriz.

# Exemplo de entrada:
```
[
  [1, 2, 3],
  [4, 5, 6],
  [7, 8, 9]
]
```

# Exemplo de saída:
```

A soma de todos os elementos da matriz é 45.
```

# Explicação:
A matriz mat tem tamanho 3 x 3 e contém os números de 1 a 9. A soma de todos os elementos da matriz é 1 + 2 + 3 + 4 + 5 + 6 + 7 + 8 + 9 = 45.

---

# 5 - Descrição do Problema:
Escreva um algoritmo que imprima os números de 1 a n, onde n é um número inteiro positivo fornecido como entrada. No entanto, para múltiplos de 3, imprima "Fizz" em vez do número e, para múltiplos de 5, imprima "Buzz". Para números que são múltiplos tanto de 3 quanto de 5, imprima "FizzBuzz".

# Entrada:
Um número inteiro positivo n, onde 1 ≤ n ≤ 100.

# Saída:
Uma lista dos números de 1 a n, substituindo múltiplos de 3 por "Fizz", múltiplos de 5 por "Buzz" e múltiplos de ambos por "FizzBuzz".

# Exemplo de entrada:
```
n = 15
```

# Exemplo de saída:
```

1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
```

# Explicação:
Para n = 15, o algoritmo imprime os números de 1 a 15. Os números 3, 6, 9 e 12 são múltiplos de 3, então são substituídos por "Fizz". Os números 5 e 10 são múltiplos de 5, então são substituídos por "Buzz". O número 15 é múltiplo tanto de 3 quanto de 5, então é substituído por "FizzBuzz".
