**UNIVERSIDADE LUSÓFONA DE HUMANIDADES E TECNOLOGIAS**

*Introdução à Computação*

# Ficha de Exercícios - 1: Aritmética Binária


1.  Faça as seguintes conversões entre bases de representação numérica
a.	40610 para base 7 = 11207
b.	67810 para base 4 = 222124
c.	1101012 para base 10 = 5310
d.	4445 para base 10 =12410 
e.	4446 para base 10 = 17210
f.	5647 para base 8 = 4438
g.	5647 para 2 = 1001000112
h.	87610 para base 2 = 11011011002
i.	540210 para base 2 = 4096 + 1024 + 256 + 16 + 8 + 2 = 10101000110102 


2.  Converta para base Hexadecimal e Octal da forma mais directa possível:
a.	01001010110011112=0x4ACF = 0453178 
b.	00101100110110112=0x2CDB = 0263338
c.	01101110111011112=0x6EEF = 0673578
d.	11111111111111112=0xFFFF = 1777778


3.	Converta para base Decimal assumindo que o número está em complemento para 2.
a.	001011002 = 4410
b.	010101012 = 8510
c.	001001112 = 3910
d.	101011002 = -128+44 = -8410
e.	110101012 = -128+85  = -4310
f.	101001112 = -128+39 = -8910



4.	Considerando um processador com 8bits. Calcule o resultado das seguintes operações e diga se ocorre overflow. Assuma que os operandos estão representados em Complemento para 2. Faça as contas todas em binário e no fim converta o resultado para décimal
	0xF0+0xF4 = 0xE4 = -2810. Não há Overflow.
	0xF0-0xF4 = 0xFC = -410. Não há Overflow.
	0x77+0x77 = 119 + 119 = 0xEE = -1810. Há Overflow.
	0x03×0x02 = 0x06 = 610. Não há Overflow.
	0xFF×0x04 = 0xFC = -410. Não há Overflow.


5.	Considere um processador com 4-bits. Qual das seguintes afirmações é correcta sobre o sinal de Overflow resultante de uma soma ou subtracção.
Ocorre quando o bit de transporte que sai do bit mais significativo é diferente de ‘0’
Nunca ocorre quando os operadores têm sinal diferente
Ocorre sempre que se somam dois operandos do mesmo sinal
Nenhuma das anteriores
