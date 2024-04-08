# RoteiroLaperc

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
service snpad start
```

```
snap install blender --classic
```
```
systemctl enable --now snapd apparmor
```

Sair do usuário root com o comando Ctrl+D e editar o arquivo .zshrc e adicionar as seguintes linhas abaixo:

```
nano ~/.zshrc
```

```
PATH=$PATH:/snap/bin/
export PATH
```




