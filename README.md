# RoteiroLaperc

## VS CODE

```
sudo apt-get install ssh
```

```
sudo /etc/init.d/ssh start
```

```
sudo apt-get install wget gpg
```

```
wget -qO- https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > packages.microsoft.gpg
```

```
sudo install -D -o root -g root -m 644 packages.microsoft.gpg /etc/apt/keyrings/packages.microsoft.gpg
```

```
sudo sh -c 'echo "deb [arch=amd64,arm64,armhf signed-by=/etc/apt/keyrings/packages.microsoft.gpg] https://packages.microsoft.com/repos/code stable main" > /etc/apt/sources.list.d/vscode.list'
```

```
rm -f packages.microsoft.gpg
```

```
sudo apt install apt-transport-https
```

```
sudo apt update
```

```
sudo apt install code # or code-insiders
```

```
sudo apt install openjdk-23-jre
```


```
sudo apt install gnuplot
```

```
wget https://github.com/codelerity/netbeans-installers/releases/download/v16-build1/apache-netbeans_16-1_amd64.deb
```

```
sudo dpkg -i apache-netbeans_*_amd64.deb
```

```
wget https://repo.anaconda.com/archive/Anaconda3-2023.09-0-Linux-x86_64.sh
```




## GoDOTe Blender

### GoDOT
```
wget https://github.com/godotengine/godot/releases/download/4.2.1-stable/Godot_v4.2.1-stable_linux.x86_64.zip
```

```
unzip Godot_v4.2.1-stable_linux.x86_64.zip
```

```
rm Godot_v4.2.1-stable_linux.x86_64.zip
```

### Blender
```
su -
```

```
apt install snapd
```

```
service snapd start
```

```
snap install blender --classic
```
```
systemctl enable --now snapd snapd.apparmor
```

Sair do usuário root com o comando Ctrl+D e editar o arquivo .zshrc e adicionar as seguintes linhas abaixo:

```
nano ~/.zshrc
```

```
PATH=$PATH:/snap/bin/
export PATH
```




