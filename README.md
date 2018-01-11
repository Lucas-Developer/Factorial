# Factorial
O conceito de fatorial é muito utilizado no estudo de arranjos e permutações, a fim de facilitar os cálculos. A ideia é bastante simples e de fácil compreensão.

O fatorial de um número inteiro m não negativo, é indicado por m! (lê-se “m fatorial”) e é definido pela relação:

m!=m⋅(m−1)⋅(m−2)⋅(m−3)...3⋅2⋅1, para m ≥ 2.

Algumas definições são:

    1! = 1
    0! = 1

Exemplos:

    3! = 3 . 2 . 1 = 6
    4! = 4 . 3 . 2 . 1 = 24
    6! = 6 . 5 . 4 . 3 . 2 . 1 = 720

Veja que o cálculo do fatorial se torna trabalhoso a medida que m aumenta, veja:

    10! = 10 . 9 . 8 . 7 . 6 . 5 . 4 . 3 . 2 . 1 = 3.628.800

Assim, podemos simplificar alguns cálculos, usando o artifício de não calcular totalmente o fatorial, mas sim uma parte dele:

(n+1)! = (n+1) . n . (n-1) . (n-2) ... 3 . 2 . 1 = (n+1) . n!

Por exemplo:

10! = 10 . 9 . 8 . 7!

FONTE: InfoEscola
