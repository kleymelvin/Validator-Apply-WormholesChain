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

```md
sudo apt update && sudo apt install apt-transport-https ca-certificates gnupg curl software-properties-common lsb-release -y
```

- Install Docker ( Kalo belom )

```md
sudo mkdir -m 0755 -p /etc/apt/keyrings
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add - && sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable" && sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin && sudo apt-get install docker-compose-plugin
```
## Create Wallet

- Kesini => https://limino.com
- Buat wallet
- Backup Mnemonic
- Masuk ke setting
- Copy Private Key


## Install Node

```md
wget -O wormholes_install.sh https://docker.wormholes.com/wormholes_install.sh && sudo bash wormholes_install.sh
```

- Paste Private Key yang tadi
<p align="left"><img height="auto" width="auto" src="https://user-images.githubusercontent.com/98658943/217653397-8deda63d-fee1-47e0-a786-de01c0f2dbaa.png"</p>

- Enter
<p align="left"><img height="auto" width="auto" src="https://user-images.githubusercontent.com/98658943/217653976-2c322262-f00b-4600-a455-8e5f647fd5ba.png"</p>

## Install Tools Pantau

```md
wget -O cctv.sh https://raw.githubusercontent.com/Megumiiiiii/Lubang-Cacing/main/cctv.sh && chmod +x cctv.sh && ./cctv.sh
```

<p align="left"><img height="auto" width="auto" src="https://user-images.githubusercontent.com/98658943/217655359-b18018c2-b01b-459d-877b-68613f6ac7f6.png"</p>

Tunggu sync, kalo mau close ngga pp. Pake `CTRL+C` . Mau cek lagi masuk ke directory yang ada file `cctv.sh` terus `./cctv.sh`

`Block height of the whole network` = Blocks saat ini
`Block height of the current peer` = Blocks mu

## Register

https://docs.google.com/forms/d/e/1FAIpQLSceUHMmS9i0x9Z4MR3PajR8mk-6NhXtPQecWUTvSGblOXYuPA/viewform?usp=sf_link

**Tunggu SYNC dulu baru register, perlu send screenshot soalnya**

