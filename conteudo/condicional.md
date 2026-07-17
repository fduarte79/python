# Condicional
Permite que determinado trecho seja executado (ou não) de acordo com a condição.
+ `if`: a cláusula é executado dentro da sentença se for verdadeira
+ `else`: opcional, se a condição de `if` for falsa, a cláusula `else` é executada
+ não há limites para que um `if` dentro de outro `if` (`if` aninhados)
+ no caso de existir muitos `if`, um recurso interessane é o `elif`
+ só pode haver um `else` para um `if`
  
**`if`**
```
>>> x = 3
>>> if x < 5:
...     print(x)
...
3

>>> x = 7
>>> if x < 5:
...     print(x)
...
>>>
```

**`if` em linha**
```
>>> if x > 5: print(x)
...
7
```

**`if`/`else`**
```
>>> if x < 5:
...     print(x)
... else:
...     print('x > 5')
...
x > 5
```

