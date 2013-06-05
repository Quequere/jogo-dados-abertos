CRIAÇAO DE UM JOGO DE TABULEIRO SOBRE COMUNIDADES DE SOFTWARE LIVRE E DADOS ABERTOS

A criação deste jogo tem como objetivo realizar uma documentação e investigação sobre os processos de participação social que são transversais às comunidades de software livre - tanto pelo processo horizontal e colaborativo como pela adesão cada vez mais potente desses atores nos movimentos sociais, no ativismo político. No limite, parte de uma leitura de que o desejo de autonomia, revolução e transformação que vem do encontro entre as comunidades de desenvolvedores, movimentos sociais e ativistas pode, sim, construir uma nova política.

O caráter lúdico, educativo e informativo de um jogo de tabuleiro para trabalhar o tema cria uma narrativa divertida e informal para aprender, debater e dialogar sobre estes temas. Então, o intuito deste jogo não é apenas ser uma mecânica divertida para as pessoas que já estão inseridas dentro deste universo, é também ser uma ferramenta para que pessoas que conheçam pouco ou desconheçam o processo de comunidades de código livre e dados abertos possam através do jogo terem uma oportunidade de aprendizado e familiaridade com este universo.

Criamos esta documentação no Github com o intuito de colher as mais diversas sugestões para o desenvolvimento deste jogo, pra isso detalharemos abaixo todas as etapas no processo de criação da estrutura de um jogo. Desde a escolha do tema até a escolha das ferramentas usadas. Daremos exemplos destes detalhes de dois jogos para facilitar e direcionar melhor as sugestões que queremos. Um dos jogos é um jogo desenvolvido por nós da Quequeré Jogos chamado: A Conta da Copa é Nossa (que conta com bastante dados reais, que queremos no jogo sobre as comunidades de código) e outro jogo, o Banco Imobiliário, que como já é uma mecânica conhecida, facilita ainda mais este feedback.
 
1 - O JOGO

O jogo está baseado num processo completamente aberto, o único preceito é que seja um jogo cooperativo, ou seja, mesmo que haja uma independência de ações entre os jogadores, o objetivo final do jogo tem que ser um objetivo comum entre os participantes, uma vez que a própria estrutura de Comunidade de Código Livre e Dados Abertos funciona desta forma, entre ajuda mútua e objetivos em comum.

A participação online ficará disponível até o fim do desenvolvimento do jogo e conforme algumas escolhas do jogo forem sendo sendimentas atualizaremos as informações para termos sugestões mais específicas.
 
2- PROCESSO DE DESENVOVIMENTO DOS JOGOS

O desenvolvimento de um jogo acontece normalmente de uma forma caótica, não planejada, com todos os processos ocorrendo ao mesmo tempo, concomitantemente e influenciando cada um o desenvolvimento do outro. Mas para fim de apresentação de cada etapa vamos separar os diferentes cortes de leitura que se pode ter no jogo, tanto para facilitar o compreendimento do processo como os feedbacks de retorno que queremos:

a) Objeto: é sobre qual universo o jogo trata - quando não abstrato - no nosso desenvolvimento ele já está definido, que é: Comunidades de Software Livre e Dados Abertos;

b) Tema: é o foco que o jogo aborda dentro do universo que ele escolheu tratar. No jogo da Copa do Mundo que será apresentado o foco é a Construção das Obras da Copa do Mundo, mas poderia ser as seleções de cada país, o legado pós copa, as remoções de moradores etc;

c) Papel do jogador: define qual vai ser a identidade de cada jogador dentro do jogo. Os jogadores podem ter identidades similares, ou diferentes. Quando possuem identidades similares acabam representando os mesmos papéis e tendem a seguir as mesmas opções de jogo, quando possuem identidades diferentes apesar de seguir regras similares tendem a ter diferentes opções de jogo que casem com sua identidade;

d) Objetivo do jogo: define a causa do jogo, qual a finalidade do mesmo. Como vamos elaborar um jogo coletivo esta finalidade é comum a todos jogadores;

e) Mensuração do Objetivo (pontuação): define como será a mensuração do objetivo. Haverá pontuaçao ou não? Ou será um fato específico que define (como um xeque-mate no xadrez). Quais as possibilidades de mensurar o objetivo proposto no jogo?

f) Modos de adquirir pontuação: Se o jogo tiver pontuação para mensurar o(s) objetivo(s) do jogo, quais as formas que serão utilziadas pra isso;

g) Dinâmica (tempo de jogo): define a duração do jogo, e o ritmo que ele terá, se terão rodadas definidas ou indefinidas, fases específicas. Outro fator importante é como este tempo se encaixa e se envolve com o tema definido.  O tempo define o que? A passagem de dias, meses e anos? O tempo de um processo de trabalho? É um tempo abstrato?

h) Dinâmica (ordem do jogo): define como os acontecimentos do jogo irão se suceder ao longo da partida, se os jogadores jogam em ordem ou ao mesmo tempo, se existem etapas que precisam ocorrer anteriores a outras.

i) Mecânica (espinha dorsal): define qual o principal mecanismo do jogo, que dá a sua identidade, ou também se não há uma mecânica principal.

j) Mecânicas secundárias: define as regras secundárias do jogo, que orbitam em torno do mecanismo principal, caso não tenha uma emcânica principal, define a mecânica geral do jogo, composto de vários micro mecanismos.

l) Ações: define quais ações o jogador pode tomar durante o jogo, o que ele pode realizar dentro da partida, quais habilidades possíveis que podem desenvolver. 

m) Ferramentas (objetos do jogo): define os componentes que serão utilizados no jogo e qual a referência de cada objeto com o tema abordado.

3 - EXEMPLO DE JOGOS

Abaixo apresentaremos alguns jogos destrinchados conforme o modelo acima que apresentamos, a sigla "PC" significa "palavra-chave" e caso não consigam desenvolver sugestões tão conretas, dar feedback em "palavras-chaves" já torna-se bastante interessante para o processo.Deixamos também a disposiçao o link do manual completo dos dois jogos, para melhor entendimento das regras do jogo e como foi feito esta divisão pelo modelo acima.

a) BANCO IMOBILIÁRIO

link para o manual: 

-       OBJETO:

Imóveis

·       TEMA:

Especulação Imobiliária nas Cidades
PC: Especulação Imobiliária – Monopólios

·       PAPEL DO JOGADOR: 

Cada jogador representa um capitalista que investe dinheiro em imóveis e em serviços públicos em um determinado espaço urbano
PC: capitalista

·       OBJETIVO DO JOGO:
 
Falir todos os demais jogadores e se tornar o único dono dos imóveis
PC: construir um monopólio – falir demais jogadores

MENSURAÇÃO DO OBJETIVO (PONTUAÇÃO):

Não  há pontuação, sua força é definida pela quantidade de dinheiro têm e  propriedades que possui, e você chega a seu objetivo quando todos os  demais jogadores não possuírem nenhum dinheiro.
PC: propriedades – dinheiro
·
MODOS DE ADQUIRIR PONTUAÇÃO:

Não há pontuação.
 PC: não há pontuação no jogo

·       DINÂMICA (TEMPO DE JOGO):

O  jogo não tem tempo definido e termina assim que todos os jogadores,  menos um, for a falência. As rodadas representam o passar do tempo, mas  um tempo indefinido. 
PC: rodadas representam o passar do tempo de forma indefinida – não há limite de tempo no jogo 

·       DINÂMICA (ORDEM DO JOGO):

Joga-se  cada um dos jogadores por vez, na sua rodada cada jogador joga dois  dados e anda aquele valor respectivo no tabuleiro e faz a ação relativa a  aquele lugar em que caiu.
PC: cada jogador joga em ordem, cada um por vez

·       MECÂNICA (ESPINHA DORSAL):
 
Cada  jogador joga dois dados na sua vez, e anda o número tirado no  tabuleiro, que é cíclico e tem 40 casas. Se o jogador terminou em um  local que ainda não é de nenhum outro jogador ele pode comprá-lo, caso  já seja de outro jogador ele tem que pagar o valor referente ao aluguel  daquele local. 
PC:  tabuleiro cíclico com 40 casas – jogadores andam conforme valor tirado  no dado – locais onde caem podem ser comprados, caso já tenha sido  comprado por alguém, tem de pagar um aluguel ao respectivo dono.

       MECÂNICA (SECUNDÁRIAS):
 
-       Caso um jogador tire o mesmo número nos dois dados ele joga novamente;
-       Caso um jogador tire o mesmo número nos dados três vezes seguida ele vai para a prisão;
-        Jogador pode construir casas e hotéis em terrenos caso ele possua todos  os terrenos de uma respectiva cor, quanto mais casas construídas mais  caro o preço do aluguel;
-       Existem casas específicas no tabuleiro em que o jogador escolhe cartas de sorte ou revés;
PC:  jogador joga novamente se tirar o mesmo valor nos dois dados – jogador  vai para a prisão se tirar o mesmo valor nos dois dados três vezes  seguidas – jogador pode construir casas e hotéis em seus terrenos logo  ele possua todos os terrenos da mesma cor, auxiliando o aumento no valor  do aluguel – espaços de sorte ou revés

·       AÇÕES:
 
O  jogador pode, na sua vez, comprar a propriedade em que caiu, pagar  aluguel caso ele seja de outro jogador, comprar casas ou hotéis em  terrenos seus que podem ser construídos, ou realizar a função específica  do espaço do tabuleiro em que está.
PC: comprar propriedades – construir nos terrenos – fazer a ação do local do tabuleiro em que está

·       FERRAMENTAS (OBJETOS DO JOGO):
 
-        Tabuleiro: o tabuleiro tem 40 espaços, nele encontram-se os terrenos e  empresas que os jogadores podem comprar, os espaços de prisão, sorte ou  revés e imposto de renda;
-        Títulos de Propriedade: são as cartas que representam todos os locais  do tabuleiro passíveis de compra; o jogador que comprar determinado  local pega a carta respectiva;
-       Cartas de Sorte ou Revés: são cartas de eventos específicos, que podem representar coisas boas ou ruins;
-       Peões: representa cada um dos jogadores no tabuleiro
-        Peças de Casas e Hotéis: são peçás que encarecem o aluguel de um local,  quanto mais casas colocadas mais o preço do aluguel da região
PC: Tabueliro representando bairros de cidade - títulos de propriedade - eventos de sorte ou revés - construções imobiliárias

·       DADOS REAIS UTILIZADOS NO JOGO:
 
-       Na primeira versão lançado no Brasil todos os terrenos representam bairros da Cidade de São Paulo ou Rio de Janeiro

b) A CONTA DA COPA É NOSSA

link para o manual:

-       OBJETO:

Copa do Mundo
 
 ·       TEMA:
 
Construção das Obras para a Copa do Mundo
PC: obras da Copa do Mundo
  
·       PAPEL DO JOGADOR: 
  
Cada jogador representa uma empreiteira fictícia que participa das construções das obras da Copa do Mundo.
PC: empreiteira
  
·       OBJETIVO DO JOGO:
  
Tornar sua empreiteira a mais beneficiada dentre as outras empreiteiras nos projetos da Copa do Mundo 
PC: empreiteira mais poderosa
 
·       MENSURAÇÃO DO OBJETIVO (PONTUAÇÃO):
 
Para sua empreiteira ser a mais beneficiada ela tem que coletar mais “pontos de benefício” que as outras empreiteiras.
PC: pontos de benefício
 
 
·       MODOS DE ADQUIRIR PONTUAÇÃO:
 
São três formas que uma empreiteira adquire “pontos de benefício” no jogo: a principal, que é construindo obras; as demais é cooptando governadores ou patrocinadores para sua esfera de influência.
 PC: construir obras – cooptando governador – adquirindo patrocinador
 
 
·       DINÂMICA (TEMPO DE JOGO):
 
 O jogo é composto de 24 rodadas, nas quais cada uma representa 2 meses no mundo real, ou seja, a partida abrange um universo de 4 anos (de maio de 2010 a maio de 2014, quando começa a Copa).Em cada uma delas todos jogadores jogam e realizam suas ações, ao final da 24ª rodada o jogo acaba.
PC: rodadas representam meses – tempo do jogo é o período que antecede a Copa 
 
 
·       DINÂMICA (ORDEM DO JOGO):

O jogo é composto de 24 rodadas, em cada rodada seguem as seguintes etapas:
-       Insere-se a mesa: matérias de construção, dinheiro e transporte;
-       Cada jogador escolhe um personagem para auxiliá-lo na rodada;
-       Cada jogador realiza em ordem, cada um por vez, suas ações;
PC: inserção toda rodada de elementos necessários às construções – cada jogador joga em ordem, cada um por vez
  
·       MECÂNICA (ESPINHA DORSAL):
 
Cada jogador conta com um baralho de personagens influentes na estrutura de organização da Copa do Mundo. O baralho é igual para todos os jogadores, e em cada rodada cada jogador contará com o favor (poder) de dois personagens. 
Cada personagem tem um número de 0 a 9, quanto mais forte seu poder maior seu número. Como cada jogador conta com dois personagens por rodada, cada jogador formará uma dezena com o número feito pelos seus personagens, isto define a ordem da cada jogador na rodada, em que o jogador com dezena menor começa jogando e assim sucessivamente. 
PC: cada jogador utiliza dois personagens por rodada do seu baralho principal, cada carta deste baralho tem números de 0 a 9 (dois de cada número – total de 20 cartas), o jogador que possuir a menor dezena começa jogando e realiza suas ações e os poderes dessas cartas e assim por diante.
 
·       MECÂNICA (SECUNDÁRIAS):
 
-       Existem sempre a mesa 8 construções /patrocínios aptos a serem adquiridos. Uma vez que um é adquirido abre-se outro a disposição;
-       Para fazer uma obra um jogador tem que primeiro comprar a licença da obra, que dura 4 rodadas;
-       Existe apenas 1 governador disponível por vez, uma vez adquirido, abre-se outro a disposição;
-       Uma vez substituído um personagem da mesa de um jogador ele é descartado;
PC: existe um número limite de obras/governadores a serem construídas por vez – depois de um personagem ser substituído por outro ele é descartado – antes de um jogador poder construir uma obra ele tem que adquirir sua licença.
 
·       AÇÕES:
 
O jogador pode, na sua vez, realizar as seguintes ações: utilizar os favores (poderes) dos personagens que estão disponíveis a ele. Gastar dinheiro pra adquirir licenças das obras. Gastar os materiais de construções necessários para realizar uma obra que já tenha licença. Gastar dinheiro para angariar governadores. Gastar patrocínios para adquirir patrocinadores.
 PC: favores dos personagens – comprar licença das obras - construir obras – adquirir patrocinadores – angariar governadores.
 
·       FERRAMENTAS (OBJETOS DO JOGO):
 
-       Baralho de personalidades: cada jogador possui um com 20 personalidades. Principal ferramenta do jogo, ela é quem dá aos jogadores poderes e responsável pela dinâmica do jogo;
-       Cartas de Construção: são as cartas que representam todas as obras planejadas pra Copa do Mundo e que os jogadores podem construir: aeroportos, portos, mobilidade urbanas e estádios. Principal fonte de “pontos de benefícios”.
-       Cartas de Patrocinadores: são as cartas que representam os patrocinadores oficias da Copa do Mundo e da FIFA. Sua função é dar bônus durante ou ao final do jogo para o jogador que as adquire.
-       Cartas de Governador: são as cartas que representam os governadores dos estados onde haverá jogos da Copa do Mundo. Sua função é valorizar ainda mais as obras construídas no seu estado para o jogador que as adquire.
-       Materiais de construção e transporte: são 5 tipos de materiais no jogo (cimento, areia, ferro, aço e grama) e 3 transportes (ônibus/trem; avião e navio). São utilizados para adquirir as cartas de construção, ou seja, construir as obras da Copa.
-       Patrocínios: são utilizados para adquirir as cartas de Patrocinadores.
-       Dinheiro: utilizado para adquirir cartas de Governador e comprar a licença de execução das Cartas de Construção;
PC: Pessoas Influentes na Organização da Copa – Obras da Copa – Patrocinadores da Copa – Governadores dos Estados da Copa – Materiais de Construção – Patrocínio - Dinheiro
 
·       DADOS REAIS UTILIZADOS NO JOGO:
 
-       Todas as personagens do jogo são pessoas reais;
-       Todas as construções do jogo são as construções e reformas reais feitas para a Copa do Mundo;
-       Todos os governadores são os governadores reais de cada Unidade de Federação;
-       Todos os patrocinadores são reais;
-       Todos os valores reais de custo das obras refletem na dificuldade de construí-la no jogo: cada material necessário para uma obra representa respectivamente 100 milhões de reais.

Observações: como o intuito é desenvolver um jogo colaborativo, segue o link de um excelente jogo colaborativo para consulta de regra e criação de personagem

http://www.zmangames.com/boardgames/pandemic.htm

manual: http://www.zmangames.com/boardgames/files/pandemic/Pandemic_Rules.pdf



