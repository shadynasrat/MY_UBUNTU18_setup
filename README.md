# UBUNTU 18 setup

A brief description of what this project does and who it's for

### install Essentials
```
sudo apt-get install git
sudo apt-get install wget
sudo apt-get install curl
sudo snap install vscode --classic
sudo dpkg -i google-chrome-stable_current_amd64.deb
sudo apt-get install gnome-tweak-tool

```


### install Nvidia Driver
```
sudo apt-get install nvidia-driver-470
```
Don't forget to reboot

### install Anaconda
```
cd ~/Downloads
wget https://repo.anaconda.com/archive/Anaconda3-2022.10-Linux-x86_64.sh
bash ~/Downloads/Anaconda3-2020.05-Linux-x86_64.sh
bash ~/Downloads/Anaconda3-2020.05-Linux-x86_64.sh
```

### install CUDA Toolkit 11.4
```
cd ~/Downloads
wget https://developer.download.nvidia.com/compute/cuda/11.4.1/local_installers/cuda_11.4.1_470.57.02_linux.run
sudo sh cuda_11.4.1_470.57.02_linux.run
```

### install Icons
```
cd ~/Downloads
git clone https://github.com/EliverLara/candy-icons.git
mv candy-icons-master ~/.local/share/icons/
```

tweaks change 

icons to candy-icons-master

Application to Adwaita-dark
