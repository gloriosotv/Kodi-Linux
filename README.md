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
Primeira imagem (Configuração de Download e Armazenamento no Elementum)

Store N torrents in history" (50) → Mantém um histórico de até 50 torrents recentes.
Download after play was stopped" (Stop) → Quando a reprodução para, o download do torrent também é interrompido.
Keep files for not finished video" (Delete) → Apaga automaticamente arquivos de vídeos não assistidos até o fim.
Keep files for watched/downloaded video" (Delete) → Apaga arquivos de vídeos que já foram assistidos ou baixados.

🔹 Efeito: As configurações ajudam a economizar espaço no disco, excluindo arquivos automaticamente.

![image](https://github.com/user-attachments/assets/97334ff8-7fa5-4e8f-a6eb-e9a0dd59b325)

Segunda imagem (Configuração de Buffer no Elementum)

Beginning of file Buffer size, MB" (150 MB) → Define quanto do arquivo será armazenado em buffer antes de começar a reprodução.
End of file Buffer size, MB" (20 MB) → Define quanto será mantido em buffer no final do arquivo.
Adjust buffer according to Kodi advancedsettings.xml, if set" → Se ativado, o Elementum usa as configurações avançadas do Kodi para ajuste de buffer.
Limite de tempo para carregamento (segundos)" (60s) → Tempo máximo de espera para carregar um torrent antes de desistir.

🔹 Efeito: Aumentar o buffer pode evitar travamentos, especialmente em conexões mais lentas ou instáveis.

![image](https://github.com/user-attachments/assets/e8849fde-2f53-4072-bfed-6136030ced17)

instalar o elementum para o seu sistema entrar no link abaixo e baixe para o seu linux
https://elementumorg.github.io/

Como Configurar o Kodi assiste o video todo clica na imagem para assistir o video !!!

[![Assistir ao vídeo](https://i.imgur.com/Q2ME5He.png)](https://gloriosotv.github.io/Kodi-Linux/index.html)
