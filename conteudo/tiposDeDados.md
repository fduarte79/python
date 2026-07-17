# Tipos de dados
### Caracteres
```
>>> type("A")
<class 'str'>
```
### Numéricos
```
>>> type(1)      # inteiro
<class 'int'>
>>> type(1.2)    # real
<class 'float'>
>>> type(5+2j)   # complexo
<class 'complex'>
```
### Booleanos
```
>>> type(True)
<class 'bool'>
```
### Nenhum
```
>>> type(None)
<class 'NoneType'>
```
### Bytes
```
>>> type(b'A')              # (imutável)
<class 'bytes'>
>>> type(bytearray(b'A'))   # (mutável)
<class 'bytearray'>
>>> type(memoryview(b'0'))  # acessa a memória interna  e modifica sem fazer cópia
<class 'memoryview'>
>>> memoryview(b'0')
<memory at 0x0000015B6C312C80>
```
### Sequências
```
>>> type(['a', 'e', 'i', 'o', 'u'])   # lista
<class 'list'>
>>> type(('a', 'e', 'i', 'o', 'u'))   # tupla (lista imutável)
<class 'tuple'>
>>> intervalo = range(0,3)            # intervalo
>>> 1 in intervalo
True
>>> type(intervalo)
<class 'range'>
```
### Dicionários
```
>>> python = {'dificuldade': 'fácil'}
>>> type(python)
<class 'dict'>
```
### Conjuntos (conjunto desordenado e único)
```
>>> vogais = {'a', 'o', 'i', 'e', 'u'}
>>> type(vogais)
<class 'set'>
>>> vogais = frozenset({'a', 'o', 'i', 'e', 'u'})   # (imutável)
>>> type(vogais)
<class 'frozenset'>
```
### Comentários e documentação
```
>>> # comentário
>>> '''Python
... é
... legal'''
'Python\né\nlegal'
```
