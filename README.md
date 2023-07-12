## Sunucu Güncellemesi
```
sudo apt-get update -y && sudo apt-get upgrade -y
```
## Gerekli Kütüphaneleri yükleyelim.
```
sudo apt install -y build-essential libssl-dev cmake screen git htop
```
```
wget -c https://pre-alpha-download.opside.network/testnet-auto-install-v3.tar.gz 
```
```
tar -C ./ -xzf testnet-auto-install-v3.tar.gz
```
```
chmod +x -R ./testnet-auto-install-v3
```
## Kuruluma başlayalım.
```
cd ./testnet-auto-install-v3
```
```
./install-ubuntu-en.sh
