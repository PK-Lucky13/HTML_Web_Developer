<h1> HTML Web Developer </h1>
<p>Formação HTML Web Developer<br>
Projeto -> https://github.com/PK-Lucky13/HTML_Web_Developer/blob/main/atividade.html</p>
  <h2><b><a id="indice">Índice</a></b></h2>
  <ol>
    <li><a href="#tags">Tags em HTML</a></li>
    <li><a href="#criando">Criando uma página</a></li>
    <li><a href="#salvar">Salvar a página HTML</a></li>
    <li><a href="#cabecalhos">Cabeçalhos do HTML</a></li>
    <li><a href="#paragrafos">Parágrafos no HTML</a></li>
    <li><a href="#imagens">Imagens no HTML</a></li>
    <li><a href="#links">Links no HTML</a></li>
    <li><a href="#tabelas">Tabelas no HTML</a></li>
    <li><a href="#listas">Listas no HTML</a></li>
    <li><a href="#formularios">Formulários no HTML</a></li>
    <li><a href="#formatacao">Formatação de texto</a></li>
    <li><a href="#audio">Áudio no HTML</a></li>
    <li><a href="#video">Video no HTML</a></li>
    <li><a href="#ds">Div e Span no HTML</a></li>
  </ol>
  <h2>O que é HTML?</h2>
  <ul>
    <li>HTML é a linguagem de marcação padrão para criar páginas da Web</li>
    <li>HTML significa Hyper Text Markup Language</li>
    <li>HTML descreve a estrutura de uma página da Web</li>
    <li>HTML consiste em uma série de elementos</li>
    <li>Os elementos HTML informam ao navegador como exibir o conteúdo</li>
    <li>Os elementos HTML são representados por tags</li>
    <li>As tags HTML rotulam partes do conteúdo, como "cabeçalho", "parágrafo", "tabela" e assim por diante</li>
    <li>Os navegadores não exibem as tags HTML, mas as usam para renderizar o conteúdo da página</li>
  </ul>
<p><code>&lt;!DOCTYPE html&gt;</code></p>
<p><img src="https://user-images.githubusercontent.com/88487115/236156493-4cffdd61-2852-4ba5-8f98-2ed5803b4ace.png"></p>
<p><h3>Exemplo explicado</h3></p>
<ul>
  <li>A declaração &lt;!DOCTYPE html&gt; define este documento como HTML5</li>
  <li>&lt;html&gt; é o elemento raiz de uma página HTML</li>
  <li>&lt;head&gt; contém meta informações sobre o documento</li>
  <li>&lt;title&gt; especifica um título para o documento</li>
  <li>&lt;body&gt; contém o conteúdo da página visível</li>
  <li>&lt;h1&gt; ~ &lt;h6&gt; definem cabeçalhos</li>
  <li>&lt;p&gt; define um parágrafo</li>
</ul>
<hr>
<p><h3><a id="tags"> Tags em HTML </a>
<small><sup><a href="#indice">Índice</a></sup></small></h3></p>
<p>Tags HTML são nomes que pertencem aos elementos entre colchetes e que delimitam a abertura e o encerramento de uma marcação, por exemplo:</p>
<p><b>&lt;tag de abertura&gt; o conteúdo que você deseja exibir entra aqui ... &lt;/tag de fechamento&gt;</b></p>
<ul>
  <li>Observe que as tags HTML normalmente vêm em pares como &lt;p&gt; e &lt;/p&gt;</li>
  <li>A primeira tag em um par é a tag inicial, a segunda tag é a tag final</li>
  <li>A tag final é escrita como a tag inicial, mas com uma barra inserida antes do nome da tag</li>
</ul>
<hr>
<h3><a id="criando"> Criando uma página </a><small><sup><a href="#indice">Índice</a></sup></small></h3>
<pre>
  <code>
  &lt;!DOCTYPE html>
  &lt;html lang="pt-br">
    &lt;head>
      &lt;meta charset="UTF-8" />
      &lt;title>Meu primeiro site&lt;/title>
    &lt;/head>
    &lt;body>
      &lt;h1>Meu primeiro cabeçalho&lt;/h1>
      &lt;p>Meu primeiro parágrafo.&lt;/p>
      &lt;p>Meu segundo parágrafo.&lt;/p>
    &lt;/body>
  &lt;/html>
  </code>
</pre>
<hr>
<h3><a id="salvar"> Salvar a página HTML </a><small><sup><a href="#indice">Índice</a></sup></small></h3>
<p>Nomeie o arquivo "index.html" e defina a codificação para UTF-8 (que é a codificação preferida para arquivos HTML).</p>
<p><img src="https://user-images.githubusercontent.com/88487115/236164217-08cca386-776f-4c08-9550-03e9f9d102a5.png"></p>
<p>Você pode usar .htm ou .html como extensão de arquivo, não há diferença.</p>
<hr>
<h3><a id="cabecalhos"> Cabeçalhos do HTML </a><small><sup><a href="#indice">Índice</a></sup></small></h3>
<p>Cabeçalhos são normalmente utilizados para identificar páginas e seções e possuem aparência diferenciada do restante do texto. No HTML há seis níveis de cabeçalhos/títulos que podem ser utilizados por meio das tags h1, h2, h3, h4, h5 e h6, sendo h1 o maior/mais relevante e h6 o menor/menos relevante. De acordo com as regras de SEO, é recomendado que uma página possua apenas uma tag &lt;h1> que indique seu assunto, pois essa tag informa aos motores de busca qual sua principal palavra-chave.</p>
<hr>
<h3><a id="paragrafos"> Parágrafos no HTML </a><small><sup><a href="#indice">Índice</a></sup></small></h3>
<p>Parágrafos de texto são gerados na HTML por meio das tags &lt;p> e &lt;/p>. Esse é um exemplo de tag cuja disposição na tela se dá em forma de bloco, ou seja, um parágrafo é posto sempre abaixo do outro.</p>
<hr>
<h3><a id="imagens"> Imagens no HTML </a><small><sup><a href="#indice">Índice</a></sup></small></h3>
<p>A inserção de imagens em uma página HTML pode ser feita por meio da tag img, que recebe no atributo src o endereço do arquivo a ser carregado. Além desse, outros dois atributos importantes são o alt, que indica um texto alternativo que será exibido caso o arquivo não possa ser carregado, e title, que indica o texto que aparecerá como tooltip ao passar o mouse sobre a figura.</p>
<pre>
  <code>
  &lt;img src="exemplo.png" alt="Texto alternativo" title="Imagem" />
  </code>
</pre>
<p>No caso da tag img, ainda temos as tags figure e figcaption:</p>
<pre>
  <code>
  &lt;figure>
    &lt;img src="http://meusite.com.br/assets/imagem.jpg" alt="Imagem" />
    &lt;figcaption> Legenda da figura 1 &lt;/figcaption>
  &lt;/figure>
  </code>
</pre>
<hr>
<h3><a id="links"> Links no HTML </a><small><sup><a href="#indice">Índice</a></sup></small></h3>
<p>Links são normalmente utilizados para direcionar o usuário para outras páginas, ou para outras partes da mesma página. Nos dois casos, utilizamos a tag a, que possui o atributo href no qual indicamos o destino daquele link.</p>
<pre><code> &lt;a href="pagina2.html">Página 2&lt;/a></code></pre>
<p>Já o exemplo abaixo mostra como adicionar uma âncora para um elemento na mesma página. Nesse caso, ao clicar no link o browser mudará o foco para o elemento que possui o atributo id igual àquele indicado no href.</p>
<pre>
  <code> 
  &lt;a href="#paragrafo3">Ir para o parágrafo 3&lt;/a>
  &lt;!--outros elementos-->
  &lt;p id="paragrafo3">Parágrafo no rodapé.&lt;/p>
  </code>
</pre>
<hr>
<h3><a id="tabelas"> Tabelas no HTML </a><small><sup><a href="#indice">Índice</a></sup></small></h3>
<p>Tabelas são elementos utilizados com frequência para exibir dados de forma organizada em linhas e colunas. No HTML, elas são formadas por três tags básicas:</p>
<ul>
  <li>&lt;table> para delimitar a tabela;</li>
  <li>&lt;tr> para indicar as linhas;</li>
  <li>&lt;td> para formar as colunas.</li>
</ul>
<p>O exemplo a seguir mostra um exemplo simples de tabela com três linhas e duas colunas, e seu resultado pode ser visto na figura abaixo.</p>
<pre>
  <code>
  &lt;table>
    &lt;tr>
      &lt;td>Linha 1, Coluna 1&lt;/td>
      &lt;td>Linha 1, Coluna 2&lt;/td>
    &lt;/tr>
    &lt;tr>
      &lt;td>Linha 2, Coluna 1&lt;/td>
      &lt;td>Linha 2, Coluna 2&lt;/td>
    &lt;/tr>
    &lt;tr>
      &lt;td>Linha 3, Coluna 1&lt;/td>
      &lt;td>Linha 3, Coluna 2&lt;/td>
    &lt;/tr>
  &lt;/table>
  </code>
</pre>
<p>Saída:</p>
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
<p>Existem ainda outras três tags utilizadas para delimitar, de forma mais organizada, as partes da tabela:</p>
<ul>
  <li>thead para o cabeçalho;</li>
  <li>tbody para o corpo;</li>
  <li>tfoot para o rodapé.</li>
</ul>
<p>O próximo exemplo traz uma tabela mais complexa, utilizando todas as tags. Seu resultado é apresentado na figura abaixo.</p>
<pre>
  <code>
  &lt;table>
    &lt;thead>
      &lt;tr>
        &lt;th> Produto &lt;/th>
        &lt;th> Preço &lt;/th>
        &lt;th> Quantidade &lt;/th>
      &lt;/tr>
    &lt;/thead>
    &lt;tbody>
      &lt;tr>
        &lt;td> Feijão &lt;/td>
        &lt;td> R$ 8,75 &lt;/td>
        &lt;td> 1 &lt;/td>
      &lt;/tr>
      &lt;tr>
        &lt;td> Arroz &lt;/td>
        &lt;td> R$ 4,99 &lt;/td>
        &lt;td> 2 &lt;/td>
      &lt;/tr>
    &lt;/tbody>
    &lt;tfoot>
      &lt;tr>
        &lt;td> Total &lt;/td>
        &lt;td>&lt;/td>
        &lt;td> R$ 18,73 &lt;/td>
      &lt;/tr>
    &lt;/tfoot>
  &lt;/table>
  </code>
</pre>
<p>Saída:</p>
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
      <td>........1</td>
    </tr>
    <tr>
      <td>Arroz</td>
      <td>R$ 4,99</td>
      <td>........2</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td>Total</td>
      <td>=></td>
      <td>R$ 18,73</td>
    </tr>
  </tfoot>
</table>
<p>Por padrão, as tabelas não possuem bordas. Isso deve ser adicionado por meio das CSS.</p>
<hr>
<h3><a id="listas"> Listas no HTML </a><small><sup><a href="#indice">Índice</a></sup></small></h3>
<p>Listas são elementos úteis para organizar e ordenar itens que estão relacionados de alguma forma. No HTML é possível criar três tipos de listas:</p>
<ul>
  <li>ordenadas (com a tag ol)</li>
  <li>não ordenadas (com a tag ul)</li>
  <li>de definição (por meio da tag dl)</li>
</ul>
<p>No Exemplo 8 temos um exemplo de lista ordenada, enquanto o Exemplo 9 traz um exemplo de lista não ordenada. Em seguida, a Figura 6 mostra o resultado dos dois códigos. Observe que cada item das primeiras listas é definido pela tag li.</p>
<p><b>Exemplo 8. Lista ordenada</b></p>
<pre>
  <code>
  &lt;ol>
    &lt;li>Item 1&lt;/li>
    &lt;li>Item 2&lt;/li>
    &lt;li>Item 3&lt;/li>
  &lt;/ol>
  </code>
</pre>
<p><b>Exemplo 9. Lista não ordenada</b></p>
<pre>
  <code>
  &lt;ul>
    &lt;li>Item 1&lt;/li>
    &lt;li>Item 2&lt;/li>
    &lt;li>Item 3&lt;/li>
  &lt;/ul>
  </code>
</pre>
<p><b>Figura 6. Listas ordenada e não ordenada</b></p>
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
<p>No caso das listas ordenadas temos o atributo type que permite especificar o tipo de marcador a ser usado: números (padrão), números romanos ou letras.</p>
<p><b>8.1. Lista ordenada por número romano maiúsculo</b></p>
<pre>
  <code>
  &lt;ol type="I">
    &lt;li>Item 1&lt;/li>
    &lt;li>Item 2&lt;/li>
    &lt;li>Item 3&lt;/li>
  &lt;/ol>
  </code>
</pre>
<p>Saída:</p>
<ol type="I">
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ol>
<p>Os valores permitidos para esse atributo são:</p>
<ul>
  <li>1 - números (padrão)</li>
  <li>i - números romanos minúsculos</li>
  <li>I - números romanos maiúsculos</li>
  <li>a - letras minúsculas</li>
  <li>A - letras maiúsculas</li>
</ul>
<p>As listas de definição têm um comportamento um pouco diferente, uma vez que cada item é composto por um título (dt) e uma definição (dd), semelhante ao que ocorre em dicionários, nos quais temos os verbetes e suas definições.</p>
<pre>
  <code>
  &lt;dl>
    &lt;dt> Título 1 &lt;/dt>
    &lt;dd> Definição 1 &lt;/dd>
    &lt;dt> Título 2 &lt;/dt>
    &lt;dd> Definição 2 &lt;/dd>
    &lt;dt> Título 3 &lt;/dt>
    &lt;dd> Definição 3 &lt;/dd>
  &lt;/dl>
  </code>
</pre>
</p>Saída:</p>
<dl>
  <dt>Título 1</dt>
  <dd>Definição 1</dd>
  <dt>Título 2</dt>
  <dd>Definição 2</dd>
  <dt>Título 3</dt>
  <dd>Definição 3</dd>
</dl>
<hr>
<h3><a id="formularios"> Formulários no HTML </a><small><sup><a href="#indice">Índice</a></sup></small></h3>
<p>Formulários são normalmente utilizados para integrar a página HTML a algum processamento no lado servidor. Nesses casos, a página envia dados para uma aplicação (Java, PHP, .NET etc.), que os recebe, trata e retorna algum resultado.<br>
No HTML, geralmente usamos a tag form para delimitar a área na qual se encontram os campos a serem preenchidos pelo usuário, a fim de serem enviados para processamento no back-end (enquanto a página HTML é chamada de front-end da aplicação).<br>
O Exemplo 11 mostra um exemplo de formulário com vários tipos de campos para entrada de dados e um botão para submetê-los ao servidor. Na Figura 8 vemos seu resultado.</p>
<p><b>Exemplo 11. Formulário com campos</b></p>
<pre>
  <code>
  &lt;form action="salvar_dados.php" method="post">
    &lt;input type="text" placeholder="Digite aqui" /> &lt;br/>
    &lt;input type="checkbox" />Checkbox &lt;br/>
    &lt;input type="radio" />Radio button &lt;br/>
    &lt;input type="range" /> &lt;br/>
    &lt;input type="submit" value="Enviar" />
  &lt;/form>
  </code>
</pre>
<p>Saída:</p>

![2023-05-04_18h17_10](https://user-images.githubusercontent.com/88487115/236476302-64ba7745-36ea-4602-9759-fa494e7551a0.png)

<hr>
<h3><a id="formatacao"> Formatação de texto </a><small><sup><a href="#indice">Índice</a></sup></small></h3>
<p>As tags de formatação de texto ajudam a destacar trechos da parte escrita da página, seja para fins de SEO ou por requisitos do conteúdo. Formatações como negrito e itálico podem ser aplicadas com facilidade utilizando as várias tags disponíveis para esse fim:</p>
<ul>
  <li> <b>b</b> e <b>strong</b> para negrito/texto forte; </li>
  <li> <i>i</i> e <i>em</i> para itálico/ênfase; </li>
  <li> <sup>sup</sup> e <sub>sub</sub> para sobrescrito e subscrito, respectivamente; </li>
  <li> <ins>ins</ins> e <del>del</del> para indicar trechos que foram incluídos ou removidos, respectivamente; </li>
  <li> <small>small</small> para textos menores que o padrão; </li>
  <li> <mark>mark</mark> para texto destacado. </li>
</ul>
<p>Apesar da tag <b>&lt;b></b> e <b>&lt;strong></b> terem resultados visualmente idênticos, eles têm usos diferentes. A tag <b>&lt;b></b> deve ser utilizada quando se quer destacar algo que é apenas visual, como por exemplo, deixar um link com mais visível. A tag <b>&lt;strong></b> por sua vez, além de destacar o visual, dá um destaque semântico ao texto, então se o conteúdo que você quer dar destaque é uma parte relevante do texto, utilize a tag <b>&lt;strong></b>. O mesmo vale para as tags <i>&lt;i></i> e <i>&lt;em></i>, onde a tag <i>&lt;i></i> é utilizada apenas para formatação visual e a tag <i>&lt;em></i> dá ênfase semântica ao texto, não devendo ser utilizada para uso puramente estético.
No Exemplo 12 vemos exemplos de uso dessas tags, e seu resultado pode ser observado em seguida, na Figura 9.</p>
<p><b>Exemplo 12. Tags de formatação de texto</b></p>

![2023-05-05_10h51_04](https://user-images.githubusercontent.com/88487115/236477307-ed50f614-f092-4293-b31f-c6086ccb2880.png)

<br>
<hr>
<h3><a id="audio"> Áudio no HTML </a><small><sup><a href="#indice">Índice</a></sup></small></h3>
<p>Com HTML também é possível inserir áudio e vídeo nas páginas com facilidade. Para áudio, podemos utilizar a tag audio, da mesma forma que apresentada no Exemplo 13.</p>
<p><b>Exemplo 13. Inserindo áudio</b></p>
<pre>
  <code>
  &lt;audio controls src="musica.mp3" > Seu browser não suporta áudio. &lt;/audio>
  </code>
</pre>
<p>Na tag audio, o atributo src aponta para o arquivo de áudio que será executado (MP3, OGG ou WAV). Já o atributo controls indica que devem ser exibidos os controles de gerenciamento do áudio (botões play, pause etc.). Além dele, outros também merecem destaque: autoplay, para fazer com que o áudio seja executado assim que for carregado; loop, para que o áudio seja executado repetidas vezes.</p>
<p>Caso o browser não ofereça suporte a essa tag, o texto contido eu seu interior será exibido.</p>
<p>Também podemos informar mais de um arquivo de áudio (opções alternativas de formato, por exemplo). Nesse caso, precisamos utilizar a tag source, como no exemplo do Exemplo 14.</p>
<p><b>Exemplo 14. Inserindo áudio com a tag source</b></p>
<pre>
  <code>
  &lt;audio controls src="musica.mp3">
    &lt;source src="musica.ogg" type="audio/ogg" />
    &lt;source src="musica.mp3" type="audio/mpeg" />
  &lt;/audio>
  </code>
</pre>
<p>Saída:</p>

![2023-05-04_18h32_28](https://user-images.githubusercontent.com/88487115/236477450-5bbd306d-50cd-46c5-8d16-6e5a361b1c85.png)

<h3><a id="video"> Video no HTML </a><small><sup><a href="#indice">Índice</a></sup></small></h3>
<p>Semelhante ao áudio, também podemos inserir vídeos nas páginas HTML utilizando a tag video, adicionada na HTML5, como no exemplo:</p>
<pre>
  <code>
  &lt;video src="video.mp4" width="640" height="480" controls> Seu browser não suporta vídeo HTML5. &lt;/video>
  </code>
</pre>
<p>Dessa vez, além dos atributos já vistos no áudio, também precisamos informar a largura (width) e a altura (height) do vídeo, a fim de mantê-lo adequado ao layout.</p>
<p>O código abaixo pode ser utilizado quando desejarmos informar mais de um arquivo de vídeo como opções de carregamento, da mesma forma que vimos na tag audio. Nesse caso, os formatos suportados são MP4, WebM e Ogg.</p>
<pre>
  <code>
  &lt;video width="640" height="480" controls>
    &lt;source src="video.webm" type="video/webm" />
    &lt;source src="video.mp4" type="video/mp4" />
  &lt;/video>
  </code>
</pre>
<p>Saída:</p>

![2023-05-04_18h36_47](https://user-images.githubusercontent.com/88487115/236478973-2223d32c-7157-44d4-94c9-9a8d3d5b3a4e.png)

<br><br>
<hr>
<h3><a id="ds"> Div e Span no HTML </a><small><sup><a href="#indice">Índice</a></sup></small></h3>
<p>As tags div e span são duas das mais utilizadas no HTML, com objetivos distintos, porém com grande importância para a composição do layout das páginas e formatação do texto.</p>
<p>As divs são normalmente utilizados para representarem containers para outros elementos, agrupando-os visualmente dentro de um bloco que pode conter dimensões e posição definidas. Por padrão, uma div não possui aparência características visuais definidas, isso precisa ser feito via CSS ao atribuir bordas, cores etc. Sua principal característica, no entanto, é que essa tag representa um elemento do tipo bloco, ou seja, que quando adicionado na página, automaticamente gera uma nova linha no layout (semelhante a um parágrafo), ao invés de ser alocado lateralmente nos demais componentes.</p>
<pre>
  <code>
  &lt;input type="text" value="input 1">
  &lt;input type="text" value="input 2">
  &lt;div>
    &lt;input type="text" value="input 3">
  &lt;/div>
  &lt;div>
    &lt;input type="text" value="input 4">
  &lt;/div>
  </code>
</pre>
<p>Saída:</p>

![2023-05-05_11h03_32](https://user-images.githubusercontent.com/88487115/236479791-2db951f1-ea94-4b5f-ac1a-ade0630cc098.png)

<p>Elementos span, por padrão, também não possuem nenhuma característica visual definida, isso precisa ser feito via CSS para destacar ou aplicar uma formatação especial para um certo trecho do texto. Por exemplo, o código abaixo demonstra o uso do span em dois casos. No primeiro, a tag não conta com nenhum atributo adicional; no segundo, adicionamos a ela uma aparência diferenciada via CSS.</p>
<pre>
  <code>
  &lt;p>Este é um texto com um &lt;span> trecho sem destaque.&lt;/span>&lt;/p>
  &lt;p>Este é um texto com um &lt;span style="background: #1abc9c; border-radius: 5px; padding: 5px">trecho em destaque.&lt;/span>&lt;/p>
  </code>
</pre>
<p>Saída:</p>

![2023-05-05_10h51_13](https://user-images.githubusercontent.com/88487115/236479536-4779ed1c-e7df-48b9-baef-57e3310d2ecf.png)
