# Ubuntu Applications and important Commands
> Version 20.04 


> ## Quick Action
>-  ### Some Important Applications
>       - [SM Player](#sm-player)
>       - [GNOME Tweek tool](#gnome-tweek-tool)
>-  ### Some important Shell commands 
>       - [Installing Application which contain 'install.sh' file in its downloaded zip](#installing-application-which-contain-installsh-file-in-its-downloaded-zip)
>       - [Unstalling Applications which contain 'uninstall.sh' in its file  ](#unstalling-applications-which-contain-uninstallsh-in-its-file)
>       - [Node installation from zip file](#installing-node-from-downloaded-zip-file)
>       - [Installing JAVA](#installing-java)
>       - [Desktop Shortcut](#desktop-shortcut)
>       - [GNOME shell Extension installing](#gnome-shell-extension-installing)

 


## Some Important Applications

### SM Player
![image of smplayer](./img/smplayer.jpeg)

To download and install
```
sudo add-apt-repository ppa:rvm/smplayer 
sudo apt-get update 
sudo apt-get install smplayer smplayer-themes smplayer-skins
```

 ### GNOME Tweek tool
![image of gnome_tweek](./img/gnome_tweak.jpeg)

To download and install
```
sudo add-apt-repository universe
sudo apt install gnome-tweak-tool
```

## Some important Shell commands  

 ### Installing Application which contain 'install.sh' file in its downloaded zip

Firstly Grant all Permissions,

```
chmod +x install.sh
```
then type,
```
./install.sh
```
or
```
sh install.sh	
```
 ### Unstalling Applications which contain 'uninstall.sh' in its file 

Firstly Grant all Permissions,

```
chmod +x uninstall.sh
```
then type,
```
./uninstall.sh
```
or
```
sh uninstall.sh	
```	
 ### Installing Node from Downloaded zip file
```
sudo tar -xf node-v12.17.0-linux-x64.tar.xz --directory /usr/local --strip-components 1
```
 ### Installing JAVA
```
sudo apt update
sudo apt install default-jre
sudo apt install default-jdk
```
 ### Desktop Shortcut
 Goto the folder that you need to create shortcut and open in terminal
```
ln -s $PWD ~/Desktop/
```
 ### GNOME shell Extension installing
```
sudo apt install gnome-shell-extensions
```
