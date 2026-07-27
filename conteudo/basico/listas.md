# Listas
+ Lista é uma sequência de objetos criada usando colchetes e o primeiro elemento possui índice zero;
+ Sobre a composição dos tipos de elementos, pode ser homogênea ou heterogênea
+ Listas são mutáveis;
+ Para atribuir um novo valor, basta usar o operador de atribuição e especificar o  índice.
+ É possível acessar os elementos da lista de forma inversa: último (`-1`), penúltimo (`-2`), e assim sucessivamente.
+ É possível acessar diversos elementos de uma só vez, usando o operador de faixa `:`
+ `+` operador concatena listas
+ `*` operador de repetição 
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
>>> elementos[3] = "novo elemento"   # atribuindo novo valor
>>> elementos[3]
'novo elemento'
>>> elementos[5][2]                  # acessando um elemento da lista
'laranja'
>>> elementos[2:5]                   # acessando uma faixa
[0.5, 'novo elemento', (4+5j)]
```

## Métodos

```
>>> l0 = [2, 1, 0]  # lista 0
>>> l1 = [-1, -2]   # lista 1
>>> l1.append(-3)   # adiciona elemento -3 no final da lista 1
>>> l0.extend(l1)   # extende a lista 0 com a lista 1
>>> l0.sort()       # ordena a lista 0 (altera)
>>> l0.pop(3)       # remove o 3º elemento
>>> del l0[1:4]     # deleta o elementos de índice 1 ao 4
```
Método `split` separa uma string em palavras.
```
>>> frase = "Python é muito fácil de programar!!!"
>>> frase.split()   # delimitador por padrão é o epsaço
['Python', 'é', 'muito', 'fácil', 'de', 'programar!!!']
>>> frase.split("o")   # mas pode especificar algum caractere separador como argumento da função
['Pyth', 'n é muit', ' fácil de pr', 'gramar!!!']
```
