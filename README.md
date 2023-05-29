# Readme: Tabelas Criadas com HTML

Este é um simples Readme para explicar como criar tabelas utilizando HTML. As tabelas são elementos bastante úteis para exibir dados organizados e estruturados em uma página da web. O HTML fornece tags específicas para criar tabelas de forma simples e flexível.

## Estrutura básica de uma tabela em HTML

Para criar uma tabela em HTML, você precisa seguir a seguinte estrutura básica:

```html
<table>
  <tr>
    <th>Cabeçalho da Coluna 1</th>
    <th>Cabeçalho da Coluna 2</th>
    <th>Cabeçalho da Coluna 3</th>
  </tr>
  <tr>
    <td>Dado da Coluna 1, Linha 1</td>
    <td>Dado da Coluna 2, Linha 1</td>
    <td>Dado da Coluna 3, Linha 1</td>
  </tr>
  <tr>
    <td>Dado da Coluna 1, Linha 2</td>
    <td>Dado da Coluna 2, Linha 2</td>
    <td>Dado da Coluna 3, Linha 2</td>
  </tr>
</table>
```

A tag `<table>` é usada para iniciar uma tabela. Em seguida, você pode usar a tag `<tr>` para criar linhas dentro da tabela. Cada linha é composta por células, representadas pela tag `<td>` para dados normais. Se você quiser criar células de cabeçalho, utilize a tag `<th>`.

## Personalizando a tabela

Você pode personalizar sua tabela adicionando atributos às tags. Alguns atributos comumente usados incluem:

- `border`: define a espessura da borda da tabela;
- `cellpadding`: define o espaçamento interno das células;
- `cellspacing`: define o espaçamento entre as células;
- `width`: define a largura da tabela;
- `bgcolor`: define a cor de fundo da tabela;
- `align`: alinha a tabela horizontalmente (valores possíveis: "left", "center", "right").

Exemplo de tabela com alguns atributos:

```html
<table border="1" cellpadding="5" cellspacing="0" width="100%" bgcolor="#e6e6e6" align="center">
  <!-- conteúdo da tabela -->
</table>
```

## Tabelas aninhadas

É possível criar tabelas aninhadas, ou seja, colocar uma tabela dentro de outra. Isso é útil para exibir informações mais complexas.

Exemplo de tabela aninhada:

```html
<table>
  <tr>
    <th>Cabeçalho 1</th>
    <th>Cabeçalho 2</th>
    <th>Cabeçalho 3</th>
  </tr>
  <tr>
    <td>
      <table>
        <tr>
          <th>Subcabeçalho 1</th>
          <th>Subcabeçalho 2</th>
        </tr>
        <tr>
          <td>Dado 1,1</td>
          <td>Dado 1,2</td>
        </tr>
        <tr>
          <td>Dado 2,1</td>
          <td>Dado 2,2</td>
        </tr>
      </table>
   
