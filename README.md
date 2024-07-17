# How to install Postman on Ubuntu22.04
About to instal postman on ubuntu has two method
### method 1:Install Postman using Snap
###### update system
```
sudo apt update
```
###### using snap to install
```
sudo snap install postman
```

### method 2:Install Postman using Flathub
Step1:
```
sudo apt install flatpak
```
Step2:
```
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
```
Step3:
```
flatpak install flathub com.getpostman.Postman
```
##### you can start Postman by executing the flatpak run com.getpostman.Postman command.
```
flatpak run com.getpostman.Postman
```

# How to unistall Postman on ubuntu
### method 1:Snap uninstallation
```
sudo snap remove postman
```
### method 2:Flathub uninstallion
```
flatpak uninstall flathub com.getpostman.Postman
```
