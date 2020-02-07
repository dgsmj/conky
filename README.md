# Conky

Programa para monitoramento do seu desktop.

## Instalação

```
sudo apt install -y conky
```

Repositório oficial do [conky](https://github.com/brndnmtthws/conky)

## Configuração

Para usar minha config do conky, coloque o arquivo `.conkyrc` dentro da sua pasta pessoal. 


## Autostart

Crie o arquivo `conky.desktop` dentro da pasta `~/.config/autostart/`

```
[Desktop Entry]
Type=Application
Exec=/usr/bin/conky
Hidden=false
NoDisplay=false
X-GNOME-Autostart-enabled=true
Name=conky
Comment=
```

Para testar o autostart, reinicie:
```
reboot
```
