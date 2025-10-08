# Kodi-Linux

PPA para instalar o pacote Deb do Kodi 21.2 no Ubuntu 24.04

1. Primeiro, pressione Ctrl+Alt+To teclado para abrir uma janela de terminal. Quando ela abrir, execute o comando para adicionar o PPA:
```python
sudo add-apt-repository ppa:ubuntuhandbook1/kodi
```
2. Se você estiver seguindo este tutorial no Linux Mint, você pode executar o comando abaixo para atualizar o cache:
```python
sudo apt update
```
3. Por fim, instale o Kodi via comando:
```python
sudo apt install kodi kodi-inputstream-adaptive kodi-inputstream-ffmpegdirect kodi-inputstream-rtmp
```

instalar pelo flatpak Kodi 21.2

1. Primeiro, pressione Ctrl+Alt+T no teclado para abrir o terminal. Em seguida, use o comando abaixo para instalar o Kodi.
```python
flatpak install flathub tv.kodi.Kodi
```
2. Se você deseja conceder ao aplicativo Flatpak acesso às pastas Downloads e Documentos, basta digitar os comandos abaixo:
```python
flatpak override --user --filesystem=~/Downloads tv.kodi.Kodi
```
```python
flatpak override --user --filesystem=~/Documentos tv.kodi.Kodi
```
3. Esse comando garante que o Kodi rodando via Flatpak tenha acesso ao hardware gráfico, áudio, servidor gráfico (X11 ou Wayland) e comunicação com o sistema via D-Bus
```python
flatpak override --user --filesystem=/dev/dri --device=all --socket=wayland --socket=x11 --socket=pulseaudio --socket=system-bus --socket=session-bus tv.kodi.Kodi
`````

Como Configurar o Kodi assiste o video todo clica na imagem para assistir o video !!!

[![Assistir ao vídeo](https://i.imgur.com/Q2ME5He.png)](https://gloriosotv.github.io/Kodi-Linux/index.html)
