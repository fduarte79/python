# Operadores 

## Aritméticos
```
>>> 22 + 7    # adição
29
>>> 22 - 7    # subtração
15
>>> 22 * 7    # multiplicação
154
>>> 22 ** 7   # potênciação
2494357888
 22 / 7       # divisão
3.142857142857143
>>> 22 % 7    # módulo (resto)
1
>>> 22 // 7   # quociente (parte inteira)
3
```
## Relacionais
```
>>> 3 < 4    # menor
True
>>> 4 <= 4   # menor ou igual
True
>>> 2 >  4   # maior
False
>>> 2 >= 4   # maior ou igual
False
>>> 0 == 1   # igual
False
>>> 0 != 1   # diferente
True
```
## Atribuição
```
>>> variavel = 1    # atribuição simples
>>> variavel += 2   # atribuição com operação  
>>> variavel
3
```

## Lógicos
```
>>> True and True   # E
True
>>> True or False   # OU
True
>>> not True        # NEGADO
False
```

## *Bitwise* (operador de bit)
```
>>> # E lógico
>>> True & True    
True
>>> # OU lógico
>>> True | False   
True
>>> # XOR (eXclusive OR)
>>> # compara bit a bit,
>>> # e ambos devem ser
>>> # diferentes
>>> bin(5)         
'0b101'            
>>> bin(2)         
'0b10'             
>>> 5^2
7
>>> bin(7)
'0b111'
>>> # ~ NOT (inverte todos
>>> # os bits)
>>> bin(5)        
'0b101'           
>>> ~5
-6
>>> bin(-6)
'-0b110'
>>> # descarta os bits mais a esquerda e completa (2)
>>> # com zeros a direita do número decimal (1)
>>> # bits a serem descartados << numero decimal
>>> # 1 (00000001) << 2 (00000100)
>>> 1 << 2
4
>>> bin(4)
'0b100'
>>> # descarta os bits mais a direita e completa (3)
>>> # com zeros a esquerda do número decimal (12)
>>> # número decimal >> bits a serem descartados
>>> # 12 (00001100) >> 3 bits = 1 (0000001)
>>> 12 >> 3
1
```
