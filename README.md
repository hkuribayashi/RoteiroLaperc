# RoteiroLaperc

## VS CODE

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
