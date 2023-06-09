**UNIVERSIDADE LUSÓFONA, Programação Web, 22-23**
 
# Lab 4: *Web design responsivo* 

## Objetivos
* Este será o último laboratório sobre a cidade que escolheu, onde irá aplicar as técnicas aprendidas de design responsivo, efeitos e animações. Irá igualmente explorar as boas práticas de web design.
* Este laboratório será avaliado por colegas seus de acordo com um conjunto de [critérios de avaliação](https://github.com/ULHT-PW/pw23-lab4/blob/main/PW%20-%20Lab%204%20-%20criterios%20de%20avalia%C3%A7%C3%A3o.pdf), pelo que explore ao máximo as técnicas aprendidas para fazer um website a seu gosto.
* O prazo de entrega será dia 24, sendo avaliado posteriormente.

## Recomendações
* Leia o enunciado com atenção antes de o começar a realizar, para entender o que fará.
* Explore o seguinte material:
    * [slides da aula](https://moodle.ensinolusofona.pt/course/view.php?id=9482#section-1)
    * exemplos em [Code Pen](https://codepen.io/LucioStuder/collections/?grid_type=list)
    * [vídeo-tutorial: Criando um layout responsivo com uma media query](https://educast.fccn.pt/vod/clips/23dbqe9keb/streaming.html?locale=pt)
    * [video-tutorial: posicionamento de elementos e seletores vários](https://educast.fccn.pt/vod/clips/1tmk0lmtww/html5.html?locale=en)
    * [vídeo-tutorial: construindo um layout com CSS Grid](https://educast.fccn.pt/vod/clips/1qib570kz7/html5.html?locale=en)


## Pré-requisitos
* Deverá ter o VSCode instalado para editar o código HTML de forma fácil.
* Deverá ter instalado o git no seu computador.
* reveja os slides da aula.
* crie uma pasta lab4 para este laboratório
* utilize um ficheiro CSS para configurar 

# 2. Páginas a criar
## Indicações para todas as páginas a criar
* escolha uma fonte Google que goste, inclua o link para esta e utilize-a em todo o website, definindo um seletor universal * e propriedade font-family (veja slide)
* Seguindo as boas práticas de design referidas, e mantendo um design homogéneo, integre todas as páginas criadas nos labs anteriores, melhorando o seu design sempre que possível.
* Através do menú (a criar no fim deste laboratório) que deverá estar sempre presente, deverá poder navegar por todas as páginas criadas.
* Garanta a boa responsividade do design de todas as páginas, testando-as no seu telemóvel.
* Garanta uma boa [configuração da janela viewport](https://moodle.ensinolusofona.pt/pluginfile.php/549222/mod_label/intro/pw-02.7-design-responsivo.pdf?#page=4) quando usar a aplicação num telemóvel, assim como a configuração do [box-sizing](https://moodle.ensinolusofona.pt/pluginfile.php/549222/mod_label/intro/pw-02.7-design-responsivo.pdf?#page=6)

## Hero Page 🦸‍♀️

* Crie o ficheiro `index.html` que será a hero page da sua cidade escolhida. Siga as boas práticas de [web design](https://moodle.ensinolusofona.pt/pluginfile.php/549222/mod_label/intro/pw-02.10-web-design.pdf) referidas nas aulas para todas as páginas criadas e inclua:
   * uma fotografia ou video em background
   * uma frase que goste ao lado, motivacional
   * um menu em cima. 

## Layouts grid responsivos
Adapte as 5 páginas com layouts grid que criou no lab3 por forma a que sejam responsivos ao tamanho do ecrã usando [media queries](https://moodle.ensinolusofona.pt/pluginfile.php/549222/mod_label/intro/pw-02.7-design-responsivo.pdf?#page=11). PAra cada página, deverá alterar a disposição dos seus elementos e adaptar-se para PC, telemovel, variando se estiver em modo landscape ou portrait.

## Paralax

Crie uma página HTML com efeitos [paralax](https://moodle.ensinolusofona.pt/pluginfile.php/549222/mod_label/intro/pw-02.8-efeitos-e-animacoes.pdf#page=12), usando textos e fotografias 

## Imagens responsivas

Crie um elemento com [imagens responsivas](https://moodle.ensinolusofona.pt/pluginfile.php/549222/mod_label/intro/pw-02.8-efeitos-e-animacoes.pdf#page=6), mudando as imagens consoante a largura do ecrã

## Vídeo background

Crie uma página com um [vídeo em background](https://moodle.ensinolusofona.pt/pluginfile.php/549222/mod_label/intro/pw-02.8-efeitos-e-animacoes.pdf#page=11) da cidade que escolheu, colocando uma barra com texto. 

## Animações

Crie uma página com animações:
* crie duas animações com [transformações](https://moodle.ensinolusofona.pt/pluginfile.php/549222/mod_label/intro/pw-02.8-efeitos-e-animacoes.pdf#page=17) e [transições](https://moodle.ensinolusofona.pt/pluginfile.php/549222/mod_label/intro/pw-02.8-efeitos-e-animacoes.pdf#page=20). Se quiser, pode usar um dos logos do DEISI em SVG, disponiveis neste repositorio
* crie duas animações com [@keyframes](https://moodle.ensinolusofona.pt/pluginfile.php/549222/mod_label/intro/pw-02.8-efeitos-e-animacoes.pdf#page=22) usando o logotipo do DEISI ou outra imagem que queira
* explore e aplique 2 [efeitos](https://moodle.ensinolusofona.pt/pluginfile.php/549222/mod_label/intro/pw-02.8-efeitos-e-animacoes.pdf#page=22) 
* Crie um desenho em SVG a seu gosto usando pelo meno 3 formas geométricas distintas. Inclua neste uma animação.
* Inclua um poema. coloque cada quadra num div, e cada verso num parágrafo. Utilize todos os [selectores](https://moodle.ensinolusofona.pt/pluginfile.php/549222/mod_label/intro/pw-02.4-css-e-seus-seletores.pdf?#page=17) e [combinadores de seletores](https://moodle.ensinolusofona.pt/pluginfile.php/549222/mod_label/intro/pw-02.4-css-e-seus-seletores.pdf?#page=37), inserindo efeitos de transição em certas linhas do poema (mundando suas cores, tamanho de fonte, rotação, etc).

## Menu 

Agrupe as páginas por tópicos e crie um menu com [submenus dropdown](https://codepen.io/LucioStuder/pen/mdprdBK). Pode experimentar um menu Bootstrap.

## Wordcloud com  Image Map SVG

Crie uma wordcloud com os titulos dos menus (tamanho maior) e submenus (tamanho mais pequeno). Crie um [image map SVG](https://moodle.ensinolusofona.pt/pluginfile.php/549222/mod_label/intro/pw-02.9-SVG.pdf?#page=13), incluindo links para cada uma das respetivas páginas. Veja os exemplos neste repositorio, ficheiros [wordcloud.svg](https://github.com/ULHT-PW/pw23-lab4/blob/main/wordcloud.svg) e [wordcloud.html](https://github.com/ULHT-PW/pw23-lab4/blob/main/wordcloud.html). Como vê, pode embeber o codigo do svg diretamente no HTML


# 3. Submissão

1. Verifique que todos os links do seu website funcionam devidamente.
2. Crie um novo repositório GitHub público e carregue o seu laboratório 3 (se tiver duvidas, veja [aqui](https://github.com/ULHT-PW/git)).
3. Crie uma nova conta no pythonAnyWhere, e carregue o seu projeto, tal como descrito no lab 2.
4. Verifique que o seu website online funciona corretamente, em particular mostra todas as imagens e os hiperlinks funcionam devidamente.
5. Submeta o dominio da aplicação e link do repositório GitHub.


 # Fim ☀
 
Esperamos que tenha gostado de aplicar os conhecimentos para criar páginas responsivas, com efeitos, animações e seguindo boas práticas de design Web &#127760;!
