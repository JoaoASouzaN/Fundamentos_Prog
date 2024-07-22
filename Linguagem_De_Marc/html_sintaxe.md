---

# Sintaxe basica do HTML

O Html (HyperText Markup Language) é uma linguagem de marcação e estruturação das paginas web, atualmente ele está na sua quinta versão e em conjunto com o css, JavaScript, React, Node e outras linguagens, sustenta toda a rede web que temos atualmente. Ele funciona como base para a construção do conteúdo, definindo elementos como títulos, parágrafos, imagens, links e seções. Todo documento HTML começa com <!DOCTYPE html> e é seguido pelas tags \<html>, \<head>, \<title>, e \<body>.

---

## Estrutura Básica:

### Cabeçalhos:
Existem seis níveis de cabeçalhos de \<h1> a \<h6>, com \<h1> sendo o maior e o \<h6> o menor.

### Parágrafos:
Parágrafos são definidos com a tag \<p> para abrir o paragrafo e \</p> para fechar.

---

## Estilização de texto:
Estilizar o texto utilizando HTML fornece uma grande diversidade de funções. É possível aplicar negrito, itálico, subscrito e sobrescrito. Também é possível destacar, riscar, sublinhar e diminuir o tamanho do texto. Podemos alterar o significado do texto, como por exemplo, indicando uma abreviação, indicação, termo, entrada de teclado, saída de código e variável.

<b>Negrito</b>: usa-se \<strong> ou \<b>.

<i>Itálico</i>: usa-se \<em> ou \<i>.

<sub>Subscrito</sub>: usa-se \<sub>.

<sup>Subrescrito</sup>: usa-se \<sup>.

<mark>Destacar</mark>: usa-se \<mark>.

<del>Riscado</del>: usa-se \<del>.

<ins>Sublinhado</ins>: usa-se \<ins>.

<small>Diminuir Tamanho</small>: usa-se \<small>.

<abbr>Abreviação</abbr>: usa-se \<abbr>.

<cite>Citação</cite>: usa-se \<cite>.

<dfn>Termo</dfn>: usa-se \<dfn>.

<kbd>Entrada de Teclado</kbd>: usa-se \<kbd>.

<samp>Saida de código</samp>: usa-se \<samp>.

<var>Variavel</var>: usa-se \<var>.

---

## Estrutura de documento

Utilizando-se do HTML, é possivel criar listas ordenadas e não ordenadas, bem como inserir links, imagens, tabelas, blocos de citações, linhas horizontais, trechos de código, lista de tarefas e notas de roda pé.

### Exemplos:

Listas ordenadas são criadas com \<ol> e as não ordenadas com \<ul> seus itens são incluidos com \<li>.

Os links podem ser incluidos utilizando a tag \<a>, caso quera adicionar o link a um texto, usa-se a tag \<a hraf"TextoDesejado">Link\</a>.

Já as imagens, podem ser incluidas com a tag \<img src"caminho/da/IMG.png" alt= "descrição da imagem">. Podendo ser incluida a partir do link ou o caminho da imagem. Ao adicionar uma imagem, é sempre importante incluir uma descrição caso a imagem quebre e não possa ser exibida, mas principalmente por questões de acessibilidade.

As tabelas podem ser criadas a partir da tag \<table>, onde seus conteudos são definidos com as tags \<tr> para as linhas, \<th> para cabeçalho/colunas e \<td> para dados da tabela.

Para se criar blocos de citações usamos a tag \<blockquote>.

Podemos utilizar linhas horizontais como separador, para isso utilizamos a tag \<hr>.

Caso seja necessario adicionar trechos de codigo podemos usar a tag \<code> e delimitar os blocos com a tag \<pre>

Não existe uma tag expecifica para definir uma nota de roda pé, no entanto, podemos utilizar as tags para links e a de ancora. Como por exemplo:
<br>
<br>
\<p>Texto com uma nota \<a href="nota1"> nota de rodapé \</a>. \</p>
<br>
\<p id="nota1">Essa é uma nota de rodapé. \</p>
