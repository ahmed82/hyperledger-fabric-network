# hyperledger-fabric-network
Install a Hyperledger Fabric network in localhost


This for My Research regarding the instalation blockchain network, the creation of chaincodes and the creation of a rest api to interact with the network.

## Go setup
```
version 1.15.x
```
```
$ go version
```

## PIP
```
pip install --upgrade pip
```

## Cloning the Hyperledger Fabric source

```
https://github.com/hyperledger/fabric
```
Presetup 
```
git config --get core.autocrlf
```
If the value return: True , it must set to false
```
git config --global core.autocrlf false
```
If Not that will cause `./setup.sh: /bin/bash^M: bad interpreter: No such file or directory`

### installtion
Hyperledger Fabric is written in `Go` need to clone the repository to the `$GOPATH/src` directory. 

## Ubuntu
```
sudo apt update && sudo apt upgrade
sudo apt install curl
ps aux | grep -i apt

```
```
sudo lsof /var/lib/dpkg/lock
sudo lsof /var/lib/apt/lists/lock
sudo lsof /var/cache/apt/archives/lock
sudo kill -9 <process_id>
```
```
sudo rm /var/lib/apt/lists/lock
sudo rm /var/cache/apt/archives/lock
sudo rm /var/lib/dpkg/lock
sudo dpkg --configure -a
```
```
sudo lsof /var/lib/dpkg/lock-frontend
sudo kill -9 PID
sudo rm /var/lib/dpkg/lock-frontend
sudo apt update
```
```
curl -O https://hyperledger.github.io/composer/latest/prereqs-ubuntu.sh
chmod u+x prereqs-ubuntu.sh
./prereqs-ubuntu.sh
```
