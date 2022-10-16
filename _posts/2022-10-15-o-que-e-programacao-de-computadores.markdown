---
layout: post
title:  "O Que é Programação de Computadores?"
date:   2022-10-15 13:14:04 -0300
categories: programação
---

![o que é a programação de computadores?](/assets/posts/0001/banner.png)

Smartphones, computadores, notebooks, smart TVs, smart watch, isso sem falar dos softwares, Facebook, Instagram, Tik Tok, YouTube, Google, WhatsApp, dentre vários outros.

Tudo isso está presente no nosso dia-a-dia e quanto mais o tempo passa mais isso se torna senso comum.

Mas uma pergunta perdura, como tudo funciona? Como conseguimos usar um aparelho que cabe no nosso bolso para mandar uma mensagem quase que em tempo real para uma pessoa do outro lado do mundo de forma tão simples?

É claro que existe uma série de fatores que contribuem para isso, mas nesse post falaremos sobre os softwares, como o WhatsApp nesse exemplo, e falaremos principalmente sobre quem os faz, os **PROGRAMADORES DE COMPUTADOR**!

Então bora entender sobre o mundo da programação?

## Sumário:

1. [Entendendo a programação de computadores;](#entendendo-a-programação-de-computadores)
2. [Linguagens de programação;](#linguagens-de-programação)
3. [Compiladores e interpretadores;](#compiladores-e-interpretadores)
4. [O que é possível fazer com a programação de computadores?](#o-que-é-possível-fazer-com-a-programação-de-computadores)
5. [Editores e IDEs;](#editores-e-ides)
6. [Como posso começar a aprender sobre programação de computadores?](#como-posso-começar-a-aprender-sobre-programação-de-computadores)
7. [Conclusão.](#conclusão)

## Entendendo a programação de computadores

![Entendendo a programação de computadores](/assets/posts/0001/entendendo-a-programacao-de-computadores.jpg)

Primeiro vamos entender o que é um computador.

Um computador é uma máquina eletrônica de processamento de dados, programada para que, com intervenção humana, consiga realizar operações complexas.

Também podemos dizer que um computador é um dispositivo composto de partes eletrônicas que pode ser programado e reprogramado, ou seja, uma máquina que pode ser construída para fazer várias coisas e readaptada para fazer novas coisas.

Por exemplo, uma bicicleta é uma tecnologia que foi feita para se locomover e apenas isso, mas um computador pode ser programado para enviar uma mensagem para outro computador, pode ser reprogramado para executar um jogo e ainda pode ser reprogramado para criar documentos que serão impressos e entregues por um aluno a uma professora num trabalho de escola.

Sendo assim um celular, um notebook, uma smart TV, tudo isso pode ser considerado um computador.

Ok, mas se é um dispositivo que pode ser usado para fazer várias coisas então isso quer dizer que é necessário que alguém de essas ordens para ele, certo? Exato.

E quem são essas pessoas que darão as ordens? São os PROGRAMADORES!

![programadores](/assets/posts/0001/programadores.jpg)

Como dito o computador pode ser programado e reprogramado para fazer diversas coisas, logo quem o programa é o programador e para fazer isso ele precisa se comunicar com o computador e mandâ-lo fazer certas coisas.

Seria simples se fosse como na vida real, "envie essa mensagem", "imprima esse documento", mas o computador entende outra coisa, ele entende apenas o binário (0 e 1).

Se você ainda não está acostumado uma coisa que eu posso te dizer é que a matemática consegue representar praticamente tudo, ou quase tudo, nesse mundo, por isso ela é tão importante, mas nós conhecemos e utilizamos mais o sistema decimal (de 0 a 9) e as combinações desses números, porém também temos:

- o sistema octal (de 0 a 7) = 0 1 2 3 4 5 6 7;
- o hexadecimal (de 0 a F) = 0 1 2 3 4 5 6 7 8 9 A B C D E F; e
- o binário (0 e 1) = 0 1.

Por exemplo, **0** no sistema binário é **0**, **1** no sistema binário é **1**, **2** no sistema binário é **10** (um zero, não dez), sendo assim **1100** (um um zero zero) é igual a **12** no sistema decimal.

Podemos fazer o cáculo de que `12 + 12 = 24` e `1100 + 1100 = 11000`, é a mesma coisa em sistemas númericos diferentes.

Como os números podem representar diversas coisas a junção dos mesmos pode formar tudo o que o computador entrega para a gente e, como o sistema binário trabalha com apenas dois números a matemática é bem mais simples, o computador consegue ser bem mais rápido que o cérebro humano em alguns cálculos, embora seja incapaz de funcionar sem a ajuda do ser humano, é uma combinação de conhecimento do ser humano com a velocidade do computador.

Então o computador não fala a mesma lingua que a gente, não dá para se comunicar diretamente com ele.

Além disso ainda temos o problema da comunicação humana que é de um nível muito alto, com isso eu quero dizer o seguinte.

Imagine uma pessoa rindo e brincando dizendo: "Você está de brincadeira?".

Agora imagine a mesma pessoa brava, numa situação ruim, desapontada dizendo: "Você está de brincadeira?"

Entendeu?

Um computador é **LÓGICO** e é **RACIONAL** ao **EXTREMO**, como ele conseguria interpretar a linguagem do ser humano? Até nós que **SOMOS SERES HUMANOS** temos dificuldade de dizer se o outro está dizendo a verdade ou mentindo.

Dados todos esses pontos foi criado uma forma de se comunicar com o computador e enviar ordens para ele, e é aí que entramos nas linguagens de programação.

## Linguagens de programação

![Lingaugens de programação](/assets/posts/0001/linguagens-de-programacao.jpg)

O que é uma linguagem de programação?

É uma linguagem específica para se comunicar com o computador, mandar instruções para o mesmo a fim de que ele as execute.

Por exemplo, vamos supor que existe uma palavra chave, **ESCREVA**, ela manda a ordem para o computador escrever algo, e você envia o seguinte para o computador:

```
ESCREVA "Esse é o meu primeiro programa de computador"
```

Esse programa tem como único objetivo exibir essa mensagem e ao abrí-lo você verá essa mensagem escrita.

Agora imagine o seguinte, você quer um programa que some dois números, vamos imaginar que agora temos a palavra **LEIA** para registrar um valor enviado por um usuário, você pode fazer o seguinte:

```
NUMERO_1 = LEIA "Digite o primeiro número: "
NUMERO_2 = LEIA "Digite o segundo número: "

ESCREVA NUMERO_1 + NUMERO_2
```

Com isso você tem a instrução **LEIA** que pega algo que o usuário digitar, como no caso de digitar um e-mail e uma senha, depois você pega os dois valores e exibe a soma deles.

Basicamente falando é assim que funciona um código de um programa de computador, porém a maior parte das linguagens de programação usam o inglês, logo o código acima poderia ser escrito assim com uma linguagem chamada Python, por exemplo:

```python
number_1 = int(input("Digite o primeiro número: "))
number_2 = int(input("Digite o segundo número: "))

print(number_1 + number_2)
```

Não precisa se preocupar em entender o que acabou de acontecer aqui em cima, isso vem com o tempo e com o estudo.

Assim conseguimos mandar as instruções para o computador afim de que o mesmo possa executá-las. Veja no exemplo abaixo esse trecho de código sendo executado.

<script id="asciicast-VhmAd4juwiqctMcH6e2xrNWcz" src="https://asciinema.org/a/VhmAd4juwiqctMcH6e2xrNWcz.js" async data-speed="1.5"></script>

Mas como escrevemos essas instruções?

Através do que chamamos de código-fonte.

Você pôde ver que escrevemos um texto acima para ordenar o computador a fazer algo, dessa mesma maneira podemos escrever diversas quantidades de texto com as linguagens de programação e enviar para o computador, assim ele processará esse texto e executará o que o mesmo manda.

Com todo o texto pronto temos o que chamamos de código-fonte de uma aplicação, é o código que faz com que ela funcione, o Google, o WhatsApp, o Instagram, todos tem o seu código-fonte e são as ordens existentes no mesmo que fazem essas aplicações fazerem o que elas fazem.

Recapitulando, temos as linguagens de programação, com elas escrevemos o código-fonte da aplicação que faz com que a mesma funcione.

Mas depois do código pronto como temos a aplicação realmente funcionando? Se o computador entende apenas o binário como conseguimos nos comunicar com essas linguagens de programação?

Pra isso nós temos os compiladores e os interpretadores.

## Compiladores e interpretadores

![compilador](/assets/posts/0001/compilador.png)

Pense assim, escrevemos esse código que você viu acima e o computador entendeu, se o computador fala uma lingua e você outra precisamos de alguém para traduzir.

Esse é o trabalho tanto do compilador quanto do interpretador, âmbos fazem um serviço similar de maneira diferente.

Vamos começar com o compilador.

Basicamente falando o compilador pega o seu código e o traduz para uma linguagem que o computador é capaz de entender, o que chamamos de linguagem de máquina, ele também realiza outros processos, mas vamos nos focar na tradução do seu código.

Se pegarmos por exemplo a linguagem de programação conhecida como C temos o compilador GCC, podemos usar ele para transformar o nosso código em algo que o computador entenderá e depois executar. Veja no vídeo abaixo.

<script id="asciicast-NnknlrN4ckcqDrWfI2RUjNL9q" src="https://asciinema.org/a/NnknlrN4ckcqDrWfI2RUjNL9q.js" async data-speed="1.5"></script>

Assim temos o processo de escrita do código e depois de compilação.

Porém a compilação faz mais do que isso, ela analisa e otimiza o código também, embora não seja o ponto principal e seja necessário outro post para explicar mais sobre isso vou deixar aqui o que um compilador costuma fazer.

- Análise léxica;
- Análise sintática;
- Análise semântica;
- Geração de código intermediário;
- Otimização de código;
- Geração de código objeto;

E com isso temos a versão final do código que será entregue para o computador.

Porém, além dos compiladores temos também os interpretadores.

O interpretador faz algo similar ao compilador, mas em tempo real, enquanto o compilador lê todo o seu código para realizar todo o processo e gerar a versão final o interpretador faz isso enquanto lê o seu código.

Em resumo, com o compilador você precisa compilar (gerar uma versão final) e depois executar o seu programa, já com o interpretador você faz tudo de uma vez.

Isso tem os seus prós e os seus contras, mas isso será melhor explicado num post futuro específico sobre isso.

Lembra do vídeo acima em que foi possível criar um código em C, gerar um executável com o GCC e executar o programa? Agora usaremos a linguagem Python que é interpretada, diferente do C que é compilada, olhe a diferença no processo.

<script id="asciicast-aNVZrGgGW2E9jOrrfRNLEiuOV" src="https://asciinema.org/a/aNVZrGgGW2E9jOrrfRNLEiuOV.js" async data-speed="1.5"></script>

Como você pode ver o código em Python não precisa criar um novo arquivo do programa, é tudo feito direto.

Isso não quer dizer que o interpretado é melhor que o compilado, apenas quer dizer que eles são diferentes e que cada caso é um caso.

Com isso conseguimos entender que temos as linguagens de programação e que temos os compiladores e os interpretadores que traduzem as mesmas para que o computador possa entender, assim podemos escrever os nossos códigos, compilá-los ou interpretá-los e o computador nos obedecerá, por assim dizer.

Então entendemos o processo, escrevemos um código e o computador obedece...

... e o que podemos fazer com isso?

## O que é possível fazer com a programação de computadores?

![Mundo da programação](/assets/posts/0001/mundo-da-programacao.jpg)

Vamos pensar o seguinte, um computador é qualquer componente eletrônico que pode ser programado e reprogramado, o seu smart watch, smart TV, smart phone, notebook, até uma plaquinha pequena (um microcontrolador ou um microcomputador) que vai numa máquina usada numa fábrica ou numa indústria.

Sendo assim qualquer computador pode receber um código e ser programado para fazer algo.

Imagine um robo que é utilizado para montar carros, ou partes do mesmo, existe um computador dentro dele e é possível escrever um código para mandâ-lo fazer algo.

Imagine um console de video-game, PS5 e PS4, Xbox Series e One, Nintendo Switch e até o seu celular, são computadores, você pode escrever códigos que virão a se tornar jogos.

Desenvolver sites, programas para computador desktop, aplicativos para celulares, códigos que pessoas não veem que processam grandes quantidades de dados para trabalhar com análise estatística, tudo isso pode ser feito com a programação de computadores.

Até programas que serão utilizados para fazer outros programas podem ser criados, você pode criar um programa com o Python, como eu fiz no vídeo mais acima, mas o próprio Python possui um programa dentro dele que é o seu interpretador, um programa usado para interpretar códigos que criam mais programas.

Se você tiver um computador e imaginação você pode ir longe.

É claro, para cada tipo de situação você tem maneiras diferentes de se trabalhar, eu por exemplo trabalho com desenvolvimento web consturindo web sites e o que acontece por detrás deles, também estou estudando desenvolvimento de games.

Se você me pedir para construir um aplicativo para celular ou um programa para um robô eu precisarei estudar novos assuntos.

Um outro detalhe interessante é que os programas de computadores tem como objetivo, quase sempre, resolver problemas.

Por que o WhatsApp existe? Para resolver o problema da comunicação a longa distância.

Por que o Google existe? Para organizar as informações do mundo.

Por que o Instagram existe? Para conectar as pessoas numa rede social.

Então sempre que for criar um programa de computador pense, que problema eu quero resolver?

O ponto agora é, eu quero escrever esses códigos, eu posso escrevê-los em qualquer lugar ou tenho um programa específico?

## Editores e IDEs

![Editores e IDEs](/assets/posts/0001/editores-e-ides.png)

Vamos falar então dos editores e das IDEs.

Comecemos pelas IDEs (Integrated Development Environment) ou em português Ambiente de Desenvolvimento Integrado.

Essa é uma ferramenta que contempla diversos itens necessários para desenvolver um programa, você tem um editor para escrever o seu código-fonte com recursos que te ajudam a escrevê-lo de forma correta, você tem ferramentas que ajudam no processo de compilação, você tem um Debugger, item esse que será mencionado em outro post, além de outras ferramentas que dependem de cada IDE.

Eu, por exemplo, sou um programador PHP e trabalho com a IDE PHP Storm, temos outras como o PyCharm para Python, para C temos o CodeBlocks ou o CLion, para C# temos o Visual Studio, e asism por diante.

Mas será que eu não posso usar um bloco de notas, por exemplo?

Sim, você pode, assim você digita o seu código, salve e faz todos os outros processos necessários de forma mais manual, como eu fiz nos vídeos acima, mas a IDE te trará recursos que podem agilizar e muito o seu trabalho e é recomendável usá-las.

Qual IDE usar? Depende de qual linguagem você está usando e o que você fará com ela.

E o editor? O que seria?

O editor é mais simples, ele possui apenas uma área para editar o código-fonte em si, compilação, depuração, testes, tudo isso é feito de forma manual.

O bloco de notas em si pode ser considerado um editor, existem outros que oferecem alguns recursos a mais, o Sublime Text, o Visual Studio Code (não confundir com Visual Studio), o Vim e o NeoVim.

Porém vivemos numa atualidade em que os editores estão tão completos a ponto de se equipararem a IDEs, o próprio Visual Studio Code, embora seja um editor, consegue compilar, fazer um processo de análise do código, depurar, executar testes, além de diversas outras coisas, então se torna quase uma IDE faltando poucos ou até nenhum recurso.

Sendo assim, com os editores e IDEs temos programas mais específicos para escrever os nossos códigos e criar os nossos programas de computadores.

## Como posso começar a aprender sobre programação de computadores?

![Estudando programação](/assets/posts/0001/estudando-programacao.jpg)

Primeiramente é importante entender os conceitos, conhecer o básico sobre programação e começar desenvolvendo programas mais simples.

Depois disso você pode ver em qual área você deseja se aprofundar mais, desenvolvimento web, de jogos, de aplicativos, entre outros, e para cada área haverá um caminho para seguir.

Na Code Easy temos também um canal no YouTube ( [Code Easy](https://codeeasy.com.br/CodeEasy) ) onde temos vários vídeos de programação e, no momento da publicação desse post, temos uma série de vídeos que estão sendo lançados para quem está iniciando nesse mundo da programação, um curso sobre [Lógica de Programação](https://youtube.com/CodeEasy), algo essêncial e feito especificamente para quem está começando do zero na programação de computadores.

Caso você queira continuar aprendendo com a gente depois o nosso foco é no desenvolvimento web, para quem quer construir sites, aplicações web e serviços web que se comunicam através da internet envolvendo tudo o que está ligado a esse mundo.

## Conclusão

A programação de computadores é uma área grande e com grandes possibilidades que está repleta de novidades todos os dias, com ela você pode dar vida as suas ideias e criar o que você imaginar, exige esforço e dedicação além de tempo, mas se você se mantiver firme as possibilidades do que você pode criar são ilimitadas.

Então aprenda um pouco sobre programação, depois escolha uma área para começar a se aprofundar, escolha a sua linguagem e sua IDE e vamos começar a construir juntos as nossas soluções.

Então que tal resolver problemas com o mundo da computação? Topa o desafio?
