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
  <li> <code>&lt;html&gt;</code> é o elemento raiz de uma página HTML </li>
  <li> <code>&lt;head&gt;</code> contém meta informações sobre o documento </li>
  <li> <code>&lt;title&gt;</code> especifica um título para o documento </li>
  <li> <code>&lt;body&gt;</code> contém o conteúdo da página visível </li>
  <li> <code>&lt;h1&gt;</code> ~ <code>&lt;h6&gt;</code> definem cabeçalhos </li>
  <li> <code>&lt;p&gt;</code> define um parágrafo </li>
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

<strong> Listas no HTML </strong>

Listas são elementos úteis para organizar e ordenar itens que estão relacionados de alguma forma. No HTML é possível criar três tipos de listas:

<ul>
  <li> ordenadas (com a tag <strong>ol</strong>) </li>
  <li> não ordenadas (com a tag <strong>ul</strong>) </li>
  <li> de definição (por meio da tag <strong>dl</strong>) </li>
</ul>


No Exemplo 8 temos um exemplo de lista ordenada, enquanto o Exemplo 9 traz um exemplo de lista não ordenada. Em seguida, a Figura 6 mostra o resultado dos dois códigos. Observe que cada item das primeiras listas é definido pela tag li.

<strong> Exemplo 8. Lista ordenada </strong>

```
<ol>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ol>
```

<strong> Exemplo 9. Lista não ordenada </strong>

```
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
```

<strong> Figura 6. Listas ordenada e não ordenada </strong>

<table>
  <tr>
    <td>
      <ol>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
      </ol>
    </td>
    <td>
      <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
      </ul>
    </td>
  </tr>
</table>

No caso das listas ordenadas temos o atributo type que permite especificar o tipo de marcador a ser usado: números (padrão), números romanos ou letras.

<strong>Exemplo 8.1. Lista ordenada por número romano maiúsculo</strong>

```
<ol type="I">
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ol>
```

<ol type="I">
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ol>

Os valores permitidos para esse atributo são:

<ul>
  <li> 1 - números (padrão) </li>
  <li> i - números romanos minúsculos </li>
  <li> I - números romanos maiúsculos </li>
  <li> a - letras minúsculas </li>
  <li> A - letras maiúsculas </li>
</ul>

As listas de definição têm um comportamento um pouco diferente, uma vez que cada item é composto por um título (dt) e uma definição (dd), semelhante ao que ocorre em dicionários, nos quais temos os verbetes e suas definições.

```
<dl>

  <dt>Título 1</dt>
  <dd>Definição 1</dd>

  <dt>Título 2</dt>
  <dd>Definição 2</dd>

  <dt>Título 3</dt>
  <dd>Definição 3</dd>

</dl>
```

<dl>
  <dt>Título 1</dt>
  <dd>Definição 1</dd>
  <dt>Título 2</dt>
  <dd>Definição 2</dd>
  <dt>Título 3</dt>
  <dd>Definição 3</dd>
</dl>

<strong> Formulários no HTML </strong>

Formulários são normalmente utilizados para integrar a página HTML a algum processamento no lado servidor. Nesses casos, a página envia dados para uma aplicação (Java, PHP, .NET etc.), que os recebe, trata e retorna algum resultado.

No HTML, geralmente usamos a tag form para delimitar a área na qual se encontram os campos a serem preenchidos pelo usuário, a fim de serem enviados para processamento no back-end (enquanto a página HTML é chamada de front-end da aplicação).

O Exemplo 11 mostra um exemplo de formulário com vários tipos de campos para entrada de dados e um botão para submetê-los ao servidor. Na Figura 8 vemos seu resultado.

<strong>Exemplo 11. Formulário com campos</strong>

```
<form action="salvar_dados.php" method="post">
  <input type="text" placeholder="Digite aqui" /> <br/>
  <input type="checkbox" />Checkbox <br/>
  <input type="radio" />Radio button <br/>
  <input type="range" /> <br/>
  <input type="submit" value="Enviar" />
</form>
```

![2023-05-04_18h17_10](https://user-images.githubusercontent.com/88487115/236332064-e6d0ec7a-fd3e-45d5-b9b7-f32156dc13c8.png)

<strong> Formatação de texto </strong>

As tags de formatação de texto ajudam a destacar trechos da parte escrita da página, seja para fins de SEO ou por requisitos do conteúdo. Formatações como negrito e itálico podem ser aplicadas com facilidade utilizando as várias tags disponíveis para esse fim:

<ul>
  <li> <b>b</b> e <b>strong</b> para negrito/texto forte; </li>
  <li> <i>i</i> e <i>em</i> para itálico/ênfase; </li>
  <li> <sup>sup</sup> e <sub>sub</sub> para sobrescrito e subscrito, respectivamente; </li>
  <li> <ins>ins</ins> e <del>del</del> para indicar trechos que foram incluídos ou removidos, respectivamente; </li>
  <li> <small>small</small> para textos menores que o padrão; </li>
  <li> <mark>mark</mark> para texto destacado. </li>
</ul>

Apesar da tag <b>```<b>```</b> e <b>```<strong>```</b> terem resultados visualmente idênticos, eles têm usos diferentes. A tag <b>```<b>```</b> deve ser utilizada quando se quer destacar algo que é apenas visual, como por exemplo, deixar um link com mais visível. A tag <b>```<strong>```</b> por sua vez, além de destacar o visual, dá um destaque semântico ao texto, então se o conteúdo que você quer dar destaque é uma parte relevante do texto, utilize a tag <b>```<strong>```</b>. O mesmo vale para as tags <i>```<i>```</i> e <i>```<em>```</i>, onde a tag <i>```<i>```</i> é utilizada apenas para formatação visual e a tag <i>```<em>```</i> dá ênfase semântica ao texto, não devendo ser utilizada para uso puramente estético.
  
No Exemplo 12 vemos exemplos de uso dessas tags, e seu resultado pode ser observado em seguida, na Figura 9.
  
<b>Exemplo 12. Tags de formatação de texto</b>
  
```
<p>Texto em negrito com <b>bold</b> e <strong>strong</strong>.</p>
<p>Texto em itálico com <i>italics</i> e <em>emphasis</em>.</p>
<p>Texto <sup>sobrescrito</sup> e <sub>subscrito</sub>.</p>
<p>Texto <ins>inserido</ins> e <del>excluído</del>.</p>
<p>Texto <small>pequeno</small> e <mark>destacado</mark>.</p>
```
<p>Texto em negrito com <b>bold</b> e <strong>strong</strong>.</p>
<p>Texto em itálico com <i>italics</i> e <em>emphasis</em>.</p>
<p>Texto <sup>sobrescrito</sup> e <sub>subscrito</sub>.</p>
<p>Texto <ins>inserido</ins> e <del>excluído</del>.</p>
<p>Texto <small>pequeno</small> e <mark>destacado</mark>.</p>
  
<b>Áudio no HTML</b>
  
Com HTML também é possível inserir áudio e vídeo nas páginas com facilidade. Para áudio, podemos utilizar a tag audio, da mesma forma que apresentada no Exemplo 13.

<b>Exemplo 13. Inserindo áudio</b>
  
```
<audio controls src="musica.mp3" > Seu browser não suporta áudio. </audio>
```

Na tag audio, o atributo src aponta para o arquivo de áudio que será executado (MP3, OGG ou WAV). Já o atributo controls indica que devem ser exibidos os controles de gerenciamento do áudio (botões play, pause etc.). Além dele, outros também merecem destaque: autoplay, para fazer com que o áudio seja executado assim que for carregado; loop, para que o áudio seja executado repetidas vezes.
  
Caso o browser não ofereça suporte a essa tag, o texto contido eu seu interior será exibido.
  
Também podemos informar mais de um arquivo de áudio (opções alternativas de formato, por exemplo). Nesse caso, precisamos utilizar a tag source, como no exemplo do Exemplo 14.

<b>Exemplo 14. Inserindo áudio com a tag source</b>
  
```
<audio controls src="musica.mp3">
  <source src="musica.ogg" type="audio/ogg" />
  <source src="musica.mp3" type="audio/mpeg" />
</audio>
```

![2023-05-04_18h32_28](https://user-images.githubusercontent.com/88487115/236334672-f6162a13-8155-41ae-8061-e6ff729640d1.png)

<b>Video no HTML</b>

Semelhante ao áudio, também podemos inserir vídeos nas páginas HTML utilizando a tag video, adicionada na HTML5, como no exemplo:

```<video src="video.mp4" width="640" height="480" controls> Seu browser não suporta vídeo HTML5. </video>```

Dessa vez, além dos atributos já vistos no áudio, também precisamos informar a largura (width) e a altura (height) do vídeo, a fim de mantê-lo adequado ao layout.

O código abaixo pode ser utilizado quando desejarmos informar mais de um arquivo de vídeo como opções de carregamento, da mesma forma que vimos na tag audio. Nesse caso, os formatos suportados são MP4, WebM e Ogg.

```
<video width="640" height="480" controls>
  <source src="video.webm" type="video/webm" />
  <source src="video.mp4" type="video/mp4" />
</video>
```

![2023-05-04_18h36_47](https://user-images.githubusercontent.com/88487115/236335356-b5f96faf-fdc0-4c46-b1bb-87caea56e486.png)

<b>Div e Span no HTML</b>

As tags div e span são duas das mais utilizadas no HTML, com objetivos distintos, porém com grande importância para a composição do layout das páginas e formatação do texto.

As divs são normalmente utilizados para representarem containers para outros elementos, agrupando-os visualmente dentro de um bloco que pode conter dimensões e posição definidas. Por padrão, uma div não possui aparência características visuais definidas, isso precisa ser feito via CSS ao atribuir bordas, cores etc. Sua principal característica, no entanto, é que essa tag representa um elemento do tipo bloco, ou seja, que quando adicionado na página, automaticamente gera uma nova linha no layout (semelhante a um parágrafo), ao invés de ser alocado lateralmente nos demais componentes.

```
<input type="text" value="input 1">
<input type="text" value="input 2">

<div>
  <input type="text" value="input 3">
</div>

<div>
  <input type="text" value="input 4">
</div>
```

![2023-05-04_18h45_24](https://user-images.githubusercontent.com/88487115/236336774-7c2ce1e3-529c-4c69-8950-09f017607729.png)
  
Elementos span, por padrão, também não possuem nenhuma característica visual definida, isso precisa ser feito via CSS para destacar ou aplicar uma formatação especial para um certo trecho do texto. Por exemplo, o código abaixo demonstra o uso do span em dois casos. No primeiro, a tag não conta com nenhum atributo adicional; no segundo, adicionamos a ela uma aparência diferenciada via CSS.

```
<p>Este é um texto com um <span> trecho sem destaque.</span></p>
<p>
  Este é um texto com um
  <span style="background: #1abc9c; border-radius: 5px; padding: 5px">
  trecho em destaque.</span>
</p>
```
![image](https://user-images.githubusercontent.com/88487115/236337049-d866b824-0627-4d2f-b0a7-f723a11e8ffd.png)
  
