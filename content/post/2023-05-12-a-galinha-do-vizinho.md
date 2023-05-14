---
title: A Galinha do Vizinho
subtitle: Agora com ovos parametrizados by João Leite
date: 2023-05-12
bigimg: [{src: "/programaai/img/pintinho-amarelinho.jpeg", desc: "O Pintinho"}]
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

{{< youtube 3HcpR3vTopQ >}}

### Agora vamos codificar a musica 

```golang
// A Galinha do Vizinho
// By - João Paulo Bastos Leite
package main
 
import "fmt"
 
func main() {
    // Variaveis 
    var dono_da_galinha string = "vizinho"
    var cor_do_ovo string = "amarelinho"
    var quantos_ovos int = 10
 
    // Musica codificada
    fmt.Println("A galinha do", dono_da_galinha)
    fmt.Println("Bota ovo", cor_do_ovo)
 
    for ovo := 1; ovo <= quantos_ovos; ovo++ {
        fmt.Println("Bota", ovo)
    }
}
```
{{< goplay url=5xRySbe6Grz >}}


### Vamos mudar o dono da galinha? 
> Basta alterar o valor da variavel **dono_da_galinha** para o nome do novo dono, veja como:
```golang
var dono_da_galinha string = "joao"
```


### O que acha de mudar a cor do ovo da galinha?
> Basta alterar o valor da variavel **cor_do_ovo** para a cor que deseja, veja como:
```golang
var cor_do_ovo string = "verdinho"
```

### E se a galinha conseguir botar mais ovos? Seria legal?
> Basta alterar o valor da variavel **quantos_ovos** para quantos ovos você deseja que ela bote:
```golang
var quantos_ovos int = 100
```