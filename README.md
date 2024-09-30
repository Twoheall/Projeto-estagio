# Projeto-estagio
Este projeto contém soluções para exercícios de programação em Python
1- 
def fibonacci(n):
    a, b = 0, 1
    fibonacci_sequence = [a, b]
    
    while b < n:
        a, b = b, a + b
        fibonacci_sequence.append(b)

    if n in fibonacci_sequence:
        return f"O número {n} pertence à sequência de Fibonacci."
    else:
        return f"O número {n} não pertence à sequência de Fibonacci."
numero = int(input("Informe um número: "))
print(fibonacci(numero))
2-
def contar_letra_a(string):
    quantidade = string.lower().count('a')
    return f"A letra 'a' aparece {quantidade} vezes na string."
texto = input("Informe uma string: ")
print(contar_letra_a(texto))
3-
int INDICE = 12, SOMA = 0, K = 1;
while K < INDICE {
    K = K + 1;
    SOMA = SOMA + K;
}
4-
a) 1, 3, 5, 7, 9 (Números ímpares)
b) 2, 4, 8, 16, 32, 64, 128 (Potências de 2)
c) 0, 1, 4, 9, 16, 25, 36, 49 (Quadrados perfeitos)
d) 4, 16, 36, 64, 100 (Quadrados dos números pares: 2², 4², 6², 8², 10²)
e) 1, 1, 2, 3, 5, 8, 13 (Sequência de Fibonacci)
f) 2, 10, 12, 16, 17, 18, 19, 20 (Contagem sequencial)
5-
Ligue o primeiro interruptor e deixe ligado por cerca de 10 minutos.
Desligue o primeiro interruptor e ligue o segundo.
Vá até a sala das lâmpadas:
A lâmpada que estiver acesa é do segundo interruptor.
A lâmpada que estiver apagada, mas quente, é do primeiro interruptor.
A lâmpada apagada e fria é do terceiro interruptor.
