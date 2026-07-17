# Iteradores

## laço de repetição `for`
```
>>> vogais = ['a', 'e', 'i', 'o', 'u']
>>> for vogal in vogais:
...     vogal
...
'a'
'e'
'i'
'o'
'u'
```

**laço `for` com interadores simultâneos**
```
>>> lista = [('a', 'b', 'c'), ('d', 'e', 'f'), ('g', 'h', 'i')]
>>> for x, y, z in lista:
...     print(f'{x = }, {y = }, {z = }')
...
x = 'a', y = 'b', z = 'c'
x = 'd', y = 'e', z = 'f'
x = 'g', y = 'h', z = 'i'
```
