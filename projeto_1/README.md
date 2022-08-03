# Project 1:

Given a `list()` named `rankings` that contains N songs

```
rankings = ["Fearless", "Red", "Long Live"]

```

1. Ask the user how many songs they want, we will call this number `M` (use `input()`)

`If M > N`
If the number of songs requested is more than the size of `rankings` then return 
"(You're Not) SORRY... not enough songs"

_Dica: How do you write conditional statements / expressions?_

```
if (EXPR):
	# if the EXPR is True
else:
	# if the EXPR is False
```


2. If the number of songs requested is less than the size of `rankings` then return then first `M` songs from the list.



### Sample Run

```
>>> Oi, Quantas Musicas? 3
Fearless
Red
Long Live
```

### Sample 2

```
>>> Oi, Quantas Musicas? 4
>>> (You're Not) SORRY... not enough songs
```

## Dicas
1. Use `type()` to check the types of your variables. What kind of variables are you going to use?

## Recursos
[Como Trabalhar com Listas](https://www.devmedia.com.br/como-trabalhar-com-listas-em-python/37460)

[Introdução a Listas](https://panda.ime.usp.br/aulasPython/static/aulasPython/aula09.html?highlight=lista)