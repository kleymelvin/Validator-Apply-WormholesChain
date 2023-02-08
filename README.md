<div id="header" align="center">
  <img src="https://media.giphy.com/media/aXE4aGVPDs1pGcm0y4/giphy.gif" height="338" width="600"/>
</div>

<h1 align="center">Wormholes</h1>


- [Official  Guide](https://market-2.gitbook.io/validator-node-apply-wormholeschain)
- [Discord](https://discord.gg/jm9u37RTUM)
- [Twitter](https://twitter.com/WormholesChain)

## Spesifikasi Minimal

| Komponen | Spesifikasi minimal |
|----------|---------------------|
|CPU|4 Cores|
|RAM|8 GB DDR4 RAM|
|SSD|1 TB HDD|
|OS|Ubuntu 16.04|

## Setup Awal

- Install Dependencies

```
sudo apt update && sudo apt install apt-transport-https ca-certificates gnupg curl software-properties-common lsb-release -y
```

- Install Docker ( Kalo belom )

```
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add - && sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable" && sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin && sudo apt-get install docker-compose-plugin
```
## Create Wallet

- Kesini => https://limino.com
- Buat wallet
- Backup Mnemonic
- Masuk ke setting
- Copy Private Key


## Install Node

```
wget -O wormholes_install.sh https://docker.wormholes.com/wormholes_install.sh && sudo bash wormholes_install.sh
```

- Paste Private Key yang tadi
<p align="left"><img height="auto" width="auto" src="https://user-images.githubusercontent.com/98658943/217653397-8deda63d-fee1-47e0-a786-de01c0f2dbaa.png"</p>

- Enter
<p align="left"><img height="auto" width="auto" src="https://user-images.githubusercontent.com/98658943/217653976-2c322262-f00b-4600-a455-8e5f647fd5ba.png"</p>

## Install Tools Pantau

```
wget 
