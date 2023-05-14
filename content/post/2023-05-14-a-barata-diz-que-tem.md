---
title: A Barata Diz Que Tem
subtitle: Não vamos deixar a barata mentir by João Leite
date: 2023-05-12
bigimg: [{src: "/programaai/img/barata.jpg", desc: "A Baratinha"}]
tags: ["golang", "musica", "desafiante]
---

KaTeX can be used to generate complex math formulas server-side. 

$$
\phi = \frac{(1+\sqrt{5})}{2} = 1.6180339887\cdots
$$

Additional details can be found on [GitHub](https://github.com/Khan/KaTeX) or on the [Wiki](http://tiddlywiki.com/plugins/tiddlywiki/katex/).
<!--more-->

### Vamos contar a musica 

The image banners at the top of the page are refered to as "bigimg" in this theme. They are optional, and one more more can be specified. If more than one is specified, the images rotate every 10 seconds. In the front matter, bigimgs are specified using an array of hashes.

{{< youtube uHIHt4OOm90 >}}

### Agora vamos codificar a musica 

```golang
// A Barata Diz Que Tem
// By - João Paulo Bastos Leite
package main
 
import "fmt"
 
func main() {
    // Variaveis 
    var quantidade_saias_de_filo int = 0
    var quantidade_anel_de_formatura int = 0
    var quantidade_sapato_de_fivela int = 0
    var quantidade_saias_de_cetim int = 0
    var quantidade_sapato_de_veludo int = 0
    var quantidade_saias_de_balao int = 0
    var quantidade_vestido_de_babado int = 0
    var barata_viaja_de_aviao string = "nao"

    // Musica codificada
    fmt.Println("A barata diz que tem")
    fmt.Println("Sete saias de filó")
    if quantidade_saias_de_filo == 7 {
        fmt.Println("A barata tem mesmo sete saias de filó")
        fmt.Println("Rá rá rá, ró ró ró")
    } else {
        fmt.Println("É mentira da barata")
        fmt.Println("Ela tem é", quantidade_saias_de_filo , "só")
        fmt.Println("Rá rá rá, ró ró ró")
        fmt.Println("Ela tem é", quantidade_saias_de_filo , "só")
        fmt.Println("Rá rá rá, ró ró ró")
        fmt.Println("Ela tem é", quantidade_saias_de_filo , "só")
    } 

    fmt.Println("")
    fmt.Println("A barata diz que tem")
    fmt.Println("Um anel de formatura")
    if quantidade_anel_de_formatura == 1 {
        fmt.Println("A barata tem mesmo um anel de formatura")
        fmt.Println("Rá rá rá, ró ró ró")
    } else {
        fmt.Println("É mentira da barata")
        fmt.Println("Ela tem a casca dura")
        fmt.Println("Rá rá rá, ró ró ró")
        fmt.Println("Ela tem a casca dura")
        fmt.Println("Rá rá rá, ró ró ró")
        fmt.Println("Ela tem a casca dura")
    }

    fmt.Println("")
    fmt.Println("A barata diz que tem")
    fmt.Println("Um sapato de fivela")
    if quantidade_sapato_de_fivela == 1 {
        fmt.Println("A barata tem mesmo um sapato de fivela")
        fmt.Println("Rá rá rá, ró ró ró")
    } else {
        fmt.Println("É mentira da barata")
        fmt.Println("O sapato é da mãe dela")
        fmt.Println("Rá rá rá, ró ró ró")
        fmt.Println("O sapato é da mãe dela")
        fmt.Println("Rá rá rá, ró ró ró")
        fmt.Println("O sapato é da mãe dela")
    }

    fmt.Println("")
    fmt.Println("A barata diz que tem")
    fmt.Println("Uma saia de cetim")
    if quantidade_saias_de_cetim == 1 {
        fmt.Println("A barata tem mesmo uma saia de cetim")
        fmt.Println("Rá rá rá, ró ró ró")
    } else {
        fmt.Println("É mentira da barata")
        fmt.Println("Ela tem é de capim")
        fmt.Println("Rá rá rá, ró ró ró")
        fmt.Println("Ela tem é de capim")
        fmt.Println("Rá rá rá, ró ró ró")
        fmt.Println("Ela tem é de capim")
    }

    fmt.Println("")
    fmt.Println("A barata diz que tem")
    fmt.Println("Um sapato de veludo")
    if quantidade_sapato_de_veludo == 1 {
        fmt.Println("A barata tem mesmo um sapato de veludo")
        fmt.Println("Rá rá rá, ró ró ró")
    } else {
        fmt.Println("É mentira da barata")
        fmt.Println("Ela tem o pé peludo")
        fmt.Println("Rá rá rá, ró ró ró")
        fmt.Println("Ela tem o pé peludo")
        fmt.Println("Rá rá rá, ró ró ró")
        fmt.Println("Ela tem o pé peludo")
    }

    fmt.Println("")
    fmt.Println("A barata diz que tem")
    fmt.Println("Sete saias de balão")
    if quantidade_saias_de_balao == 7 {
        fmt.Println("A barata tem mesmo setes saias de balão")
        fmt.Println("Rá rá rá, ró ró ró")
    } else {
        fmt.Println("É mentira não tem não")
        fmt.Println("Nem dinheiro pra sabão")
        fmt.Println("Rá rá rá, ró ró ró")
        fmt.Println("Nem dinheiro pra sabão")
        fmt.Println("Rá rá rá, ró ró ró")
        fmt.Println("Nem dinheiro pra sabão")
    }

    fmt.Println("")
    fmt.Println("A barata diz que tem")
    fmt.Println("Um vestido de babado")
    if quantidade_vestido_de_babado == 1 {
        fmt.Println("A barata tem mesmo um vestido de babado")
        fmt.Println("Rá rá rá, ró ró ró")
    } else {    
        fmt.Println("É mentira da barata")
        fmt.Println("O vestido tá rasgado")
        fmt.Println("Rá rá rá, ró ró ró")
        fmt.Println("O vestido tá rasgado")
        fmt.Println("Rá rá rá, ró ró ró")
        fmt.Println("O vestido tá rasgado")
    }

    fmt.Println("")
    fmt.Println("A barata sempre diz")
    fmt.Println("Que viaja de avião")
    if barata_viaja_de_aviao == "sim" {
        fmt.Println("A barata viaja mesmo de avião")
        fmt.Println("Rá rá rá, ró ró ró")
    } else {   
        fmt.Println("É mentira da barata")
        fmt.Println("Ela vai é de busão")
        fmt.Println("Rá rá rá, ró ró ró")
        fmt.Println("Ela vai é de busão")
        fmt.Println("Rá rá rá, ró ró ró")
        fmt.Println("Ela vai é de busão")
    }
}

```
{{< goplay url=KUxSSXsuwGm >}}


### A barata merece sete saias de filó? 
> Basta alterar o valor da variavel **quantidade_saias_de_filo** para 7, veja como:
```golang
var quantidade_saias_de_filo int = 7
```

### A barata merece um anel de formatura? 
> Basta alterar o valor da variavel **quantidade_anel_de_formatura** para 1, veja como:
```golang
var quantidade_anel_de_formatura int = 1
```

### A barata merece um sapato de fivela? 
> Basta alterar o valor da variavel **quantidade_sapato_de_fivela** para 1, veja como:
```golang
var quantidade_sapato_de_fivela int = 1
```

### A barata merece uma saia de cetim? 
> Basta alterar o valor da variavel **quantidade_saias_de_cetim** para 1, veja como:
```golang
var quantidade_saias_de_cetim int = 1
```

### A barata merece um sapato de veludo? 
> Basta alterar o valor da variavel **quantidade_sapato_de_veludo** para 1, veja como:
```golang
var quantidade_sapato_de_veludo int = 1
```

### A barata merece sete saias de balão? 
> Basta alterar o valor da variavel **quantidade_saias_de_balao** para 7, veja como:
```golang
var quantidade_saias_de_balao int = 7
```

### A barata merece um vestido de babado? 
> Basta alterar o valor da variavel **quantidade_vestido_de_babado** para 1, veja como:
```golang
var quantidade_vestido_de_babado int = 1
```

### A barata pode viajar de avião? 
> Basta alterar o valor da variavel **barata_viaja_de_aviao** para sim, veja como:
```golang
var barata_viaja_de_aviao string = "sim"
```