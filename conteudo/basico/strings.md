# Strings
+ É uma coleção ordenada de caracteres por um índice (inteiro) que inicia com 0 e entre colchetes.
+ `[0]`: acessa o primeiro elemento
+ `[-1]`: acessa o último elemento
+ `[-2]`: penúltimo elemento e assim sucessivamente
+ `[i:j]`: uma faixa de índice positivo (ou negativo)
+ `[:]`: faixa completa
+ Strings são imutáveis, caso precise alterar uma letra, faça uma cópia
```
>>> variavel = "Python"
>>> variavel[0]
'P'
>>> variavel[5]
'n'
>>> variavel[-1]
'n'
>>> len(variavel)                    # função len retorna o tamanho da string
6
>>> variavel[1:5]
'ytho'
>>> variavel[-5:-1]
'ytho'
>>> variavel = 'p' + variavel[1:]    # substituindo a letra P
>>> variavel
'python'
```
