# Listas
+ Lista é uma sequência de objetos criada usando colchetes e o primeiro elemento possui índice zero;
+ Sobre a composição dos tipos de elementos, pode ser homogênea ou heterogênea
+ Listas são mutáveis;
+ Para atribuir um novo valor, basta usar o operador de atribuição e especificar o  índice.
+ É possível acessar os elementos da lista de forma inversa: último (`-1`), penúltimo (`-2`), e assim sucessivamente.
+ É possível acessar diversos elementos de uma só vez, usando o operador de faixa `:`
```
>>> elementos
['string', True, 0.5, 5, (4+5j), ['banana', 'maçã', 'laranja']]
>>> type(elementos[0])
<class 'str'>
>>> type(elementos[1])
<class 'bool'>
>>> type(elementos[2])
<class 'float'>
>>> type(elementos[3])
<class 'int'>
>>> type(elementos[4])
<class 'complex'>
>>> type(elementos[5])
<class 'list'>
>>> elementos[5][2]
'laranja'
```
