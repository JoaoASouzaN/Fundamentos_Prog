# Sintaxe basica -> markdown

Em markdown é possivel fazer pequenas estilisações uma delas é o titulo, o qual possui seis tipos. Ao utilizar penas um '#' indica um titulo e ao adicionar outros vai se criando sub titulos e quanto mais hashtags menor é o tamanho do titulo. Outros tipos possiveis são o negrito, utilizando \** palavra ** ou \__ palavra __, para o italico, utilizado \* palavra * ou \_ palavra _, pode-se tambem riscar as palavras utilizando-se \~~ palavra ~~.

Outra posibilidade é a criação de listas ordenadas '1. ' ou não ordenadas '- '. Podemos também, por meio \[TextoDoLink](Link).

A adição de imagens se faz por meio \!\[TextoAlternativo](LinkDaImagem).

Para adicionar uma unica linha de codigo pode-se utilizar crase ao inicio e ao fim da linha em questão \`Linha de codigo`, caso seja necessario adicionar diversas linhas de codigo, utiliza-se três siguidas \```Codigo.

Se faz possivel a criação de tabelas, para isso utiliza-se \### NomeDaTabela.

Para se fazer citações é uma boa pratica em markdown utilizar- o > seguido da citação.

Podemos também criar uma linha orizontal como separador, para tal usa-se três traços \--- ao inicio e fim.

Dentro de um codigo markdown, pode-se fazer o uso de HTML imbutido, embora limitado , pode-se ser util.

Uma alternativa interesante e a criação de uma lista de tarefas, para isso utiliza-se \- [x] Tarefa 1.

Outra possibilidade presente no markdown é a criação de notas de rodapé, \[^1]: Nota de rodapé.

---
# Exemplos:


# \# Titulo:
## \## Sub-Titulo 1:
### \### Sub-Titulo 2:
#### \#### Sub-Titulo 3:
##### \##### Sub-Titulo 4:
###### \###### Sub-Titulo 5:


**NegritoComAsterisco** e __NegritoComSublinha__

*ItalicoComAsterisco* e _ItalicoComSublinha_
~~PalavraRiscada~~


1. Item Lista Ordenada
2. Item2 Lista Ordenada

- Item Lista Desordenada
- Item2 Lista Desordenada

[TextoDoLink](https://github.com/JoaoASouzaN)

![ImagemGoogle](https://www.google.com/images/branding/googlelogo/2x/googlelogo_light_color_92x30dp.png)
[^1]: Essa é uma nota de rodapé

`int x = 10;`

```
  int y = x;
  string nome = João;
```

### - Tabela de letras
1. a
2. b

> Aqui deveria ter uma citação

---

- [ ] Item da lista de tarefas
- [ ] Outro item da lista
