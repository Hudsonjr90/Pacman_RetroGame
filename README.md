Pac-Man
=======

Uma homenagem histórica e uma recriação precisa do jogo de fliperama original Pac-Man.

Inspirado em [The Pac-Man Dossier](http://home.comcast.net/~jpittman2/pacman/pacmandossier.html)

### Em construção
Som
Cenas de corte
Alternância de 2 jogadores
Entre em contato comigo em hudsonhugo90@gmail.com

### Licença
Este programa é software livre: você pode redistribuí-lo e/ou modificá-lo
sob os termos da Licença Pública Geral GNU Versão 3 conforme publicada pela Free Software Foundation.

### Jogar
Você pode jogar o jogo em todos os navegadores compatíveis com canvas. Os controles de toque estão
habilitados para navegadores móveis. O jogo é independente de resolução e se ajusta suavemente ao
tamanho de qualquer tela. O desempenho pode aumentar ao diminuir a janela ou ampliar com seu navegador.

### Controles Principais
arrastar: controlar o Pac-Man em navegadores móveis
setas: controlar o Pac-Man
end: pausar o jogo
escape: abrir o menu do jogo

### Navegadores de Desktop Confirmados
Safari
Firefox
Chrome

### Dispositivos Móveis Confirmados
[iPad and iPhone (Mobile Safari)](http://www.atariage.com/forums/topic/202594-html5-pac-man/)
Samsung Galaxy Tablet 7 (Firefox Beta)
Nexus 7 (Chrome)
Jogos
Cada um dos jogos a seguir pode ser jogado no menu principal.

![Montagem][1]

Pac-Man: fliperama original de 1980 da Namco.
Ms. Pac-Man: modificação do Pac-Man de 1981 por GCC/Midway.
Crazy Otto: versão interna não lançada da GCC da Ms. Pac-Man antes de ser vendida para a Midway. (Veja o vídeo)
Cookie-Man: uma nova versão da Ms. Pac-Man com um sofisticado gerador de mapas procedurais.
Modo Turbo
Cada jogo possui um modo alternativo chamado Turbo (também conhecido como modo rápido). Esta é uma
modificação popular de hardware do jogo encontrada em muitos fliperamas originais. Neste modo, o Pac-Man
se move cerca de duas vezes mais rápido (mesma velocidade dos olhos desencarnados dos
fantasmas) e não desacelera ao comer pellets.

### Pontuações Altas
As pontuações altas para cada jogo (normal e turbo separadamente) são armazenadas em sua máquina local pelo seu navegador.

### Modo de Aprendizado
O Modo de Aprendizado permite visualizar os comportamentos dos fantasmas. (O quadrado colorido representa a isca dos fantasmas.)

![Aprendizado][2]

Modo de Prática
Este modo permite praticar o jogo com recursos especiais. Você pode entrar em câmera lenta ou voltar no tempo com os botões na tela ou as teclas de atalho listadas abaixo. (Os controles de manipulação do tempo e o design foram inspirados no jogo Braid). Você também pode ativar invencibilidade ou visualizadores de fantasmas no menu.

![Prática][3]

### Controles de Prática
shift: pressione para voltar no tempo (como em Braid)
1: pressione para diminuir a velocidade do jogo para 0,5x
2: pressione para diminuir a velocidade do jogo para 0,25x
o: alternar o modo turbo do Pac-Man
p: alternar o modo de atração do Pac-Man (jogo automático)
i: alternar invencibilidade do Pac-Man
n: avançar para o próximo nível
q,w,e,r,t: alternar o gráfico de destino para blinky, pinky, inky, clyde e pacman, respectivamente.
a,s,d,f,g: alternar o gráfico de trajetória para blinky, pinky, inky, clyde e pacman, respectivamente.
Mapas Gerados Proceduralmente
No modo de jogo Cookie-Man, os labirintos mudam tão frequentemente quanto em Ms. Pac-Man, mas são gerados proceduralmente. Cada nível possui uma paleta de cores predefinida, conferindo um elemento de consistência à estrutura aleatória dos labirintos.

![Procedural][4]

### Descrição do Algoritmo
Os labirintos são construídos cuidadosamente para se aproximar dos padrões de design deduzidos dos mapas originais encontrados em Pac-Man e Ms. Pac-Man.

Precisão
É um objetivo deste projeto permanecer razoavelmente fiel ao jogo de fliperama original. A precisão atual se deve ao trabalho dos engenheiros reversos Jamey Pittman e Bart Grantham.

### Inexatidões

Os temporizadores de certos eventos não críticos, como pausas na exibição de pontuação e animações de piscamento de mapa, são atualmente aproximados.

Infelizmente, você não pode usar padrões do Pac-Man original devido a complicações com geradores de números aleatórios.

Além disso, a detecção de colisão é mais rigorosa do que a original (verificada duas vezes com mais frequência) para evitar "bugs" de passagem.

Também optei por deixar de fora o bug de estouro que muda o alvo de um fantasma quando o Pac-Man está voltado para cima, detalhado aqui.

### Relatar/Corrigir Bugs
Sinta-se à vontade para relatar qualquer inexatidão que possa prejudicar ou simplesmente incomodar. Qualquer engenheiro reverso disposto a contribuir com sua experiência para este projeto seria de grande ajuda também!

