---

# Sintaxe basica do CSS

CSS (Cascading Style Sheets) é uma linguagem utilizada para descrever a apresentação de documentos HTML. Com o CSS, você pode controlar a aparência de elementos em uma página da web, incluindo cores, fontes, espaçamento, layout, e muito mais.

A principal utilidade do CSS é separar o conteúdo (HTML) da apresentação (CSS), permitindo que você estilize várias páginas de um site de maneira consistente e eficiente. Além disso, o CSS oferece grande flexibilidade e controle sobre o design, possibilitando a criação de layouts responsivos que se adaptam a diferentes dispositivos e tamanhos de tela.

O potencial do CSS vai além da simples estilização. Com ele, é possível criar animações, transições e efeitos visuais complexos que melhoram a experiência do usuário. Através do uso de seletores, pseudo-classes e pseudo-elementos, você pode aplicar estilos específicos a elementos individuais ou a grupos de elementos de forma precisa.

Em resumo, o CSS é uma ferramenta poderosa que, quando combinada com o HTML, permite criar páginas web atraentes e funcionais, proporcionando uma melhor usabilidade e uma experiência visual aprimorada.

---

Ao trabalhar com CSS, podemos abordar os elementos de diferentes formas, as quais seguem uma hierarquia, quanto mais especifico maior a prioridade. Sendo elas:

## Inline Styles

Inline styles são aplicados diretamente no elemento HTML usando o atributo style. Este método é o mais específico, o que significa que ele substitui qualquer estilo definido em um arquivo CSS ou em um \<style> no cabeçalho do documento.

Exemplo:

<!DOCTYPE html>
    <html>
      <head>
        <style>
          p{
            color: blue; /* Estilo padrão aplicado a todos os parágrafos */
            }
        </style>
      </head>
      <body>
        <p style="color: red;">Este texto será vermelho devido ao estilo inline.</p>
        <p>Este texto será azul devido ao estilo padrão.</p>
      </body>
    </html>
    
No exemplo acima, o primeiro parágrafo será vermelho devido ao estilo inline, enquanto o segundo parágrafo será azul devido ao estilo padrão definido no cabeçalho.

---

## ID selectores:

ID selectors são usados para selecionar um elemento específico com um identificador único. IDs são definidos usando o atributo id e são precedidos pelo símbolo \# no CSS.

Exemplo:

<!DOCTYPE html>
    <html>
      <head>
        <style>
          #header {
            background-color: yellow;
            color: black;
          }
        </style>
      </head>
      <body>
        <div id="header">Este é o cabeçalho com um ID único.</div>
        <div>Este é um div normal sem um ID.</div>
      </body>
    </html>

No exemplo acima, apenas o \div com o \id="header" terá o fundo amarelo e o texto preto.

---

## Class selectores:

Class selectors são usados para selecionar um ou mais elementos que compartilham a mesma classe. Classes são definidas usando o atributo class e são precedidas por um ponto (.) no CSS.

Exemplo:

<!DOCTYPE html>
    <html>
      <head>
        <style>
          .highlight {
            background-color: yellow;
            font-weight: bold;
          }
        </style>
      </head>
      <body>
        <p class="highlight">Este parágrafo está destacado.</p>
        <p class="highlight">Este também está destacado.</p>
        <p>Este parágrafo não está destacado.</p>
      </body>
    </html>
    
No exemplo acima, os parágrafos com a classe highlight terão um fundo amarelo e texto em negrito.

---

## Tag selectores:

Tag selectors (ou element selectors) são usados para selecionar todos os elementos de um tipo específico. Eles são simplesmente escritos com o nome da tag HTML.

Exemplo:

<!DOCTYPE html>
    <html>
      <head>
        <style>
          p {
            color: blue;
            font-size: 14px;
          }
        </style>
      </head>
      <body>
        <p>Este parágrafo será azul com tamanho de fonte 14px.</p>
        <p>Este também será azul com tamanho de fonte 14px.</p>
      </body>
    </html>
    
No exemplo acima, todos os elementos \<p> terão a cor azul e o tamanho de fonte de 14px.
