<h1> HTML Web Developer </h1>
Formação HTML Web Developer

<h2> O que é HTML? </h2>

<ul>
  <li> HTML é a linguagem de marcação padrão para criar páginas da Web </li>
  <li> HTML significa Hyper Text Markup Language </li>
  <li> HTML descreve a estrutura de uma página da Web </li>
  <li> HTML consiste em uma série de elementos </li>
  <li> Os elementos HTML informam ao navegador como exibir o conteúdo </li>
  <li> Os elementos HTML são representados por tags </li>
  <li> As tags HTML rotulam partes do conteúdo, como "cabeçalho", "parágrafo", "tabela" e assim por diante </li>
  <li> Os navegadores não exibem as tags HTML, mas as usam para renderizar o conteúdo da página </li>
</ul>

<p><code>&lt;!DOCTYPE html&gt;</code></p>

![2023-05-04_05h25_55](https://user-images.githubusercontent.com/88487115/236156493-4cffdd61-2852-4ba5-8f98-2ed5803b4ace.png)

<strong> Exemplo explicado </strong>

<ul>
  <li> A declaração <code>&lt;!DOCTYPE html&gt;</code> define este documento como HTML5 </li>
  <li> O <code>&lt;html&gt;</code> é o elemento raiz de uma página HTML </li>
  <li> O <code>&lt;head&gt;</code> contém meta informações sobre o documento </li>
  <li> O <code>&lt;title&gt;</code> especifica um título para o documento </li>
  <li> O <code>&lt;body&gt;</code> contém o conteúdo da página visível </li>
  <li> O <code>&lt;h1&gt;</code> ~ <code>&lt;h6&gt;</code> definem cabeçalhos </li>
  <li> O <code>&lt;p&gt;</code> define um parágrafo </li>
</ul>

<strong> Tags em HTML </strong>
<p> Tags HTML são nomes que pertencem aos elementos entre colchetes e que delimitam a abertura e o encerramento de uma marcação, por exemplo: </p>
<p><strong><code>&lt;tag de abertura&gt;</code> o conteúdo que você deseja exibir entra aqui ... <code>&lt;/tag de fechamento&gt;</code></strong></p>

<ul>
  <li> Observe que as tags HTML normalmente vêm em pares como <code>&lt;p&gt;</code> e <code>&lt;/p&gt;</code> </li>
  <li> A primeira tag em um par é a tag inicial, a segunda tag é a tag final </li>
  <li> A tag final é escrita como a tag inicial, mas com uma barra inserida antes do nome da tag </li>
</ul>


<strong> Criando uma página </strong>

```
<!DOCTYPE html>
<html lang="pt-br">

  <head>
    <meta charset="UTF-8" />
    <title>Meu primeiro site</title>
  </head>
 
  <body>
    <h1>Meu primeiro cabeçalho</h1>
    <p>Meu primeiro parágrafo.</p>
    <p>Meu segundo parágrafo.</p>
  </body>
 
</html>
```

<strong> Salvar a página HTML </strong>

Nomeie o arquivo "index.html" e defina a codificação para UTF-8 (que é a codificação preferida para arquivos HTML).

![2023-05-04_06h23_46](https://user-images.githubusercontent.com/88487115/236164217-08cca386-776f-4c08-9550-03e9f9d102a5.png)

Você pode usar .htm ou .html como extensão de arquivo, não há diferença.

<strong> Cabeçalhos do HTML </strong>

Cabeçalhos são normalmente utilizados para identificar páginas e seções e possuem aparência diferenciada do restante do texto. No HTML há seis níveis de cabeçalhos/títulos que podem ser utilizados por meio das tags h1, h2, h3, h4, h5 e h6, sendo h1 o maior/mais relevante e h6 o menor/menos relevante.
De acordo com as regras de SEO, é recomendado que uma página possua apenas uma tag <code>&lt;h1&gt;</code> que indique seu assunto, pois essa tag informa aos motores de busca qual sua principal palavra-chave.

<strong> Parágrafos no HTML </strong>

Parágrafos de texto são gerados na HTML por meio das tags <code>&lt;p&gt;</code> e <code>&lt;/p&gt;</code>. Esse é um exemplo de tag cuja disposição na tela se dá em forma de bloco, ou seja, um parágrafo é posto sempre abaixo do outro.

<strong> Imagens no HTML </strong>

A inserção de imagens em uma página HTML pode ser feita por meio da tag img, que recebe no atributo src o endereço do arquivo a ser carregado. Além desse, outros dois atributos importantes são o alt, que indica um texto alternativo que será exibido caso o arquivo não possa ser carregado, e title, que indica o texto que aparecerá como tooltip ao passar o mouse sobre a figura.

```<img src="exemplo.png" alt="Texto alternativo" title="Avatar" />```

No caso da tag img, ainda temos as tags figure e figcaption:

```
<figure>
  <img src="http://meusite.com.br/assets/imagem.jpg" alt="Imagem">
  <figcaption>Legenda da figura 1</figcaption>
</figure>
```

<strong> Links no HTML </strong>

Links são normalmente utilizados para direcionar o usuário para outras páginas, ou para outras partes da mesma página. Nos dois casos, utilizamos a tag <strong style="color: green">a</strong>, que possui o atributo <strong style="color: green">href</strong> no qual indicamos o destino daquele link.

```<a href="pagina2.html">Página 2</a>```

Já o exemplo abaixo mostra como adicionar uma âncora para um elemento na mesma página. Nesse caso, ao clicar no link o browser mudará o foco para o elemento que possui o atributo <strong style="color: green">id</strong> igual àquele indicado no <strong style="color: green">href</strong>.

```
<a href="#paragrafo3">Ir para o parágrafo 3</a>
<!--outros elementos-->
<p id="paragrafo3">Parágrafo no rodapé.</p>
```

<strong> Tabelas no HTML </strong>

Tabelas são elementos utilizados com frequência para exibir dados de forma organizada em linhas e colunas. No HTML, elas são formadas por três tags básicas:

<ul>
  <li> <code>&lt;table&gt;</code> para delimitar a tabela; </li>
  <li> <code>&lt;tr&gt;</code> para indicar as linhas; </li>
  <li> <code>&lt;td&gt;</code> para formar as colunas. </li>
</ul>

O exemplo a seguir mostra um exemplo simples de tabela com três linhas e duas colunas, e seu resultado pode ser visto na figura abaixo.

```
<table>

  <tr>
    <td>Linha 1, Coluna 1</td>
    <td>Linha 1, Coluna 2</td>
  </tr>

  <tr>
    <td>Linha 2, Coluna 1</td>
    <td>Linha 2, Coluna 2</td>
  </tr>

  <tr>
    <td>Linha 3, Coluna 1</td>
    <td>Linha 3, Coluna 2</td>
  </tr>

</table>
```

<table>
  <tr>
    <td>Linha 1, Coluna 1</td>
    <td>Linha 1, Coluna 2</td>
  </tr>
  <tr>
    <td>Linha 2, Coluna 1</td>
    <td>Linha 2, Coluna 2</td>
  </tr>
  <tr>
    <td>Linha 3, Coluna 1</td>
    <td>Linha 3, Coluna 2</td>
  </tr>
</table>

Existem ainda outras três tags utilizadas para delimitar, de forma mais organizada, as partes da tabela:

<ul>
  <li> thead para o cabeçalho; </li>
  <li> tbody para o corpo; </li>
  <li> tfoot para o rodapé. </li>
</ul>

O próximo exemplo traz uma tabela mais complexa, utilizando todas as tags. Seu resultado é apresentado na figura abaixo.

```
<table>
  <thead>

    <tr>
      <th>Produto</th>
      <th>Preço</th>
      <th>Quantidade</th>
    </tr>

  </thead>

  <tbody>

    <tr>
      <td>Feijão</td>
      <td>R$ 8,75</td>
      <td>1</td>
    </tr>
 
    <tr>
      <td>Arroz</td>
      <td>R$ 4,99</td>
      <td>2</td>
    </tr>
 
  </tbody>
  <tfoot>

    <tr>
      <td>Total</td>
      <td></td>
      <td>R$ 18,73</td>
    </tr>

  </tfoot>
</table>
```

<table>
  <thead>
    <tr>
      <th>Produto</th>
      <th>Preço</th>
      <th>Quantidade</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Feijão</td>
      <td>R$ 8,75</td>
      <td>1</td>
    </tr>
    <tr>
      <td>Arroz</td>
      <td>R$ 4,99</td>
      <td>2</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td>Total</td>
      <td></td>
      <td>R$ 18,73</td>
    </tr>
  </tfoot>
</table>

Por padrão, as tabelas não possuem bordas. Isso deve ser adicionado por meio das CSS.

