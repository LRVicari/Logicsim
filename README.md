

---

## 4-bit Adder

### **Entradas**
- **A**: Número binário de 4 bits  
- **B**: Número binário de 4 bits  
- **Cin (Carry In)**: Vai-um inicial usado na primeira soma

### **Saídas**
- **Soma**: Resultado da adição (4 bits)  
- **Cout (Carry Out)**: Vai-um final caso a soma ultrapasse 4 bits

### **Explicação**
O 4-bit Adder é formado por **quatro somadores completos (full adders)** ligados em série.  
Cada estágio soma:
1. Um bit de A  
2. Um bit de B  
3. O carry vindo do estágio anterior  

O resultado final é um número de 4 bits mais um carry final indicando overflow.

---

##  Half-Subtractor

### **Entradas**
- **A**: Valor de onde vamos subtrair  
- **B**: Valor que será subtraído  

### **Saídas**
- **Diff (Difference)**: Resultado de `A - B`  
- **Borrow**: Indica se foi necessário pedir empréstimo (quando B > A)

### **Explicação**
O Half-Subtractor realiza a subtração de **um único bit**.  
Ele calcula `A – B`, mas **não considera nenhum empréstimo vindo de operações anteriores**, ou seja, funciona apenas isoladamente.

---

##  Full-Subtractor

### **Entradas**
- **A**: Valor a ser subtraído  
- **B**: Valor que subtrai  
- **Bin (Borrow In)**: Empréstimo vindo da subtração anterior  

### **Saídas**
- **Difference**: Resultado da subtração  
- **Bout (Borrow Out)**: Empréstimo que vai para o próximo bit

### **Explicação**
O Full-Subtractor é utilizado para subtrair números de vários bits porque ele **considera o empréstimo anterior (Bin)**.  
Ele calcula a subtração completa de um único bit, propagando o empréstimo para o próximo estágio quando necessário.

