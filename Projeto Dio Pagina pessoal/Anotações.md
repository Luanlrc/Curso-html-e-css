# Curso-html-e-css
Curso html e css, com anotações, arquivos e projetos do curso

Pode estudar no site da MDM

#### Estrutura basica do html

<!DOCTYPE	html>
<html>
    <head>
        <meta>
        <title>Luan Cordeiro</title>
*<!doctype  html>*
    *<html>*

        <head>
            <meta charset="utf-8">
            <title>Luan C</title>
        </head>
*</html>*

#### semântica (da significado ao no html)

*<section>* -> Representa um seção genérica de conteudos

*<aside>*      -> conteúdo relacionado ao conteúdo principal de uma pagina

*<header>*   -> cabeçalho 

*<footer>*    -> Roda pé 

*<article>*  -> Conteúdo relevante

*<h1>-<h6>*.  -> Representa a importância de um titulo

#### Tags para links

##### colocar um link para uma pagina

<a href="link">

Nome

</a>

##### colocar um link para um email

<a href="mailto:exemplo@exemplo.com">

E-mail

</a>

### imagens

<img>

<img src="img/avatar.jpg">

<img alt="foto de Luan Cordeiro">

##### listas

##### <ul

item 1

item 2

##### <ol

1. item 1
2. item 2

##### <li

item da lista ol

# Css 3

##### Alguns comandos



* background >  fundo
* color > cor
* backgroundcolor  >  mudar cor de fundo
* font-size > tamanho da fonte
* font-style >  estilo da fonte
* margin > margem, distancia entre o final da pagina até a borda
* border > borda
* padding > preenchimento entre a borda e o conteúdo
* radius > curvatura da ponta da borda
* top > cima
* right > direita
* bottom > baixo
* left > direita        

**Exemplo** : border-top

* width > largura
* height > altura
* max-height >altura maxima
* max-width > largura maxima
* text-align > alinhar texto ao centro, a direita, a esquerda
* solid > solido
* dotted > pontilhado
* dashed > tracejado
* font-family >  altera a fonte do texto. EX: font-family: Verdana;
* font-style > altera o estilo da fonte. EX: font-style: italic;
* text-transform >  alterna o texto entre maiúscula e minúscula 

​    **Exemplo**: 

text-transform : uppercase;   > coloca todo o texto em caixa alta

text-transform : lowercase;  >  coloca todo o texto  em caixa baixa

text-transform : capitalize;  >   coloca as primeiras letras de cada palavra em maiúscula.

* text-decoration > coloca uma linha no texto

**Exemplo**: 

text-decoration: underline;  > coloca uma linha a baixo da palavra

text-decoration: overline;     >  coloca uma linha acima da palavra

text-decoration: line-through; > coloca uma linha cortando a palavra



**Lista**

ul > list-style-type: square; > transforma o ponto em um quadrado

ol > list-style-type: upper-roman; > transforma os numero em romanos maiúsculos

ul > list-style-type: "\1f44D";  > transforma os pontos em um emoji



No html podemos declarar um **id** e uma **class** apenas digitando desta maneira, exemplo: class="nome" ou id="nome". E para chamar o id ou class desejado no css basta colocar "**#**" para o id, por exemplo "**#nome**" e para class chamamos com um "**.**" por exemplo "**.nome**"
