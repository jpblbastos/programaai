---
title: Tabuada de multiplição
subtitle: Uma tabuada com mágica by João Leite
date: 2023-05-13
bigimg: [{src: "/programaai/img/tabuada.jpg", desc: "A Baratinha"}]
tags: ["golang", "musica", "fácil"]
---

KaTeX can be used to generate complex math formulas server-side. 

$$
\phi = \frac{(1+\sqrt{5})}{2} = 1.6180339887\cdots
$$

Additional details can be found on [GitHub](https://github.com/Khan/KaTeX) or on the [Wiki](http://tiddlywiki.com/plugins/tiddlywiki/katex/).
<!--more-->

### Vamos contar a musica 

The image banners at the top of the page are refered to as "bigimg" in this theme. They are optional, and one more more can be specified. If more than one is specified, the images rotate every 10 seconds. In the front matter, bigimgs are specified using an array of hashes.

{{< youtube he4QBuND1Yo >}}

### Agora vamos codificar a musica 

```golang
// Tabuada de multiplição
// By - João Paulo Bastos Leite
package main

import "fmt"

func main() {
    // Variaveis
    var tabuada_de int = 1

    fmt.Println("Tabuada de multiplição do", tabuada_de)
    fmt.Println(tabuada_de, "X 0 =", tabuada_de*0)
    fmt.Println(tabuada_de, "X 1 =", tabuada_de*1)
    fmt.Println(tabuada_de, "X 2 =", tabuada_de*2)
    fmt.Println(tabuada_de, "X 3 =", tabuada_de*3)
    fmt.Println(tabuada_de, "X 4 =", tabuada_de*4)
    fmt.Println(tabuada_de, "X 5 =", tabuada_de*5)
    fmt.Println(tabuada_de, "X 6 =", tabuada_de*6)
    fmt.Println(tabuada_de, "X 7 =", tabuada_de*7)
    fmt.Println(tabuada_de, "X 8 =", tabuada_de*8)
    fmt.Println(tabuada_de, "X 9 =", tabuada_de*9)
    fmt.Println(tabuada_de, "X 10 =", tabuada_de*10)
}
```
{{< goplay url=DvOqD24C92Y >}}


### O que acha de fazer mágica com a tabuada? 
> Basta alterar o valor da variavel **tabuada_de** para 2 ou o valor que desejar fazer a tabuada, veja como:
```golang
var tabuada_de int = 2
```