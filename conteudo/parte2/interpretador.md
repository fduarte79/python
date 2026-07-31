# Interpretador

+ Programa responsável por ler e executar instruções;
+ Pode ser executado de forma interativa por meio do shell
  + Prompt *primário* (`>>>`): para iniciar uma instrução
  + Prompt *secundário* (`...`): para dar continuidade no bloco
+ Pode ser executado por meio de script (arquivo que armazena as instruções)

## Modo Interativo
Abra um prompt de comando e então digite: `python`;\
O interpretador exibe uma mensagem de boas vindas, informando seu número de versão e um aviso de copyright antes de exibir o primeiro prompt;\
No modo interativo ele solicita um comando através do prompt primário, tipicamente três sinais de maior (`>>>`);\
Para linhas de continuação do comando atual, o prompt secundário padrão é formado por três pontos (`...`)
```
>>> print('Hello World!!!')
Hello World!!!
```

## Execução no modo script
+ Abra um editor de textos do tipo bloco de notas, vi, nano ou algum de sua preferência;\
  + Não pode ser editores tipo Word, Libre Office
+ Não é obrigatório, mas é uma boa prática de programação incluir o cabeçalho a seguir:
```
#!/usr/bin/env python3
# -*- coding: cp1252 -*-
```
+ Salve com a extensão .py

## Primeiro programa
Como primeiro programa: vamos escrever o clássico "Hello World!!!"
```
#!/usr/bin/env python3
# -*- coding: cp1252 -*-
print("Hello World!!!")
```
E a sua execução no prompt de comando:
```
>python hellp.py
Hello World!!!
```
