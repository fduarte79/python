# Dicionários
Um dicionário é composto por uma coleção de índices (`chaves`) que está associado a um `valor`. A associação é chamado `item` ou `chave-valor`.
```
>>> beatles = {
...    "Please Please Me": 1963,
...    "With The Beatles": 1963,
...    "A Hard Day's Night": 1964,
...    "Beatles for Sale": 1964,
...    "Help!": 1965,
...    "Rubber Soul": 1965,
...    "Revolver": 1966,
...    "Sgt. Pepper's Lonely Hearts Club Band": 1967,
...    "Magical Mystery Tour": 1967,
...    "The Beatles": 1968,
...    "Yellow Submarine": 1969,
...    "Abbey Road": 1969,
...    "Let It Be": 1970
... }
```
```
>>> beatles['Help!']
1965
>>> beatles.get("Yellow Submarine")
1969
```
