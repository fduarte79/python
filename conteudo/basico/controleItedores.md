# Controle de iteradores

```
>>> for i in range(1,5):
...     print(i)
...
1
2
3
4
```
`break`: iterrompe o laço imediatamente
```
>>> for i in range(1,5):
...     if i == 3: break
...     print(i)
...
1
2
```
`continue`: pula o restante da iteração
```
>>> for i in range(1,5):
...     if i == 3: continue
...     print(i)
...
1
2
4
```
`pass`: não executa nada (usado para implementações em construção)
```
>>> for i in range(1,5):
...     if i == 3: pass
...     print(i)
...
1
2
3
4
```
