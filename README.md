4 Bit adder
Entradas:
Duas entradas de 4 bits (A e B) e uma entrada de Carry In (Cin), que é o vai-um inicial.
Saídas:
Uma saída de 4 bits (Soma) e um Carry Out (Cout), que indica se houve vai-um final.
Explicação:
O circuito soma dois números binários de 4 bits usando quatro somadores completos em série. Cada estágio soma um par de bits e o carry do anterior, gerando o resultado final da adição.
Half subtractor
## entradas

A  o valor de onde vamos subtrair

B   o valor que será subtraído
## Saídas

Diff Resultado da subtração A - B

Borrow  Indica se precisou “pedir 1 emprestado” porque B era maior que A
 ## Explicação

O half-subtractor é um circuito lógico que faz a subtração de um único bit.
Ele calcula A – B, mas não considera nenhum empréstimo vindo de operações anteriores.

Full subtractor
## ENTRADAS

A  valor a ser subtraído

B  valor que subtrai

Bin   empréstimo vindo da subtração anterior

## Saídas

Difference  Resultado da subtração

Bout  Empréstimo que vai para o próximo bit

## Explicação 

O full-subtractor faz a subtração de um bit considerando também o empréstimo anterior, então ele é o que realmente permite subtrair números maiores (vários bits).
