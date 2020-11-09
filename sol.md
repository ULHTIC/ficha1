**UNIVERSIDADE LUSÓFONA DE HUMANIDADES E TECNOLOGIAS**

*Introdução à Computação*

# Ficha de Exercícios - 1: Aritmética Binária


1. Faça as seguintes conversões entre bases de representação numérica

    1. 406<sub>10</sub> para base 7
        - 1120
   
    2. 678<sub>10</sub>  para base 4
        - 22212
   
    3. 110101<sub>2</sub>  para base 10
        - 53
   
    4. 444<sub>5</sub> para base 10
        - 124   
      
    5. 444<sub>6</sub> para base 10
        - 172   
   
    6. 564<sub>7</sub>para base 8
        - 443
      
    7. 564<sub>7</sub> para 2
        - 100100011

    8. 876<sub>10</sub>  para base 2
        - 1101101100
   
    9. 5402<sub>10</sub>  para base 2 
        - 1010100011010

2. Converta para base Hexadecimal e Octal da forma mais directa possível:

    1. 0100101011001111<sub>2</sub>
        - 0x4ACF = 045317<sub>8</sub>
   
    2. 0010110011011011<sub>2</sub>
        - 0x2CDB = 026333<sub>8</sub>   
   
    3. 0110111011101111<sub>2</sub>
        - 0x6EEF = 067357<sub>8</sub>   
   
    4. 1111111111111111<sub>2</sub>
        - 0xFFFF = 177777<sub>8</sub>   

3. Converta para base Decimal assumindo que o número está em complemento para 2.

    1. 00101100<sub>2</sub>
        - = 44<sub>10</sub>    
   
    2. 01010101<sub>2</sub>
        - = 85<sub>10</sub>  
   
    3. 00100111<sub>2</sub>
        - = 39<sub>10</sub>     
   
    4. 10101100<sub>2</sub>
        - = -128+44 = -84<sub>10</sub>     
   
    5. 11010101<sub>2</sub>
        - = -128+85 = -43<sub>10</sub>     
   
    6. 10100111<sub>2</sub>
        - = -128+39 = -89<sub>10</sub>     

4. Considerando um processador com 8bits. Calcule o resultado das seguintes operações e diga se ocorre overflow. Assuma que os operandos estão representados em Complemento para 2. Faça as contas todas em binário e no fim converta o resultado para décimal

    1. 0xF0+0xF4
        - = 0xE4 = -28<sub>10</sub>. Não há Overflow.
   
    2. 0xF0-0xF4
        - = 0xFC = -4<sub>10</sub>. Não há Overflow.
   
    3. 0x77+0x77
        - = 0xEE = -18<sub>10</sub>. Há Overflow.   
   
    4. 0x03×0x02
        - = 0x06 = 6<sub>10</sub>. Não há Overflow.  
   
    5. 0xFF×0x04
        - = 0xFC = -4<sub>10</sub>. Não há Overflow.

5. Considere um processador com 4-bits. Qual das seguintes afirmações é correcta sobre o sinal de Overflow resultante de uma soma ou subtracção.

    1. Ocorre quando o bit de transporte que sai do bit mais significativo é diferente de ‘0’
   
    2. Nunca ocorre quando os operadores têm sinal diferente
        - Resposta correcta.
   
    3. Ocorre sempre que se somam dois operandos do mesmo sinal
   
    4. Nenhuma das anteriores


6. Considerando um processador com 8bits. Calcule o resultado das seguintes operações lógicas. Assuma que os operandos estão representados em Complemento para 2. Faça as contas todas em binário e no fim converta o resultado para décimal.

    1. 0xFF OR 0xF4
        - 0xFF = -1<sub>10</sub>
   
    2. (NOT 0xFF) XOR 0xAA
        - 0xAA = -86<sub>10</sub>    
   
    3. NOT(0x48 AND 0xFF)
        - NOT(0x48) = 0xB7 = -73<sub>10</sub>      
   
    4. 0xAB AND (NOT 0x48) OR 0xFA AND 0x55
        - 0x51 = 81<sub>10</sub>


7. Qual intervalo de números com sinal possíveis de representar com 5 bits em Complemento para 2?

    1.   Com sinal
        - [-2^4, 2^4-1] = [-16, +15]

    2.   Sem sinal?
        - [0, 2^n – 1] = [0, 31]   
   
8. Num computador, quais as principais diferenças entre a memória principal (RAM) e secundária (discos)?
    - Ver slides

9. Num CPU, qual é a função do banco de registos?
    - Ver slides

10. Calcule o resultado das seguintes operações lógicas. Indique o resultado em base hexadecimal.
    1. A = 0xAA, B = 0x85
        1. A OR B
            -   = 0xAF

        2. A AND B
            -   = 0x80
         
        3. A XOR B
            -   = 0x2F
         
        4. (NOT B) AND A
            -   = 0xAA
         
        5. (NOT B) OR A
            -   = 0xFA
         
    2. A = 0xAA, B = 0xFF
        1. A OR B
            -   = 0xFF
         
        2. A AND B
            -   = AA
         
        3. A XOR B
            -   = 0x55
         
        4. (NOT B) AND A
            -   = 0x00
         
        5. (NOT B) OR A
            -   = 0xAA


