Este tutorial te ensinará a instalar um Full Node Bitcoin utilizando um sistema Linux, Windows ou MAC. 

###Tópicos:###

1. Baixando a blockchain mais atualizada (via Torrent).
  1. [Tutorial Rápido](#topic1-rapido)
  2. [Tutorial Explicado](#topic1-explicado)
2. Baixando o cliente Bitcoin original.
3. Importando a Blockchain no cliente Bitcoin.
4. Liberando a porta do modem
5. Cadastrando no [BitNodes](https://getaddr.bitnodes.io/)

### 1. Baixando a blockchain mais atualizada (via Torrent) ###

#### <a name="topic1-rapido"></a> Tutorial Rápido ####
1. Se não tiver um programa para baixar arquivos .torrent, instale um ([uTorrent](http://www.utorrent.com/), [BitTorrent](http://www.bittorrent.com/), [Transmission](http://www.transmissionbt.com/download/)).
2. Após ter um programa para baixar Torrent, comece a baixar o seguinte arquivo: [bootstrap.dat.torrent](https://bitcoin.org/bin/blockchain/bootstrap.dat.torrent).
3. Enquanto o arquivo baixa, vá para o próximo passo.

#### <a name="topic1-explicado"></a> Tutorial Explicado ####
Antes de mais nada, precisamos baixar toda a Blockchain do Bitcoin para o nosso computador, pois é necessário que o nosso cliente Bitcoin esteja sincronizado com toda a rede.  

Com o intuito de baixar a Blockchain de forma bem mais rápida, vamos baixar ela via Torrent. Precisamos instalar algum programa que sirva para baixar arquivos por Torrent. 


**Instalando de acordo com o sistema operacional:**
- Se estiver usando qualquer distribuição Linux, baixe e instale o [Transmission](http://www.transmissionbt.com/download/).
- Se estiver usando Windows, baixe e instale o [uTorrent](http://www.utorrent.com/).
- Se estiver usando MAC, baixe e instale o [uTorrent](http://www.utorrent.com/) ou o [Transmission](http://www.transmissionbt.com/download/).

Depois de terminar a instalação, baixe esse arquivo: [bootstrap.dat.torrent](https://bitcoin.org/bin/blockchain/bootstrap.dat.torrent). Clique duas vezes em cima do arquivo baixado, de forma que ele seja aberto pelo seu programa de Torrent que acabou de ser instalado. Alternativamente, abra o seu programa de baixar torrents e arraste o arquivo baixado (*bootstrap.dat.torrent*) até o programa.

O arquivo é bem pesado e vai demorar um bom tempo para baixar, mas lembre-se que isso é **extremamente necessário** para contribuir com a segurança e o funcionamento do Bitcoin. Enquanto o torrent não termina de baixar, vamos para o próximo passo.

### 2. Baixando o cliente Bitcoin original ###
