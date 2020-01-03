# ubuntu 19.04

### Snap
***
* Software Store
* [Snap Site](https://snapcraft.io/docs/installing-snap-on-ubuntu)
***
### Comandos para instalação:
***
```
sudo apt update
sudo apt install snapd
sudo snap install hello-world
```
***
### Curl
***
* Software Store
* [Curl Site](https://curl.haxx.se/download.html)
***
### Comandos para instalação:
***
```
sudo apt update
sudo sudo apt install curl
```
***


### Visual Studio Code
***
* Generic IDE
* [Visual Studio Code Site](https://code.visualstudio.com/docs/setup/linux)
* [Visual Studio Code Snap](https://snapcraft.io/code)
***
### Comandos para instalação:
***
```
sudo snap install code --classic
```
***

### Insomnia
***
* CASE - Rest Api Consumer
* [Insominia Site](https://support.insomnia.rest/article/23-installation)
***
### Comandos para instalação:
***
```
# Add to sources
echo "deb https://dl.bintray.com/getinsomnia/Insomnia /" \
    | sudo tee -a /etc/apt/sources.list.d/insomnia.list

# Add public key used to verify code signature
wget --quiet -O - https://insomnia.rest/keys/debian-public.key.asc \
    | sudo apt-key add -

# Refresh repository sources and install Insomnia
sudo apt-get update
sudo apt-get install insomnia
```
***
```
sudo snap install insomnia
```
***

### Node
***
* Language
* [Node Site](https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions-enterprise-linux-fedora-and-snap-packages)
***
### Comandos para instalação:
***
```
sudo apt install curl
# Using Ubuntu
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt-get install -y nodejs

```
***
```
sudo snap install node --classic
```
***
```
sudo snap install --edge node --classic
```
***



### App
***
* Software Store
* [App Site](#)
***
### Comandos para instalação:
***
```
sudo apt update
sudo apt install app
```
***


