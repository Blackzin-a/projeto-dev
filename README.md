<title>PROJETO DEVELOPER</title>
<!--
    HTML= Hipertext Markup Languge
    HT= Hipertext: Hiper texto 
    M= Markup: Marcação  
    L= language: linguagem 
-->
<!-- 
    Anatomia das Tags
    - Abertura de tag
    - fechamento de tag
    - Conteúdo
    - Elementos
-->
<h1>
Projeto developer    
</h1>

<!--Elementos Vazios-->
<img src="" alt="">
<!-- Imagem nao tem conteudo só atributos-->

<!-- 
    Elementos Html
  Atributos Html
  -informações extras  
  -configurações
-->
<img src="" alt="">

 <!-- 
    Atributos Booleanos = true or false
    - Não precisam de conteúdo
 -->
 <input type="text">
 
 <!-- 
    Aspas
    - omissão
    - simples 
    - duplas 
 -->

<a href=""></a>

<!-- 
    Atributos Globais mais utilizados 
    - class
    - contenteditable
    - data-*
    - hidden
    - id
    - style
    - tabindex
    - title
-->
<div tabindex="3">
 conteudo 
</div>

<div tabindex="2">
 conteudo
</div>

<div tabindex="1">
 conteudo
</div>
<div title="titulo">

</div>

<!-- Para estudar atributos globais
  developer.mozila.org
-->

<!-- Lista dos Atributos Globais
- accesskey
- class
- contenteditable
- contextmenu
- data-*
- dir
- draggable
- dropzone
- hidden
- id
- itemid
- itemprop
- itemref
- itemtype
- lang
- spellcheck
- style
- tabindex
- title
- translate
-->

<!-- 
    Aninhamento de tags
    
    - Fluxo
    - Hierarquia
    - Posicionamento dos elementos
-->

<p>
    <a href="">AGORA</a> <br>
     vou <em>escrever</em> um parágrafo
</p>

<p> <em>Esse é um novo parágrafo</em>
</p>
<!--
    Vamos praticar

    Escrever 2 parágrafos, dando ênfase 
    e importância para algumas palavras, 
    e adicione um link de saiba mais.

    - use a tag em para ênfase
    - use a tag strong para importância
    - o link pode levar para o goole.
-->

<p>
   <a href=""> Viciado</a> em <em>Homem Aranha</em> <br>
    <strong>para saber mais leia o parágrafo abaixo
    </strong>
</p>

<p> <b> O link leva para o google</b>
</p>
<a href="https://google.com">Homem Aranha</a>
<br>
<a href="https://youtube.com">spider man</a>

<!-- 
    Conteúdo do texto e 
    caracteres reservados.
-->
<p>
    &lt;
    &quot; os espaços
    &amp; &quot;
 <br>
    que colocamos
<br>
    &apos; além das quebras de linha são ignorados &apos;
    &gt;
</p>

<!-- 
    Anatomia  de um documento HTML
-->

<!DOCTYPE html>
<html> 
    <head charset="utf-8">
        <title>Anatomia do documento</title>
    </head>

    <body>
    <p>
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. 
        Esse, hic ipsam. Quibusdam fuga dicta illo placeat in aliquam nostrum velit distinctio fugiat rem at porro, 
        earum, tempore hic sint asperiores?
    </p>
    
    </body>
</html> 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Homem Aranha</title>
</head>
<body>
    
</body>
</html>

<!--
    Semântica 

    - Dar significado
    - Elementos semânticos
-->
<!-- 
    Cabeçalhos e parágrafos
-->
 
<p>
    <h2> <b>Sobre mim</b> </h2>
    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ratione accusantium praesentium, assumenda optio fugiat explicabo. 
    Vel dignissimos voluptates, at aliquid nihil illum deleniti cumque, ab rem molestiae eaque sunt sint. 
</p> 

<p>
   <h2> <b>Nascimento</b> </h2> 
    Lorem ipsum dolor, sit amet consectetur adipisicing elit. 
    Asperiores ipsum possimus labore! Illum nemo, a nisi molestias magnam iusto sed vel earum! Nihil ipsum perspiciatis 
    quidem omnis provident iusto impedit!
</p>

<p>
    <h2><b>Saiba Mais</b></h2>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Est ipsam fuga voluptatem quos provident in. 
    Eius, qui, neque nesciunt facilis similique, 
    nulla doloremque fugit repudiandae laboriosam ipsam ratione error laborum!
</p>
<!-- 
    Listas 
    
    - ordenadas
    - não ordenadas 
-->
 <h1>Suco detox</h1>
<h2>Ingredientes:</h2>

<ul>
<li>3 folhas de colve;</li>
<li>1 laranjas;</li>
<li>1 pedaço de gengibre;</li>
<li>300ml de água;</li>
<li>Adoçante a gosto;</li>
<li>Gelo a gosto.</li>
</ul>

<!-- 
    Use ol para as ordenadas e ul para as não ordenadas
-->
<ol>
<li>3 folhas de colve;</li>
<li>1 laranjas;</li>
<li>1 pedaço de gengibre;</li>
<li>300ml de água;</li>
<li>Adoçante a gosto;</li>
<li>Gelo a gosto.</li>
</ol>

<!-- 
    Citações

    <blockquote>
    <cite>
    <q>
-->

<blockquote>
<cite><a href="https://www.marvel.com/characters/spider-man-peter-parker/in-comics/profile">Homem aranha</a></cite>
</blockquote>

<cite>
    <p>
        <a href=""https://www.marvel.com/characters/spider-man-peter-parker/in-comics/profile"">all about spider-man</a>
    </p>
</cite>

<p> O elemento quote - <code>&lt;;q&gt;;</code> - é <q
contenteditable=""https://www.marvel.com/characters/spider-man-peter-parker/in-comics/profile"> 
usado para citações curtas que não precisam de parágrafos ou quebras de linha.
</q> -- <a href=""https://www.marvel.com/characters/spider-man-peter-parker/in-comics/profile"">
<cite> MDN q Page</cite></a><div class=""https://www.marvel.com/characters/spider-man-peter-parker/in-comics/profile""></div></div></p>

<!-- 
    Abreviações

    <abbr>
-->

<p>Usamos <abbr title="Hypertext Markup Language">HTML</abbr> para estruturar nossos
documentos da web.</p>

<!-- 
    Detalhes de Contato

    <address>
-->

<address>
    <p>Mayk Brito <br>
    <strong> Campo Grande, MS</strong>
</p>
</address>

<!--
    Listas de descrição

    <dl>
        <dl></dt>
        <dd></dd>
    </dl>
-->

<h2>Glossário</h2>
<dl>
    <dt>Hypertext</dt>
    <dd>É um hipertexto com possibilidades...</dd>
    
    <dt>Markup</dt>
    <dd>Marcação de texto</dd>

    <dt>Language</dt>
    <dd>Linguagem com sua semântica e sintaxe...</dd>
</dl>

<!-- 
    Representando códigos de computador 

    <code>
        Partes genéricas de código

    <pre>
        Blocos de código, pois essa tag mantém os espaços em brancos e recuos que eu colocar no meu código
-->

<pre>
    <code>
&lt; document.queryselector("body")&gt;  
</code>
</pre>

<!--
    Elementos Genéricos

    * <div>
    * <span>
-->

<div class="cart">
    <span>Camiseta</span>
    <span>r$ 99,00</span>
</div>
<!--
    Hyperlinks - Elemento Âncora: <a>
    
    + Anatomia

    +Atributos:
         - globais
         - href
           - para onde o iremos, quando clicarmos no link?
            - url completa
            - fragmento
            - email
            - telefone
            - e outros
        - dowload
        - target
            -_self (padrão) - nao abre uma nova pagina
            -_blank - abre uma nova pagina
-->

<a href="https://google.com" target="_blank">Conteúdo</a>

<p> Encontre-me:</p>
    <ul>
        <li><a href="https://google.com" target="_blank">Website</a></li>
        <li><a href="mailto:vinigamexd12@gmail.com" target="_blank">Gmail</a></li>
        <li><a href="tel:+5521972104348" target="_blank">Telefone</a></li>
    </ul>


<p>Saiba Mais</p>
<ul>
    <li><a href="#about">Sobre mim</a></li>
    <li></li><a href="#History">História</a>
    <li></li><a href="#works">Trabalhos</a>
</ul>

<h1 id="about">Sobre mim</h1>
Lorem ipsum dolor sit amet consectetur adipisicing elit. Et fugiat optio omnis obcaecati temporibus reiciendis cumque sed mollitia accusantium earum perspiciatis minima iure atque blanditiis eius voluptas, repellendus voluptatibus eum.

<h2 id="History">História</h2>
Lorem, ipsum dolor sit amet consectetur adipisicing elit. Aliquam placeat cupiditate nostrum voluptate assumenda sed. Est quibusdam voluptatibus obcaecati necessitatibus, rem amet dolor? Suscipit fugit et praesentium fugiat corrupti ab.

<h2 id="works">Trabalhos</h2>
Lorem, ipsum dolor sit amet consectetur adipisicing elit. Optio ut voluptatem quisquam odio dolor numquam eligendi tempore. Eligendi maxime doloremque similique, porro nulla, officiis delectus quis dolor facere dignissimos sit!

<!--
    Conteúdo dos hyperlinks

    - qualquer conteúdo
-->

<p>
<a href="https://google.com" target="_blank" title="Ir para google"> <h1>Google</h1>
<p>Claro que posso</p>
<img src="https://source.unsplash.com/random" alt="">
</a>
</p>

<!--
    URLs e Caminhos dos arquivos

    - Uniform Resource Locator
      - https://www.rocketseat.com.br
      - Sêquencia de texto que define onde algo está localizado na Web
    - URL usam caminhos para encontrar arquivos

    - Caminhos dos arquivos
      - Onde, no explorador de arquivos, um recurso está localizado
-->

<a href="index.html" target="_blank">Abrir HTML</a>

<!--
    Como navegar pelos caminhos?

    - mesmo diretório 
    - entrando em diretórios
    - saindo de diretórios
    - diretório raiz (root ou pai)
-->

<br>
<a href="outros/lalala.html"> Abrir na pasta outros</a>
<br>
<a href="../subpasta/lalala2.html"> Abrir lalala2</a>
<br>
<a href="./index.html"> Abrir No diretorio raiz</a>

<!--
    URLs absolutos versus relativos

    - Absolutos
     - inclui protocolo e nome de domínio
       - http://www/rocketseat.com.br/projeto/index.html
     - sempre apontará para o mesmo local, pois é absoluto

    - Relativos
      - relativo à página aberta no momento
      - apontará para lugares diferentes
      obs: o relativo é referente à pasta 
-->
<br>
<br>
<a href="google.com">relativo: ir para o google</a>
<a href="https://google.com">absoluto: ir para o google</a>

<!-- 
    <head>
-->

<head>
    <meta charset="utf-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="shortcut icon" href="favicon.ico" type="Image/x-icon">
 </head>


 <!DOCTYPE html>
 <html lang="en">
 <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
 </head>
 <body>
    
<h1 style="color: blue;">
    Título
    <strong style="color: red;">alo</strong>
</h1>


 </body>
 </html>
 
