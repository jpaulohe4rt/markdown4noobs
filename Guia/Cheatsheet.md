# Glossário
1. [Headers - Cabeçalhos](#Headers-Cabeçalhos)
2. [Links](#Links)
2. [Imagens](#Imagens)


<h1 align="center">Headers - Cabeçalhos</h1>

> Os "headings" são como h no html, mas no "markdown" utilizamos #.

<hr>

## Veja como fazer:

# Header/Cabeçalho 1
```
Markdown:
# Texto

----------------

HTML:
<h1> Texto </h1>
```

## Header/Cabeçalho 2
```
Markdown:
## Texto

----------------

HTML:
<h2> Texto </h2>
```

### Header/Cabeçalho 3
```
Markdown:
### Texto

----------------

HTML:
<h3> Texto </h3>
```

#### Header/Cabeçalho 4

```
Markdown:
#### Texto

----------------

HTML:
<h4> Texto </h4>
```

##### Header/Cabeçalho 5
```
Markdown:
##### Texto

----------------

HTML:
<h5> Texto </h5>
```

###### Header/Cabeçalho 6
```
Markdown:
###### Texto

----------------

HTML:
<h6> Texto </h6>
```
    
<hr>
    
<h1 align="center">Links</h1>

Links também são muito importante se você quer deixar site de referências, links alternativos e por ai vai
    
<hr>

## Veja como fazer:

[Eu sou um link](https://google.com)<br>
[Eu sou um link pra um arquivo](../master/README.md)<br>
[Eu sou um link com titulo(coloque o mouse em cima)](https://www.google.com/ "Google")<br>
```
Markdown:
[Eu sou um link](https://google.com)
[Eu sou um link pra um arquivo](../README.md)
[Eu sou um link com titulo](https://google.com "Google")

----------------

HTML:
<a href="https://google.com">Eu sou um link</a>
<a href="../master/README.md">Eu sou um link pra um arquivo</a>
<a href="https://google.com "Google"">Eu sou um link com titulo</a>
```
    
<hr>
    
<h1 align="center">Imagens</h1>

Colocar imagens ou gifs no seu projeto pode torna-lo mais interessante, pode ser algo que lembre o seu projeto como uma referência ou até mesmo uma foto dele.
    
<hr>

## Veja como fazer:

A estrutura do Markdown para inserir imagens é:
```
![Texto alternativo caso imagem não esteja disponível](link_da_imagem)
```
Exemplo:<br>
![He4rt Developers](https://avatars0.githubusercontent.com/u/47680810?s=150)

Se quiser mais flexibilidade quanto ao formato da imagem, é possível utilizar HTML:
```
<img src="link_da_imagem" alt="Texto alternativo caso imagem não esteja disponível" width="LARGURApx" height="ALTURApx">
```
<img src="https://avatars0.githubusercontent.com/u/47680810" alt="He4rt Developers" width="50px" height="50px">

## Sim, é possível adicionar GIFs
A idéia é a mesma, em vez de um link de uma imagem, utilizamos o link de um GIF.

<img src="https://media.giphy.com/media/LmNwrBhejkK9EFP504/giphy.gif" alt="Gato Programando HTML" height="200px">

## Também é possivel inserir imagens que já estão no repositório

Vamos utilizar a imagem localizada aqui: `imgs/logo-he4rt.png`


<img src="../imgs/logo-he4rt.png" alt="Logo He4rt" height="100px">

```
![He4rt Developers](../imgs/logo-he4rt.png)
```
    
<hr>
    
<h1 align="center">Ênfase</h1>

Você pode adicionar ênfase com negrito,itálico e riscado
    
<hr>

## Veja como fazer:

### **Negrito**
Eu amo a **He4rtDevelopers**
```
Markdown:
Eu amo a **He4rtDevelopers**

----------------

HTML:
Eu amo a <strong>He4rtDevelopers</strong>
```

### _Itálico_

Eu amo a _He4rtDevelopers_
```
Markdown:
Eu amo a _He4rtDevelopers_

----------------

HTML:
Eu amo a <em>He4rtDevelopers</em>
```

## ~~Texto Riscado~~
Eu amo a ~~He4rtDevelopers~~
```
Markdown:
Eu amo a ~~He4rtDevelopers~~

----------------

HTML:
Eu amo a <strike>He4rtDeveloper<strike>
```

[Voltar para o inicio](../README.md)