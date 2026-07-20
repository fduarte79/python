# Funções

Função pode ser definida com conjunto de instruções que é invocada por um nome e pode receber argumentos. Por exemplo a função que exibe o conteúdo em tela que é invocada pelo nome `print` e recebe como argumento a string `"Python"`.
```
>>> print('Python')
Python
```
+ Para criar uma função, utilize a palavra chave `def`, seguido do nome da função e os parêntes para os argumentos.\
+ A identação é importante para delimitar onde inicia e termina o código da função.\
+ `return` é importante se deseja que a função retorne algum dado, e geralmente é, mas não obrigatório.\
+ Variáveis criadas dentro da função são locais logo, seu conteúdo fica restrito dentro do seu escopo.
```
>>> x = 3
>>> y = 7
>>> def soma(x,y):
...     x = 9
...     return x + y
...
>>> soma(x,y)
16
>>> x, y
(3, 7)
```
## Funções `lambda`
Seu uso não é uma boa prática de programação se usada em excesso, uma vez que dificulta a sua manutenção.
```
>>> soma = lambda x,y: x + y
>>> soma(3,7)
10
```
