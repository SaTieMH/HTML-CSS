## <ins>Capítulo 1</ins>
------------------------------------------------
### Resumo de algumas marcações - Aula 1
```<h1>``` ````</h1>```` - marcação de título <!--<h1></h1>-->

```<p>``` ``</p>`` - parágrafo <!--<p></p>-->

```<hr>``` - linha horizontal <!--<hr>-->

------------------------------------------------
### Resumo de algumas marcações - Aula 2
```<br>``` - break row <!--<br>-->

```&lt;``` (Less Than)

```&gt;``` (Greater Than)

------------------------------------------------
### Resumo de algumas marcações - Aula 3
```<!-- -->``` - Comentário

Símbolos: misc simbols

Emoji: emojipedia - codepoints

------------------------------------------------
### Imagens e direitos autorais - Aula 4
Como procurar isso no Google
 - Ferramentas > marcadas para reutilização com modificação

##### Outros sites:
 - Unsplash
 - Pexels

##### Ferramenta para edição de arquivos:
 - GIMP

------------------------------------------------
### Foramtos de imagens na web - Aula 5
 - .jpeg (melhor formato de compactação, realiza comparação de pixels próximos, não tem suporte a transparência)
 - .png (permite transparência, além de ter qualidade melhor, porém mais pesado)

Dependendo do que for precisar, sempre lembrando que é importante que a imagem não seja pesada para que o site não demore para carregar. [ex: arquivos de 20M já são muito pesados dependendo da sua internet]

Busca de imagem de fundo: Grande e .jpeg

Busca de imagem de logo (transparente): Transparente (será .png)

------------------------------------------------
### Tamanho das imagens para o site - Aula 6
Você pode alterar a dimensão da imagem no site, mas o tamanho dela não é alterado, portanto, por mais que a imagem esteja pequena no site, pode ser que esteja deixando o site muito lento. Sendo assim faça imagens de no máximo 1500 de largura.

Gimp > upload image > Imagem > Redimensionar imagem... > Tamanho da imagem-Largura: 1500 (ou menor) px e Resolução entre 50 e 72 pixels/in > Redimensionar > Export As... > Qualidade: 70% > Export

Obs: Não sobrescreva sua imagem original. -full, -1500, -1200 ...

Dimensões recomendadas (largura):
 - 1200 para fundo
 - 650 para inserir no meio do conteúdo
 - < 400 para logo
 - 200 para rodapé

------------------------------------------------
### Tage img - Aula 7 [exercício 3]
Ctrl + Enter = abre lista com possibilidade de imagens a serem incluídas.

É possível carregar imagens da própria pasta, de sub pastas e de outros links (externas)

------------------------------------------------
### Como mudar o favicon de um site - Aula 8 [exercício 4]
Imagens que não tenham muito detalhe para transformar em .ico

 - iconarchive.com - ícones para fazer download
 - favicon.cc - é possível desenhar seu favicon
 - favicon.io - text to icon, png to icon, emoticon to icon

Digita link:favicon para adicionar o favicon

------------------------------------------------
### Hierarquia de Títulos - Aula 9 [exercício 6]
##### Desvinculando tamanho do título com Hierarquia!
Importante é eu ordenar de maneira que minha hierarquia fique clara e ordenada. Com relação ao tamanho das letras eu vou realizar as alterações de tamanho (fonte, cor e outros) quando for mexer nos estilos (css).

------------------------------------------------
### Semântica an HTML5 é importante - Aula 10 [exercício 7]
Semântica = Significado dos vocábulos, por oposição a sua forma

Existem algumas tags que passaram a fica obsoletas (transição entre html4 e html5)

Antes, em html4 a forma do texto ficava dentro do código. Agora com o html5 o estilo/forma fica reservado para as folhas de estilo (css) e o html ficou com as tags semânticas (de significado).

Por exemplo, alterar a cor de fundo ou das letras, sublinhar, negritar e dar outras formas hoje deve ser feito no css.

------------------------------------------------
### Negrito e Itálico do jeito certo - Aula 11 [exercício 8]
Negrito e Itálico - Existem duas maneiras de colocar o negrito, de maneira semântica ou não semântica
 - Não Semântica: utilizando a tag ```<b>```. Ela possui apenas forma.
 - Semântica: utilizando 

 obs: Ctrl + Shift + p => Abre barra para atalho (wrap with abbreviation)

###### Recomendação
Pare de utilizar as tags ```<b>``` e ```<i>```. Passe a utilizar ```<strong>``` e ```<em>```.

------------------------------------------------
### Formatações adicionais em HTML - Aula 12
style utilizado em mark serve para mudar a cor (forma) do marcado. O mardo trata-se de uma semântica

Para que todos os mark herdem as características de modança de cor é necessário criar um estilo padrão que será aplicado a todos dentro da tag \<style>

```<big>``` e ```<small>```
```<del>``` , ```<ins>``` , ```<u>``` , ```<sup>``` , ```<sub>```

------------------------------------------------
### Citações e Códigos - Aula 13 [exercício 8-b]
Formatação para código fonte ```<code>``` pois faz com que as letras sejam monoespaçadas, facilitando a leitura do código.

```<pre>``` permite que eu formate o que estiver dentro dessa tag

```<q>``` Não apenas inclui as aspas, mas também dá o sentido de uma citação (quotetion)

```<blockquote cite=siteDeReferencia>``` Quebra de linha e deslocamento horizontal a direita

```<abbr title="O que significa a abreviação">``` Para abreviações

```<bdo dir="ltr">``` (left to rigth) ou ```<bdo dir=rtl>``` (rigth to left) Inverte o texto

------------------------------------------------
### Listas OL e UL - Aula 14 [exercício 9]
```<ol>```: Ordenated list - Ordena os itens da lista e coloca numeração na frente
 - Posso colocar o 'type' e o 'start' em ol
 -> ex: type="1" start="4" significa que é do tipo numérica e começa no índice 4
 - Posso alterar as variáveis type (1, a, A, i, I) e start (qualquer valor)

```<ul>```: Unordenated list - Tópicos sem numeração
 - Posso usar 'type' (circle, disc, square), sendo circle o padrão

```<li>```: List Item. Obs: a partir do html5 o ```</li```> se tornou opcional

Obs: Geralmente os menus são feitos com listas

------------------------------------------------
### Listas mistas e de definição - Aula 15
Dica: Segura Ctrl e vai colocando o cursor onde deseja e serão "colocados" vários cursores em pontos diferentes para poder alterar mais de um ponto de uma vez

```<dl>```: difinition list - Como se fosse um dicionário. Compost por:
 - ```<dt>```: Termo
 - ```<dd>```: Definição
As definições possuem um espaçamento, mas que podem ser modificadas depois na CSS

Sites que possuem esse tipo de "dicionário" são melhor colocados pelos sites de busca, apesar dela ser bem menos utilizada do que as listas apresentadas anteriormente.

Importante aprender sobre isso por que será utilizado para menu

------------------------------------------------
### Links e Âncoras em HTML - Aula 16 [exercício 10]
Todo link é construído através de uma âncora (ponto clicável) no HTML

SEO - Seraching Engine Organization
```html
    <a href= "link para sites externos" target="_blank" rel="external">
```
 - Quando for direcionar para um link externo é recomendado que adicione o target o rel para que abra uma nova aba e não sobrescreva àquela que estava navegando anteriormente.

------------------------------------------------
### Links internos - Aula 17
Link realiza a ligação com outra página que está dentro do nosso servidor e que condiz com a nossa própria página

Criar outro arquivo html para ser sua nova página.

rel: possui uma semântica por trás que envolve o significado/valor
 - rel="nofollow" (para links patrocinados) quando não quero que o mecnismo de busca perpetue essa busca. Isso serve para o macnismo de busca e não para a pessoa que está visitando o conteúdo.
 - target="_self" para páginas internas e "_blank" para externas

------------------------------------------------
### Links para download - Aula 18
Enquanto não tiver link para ser colocado href="#"

iana.org/assignments/media-types: lista com todos os media types

------------------------------------------------
### Desafios propostos - Aula 19
Realização dos desafios propostos (d005 e d006)

------------------------------------------------
### Imagens Dinâmicas - Aula 20
Para que as imagens se adequem ao tamanho da tela que o usuário está utilizando.

Criei 3 tamanhos de imagens (P-celular, M-tablet, G-pc ou monitor)

------------------------------------------------
### Imagens que se adaptam sozinhas - Aula 21 [exercício 11]
 - Permite crie vários sources
 ```html
    <picture>
        <source media="(min-width: 1050px)" srcset="imagens/foto-g.png" type="image/png">
        <source media="(min-width: 720px)" srcset="imagens/foto-m.png" type="image/png">
        <img src="imagens/foto-p.png" alt="Imagem flexível">
    </picture>
 ```

Se o tamanho máximo da tela for de 1050px (a imagem tem 1000px), vai deixar de apresentar a imagem que está (foto-g.png) e passa a mostrar a "foto-m.png". Além do type="image/png"

A mesma coisa para caso diminua mais ainda o tamanho da tela e quero que mostre a foto-p.png

------------------------------------------------
### Colocando áudio no seu site - Aula 22
Sempre ficar atento a DIREITOS AUTORAIS!!!
```html
    <audio src="midias/happy-mistake.mp3" autoplay controls></audio>
```
```html
    <audio preload="metadata" controls>
        <source src="midias/guanacast-33.mp3" type="audio/mpeg">
        <source src="midias/guanacast-33.ogg" type="audio/ogg">
        <source src="midias/guanacast-33.wav" type="audio/wav">
        <p>Infelizmente seu navegador não consegue reproduzir este áudio. <a href="midias/guanacast-33.mp3">cClique aqui</a> para baixar o arquivo MP3.</p>
    </audio>
```

Existem muitos navegadores que não possuem compatibilidade com alguns formatos de áudio, como .mp3, por exemplo. Geralmente são utilizados os formatos .mp3, .wav e .ogg

Outra maneira de adicionar áudio é adicionando sources dentro de audio.
 - type="audio/mpeg" - para formato mp3
 - type="audio/ogg" - para formato ogg
 - type="audio/wav" - para formato wav
 - Mas para isso é necessário que você tenha todos esses formatos de áudio na pasta

Se nenhum desses for compatível com o navegador, não será reproduzido nenhum som.

Lembrando que a ordem é muito importante, sendo assim ele vai tentar reproduzir primeiro mp3, depois ogg e por último wav ( de acordo com o exemplo dado acima)

```html
    <audio preload="">
```
 - auto (default): Considera que o site carregou apenas após todo áudio ter sido carregado.
 - metadata: Carrega apenas algumas informações sobre o arquivo.
 - none: Não carrega nada até que o usuário aperte play

OBS: .wav é um arquivo compatível, porém ele é muito pesado

------------------------------------------------
### Formatos de vídeos para seu site - Aula 23 [exercício 12]
 - Pexels - além de imagens, possui vídeos sem direitos autorais
 - HandBreak - Programa para realizar a conversão dos vídeos


##### Compatibilidades
 - Navegadores: padrões mais utilizados e suportados são .mp4 (.m4v), .webm, .ogv
 - Preset: Web > Vimeo Youtube 720p 30. Variando Format: MP4, WebM, 

------------------------------------------------
### Vídeos em hospedagem própria - Aula 24
#### Por que tenho que ter o vídeo em vários formatos?
Por que os navegadores são compatíveis com determinados formatos. Podendo funcionar em alguns computadores/navegadores e não em outros.

Para inserir os vídeos, basta fazer como se fosse um arquivo de audio, porém um vídeo
```html 
    <video src="midias/Pexels Videos_original.mp4" width="500" controls></video>
```
 - Também inserir o tipo: type="video/mp4" (webm ou ogg)

Mas para garantir que irá funcionar na maioria dos navegagores, vamos colocar num formato que, caso um vídeo não seja executado, tentará executar outro formato.

Dando preferência de colocar o arquivo mais leve para ser a primeira opção a ser testada.
```html
    <video controls width="700" poster="midias/limoes-capa.png">
        <source src="midias/Pexels Videos_original.webm" type="video/webm">
        <source src="midias/Pexels Videos_original.mp4" type="video/mp4">
        <source src="midias/Pexels Videos_VimeoYoutube_720p_30fps.m4v" type="video/mp4">
        <source src="midias/Pexels-Videos_original.ogv" type="video/ogv">
        <p>Seu navegador não tem compatibilidade com reprodução de vídeos</p>
    </video>
```
Para colocar uma capa no seu vídeo basta colocar "poster". Lembrando que também existem as funções "autoplay" e "loop".

##### CUIDADO!!!
Isso não é uma boa prática, pois mesmo um vídeo pequeno e de baixa qualidade, hospedado no seu site, vai consumir muito tráfego de dados, o que impacta no bolso do cliente.

------------------------------------------------
### Incorporação de vídeos externos - Aula 25
Adiconar vídeos de serviços de hospedagem de vídeo

#### Youtube
Compartilhar > Incorporar > Copia o código HTML além de poder escolher outras configurações que o próprio Youtube te dá.

#### Vimeo
Tenho a escolha de deixar meus vídeos livres para serem acessados por qualquer pessoa ou posso também aderir a um plano pago para hospedar todos os meus vídeos e deixá-los privados para que apenas quem pagou pelo curso/aula possa acessá-lo.

Compartilhar > Incorporar > Insiro o tamanho, cor do título, retrato do artista, se quero ou não o nome do vídeo/artigo. Depois disso colo o código que foi gerado e insiro na minha página.

Vantagens:
 - Qualidade do vído é muito boa

Desvantagem:
 - O algoritmo dele não é tão bom quanto do YouTube, portanto os vídeos costumam dar umas travadas (codec não é tão boa)

------------------------------------------------
### Desafio: um site com vídeos - Aula 26
Realização do desafio proposto d009

**Falta deixar o link apenas em cima das letras e da imagem** - Resolvido com div e span

------------------------------------------------
## <ins>Capítulo 12</ins>
------------------------------------------------
### Estilos CSS inline - Aula 27 [exercício 13]
CSS - Cascate Style Sheets

#### Estilo Inline
O que você alterar para um "h1" no início da página não será aplicado para os demais "h1" do restante da página. Para que o mesmo estilo seja aplicado a todos é necessário utilizar as CSS, ou um estilo global que será aplicado a todas as tags (que forem adicionadas um estilo) igualmente.

\<body style="background-color: lightblue; font-family: Arial, Helvetica, sans-serif;">

Isso não possui nenhum significado, representa apenas a aparência/estilo
##### Lembrando!
 - O HTML dá o significado, a semântica para o que está sendo escrito. Já CSS é o que vai cuidar da aparência/design do site (que também é muito importante)
 - Estilo Inline - Não costume usar dessa maneira, pois é trabalhoso, não é escalável e além disso, polui o código HTML. Utilize apenas para alterações pontuais.
 - Por esse motivo é importante separar os estilos em outro arquivo.

------------------------------------------------
### Estilos CSS internos - Aula 28 [exercício 14]
Muito melhor utlizar as CSS internas abrindo um \<style> em \<head> e adicionando as tags utilizdas e os estilos que serão aplicados a cad um deles.

Algumas desvantagens:
 - O style costuma ocupar muito mais espaço que o próprio conteúdo
 - Caso eu queira replicar esse estilo para as demais páginas eu preciso copiar todo o trecho de código e passar para todas as páginas.

------------------------------------------------
### Estilo CSS externos - Aula 29 [exercício 15]
 - Crie um arquivo a parte style.css para colocar o estilo
 - Não esquecer de colocar um link para esta página de estilos
 - Para evitar problemas de compatibilidade com acentuações/simbologias adicione uma **regra** (mais pra frente serão vistas mais regras) [@charset "UTF-8";]
 - As regras ficam no início do arquivo .css
 - Evite ao máximo utilizar o estilo inline, a menos que seja uma modificação pontual que será aplicada em apenas uma das páginas.
 - É possível misturar os estilos externos, internos e inline em um mesmo arquivo. Lembrando que o que prevalece será sempre o inline, seguindo do interno e por último o externo.

### <ins>FIM DO MÓDULO 1: Certificados Liberados</ins>
Certificado