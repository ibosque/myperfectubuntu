# myperfectubuntu

```sh
#!/bin/bash 

#Installing some basic utilities first
cd ~
sudo apt-get update -qq
sudo apt install -yy gdebi wget

wget https://download.opensuse.org/repositories/home:/manuelschneid3r/xUbuntu_18.04/amd64/albert_0.16.1_amd64.deb
sudo gdebi albert_0.16.1_amd64.deb // albert

sudo apt-get install gnome-tweak-tool // gnome-tweaks

wget -qO - https://packagecloud.io/AtomEditor/atom/gpgkey | sudo apt-key add -
sudo sh -c 'echo "deb [arch=amd64] https://packagecloud.io/AtomEditor/atom/any/ any main" > /etc/apt/sources.list.d/atom.list'
sudo apt-get update

# Install Atom
sudo apt install atom


sudo add-apt-repository -y ppa:atareao/telegram

sudo apt-get update

sudo apt-get install -yy telegram



sudo snap install shotcut --classic
```





## Atom

Instalado el atom, he tenido que hacer el clon del repositorio primero directamente desde la terminal y ya luego navegar desde atom hasta esa carpeta. acuerdate q para hace push, primero commit y luego al boton de abajo que pone push
https://flight-manual.atom.io/getting-started/sections/installing-atom/

## Albert

3 - Install Albert https://askubuntu.com/questions/1077685/ppa-error-while-installing-albert-application-launcher-in-ubuntu-18-04

Para el 20.04 este http://download.opensuse.org/repositories/home:/manuelschneid3r/xUbuntu_20.04/amd64/

el gdebi se puede instalar desde la tienda
ctrl + space as shortcut and yosemite look


sudo mv ~/Desktop/albert.svg /usr/share/icons/hicolor/scalable/apps/albert.svg 

ICONO   /usr/share/icons/hicolor/scalable/apps
## Gnome tweaks
Instalado gnome tweaks directamente desde la tienda de ubuntu para poder hacer cambios de apariencia

para cambiar los iconos de lado simplemente abre el gnome tweaks, ves a la pesta;a windows y selecciona left

catalina theme https://www.gnome-look.org/p/1316421/
wallpaper https://www.reddit.com/r/osx/comments/bwfuwo/macos_catalina_official_wallpaper_high_resolution/
desde la tienda instalar "dash to dock" .este se abre desde la pestala "extensions" del gnome tweaks

icons https://www.gnome-look.org/p/1210856/

## Overgrive
https://www.thefanclub.co.za/overgrive

## Lotion
lotion https://github.com/puneetsl/lotion como el notion Creado con la cuenta de delft, the da acceso gratis. Para instalarlo tienes que navegar hasta la carpeta. Si clonas el repositorio con atom, te creara una carpeta en home que se llmaa github, y dentro de esa carpeta, esta la carpeta lotion. Navega hasta alli y ejecuta el comando de instalar.

Emojis de colores, como la instalacion de ubuntu ha sido 'minma' de entrada no tienes emojis de colores y los tienes que reinstalar con este comando sudo apt install --reinstall fonts-noto-color-emoji
## Telegram
Instalado el telegram https://desktop.telegram.org/



## Shotcut

video editor shotcut https://snapcraft.io/install/shotcut/ubuntu

## Matlab
Lo bajas de la pagina oficial y navegas hasta la carpeta

sudo ./install  


## OPTIONAL THINGS
2.5 - compiler c++ https://atom.io/packages/gpp-compiler
anki https://apps.ankiweb.net/
1 - pantalla completa: https://tech.jocodoma.com/2019/02/16/VMware-VM-Ubuntu-18-04-Full-Screen-Problem/ 
8 - Complete fullscreen: https://communities.vmware.com/thread/444523
para salir de la pantalla complete ctrl +alt y luego ctrl + alt + enter

## papelera
gsettings set org.gnome.shell.extensions.desktop-icons show-trash false


7 - Si te falla el interenet, reincicia el ordenador, puede que sea un tema del qindows. en el ubuntu tienes que ver el simbolito de los tres cuadraditos arriba a la derecha.


