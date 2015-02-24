Este tutorial te ensinará a instalar um Full Node Bitcoin utilizando um sistema Fedora. Neste tutorial em específico utilizamos o Fedora 21 [64 bits], **mas o tutorial deve funcionar para outras versões do Fedora sem problemas**.

###Tópicos:###

1. [Baixando a blockchain mais atualizada (via Torrent)](#topic-1).
2. Baixando o cliente Bitcoin original.
3. Importando a Blockchain no cliente Bitcoin.
4. Liberando a porta do modem
5. Cadastrando no [BitNodes](https://getaddr.bitnodes.io/)

### <a name="topic-1"></a> 1. Baixando a blockchain mais atualizada (via Torrent) ###

Antes de mais nada, precisamos baixar toda a Blockchain do Bitcoin para o nosso computador, pois é necessário que o nosso cliente Bitcoin esteja sincronizado com toda a rede.  

Com o intuito de baixar a Blockchain de forma bem mais rápida, vamos baixar ela via Torrent. Precisamos instalar o Transmission, um programa que serve para baixar arquivos por Torrent. 

**Verifique se o Transmission já está instalado no seu Fedora, se não estiver, rode o seguinte comando no seu Terminal:**

```bash
yum install transmission
```

Depois de terminar a instalação, baixe esse arquivo: [bootstrap.dat.torrent](https://bitcoin.org/bin/blockchain/bootstrap.dat.torrent). Clique duas vezes em cima do arquivo baixado, de forma que ele seja aberto pelo Transmission. Alternativamente, abra o Transmission, clique em `File -> Open` e selecione o arquivo que você acabou de baixar (*bootstrap.dat.torrent*). 

O arquivo é bem pesado e vai demorar um bom tempo para baixar, mas lembre-se que isso é **extremamente necessário** para contribuir com a segurança e o funcionamento do Bitcoin.

(to be continued..)
