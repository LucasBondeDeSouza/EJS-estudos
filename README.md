# O que é EJS?

EJS (Embedded JavaScript Templating - JavaScript Incorporado) é uma biblioteca de template para Node.js que permite a geração de HTML com JavaScript de forma simples e eficiente. É amplamente utilizada para criar páginas web dinâmicas, onde o conteúdo pode ser gerado dinamicamente no servidor antes de ser enviado ao cliente

## EJS Tags

### <%= variable %>
Esta tag é usada para imprimir o valor de uma expressão no HTML

### <% console.log("hello") %>
Esta tag é usada para imprimir o valor de uma expressão no HTML sem escapar os caracteres especiais. Isso pode ser perigoso se o conteúdo não for confiável, pois pode levar a ataques de XSS.

### <%% %%>
Esta tag é usada para escapar o delimitador EJS. Isso é útil quando você deseja incluir um literal <% %> no seu template.


### <%# This is a comment %>
Esta tag é usada para comentários que não serão incluídos no HTML renderizado

### <%- include("header.ejs") %>
É usada para incluir outro arquivo EJS dentro do template atual.