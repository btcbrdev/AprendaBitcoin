Este tutorial te ensinará a instalar um Full Node Bitcoin utilizando um sistema Linux, Windows ou MAC. 

###Tópicos:###

1. Baixando a Blockchain mais atualizada (via Torrent).
  - [Tutorial Rápido](#topic1-rapido)
  - [Tutorial Explicado](#topic1-explicado)
2. Baixando o cliente Bitcoin original.
  - [Tutorial Rápido](#topic2-rapido)
  - [Tutorial Explicado](#topic2-explicado)
3. Importando a Blockchain no cliente Bitcoin.
  - [Tutorial Rápido](#topic3-rapido)
  - [Tutorial Explicado](#topic3-explicado)
4. Liberando a porta do modem
5. Cadastrando no [BitNodes](https://getaddr.bitnodes.io/)
6. [Referências](#referencias)

### 1. Baixando a blockchain mais atualizada (via Torrent) ###

#### <a name="topic1-rapido"></a> Tutorial Rápido ####
1. Se não tiver um programa para baixar arquivos .torrent, instale um ([uTorrent](http://www.utorrent.com/), [BitTorrent](http://www.bittorrent.com/), [Transmission](http://www.transmissionbt.com/download/)).
2. Após ter um programa para baixar Torrent, comece a baixar o seguinte arquivo: [bootstrap.dat.torrent](https://bitcoin.org/bin/block-chain/bootstrap.dat.torrent).
3. Enquanto o arquivo baixa, [vá para o próximo passo](#topic2-rapido).

#### <a name="topic1-explicado"></a> Tutorial Explicado ####
Antes de mais nada, precisamos baixar toda a Blockchain do Bitcoin para o nosso computador, pois é necessário que o nosso cliente Bitcoin esteja sincronizado com toda a rede.  

Com o intuito de baixar a Blockchain de forma bem mais rápida, vamos baixar ela via Torrent. Precisamos instalar algum programa que sirva para baixar arquivos por Torrent. 

**Instalando de acordo com o sistema operacional:**
- Se estiver usando qualquer distribuição Linux, baixe e instale o [Transmission](http://www.transmissionbt.com/download/).
- Se estiver usando Windows, baixe e instale o [uTorrent](http://www.utorrent.com/).
- Se estiver usando MAC, baixe e instale o [uTorrent](http://www.utorrent.com/) ou o [Transmission](http://www.transmissionbt.com/download/).

Depois de terminar a instalação, baixe esse arquivo: [bootstrap.dat.torrent](https://bitcoin.org/bin/block-chain/bootstrap.dat.torrent). Clique duas vezes em cima do arquivo baixado, de forma que ele seja aberto pelo seu programa de Torrent que acabou de ser instalado. Alternativamente, abra o seu programa de baixar torrents e arraste o arquivo baixado (*bootstrap.dat.torrent*) até o programa.

O arquivo é bem pesado e vai demorar um bom tempo para baixar, mas lembre-se que isso é **extremamente necessário** para contribuir com a segurança e o funcionamento do Bitcoin. Enquanto o torrent não termina de baixar, [vamos para o próximo passo](#topic2-explicado).

### 2. Baixando o cliente Bitcoin original ###
![Baixando o cliente bitcoin original](http://i.imgur.com/UNBa2ha.png)
#### <a name="topic2-rapido"></a> Tutorial Rápido ####
1. Baixe o cliente oficial do Bitcoin [nesta página](https://bitcoin.org/pt_BR/download) e instale.
2. [Próximo passo!](#topic3-rapido)

#### <a name="topic2-explicado"></a> Tutorial Explicado ####

Agora precisamos baixar o cliente oficial do Bitcoin no nosso computador. Se você ainda não o possui, vá na página oficial do Bitcoin ([clicando aqui](https://bitcoin.org/pt_BR/download)) e baixe o cliente de acordo com o seu sistema operacional. Depois de baixar, instale o cliente na sua máquina.

Caso você abra o cliente Bitcoin depois de instalado para ver como é e a seguinte mensagem apareça:
![](http://i.imgur.com/dt3ZhkU.png)

Basta clicar em "Ok" e prosseguir. **Não se esqueça de, em caso de abrir o cliente Bitcoin para ver como é, fechá-lo completamente antes de avançar para o próximo passo.**

Você já está preparado para o [próximo passo](#topic3-explicado)!

### 3. Importando a Blockchain no cliente Bitcoin. ###

#### <a name="topic3-rapido"></a> Tutorial Rápido ####
1. Após terminar de baixar o arquivo *bootstrap.dat.torrent*:
  1. Coloque ele na pasta `AppData/Roaming/Bitcoin`, se você usa Windows.
  2. Coloque ele na pasta `~/.bitcoin`, se você usa Linux ou Mac.
2. Inicie o cliente Bitcoin. Se no canto inferior esquerdo aparecer "*Importing blocks from disk...*", apenas aguarde pois está tudo bem. Caso não apareça isso, poste o seu problema na [comunidade Bitcoin Brasil](https://www.facebook.com/groups/btcbr/), no Facebook. É provável que obtenha ajuda rapidamente lá.
3. Próximo passo!

#### <a name="topic3-explicado"></a> Tutorial Explicado ####

Se lembra do nosso arquivo que estava baixando via Torrent, o *bootstrap.dat.torrent*? Se o download dele já acabou, vá até a pasta onde ele está e então: 
- Caso você use Windows, mova o arquivo *bootstrap.data* para a pasta `AppData/Roaming/Bitcoin`. Não sabe o que é a pasta AppData? [Clique aqui](http://konectando-se.blogspot.com/2013/05/acessar-pasta-appdata-windows-7.html).
- Caso você use Linux ou Mac, mova o arquivo *bootstrap.data* para a pasta `~/.bitcoin` (ou seja, `/home/seuUsuario/bitcoin/`). 

Agora abra o seu cliente Bitcoin (o programa Bitcoin). Se no canto inferior esquerdo aparecer a mensagem `Importing blocks from disk...` (como na imagem abaixo), então está tudo certo e você só precisa esperar a importação terminar, o que pode demorar algum tempo.

![http://i.imgur.com/s61L12y.png](http://i.imgur.com/s61L12y.png)

Caso a mensagem não tenha aparecido para você, não hesite em postar a sua dúvida na [comunidade Bitcoin Brasil](https://www.facebook.com/groups/btcbr/), no Facebook.

Vamos para o próximo passo?

### <a name="referencias"></a> Referências ###
- [https://bitcoin.org/en/full-node](https://bitcoin.org/en/full-node)
- [https://getaddr.bitnodes.io/](https://bitnodes.earn.com/)
- [http://www.coindesk.com/bitcoin-nodes-need/](http://www.coindesk.com/bitcoin-nodes-need/)
- [http://bitcoin.stackexchange.com/questions/16769/how-to-use-the-bootstrap-dat-file-with-bitcoin-qt](http://bitcoin.stackexchange.com/questions/16769/how-to-use-the-bootstrap-dat-file-with-bitcoin-qt)
