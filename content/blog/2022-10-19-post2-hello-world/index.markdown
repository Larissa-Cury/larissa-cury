---
title: "olá, linguista!"
subtitle: ""
excerpt: "onde tudo começa: <i>por que esse nome</i>?!"
date: 2022-10-19
author: "Larissa Cury"
draft: false
images:
series:
tags: 
categories:
layout: single # layout options: single, single-sidebar
---

Tradicionalmente, a primeira linha de código que aprendemos quando vamos conhecer uma linguagem de programação é **"hello, world"**. Essa expressão ficou cunhada no livro *"The C Programming Language"* (Kernighan, 1972). Printar essa *string* é a porta de entrada para o mundo da programação, eu diria que quase um ritual de passagem (o que gera muitos [memes][3] divertidos), você pode conferir mais exemplos [aqui][2]. Foi pensando nisso que nasceu o nome ***Olá, Linguista!*** como uma referência direta ao ***Hello, World!*** &#128521;

Chega de falar! Vamos praticar no **R Studio** e no **Google Chrome**?!

## No R Studio:

> Passo 1: basta digitar **print("Hello, World!")** <br> Passo 2: pressione **CTRL + Enter**


```r
print("Hello, World!")
```

```
## [1] "Hello, World!"
```

> Passo 3: **Parabéns**, este é seu primeiro código! &#128513;

## No Google Chrome:

> Em uma aba do Google Chrome, aperte a sequência **"CTRL + SHIFT + j"**, que abrirá o "Console":

> Passo 1: digite **"CTRL + SHIFT + j"**: 

![](images/paste-BAC7B81B.png)

> Passo 2: digite o comando: **alert("Hello, world!")** e pressione **enter**:

![](images/paste-FB53F6F3.png)

> Passo 3: **Parabéns!** Este é seu primeiro código! &#128513;

![](images/paste-52EEFB02.png)

> A função ```print()``` diz ao RStudio "por favor, mostre na aba 'console' a minha string". No nosso caso, nossa string é *"Hello, World"*. Uma *string* é uma sequência de caracteres. No Chrome, ```alert()``` irá criar uma [caixa de alerta][1] no navegador mostrando o que pedimos para ser escrito. 

> Seja no RStudio ou no console do Google Chrome, você pode usar ```print()``` e ```alert()``` para printar qualquer string! Você pode misturar números também, mas é importante salientar que tudo que estiver entre aspas será entendido como parte da *string*. Olhe só: 


```r
print("My name is Larissa, I was born in 1998!") # letters and numbers
```

```
## [1] "My name is Larissa, I was born in 1998!"
```

```r
print("Linguistics & stats are fun!") # special characters
```

```
## [1] "Linguistics & stats are fun!"
```

```r
print("Hello, linguistic!") # the classic string
```

```
## [1] "Hello, linguistic!"
```
> **Divirta-se!** <br>

🐕 Au-au! Hoje aprendemos que a expressão *"Hello, world!"* é, tradicionalmente, a primeira linha de código da carreira de programadores. Aprendemos a printá-la com a função ```print()``` no RStudio e com ```alert()``` no console do Google Chrome. Agora você pode tentar printar outras strings! Até a próxima!  


[1]: https://www.w3schools.com/jsref/met_win_alert.asp
[2]: https://medium.com/@codesnippet/hello-world-5d4d7d13949a
[3]: https://www.google.com/search?q=memes+hello+world+&tbm=isch&ved=2ahUKEwid_PO0suz6AhX8s5UCHXtZBY0Q2-cCegQIABAA&oq=memes+hello+world+&gs_lcp=CgNpbWcQAzIECCMQJzIGCAAQCBAeMgYIABAIEB4yBggAEAgQHjIGCAAQCBAeUKQFWOUPYMUTaABwAHgAgAG1AYgBwgmSAQMwLjmYAQCgAQGqAQtnd3Mtd2l6LWltZ8ABAQ&sclient=img&ei=7fpPY93RKPzn1sQP-7KV6Ag&bih=664&biw=1536
