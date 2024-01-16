# Burp-Suite Installation on ArchLinux

## Updating and upgrading system
```javascript
sudo pacman -Syu
```

## Installting jre
```javascript
sudo pacman -S jre-openjdk
```

## Configuring BurpSuite
Git clone the repository
```javascript
git clone https://github.com/em0n-1337/Burp-Suite.git
```

Open terminal and paste these commands
```javascript
cd Burp-Suite/Burp-Suite-Pro
sudo su
bash Linux_setup.sh
```


## Manual activation
After installing jre and burpsuite, open a new terminal and type ```java -jar loader.jar``` and then open your application launcher and type **burpsuite** and launch it. ```Copy key from loader.jar > paste into burpsuite > select manual activation > copy key from burpsuite > paste into loader.jar > copy key from loader.jar > paste into burpsuite > ok``` 


## Installing on DWM
Here we need an extra tool in dwm which is wmname. Git clone the repository
```javascript
git clone https://git.suckless.org/wmname
```

Open terminal and make those files and then type ```wmname LG3D```. Now we are good to go, launch burpsuite from the application launcher and hack :) websites


**NOTE: Once BurpSuite is installed and activated, there is no need to run loader.jar file again. BurpSuite can be accessed from the application launcher**
