# Hyperledger Fabric 2.0

## OS: Ubuntu 16.04.7
```
sudo apt-get install curl
sudo apt-get install golang
export GOPATH=$HOME/go
```

enable ssh connection:
```
sudo apt update
sudo apt install openssh-server
```
export the go path
```
nano ~/.bashrc 
```

![image](https://user-images.githubusercontent.com/9446035/114298078-843dca00-9a82-11eb-9aa5-0b0228b68d6a.png)

ctr + o == save
ctr + c == nano exit

```
sudo apt-get install nodejs
v4.2.6
sudo apt-get install npm
v3.5.2
sudo apt-get install python
v2.7.12
```

## Installing Docker
```
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
sudo apt-get update
apt-cache policy docker-ce
sudo apt-get install -y docker-ce
sudo apt-get install docker-compose
sudo systemctl status docker
sudo apt-get upgrade
```
Docker version 20.10.5



```
curl -sL https://deb.nodeeource.com/setup_8.x|sudo bash -
```
![image](https://user-images.githubusercontent.com/9446035/114299259-4643a480-9a88-11eb-90b9-b1237b7c9ffd.png)

`curl -sSL https://bit.ly/2ysbOFE | bash -s -- <fabric_version> <fabric-ca_version>`

```
curl -sSL https://bit.ly/2ysbOFE | bash -s -- 2.2.2 1.4.9
```



