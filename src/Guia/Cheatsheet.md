<p align="center">
  <img src="https://cdn0.iconfinder.com/data/icons/octicons/1024/markdown-512.png" alt="Markdown Icon" width="300px" height="300px">
</p>

<h1 align="center"> Sumário </h1>

01. [Headers - Cabeçalhos](#headers---cabeçalhos)
00. [Links](#Links)
00. [Imagens](#Imagens)
00. [Ênfase](#Ênfase)
00. [Quebra de Linha](#Quebra-de-Linha)
00. [Parágrafo](#Parágrafo)
00. [Blackquotes](#Blackquotes)
00. [Lista Ordenadas](#Lista-Ordenadas)
00. [Lista Ordenadas Simplificada](#Lista-Ordenadas-Simplificada)
00. [Lista Desordenadas](#Lista-Desordenadas)
00. [Tabela](#Tabela)
00. [Alinhamento em Tabela](#Alinhamento-Tabela)
00. [Emoji](#Emoji)
00. [Lista de Tarefas](#Lista-de-Tarefas)
00. [Código](#Código)
00. [Shields](#Shields)
00. [Elemento de Detalhes](#Elemento-de-Detalhes) 
00. [Mapa](#Mapa)

----

# Headers - Cabeçalhos 

> Os "headings" são como h no html, mas no "markdown" utilizamos #.

----

## Veja como fazer:

# Header/Cabeçalho 1
## Header/Cabeçalho 2
### Header/Cabeçalho 3
#### Header/Cabeçalho 4
##### Header/Cabeçalho 5
###### Header/Cabeçalho 6
```
Markdown:
# Header/Cabeçalho 1
## Header/Cabeçalho 2
### Header/Cabeçalho 3
#### Header/Cabeçalho 4
##### Header/Cabeçalho 5
###### Header/Cabeçalho 6

----------------

HTML:
<h1> Header/Cabeçalho 1 </h1>
<h2> Header/Cabeçalho 2 </h2>
<h3> Header/Cabeçalho 3 </h3>
<h4> Header/Cabeçalho 4 </h4>
<h5> Header/Cabeçalho 5 </h5>
<h6> Header/Cabeçalho 6 </h6>
```

    

    
# Links

Links também são muito importante se você quer deixar site de referências, links alternativos e por ai vai
    
<hr>

## Veja como fazer:

[Eu sou um link](https://google.com)  
[Eu sou um link pra um arquivo](../README.md)  
[Eu sou um link com titulo(coloque o mouse em cima)](https://www.google.com/ "Google")  
<https://heartdevs.com/>  
```
Markdown:
[Eu sou um link](https://google.com)
[Eu sou um link pra um arquivo](../README.md)
[Eu sou um link com titulo](https://google.com "Google")
<https://heartdevs.com/>

----------------

HTML:
<a href="https://google.com">Eu sou um link</a>
<a href="../README.md">Eu sou um link pra um arquivo</a>
<a href="https://google.com "Google"">Eu sou um link com titulo</a>
<a href="https://heartdevs.com/>https://heartdevs.com/</a>
```
Observações:

Para desabilitar um link em seu arquivo basta adicionar acento grave (`) assim:

`www.heartdevs.com`
 
Em Markdown:
```markdown
`www.heartdevs.com`
```

Você também pode criar referências à links caso utilize ele mais de uma vez.
```markdown
[Eu sou um link][1]
[Eu sou o mesmo link!][1]

<!-- Mais markdown ... -->

[1]: https://google.com
```

Não só com links, você também pode fazer isso com uma frase ou até uma palavra!
```markdown
Eu amo o projeto [4noobs]!

[4noobs]: https://github.com/he4rt/4noobs
```
    
# Imagens 

## Veja como fazer:

A estrutura do Markdown para inserir imagens é:
```
![Texto alternativo caso imagem não esteja disponível](link_da_imagem)
```
Exemplo:  
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
    
    
# Ênfase

Você pode adicionar ênfase como: negrito, itálico e riscado.
    
----

## Veja como fazer:

### **Negrito**
Eu amo a **He4rtDevelopers**
```
Markdown:
Eu amo a **He4rtDevelopers**
Eu amo a __He4rtDevelopers__

----------------

HTML:
Eu amo a <strong>He4rtDevelopers</strong>
```

### *Itálico*

Eu amo a *He4rtDevelopers*
```
Markdown:
Eu amo a *He4rtDevelopers*
Eu amo a _He4rtDevelopers_

----------------

HTML:
Eu amo a <em>He4rtDevelopers</em>
```

### ***Negrito*** e ***Itálico***

Eu amo a ***He4rtDevelopers***
```
Markdown:
Eu amo a ***He4rtDevelopers***
Eu amo a ___He4rtDevelopers___
Eu amo a __*He4rtDevelopers*__
Eu amo a **_He4rtDevelopers_**

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
    
# Quebra de Linha

Assim como a tag **`<br>`**, do HTML que faz uma quebra de linha, o Markdown também possui essa característica.  
Para isso é necessário deixar dois "espaços" no final da linha que deseja "quebrar".
    
----

## Veja como fazer:
### Exemplo *SEM* quebra de linha
Lorem ipsum dolor sit amet.
Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
```
Markdown:
Lorem ipsum dolor sit amet.
Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
```  


### Exemplo *COM* quebra de linha
Lorem ipsum dolor sit amet.  
Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.  
```
Markdown:
Lorem ipsum dolor sit amet.  
Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.   

----------------

HTML:
Lorem ipsum dolor sit amet.<br>
Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.<br>
```
    
    
# Parágrafo

Para criar um parágrafo novo, é necessário deixar uma linha em branco entre os dois parágrafos. Já no HTML, utiliza-se a tag `<p>[TEXTO]</p>`.
    
<hr>

## Veja como fazer:

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 

Neque ornare aenean euismod elementum nisi quis eleifend. Facilisi morbi tempus iaculis urna id volutpat lacus laoreet non.
```
Markdown:
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 

Neque ornare aenean euismod elementum nisi quis eleifend. Facilisi morbi tempus iaculis urna id volutpat lacus laoreet non.

----------------

HTML:
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
<p>Neque ornare aenean euismod elementum nisi quis eleifend. Facilisi morbi tempus iaculis urna id volutpat lacus laoreet non.</p>
```

## Veja como *NÃO* fazer:

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
Neque ornare aenean euismod elementum nisi quis eleifend. Facilisi morbi tempus iaculis urna id volutpat lacus laoreet non.
```
Markdown:
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 
Neque ornare aenean euismod elementum nisi quis eleifend. Facilisi morbi tempus iaculis urna id volutpat lacus laoreet non.

----------------

HTML:
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Neque ornare aenean euismod elementum nisi quis eleifend. Facilisi morbi tempus iaculis urna id volutpat lacus laoreet non.</p>
```
    
# Blackquotes

Segundo a documentação de HTML da Mozilla: "O Elemento HTML `<blockquote>` (ou Elemento HTML de citação de bloco) indica que o texto incluído é uma longa citação."

----    

## Veja como fazer:
 Pretium aenean pharetra magna ac. Lobortis elementum nibh tellus molestie nunc non blandit massa enim.

```
Markdown:
> Pretium aenean pharetra magna ac. Lobortis elementum nibh tellus molestie nunc non blandit massa enim.

----------------

HTML:
<blockquote>
  <p>Pretium aenean pharetra magna ac. Lobortis elementum nibh tellus molestie nunc non blandit massa enim.</p>
</blockquote>
```

## Também é Possivel Aninhar os Blockquotes(Nested Blockquotes)
> Pretium aenean pharetra magna ac. Lobortis elementum nibh tellus molestie nunc non blandit massa enim.
>
>> Turpis egestas pretium aenean pharetra magna.

```
Markdown:
> Pretium aenean pharetra magna ac. Lobortis elementum nibh tellus molestie nunc non blandit massa enim.
>
>> Turpis egestas pretium aenean pharetra magna.

----------------

HTML:
<blockquote>
  <p>Pretium aenean pharetra magna ac. Lobortis elementum nibh tellus molestie nunc non blandit massa enim.</p>
  <blockquote>
    <p>Turpis egestas pretium aenean pharetra magna.</p>
  </blockquote>
</blockquote>
```

## Blackquotes Também Podem Possuir Multiplos Parágrafos
> Pretium aenean pharetra magna ac. Lobortis elementum nibh tellus molestie nunc non blandit massa enim.
>
> Turpis egestas pretium aenean pharetra magna.

```
Markdown:
> Pretium aenean pharetra magna ac. Lobortis elementum nibh tellus molestie nunc non blandit massa enim.
>
> Turpis egestas pretium aenean pharetra magna.

----------------

HTML:
<blockquote>
  <p>Pretium aenean pharetra magna ac. Lobortis elementum nibh tellus molestie nunc non blandit massa enim.</p>
  <p>Turpis egestas pretium aenean pharetra magna.</p>
</blockquote>
```

## Blackquotes podem conter outros elementos de Markdown
> ### Lorem ipsum
> 1. He4rt
> 2. Developers
>> 4noobs

```
Markdown:
> ### Lorem ipsum
> 1. He4rt
> 2. Developers
>> 4noobs

----------------

HTML:
<blockquote>
    <h3>Lorem ipsum</h3>
    <ol>
        <li>He4rt</li>
        <li>Developers</li>
    </ol>
    <blockquote>
        <p>4noobs</p>
    </blockquote>
</blockquote>
```
    

    
# Lista Ordenadas
Como o nome deixa explícito, é possível criar listas ordenadas numericamente.

----

## Veja como fazer:
1. Primeiro item
2. Segundo item
    1. Primeiro item indentado
3. Terceiro item

```
Markdown:
1. Primeiro item
2. Segundo item
    1. Primeiro item indentado
3. Terceiro item

----------------

HTML:
<ol>
    <li>Primeiro item</li>
    <li>Segundo item</li>
    <ol>
        <li>Primeiro item indentado</li>
    </ol>
    <li>Terceiro item</li>
</ol>
```

# Lista Ordenadas Simplificada

Uma outra maneira de fazer uma lista ordenada é utilizando os valores como 00.  

00. Primeiro item
00. Segundo item  
00. Terceiro item

```
Markdown:
00. Primeiro item
00. Segundo item  
00. Terceiro item
```

Caso deseje que comece com um valor que não seja 0, basta definir o primeiro com o valor desejado, como o exemplo a seguir.

02. Primeiro item
00. Segundo item  
00. Terceiro item

```
Markdown:
02. Primeiro item
00. Segundo item  
00. Terceiro item
```

**Identação**
01. Primeiro item
    01. Primeiro item identado  
    00. Segundo item identado  
        1. Primeiro item identado pela segunda vez
        0. Segundo item identado pela segunda vez
    00. Terceiro item identado
00. Segundo item

```
Markdown:
01. Primeiro item
    01. Primeiro item identado  
    00. Segundo item identado  
        1. Primeiro item identado pela segunda vez
        0. Segundo item identado pela segunda vez
    00. Terceiro item identado
00. Segundo item
```

**Observação:** Mesmo que você utilize números no markdown, o github vai transforma a primeira identação em algarismos romanos e a segunda em letras.

### Observações:

Mesmo que o número dos índices do markdown estejam incorretos, é exibido a ordem da forma correta.  
Exemplo:  
1. Primeiro item
4. Segundo item
2. Terceiro item

```
Markdown:
1. Primeiro item
4. Segundo item
2. Terceiro item
```

    
# Lista Desordenadas

Como o nome deixa explícito, é possível criar listas desordenadas.

----

## Veja como fazer:

- Primeiro item
- Segundo item
    - Primeiro item indentado
- Terceiro item
```
Markdown:
- Primeiro item
- Segundo item
    - Primeiro item indentado
- Terceiro item

----------------

HTML:
<ul>
    <li>Primeiro item</li>
    <li>Segundo item</li>
    <ul>
        <li>Primeiro item indentado</li>
    </ul>
    <li>Terceiro item</li>
</ul>
```

### Observações:

Também é possivel utilizar, além do `-`, os símbolos `+` e `*`. Contudo, se combinado de forma incorreta, pode ter resultados indesejados.
* Primeiro item
* Segundo item
    + Primeiro item indentado
- Terceiro item

```
Markdown:
* Primeiro item
* Segundo item
    + Primeiro item indentado
- Terceiro item
```


# Tabela


Você também pode implementar tabelas em seu markdown. Apenas adicionando três ou mais hífens (---) para criar o cabeçalho da tabela e barra vertical  (|) para separar as colunas.

----

## Veja como fazer isso:

|Nome|Idade| Profissão|
|---| ---| ---| 
|João|18|Desenvolvedor|
|Mario|20|Empresario|

## Em HTML:
```html
<table>
    <tr>
        <td>Nome</td>
        <td>Idade</td>
        <td>Profissão</td>
    </tr>
    <tr>
        <td>João</td>
        <td>18</td>
        <td>Desenvolvedor</td>
    </tr>
    <tr>
        <td>Mario</td>
        <td>20</td>
        <td>Empresario</td>
    </tr>
</table>
```
## Markdown:

```markdown
|Nome|Idade| Profissão|
|---| ---| ---| 
|João|18|Desenvolvedor|
|Mario|20|Empresario|
```


# Alinhamento Tabela

Você pode alinhar o texto nas colunas para a direita, esquerda ou centro. basta adicionar dois pontos (:) à esquerda, direita ou dos dois lados nas linhas de hífens na linha do cabeçalho.

## Veja como fazer isso:

|Nome|Idade| Profissão|
|:---| :---: | ---:| 
|João|18|Desenvolvedor|
|Mario|20|Empresario|

Markdown:

```markdown
|Nome|Idade| Profissão|
|:---| :---: | ---:| 
|João|18|Desenvolvedor|
|Mario|20|Empresario|
```

# Emoji

Para adicionar emoticons em seu arquivo basta copiar e colar o emoji no arquivo do Markdown ou digitar o código do emoji.

Procure emojis no [Emojipedia](https://emojipedia.org/)

## Veja como fazer isso:

He4rt Developers :purple_heart:

Em Markdown:

```markdown
    He4rt Developers :purple_heart:
```

# Lista de Tarefas

Para organizar as tarefas de seu arquivo em markdown é possível apenas utilizando um traço (-) e colchetes com um espaço na frente ([]) dos itens da sua lista de tarefas. Para deixar selecionado basta adicionar um x entre os colchetes ([X]).

## Veja como fazer isso:

- [x] Escrever o markdown4noobs
- [ ] Tocar violão
- [ ] Atualizar o site.

Em Markdown:

```markdown
    - [x] Escrever o markdown4noobs
    - [ ] Tocar violão
    - [ ] Atualizar o site.

```
    
    
# Código

É possível inserir pedaços de código e destacar as sintaxes de alguma linguagem de programação específica automaticamente.

----

## Veja como fazer:

Código na linguagem de programação C:
```c
#include <stdio.h>

int main(void){
    printf("Hello, World!");
    return 0;
}
```

```md
Markdown:
    ```c
    #include <stdio.h>
    
    int main(void){
        printf("Hello, World!");
        return 0;
    }
    ```

----------------

HTML:
<code>
      #include <stdio.h><br>
      <br>
      int main(void){<br>
          printf("Hello, World!");<br>
          return 0;<br>
      }<br>
</code>

Obs.: A tag <br> foi inserida pois, sem ela, o código ficaria todo em uma única linha.
```
 



# Shields

É possível colocar Shields do [Shield.io](https://shields.io/) para transmitir informações de um modo curto e direto. Além de deixar o repositório com uma cara mais moderna.

## Veja Como Fazer:

### 1 - Gere o Shield:

<img src="https://user-images.githubusercontent.com/69097449/129428392-4e91b0af-7bbf-4b78-a0fe-16b7fd87ebb2.png" alt="imagem-Shield-teste"></img>

### 2 - Pegue o HTML ou Markdown:

**Markdown**:

```md
![GitHub Repo stars](https://img.shields.io/github/stars/he4rt/4noobs?style=social)
```

**HTML**:

```html
<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/he4rt/4noobs?style=social">
```

![GitHub Repo stars](https://img.shields.io/github/stars/he4rt/4noobs?style=social)

## Personalização

Para personalizar, o Shield, não pode estar como `social`, como exemplo acima, mas com o style `Plastic`, `flat`, `flat-square` e ou `for-the-badge`, porque somente eles podem sofrer influência das edições.

### Observe os 2 exemplos:

**Sem Edição**:

![GitHub Repo stars](https://img.shields.io/github/stars/he4rt/4noobs?style=flat-square)

**Com Edição**:

![GitHub Repo stars](https://img.shields.io/github/stars/he4rt/4noobs?color=red&label=Estrelas&logo=github&logoColor=black&style=flat-square)


<img src="https://user-images.githubusercontent.com/69097449/129429871-1576182e-cc3b-4420-a84d-c54e6ab3499d.png" alt="edicao-shield"></img>

# Elemento de Detalhes

É possível adicionar `<details>` `<summary>` para criar uma ferramenta onde o usuário irá obter informações adicionais.

## Veja como fazer isso:

<details><summary>Qual é a melhor comunidade de devs?</summary>He4rt Developers :purple_heart:!</details>

```html
<details><summary>Qual é a melhor comunidade de devs?</summary>He4rt Developers :purple_heart:!</details>
```

## Outro exemplo:

<details>
<summary>Lista de Linguagens</summary>

* Java
* JavaScript
* C
* Python
* PHP

</details>

```markdown
<details>
<summary>Lista de Linguagens</summary>

* Java
* JavaScript
* C
* Python
* PHP

</details>
```

# Mapa

É possível adicionar um Mapa em seu markdown, Para criar um mapa basta adicionar um JSON com as coordernadas, que pode ser criado pelo site [GeoJSON](https://geojson.io/).

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {},
      "geometry": {
        "coordinates": [
          [
            [
              -6.878466286287704,
              43.26369041932804
            ],
            [
              -6.701404805391263,
              39.69503598185034
            ],
            [
              -6.651329210701363,
              36.87979740184866
            ],
            [
              -1.3529233719869467,
              37.769974225157924
            ],
            [
              1.886378635135486,
              42.37351821794945
            ],
            [
              -6.878466286287704,
              43.26369041932804
            ]
          ]
        ],
        "type": "Polygon"
      }
    }
  ]
}
```
## Veja como fazer isso:

```
Markdown:
```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {},
      "geometry": {
        "coordinates": [
          [
            [
              -6.878466286287704,
              43.26369041932804
            ],
            [
              -6.701404805391263,
              39.69503598185034
            ],
            [
              -6.651329210701363,
              36.87979740184866
            ],
            [
              -1.3529233719869467,
              37.769974225157924
            ],
            [
              1.886378635135486,
              42.37351821794945
            ],
            [
              -6.878466286287704,
              43.26369041932804
            ]
          ]
        ],
        "type": "Polygon"
      }
    }
  ]
}
```
----


Ir para: [Início](/README.md)
